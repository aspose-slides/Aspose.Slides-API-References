---
title: insert_chart method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ishapecollection/insert_chart/
weight: 240
---
## insert_chart(self, type, x, y, width, height, index) {#asposeslideschartscharttype-float-float-float-float-int}
새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 다음 지정된 인덱스에 shape 컬렉션에 삽입합니다.

### 반환값

새로 생성된 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype) | 생성할 차트의 유형. |
| x | **float** | 새 차트의 x 좌표(포인트 단위). |
| y | **float** | 새 차트의 y 좌표(포인트 단위). |
| width | **float** | 새 차트의 너비(포인트 단위). |
| height | **float** | 새 차트의 높이(포인트 단위). |
| index | **int** | shape 컬렉션에 새 차트를 삽입할 0 기반 인덱스. |


## insert_chart(self, type, x, y, width, height, index, init_with_sample) {#asposeslideschartscharttype-float-float-float-float-int-bool}
새 차트를 생성하고 샘플 시리즈 데이터와 설정으로 초기화한 다음 지정된 인덱스에 shape 컬렉션에 삽입합니다.

### 반환값

새로 생성된 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart).



```python
def insert_chart(self, type, x, y, width, height, index, init_with_sample):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype) | 생성할 차트의 유형. |
| x | **float** | 새 차트의 x 좌표(포인트 단위). |
| y | **float** | 새 차트의 y 좌표(포인트 단위). |
| width | **float** | 새 차트의 너비(포인트 단위). |
| height | **float** | 새 차트의 높이(포인트 단위). |
| index | **int** | shape 컬렉션에 새 차트를 삽입할 0 기반 인덱스. |
| init_with_sample | **bool** | True이면 새 차트를 샘플 시리즈 데이터와 설정으로 초기화합니다; <br/><br/>            false이면 시리즈 없이 최소 설정만으로 차트를 생성하여 생성 속도를 높입니다. |



### 참고
* 열거형 [`ChartType`](/slides/python-net/ko/aspose.slides.charts/charttype)
* 클래스 [`IChart`](/slides/python-net/ko/aspose.slides.charts/ichart)
* 클래스 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)