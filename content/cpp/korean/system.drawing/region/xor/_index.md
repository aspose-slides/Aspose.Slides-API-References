---
title: Xor()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 영역을 이 영역과 지정된 직사각형이 정의하는 영역 중 교차하지 않는 부분으로 교체합니다.
type: docs
weight: 144
url: /ko/system.drawing/region/xor/
---
## Region::Xor(const RectangleF\&) 메서드

현재 객체가 나타내는 영역을 이 영역과 지정된 직사각형이 정의하는 영역 중 교차하지 않는 부분으로 교체합니다.

```cpp
void System::Drawing::Region::Xor(const RectangleF &rect)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [RectangleF](../../rectanglef/)\& | 현재 객체가 나타내는 영역과 xor 연산을 수행하기 위해 영역을 정의하는 직사각형 |

## Region::Xor(const Rectangle\&) 메서드

현재 객체가 나타내는 영역을 이 영역과 지정된 직사각형이 정의하는 영역 중 교차하지 않는 부분으로 교체합니다.

```cpp
void System::Drawing::Region::Xor(const Rectangle &rect)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | 현재 객체가 나타내는 영역과 xor 연산을 수행하기 위해 영역을 정의하는 직사각형 |

## Region::Xor(const SharedPtr\<Drawing2D::GraphicsPath\>\&) 메서드

현재 객체가 나타내는 영역을 이 영역과 지정된 경로가 정의하는 영역 중 교차하지 않는 부분으로 교체합니다.

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Drawing2D::GraphicsPath> &path)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | 현재 객체가 나타내는 영역과 xor 연산을 수행하기 위해 영역을 정의하는 경로 |

## Region::Xor(const SharedPtr\<Region\>\&) 메서드

현재 객체가 나타내는 영역을 이 영역과 지정된 영역이 교차하지 않는 부분으로 교체합니다.

```cpp
void System::Drawing::Region::Xor(const SharedPtr<Region> &region)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 현재 객체가 나타내는 영역과 xor 연산을 수행하기 위해 사용되는 영역 |

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [RectangleF](../../rectanglef/)
* 클래스 [Region](../)
* 클래스 [Rectangle](../../rectangle/)
* 클래스 [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)