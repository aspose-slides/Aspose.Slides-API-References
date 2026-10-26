---
title: Union()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 영역을 이 영역과 지정된 사각형으로 정의된 영역의 합집합 연산 결과로 교체합니다.
type: docs
weight: 53
url: /ko/system.drawing/region/union/
---
## Region::Union(const RectangleF\&) 메서드

현재 객체가 나타내는 영역을 이 영역과 지정된 사각형으로 정의된 영역의 합집합 연산 결과로 교체합니다.

```cpp
void System::Drawing::Region::Union(const RectangleF &rect)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 이 영역과 결합할 영역을 정의하는 사각형 |

## Region::Union(const Rectangle\&) 메서드

현재 객체가 나타내는 영역을 이 영역과 지정된 사각형으로 정의된 영역의 합집합 결과로 교체합니다.

```cpp
void System::Drawing::Region::Union(const Rectangle &rect)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 이 영역과 결합할 영역을 정의하는 사각형 |

## Region::Union(const SharedPtr\<Drawing2D::GraphicsPath\>\&) 메서드

현재 객체가 나타내는 영역을 이 영역과 지정된 경로로 정의된 영역의 합집합 결과로 교체합니다.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 이 영역과 결합할 영역을 정의하는 경로 |

## Region::Union(const SharedPtr\<Region\>\&) 메서드

현재 객체가 나타내는 영역을 이 영역과 지정된 영역의 합집합 결과로 교체합니다.

```cpp
void System::Drawing::Region::Union(const SharedPtr<Region> &region)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 이 영역과 결합할 영역 |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [RectangleF](../../rectanglef/)
* 클래스 [Region](../)
* 클래스 [Rectangle](../../rectangle/)
* 클래스 [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)