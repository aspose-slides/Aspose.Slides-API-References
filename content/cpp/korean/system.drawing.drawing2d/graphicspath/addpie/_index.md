---
title: AddPie()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 경로에 파이 모양의 지정된 외곽선을 추가합니다.
type: docs
weight: 209
url: /ko/system.drawing.drawing2d/graphicspath/addpie/
---
## GraphicsPath::AddPie(float, float, float, float, float, float) 메서드

현재 객체가 나타내는 경로에 파이 모양의 지정된 외곽선을 추가합니다.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(float x, float y, float width, float height, float startAngle, float sweepAngle)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 파이가 그려지는 타원을 둘러싼 사각형의 왼쪽 위 모서리의 X 좌표 |
| y | **float** | 파이가 그려지는 타원을 둘러싼 사각형의 왼쪽 위 모서리의 Y 좌표 |
| width | **float** | 파이가 그려지는 타원을 둘러싼 사각형의 왼쪽 위 모서리의 너비 |
| height | **float** | 파이가 그려지는 타원을 둘러싼 사각형의 왼쪽 위 모서리의 높이 |
| startAngle | **float** | X축을 기준으로 시계 방향으로 측정한 파이의 시작 각도(도) |
| sweepAngle | **float** | 시작 각도와 파이의 끝 사이의 각도(도) |

## GraphicsPath::AddPie(int, int, int, int, float, float) 메서드

현재 객체가 나타내는 경로에 파이 모양의 지정된 외곽선을 추가합니다.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(int x, int y, int width, int height, float startAngle, float sweepAngle)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | int | 파이가 그려지는 타원을 둘러싼 사각형의 왼쪽 위 모서리의 X 좌표 |
| y | int | 파이가 그려지는 타원을 둘러싼 사각형의 왼쪽 위 모서리의 Y 좌표 |
| width | int | 파이가 그려지는 타원을 둘러싼 사각형의 왼쪽 위 모서리의 너비 |
| height | int | 파이가 그려지는 타원을 둘러싼 사각형의 왼쪽 위 모서리의 높이 |
| startAngle | **float** | X축을 기준으로 시계 방향으로 측정한 파이의 시작 각도(도) |
| sweepAngle | **float** | 시작 각도와 파이의 끝 사이의 각도(도) |

## GraphicsPath::AddPie(const Rectangle\&, float, float) 메서드

현재 객체가 나타내는 경로에 파이 모양의 지정된 외곽선을 추가합니다.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPie(const Rectangle &rect, float startAngle, float sweepAngle)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | 파이가 그려지는 타원을 둘러싼 사각형 |
| startAngle | **float** | X축을 기준으로 시계 방향으로 측정한 파이의 시작 각도(도) |
| sweepAngle | **float** | 시작 각도와 파이의 끝 사이의 각도(도) |

## 참고

* 클래스 [GraphicsPath](../)
* 클래스 [Rectangle](../../../system.drawing/rectangle/)
* 네임스페이스 [System::Drawing::Drawing2D](../../)
* 라이브러리 [Aspose.Slides](../../../)