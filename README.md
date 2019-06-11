# Lut3D
3D Lookup Table filter Port From FFmpeg

# before
![image](https://github.com/cpuimage/Lut3D/blob/master/example/example.jpg)

# after
![image](https://github.com/cpuimage/Lut3D/blob/master/example/out.jpg)

# 命令行参数:

lut3d 3d预设文件  图片路径

例如: lut3d ../god.cube ../sample.jpg

用cmake即可进行编译示例代码，详情见CMakeLists.txt。

# 3d lut 的实现算法

[Nearest_interpolation](https://en.wikipedia.org/wiki/Nearest-neighbor_interpolation)

[Trilinear_interpolation](https://en.wikipedia.org/wiki/Trilinear_interpolation)

[Tetrahedral interpolation](https://www.filmlight.ltd.uk/pdf/whitepapers/FL-TL-TN-0057-SoftwareLib.pdf)

Trilinear_interpolation 是用得最广泛的一种
