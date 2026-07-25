---
title: Graphics
second_title: Aspose.Slides for C++ API リファレンス
description: "描画サーフェスを表します。このクラスのオブジェクトは System::MakeObject() 関数を使用してのみ割り当てるべきです。スタック上や operator new を使用してこの型のインスタンスを作成しないでください。そうしないと実行時エラーやアサーション違反が発生します。常にこのクラスを System::SmartPtr ポインタでラップし、そのポインタを関数への引数として使用してください。"
type: docs
weight: 118
url: /ja/system.drawing/graphics/
---
## Graphics クラス

描画サーフェスを表します。このクラスのオブジェクトは [System::MakeObject()](../../system/makeobject/) 関数を使用してのみ割り当てるべきです。このタイプのインスタンスをスタック上で作成したり operator new を使用したりしないでください。そうしないと実行時エラーやアサーション障害が発生します。常にこのクラスを [System::SmartPtr](../../system/smartptr/) ポインタでラップし、そのポインタを関数への引数として渡すようにしてください。

```cpp
class Graphics : public virtual System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [AddMetafileComment](./addmetafilecomment/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | 未実装です。 |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsContainer](../../system.drawing.drawing2d/graphicscontainer/)\> [BeginContainer](./begincontainer/)() | このオブジェクトの現在の状態を保持したコンテナを保存し、新しいコンテナを開いて使用し、保存したコンテナを返します。 |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsContainer](../../system.drawing.drawing2d/graphicscontainer/)\> [BeginContainer](./begincontainer/)([Rectangle](../rectangle/), [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/)) | このオブジェクトの現在の状態を保持したコンテナを保存し、新しいコンテナを開いて使用し、保存したコンテナを返します。 |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsContainer](../../system.drawing.drawing2d/graphicscontainer/)\> [BeginContainer](./begincontainer/)([RectangleF](../rectanglef/), [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/)) | このオブジェクトの現在の状態を保持したコンテナを保存し、新しいコンテナを開いて使用し、保存したコンテナを返します。 |
| void [Clear](./clear/)([Color](../color/)) | 現在のオブジェクトが表す描画サーフェスをクリアし、指定された色で塗りつぶします。 |
| void [CopyFromScreen](./copyfromscreen/)([Point](../point/), [Point](../point/), [Size](../size/), [CopyPixelOperation](../copypixeloperation/)) | 未実装です。 |
| void [CopyFromScreen](./copyfromscreen/)(**int32_t**, **int32_t**, **int32_t**, **int32_t**, [Size](../size/), [CopyPixelOperation](../copypixeloperation/)) | 未実装です。 |
| void [Dispose](./dispose/)() | 現在のオブジェクトが取得したすべての OS リソースを解放します。 |
| void [DrawArc](./drawarc/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **int32_t**, **int32_t**, **int32_t**, **int32_t**, **int32_t**, **int32_t**) | 現在のオブジェクトが表すサーフェス上に、指定されたペンで指定された円弧を描画します。 |
| void [DrawArc](./drawarc/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**, **float**, **float**) | 現在のオブジェクトが表すサーフェス上に、指定されたペンで指定された円弧を描画します。 |
| void [DrawArc](./drawarc/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Rectangle](../rectangle/), **float**, **float**) | 現在のオブジェクトが表すサーフェス上に、指定されたペンで指定された円弧を描画します。 |
| void [DrawArc](./drawarc/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [RectangleF](../rectanglef/), **float**, **float**) | 現在のオブジェクトが表すサーフェス上に、指定されたペンで指定された円弧を描画します。 |
| void [DrawBezier](./drawbezier/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [Point](../point/)\&, const [Point](../point/)\&, const [Point](../point/)\&, const [Point](../point/)\&) | 未実装です。 |
| void [DrawBezier](./drawbezier/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [PointF](../pointf/)\&, const [PointF](../pointf/)\&, const [PointF](../pointf/)\&, const [PointF](../pointf/)\&) | 未実装です。 |
| void [DrawBezier](./drawbezier/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | 未実装です。 |
| void [DrawBeziers](./drawbeziers/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&) | 指定されたペンでベジェスプラインの系列を描画します。 |
| void [DrawBeziers](./drawbeziers/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&) | 指定されたペンでベジェスプラインの系列を描画します。 |
| void [DrawClosedCurve](./drawclosedcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, **float**, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/)) | 指定されたペンで閉じたスプラインを描画します。 |
| void [DrawClosedCurve](./drawclosedcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, **float**, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/)) | 指定されたペンで閉じたスプラインを描画します。 |
| void [DrawCurve](./drawcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, **float**) | 指定されたペンでスプラインを描画します。 |
| void [DrawCurve](./drawcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, **float**) | 指定されたペンでスプラインを描画します。 |
| void [DrawCurve](./drawcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, **int32_t**, **int32_t**, **float**) | 指定されたペンでスプラインを描画します。 |
| void [DrawCurve](./drawcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, **int32_t**, **int32_t**, **float**) | 指定されたペンでスプラインを描画します。 |
| void [DrawEllipse](./drawellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Rectangle](../rectangle/)) | 現在のオブジェクトが表すサーフェス上に、指定されたペンで指定された楕円を描画します。 |
| void [DrawEllipse](./drawellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [RectangleF](../rectanglef/)) | 現在のオブジェクトが表すサーフェス上に、指定されたペンで指定された楕円を描画します。 |
| void [DrawEllipse](./drawellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, int, int, int, int) | 現在のオブジェクトが表すサーフェス上に、指定されたペンで指定された楕円を描画します。 |
| void [DrawEllipse](./drawellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**) | 現在のオブジェクトが表すサーフェス上に、指定されたペンで指定された楕円を描画します。 |
| void [DrawIcon](./drawicon/)(const [SharedPtr](../../system/sharedptr/)\<[Icon](../icon/)\>\&, [Rectangle](../rectangle/)) | 未実装です。 |
| void [DrawIcon](./drawicon/)(const [SharedPtr](../../system/sharedptr/)\<[Icon](../icon/)\>\&, **int32_t**, **int32_t**) | 未実装です。 |
| void [DrawIconUnstretched](./drawiconunstretched/)(const [SharedPtr](../../system/sharedptr/)\<[Icon](../icon/)\>\&, [Rectangle](../rectangle/)) | 未実装です。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [System::ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&) | 未実装です。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [System::ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, const [RectangleF](../rectanglef/)\&, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | 指定された画像の指定領域を指定された位置に描画します。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const System::Details::ArrayView\<[PointF](../pointf/)\>\&, const [RectangleF](../rectanglef/)\&, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | 指定された画像の指定領域を指定された位置に描画します。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const System::Details::StackArray\<[PointF](../pointf/), N\>\&, const [RectangleF](../rectanglef/)\&, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | 指定された画像の指定領域を指定された位置に描画します。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | 指定された画像を指定された位置に描画します。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, **float**, **float**) | 指定された画像を指定された位置に描画します。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Point](../point/)) | 指定された画像を指定された位置に描画します。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [PointF](../pointf/)) | 指定された画像を指定された位置に描画します。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int, int, int) | 指定された画像を指定された矩形に描画します。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, **float**, **float**, **float**, **float**) | 指定された画像を指定された矩形に描画します。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [RectangleF](../rectanglef/), [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/)) | 指定された画像の指定領域を指定された位置に描画します。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/)) | 指定された画像の指定領域を指定された位置に描画します。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int, [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/)) | 指定された画像の指定領域を指定された位置に描画します。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Rectangle](../rectangle/)\&) | 指定された画像を指定された位置に描画します。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [RectangleF](../rectanglef/)\&) | 指定された画像を指定された位置に描画します。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), int, int, int, int, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | 指定された画像の指定領域を指定された矩形に描画します。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), **float**, **float**, **float**, **float**, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | 指定された画像の指定領域を指定された矩形に描画します。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), int, int, int, int, [GraphicsUnit](../graphicsunit/)) | 指定された画像の指定領域を指定された矩形に描画します。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), **float**, **float**, **float**, **float**, [GraphicsUnit](../graphicsunit/)) | 指定された画像の指定領域を指定された矩形に描画します。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), int, int, int, int, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&, [Graphics::DrawImageAbort](./drawimageabort/)) | 未実装です。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), **float**, **float**, **float**, **float**, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&, [Graphics::DrawImageAbort](./drawimageabort/)) | 未実装です。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), int, int, int, int, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&, [Graphics::DrawImageAbort](./drawimageabort/), IntPtr) | 未実装です。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), **float**, **float**, **float**, **float**, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&, [Graphics::DrawImageAbort](./drawimageabort/), IntPtr) | 未実装です。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/)) | 未実装です。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&) | 未実装です。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/)) | 未実装です。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/), const [SharedPtr](../../system/sharedptr/)\<[Imaging::ImageAttributes](../../system.drawing.imaging/imageattributes/)\>\&) | 指定された画像の指定領域を指定された位置に描画します。 |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, **float**, **float**, [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/)) | 指定された画像の指定領域を指定された位置に描画します。 |
| void [DrawImageUnscaled](./drawimageunscaled/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | 指定された画像を元の実寸サイズで指定された位置に描画します。 |
| void [DrawImageUnscaled](./drawimageunscaled/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int, int, int) | 指定された画像を元の実寸サイズで指定された位置に描画します。 |
| void [DrawImageUnscaled](./drawimageunscaled/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Rectangle](../rectangle/)\&) | 指定された画像を元の実寸サイズで指定された位置に描画します。 |
| void [DrawImageUnscaled](./drawimageunscaled/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Point](../point/)\&) | 指定された画像を元の実寸サイズで指定された位置に描画します。 |
| void [DrawImageUnscaledAndClipped](./drawimageunscaledandclipped/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/)) | 未実装です。 |
| void [DrawLine](./drawline/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Point](../point/), [Point](../point/)) | 指定されたペンで指定された線を描画します。 |
| void [DrawLine](./drawline/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [PointF](../pointf/), [PointF](../pointf/)) | 指定されたペンで指定された線を描画します。 |
| void [DrawLine](./drawline/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, int, int, int, int) | 指定されたペンで指定された線を描画します。 |
| void [DrawLine](./drawline/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**) | 指定されたペンで指定された線を描画します。 |
| void [DrawLines](./drawlines/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [System::ArrayPtr](../../system/arrayptr/)\<[System::Drawing::Point](../point/)\>\&) | 指定されたペンで一連の線分を描画します。 |
| void [DrawLines](./drawlines/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [System::ArrayPtr](../../system/arrayptr/)\<[System::Drawing::PointF](../pointf/)\>\&) | 指定されたペンで一連の線分を描画します。 |
| void [DrawPath](./drawpath/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 指定されたペンで指定されたパスを描画します。 |
| void [DrawPie](./drawpie/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **int32_t**, **int32_t**, **int32_t**, **int32_t**, **int32_t**, **int32_t**) | 現在のオブジェクトが表すサーフェス上に、指定されたペンで指定されたパイを描画します。 |
| void [DrawPie](./drawpie/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**, **float**, **float**) | 現在のオブジェクトが表すサーフェス上に、指定されたペンで指定されたパイを描画します。 |
| void [DrawPie](./drawpie/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Rectangle](../rectangle/), **float**, **float**) | 現在のオブジェクトが表すサーフェス上に、指定されたペンで指定されたパイを描画します。 |
| void [DrawPie](./drawpie/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [RectangleF](../rectanglef/), **float**, **float**) | 現在のオブジェクトが表すサーフェス上に、指定されたペンで指定されたパイを描画します。 |
| void [DrawPolygon](./drawpolygon/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&) | 指定されたペンで多角形を描画します。 |
| void [DrawPolygon](./drawpolygon/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&) | 指定されたペンを使用してポリゴンを描画します。 |
| void [DrawRectangle](./drawrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, int, int, int, int) | 現在のオブジェクトが表す表面上で、指定されたペンを使用して指定された矩形を描画します。 |
| void [DrawRectangle](./drawrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**) | 現在のオブジェクトが表す表面上で、指定されたペンを使用して指定された矩形を描画します。 |
| void [DrawRectangle](./drawrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Rectangle](../rectangle/)) | 現在のオブジェクトが表す表面上で、指定されたペンを使用して指定された矩形を描画します。 |
| void [DrawRectangles](./drawrectangles/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../rectangle/)\>\&) | 指定されたペンを使用して矩形の系列を描画します。 |
| void [DrawRectangles](./drawrectangles/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\>\&) | 指定されたペンを使用して矩形の系列を描画します。 |
| void [DrawString](./drawstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Font](../font/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [PointF](../pointf/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::StringFormat](../stringformat/)\>\&) | 指定されたフォントとブラシを使用して、指定された位置に指定された文字列を描画します。 |
| void [DrawString](./drawstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Font](../font/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [RectangleF](../rectanglef/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::StringFormat](../stringformat/)\>\&) | 指定されたフォントとブラシを使用して、指定された矩形内に指定された文字列を描画します。 |
| void [DrawString](./drawstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Font](../font/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**, **float**, const [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::StringFormat](../stringformat/)\>\&) | 指定されたフォントとブラシを使用して、指定された位置に指定された文字列を描画します。 |
| void [EndContainer](./endcontainer/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsContainer](../../system.drawing.drawing2d/graphicscontainer/)\>\&) | 現在のコンテナを閉じ、保存されたコンテナの状態からこのオブジェクトの状態を復元します。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未実装です。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未実装です。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [Point](../point/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未実装です。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [PointF](../pointf/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未実装です。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [Rectangle](../rectangle/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未実装です。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [RectangleF](../rectanglef/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未実装です。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [Point](../point/), [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未実装です。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [PointF](../pointf/), [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未実装です。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未実装です。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未実装です。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [Rectangle](../rectangle/), [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未実装です。 |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [RectangleF](../rectanglef/), [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 未実装です。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値（NaN を含む）とも等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値（NaN を含む）とも等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| void [ExcludeClip](./excludeclip/)([Rectangle](../rectangle/)) | 未実装です。 |
| void [ExcludeClip](./excludeclip/)(const [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&) | 未実装です。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| void [FillClosedCurve](./fillclosedcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/), **float**) | 指定されたブラシを使用して閉じたスプラインを描画します。 |
| void [FillClosedCurve](./fillclosedcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/), **float**) | 指定されたブラシを使用して閉じたスプラインを描画します。 |
| void [FillEllipse](./fillellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [Rectangle](../rectangle/)) | 指定されたブラシを使用して、境界矩形で指定された楕円の内部を塗りつぶします。 |
| void [FillEllipse](./fillellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [RectangleF](../rectanglef/)) | 指定されたブラシを使用して、境界矩形で指定された楕円の内部を塗りつぶします。 |
| void [FillEllipse](./fillellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, int, int, int, int) | 指定されたブラシを使用して、境界矩形で指定された楕円の内部を塗りつぶします。 |
| void [FillEllipse](./fillellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**, **float**, **float**, **float**) | 指定されたブラシを使用して、境界矩形で指定された楕円の内部を塗りつぶします。 |
| void [FillPath](./fillpath/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 指定されたブラシを使用して、指定されたパスの内部を塗りつぶします。 |
| void [FillPie](./fillpie/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, int, int, int, int, int, int) | 現在のオブジェクトが表す表面上で、指定されたブラシを使用して指定されたパイを塗りつぶします。 |
| void [FillPie](./fillpie/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**, **float**, **float**, **float**, **float**, **float**) | 現在のオブジェクトが表す表面上で、指定されたブラシを使用して指定されたパイを塗りつぶします。 |
| void [FillPie](./fillpie/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [Rectangle](../rectangle/), **float**, **float**) | 現在のオブジェクトが表す表面上で、指定されたブラシを使用して指定されたパイを塗りつぶします。 |
| void [FillPolygon](./fillpolygon/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/)) | 指定されたブラシを使用して、指定されたポリゴンの内部を塗りつぶします。 |
| void [FillPolygon](./fillpolygon/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/)) | 指定されたブラシを使用して、指定されたポリゴンの内部を塗りつぶします。 |
| void [FillRectangle](./fillrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**, **float**, **float**, **float**) | 指定されたブラシで指定された矩形を塗りつぶします。 |
| void [FillRectangle](./fillrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, int, int, int, int) | 指定されたブラシで指定された矩形を塗りつぶします。 |
| void [FillRectangle](./fillrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [Rectangle](../rectangle/)) | 指定されたブラシで指定された矩形を塗りつぶします。 |
| void [FillRectangle](./fillrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [RectangleF](../rectanglef/)) | 指定されたブラシで指定された矩形を塗りつぶします。 |
| void [FillRectangles](./fillrectangles/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../rectangle/)\>\&) | 指定されたブラシを使用して矩形の系列を塗りつぶします。 |
| void [FillRectangles](./fillrectangles/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\>\&) | 指定されたブラシを使用して矩形の系列を塗りつぶします。 |
| void [FillRegion](./fillregion/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&) | 指定されたブラシを使用して、指定された領域の内部を塗りつぶします。 |
| void [Flush](./flush/)([Drawing2D::FlushIntention](../../system.drawing.drawing2d/flushintention/)) | 保留中のすべての描画操作を即座に実行します。 |
| static [SharedPtr](../../system/sharedptr/)\<[Graphics](./)\> [FromHwnd](./fromhwnd/)(IntPtr) | 未実装です。 |
| static [SharedPtr](../../system/sharedptr/)\<[Graphics](./)\> [FromHwndInternal](./fromhwndinternal/)(IntPtr) | 未実装です。 |
| static [SharedPtr](../../system/sharedptr/)\<[Graphics](./)\> [FromImage](./fromimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | 指定された画像から新しい [Graphics](./) オブジェクトを作成します。 |
| [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\> [get_Clip](./get_clip/)() | [Region](../region/) オブジェクトを返します。このオブジェクトは、現在の [Graphics](./) オブジェクトが表す描画面の描画領域を制限する領域を表します。 |
| [RectangleF](../rectanglef/) [get_ClipBounds](./get_clipbounds/)() const | 現在のオブジェクトが表す表面のクリッピング領域を囲む矩形を返します。 |
| [Drawing2D::CompositingMode](../../system.drawing.drawing2d/compositingmode/) [get_CompositingMode](./get_compositingmode/)() | 現在のオブジェクトが表す表面上で合成画像がどのように描画されるかを示す値を返します。 |
| [Drawing2D::CompositingQuality](../../system.drawing.drawing2d/compositingquality/) [get_CompositingQuality](./get_compositingquality/)() | 画像を合成する際に使用される品質レベルを示す値を返します。 |
| **float** [get_DpiX](./get_dpix/)() | 水平解像度を返します。 |
| **float** [get_DpiY](./get_dpiy/)() | 垂直解像度を返します。 |
| [Drawing2D::InterpolationMode](../../system.drawing.drawing2d/interpolationmode/) [get_InterpolationMode](./get_interpolationmode/)() | 現在のオブジェクトに関連付けられた補間モードを示す値を返します。 |
| **bool** [get_IsClipEmpty](./get_isclipempty/)() const | 未実装です。 |
| **bool** [get_IsVisibleClipEmpty](./get_isvisibleclipempty/)() const | 未実装です。 |
| **float** [get_PageScale](./get_pagescale/)() const | 現在の [Graphics](./) オブジェクトに対する世界単位とページ単位のスケーリングを返します。 |
| [GraphicsUnit](../graphicsunit/) [get_PageUnit](./get_pageunit/)() const | 現在のオブジェクトが表す表面上でページ座標に使用される測定単位を返します。 |
| [Drawing2D::PixelOffsetMode](../../system.drawing.drawing2d/pixeloffsetmode/) [get_PixelOffsetMode](./get_pixeloffsetmode/)() | 現在のオブジェクトが表す表面上でレンダリング中にピクセルがどのようにオフセットされるかを示す値を返します。 |
| [Point](../point/) [get_RenderingOrigin](./get_renderingorigin/)() const | [Point](../point/) オブジェクトを返します。このオブジェクトは、現在の [Graphics](./) オブジェクトのディザリングおよびハッチブラシ用のレンダリング原点を表します。 |
| [Drawing2D::SmoothingMode](../../system.drawing.drawing2d/smoothingmode/) [get_SmoothingMode](./get_smoothingmode/)() | 現在のオブジェクトが表す表面上でレンダリング時に使用されるスムーズモードを示す値を返します。 |
| **int32_t** [get_TextContrast](./get_textcontrast/)() const | 未実装です。 |
| [Text::TextRenderingHint](../../system.drawing.text/textrenderinghint/) [get_TextRenderingHint](./get_textrenderinghint/)() | テキストレンダリングの品質を示す値を返します。 |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\> [get_Transform](./get_transform/)() | 現在の [Graphics](./) オブジェクトの幾何的なワールド変換を返します。 |
| [RectangleF](../rectanglef/) [get_VisibleClipBounds](./get_visibleclipbounds/)() const | [RectangleF](../rectanglef/) オブジェクトを返します。このオブジェクトは、現在の [Graphics](./) オブジェクトの可視クリッピング領域の境界矩形を表します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| IntPtr [GetHdc](./gethdc/)() | 未実装です。 |
| [Color](../color/) [GetNearestColor](./getnearestcolor/)([Color](../color/)) | 未実装です。 |
| SkCanvas * [GetSkCanvas](./getskcanvas/)() const |  |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| void [IntersectClip](./intersectclip/)(const [System::SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&) | このオブジェクトのクリップ領域を、現在のクリップと指定されたクリップの交差に更新します。 |
| void [IntersectClip](./intersectclip/)([System::Drawing::RectangleF](../rectanglef/)) | このオブジェクトのクリップ領域を、現在のクリップと指定されたクリップの交差に更新します。 |
| void [IntersectClip](./intersectclip/)([System::Drawing::Rectangle](../rectangle/)) | このオブジェクトのクリップ領域を、現在のクリップと指定されたクリップの交差に更新します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| **bool** [IsVisible](./isvisible/)([Point](../point/)) | 指定された点が現在の [Graphics](./) オブジェクトの可視クリップ領域に含まれているかどうかを判断します。 |
| **bool** [IsVisible](./isvisible/)([PointF](../pointf/)) | 未実装です。 |
| **bool** [IsVisible](./isvisible/)([Rectangle](../rectangle/)) | 未実装です。 |
| **bool** [IsVisible](./isvisible/)([RectangleF](../rectanglef/)) | 未実装です。 |
| **bool** [IsVisible](./isvisible/)(**int32_t**, **int32_t**) | 未実装です。 |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | 未実装です。 |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, **float**, **float**) | 未実装です。 |
| **bool** [IsVisible](./isvisible/)(**int32_t**, **int32_t**, **int32_t**, **int32_t**) | 未実装です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\> [MeasureCharacterRanges](./measurecharacterranges/)(const [System::String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Font](../font/)\>\&, [RectangleF](../rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\>\&) | 指定された文字列内の文字位置を囲む領域の配列を返します。 |
| [SizeF](../sizef/) [MeasureString](./measurestring/)([String](../../system/string/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[Font](../font/)\> const\&, [PointF](../pointf/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\> const\&) const | 指定されたフォントと指定されたフォーマットで描画されたときの、指定された文字列のサイズを返します。 |
| [SizeF](../sizef/) [MeasureString](./measurestring/)([String](../../system/string/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[Font](../font/)\> const\&, int, [System::SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\> const\&) const | 指定されたフォントと指定された形式で描画された指定文字列のサイズを返します。 |
| [SizeF](../sizef/) [MeasureString](./measurestring/)([String](../../system/string/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[Font](../font/)\> const\&, [SizeF](../sizef/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\> const\&, int\&, int\&) const | 未実装です。 |
| [SizeF](../sizef/) [MeasureString](./measurestring/)([String](../../system/string/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[Font](../font/)\> const\&, [SizeF](../sizef/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\> const\&) const | 指定されたフォントと指定された形式で描画された指定文字列のサイズを返します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | 現在の [Graphics](./) オブジェクトのワールド変換行列に指定された行列を掛けます。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合に対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合に対する特殊化です。 |
| void [ReleaseHdc](./releasehdc/)() | 未実装です。 |
| void [ReleaseHdc](./releasehdc/)(IntPtr) | 未実装です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [ResetClip](./resetclip/)() | このグラフィックのクリップ領域を無限領域にリセットします。 |
| void [ResetTransform](./resettransform/)() | 現在のオブジェクトのワールド変換行列をリセットし、単位行列にします。 |
| void [Restore](./restore/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsState](../../system.drawing.drawing2d/graphicsstate/)\>\&) | 保存された状態からこのオブジェクトの状態を復元します。 |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | 指定された順序で、現在の [Graphics](./) オブジェクトのワールド変換行列に指定された回転を適用します。 |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsState](../../system.drawing.drawing2d/graphicsstate/)\> [Save](./save/)() | 現在のオブジェクトの状態を保存し、保存された状態を返します。 |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | 指定されたスケールベクトルを現在のオブジェクトのワールド変換行列に適用します。 |
| void [set_Clip](./set_clip/)(const [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&) | 現在の描画サーフェスが表す描画領域を制限する領域を設定します。 |
| void [set_CompositingMode](./set_compositingmode/)([Drawing2D::CompositingMode](../../system.drawing.drawing2d/compositingmode/)) | 現在のオブジェクトが表すサーフェス上で合成画像が描画される方法を指定する値を設定します。 |
| void [set_CompositingQuality](./set_compositingquality/)([Drawing2D::CompositingQuality](../../system.drawing.drawing2d/compositingquality/)) | 画像を合成する際に使用する品質レベルを指定する値を設定します。 |
| void [set_InterpolationMode](./set_interpolationmode/)([Drawing2D::InterpolationMode](../../system.drawing.drawing2d/interpolationmode/)) | 現在のオブジェクトに関連付けられた補間モードを示す値を設定します。 |
| void [set_PageScale](./set_pagescale/)(**float**) | 現在の [Graphics](./) オブジェクトのワールド単位とページ単位間のスケーリングを設定します。 |
| void [set_PageUnit](./set_pageunit/)([GraphicsUnit](../graphicsunit/)) | 現在のオブジェクトが表すサーフェス上のページ座標に使用される測定単位を設定します。 |
| void [set_PixelOffsetMode](./set_pixeloffsetmode/)([Drawing2D::PixelOffsetMode](../../system.drawing.drawing2d/pixeloffsetmode/)) | 現在のオブジェクトが表すサーフェス上でレンダリング中にピクセルをどのようにオフセットするかを指定する値を設定します。 |
| void [set_RenderingOrigin](./set_renderingorigin/)([Point](../point/)) | 現在の [Graphics](./) オブジェクトのディザリングやハッチブラシ用のレンダリング原点を指定する [Point](../point/) オブジェクトを設定します。 |
| void [set_SmoothingMode](./set_smoothingmode/)([Drawing2D::SmoothingMode](../../system.drawing.drawing2d/smoothingmode/)) | 現在のオブジェクトが表すサーフェス上でレンダリング時に使用されるスムージングモードを指定する値を設定します。 |
| void [set_TextContrast](./set_textcontrast/)(**int32_t**) | 未実装です。 |
| void [set_TextRenderingHint](./set_textrenderinghint/)([Text::TextRenderingHint](../../system.drawing.text/textrenderinghint/)) | テキストレンダリングの品質を指定する値を設定します。 |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | 現在の [Graphics](./) オブジェクトの幾何的ワールド変換を設定します。 |
| void [SetClip](./setclip/)(const [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&, [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | 現在の [Graphics](./) オブジェクトが表す描画サーフェスのクリップ領域を、現在のクリップ領域と指定された領域を組み合わせた指定操作の結果に設定します。 |
| void [SetClip](./setclip/)([Rectangle](../rectangle/), [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | 現在の [Graphics](./) オブジェクトが表す描画サーフェスのクリップ領域を、現在のクリップ領域と指定された領域を組み合わせた指定操作の結果に設定します。 |
| void [SetClip](./setclip/)([RectangleF](../rectanglef/), [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | 現在の [Graphics](./) オブジェクトが表す描画サーフェスのクリップ領域を、現在のクリップ領域と指定された領域を組み合わせた指定操作の結果に設定します。 |
| void [SetClip](./setclip/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](./)\>\&, [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | 未実装です。 |
| void [SetClip](./setclip/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&, [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | 現在の [Graphics](./) オブジェクトが表す描画サーフェスのクリップ領域を、現在のクリップ領域とグラフィックパスで指定された領域を組み合わせた指定操作の結果に設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱ポインタ（共有ポインタではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| void [TransformPoints](./transformpoints/)([Drawing2D::CoordinateSpace](../../system.drawing.drawing2d/coordinatespace/), [Drawing2D::CoordinateSpace](../../system.drawing.drawing2d/coordinatespace/), const [ArrayPtr](../../system/arrayptr/)\<[System::Drawing::Point](../point/)\>\&) | 未実装です。 |
| void [TransformPoints](./transformpoints/)([Drawing2D::CoordinateSpace](../../system.drawing.drawing2d/coordinatespace/), [Drawing2D::CoordinateSpace](../../system.drawing.drawing2d/coordinatespace/), const [ArrayPtr](../../system/arrayptr/)\<[System::Drawing::PointF](../pointf/)\>\&) | 未実装です。 |
| void [TranslateClip](./translateclip/)(int, int) | 未実装です。 |
| void [TranslateClip](./translateclip/)(**float**, **float**) | 未実装です。 |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | 指定された平行移動ベクトルを現在の [Graphics](./) オブジェクトのワールド変換行列に適用します。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
|  [~Graphics](./~graphics/)() |  |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
## 型定義

| 型定義 | 説明 |
| --- | --- |
| [EnumerateMetafileProc](./enumeratemetafileproc/) | EnumerateMetafile メソッドの引数として使用されるコールバック関数オブジェクトの型です。 |
| [DrawImageAbort](./drawimageabort/) | DrawImage メソッドの引数として使用されるコールバック関数オブジェクトの型です。 |
## 参照

* クラス [Object](../../system/object/)
* 名前空間 [System::Drawing](../)
* ライブラリ [Aspose.Slides](../../)