---
title: Graphics
second_title: Aspose.Slides for C++ API 레퍼런스
description: "그리기 표면을 나타냅니다. 이 클래스의 객체는 System::MakeObject() 함수를 사용하여 할당해야 합니다. 스택이나 operator new를 사용해 이 타입의 인스턴스를 생성하면 런타임 오류 및/또는 어설션 오류가 발생할 수 있으므로 절대 생성하지 마십시오. 항상 이 클래스를 System::SmartPtr 포인터로 감싸고, 해당 포인터를 함수 인수로 전달하십시오."
type: docs
weight: 118
url: /ko/system.drawing/graphics/
---
## Graphics 클래스

그리기 표면을 나타냅니다. 이 클래스의 객체는 [System::MakeObject()](../../system/makeobject/) 함수를 사용하여만 할당해야 합니다. 스택에 이 유형의 인스턴스를 생성하거나 operator new를 사용해서는 안 되며, 이는 런타임 오류 및/또는 어설션 오류를 초래합니다. 항상 이 클래스를 [System::SmartPtr](../../system/smartptr/) 포인터로 감싸고 이 포인터를 함수에 인수로 전달하는 데 사용하십시오.

```cpp
class Graphics : public virtual System::Object
```

## 메서드

| Method | Description |
| --- | --- |
| void [AddMetafileComment](./addmetafilecomment/)(const [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | 구현되지 않음. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsContainer](../../system.drawing.drawing2d/graphicscontainer/)\> [BeginContainer](./begincontainer/)() | 현재 객체의 현재 상태를 포함하는 컨테이너를 저장하고, 새 컨테이너를 열어 사용한 뒤 저장된 컨테이너를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsContainer](../../system.drawing.drawing2d/graphicscontainer/)\> [BeginContainer](./begincontainer/)([Rectangle](../rectangle/), [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/)) | 현재 객체의 현재 상태를 포함하는 컨테이너를 저장하고, 새 컨테이너를 열어 사용한 뒤 저장된 컨테이너를 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsContainer](../../system.drawing.drawing2d/graphicscontainer/)\> [BeginContainer](./begincontainer/)([RectangleF](../rectanglef/), [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/)) | 현재 객체의 현재 상태를 포함하는 컨테이너를 저장하고, 새 컨테이너를 열어 사용한 뒤 저장된 컨테이너를 반환합니다. |
| void [Clear](./clear/)([Color](../color/)) | 현재 객체가 나타내는 그리기 표면을 지우고 지정된 색으로 채웁니다. |
| void [CopyFromScreen](./copyfromscreen/)([Point](../point/), [Point](../point/), [Size](../size/), [CopyPixelOperation](../copypixeloperation/)) | 구현되지 않음. |
| void [CopyFromScreen](./copyfromscreen/)(**int32_t**, **int32_t**, **int32_t**, **int32_t**, [Size](../size/), [CopyPixelOperation](../copypixeloperation/)) | 구현되지 않음. |
| void [Dispose](./dispose/)() | 현재 객체가 획득한 모든 운영 체제 리소스를 해제합니다. |
| void [DrawArc](./drawarc/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **int32_t**, **int32_t**, **int32_t**, **int32_t**, **int32_t**, **int32_t**) | 지정된 펜을 사용하여 현재 객체가 나타내는 표면 위에 지정된 호를 그립니다. |
| void [DrawArc](./drawarc/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**, **float**, **float**) | 지정된 펜을 사용하여 현재 객체가 나타내는 표면 위에 지정된 호를 그립니다. |
| void [DrawArc](./drawarc/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Rectangle](../rectangle/), **float**, **float**) | 지정된 펜을 사용하여 현재 객체가 나타내는 표면 위에 지정된 호를 그립니다. |
| void [DrawArc](./drawarc/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [RectangleF](../rectanglef/), **float**, **float**) | 지정된 펜을 사용하여 현재 객체가 나타내는 표면 위에 지정된 호를 그립니다. |
| void [DrawBezier](./drawbezier/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [Point](../point/)\&, const [Point](../point/)\&, const [Point](../point/)\&, const [Point](../point/)\&) | 구현되지 않음. |
| void [DrawBezier](./drawbezier/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [PointF](../pointf/)\&, const [PointF](../pointf/)\&, const [PointF](../pointf/)\&, const [PointF](../pointf/)\&) | 구현되지 않음. |
| void [DrawBezier](./drawbezier/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**, **float**, **float**, **float**, **float**) | 구현되지 않음. |
| void [DrawBeziers](./drawbeziers/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&) | 지정된 펜을 사용하여 베지어 스플라인 시리즈를 그립니다. |
| void [DrawBeziers](./drawbeziers/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&) | 지정된 펜을 사용하여 베지어 스플라인 시리즈를 그립니다. |
| void [DrawClosedCurve](./drawclosedcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, **float**, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/)) | 지정된 펜을 사용하여 닫힌 스플라인을 그립니다. |
| void [DrawClosedCurve](./drawclosedcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, **float**, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/)) | 지정된 펜을 사용하여 닫힌 스플라인을 그립니다. |
| void [DrawCurve](./drawcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, **float**) | 지정된 펜을 사용하여 스플라인을 그립니다. |
| void [DrawCurve](./drawcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, **float**) | 지정된 펜을 사용하여 스플라인을 그립니다. |
| void [DrawCurve](./drawcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, **int32_t**, **int32_t**, **float**) | 지정된 펜을 사용하여 스플라인을 그립니다. |
| void [DrawCurve](./drawcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, **int32_t**, **int32_t**, **float**) | 지정된 펜을 사용하여 스플라인을 그립니다. |
| void [DrawEllipse](./drawellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Rectangle](../rectangle/)) | 현재 객체가 나타내는 표면 위에 지정된 펜으로 지정된 타원을 그립니다. |
| void [DrawEllipse](./drawellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [RectangleF](../rectanglef/)) | 현재 객체가 나타내는 표면 위에 지정된 펜으로 지정된 타원을 그립니다. |
| void [DrawEllipse](./drawellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, int, int, int, int) | 현재 객체가 나타내는 표면 위에 지정된 펜으로 지정된 타원을 그립니다. |
| void [DrawEllipse](./drawellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**) | 현재 객체가 나타내는 표면 위에 지정된 펜으로 지정된 타원을 그립니다. |
| void [DrawIcon](./drawicon/)(const [SharedPtr](../../system/sharedptr/)\<[Icon](../icon/)\>\&, [Rectangle](../rectangle/)) | 구현되지 않음. |
| void [DrawIcon](./drawicon/)(const [SharedPtr](../../system/sharedptr/)\<[Icon](../icon/)\>\&, **int32_t**, **int32_t**) | 구현되지 않음. |
| void [DrawIconUnstretched](./drawiconunstretched/)(const [SharedPtr](../../system/sharedptr/)\<[Icon](../icon/)\>\&, [Rectangle](../rectangle/)) | 구현되지 않음. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [System::ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&) | 구현되지 않음. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [System::ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, const [RectangleF](../rectanglef/)\&, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | 지정된 위치에 지정된 이미지의 지정된 영역을 그립니다. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const System::Details::ArrayView\<[PointF](../pointf/)\>\&, const [RectangleF](../rectanglef/)\&, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | 지정된 위치에 지정된 이미지의 지정된 영역을 그립니다. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const System::Details::StackArray\<[PointF](../pointf/), N\>\&, const [RectangleF](../rectanglef/)\&, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | 지정된 위치에 지정된 이미지의 지정된 영역을 그립니다. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | 지정된 위치에 지정된 이미지를 그립니다. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, **float**, **float**) | 지정된 위치에 지정된 이미지를 그립니다. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Point](../point/)) | 지정된 위치에 지정된 이미지를 그립니다. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [PointF](../pointf/)) | 지정된 위치에 지정된 이미지를 그립니다. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int, int, int) | 지정된 사각형에 지정된 이미지를 그립니다. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, **float**, **float**, **float**, **float**) | 지정된 사각형에 지정된 이미지를 그립니다. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [RectangleF](../rectanglef/), [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/)) | 지정된 위치에 지정된 이미지의 지정된 영역을 그립니다. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/)) | 지정된 위치에 지정된 이미지의 지정된 영역을 그립니다. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int, [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/)) | 지정된 위치에 지정된 이미지의 지정된 영역을 그립니다. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Rectangle](../rectangle/)\&) | 지정된 위치에 지정된 이미지를 그립니다. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [RectangleF](../rectanglef/)\&) | 지정된 위치에 지정된 이미지를 그립니다. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), int, int, int, int, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | 지정된 사각형에 지정된 이미지의 지정된 영역을 그립니다. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), **float**, **float**, **float**, **float**, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&) | 지정된 사각형에 지정된 이미지의 지정된 영역을 그립니다. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), int, int, int, int, [GraphicsUnit](../graphicsunit/)) | 지정된 사각형에 지정된 이미지의 지정된 영역을 그립니다. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), **float**, **float**, **float**, **float**, [GraphicsUnit](../graphicsunit/)) | 지정된 사각형에 지정된 이미지의 지정된 영역을 그립니다. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), int, int, int, int, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&, [Graphics::DrawImageAbort](./drawimageabort/)) | 구현되지 않음. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), **float**, **float**, **float**, **float**, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&, [Graphics::DrawImageAbort](./drawimageabort/)) | 구현되지 않음. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), int, int, int, int, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&, [Graphics::DrawImageAbort](./drawimageabort/), IntPtr) | 구현되지 않음. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/), **float**, **float**, **float**, **float**, [GraphicsUnit](../graphicsunit/), const [Imaging::ImageAttributesPtr](../../system.drawing.imaging/imageattributesptr/)\&, [Graphics::DrawImageAbort](./drawimageabort/), IntPtr) | 구현되지 않음. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/)) | 구현되지 않음. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&) | 구현되지 않음. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/)) | 구현되지 않음. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/), const [SharedPtr](../../system/sharedptr/)\<[Imaging::ImageAttributes](../../system.drawing.imaging/imageattributes/)\>\&) | 지정된 위치에 지정된 이미지의 지정된 영역을 그립니다. |
| void [DrawImage](./drawimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, **float**, **float**, [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/)) | 지정된 위치에 지정된 이미지의 지정된 영역을 그립니다. |
| void [DrawImageUnscaled](./drawimageunscaled/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | 지정된 위치에 원본 물리적 크기로 지정된 이미지를 그립니다. |
| void [DrawImageUnscaled](./drawimageunscaled/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int, int, int) | 지정된 위치에 원본 물리적 크기로 지정된 이미지를 그립니다. |
| void [DrawImageUnscaled](./drawimageunscaled/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Rectangle](../rectangle/)\&) | 지정된 위치에 원본 물리적 크기로 지정된 이미지를 그립니다. |
| void [DrawImageUnscaled](./drawimageunscaled/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Point](../point/)\&) | 지정된 위치에 원본 물리적 크기로 지정된 이미지를 그립니다. |
| void [DrawImageUnscaledAndClipped](./drawimageunscaledandclipped/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, [Rectangle](../rectangle/)) | 구현되지 않음. |
| void [DrawLine](./drawline/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Point](../point/), [Point](../point/)) | 지정된 펜을 사용하여 지정된 선을 그립니다. |
| void [DrawLine](./drawline/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [PointF](../pointf/), [PointF](../pointf/)) | 지정된 펜을 사용하여 지정된 선을 그립니다. |
| void [DrawLine](./drawline/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, int, int, int, int) | 지정된 펜을 사용하여 지정된 선을 그립니다. |
| void [DrawLine](./drawline/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**) | 지정된 펜을 사용하여 지정된 선을 그립니다. |
| void [DrawLines](./drawlines/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [System::ArrayPtr](../../system/arrayptr/)\<[System::Drawing::Point](../point/)\>\&) | 지정된 펜을 사용하여 일련의 선분을 그립니다. |
| void [DrawLines](./drawlines/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [System::ArrayPtr](../../system/arrayptr/)\<[System::Drawing::PointF](../pointf/)\>\&) | 지정된 펜을 사용하여 일련의 선분을 그립니다. |
| void [DrawPath](./drawpath/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 지정된 펜을 사용하여 지정된 경로를 그립니다. |
| void [DrawPie](./drawpie/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **int32_t**, **int32_t**, **int32_t**, **int32_t**, **int32_t**, **int32_t**) | 현재 객체가 나타내는 표면 위에 지정된 펜으로 지정된 파이를 그립니다. |
| void [DrawPie](./drawpie/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**, **float**, **float**) | 현재 객체가 나타내는 표면 위에 지정된 펜으로 지정된 파이를 그립니다. |
| void [DrawPie](./drawpie/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Rectangle](../rectangle/), **float**, **float**) | 현재 객체가 나타내는 표면 위에 지정된 펜으로 지정된 파이를 그립니다. |
| void [DrawPie](./drawpie/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [RectangleF](../rectanglef/), **float**, **float**) | 현재 객체가 나타내는 표면 위에 지정된 펜으로 지정된 파이를 그립니다. |
| void [DrawPolygon](./drawpolygon/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&) | 지정된 펜을 사용하여 다각형을 그립니다. |
| void [DrawPolygon](./drawpolygon/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&) | 지정된 펜을 사용하여 다각형을 그립니다. |
| void [DrawRectangle](./drawrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, int, int, int, int) | 현재 객체가 나타내는 표면에 지정된 펜을 사용하여 지정된 사각형을 그립니다. |
| void [DrawRectangle](./drawrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, **float**, **float**, **float**, **float**) | 현재 객체가 나타내는 표면에 지정된 펜을 사용하여 지정된 사각형을 그립니다. |
| void [DrawRectangle](./drawrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, [Rectangle](../rectangle/)) | 현재 객체가 나타내는 표면에 지정된 펜을 사용하여 지정된 사각형을 그립니다. |
| void [DrawRectangles](./drawrectangles/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../rectangle/)\>\&) | 지정된 펜을 사용하여 일련의 사각형을 그립니다. |
| void [DrawRectangles](./drawrectangles/)(const [SharedPtr](../../system/sharedptr/)\<[Pen](../pen/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\>\&) | 지정된 펜을 사용하여 일련의 사각형을 그립니다. |
| void [DrawString](./drawstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Font](../font/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [PointF](../pointf/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::StringFormat](../stringformat/)\>\&) | 지정된 폰트와 브러시를 사용하여 지정된 위치에 지정된 문자열을 그립니다. |
| void [DrawString](./drawstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Font](../font/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [RectangleF](../rectanglef/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::StringFormat](../stringformat/)\>\&) | 지정된 폰트와 브러시를 사용하여 지정된 사각형 안에 지정된 문자열을 그립니다. |
| void [DrawString](./drawstring/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Font](../font/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**, **float**, const [System::SharedPtr](../../system/sharedptr/)\<[System::Drawing::StringFormat](../stringformat/)\>\&) | 지정된 폰트와 브러시를 사용하여 지정된 위치에 지정된 문자열을 그립니다. |
| void [EndContainer](./endcontainer/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsContainer](../../system.drawing.drawing2d/graphicscontainer/)\>\&) | 현재 컨테이너를 닫고 저장된 컨테이너의 상태로부터 이 객체의 상태를 복원합니다. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 구현되지 않음. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 구현되지 않음. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [Point](../point/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 구현되지 않음. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [PointF](../pointf/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 구현되지 않음. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [Rectangle](../rectangle/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 구현되지 않음. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [RectangleF](../rectanglef/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 구현되지 않음. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [Point](../point/), [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 구현되지 않음. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [PointF](../pointf/), [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 구현되지 않음. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 구현되지 않음. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 구현되지 않음. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [Rectangle](../rectangle/), [Rectangle](../rectangle/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 구현되지 않음. |
| void [EnumerateMetafile](./enumeratemetafile/)(const [SharedPtr](../../system/sharedptr/)\<[Imaging::Metafile](../../system.drawing.imaging/metafile/)\>\&, [RectangleF](../rectanglef/), [RectangleF](../rectanglef/), [GraphicsUnit](../graphicsunit/), [Graphics::EnumerateMetafileProc](./enumeratemetafileproc/)) | 구현되지 않음. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) 의미에 따라 객체를 비교합니다. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 참조 형식 객체를 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 스타일로 값 형식 객체를 비교합니다. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(자신 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989에 따르면 NaN은 어떤 값과도(자신 포함) 같지 않지만, 두 NaN을 동일하게 간주하는 C# 스타일 부동소수점 비교를 에뮬레이트합니다. |
| void [ExcludeClip](./excludeclip/)([Rectangle](../rectangle/)) | 구현되지 않음. |
| void [ExcludeClip](./excludeclip/)(const [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&) | 구현되지 않음. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 내부 용도 전용입니다. |
| void [FillClosedCurve](./fillclosedcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/), **float**) | 지정된 브러시를 사용하여 닫힌 스플라인을 그립니다. |
| void [FillClosedCurve](./fillclosedcurve/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/), **float**) | 지정된 브러시를 사용하여 닫힌 스플라인을 그립니다. |
| void [FillEllipse](./fillellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [Rectangle](../rectangle/)) | 지정된 브러시를 사용하여 경계 사각형으로 지정된 타원의 내부를 채웁니다. |
| void [FillEllipse](./fillellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [RectangleF](../rectanglef/)) | 지정된 브러시를 사용하여 경계 사각형으로 지정된 타원의 내부를 채웁니다. |
| void [FillEllipse](./fillellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, int, int, int, int) | 지정된 브러시를 사용하여 경계 사각형으로 지정된 타원의 내부를 채웁니다. |
| void [FillEllipse](./fillellipse/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**, **float**, **float**, **float**) | 지정된 브러시를 사용하여 경계 사각형으로 지정된 타원의 내부를 채웁니다. |
| void [FillPath](./fillpath/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&) | 지정된 브러시를 사용하여 지정된 경로의 내부를 채웁니다. |
| void [FillPie](./fillpie/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, int, int, int, int, int, int) | 현재 객체가 나타내는 표면에 지정된 브러시를 사용하여 지정된 파이를 채웁니다. |
| void [FillPie](./fillpie/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**, **float**, **float**, **float**, **float**, **float**) | 현재 객체가 나타내는 표면에 지정된 브러시를 사용하여 지정된 파이를 채웁니다. |
| void [FillPie](./fillpie/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [Rectangle](../rectangle/), **float**, **float**) | 현재 객체가 나타내는 표면에 지정된 브러시를 사용하여 지정된 파이를 채웁니다. |
| void [FillPolygon](./fillpolygon/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Point](../point/)\>\&, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/)) | 지정된 브러시를 사용하여 지정된 다각형의 내부를 채웁니다. |
| void [FillPolygon](./fillpolygon/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[PointF](../pointf/)\>\&, [Drawing2D::FillMode](../../system.drawing.drawing2d/fillmode/)) | 지정된 브러시를 사용하여 지정된 다각형의 내부를 채웁니다. |
| void [FillRectangle](./fillrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, **float**, **float**, **float**, **float**) | 지정된 브러시로 지정된 사각형을 채웁니다. |
| void [FillRectangle](./fillrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, int, int, int, int) | 지정된 브러시로 지정된 사각형을 채웁니다. |
| void [FillRectangle](./fillrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [Rectangle](../rectangle/)) | 지정된 브러시로 지정된 사각형을 채웁니다. |
| void [FillRectangle](./fillrectangle/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, [RectangleF](../rectanglef/)) | 지정된 브러시로 지정된 사각형을 채웁니다. |
| void [FillRectangles](./fillrectangles/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[Rectangle](../rectangle/)\>\&) | 지정된 브러시를 사용하여 일련의 사각형을 채웁니다. |
| void [FillRectangles](./fillrectangles/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [ArrayPtr](../../system/arrayptr/)\<[RectangleF](../rectanglef/)\>\&) | 지정된 브러시를 사용하여 일련의 사각형을 채웁니다. |
| void [FillRegion](./fillregion/)(const [SharedPtr](../../system/sharedptr/)\<[Brush](../brush/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&) | 지정된 브러시를 사용하여 지정된 영역의 내부를 채웁니다. |
| void [Flush](./flush/)([Drawing2D::FlushIntention](../../system.drawing.drawing2d/flushintention/)) | 보류 중인 모든 그리기 작업을 즉시 실행하도록 트리거합니다. |
| static [SharedPtr](../../system/sharedptr/)\<[Graphics](./)\> [FromHwnd](./fromhwnd/)(IntPtr) | 구현되지 않음. |
| static [SharedPtr](../../system/sharedptr/)\<[Graphics](./)\> [FromHwndInternal](./fromhwndinternal/)(IntPtr) | 구현되지 않음. |
| static [SharedPtr](../../system/sharedptr/)\<[Graphics](./)\> [FromImage](./fromimage/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | 지정된 이미지에서 새로운 [Graphics](./) 객체를 생성합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\> [get_Clip](./get_clip/)() | 현재 [Graphics](./) 객체가 나타내는 그리기 표면의 그리기 영역을 제한하는 영역을 나타내는 [Region](../region/) 객체를 반환합니다. |
| [RectangleF](../rectanglef/) [get_ClipBounds](./get_clipbounds/)() const | 현재 객체가 나타내는 표면의 클리핑 영역을 경계하는 사각형을 반환합니다. |
| [Drawing2D::CompositingMode](../../system.drawing.drawing2d/compositingmode/) [get_CompositingMode](./get_compositingmode/)() | 현재 객체가 나타내는 표면에 합성된 이미지가 그려지는 방식을 나타내는 값을 반환합니다. |
| [Drawing2D::CompositingQuality](../../system.drawing.drawing2d/compositingquality/) [get_CompositingQuality](./get_compositingquality/)() | 이미지를 합성할 때 사용되는 품질 수준을 나타내는 값을 반환합니다. |
| **float** [get_DpiX](./get_dpix/)() | 가로 해상도를 반환합니다. |
| **float** [get_DpiY](./get_dpiy/)() | 세로 해상도를 반환합니다. |
| [Drawing2D::InterpolationMode](../../system.drawing.drawing2d/interpolationmode/) [get_InterpolationMode](./get_interpolationmode/)() | 현재 객체와 연관된 보간 모드를 나타내는 값을 반환합니다. |
| **bool** [get_IsClipEmpty](./get_isclipempty/)() const | 구현되지 않음. |
| **bool** [get_IsVisibleClipEmpty](./get_isvisibleclipempty/)() const | 구현되지 않음. |
| **float** [get_PageScale](./get_pagescale/)() const | 현재 [Graphics](./) 객체에 대한 세계 단위와 페이지 단위 사이의 스케일링을 반환합니다. |
| [GraphicsUnit](../graphicsunit/) [get_PageUnit](./get_pageunit/)() const | 현재 객체가 나타내는 표면에서 페이지 좌표에 사용되는 측정 단위를 반환합니다. |
| [Drawing2D::PixelOffsetMode](../../system.drawing.drawing2d/pixeloffsetmode/) [get_PixelOffsetMode](./get_pixeloffsetmode/)() | 현재 객체가 나타내는 표면에서 렌더링 중 픽셀 오프셋 방식을 나타내는 값을 반환합니다. |
| [Point](../point/) [get_RenderingOrigin](./get_renderingorigin/)() const | 현재 [Graphics](./) 객체에 대한 디더링 및 해치 브러시용 렌더링 기준점을 나타내는 [Point](../point/) 객체를 반환합니다. |
| [Drawing2D::SmoothingMode](../../system.drawing.drawing2d/smoothingmode/) [get_SmoothingMode](./get_smoothingmode/)() | 현재 객체가 나타내는 표면에서 렌더링 중 사용되는 진정 모드를 나타내는 값을 반환합니다. |
| **int32_t** [get_TextContrast](./get_textcontrast/)() const | 구현되지 않음. |
| [Text::TextRenderingHint](../../system.drawing.text/textrenderinghint/) [get_TextRenderingHint](./get_textrenderinghint/)() | 텍스트 렌더링 품질을 나타내는 값을 반환합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\> [get_Transform](./get_transform/)() | 현재 [Graphics](./) 객체에 대한 기하학적 세계 변환을 반환합니다. |
| [RectangleF](../rectanglef/) [get_VisibleClipBounds](./get_visibleclipbounds/)() const | 현재 [Graphics](./) 객체의 가시 클리핑 영역의 경계 사각형을 나타내는 [RectangleF](../rectanglef/) 객체를 반환합니다. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 객체와 연관된 참조 카운터 데이터 구조를 가져옵니다. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 메서드와 유사합니다. 사용자 정의 객체의 해싱을 가능하게 합니다. |
| IntPtr [GetHdc](./gethdc/)() | 구현되지 않음. |
| [Color](../color/) [GetNearestColor](./getnearestcolor/)([Color](../color/)) | 구현되지 않음. |
| SkCanvas * [GetSkCanvas](./getskcanvas/)() const |  |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 객체의 실제 타입을 가져옵니다. C# [System.Object.GetType()](../../system/object/gettype/) 호출과 유사합니다. |
| void [IntersectClip](./intersectclip/)(const [System::SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&) | 현재 클립과 지정된 클립의 교차 영역으로 이 객체의 클립 영역을 업데이트합니다. |
| void [IntersectClip](./intersectclip/)([System::Drawing::RectangleF](../rectanglef/)) | 현재 클립과 지정된 클립의 교차 영역으로 이 객체의 클립 영역을 업데이트합니다. |
| void [IntersectClip](./intersectclip/)([System::Drawing::Rectangle](../rectangle/)) | 현재 클립과 지정된 클립의 교차 영역으로 이 객체의 클립 영역을 업데이트합니다. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 객체가 targetType으로 설명된 유형의 인스턴스를 나타내는지 확인합니다. C# 'is' 연산자와 유사합니다. |
| **bool** [IsVisible](./isvisible/)([Point](../point/)) | 지정된 점이 현재 [Graphics](./) 객체의 가시 클립 영역에 포함되는지 여부를 판단합니다. |
| **bool** [IsVisible](./isvisible/)([PointF](../pointf/)) | 구현되지 않음. |
| **bool** [IsVisible](./isvisible/)([Rectangle](../rectangle/)) | 구현되지 않음. |
| **bool** [IsVisible](./isvisible/)([RectangleF](../rectanglef/)) | 구현되지 않음. |
| **bool** [IsVisible](./isvisible/)(**int32_t**, **int32_t**) | 구현되지 않음. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**) | 구현되지 않음. |
| **bool** [IsVisible](./isvisible/)(**float**, **float**, **float**, **float**) | 구현되지 않음. |
| **bool** [IsVisible](./isvisible/)(**int32_t**, **int32_t**, **int32_t**, **int32_t**) | 구현되지 않음. |
| void [Lock](../../system/object/lock/)() | C# lock() 문장의 잠금을 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하십시오. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\> [MeasureCharacterRanges](./measurecharacterranges/)(const [System::String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Font](../font/)\>\&, [RectangleF](../rectanglef/), const [SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\>\&) | 지정된 문자열에서 문자 위치를 경계하는 각 영역의 배열을 반환합니다. |
| [SizeF](../sizef/) [MeasureString](./measurestring/)([String](../../system/string/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[Font](../font/)\> const\&, [PointF](../pointf/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\> const\&) const | 지정된 형식으로 지정된 폰트로 그려졌을 때 지정된 문자열의 크기를 반환합니다. |
| [SizeF](../sizef/) [MeasureString](./measurestring/)([String](../../system/string/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[Font](../font/)\> const\&, int, [System::SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\> const\&) const | 지정된 형식과 지정된 폰트로 그려졌을 때 지정된 문자열의 크기를 반환합니다. |
| [SizeF](../sizef/) [MeasureString](./measurestring/)([String](../../system/string/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[Font](../font/)\> const\&, [SizeF](../sizef/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\> const\&, int\&, int\&) const | 구현되지 않음. |
| [SizeF](../sizef/) [MeasureString](./measurestring/)([String](../../system/string/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[Font](../font/)\> const\&, [SizeF](../sizef/) const\&, [System::SharedPtr](../../system/sharedptr/)\<[StringFormat](../stringformat/)\> const\&) const | 지정된 형식과 지정된 폰트로 그려졌을 때 지정된 문자열의 크기를 반환합니다. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 메서드와 유사합니다. 사용자 정의 형식의 복제를 가능하게 합니다. |
| void [MultiplyTransform](./multiplytransform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | 현재 [Graphics](./) 객체의 월드 변환 행렬에 지정된 행렬을 곱합니다. |
|  [Object](../../system/object/object/)() | 객체를 생성합니다. 모든 내부 데이터 구조를 초기화합니다. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 복사 생성자입니다. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하고 서브클래스의 복사 생성을 가능하게 합니다. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 대입 연산자입니다. 실제로는 아무 것도 복사하지 않고, 새 객체를 초기화하고 서브클래스의 복사 생성을 가능하게 합니다. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 객체를 레퍼런스로 비교합니다. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 값 유형 객체를 nullptr와 레퍼런스로 비교합니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 및 nullptr 경우에 대한 특수화입니다. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)의 문자열 경우에 대한 특수화입니다. |
| void [ReleaseHdc](./releasehdc/)() | 구현되지 않음. |
| void [ReleaseHdc](./releasehdc/)(IntPtr) | 구현되지 않음. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 지정된 값만큼 공유 참조 카운트를 감소시킵니다. |
| void [ResetClip](./resetclip/)() | 이 그래픽스의 클립 영역을 무한 영역으로 재설정합니다. |
| void [ResetTransform](./resettransform/)() | 현재 객체의 월드 변환 행렬을 단위 행렬이 되도록 재설정합니다. |
| void [Restore](./restore/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsState](../../system.drawing.drawing2d/graphicsstate/)\>\&) | 저장된 상태에서 이 객체의 상태를 복원합니다. |
| void [RotateTransform](./rotatetransform/)(**float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | 지정된 순서대로 현재 [Graphics](./) 객체의 월드 변환 행렬에 지정된 회전을 적용합니다. |
| [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsState](../../system.drawing.drawing2d/graphicsstate/)\> [Save](./save/)() | 현재 이 객체의 상태를 저장하고 저장된 상태를 반환합니다. |
| void [ScaleTransform](./scaletransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | 지정된 스케일 벡터를 현재 객체의 월드 변환 행렬에 적용합니다. |
| void [set_Clip](./set_clip/)(const [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&) | 현재가 나타내는 그리기 표면의 그리기 영역을 제한하는 영역을 설정합니다. |
| void [set_CompositingMode](./set_compositingmode/)([Drawing2D::CompositingMode](../../system.drawing.drawing2d/compositingmode/)) | 현재 객체가 나타내는 표면에 합성된 이미지가 그려지는 방식을 지정하는 값을 설정합니다. |
| void [set_CompositingQuality](./set_compositingquality/)([Drawing2D::CompositingQuality](../../system.drawing.drawing2d/compositingquality/)) | 이미지를 합성할 때 사용할 품질 수준을 지정하는 값을 설정합니다. |
| void [set_InterpolationMode](./set_interpolationmode/)([Drawing2D::InterpolationMode](../../system.drawing.drawing2d/interpolationmode/)) | 현재 객체와 연관된 보간 모드를 나타내는 값을 설정합니다. |
| void [set_PageScale](./set_pagescale/)(**float**) | 현재 [Graphics](./) 객체에 대한 월드 단위와 페이지 단위 사이의 스케일을 설정합니다. |
| void [set_PageUnit](./set_pageunit/)([GraphicsUnit](../graphicsunit/)) | 현재 객체가 나타내는 표면의 페이지 좌표에 사용되는 측정 단위를 설정합니다. |
| void [set_PixelOffsetMode](./set_pixeloffsetmode/)([Drawing2D::PixelOffsetMode](../../system.drawing.drawing2d/pixeloffsetmode/)) | 현재 객체가 나타내는 표면에서 렌더링 중 픽셀 오프셋 방식을 지정하는 값을 설정합니다. |
| void [set_RenderingOrigin](./set_renderingorigin/)([Point](../point/)) | 디더링 및 해치 브러시용 현재 [Graphics](./) 객체의 렌더링 원점을 지정하는 [Point](../point/) 객체를 설정합니다. |
| void [set_SmoothingMode](./set_smoothingmode/)([Drawing2D::SmoothingMode](../../system.drawing.drawing2d/smoothingmode/)) | 현재 객체가 나타내는 표면에서 렌더링 중에 사용되는 진정 모드를 지정하는 값을 설정합니다. |
| void [set_TextContrast](./set_textcontrast/)(**int32_t**) | 구현되지 않음. |
| void [set_TextRenderingHint](./set_textrenderinghint/)([Text::TextRenderingHint](../../system.drawing.text/textrenderinghint/)) | 텍스트 렌더링 품질을 지정하는 값을 설정합니다. |
| void [set_Transform](./set_transform/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::Matrix](../../system.drawing.drawing2d/matrix/)\>\&) | 현재 [Graphics](./) 객체에 대한 기하학적 월드 변환을 설정합니다. |
| void [SetClip](./setclip/)(const [SharedPtr](../../system/sharedptr/)\<[Region](../region/)\>\&, [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | 현재 [Graphics](./) 객체가 나타내는 그리기 표면의 클리핑 영역을 현재 클립 영역과 지정된 영역을 결합하는 지정된 연산 결과로 설정합니다. |
| void [SetClip](./setclip/)([Rectangle](../rectangle/), [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | 현재 [Graphics](./) 객체가 나타내는 그리기 표면의 클리핑 영역을 현재 클립 영역과 지정된 영역을 결합하는 지정된 연산 결과로 설정합니다. |
| void [SetClip](./setclip/)([RectangleF](../rectanglef/), [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | 현재 [Graphics](./) 객체가 나타내는 그리기 표면의 클리핑 영역을 현재 클립 영역과 지정된 영역을 결합하는 지정된 연산 결과로 설정합니다. |
| void [SetClip](./setclip/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](./)\>\&, [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | 구현되지 않음. |
| void [SetClip](./setclip/)(const [SharedPtr](../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../system.drawing.drawing2d/graphicspath/)\>\&, [Drawing2D::CombineMode](../../system.drawing.drawing2d/combinemode/)) | 현재 [Graphics](./) 객체가 나타내는 그리기 표면의 클리핑 영역을 현재 클립 영역과 그래픽 경로가 지정한 영역을 결합하는 지정된 연산 결과로 설정합니다. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n번째 템플릿 인자를 약한 포인터(공유가 아닌)로 설정합니다. 컨테이너의 포인터를 약한 모드로 전환할 수 있습니다. |
| int [SharedCount](../../system/object/sharedcount/)() const | 현재 공유 참조 카운터 값을 가져옵니다. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 공유 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 공유 참조 카운트를 감소시키고 반환합니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 메서드와 유사합니다. 사용자 정의 객체를 문자열로 변환할 수 있게 합니다. |
| void [TransformPoints](./transformpoints/)([Drawing2D::CoordinateSpace](../../system.drawing.drawing2d/coordinatespace/), [Drawing2D::CoordinateSpace](../../system.drawing.drawing2d/coordinatespace/), const [ArrayPtr](../../system/arrayptr/)\<[System::Drawing::Point](../point/)\>\&) | 구현되지 않음. |
| void [TransformPoints](./transformpoints/)([Drawing2D::CoordinateSpace](../../system.drawing.drawing2d/coordinatespace/), [Drawing2D::CoordinateSpace](../../system.drawing.drawing2d/coordinatespace/), const [ArrayPtr](../../system/arrayptr/)\<[System::Drawing::PointF](../pointf/)\>\&) | 구현되지 않음. |
| void [TranslateClip](./translateclip/)(int, int) | 구현되지 않음. |
| void [TranslateClip](./translateclip/)(**float**, **float**) | 구현되지 않음. |
| void [TranslateTransform](./translatetransform/)(**float**, **float**, [Drawing2D::MatrixOrder](../../system.drawing.drawing2d/matrixorder/)) | 지정된 평행 이동 벡터를 현재 [Graphics](./) 객체의 월드 변환 행렬에 적용합니다. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 구문을 구현합니다. |
| void [Unlock](../../system/object/unlock/)() | C# lock() 구문의 잠금 해제를 구현합니다. 직접 호출하거나 [LockContext](../../system/lockcontext/) 센트리 객체를 사용하세요. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 약한 참조 카운트를 증가시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 약한 참조 카운트를 감소시킵니다. 직접 호출해서는 안 되며, 대신 스마트 포인터나 ThisProtector를 사용하세요. |
|  [~Graphics](./~graphics/)() |  |
| virtual  [~Object](../../system/object/~object/)() | 객체를 파괴합니다. 모든 내부 데이터 구조를 해제합니다. |

## 타입 정의

| 타입 정의 | 설명 |
| --- | --- |
| [EnumerateMetafileProc](./enumeratemetafileproc/) | EnumerateMetafile 메서드의 인수로 사용되는 콜백 함수 객체의 타입입니다. |
| [DrawImageAbort](./drawimageabort/) | DrawImage 메서드의 인수로 사용되는 콜백 함수 객체의 타입입니다. |

## 관련 항목

* 클래스 [Object](../../system/object/)
* 네임스페이스 [System::Drawing](../)
* 라이브러리 [Aspose.Slides](../../)