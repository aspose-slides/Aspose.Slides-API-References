---
title: Graphics
second_title: Aspose.Slides C++ 版 API 參考
description: "代表一個繪圖表面。此類別的物件只能透過 System::MakeObject() 函式分配。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤或斷言失敗。請始終將此類別包裝成 System::SmartPtr 智慧指標，並使用該指標作為參數傳遞給函式。"
type: docs
weight: 118
url: /zh-hant/system.drawing/graphics/
---
## Graphics 類


表示一個繪圖表面。此類的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式分配。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。始終將此類包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

```cpp
class Graphics : public virtual System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [AddMetafileComment](./addmetafilecomment/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | 未實作。 |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsContainer](../../system.drawing.drawing2d/graphicscontainer/)\> [BeginContainer](./begincontainer/)() | 儲存一個包含此物件目前狀態的容器，開啟並使用新的容器，並返回已儲存的容器。 |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsContainer](../../system.drawing.drawing2d/graphicscontainer/)\> [BeginContainer](./begincontainer/)([Rectangle](../rectangle/), [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/)) | 儲存一個包含此物件目前狀態的容器，開啟並使用新的容器，並返回已儲存的容器。 |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsContainer](../../system.drawing.drawing2d/graphicscontainer/)\> [BeginContainer](./begincontainer/)([RectangleF](../rectanglef/), [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/)) | 儲存一個包含此物件目前狀態的容器，開啟並使用新的容器，並返回已儲存的容器。 |
| void [Clear](./clear/)([Color](../color/)) | 清除目前物件所表示的繪圖表面，並以指定的顏色填滿。 |
| void [CopyFromScreen](./copyfromscreen/)([Point](../point/), [Point](../point/), [Size](../size/), [CopyPixelOperation](../copypixeloperation/)) | 未實作。 |
| void [CopyFromScreen](./copyfromscreen/)(**int32_t**, **int32_t**, **int32_t**, **int32_t**, [Size](../size/), [CopyPixelOperation](../copypixeloperation/)) | 未實作。 |
| void [Dispose](./dispose/)() | 釋放目前物件所取得的所有作業系統資源。 |
| void [DrawArc](./drawarc/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **int32_t**, **int32_t**, **int32_t**, **int32_t**, **int32_t**, **int32_t**) | 在目前物件所表示的表面上，使用指定的筆畫指定的弧線。 |
| void [DrawArc](./drawarc/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**, **float**, **float**) | 在目前物件所表示的表面上，使用指定的筆畫指定的弧線。 |
| void [DrawArc](./drawarc/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Rectangle](../rectangle/), **float**, **float**) | 在目前物件所表示的表面上，使用指定的筆畫指定的弧線。 |
| void [DrawArc](./drawarc/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [RectangleF](../rectanglef/), **float**, **float**) | 在目前物件所表示的表面上，使用指定的筆畫指定的弧線。 |
| void [DrawBezier](./drawbezier/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [Point](../point/)\&, const [Point](../point/)\&, const [Point](../point/)\&, const [Point](../point/)\&) | 未實作。 |
| void [DrawBezier](./drawbezier/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [PointF](../pointf/)\&, const [PointF](../pointf/)\&, const [PointF](../pointf/)\&, const [PointF](../pointf/)\&) | 未實作。 |
| void [DrawBezier](./drawbezier/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | 未實作。 |
| void [DrawBeziers](./drawbeziers/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&) | 使用指定的筆畫一系列貝茲曲線樣條。 |
| void [DrawBeziers](./drawbeziers/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&) | 使用指定的筆畫一系列貝茲曲線樣條。 |
| void [DrawClosedCurve](./drawclosedcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, **float**, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/)) | 使用指定的筆畫一條閉合樣條。 |
| void [DrawClosedCurve](./drawclosedcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, **float**, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/)) | 使用指定的筆畫一條閉合樣條。 |
| void [DrawCurve](./drawcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, **float**) | 使用指定的筆畫一條樣條。 |
| void [DrawCurve](./drawcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, **float**) | 使用指定的筆畫一條樣條。 |
| void [DrawCurve](./drawcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, **int32_t**, **int32_t**, **float**) | 使用指定的筆畫一條樣條。 |
| void [DrawCurve](./drawcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, **int32_t**, **int32_t**, **float**) | 使用指定的筆畫一條樣條。 |
| void [DrawEllipse](./drawellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Rectangle](../rectangle/)) | 在目前物件所表示的表面上，使用指定的筆畫指定的橢圓。 |
| void [DrawEllipse](./drawellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [RectangleF](../rectanglef/)) | 在目前物件所表示的表面上，使用指定的筆畫指定的橢圓。 |
| void [DrawEllipse](./drawellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, int, int, int, int) | 在目前物件所表示的表面上，使用指定的筆畫指定的橢圓。 |
| void [DrawEllipse](./drawellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**) | 在目前物件所表示的表面上，使用指定的筆畫指定的橢圓。 |
| void [DrawIcon](./drawicon/)(const [SharedPtr](../../system/sharedptr/)\<[Icon](../icon/)\>\&, [Rectangle](../rectangle/)) | 未實作。 |
| void [DrawIcon](./drawicon/)(const [SharedPtr](../../system/sharedptr/)\<[Icon](../icon/)\>\&, **int32_t**, **int32_t**) | 未實作。 |
| void [DrawIconUnstretched](./drawiconunstretched/)(const [SharedPtr](../../system/sharedptr/)\<[Icon](../icon/)\>\&, [Rectangle](../rectangle/)) | 未實作。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [System::ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&) | 未實作。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [System::ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, const [RectangleF](../rectanglef/)\&, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | 在指定位置繪製指定影像的指定區域。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const System::Details::ArrayView\<[PointF](../pointf/)\>\&, const [RectangleF](../rectanglef/)\&, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | 在指定位置繪製指定影像的指定區域。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const System::Details::StackArray\<[PointF](../pointf/), N\>\&, const [RectangleF](../rectanglef/)\&, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | 在指定位置繪製指定影像的指定區域。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | 在指定位置繪製指定的影像。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, **float**, **float**) | 在指定位置繪製指定的影像。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Point](../point/)) | 在指定位置繪製指定的影像。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [PointF](../pointf/)) | 在指定位置繪製指定的影像。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int, int, int) | 將指定的影像繪製至指定的矩形。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, **float**, **float**, **float**, **float**) | 將指定的影像繪製至指定的矩形。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [RectangleF](../rectanglef/), [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/)) | 在指定位置繪製指定影像的指定區域。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/)) | 在指定位置繪製指定影像的指定區域。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int, [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/)) | 在指定位置繪製指定影像的指定區域。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Rectangle](../rectangle/)\&) | 在指定位置繪製指定的影像。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [RectangleF](../rectanglef/)\&) | 在指定位置繪製指定的影像。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), int, int, int, int, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | 將指定影像的指定區域繪製至指定的矩形。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), **float**, **float**, **float**, **float**, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | 將指定影像的指定區域繪製至指定的矩形。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), int, int, int, int, [GraphicsUnit](../graphicsunit/)) | 將指定影像的指定區域繪製至指定的矩形。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), **float**, **float**, **float**, **float**, [GraphicsUnit](../graphicsunit/)) | 將指定影像的指定區域繪製至指定的矩形。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), int, int, int, int, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&, [Graphics::DrawImageAbort](./drawimageabort/)) | 未實作。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), **float**, **float**, **float**, **float**, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&, [Graphics::DrawImageAbort](./drawimageabort/)) | 未實作。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), int, int, int, int, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&, [Graphics::DrawImageAbort](./drawimageabort/), IntPtr) | 未實作。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), **float**, **float**, **float**, **float**, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&, [Graphics::DrawImageAbort](./drawimageabort/), IntPtr) | 未實作。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/)) | 未實作。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&) | 未實作。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/)) | 未實作。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/), const [SharedPtr](../../system/sharedptr/)\<[Imaging::ImageAttributes](../../system.drawing.imaging/imageattributes/)\>\&) | 在指定位置繪製指定影像的指定區域。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, **float**, **float**, [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/)) | 在指定位置繪製指定影像的指定區域。 |
| void [DrawImageUnscaled](./drawimageunscaled/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | 在指定位置以原始實體尺寸繪製指定的影像。 |
| void [DrawImageUnscaled](./drawimageunscaled/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int, int, int) | 在指定位置以原始實體尺寸繪製指定的影像。 |
| void [DrawImageUnscaled](./drawimageunscaled/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Rectangle](../rectangle/)\&) | 在指定位置以原始實體尺寸繪製指定的影像。 |
| void [DrawImageUnscaled](./drawimageunscaled/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Point](../point/)\&) | 在指定位置以原始實體尺寸繪製指定的影像。 |
| void [DrawImageUnscaledAndClipped](./drawimageunscaledandclipped/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/)) | 未實作。 |
| void [DrawLine](./drawline/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Point](../point/), [Point](../point/)) | 使用指定的筆畫指定的直線。 |
| void [DrawLine](./drawline/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [PointF](../pointf/), [PointF](../pointf/)) | 使用指定的筆畫指定的直線。 |
| void [DrawLine](./drawline/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, int, int, int, int) | 使用指定的筆畫指定的直線。 |
| void [DrawLine](./drawline/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**) | 使用指定的筆畫指定的直線。 |
| void [DrawLines](./drawlines/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [System::ArrayPtr](../../system/arrayptr/)\<[System::Drawing::Point](../point/)\>\&) | 使用指定的筆畫一系列線段。 |
| void [DrawLines](./drawlines/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [System::ArrayPtr](../../system/arrayptr/)\<[System::Drawing::PointF](../pointf/)\>\&) | 使用指定的筆畫一系列線段。 |
| void [DrawPath](./drawpath/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 使用指定的筆畫繪製指定的路徑。 |
| void [DrawPie](./drawpie/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **int32_t**, **int32_t**, **int32_t**, **int32_t**, **int32_t**, **int32_t**) | 在目前物件所表示的表面上，使用指定的筆畫指定的扇形。 |
| void [DrawPie](./drawpie/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**, **float**, **float**) | 在目前物件所表示的表面上，使用指定的筆畫指定的扇形。 |
| void [DrawPie](./drawpie/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Rectangle](../rectangle/), **float**, **float**) | 在目前物件所表示的表面上，使用指定的筆畫指定的扇形。 |
| void [DrawPie](./drawpie/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [RectangleF](../rectanglef/), **float**, **float**) | 在目前物件所表示的表面上，使用指定的筆畫指定的扇形。 |
| void [DrawPolygon](./drawpolygon/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&) | 使用指定的筆畫繪製多邊形。 |
| void [DrawPolygon](./drawpolygon/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&) | 使用指定的筆繪製多邊形。 |
| void [DrawRectangle](./drawrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, int, int, int, int) | 在目前物件所代表的表面上，使用指定的筆繪製指定的矩形。 |
| void [DrawRectangle](./drawrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**) | 在目前物件所代表的表面上，使用指定的筆繪製指定的矩形。 |
| void [DrawRectangle](./drawrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Rectangle](../rectangle/)) | 在目前物件所代表的表面上，使用指定的筆繪製指定的矩形。 |
| void [DrawRectangles](./drawrectangles/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../rectangle/)\>\&) | 使用指定的筆繪製一系列矩形。 |
| void [DrawRectangles](./drawrectangles/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\>\&) | 使用指定的筆繪製一系列矩形。 |
| void [DrawString](./drawstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Font](../font/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [PointF](../pointf/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::StringFormat](../stringformat/)\>\&) | 在指定位置使用指定的字型與畫筆繪製指定的字串。 |
| void [DrawString](./drawstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Font](../font/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [RectangleF](../rectanglef/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::StringFormat](../stringformat/)\>\&) | 在指定的矩形內使用指定的字型與畫筆繪製指定的字串。 |
| void [DrawString](./drawstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Font](../font/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**, **float**, const [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::StringFormat](../stringformat/)\>\&) | 在指定位置使用指定的字型與畫筆繪製指定的字串。 |
| void [EndContainer](./endcontainer/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsContainer](../../system.drawing.drawing2d/graphicscontainer/)\>\&) | 關閉目前的容器，並從已儲存的容器狀態還原此物件的狀態。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未實作。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未實作。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [Point](../point/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未實作。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [PointF](../pointf/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未實作。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [Rectangle](../rectangle/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未實作。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [RectangleF](../rectanglef/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未實作。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [Point](../point/), [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未實作。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [PointF](../pointf/), [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未實作。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未實作。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未實作。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [Rectangle](../rectangle/), [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未實作。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [RectangleF](../rectanglef/), [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未實作。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| void [ExcludeClip](./excludeclip/)([Rectangle](../rectangle/)) | 未實作。 |
| void [ExcludeClip](./excludeclip/)(const [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&) | 未實作。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| void [FillClosedCurve](./fillclosedcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/), **float**) | 使用指定的畫筆繪製封閉樣條曲線。 |
| void [FillClosedCurve](./fillclosedcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/), **float**) | 使用指定的畫筆繪製封閉樣條曲線。 |
| void [FillEllipse](./fillellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [Rectangle](../rectangle/)) | 使用指定的畫筆填滿由邊界矩形所界定的橢圓內部。 |
| void [FillEllipse](./fillellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [RectangleF](../rectanglef/)) | 使用指定的畫筆填滿由邊界矩形所界定的橢圓內部。 |
| void [FillEllipse](./fillellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, int, int, int, int) | 使用指定的畫筆填滿由邊界矩形所界定的橢圓內部。 |
| void [FillEllipse](./fillellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**, **float**, **float**, **float**) | 使用指定的畫筆填滿由邊界矩形所界定的橢圓內部。 |
| void [FillPath](./fillpath/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 使用指定的畫筆填滿指定路徑的內部。 |
| void [FillPie](./fillpie/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, int, int, int, int, int, int) | 使用指定的畫筆在目前物件所代表的表面上填滿指定的圓餅形。 |
| void [FillPie](./fillpie/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**, **float**, **float**, **float**, **float**, **float**) | 使用指定的畫筆在目前物件所代表的表面上填滿指定的圓餅形。 |
| void [FillPie](./fillpie/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [Rectangle](../rectangle/), **float**, **float**) | 使用指定的畫筆在目前物件所代表的表面上填滿指定的圓餅形。 |
| void [FillPolygon](./fillpolygon/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/)) | 使用指定的畫筆填滿指定多邊形的內部。 |
| void [FillPolygon](./fillpolygon/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/)) | 使用指定的畫筆填滿指定多邊形的內部。 |
| void [FillRectangle](./fillrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**, **float**, **float**, **float**) | 使用指定的畫筆填滿指定的矩形。 |
| void [FillRectangle](./fillrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, int, int, int, int) | 使用指定的畫筆填滿指定的矩形。 |
| void [FillRectangle](./fillrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [Rectangle](../rectangle/)) | 使用指定的畫筆填滿指定的矩形。 |
| void [FillRectangle](./fillrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [RectangleF](../rectanglef/)) | 使用指定的畫筆填滿指定的矩形。 |
| void [FillRectangles](./fillrectangles/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../rectangle/)\>\&) | 使用指定的畫筆填滿一系列矩形。 |
| void [FillRectangles](./fillrectangles/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\>\&) | 使用指定的畫筆填滿一系列矩形。 |
| void [FillRegion](./fillregion/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&) | 使用指定的畫筆填滿指定區域的內部。 |
| void [Flush](./flush/)([Drawing2D::FlushIntention](../../system.drawing.drawing2d/flushintention/)) | 觸發立即執行所有未完成的繪圖操作。 |
| static [SharedPtr](../../system/sharedptr/)\<[Graphics](./)\> [FromHwnd](./fromhwnd/)(IntPtr) | 未實作。 |
| static [SharedPtr](../../system/sharedptr/)\<[Graphics](./)\> [FromHwndInternal](./fromhwndinternal/)(IntPtr) | 未實作。 |
| static [SharedPtr](../../system/sharedptr/)\<[Graphics](./)\> [FromImage](./fromimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | 從指定的影像建立新的 [Graphics](./) 物件。 |
| [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\> [get_Clip](./get_clip/)() | 傳回一個 [Region](../region/) 物件，該物件代表限制目前 [Graphics](./) 物件所代表之繪圖表面繪圖區域的區域。 |
| [RectangleF](../rectanglef/) [get_ClipBounds](./get_clipbounds/)() const | 傳回一個矩形，該矩形界定目前物件所代表之表面的裁切區域。 |
| [Drawing2D::CompositingMode](../../system.drawing.drawing2d/compositingmode/) [get_CompositingMode](./get_compositingmode/)() | 傳回一個值，表示在目前物件所代表之表面上合成影像的繪製方式。 |
| [Drawing2D::CompositingQuality](../../system.drawing.drawing2d/compositingquality/) [get_CompositingQuality](./get_compositingquality/)() | 傳回一個值，表示合成影像時使用的品質等級。 |
| **float** [get_DpiX](./get_dpix/)() | 傳回水平解析度。 |
| **float** [get_DpiY](./get_dpiy/)() | 傳回垂直解析度。 |
| [Drawing2D::InterpolationMode](../../system.drawing.drawing2d/interpolationmode/) [get_InterpolationMode](./get_interpolationmode/)() | 傳回一個值，表示目前物件相關的插值模式。 |
| **bool** [get_IsClipEmpty](./get_isclipempty/)() const | 未實作。 |
| **bool** [get_IsVisibleClipEmpty](./get_isvisibleclipempty/)() const | 未實作。 |
| **float** [get_PageScale](./get_pagescale/)() const | 傳回目前 [Graphics](./) 物件之世界單位與頁面單位之間的縮放比例。 |
| [GraphicsUnit](../graphicsunit/) [get_PageUnit](./get_pageunit/)() const | 傳回目前物件所代表之表面上頁面座標所使用的測量單位。 |
| [Drawing2D::PixelOffsetMode](../../system.drawing.drawing2d/pixeloffsetmode/) [get_PixelOffsetMode](./get_pixeloffsetmode/)() | 傳回一個值，表示在目前物件所代表之表面上渲染時像素的偏移方式。 |
| [Point](../point/) [get_RenderingOrigin](./get_renderingorigin/)() const | 傳回一個 [Point](../point/) 物件，該物件代表目前 [Graphics](./) 物件用於抖動及斜紋畫筆的渲染原點。 |
| [Drawing2D::SmoothingMode](../../system.drawing.drawing2d/smoothingmode/) [get_SmoothingMode](./get_smoothingmode/)() | 傳回一個值，表示在目前物件所代表之表面上渲染時使用的舒緩模式。 |
| **int32_t** [get_TextContrast](./get_textcontrast/)() const | 未實作。 |
| [Text::TextRenderingHint](../../system.drawing.text/textrenderinghint/) [get_TextRenderingHint](./get_textrenderinghint/)() | 傳回一個值，表示文字渲染的品質。 |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\> [get_Transform](./get_transform/)() | 傳回目前 [Graphics](./) 物件的幾何世界變換。 |
| [RectangleF](../rectanglef/) [get_VisibleClipBounds](./get_visibleclipbounds/)() const | 傳回 [RectangleF](../rectanglef/) 物件，該物件代表目前 [Graphics](./) 物件之可見裁切區域的邊界矩形。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| IntPtr [GetHdc](./gethdc/)() | 未實作。 |
| [Color](../color/) [GetNearestColor](./getnearestcolor/)([Color](../color/)) | 未實作。 |
| SkCanvas * [GetSkCanvas](./getskcanvas/)() const |  |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| void [IntersectClip](./intersectclip/)(const [System::SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&) | 將此物件的裁切區域更新為目前裁切與指定裁切的交集。 |
| void [IntersectClip](./intersectclip/)([System::Drawing::RectangleF](../rectanglef/)) | 將此物件的裁切區域更新為目前裁切與指定裁切的交集。 |
| void [IntersectClip](./intersectclip/)([System::Drawing::Rectangle](../rectangle/)) | 將此物件的裁切區域更新為目前裁切與指定裁切的交集。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否代表 targetType 所描述的型別實例。相當於 C# 的 'is' 運算子。 |
| **bool** [IsVisible](./isvisible/)([Point](../point/)) | 判斷指定的點是否位於目前 [Graphics](./) 物件之可見裁切區域內。 |
| **bool** [IsVisible](./isvisible/)([PointF](../pointf/)) | 未實作。 |
| **bool** [IsVisible](./isvisible/)([Rectangle](../rectangle/)) | 未實作。 |
| **bool** [IsVisible](./isvisible/)([RectangleF](../rectanglef/)) | 未實作。 |
| **bool** [IsVisible](./isvisible/)(**int32_t**, **int32_t**) | 未實作。 |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | 未實作。 |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, **float**, **float**) | 未實作。 |
| **bool** [IsVisible](./isvisible/)(**int32_t**, **int32_t**, **int32_t**, **int32_t**) | 未實作。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\> [MeasureCharacterRanges](./measurecharacterranges/)(const [System::String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Font](../font/)\>\&, [RectangleF](../rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\>\&) | 傳回一個陣列，每個區域界定指定字串中字元位置的範圍。 |
| [SizeF](../sizef/) [MeasureString](./measurestring/)([String](../../system/string/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[Font](../font/)\> const\&, [PointF](../pointf/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\> const\&) const | 傳回在指定字型與指定格式下繪製指定字串時的尺寸。 |
| [SizeF](../sizef/) [MeasureString](./measurestring/)([String](../../system/string/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[Font](../font/)\> const\&, int, [System::SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\> const\&) const | 返回在指定字型與指定格式下繪製指定字串的大小。 |
| [SizeF](../sizef/) [MeasureString](./measurestring/)([String](../../system/string/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[Font](../font/)\> const\&, [SizeF](../sizef/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\> const\&, int\&, int\&) const | 未實作。 |
| [SizeF](../sizef/) [MeasureString](./measurestring/)([String](../../system/string/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[Font](../font/)\> const\&, [SizeF](../sizef/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\> const\&) const | 返回在指定字型與指定格式下繪製指定字串的大小。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂類型的複製。 |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | 將目前 [Graphics](./) 物件的世界轉換矩陣乘以指定的矩陣。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構函式。實際上不會複製任何東西，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何東西，只是初始化新物件並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 依參照比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 依參照比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參照比較值類型物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的專門化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的專門化，用於字串的情況。 |
| void [ReleaseHdc](./releasehdc/)() | 未實作。 |
| void [ReleaseHdc](./releasehdc/)(IntPtr) | 未實作。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的數值。 |
| void [ResetClip](./resetclip/)() | 將此圖形的裁剪區域重設為無限區域。 |
| void [ResetTransform](./resettransform/)() | 將目前物件的世界轉換矩陣重設為單位矩陣。 |
| void [Restore](./restore/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsState](../../system.drawing.drawing2d/graphicsstate/)\>\&) | 從已保存的狀態還原此物件的狀態。 |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | 依指定順序將指定的旋轉套用至目前 [Graphics](./) 物件的世界轉換矩陣。 |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsState](../../system.drawing.drawing2d/graphicsstate/)\> [Save](./save/)() | 保存此物件的目前狀態並返回已保存的狀態。 |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | 將指定的縮放向量套用至目前物件的世界轉換矩陣。 |
| void [set_Clip](./set_clip/)(const [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&) | 設定一個區域，以限制目前所代表的繪圖表面的繪製區域。 |
| void [set_CompositingMode](./set_compositingmode/)([Drawing2D::CompositingMode](../../system.drawing.drawing2d/compositingmode/)) | 設定一個值，以指定在目前物件所代表的表面上合成圖像的繪製方式。 |
| void [set_CompositingQuality](./set_compositingquality/)([Drawing2D::CompositingQuality](../../system.drawing.drawing2d/compositingquality/)) | 設定一個值，以指定合成圖像時使用的品質等級。 |
| void [set_InterpolationMode](./set_interpolationmode/)([Drawing2D::InterpolationMode](../../system.drawing.drawing2d/interpolationmode/)) | 設定一個值，以指示與目前物件相關的插值模式。 |
| void [set_PageScale](./set_pagescale/)(**float**) | 設定目前 [Graphics](./) 物件的世界單位與頁面單位之間的縮放比例。 |
| void [set_PageUnit](./set_pageunit/)([GraphicsUnit](../graphicsunit/)) | 設定目前物件所代表表面上的頁面座標使用的測量單位。 |
| void [set_PixelOffsetMode](./set_pixeloffsetmode/)([Drawing2D::PixelOffsetMode](../../system.drawing.drawing2d/pixeloffsetmode/)) | 設定一個值，以指定在目前物件所代表的表面上渲染時像素的偏移方式。 |
| void [set_RenderingOrigin](./set_renderingorigin/)([Point](../point/)) | 設定一個 [Point](../point/) 物件，以指定目前 [Graphics](./) 物件在抖動與圖案筆刷時的渲染原點。 |
| void [set_SmoothingMode](./set_smoothingmode/)([Drawing2D::SmoothingMode](../../system.drawing.drawing2d/smoothingmode/)) | 設定一個值，以指定在目前物件所代表的表面上渲染時使用的平滑模式。 |
| void [set_TextContrast](./set_textcontrast/)(**int32_t**) | 未實作。 |
| void [set_TextRenderingHint](./set_textrenderinghint/)([Text::TextRenderingHint](../../system.drawing.text/textrenderinghint/)) | 設定一個值，以指定文字渲染的品質。 |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | 設定目前 [Graphics](./) 物件的幾何世界轉換。 |
| void [SetClip](./setclip/)(const [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&, [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | 將目前 [Graphics](./) 物件所代表的繪圖表面的裁剪區域設定為指定運算（結合目前裁剪區域與指定區域）的結果。 |
| void [SetClip](./setclip/)([Rectangle](../rectangle/), [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | 將目前 [Graphics](./) 物件所代表的繪圖表面的裁剪區域設定為指定運算（結合目前裁剪區域與指定區域）的結果。 |
| void [SetClip](./setclip/)([RectangleF](../rectanglef/), [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | 將目前 [Graphics](./) 物件所代表的繪圖表面的裁剪區域設定為指定運算（結合目前裁剪區域與指定區域）的結果。 |
| void [SetClip](./setclip/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](./)\>\&, [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | 未實作。 |
| void [SetClip](./setclip/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&, [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | 將目前 [Graphics](./) 物件所代表的繪圖表面的裁剪區域設定為指定運算（結合目前裁剪區域與圖形路徑所指定的區域）的結果。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。啟用將自訂物件轉換為字串。 |
| void [TransformPoints](./transformpoints/)([Drawing2D::CoordinateSpace](../../system.drawing.drawing2d/coordinatespace/), [Drawing2D::CoordinateSpace](../../system.drawing.drawing2d/coordinatespace/), const [ArrayPtr](../../system/arrayptr/)\<[System::Drawing::Point](../point/)\>\&) | 未實作。 |
| void [TransformPoints](./transformpoints/)([Drawing2D::CoordinateSpace](../../system.drawing.drawing2d/coordinatespace/), [Drawing2D::CoordinateSpace](../../system.drawing.drawing2d/coordinatespace/), const [ArrayPtr](../../system/arrayptr/)\<[System::Drawing::PointF](../pointf/)\>\&) | 未實作。 |
| void [TranslateClip](./translateclip/)(int, int) | 未實作。 |
| void [TranslateClip](./translateclip/)(**float**, **float**) | 未實作。 |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | 將指定的平移向量套用至目前 [Graphics](./) 物件的世界轉換矩陣。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
|  [~Graphics](./~graphics/)() |  |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
## 型別別名

| 型別別名 | 描述 |
| --- | --- |
| [EnumerateMetafileProc](./enumeratemetafileproc/) | 用於 EnumerateMetafile 方法之參數的回呼函式物件類型。 |
| [DrawImageAbort](./drawimageabort/) | 用於 DrawImage 方法之參數的回呼函式物件類型。 |
## 另請參閱

* 類別 [Object](../../system/object/)
* 命名空間 [System::Drawing](../)
* 函式庫 [Aspose.Slides](../../)