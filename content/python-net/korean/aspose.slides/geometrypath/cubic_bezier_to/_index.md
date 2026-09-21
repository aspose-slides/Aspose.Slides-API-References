---
title: cubic_bezier_to method
second_title: Aspose.Slides for Python용 .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/geometrypath/cubic_bezier_to/
weight: 40
---
## cubic_bezier_to(self, point1, point2, point3) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf}
경로 끝에 3차 베지어 곡선을 추가합니다

```python
def cubic_bezier_to(self, point1, point2, point3):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | 첫 번째 방향 점 |
| point2 | **aspose.slides.PointF** | 두 번째 방향 점 |
| point3 | **aspose.slides.PointF** | 끝점 |

## cubic_bezier_to(self, point1, point2, point3, index) {#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int}
지정된 위치에 3차 베지어 곡선을 추가합니다

```python
def cubic_bezier_to(self, point1, point2, point3, index):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| point1 | **aspose.slides.PointF** | 첫 번째 방향 점 |
| point2 | **aspose.slides.PointF** | 두 번째 방향 점 |
| point3 | **aspose.slides.PointF** | 끝점 |
| index | **int** | PathData에서 세그먼트 인덱스 |

### 예외

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 세그먼트 인덱스가 PathData 범위를 벗어났습니다 |

## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3) {#float-float-float-float-float-float}
경로 끝에 3차 베지어 곡선을 추가합니다

```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| x1 | **float** | 첫 번째 방향 점의 X 좌표 |
| y1 | **float** | 첫 번째 방향 점의 Y 좌표 |
| x2 | **float** | 두 번째 방향 점의 X 좌표 |
| y2 | **float** | 두 번째 방향 점의 Y 좌표 |
| x3 | **float** | 끝점의 X 좌표 |
| y3 | **float** | 끝점의 Y 좌표 |

## cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index) {#float-float-float-float-float-float-int}
지정된 위치에 3차 베지어 곡선을 추가합니다

```python
def cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| x1 | **float** | 첫 번째 방향 점의 X 좌표 |
| y1 | **float** | 첫 번째 방향 점의 Y 좌표 |
| x2 | **float** | 두 번째 방향 점의 X 좌표 |
| y2 | **float** | 두 번째 방향 점의 Y 좌표 |
| x3 | **float** | 끝점의 X 좌표 |
| y3 | **float** | 끝점의 Y 좌표 |
| index | **int** | PathData에서 세그먼트 인덱스 |

### 예외

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 세그먼트 인덱스가 PathData 범위를 벗어났습니다 |

### 참조
* 클래스 [`GeometryPath`](/slides/python-net/ko/aspose.slides/geometrypath)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)