---
title: DrawPie()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 표면에 지정된 펜을 사용하여 지정된 파이를 그립니다.
type: docs
weight: 261
url: /ko/system.drawing/graphics/drawpie/
---
## Graphics::DrawPie(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) method

현재 객체가 나타내는 표면에 지정된 펜을 사용하여 지정된 파이를 그립니다.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 파이를 그릴 때 사용할 펜 |
| x | **int32_t** | 타원을 정의하는 사각형의 왼쪽 위 모서리의 X 좌표 |
| y | **int32_t** | 타원을 정의하는 사각형의 왼쪽 위 모서리의 Y 좌표 |
| width | **int32_t** | 타원을 정의하는 사각형의 너비 |
| height | **int32_t** | 타원을 정의하는 사각형의 높이 |
| startAngle | **int32_t** | 시계 방향으로 X축에서 파이의 시작점까지 측정한 각도(도) |
| sweepAngle | **int32_t** | 시계 방향으로 **startAngle**에서 파이의 끝점까지 측정한 각도(도) |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) method

현재 객체가 나타내는 표면에 지정된 펜을 사용하여 지정된 파이를 그립니다.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 파이를 그릴 때 사용할 펜 |
| x | **float** | 타원을 정의하는 사각형의 왼쪽 위 모서리의 X 좌표 |
| y | **float** | 타원을 정의하는 사각형의 왼쪽 위 모서리의 Y 좌표 |
| width | **float** | 타원을 정의하는 사각형의 너비 |
| height | **float** | 타원을 정의하는 사각형의 높이 |
| startAngle | **float** | 시계 방향으로 X축에서 파이의 시작점까지 측정한 각도(도) |
| sweepAngle | **float** | 시계 방향으로 **startAngle**에서 파이의 끝점까지 측정한 각도(도) |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, Rectangle, float, float) method

현재 객체가 나타내는 표면에 지정된 펜을 사용하여 지정된 파이를 그립니다.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 파이를 그릴 때 사용할 펜 |
| rect | [Rectangle](../../rectangle/) | 타원을 정의하는 사각형 |
| startAngle | **float** | 시계 방향으로 X축에서 파이의 시작점까지 측정한 각도(도) |
| sweepAngle | **float** | 시계 방향으로 **startAngle**에서 파이의 끝점까지 측정한 각도(도) |

## Graphics::DrawPie(const SharedPtr\<Pen\>\&, RectangleF, float, float) method

현재 객체가 나타내는 표면에 지정된 펜을 사용하여 지정된 파이를 그립니다.

```cpp
void System::Drawing::Graphics::DrawPie(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 파이를 그릴 때 사용할 펜 |
| rect | [RectangleF](../../rectanglef/) | 타원을 정의하는 사각형 |
| startAngle | **float** | 시계 방향으로 X축에서 파이의 시작점까지 측정한 각도(도) |
| sweepAngle | **float** | 시계 방향으로 **startAngle**에서 파이의 끝점까지 측정한 각도(도) |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)