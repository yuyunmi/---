# 尘白禁区-研析小助手

# 项目介绍
本项目式基于开源OCR和DFS搜索实现的尘白禁区信源研析自动化识别项目
可以实现研析的一键化自动给出方案
（目前ocr的识别精度不是很高,~~但是已经够用了~~，后面可能会改进，咕咕咕~）
 
# 环境依赖
opencv-python
cnocr
numpy
onnxruntime
pywin32
 
# 目录结构描述
    ├── ReadMe.md           // 帮助文档
    
    ├── snow.py             // 程序主函数，界面设计
    
    ├── get_frame.py        // 获取游戏窗口截图

    ├── cut.py              // 对获取的截图进行切割
    
    ├── ocr.py              // 对切割的截图进行识别碎片数目

    ├── get_matrix.py       // 对游戏棋盘的识别

    ├── snow_dfs.py         // DFS深度搜索实现
    
    └── cache.png           // 临时存放的游戏截图
 
# 使用说明
 
 ![image](https://github.com/yuyunmi/cbjq-yx/assets/120000886/611a0974-ac0f-4c48-83b1-0dfcf94620e4)

 
# 版本内容更新

研析小助手 v1.0.0:  

  1.可视化界面实现
  2.打包版本已发布

鸣谢：[cnocr](https://github.com/shiwen1234/cnocr)
 
