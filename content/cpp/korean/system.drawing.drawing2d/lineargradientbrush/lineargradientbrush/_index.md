---
title: LinearGradientBrush()
second_title: Aspose.Slides for C++ API 레퍼런스
description: LinearGradientBrush의 새 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system.drawing.drawing2d/lineargradientbrush/lineargradientbrush/
---
## LinearGradientBrush::LinearGradientBrush(const PointF\&, const PointF\&, const Color\&, const Color\&) constructor

[LinearGradientBrush](../)의 새 인스턴스를 생성합니다.

```cpp
System::Drawing::Drawing2D::LinearGradientBrush::LinearGradientBrush(const PointF &point1, const PointF &point2, const Color &color1, const Color &color2)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point1 | const [PointF](../../../system.drawing/pointf/)\& | 그라디언트의 시작점 |
| point2 | const [PointF](../../../system.drawing/pointf/)\& | 그라디언트의 끝점 |
| color1 | const [Color](../../../system.drawing/color/)\& | 그라디언트의 시작 색상 |
| color2 | const [Color](../../../system.drawing/color/)\& | 그라디언트의 끝 색상 |

## LinearGradientBrush::LinearGradientBrush(const Point\&, const Point\&, const Color\&, const Color\&) constructor

[LinearGradientBrush](../)의 새 인스턴스를 생성합니다.

```cpp
System::Drawing::Drawing2D::LinearGradientBrush::LinearGradientBrush(const Point &point1, const Point &point2, const Color &color1, const Color &color2)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point1 | const [Point](../../../system.drawing/point/)\& | 그라디언트의 시작점 |
| point2 | const [Point](../../../system.drawing/point/)\& | 그라디언트의 끝점 |
| color1 | const [Color](../../../system.drawing/color/)\& | 그라디언트의 시작 색상 |
| color2 | const [Color](../../../system.drawing/color/)\& | 그라디언트의 끝 색상 |

## LinearGradientBrush::LinearGradientBrush(const RectangleF\&, const Color\&, const Color\&, LinearGradientMode) constructor

[LinearGradientBrush](../)의 새 인스턴스를 생성합니다.

```cpp
System::Drawing::Drawing2D::LinearGradientBrush::LinearGradientBrush(const RectangleF &rect, const Color &color1, const Color &color2, LinearGradientMode linearGradientMode)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [RectangleF](../../../system.drawing/rectanglef/)\& | 그라디언트의 경계 사각형 |
| color1 | const [Color](../../../system.drawing/color/)\& | 그라디언트의 시작 색상 |
| color2 | const [Color](../../../system.drawing/color/)\& | 그라디언트의 끝 색상 |
| linearGradientMode | [LinearGradientMode](../../lineargradientmode/) | 그라디언트 방향 |

## LinearGradientBrush::LinearGradientBrush(const Rectangle\&, const Color\&, const Color\&, LinearGradientMode) constructor

[LinearGradientBrush](../)의 새 인스턴스를 생성합니다.

```cpp
System::Drawing::Drawing2D::LinearGradientBrush::LinearGradientBrush(const Rectangle &rect, const Color &color1, const Color &color2, LinearGradientMode linearGradientMode)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | 그라디언트의 경계 사각형 |
| color1 | const [Color](../../../system.drawing/color/)\& | 그라디언트의 시작 색상 |
| color2 | const [Color](../../../system.drawing/color/)\& | 그라디언트의 끝 색상 |
| linearGradientMode | [LinearGradientMode](../../lineargradientmode/) | 그라디언트 방향 |

## LinearGradientBrush::LinearGradientBrush(const RectangleF\&, const Color\&, const Color\&, float, bool) constructor

[LinearGradientBrush](../)의 새 인스턴스를 생성합니다.

```cpp
System::Drawing::Drawing2D::LinearGradientBrush::LinearGradientBrush(const RectangleF &rect, const Color &color1, const Color &color2, float angle, bool isAngleScaleable=false)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [RectangleF](../../../system.drawing/rectanglef/)\& | 그라디언트의 경계 사각형 |
| color1 | const [Color](../../../system.drawing/color/)\& | 그라디언트의 시작 색상 |
| color2 | const [Color](../../../system.drawing/color/)\& | 그라디언트의 끝 색상 |
| angle | **float** | 그라디언트 방향선의 각도(단위: 도, x축에서 시계 방향) |
| isAngleScaleable | **bool** | 브러시와 연결된 변환에 따라 그라디언트 각도가 영향을 받는지 여부를 지정합니다 |

## LinearGradientBrush::LinearGradientBrush(const Rectangle\&, const Color\&, const Color\&, float, bool) constructor

[LinearGradientBrush](../)의 새 인스턴스를 생성합니다.

```cpp
System::Drawing::Drawing2D::LinearGradientBrush::LinearGradientBrush(const Rectangle &rect, const Color &color1, const Color &color2, float angle, bool isAngleScaleable=false)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | 그라디언트의 경계 사각형 |
| color1 | const [Color](../../../system.drawing/color/)\& | 그라디언트의 시작 색상 |
| color2 | const [Color](../../../system.drawing/color/)\& | 그라디언트의 끝 색상 |
| angle | **float** | 그라디언트 방향선의 각도(단위: 도, x축에서 시계 방향) |
| isAngleScaleable | **bool** | 브러시와 연결된 변환에 따라 그라디언트 각도가 영향을 받는지 여부를 지정합니다 |

## 또 보기

* Enum [LinearGradientMode](../../lineargradientmode/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [Color](../../../system.drawing/color/)
* Class [LinearGradientBrush](../)
* Class [Point](../../../system.drawing/point/)
* Class [RectangleF](../../../system.drawing/rectanglef/)
* Class [Rectangle](../../../system.drawing/rectangle/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)