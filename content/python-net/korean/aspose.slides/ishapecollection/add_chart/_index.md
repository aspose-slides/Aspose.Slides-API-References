---
title: add_chart method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ishapecollection/add_chart/
weight: 50
---
## add_chart(self, type, x, y, width, height) {#asposeslideschartscharttype-float-float-float-float}
새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 다음, 모양 컬렉션의 끝에 추가합니다.

### 반환

새로 생성된 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype) | 추가할 차트의 유형입니다. |
| x | **float** | 새 차트의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새 차트의 y 좌표(포인트 단위)입니다. |
| width | **float** | 차트의 너비(포인트 단위)입니다. |
| height | **float** | 차트의 높이(포인트 단위)입니다. |


## add_chart(self, type, x, y, width, height, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-bool}
새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 다음, 모양 컬렉션의 끝에 추가합니다.

### 반환

새로 생성된 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart).



```python
def add_chart(self, type, x, y, width, height, init_with_sample):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype) | 추가할 차트의 유형입니다. |
| x | **float** | 새 차트의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새 차트의 y 좌표(포인트 단위)입니다. |
| width | **float** | 차트의 너비(포인트 단위)입니다. |
| height | **float** | 차트의 높이(포인트 단위)입니다. |
| init_with_sample | **bool** | True를 지정하면 샘플 시리즈 데이터와 설정으로 새 차트를 초기화합니다; <br/><br/>            false를 지정하면 시리즈 없이 최소 설정만으로 차트를 생성하여 생성 속도를 높입니다. |



### 참고
* 열거형 [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype)
* 클래스 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart)
* 클래스 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)