---
title: FillPie()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 표면에 지정된 브러시를 사용하여 지정된 파이를 채웁니다.
type: docs
weight: 274
url: /ko/system.drawing/graphics/fillpie/
---
## Graphics::FillPie(const SharedPtr<Brush>&, int, int, int, int, int, int) 메서드


현재 객체가 나타내는 표면에 지정된 브러시를 사용하여 지정된 파이를 채웁니다.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, int x, int y, int width, int height, int startAngle, int sweepAngle)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)<[Brush](../../brush/)>& | 파이를 채울 때 사용할 브러시 |
| x | int | 타원을 정의하는 사각형의 왼쪽 위 모서리 X 좌표 |
| y | int | 타원을 정의하는 사각형의 왼쪽 위 모서리 Y 좌표 |
| width | int | 타원을 정의하는 사각형의 너비 |
| height | int | 타원을 정의하는 사각형의 높이 |
| startAngle | int | X축에서 파이 시작점까지 시계 방향으로 측정한 각도(도) |
| sweepAngle | int | **startAngle**부터 파이 끝점까지 시계 방향으로 측정한 각도(도) |

## Graphics::FillPie(const SharedPtr<Brush>&, float, float, float, float, float, float) 메서드


현재 객체가 나타내는 표면에 지정된 브러시를 사용하여 지정된 파이를 채웁니다.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)<[Brush](../../brush/)>& | 파이를 채울 때 사용할 브러시 |
| x | **float** | 타원을 정의하는 사각형의 왼쪽 위 모서리 X 좌표 |
| y | **float** | 타원을 정의하는 사각형의 왼쪽 위 모서리 Y 좌표 |
| width | **float** | 타원을 정의하는 사각형의 너비 |
| height | **float** | 타원을 정의하는 사각형의 높이 |
| startAngle | **float** | X축에서 파이 시작점까지 시계 방향으로 측정한 각도(도) |
| sweepAngle | **float** | **startAngle**부터 파이 끝점까지 시계 방향으로 측정한 각도(도) |

## Graphics::FillPie(const SharedPtr<Brush>&, Rectangle, float, float) 메서드


현재 객체가 나타내는 표면에 지정된 브러시를 사용하여 지정된 파이를 채웁니다.

```cpp
void System::Drawing::Graphics::FillPie(const SharedPtr<Brush> &brush, Rectangle rect, float startAngle, float sweepAngle)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| brush | const [SharedPtr](../../../system/sharedptr/)<[Brush](../../brush/)>& | 파이를 채울 때 사용할 브러시 |
| rect | [Rectangle](../../rectangle/) | 타원을 정의하는 사각형 |
| startAngle | **float** | X축에서 파이 시작점까지 시계 방향으로 측정한 각도(도) |
| sweepAngle | **float** | **startAngle**부터 파이 끝점까지 시계 방향으로 측정한 각도(도) |

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Brush](../../brush/)
* 클래스 [Graphics](../)
* 클래스 [Rectangle](../../rectangle/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)