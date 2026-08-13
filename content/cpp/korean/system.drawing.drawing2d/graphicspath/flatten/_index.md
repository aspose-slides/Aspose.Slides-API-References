---
title: Flatten()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 경로의 각 곡선을 연속된 직선들의 시리즈로 변환하여 평탄화합니다. 평탄도 값으로 0.25가 사용됩니다.
type: docs
weight: 391
url: /ko/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() 메서드

경로의 각 곡선을 연속된 직선들의 시리즈로 변환하여 평탄화합니다. 평탄도 값으로 0.25가 사용됩니다.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```
## GraphicsPath::Flatten(const MatrixPtr\&) 메서드

경로의 각 곡선을 연속된 직선들의 시리즈로 변환하여 평탄화합니다. 평탄도 값으로 0.25가 사용됩니다.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | 평탄화하기 전에 경로에 적용할 변환 행렬 |

## GraphicsPath::Flatten(const MatrixPtr\&, float) 메서드

경로의 각 곡선을 연속된 직선들의 시리즈로 변환하여 평탄화합니다.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | 평탄화하기 전에 경로에 적용할 변환 행렬 |
| flatness | **float** | 곡선과 평탄화된 근사 사이의 허용 가능한 최대 오차를 지정합니다 |

## 참조

* Typedef [MatrixPtr](../../matrixptr/)
* 클래스 [GraphicsPath](../)
* 네임스페이스 [System::Drawing::Drawing2D](../../)
* 라이브러리 [Aspose.Slides](../../../)