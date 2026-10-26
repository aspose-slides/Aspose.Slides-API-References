---
title: DrawArc()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 표면에 지정된 펜을 사용하여 지정된 호를 그립니다.
type: docs
weight: 248
url: /ko/system.drawing/graphics/drawarc/
---
## Graphics::DrawArc(const SharedPtr\<Pen\>\&, int32_t, int32_t, int32_t, int32_t, int32_t, int32_t) 메서드

현재 객체가 나타내는 표면에 지정된 펜을 사용하여 지정된 호를 그립니다.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, int32_t x, int32_t y, int32_t width, int32_t height, int32_t startAngle, int32_t sweepAngle)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 호를 그릴 때 사용할 펜 |
| x | **int32_t** | 타원을 정의하는 사각형의 왼쪽 위 모서리 X 좌표 |
| y | **int32_t** | 타원을 정의하는 사각형의 왼쪽 위 모서리 Y 좌표 |
| width | **int32_t** | 타원을 정의하는 사각형의 너비 |
| height | **int32_t** | 타원을 정의하는 사각형의 높이 |
| startAngle | **int32_t** | X 축에서 시계 방향으로 측정한 각도(도)이며, 호의 시작 지점을 나타냅니다 |
| sweepAngle | **int32_t** | **startAngle**에서 시계 방향으로 측정한 각도(도)이며, 호의 끝 지점을 나타냅니다 |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, float, float, float, float, float, float) 메서드

현재 객체가 나타내는 표면에 지정된 펜을 사용하여 지정된 호를 그립니다.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 호를 그릴 때 사용할 펜 |
| x | **float** | 타원을 정의하는 사각형의 왼쪽 위 모서리 X 좌표 |
| y | **float** | 타원을 정의하는 사각형의 왼쪽 위 모서리 Y 좌표 |
| width | **float** | 타원을 정의하는 사각형의 너비 |
| height | **float** | 타원을 정의하는 사각형의 높이 |
| startAngle | **float** | X 축에서 시계 방향으로 측정한 각도(도)이며, 호의 시작 지점을 나타냅니다 |
| sweepAngle | **float** | **startAngle**에서 시계 방향으로 측정한 각도(도)이며, 호의 끝 지점을 나타냅니다 |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, Rectangle, float, float) 메서드

현재 객체가 나타내는 표면에 지정된 펜을 사용하여 지정된 호를 그립니다.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, Rectangle rect, float startAngle, float sweepAngle)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 호를 그릴 때 사용할 펜 |
| rect | [Rectangle](../../rectangle/) | 타원을 정의하는 사각형 |
| startAngle | **float** | X 축에서 시계 방향으로 측정한 각도(도)이며, 호의 시작 지점을 나타냅니다 |
| sweepAngle | **float** | **startAngle**에서 시계 방향으로 측정한 각도(도)이며, 호의 끝 지점을 나타냅니다 |

## Graphics::DrawArc(const SharedPtr\<Pen\>\&, RectangleF, float, float) 메서드

현재 객체가 나타내는 표면에 지정된 펜을 사용하여 지정된 호를 그립니다.

```cpp
void System::Drawing::Graphics::DrawArc(const SharedPtr<Pen> &pen, RectangleF rect, float startAngle, float sweepAngle)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 호를 그릴 때 사용할 펜 |
| rect | [RectangleF](../../rectanglef/) | 타원을 정의하는 사각형 |
| startAngle | **float** | X 축에서 시계 방향으로 측정한 각도(도)이며, 호의 시작 지점을 나타냅니다 |
| sweepAngle | **float** | **startAngle**에서 시계 방향으로 측정한 각도(도)이며, 호의 끝 지점을 나타냅니다 |

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Pen](../../pen/)
* 클래스 [Graphics](../)
* 클래스 [Rectangle](../../rectangle/)
* 클래스 [RectangleF](../../rectanglef/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)