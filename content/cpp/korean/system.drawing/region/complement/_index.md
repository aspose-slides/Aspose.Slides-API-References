---
title: Complement()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 영역을 지정된 사각형으로 정의된 영역 중 이 영역과 교차하지 않는 부분으로 교체합니다.
type: docs
weight: 131
url: /ko/system.drawing/region/complement/
---
## Region::Complement(const RectangleF\&) 메서드

현재 객체가 나타내는 영역을 지정된 recangle으로 정의된 영역 중 이 영역과 교차하지 않는 부분으로 교체합니다.

```cpp
void System::Drawing::Region::Complement(const RectangleF &rect)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 보완할 영역을 정의하는 사각형 |

## Region::Complement(const Rectangle\&) 메서드

현재 객체가 나타내는 영역을 지정된 recangle으로 정의된 영역 중 이 영역과 교차하지 않는 부분으로 교체합니다.

```cpp
void System::Drawing::Region::Complement(const Rectangle &rect)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 보완할 영역을 정의하는 사각형 |

## Region::Complement(const SharedPtr\<Drawing2D::GraphicsPath\>\&) 메서드

현재 객체가 나타내는 영역을 지정된 경로로 정의된 영역 중 이 영역과 교차하지 않는 부분으로 교체합니다.

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 보완할 영역을 정의하는 경로 |

## Region::Complement(const SharedPtr\<Region\>\&) 메서드

현재 객체가 나타내는 영역을 지정된 영역 중 이 영역과 교차하지 않는 부분으로 교체합니다.

```cpp
void System::Drawing::Region::Complement(const SharedPtr<Region> &region)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 보완할 영역 |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RectangleF](../../rectanglef/)
* Class [Region](../)
* Class [Rectangle](../../rectangle/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)