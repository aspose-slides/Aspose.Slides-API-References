---
title: PathGradientBrush()
second_title: Aspose.Slides for C++ API 레퍼런스
description: PathGradientBrush 클래스의 새 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system.drawing.drawing2d/pathgradientbrush/pathgradientbrush/
---
## PathGradientBrush::PathGradientBrush(const ArrayPtr\<PointF\>\&, WrapMode) 생성자

새로운 [PathGradientBrush](../) 클래스 인스턴스를 생성합니다.

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const ArrayPtr<PointF> &points, WrapMode wrapMode=WrapMode::Clamp)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | 경로의 정점을 포함하는 배열 |
| wrapMode | [WrapMode](../../wrapmode/) | 생성 중인 객체가 나타내는 브러시로 그린 채우기가 어떻게 타일링될지 지정합니다 |

## PathGradientBrush::PathGradientBrush(const ArrayPtr\<Point\>\&, WrapMode) 생성자

새로운 [PathGradientBrush](../) 클래스 인스턴스를 생성합니다.

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const ArrayPtr<Point> &points, WrapMode wrapMode=WrapMode::Clamp)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | 경로의 정점을 포함하는 배열 |
| wrapMode | [WrapMode](../../wrapmode/) | 생성 중인 객체가 나타내는 브러시로 그린 채우기가 어떻게 타일링될지 지정합니다 |

## PathGradientBrush::PathGradientBrush(const SharedPtr\<GraphicsPath\>\&) 생성자

새로운 [PathGradientBrush](../) 클래스 인스턴스를 생성합니다.

```cpp
System::Drawing::Drawing2D::PathGradientBrush::PathGradientBrush(const SharedPtr<GraphicsPath> &path)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | 생성된 객체가 채우는 경로를 지정하는 [GraphicsPath](../../graphicspath/) 객체 |

## 참고

* Enum [WrapMode](../../wrapmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [PointF](../../../system.drawing/pointf/)
* Class [PathGradientBrush](../)
* Class [Point](../../../system.drawing/point/)
* Class [GraphicsPath](../../graphicspath/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)