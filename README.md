# qiantuchengxiang
开发了一个python应用程序，可以将目标对象图片分割成指定数量的图片（像素），然后通过聚类分析算法得到每张图片（像素）的主色调并与图片库中的图片比对，将图片库中的最接近像素的图片替换原始像素，最终拼接回完整的目标对象图片。此程序最终得到的图像具有很好的视觉效果。

1. 利用K-Means聚类分析算法得到图片的主色调。
2. 图像操作，如resize，图像分割，重叠，颜色矩阵运算和颜色数据分析。
3. 将RGB颜色值转换为CIE L*ab颜色值。
4. 寻找最适合的判定颜色差异的标准并用算法实现，这个项目使用的是deltaE值判断颜色差异.
5. 编写了简单的UI界面。
