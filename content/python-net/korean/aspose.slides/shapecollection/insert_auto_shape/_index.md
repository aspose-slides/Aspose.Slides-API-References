---
title: insert_auto_shape method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
새 자동 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입하며 기본 템플릿 서식을 적용합니다.

### 반환값

새로 생성된 [`IAutoShape`](/slides/python-net/ko/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | **int** | 새 자동 도형을 삽입할 0부터 시작하는 인덱스입니다. |
| shape_type | [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype) | 삽입할 자동 도형의 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype)입니다. |
| x | **float** | 도형 프레임의 x 좌표이며, 단위는 포인트입니다. |
| y | **float** | 도형 프레임의 y 좌표이며, 단위는 포인트입니다. |
| width | **float** | 도형 프레임의 너비이며, 단위는 포인트입니다. |
| height | **float** | 도형 프레임의 높이이며, 단위는 포인트입니다. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
새 자동 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입하며, 선택적으로 기본 템플릿 스타일을 적용하여 초기화합니다.

### 반환값

새로 생성된 [`IAutoShape`](/slides/python-net/ko/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | **int** | 삽입할 자동 도형의 0부터 시작하는 인덱스입니다. |
| shape_type | [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype) | 삽입할 자동 도형의 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype)입니다. |
| x | **float** | 도형 프레임의 x 좌표이며, 단위는 포인트입니다. |
| y | **float** | 도형 프레임의 y 좌표이며, 단위는 포인트입니다. |
| width | **float** | 도형 프레임의 너비이며, 단위는 포인트입니다. |
| height | **float** | 도형 프레임의 높이이며, 단위는 포인트입니다. |
| create_from_template | **bool** | True를 지정하면 기본 템플릿 스타일을 적용합니다(비어 있지 않은 이름, 간단한 스타일 및 중앙 정렬 텍스트 포함); <br/><br/>false를 지정하면 모든 속성을 기본값으로 설정하여 도형을 생성합니다. |



### 참조
* 클래스 [`IAutoShape`](/slides/python-net/ko/aspose.slides/iautoshape)
* 클래스 [`ShapeCollection`](/slides/python-net/ko/aspose.slides/shapecollection)
* 열거형 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)