---
title: GraphicsPath()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 fill mode로 GraphicsPath 클래스를 새 인스턴스로 생성합니다.
type: docs
weight: 1
url: /ko/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) 생성자

지정된 채우기 모드로 [GraphicsPath](../) 클래스의 새 인스턴스를 생성합니다.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```

### Arguments

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | 생성된 객체가 나타내는 닫힌 경로의 내부가 어떻게 채워져야 하는지를 지정합니다 |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) 생성자

지정된 경로를 나타내는 [GraphicsPath](../) 객체의 새 인스턴스를 생성합니다.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### Arguments

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | 생성된 객체가 나타내는 경로를 지정하는 포인트를 포함하는 배열 |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | **pts** 배열에서 해당 점들의 유형을 지정하는 값을 포함하는 배열 |
| fillMode | [FillMode](../../fillmode/) | 생성된 객체가 나타내는 닫힌 경로의 내부가 어떻게 채워져야 하는지를 지정합니다 |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) 생성자

지정된 경로를 나타내는 [GraphicsPath](../) 객체의 새 인스턴스를 생성합니다.

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```

### Arguments

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | 생성된 객체가 나타내는 경로를 지정하는 포인트를 포함하는 배열 |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | **pts** 배열에서 해당 점들의 유형을 지정하는 값을 포함하는 배열 |
| fillMode | [FillMode](../../fillmode/) | 생성된 객체가 나타내는 닫힌 경로의 내부가 어떻게 채워져야 하는지를 지정합니다 |

## GraphicsPath::GraphicsPath(const SkPath\&) 생성자

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## 참조

* Enum [FillMode](../../fillmode/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [GraphicsPath](../)
* Class [Point](../../../system.drawing/point/)
* Class [PointF](../../../system.drawing/pointf/)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)