使用方式
1、使用前配置encoder_ra.cfg文件，InputFile：YUV420格式视频文件；SourceWidth：视频宽；SourceHeight：视频高
2、./miniAVS3 -f encoder_ra.cfg开始运行编码器，编码完成后在run目录生成test.avs
3、使用uavs3d解码run目录下的test.avs文件，生成test.yuv视频文件
4、使用yuv播放器播放test.yuv文件查看效果