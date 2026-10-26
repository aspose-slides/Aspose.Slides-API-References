---
title: LineTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 경로 끝에 선을 추가합니다
type: docs
weight: 92
url: /ko/aspose.slides/geometrypath/lineto/
---
## GeometryPath::LineTo(System::Drawing::PointF) method

경로 끝에 선을 추가합니다

```cpp
void Aspose::Slides::GeometryPath::LineTo(System::Drawing::PointF point) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | 선의 끝점 |

## GeometryPath::LineTo(float, float) method

경로 끝에 선을 추가합니다

```cpp
void Aspose::Slides::GeometryPath::LineTo(float x, float y) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | **float** | 선 끝 점의 X 좌표 |
| y | **float** | 선 끝 점의 Y 좌표 |

## GeometryPath::LineTo(System::Drawing::PointF, uint32_t) method

경로의 지정된 위치에 선을 추가합니다

```cpp
void Aspose::Slides::GeometryPath::LineTo(System::Drawing::PointF point, uint32_t index) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point | [System::Drawing::PointF](../../../system.drawing/pointf/) | 끝점 |
| index | **uint32_t** | PathData의 세그먼트 인덱스 |

## GeometryPath::LineTo(float, float, uint32_t) method

경로의 지정된 위치에 선을 추가합니다

```cpp
void Aspose::Slides::GeometryPath::LineTo(float x, float y, uint32_t index) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | **float** | 점의 X 좌표 |
| y | **float** | 점의 Y 좌표 |
| index | **uint32_t** | PathData의 세그먼트 인덱스 |

## 참조

* 클래스 [PointF](../../../system.drawing/pointf/)
* 클래스 [GeometryPath](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)