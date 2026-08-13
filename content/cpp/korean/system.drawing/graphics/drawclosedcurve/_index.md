---
title: DrawClosedCurve()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 펜을 사용하여 닫힌 스플라인을 그립니다.
type: docs
weight: 781
url: /ko/system.drawing/graphics/drawclosedcurve/
---
## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<Point\>\&, float, Drawing2D::FillMode) 메서드

지정된 펜을 사용하여 닫힌 스플라인을 그립니다.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<Point> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 스플라인을 그릴 때 사용할 펜 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | 스플라인을 결정하는 포인트의 [Array](../../../system/array/) |
| tension | **float** | 스플라인의 장력을 지정하는 값 |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | 무시됨 |

## Graphics::DrawClosedCurve(const SharedPtr\<Pen\>\&, const ArrayPtr\<PointF\>\&, float, Drawing2D::FillMode) 메서드

지정된 펜을 사용하여 닫힌 스플라인을 그립니다.

```cpp
void System::Drawing::Graphics::DrawClosedCurve(const SharedPtr<Pen> &pen, const ArrayPtr<PointF> &points, float tension=0.5f, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 스플라인을 그릴 때 사용할 펜 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | 스플라인을 결정하는 포인트의 [Array](../../../system/array/) |
| tension | **float** | 스플라인의 장력을 지정하는 값 |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | 무시됨 |

## 참고

* 열거형 [FillMode](../../../system.drawing.drawing2d/fillmode/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [Pen](../../pen/)
* 클래스 [Point](../../point/)
* 클래스 [Graphics](../)
* 클래스 [PointF](../../pointf/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)