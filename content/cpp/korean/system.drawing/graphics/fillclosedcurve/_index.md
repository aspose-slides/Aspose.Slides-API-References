---
title: FillClosedCurve()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 브러시를 사용하여 닫힌 스플라인을 그립니다.
type: docs
weight: 807
url: /ko/system.drawing/graphics/fillclosedcurve/
---
## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode, float) 메서드

지정된 브러시를 사용하여 닫힌 스플라인을 그립니다.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 스플라인을 그릴 때 사용할 브러시 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | [Array](../../../system/array/) 스플라인을 결정하는 포인트 |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORED |
| tension | **float** | 스플라인의 장력을 지정하는 값 |

## Graphics::FillClosedCurve(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode, float) 메서드

지정된 브러시를 사용하여 닫힌 스플라인을 그립니다.

```cpp
void System::Drawing::Graphics::FillClosedCurve(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillmode=Drawing2D::FillMode::Alternate, float tension=0.5f)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 스플라인을 그릴 때 사용할 브러시 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | [Array](../../../system/array/) 스플라인을 결정하는 포인트 |
| fillmode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | IGNORED |
| tension | **float** | 스플라인의 장력을 지정하는 값 |

## 참고

* 열거형 [FillMode](../../../system.drawing.drawing2d/fillmode/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [Brush](../../brush/)
* 클래스 [PointF](../../pointf/)
* 클래스 [Graphics](../)
* 클래스 [Point](../../point/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)