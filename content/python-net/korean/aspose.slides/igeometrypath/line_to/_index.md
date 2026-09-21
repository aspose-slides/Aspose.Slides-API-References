---
title: line_to method
second_title: Aspose.Slides for Python을 통한 .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/igeometrypath/line_to/
weight: 40
---
## line_to(self, point) {#asposepydrawingpointf}
경로의 끝에 선을 추가합니다


```python
def line_to(self, point):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| point | **aspose.slides.PointF** | 선의 끝점 |


## line_to(self, x, y) {#float-float}
경로의 끝에 선을 추가합니다


```python
def line_to(self, x, y):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x | **float** | 선의 끝점의 X 좌표 |
| y | **float** | 선의 끝점의 Y 좌표 |


## line_to(self, point, index) {#asposepydrawingpointf-int}
경로의 지정된 위치에 선을 추가합니다


```python
def line_to(self, point, index):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| point | **aspose.slides.PointF** | 끝점 |
| index | **int** | PathData에서 세그먼트의 인덱스 |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 세그먼트 인덱스가 PathData 범위를 벗어났습니다 |


## line_to(self, x, y, index) {#float-float-int}
경로의 지정된 위치에 선을 추가합니다


```python
def line_to(self, x, y, index):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x | **float** | 점의 X 좌표 |
| y | **float** | 점의 Y 좌표 |
| index | **int** | PathData에서 세그먼트의 인덱스 |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 세그먼트 인덱스가 PathData 범위를 벗어났습니다 |



### 참조
* 클래스 [`IGeometryPath`](/slides/python-net/ko/aspose.slides/igeometrypath)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)