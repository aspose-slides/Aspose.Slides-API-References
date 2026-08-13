---
title: Intersect()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 영역을 지정된 사각형에 의해 정의된 영역과의 교차 결과로 교체합니다.
type: docs
weight: 79
url: /ko/system.drawing/region/intersect/
---
## Region::Intersect(const RectangleF\&) 메서드

현재 객체가 나타내는 영역을 지정된 사각형에 의해 정의된 영역과의 교차 결과로 교체합니다.

```cpp
void System::Drawing::Region::Intersect(const RectangleF &rect)
```

### 매개변수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 이 영역과 교차하도록 정의된 사각형 |

## Region::Intersect(const Rectangle\&) 메서드

현재 객체가 나타내는 영역을 지정된 사각형에 의해 정의된 영역과의 교차 결과로 교체합니다.

```cpp
void System::Drawing::Region::Intersect(const Rectangle &rect)
```

### 매개변수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 이 영역과 교차하도록 정의된 사각형 |

## Region::Intersect(const SharedPtr\<Drawing2D::GraphicsPath\>\&) 메서드

현재 객체가 나타내는 영역을 지정된 경로에 의해 정의된 영역과의 교차 결과로 교체합니다.

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### 매개변수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 이 영역과 교차하도록 정의된 경로 |

## Region::Intersect(const SharedPtr\<Region\>\&) 메서드

현재 객체가 나타내는 영역을 지정된 영역과의 교차 결과로 교체합니다.

```cpp
void System::Drawing::Region::Intersect(const SharedPtr<Region> &region)
```

### 매개변수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 이 영역과 교차하도록 정의된 영역 |

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [RectangleF](../../rectanglef/)
* 클래스 [Region](../)
* 클래스 [Rectangle](../../rectangle/)
* 클래스 [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)