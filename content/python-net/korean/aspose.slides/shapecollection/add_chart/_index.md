---
title: add_chart method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/shapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 뒤, 도형 컬렉션의 끝에 추가합니다.

### Returns

새로 생성된 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype) | 추가할 차트의 유형. |
| x | **float** | 새 차트의 x 좌표(포인트 단위). |
| y | **float** | 새 차트의 y 좌표(포인트 단위). |
| width | **float** | 차트의 너비(포인트 단위). |
| height | **float** | 차트의 높이(포인트 단위). |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 뒤, 도형 컬렉션의 끝에 추가합니다.

### Returns

새로 생성된 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype) | 추가할 차트의 유형. |
| x | **float** | 새 차트의 x 좌표(포인트 단위). |
| y | **float** | 새 차트의 y 좌표(포인트 단위). |
| width | **float** | 차트의 너비(포인트 단위). |
| height | **float** | 차트의 높이(포인트 단위). |
| init_with_sample | **bool** | 새 차트를 샘플 시리즈 데이터와 설정으로 초기화하려면 true; <br/><br/>시리즈가 없고 최소 설정만으로 차트를 생성하려면 false, 이렇게 하면 생성 속도가 빨라집니다. |



### See Also
* 열거형 [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype)
* 클래스 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart)
* 클래스 [`ShapeCollection`](/slides/python-net/ko/aspose.slides/shapecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)