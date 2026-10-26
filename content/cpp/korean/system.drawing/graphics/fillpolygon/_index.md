---
title: FillPolygon()
second_title: Aspose.Slides C++ API 레퍼런스
description: 지정된 브러시를 사용하여 지정된 다각형의 내부를 채웁니다.
type: docs
weight: 417
url: /ko/system.drawing/graphics/fillpolygon/
---
## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<Point\>\&, Drawing2D::FillMode) method


지정된 브러시를 사용하여 지정된 다각형의 내부를 채웁니다.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<Point> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 채우기 매개변수를 지정하는 [Brush](../../brush/) 객체 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | 다각형을 정의하는 점들을 포함하는 배열 |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | 채우기 모드 |

## Graphics::FillPolygon(const SharedPtr\<Brush\>\&, const ArrayPtr\<PointF\>\&, Drawing2D::FillMode) method


지정된 브러시를 사용하여 지정된 다각형의 내부를 채웁니다.

```cpp
void System::Drawing::Graphics::FillPolygon(const SharedPtr<Brush> &brush, const ArrayPtr<PointF> &points, Drawing2D::FillMode fillMode=Drawing2D::FillMode::Alternate)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | 채우기 매개변수를 지정하는 [Brush](../../brush/) 객체 |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | 다각형을 정의하는 점들을 포함하는 배열 |
| fillMode | [Drawing2D::FillMode](../../../system.drawing.drawing2d/fillmode/) | 채우기 모드 |

## 참고

* Enum [FillMode](../../../system.drawing.drawing2d/fillmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [Brush](../../brush/)
* 클래스 [Point](../../point/)
* 클래스 [Graphics](../)
* 클래스 [PointF](../../pointf/)
* 네임스페이스 [System::Drawing](../../)
* Library [Aspose.Slides](../../../)