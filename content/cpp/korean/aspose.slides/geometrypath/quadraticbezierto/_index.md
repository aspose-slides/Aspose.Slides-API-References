---
title: QuadraticBezierTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 경로 끝에 2차 베지어 곡선을 추가합니다
type: docs
weight: 118
url: /ko/aspose.slides/geometrypath/quadraticbezierto/
---
## GeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF) 메서드

경로 끝에 2차 베지어 곡선을 추가합니다

```cpp
void Aspose::Slides::GeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 방향 점 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 끝점 |

## GeometryPath::QuadraticBezierTo(float, float, float, float) 메서드

경로 끝에 2차 베지어 곡선을 추가합니다

```cpp
void Aspose::Slides::GeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x1 | **float** | 방향점의 X 좌표 |
| y1 | **float** | 방향점의 Y 좌표 |
| x2 | **float** | 끝점의 X 좌표 |
| y2 | **float** | 끝점의 Y 좌표 |

## GeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF, uint32_t) 메서드

경로의 지정된 위치에 2차 베지어 곡선을 추가합니다

```cpp
void Aspose::Slides::GeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, uint32_t index) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 방향 점 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 끝점 |
| index | **uint32_t** | PathData 내 세그먼트 인덱스 |

## GeometryPath::QuadraticBezierTo(float, float, float, float, uint32_t) 메서드

경로의 지정된 위치에 2차 베지어 곡선을 추가합니다

```cpp
void Aspose::Slides::GeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2, uint32_t index) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x1 | **float** | 방향점의 X 좌표 |
| y1 | **float** | 방향점의 Y 좌표 |
| x2 | **float** | 끝점의 X 좌표 |
| y2 | **float** | 끝점의 Y 좌표 |
| index | **uint32_t** | PathData 내 세그먼트 인덱스 |

## 참고

* 클래스 [PointF](../../../system.drawing/pointf/)
* 클래스 [GeometryPath](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)