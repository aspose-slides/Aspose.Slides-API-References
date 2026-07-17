---
title: Graphics
second_title: Aspose.Slides for C++ API 参考
description: "表示一个绘图表面。该类的对象应仅通过 System::MakeObject() 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 System::SmartPtr 指针，并使用该指针将其作为参数传递给函数。"
type: docs
weight: 118
url: /zh/system.drawing/graphics/
---
## Graphics 类


表示一个绘图表面。该类的对象应仅通过 [System::MakeObject()](../../system/makeobject/) 函数分配。切勿在栈上或使用 operator new 创建此类型的实例，因为这会导致运行时错误和/或断言故障。始终将此类包装为 [System::SmartPtr](../../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。

```cpp
class Graphics : public virtual System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [AddMetafileComment](./addmetafilecomment/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | NOT IMPLEMENTED. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsContainer](../../system.drawing.drawing2d/graphicscontainer/)\> [BeginContainer](./begincontainer/)() | 保存当前对象状态的容器，打开并使用一个新容器，然后返回已保存的容器。 |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsContainer](../../system.drawing.drawing2d/graphicscontainer/)\> [BeginContainer](./begincontainer/)([Rectangle](../rectangle/), [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/)) | 保存当前对象状态的容器，打开并使用一个新容器，然后返回已保存的容器。 |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsContainer](../../system.drawing.drawing2d/graphicscontainer/)\> [BeginContainer](./begincontainer/)([RectangleF](../rectanglef/), [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/)) | 保存当前对象状态的容器，打开并使用一个新容器，然后返回已保存的容器。 |
| void [Clear](./clear/)([Color](../color/)) | 清除当前对象所表示的绘图表面并使用指定颜色填充。 |
| void [CopyFromScreen](./copyfromscreen/)([Point](../point/), [Point](../point/), [Size](../size/), [CopyPixelOperation](../copypixeloperation/)) | NOT IMPLEMENTED. |
| void [CopyFromScreen](./copyfromscreen/)(**int32_t**, **int32_t**, **int32_t**, **int32_t**, [Size](../size/), [CopyPixelOperation](../copypixeloperation/)) | NOT IMPLEMENTED. |
| void [Dispose](./dispose/)() | 释放当前对象获取的所有操作系统资源。 |
| void [DrawArc](./drawarc/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **int32_t**, **int32_t**, **int32_t**, **int32_t**, **int32_t**, **int32_t**) | 在当前对象所表示的表面上使用指定的笔绘制指定的弧线。 |
| void [DrawArc](./drawarc/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**, **float**, **float**) | 在当前对象所表示的表面上使用指定的笔绘制指定的弧线。 |
| void [DrawArc](./drawarc/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Rectangle](../rectangle/), **float**, **float**) | 在当前对象所表示的表面上使用指定的笔绘制指定的弧线。 |
| void [DrawArc](./drawarc/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [RectangleF](../rectanglef/), **float**, **float**) | 在当前对象所表示的表面上使用指定的笔绘制指定的弧线。 |
| void [DrawBezier](./drawbezier/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [Point](../point/)\&, const [Point](../point/)\&, const [Point](../point/)\&, const [Point](../point/)\&) | NOT IMPLEMENTED. |
| void [DrawBezier](./drawbezier/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [PointF](../pointf/)\&, const [PointF](../pointf/)\&, const [PointF](../pointf/)\&, const [PointF](../pointf/)\&) | NOT IMPLEMENTED. |
| void [DrawBezier](./drawbezier/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | NOT IMPLEMENTED. |
| void [DrawBeziers](./drawbeziers/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&) | 使用指定的笔绘制一系列贝塞尔样条曲线。 |
| void [DrawBeziers](./drawbeziers/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&) | 使用指定的笔绘制一系列贝塞尔样条曲线。 |
| void [DrawClosedCurve](./drawclosedcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, **float**, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/)) | 使用指定的笔绘制闭合样条曲线。 |
| void [DrawClosedCurve](./drawclosedcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, **float**, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/)) | 使用指定的笔绘制闭合样条曲线。 |
| void [DrawCurve](./drawcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, **float**) | 使用指定的笔绘制样条曲线。 |
| void [DrawCurve](./drawcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, **float**) | 使用指定的笔绘制样条曲线。 |
| void [DrawCurve](./drawcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, **int32_t**, **int32_t**, **float**) | 使用指定的笔绘制样条曲线。 |
| void [DrawCurve](./drawcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, **int32_t**, **int32_t**, **float**) | 使用指定的笔绘制样条曲线。 |
| void [DrawEllipse](./drawellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Rectangle](../rectangle/)) | 在当前对象所表示的表面上使用指定的笔绘制指定的椭圆。 |
| void [DrawEllipse](./drawellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [RectangleF](../rectanglef/)) | 在当前对象所表示的表面上使用指定的笔绘制指定的椭圆。 |
| void [DrawEllipse](./drawellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, int, int, int, int) | 在当前对象所表示的表面上使用指定的笔绘制指定的椭圆。 |
| void [DrawEllipse](./drawellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**) | 在当前对象所表示的表面上使用指定的笔绘制指定的椭圆。 |
| void [DrawIcon](./drawicon/)(const [SharedPtr](../../system/sharedptr/)\<[Icon](../icon/)\>\&, [Rectangle](../rectangle/)) | NOT IMPLEMENTED. |
| void [DrawIcon](./drawicon/)(const [SharedPtr](../../system/sharedptr/)\<[Icon](../icon/)\>\&, **int32_t**, **int32_t**) | NOT IMPLEMENTED. |
| void [DrawIconUnstretched](./drawiconunstretched/)(const [SharedPtr](../../system/sharedptr/)\<[Icon](../icon/)\>\&, [Rectangle](../rectangle/)) | NOT IMPLEMENTED. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [System::ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&) | NOT IMPLEMENTED. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [System::ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, const [RectangleF](../rectanglef/)\&, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | 在指定位置绘制指定图像的指定区域。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const System::Details::ArrayView\<[PointF](../pointf/)\>\&, const [RectangleF](../rectanglef/)\&, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | 在指定位置绘制指定图像的指定区域。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const System::Details::StackArray\<[PointF](../pointf/), N\>\&, const [RectangleF](../rectanglef/)\&, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | 在指定位置绘制指定图像的指定区域。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | 在指定位置绘制指定图像。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, **float**, **float**) | 在指定位置绘制指定图像。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Point](../point/)) | 在指定位置绘制指定图像。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [PointF](../pointf/)) | 在指定位置绘制指定图像。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int, int, int) | 将指定图像绘制到指定矩形。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, **float**, **float**, **float**, **float**) | 将指定图像绘制到指定矩形。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [RectangleF](../rectanglef/), [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/)) | 在指定位置绘制指定图像的指定区域。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/)) | 在指定位置绘制指定图像的指定区域。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int, [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/)) | 在指定位置绘制指定图像的指定区域。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Rectangle](../rectangle/)\&) | 在指定位置绘制指定图像。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [RectangleF](../rectanglef/)\&) | 在指定位置绘制指定图像。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), int, int, int, int, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | 将指定图像的指定区域绘制到指定矩形。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), **float**, **float**, **float**, **float**, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | 将指定图像的指定区域绘制到指定矩形。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), int, int, int, int, [GraphicsUnit](../graphicsunit/)) | 将指定图像的指定区域绘制到指定矩形。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), **float**, **float**, **float**, **float**, [GraphicsUnit](../graphicsunit/)) | 将指定图像的指定区域绘制到指定矩形。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), int, int, int, int, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&, [Graphics::DrawImageAbort](./drawimageabort/)) | NOT IMPLEMENTED. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), **float**, **float**, **float**, **float**, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&, [Graphics::DrawImageAbort](./drawimageabort/)) | NOT IMPLEMENTED. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), int, int, int, int, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&, [Graphics::DrawImageAbort](./drawimageabort/), IntPtr) | NOT IMPLEMENTED. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), **float**, **float**, **float**, **float**, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&, [Graphics::DrawImageAbort](./drawimageabort/), IntPtr) | NOT IMPLEMENTED. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/)) | NOT IMPLEMENTED. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&) | NOT IMPLEMENTED. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/)) | NOT IMPLEMENTED. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/), const [SharedPtr](../../system/sharedptr/)\<[Imaging::ImageAttributes](../../system.drawing.imaging/imageattributes/)\>\&) | 在指定位置绘制指定图像的指定区域。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, **float**, **float**, [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/)) | 在指定位置绘制指定图像的指定区域。 |
| void [DrawImageUnscaled](./drawimageunscaled/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | 使用原始物理尺寸在指定位置绘制指定图像。 |
| void [DrawImageUnscaled](./drawimageunscaled/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int, int, int) | 使用原始物理尺寸在指定位置绘制指定图像。 |
| void [DrawImageUnscaled](./drawimageunscaled/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Rectangle](../rectangle/)\&) | 使用原始物理尺寸在指定位置绘制指定图像。 |
| void [DrawImageUnscaled](./drawimageunscaled/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Point](../point/)\&) | 使用原始物理尺寸在指定位置绘制指定图像。 |
| void [DrawImageUnscaledAndClipped](./drawimageunscaledandclipped/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/)) | NOT IMPLEMENTED. |
| void [DrawLine](./drawline/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Point](../point/), [Point](../point/)) | 使用指定的笔绘制指定的直线。 |
| void [DrawLine](./drawline/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [PointF](../pointf/), [PointF](../pointf/)) | 使用指定的笔绘制指定的直线。 |
| void [DrawLine](./drawline/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, int, int, int, int) | 使用指定的笔绘制指定的直线。 |
| void [DrawLine](./drawline/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**) | 使用指定的笔绘制指定的直线。 |
| void [DrawLines](./drawlines/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [System::ArrayPtr](../../system/arrayptr/)\<[System::Drawing::Point](../point/)\>\&) | 使用指定的笔绘制一系列线段。 |
| void [DrawLines](./drawlines/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [System::ArrayPtr](../../system/arrayptr/)\<[System::Drawing::PointF](../pointf/)\>\&) | 使用指定的笔绘制一系列线段。 |
| void [DrawPath](./drawpath/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 使用指定的笔绘制指定的路径。 |
| void [DrawPie](./drawpie/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **int32_t**, **int32_t**, **int32_t**, **int32_t**, **int32_t**, **int32_t**) | 在当前对象所表示的表面上使用指定的笔绘制指定的扇形。 |
| void [DrawPie](./drawpie/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**, **float**, **float**) | 在当前对象所表示的表面上使用指定的笔绘制指定的扇形。 |
| void [DrawPie](./drawpie/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Rectangle](../rectangle/), **float**, **float**) | 在当前对象所表示的表面上使用指定的笔绘制指定的扇形。 |
| void [DrawPie](./drawpie/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [RectangleF](../rectanglef/), **float**, **float**) | 在当前对象所表示的表面上使用指定的笔绘制指定的扇形。 |
| void [DrawPolygon](./drawpolygon/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&) | 使用指定的笔绘制多边形。 |
| void [DrawPolygon](./drawpolygon/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&) | 使用指定的笔绘制多边形。 |
| void [DrawRectangle](./drawrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, int, int, int, int) | 在当前对象所表示的表面上使用指定的笔绘制指定的矩形。 |
| void [DrawRectangle](./drawrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**) | 在当前对象所表示的表面上使用指定的笔绘制指定的矩形。 |
| void [DrawRectangle](./drawrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Rectangle](../rectangle/)) | 在当前对象所表示的表面上使用指定的笔绘制指定的矩形。 |
| void [DrawRectangles](./drawrectangles/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../rectangle/)\>\&) | 使用指定的笔绘制一系列矩形。 |
| void [DrawRectangles](./drawrectangles/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\>\&) | 使用指定的笔绘制一系列矩形。 |
| void [DrawString](./drawstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Font](../font/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [PointF](../pointf/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::StringFormat](../stringformat/)\>\&) | 使用指定的字体和画刷在指定位置绘制指定的字符串。 |
| void [DrawString](./drawstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Font](../font/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [RectangleF](../rectanglef/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::StringFormat](../stringformat/)\>\&) | 使用指定的字体和画刷在指定矩形内绘制指定的字符串。 |
| void [DrawString](./drawstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Font](../font/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**, **float**, const [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::StringFormat](../stringformat/)\>\&) | 使用指定的字体和画刷在指定位置绘制指定的字符串。 |
| void [EndContainer](./endcontainer/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsContainer](../../system.drawing.drawing2d/graphicscontainer/)\>\&) | 关闭当前容器并从已保存的容器状态恢复此对象的状态。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | NOT IMPLEMENTED. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | NOT IMPLEMENTED. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [Point](../point/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | NOT IMPLEMENTED. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [PointF](../pointf/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | NOT IMPLEMENTED. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [Rectangle](../rectangle/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | NOT IMPLEMENTED. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [RectangleF](../rectanglef/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | NOT IMPLEMENTED. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [Point](../point/), [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | NOT IMPLEMENTED. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [PointF](../pointf/), [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | NOT IMPLEMENTED. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | NOT IMPLEMENTED. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | NOT IMPLEMENTED. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [Rectangle](../rectangle/), [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | NOT IMPLEMENTED. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [RectangleF](../rectanglef/), [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | NOT IMPLEMENTED. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，尽管根据 IEC 60559:1989 标准，NaN 不等于任何值，包括 NaN 本身。 |
| void [ExcludeClip](./excludeclip/)([Rectangle](../rectangle/)) | NOT IMPLEMENTED. |
| void [ExcludeClip](./excludeclip/)(const [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&) | NOT IMPLEMENTED. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| void [FillClosedCurve](./fillclosedcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/), **float**) | 使用指定的画刷绘制闭合样条曲线。 |
| void [FillClosedCurve](./fillclosedcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/), **float**) | 使用指定的画刷绘制闭合样条曲线。 |
| void [FillEllipse](./fillellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [Rectangle](../rectangle/)) | 使用指定的画刷填充由边界矩形限定的椭圆内部。 |
| void [FillEllipse](./fillellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [RectangleF](../rectanglef/)) | 使用指定的画刷填充由边界矩形限定的椭圆内部。 |
| void [FillEllipse](./fillellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, int, int, int, int) | 使用指定的画刷填充由边界矩形限定的椭圆内部。 |
| void [FillEllipse](./fillellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**, **float**, **float**, **float**) | 使用指定的画刷填充由边界矩形限定的椭圆内部。 |
| void [FillPath](./fillpath/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 使用指定的画刷填充指定路径的内部。 |
| void [FillPie](./fillpie/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, int, int, int, int, int, int) | 在当前对象所表示的表面上使用指定的画刷填充指定的扇形。 |
| void [FillPie](./fillpie/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**, **float**, **float**, **float**, **float**, **float**) | 在当前对象所表示的表面上使用指定的画刷填充指定的扇形。 |
| void [FillPie](./fillpie/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [Rectangle](../rectangle/), **float**, **float**) | 在当前对象所表示的表面上使用指定的画刷填充指定的扇形。 |
| void [FillPolygon](./fillpolygon/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/)) | 使用指定的画刷填充指定多边形的内部。 |
| void [FillPolygon](./fillpolygon/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/)) | 使用指定的画刷填充指定多边形的内部。 |
| void [FillRectangle](./fillrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**, **float**, **float**, **float**) | 使用指定的画刷填充指定的矩形。 |
| void [FillRectangle](./fillrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, int, int, int, int) | 使用指定的画刷填充指定的矩形。 |
| void [FillRectangle](./fillrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [Rectangle](../rectangle/)) | 使用指定的画刷填充指定的矩形。 |
| void [FillRectangle](./fillrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [RectangleF](../rectanglef/)) | 使用指定的画刷填充指定的矩形。 |
| void [FillRectangles](./fillrectangles/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../rectangle/)\>\&) | 使用指定的画刷填充一系列矩形。 |
| void [FillRectangles](./fillrectangles/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\>\&) | 使用指定的画刷填充一系列矩形。 |
| void [FillRegion](./fillregion/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&) | 使用指定的画刷填充指定区域的内部。 |
| void [Flush](./flush/)([Drawing2D::FlushIntention](../../system.drawing.drawing2d/flushintention/)) | 触发所有挂起的绘制操作的立即执行。 |
| static [SharedPtr](../../system/sharedptr/)\<[Graphics](./)\> [FromHwnd](./fromhwnd/)(IntPtr) | NOT IMPLEMENTED. |
| static [SharedPtr](../../system/sharedptr/)\<[Graphics](./)\> [FromHwndInternal](./fromhwndinternal/)(IntPtr) | NOT IMPLEMENTED. |
| static [SharedPtr](../../system/sharedptr/)\<[Graphics](./)\> [FromImage](./fromimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | 从指定图像创建一个新的 [Graphics](./) 对象。 |
| [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\> [get_Clip](./get_clip/)() | 返回一个 [Region](../region/) 对象，表示限制当前 [Graphics](./) 对象所表示绘图表面绘制区域的区域。 |
| [RectangleF](../rectanglef/) [get_ClipBounds](./get_clipbounds/)() const | 返回一个矩形，界定当前对象所表示表面的裁剪区域。 |
| [Drawing2D::CompositingMode](../../system.drawing.drawing2d/compositingmode/) [get_CompositingMode](./get_compositingmode/)() | 返回一个值，指示在当前对象所表示的表面上合成图像的绘制方式。 |
| [Drawing2D::CompositingQuality](../../system.drawing.drawing2d/compositingquality/) [get_CompositingQuality](./get_compositingquality/)() | 返回一个值，指示合成图像时使用的质量级别。 |
| **float** [get_DpiX](./get_dpix/)() | 返回水平分辨率。 |
| **float** [get_DpiY](./get_dpiy/)() | 返回垂直分辨率。 |
| [Drawing2D::InterpolationMode](../../system.drawing.drawing2d/interpolationmode/) [get_InterpolationMode](./get_interpolationmode/)() | 返回一个值，指示与当前对象关联的插值模式。 |
| **bool** [get_IsClipEmpty](./get_isclipempty/)() const | NOT IMPLEMENTED. |
| **bool** [get_IsVisibleClipEmpty](./get_isvisibleclipempty/)() const | NOT IMPLEMENTED. |
| **float** [get_PageScale](./get_pagescale/)() const | 返回当前 [Graphics](./) 对象的世界单位与页面单位之间的缩放比例。 |
| [GraphicsUnit](../graphicsunit/) [get_PageUnit](./get_pageunit/)() const | 返回在当前对象所表示的表面上用于页面坐标的测量单位。 |
| [Drawing2D::PixelOffsetMode](../../system.drawing.drawing2d/pixeloffsetmode/) [get_PixelOffsetMode](./get_pixeloffsetmode/)() | 返回一个值，指示在当前对象所表示的表面上渲染时像素的偏移方式。 |
| [Point](../point/) [get_RenderingOrigin](./get_renderingorigin/)() const | 返回一个 [Point](../point/) 对象，表示当前 [Graphics](./) 对象用于抖动和线条画刷的渲染原点。 |
| [Drawing2D::SmoothingMode](../../system.drawing.drawing2d/smoothingmode/) [get_SmoothingMode](./get_smoothingmode/)() | 返回一个值，指示在当前对象所表示的表面上渲染时使用的舒缓模式。 |
| **int32_t** [get_TextContrast](./get_textcontrast/)() const | NOT IMPLEMENTED. |
| [Text::TextRenderingHint](../../system.drawing.text/textrenderinghint/) [get_TextRenderingHint](./get_textrenderinghint/)() | 返回一个值，指示文本渲染的质量。 |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\> [get_Transform](./get_transform/)() | 返回当前 [Graphics](./) 对象的几何世界变换。 |
| [RectangleF](../rectanglef/) [get_VisibleClipBounds](./get_visibleclipbounds/)() const | 返回一个 [RectangleF](../rectanglef/) 对象，表示当前 [Graphics](./) 对象可见裁剪区域的边界矩形。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# 的 [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| IntPtr [GetHdc](./gethdc/)() | NOT IMPLEMENTED. |
| [Color](../color/) [GetNearestColor](./getnearestcolor/)([Color](../color/)) | NOT IMPLEMENTED. |
| SkCanvas * [GetSkCanvas](./getskcanvas/)() const |  |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# 的 [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| void [IntersectClip](./intersectclip/)(const [System::SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&) | 将此对象的剪裁区域更新为当前剪裁区域与指定剪裁区域的交集。 |
| void [IntersectClip](./intersectclip/)([System::Drawing::RectangleF](../rectanglef/)) | 将此对象的剪裁区域更新为当前剪裁区域与指定剪裁区域的交集。 |
| void [IntersectClip](./intersectclip/)([System::Drawing::Rectangle](../rectangle/)) | 将此对象的剪裁区域更新为当前剪裁区域与指定剪裁区域的交集。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否为目标类型的实例。相当于 C# 的 'is' 运算符。 |
| **bool** [IsVisible](./isvisible/)([Point](../point/)) | 确定指定点是否位于当前 [Graphics](./) 对象的可见剪裁区域内。 |
| **bool** [IsVisible](./isvisible/)([PointF](../pointf/)) | NOT IMPLEMENTED. |
| **bool** [IsVisible](./isvisible/)([Rectangle](../rectangle/)) | NOT IMPLEMENTED. |
| **bool** [IsVisible](./isvisible/)([RectangleF](../rectanglef/)) | NOT IMPLEMENTED. |
| **bool** [IsVisible](./isvisible/)(**int32_t**, **int32_t**) | NOT IMPLEMENTED. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | NOT IMPLEMENTED. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, **float**, **float**) | NOT IMPLEMENTED. |
| **bool** [IsVisible](./isvisible/)(**int32_t**, **int32_t**, **int32_t**, **int32_t**) | NOT IMPLEMENTED. |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\> [MeasureCharacterRanges](./measurecharacterranges/)(const [System::String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Font](../font/)\>\&, [RectangleF](../rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\>\&) | 返回一个数组，每个元素对应指定字符串中字符位置的区域。 |
| [SizeF](../sizef/) [MeasureString](./measurestring/)([String](../../system/string/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[Font](../font/)\> const\&, [PointF](../pointf/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\> const\&) const | 返回在指定字体和格式下绘制指定字符串时的尺寸。 |
| [SizeF](../sizef/) [MeasureString](./measurestring/)([String](../../system/string/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[Font](../font/)\> const\&, int, [System::SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\> const\&) const | 返回在指定字体和格式下绘制指定字符串时的尺寸。 |
| [SizeF](../sizef/) [MeasureString](./measurestring/)([String](../../system/string/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[Font](../font/)\> const\&, [SizeF](../sizef/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\> const\&, int\&, int\&) const | NOT IMPLEMENTED. |
| [SizeF](../sizef/) [MeasureString](./measurestring/)([String](../../system/string/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[Font](../font/)\> const\&, [SizeF](../sizef/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\> const\&) const | 返回在指定字体和格式下绘制指定字符串时的尺寸。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# 的 [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | 将当前 [Graphics](./) 对象的世界变换矩阵乘以指定矩阵。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷贝构造函数。实际上不复制任何内容，仅初始化新对象并允许子类拷贝构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，仅初始化新对象并允许子类拷贝构造。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 按引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串与 nullptr 情况下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字符串情况的特化。 |
| void [ReleaseHdc](./releasehdc/)() | NOT IMPLEMENTED. |
| void [ReleaseHdc](./releasehdc/)(IntPtr) | NOT IMPLEMENTED. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值递减共享引用计数。 |
| void [ResetClip](./resetclip/)() | 将此图形的剪裁区域重置为无限区域。 |
| void [ResetTransform](./resettransform/)() | 将当前对象的世界变换矩阵重置为单位矩阵。 |
| void [Restore](./restore/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsState](../../system.drawing.drawing2d/graphicsstate/)\>\&) | 从已保存的状态恢复此对象的状态。 |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | 按指定顺序将指定旋转应用于当前 [Graphics](./) 对象的世界变换矩阵。 |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsState](../../system.drawing.drawing2d/graphicsstate/)\> [Save](./save/)() | 保存当前对象的状态并返回已保存的状态。 |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | 将指定的缩放向量应用于当前对象的世界变换矩阵。 |
| void [set_Clip](./set_clip/)(const [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&) | 设置限制当前绘图表面绘制区域的区域。 |
| void [set_CompositingMode](./set_compositingmode/)([Drawing2D::CompositingMode](../../system.drawing.drawing2d/compositingmode/)) | 设置指定在当前对象所表示的表面上合成图像的绘制方式的值。 |
| void [set_CompositingQuality](./set_compositingquality/)([Drawing2D::CompositingQuality](../../system.drawing.drawing2d/compositingquality/)) | 设置在合成图像时使用的质量级别的值。 |
| void [set_InterpolationMode](./set_interpolationmode/)([Drawing2D::InterpolationMode](../../system.drawing.drawing2d/interpolationmode/)) | 设置指示与当前对象关联的插值模式的值。 |
| void [set_PageScale](./set_pagescale/)(**float**) | 设置当前 [Graphics](./) 对象的世界单位与页面单位之间的缩放比例。 |
| void [set_PageUnit](./set_pageunit/)([GraphicsUnit](../graphicsunit/)) | 设置在当前对象所表示的表面上用于页面坐标的测量单位。 |
| void [set_PixelOffsetMode](./set_pixeloffsetmode/)([Drawing2D::PixelOffsetMode](../../system.drawing.drawing2d/pixeloffsetmode/)) | 设置指示在当前对象所表示的表面上渲染时像素应如何偏移的值。 |
| void [set_RenderingOrigin](./set_renderingorigin/)([Point](../point/)) | 设置一个 [Point](../point/) 对象，指定当前 [Graphics](./) 对象用于抖动和线条画刷的渲染原点。 |
| void [set_SmoothingMode](./set_smoothingmode/)([Drawing2D::SmoothingMode](../../system.drawing.drawing2d/smoothingmode/)) | 设置一个指示在当前对象所表示的表面上渲染时使用的舒缓模式的值。 |
| void [set_TextContrast](./set_textcontrast/)(**int32_t**) | NOT IMPLEMENTED. |
| void [set_TextRenderingHint](./set_textrenderinghint/)([Text::TextRenderingHint](../../system.drawing.text/textrenderinghint/)) | 设置指示文本渲染质量的值。 |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | 设置当前 [Graphics](./) 对象的几何世界变换。 |
| void [SetClip](./setclip/)(const [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&, [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | 将当前 [Graphics](./) 对象的剪裁区域设置为将当前剪裁区域与指定区域合并的指定操作的结果。 |
| void [SetClip](./setclip/)([Rectangle](../rectangle/), [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | 将当前 [Graphics](./) 对象的剪裁区域设置为将当前剪裁区域与指定区域合并的指定操作的结果。 |
| void [SetClip](./setclip/)([RectangleF](../rectanglef/), [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | 将当前 [Graphics](./) 对象的剪裁区域设置为将当前剪裁区域与指定区域合并的指定操作的结果。 |
| void [SetClip](./setclip/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](./)\>\&, [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | NOT IMPLEMENTED. |
| void [SetClip](./setclip/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&, [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | 将当前 [Graphics](./) 对象的剪裁区域设置为将当前剪裁区域与图形路径指定的区域合并的指定操作的结果。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中将指针切换为弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取当前共享引用计数的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 减少并返回共享引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相当于 C# 的 [Object.ToString()](../../system/object/tostring/) 方法。启用将自定义对象转换为字符串。 |
| void [TransformPoints](./transformpoints/)([Drawing2D::CoordinateSpace](../../system.drawing.drawing2d/coordinatespace/), [Drawing2D::CoordinateSpace](../../system.drawing.drawing2d/coordinatespace/), const [ArrayPtr](../../system/arrayptr/)\<[System::Drawing::Point](../point/)\>\&) | NOT IMPLEMENTED. |
| void [TransformPoints](./transformpoints/)([Drawing2D::CoordinateSpace](../../system.drawing.drawing2d/coordinatespace/), [Drawing2D::CoordinateSpace](../../system.drawing.drawing2d/coordinatespace/), const [ArrayPtr](../../system/arrayptr/)\<[System::Drawing::PointF](../pointf/)\>\&) | NOT IMPLEMENTED. |
| void [TranslateClip](./translateclip/)(int, int) | NOT IMPLEMENTED. |
| void [TranslateClip](./translateclip/)(**float**, **float**) | NOT IMPLEMENTED. |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | 将指定的平移向量应用于当前 [Graphics](./) 对象的世界变换矩阵。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 减少弱引用计数。不应直接调用；请使用智能指针或 ThisProtector。 |
|  [~Graphics](./~graphics/)() |  |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 类型定义

| 类型定义 | 描述 |
| --- | --- |
| [EnumerateMetafileProc](./enumeratemetafileproc/) | 用作 EnumerateMetafile 方法参数的回调函数对象的类型。 |
| [DrawImageAbort](./drawimageabort/) | 用作 DrawImage 方法参数的回调函数对象的类型。 |

## 另见

* 类 [Object](../../system/object/)
* 命名空间 [System::Drawing](../)
* 库 [Aspose.Slides](../../)