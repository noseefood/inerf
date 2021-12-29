#个人Debug
##依赖库的问题
###opencv的安装
requirements里面需要修改以下部分，opencv不用指定版本，但opencv-contrib-python必须指定>4.4.0以上的版本，否则会出现SIFT无法使用的错误
>opencv-contrib-python ==4.4.0.44>

然后不知道为什么在本地conda的虚拟环境中会出现cuda版本的问题，建议使用colab运行...