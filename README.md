使用Jetbot机器人识别交通信号灯

快速开始：

使用 **JupyterLab** 打开 **adjust**.ipynb 和 **main**.ipynb

优先运行 **adjust**.ipynb 根据环境光影，使用滑块实时调整HSV，以达到最优检测效果

![Snipaste_2025-04-17_17-25-41](https://github.com/user-attachments/assets/34bcf36f-ca32-4bc7-a59c-d8331af8f0ea)


左为原始输入图像，中为掩膜处理后的图像，右为作为识别的图像

理想效果为，中间掩膜图像只有待检测部分为白色，其余部分为黑色阴影，右结果图像仅待检测部分为待检测的颜色，如下图所示：

![Snipaste_2025-04-17_17-28-27](https://github.com/user-attachments/assets/01f8f96a-bdf1-45fb-89ae-b6c016188f68)


调整完成后运行 **main**.ipynb 调用摄像头进行实时检测并在检测到之后进行运动逻辑的实现
