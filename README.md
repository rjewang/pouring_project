# pouring_project



* To generate the video based on the image screenshot 
  *   based on `img`: `ffmpeg -i img_%04d.png -vcodec libx264 -pix_fmt yuv420p MIX_cube_and_sphere_in_bowl.mp4 ` (for original image)
  *   based on `id`: `ffmpeg -i id_%04d.png -vcodec libx264 -pix_fmt yuv420p MIX_cube_and_sphere_in_bowl_id.mp4 ` (for segmented version)
  *   the final `.mp4` is the filename wanted.
