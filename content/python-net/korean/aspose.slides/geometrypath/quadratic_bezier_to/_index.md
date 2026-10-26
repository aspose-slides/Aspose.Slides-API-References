---
title: quadratic_bezier_to method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/geometrypath/quadratic_bezier_to/
weight: 70
---
## quadratic_bezier_to(self, point1, point2) {#asposeslidespointf-asposeslidespointf}
경로의 끝에 2차 베지어 곡선을 추가합니다


```python
def quadratic_bezier_to(self, point1, point2):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/ko/aspose.slides/pointf) | 방향 점 |
| point2 | [`PointF`](/slides/python-net/ko/aspose.slides/pointf) | 끝점 |


## quadratic_bezier_to(self, point1, point2, index) {#asposeslidespointf-asposeslidespointf-int}
경로의 지정된 위치에 2차 베지어 곡선을 추가합니다


```python
def quadratic_bezier_to(self, point1, point2, index):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| point1 | [`PointF`](/slides/python-net/ko/aspose.slides/pointf) | 방향 점 |
| point2 | [`PointF`](/slides/python-net/ko/aspose.slides/pointf) | 끝점 |
| index | **int** | PathData 내 세그먼트의 인덱스 |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 세그먼트 인덱스가 PathData 범위를 벗어났습니다 |


## quadratic_bezier_to(self, x1, y1, x2, y2) {#float-float-float-float}
경로의 끝에 2차 베지어 곡선을 추가합니다


```python
def quadratic_bezier_to(self, x1, y1, x2, y2):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x1 | **float** | 방향 점의 X 좌표 |
| y1 | **float** | 방향 점의 Y 좌표 |
| x2 | **float** | 끝점의 X 좌표 |
| y2 | **float** | 끝점의 Y 좌표 |


## quadratic_bezier_to(self, x1, y1, x2, y2, index) {#float-float-float-float-int}
경로의 지정된 위치에 2차 베지어 곡선을 추가합니다


```python
def quadratic_bezier_to(self, x1, y1, x2, y2, index):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x1 | **float** | 방향 점의 X 좌표 |
| y1 | **float** | 방향 점의 Y 좌표 |
| x2 | **float** | 끝점의 X 좌표 |
| y2 | **float** | 끝점의 Y 좌표 |
| index | **int** | PathData 내 세그먼트의 인덱스 |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 세그먼트 인덱스가 PathData 범위를 벗어났습니다 |



### 참고
* 클래스 [`GeometryPath`](/slides/python-net/ko/aspose.slides/geometrypath)
* 클래스 [`PointF`](/slides/python-net/ko/aspose.slides/pointf)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)