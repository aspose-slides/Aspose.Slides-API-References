---
title: AddArc()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 경로에 지정된 타원형 호를 추가합니다.
type: docs
weight: 183
url: /ko/system.drawing.drawing2d/graphicspath/addarc/
---
## GraphicsPath::AddArc(float, float, float, float, float, float) 메서드


지정된 타원형 호를 현재 객체가 나타내는 경로에 추가합니다.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(float x, float y, float width, float height, float startAngle, float sweepAngle)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 호가 그려지는 타원을 둘러싸는 사각형의 왼쪽 위 모서리의 X 좌표 |
| y | **float** | 호가 그려지는 타원을 둘러싸는 사각형의 왼쪽 위 모서리의 Y 좌표 |
| width | **float** | 호가 그려지는 타원을 둘러싸는 사각형의 너비 |
| height | **float** | 호가 그려지는 타원을 둘러싸는 사각형의 높이 |
| startAngle | **float** | 호의 시작 각도를 지정합니다. 단위는 도이며 X축을 기준으로 시계 방향으로 측정됩니다 |
| sweepAngle | **float** | 시작 각도와 호의 끝 사이의 각도를 지정합니다 |

## GraphicsPath::AddArc(int, int, int, int, float, float) 메서드


지정된 타원형 호를 현재 객체가 나타내는 경로에 추가합니다.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(int x, int y, int width, int height, float startAngle, float sweepAngle)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | int | 호가 그려지는 타원을 둘러싸는 사각형의 왼쪽 위 모서리의 X 좌표 |
| y | int | 호가 그려지는 타원을 둘러싸는 사각형의 왼쪽 위 모서리의 Y 좌표 |
| width | int | 호가 그려지는 타원을 둘러싸는 사각형의 너비 |
| height | int | 호가 그려지는 타원을 둘러싸는 사각형의 높이 |
| startAngle | **float** | 호의 시작 각도를 지정합니다. 단위는 도이며 X축을 기준으로 시계 방향으로 측정됩니다 |
| sweepAngle | **float** | 시작 각도와 호의 끝 사이의 각도를 지정합니다 |

## GraphicsPath::AddArc(const RectangleF\&, float, float) 메서드


지정된 타원형 호를 현재 객체가 나타내는 경로에 추가합니다.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(const RectangleF &rect, float startAngle, float sweepAngle)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [RectangleF](../../../system.drawing/rectanglef/)\& | 호가 그려지는 타원을 둘러싸는 사각형 |
| startAngle | **float** | 호의 시작 각도를 지정합니다. 단위는 도이며 X축을 기준으로 시계 방향으로 측정됩니다 |
| sweepAngle | **float** | 시작 각도와 호의 끝 사이의 각도를 지정합니다 |

## GraphicsPath::AddArc(const Rectangle\&, float, float) 메서드


지정된 타원형 호를 현재 객체가 나타내는 경로에 추가합니다.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddArc(const Rectangle &rect, float startAngle, float sweepAngle)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [Rectangle](../../../system.drawing/rectangle/)\& | 호가 그려지는 타원을 둘러싸는 사각형 |
| startAngle | **float** | 호의 시작 각도를 지정합니다. 단위는 도이며 X축을 기준으로 시계 방향으로 측정됩니다 |
| sweepAngle | **float** | 시작 각도와 호의 끝 사이의 각도를 지정합니다 |

## 참조

* 클래스 [GraphicsPath](../)
* 클래스 [RectangleF](../../../system.drawing/rectanglef/)
* 클래스 [Rectangle](../../../system.drawing/rectangle/)
* 네임스페이스 [System::Drawing::Drawing2D](../../)
* 라이브러리 [Aspose.Slides](../../../)