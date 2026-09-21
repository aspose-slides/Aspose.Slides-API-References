---
title: insert_auto_shape method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/ishapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
새 자동 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입하며,
기본 템플릿 서식을 적용합니다.

### Returns

새로 생성된 [`IAutoShape`](/slides/python-net/ko/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | 새 자동 도형을 삽입할 0부터 시작하는 인덱스입니다. |
| shape_type | [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype) | 삽입할 자동 도형의 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype)입니다. |
| x | **float** | 도형 프레임의 x 좌표(포인트)입니다. |
| y | **float** | 도형 프레임의 y 좌표(포인트)입니다. |
| width | **float** | 도형 프레임의 너비(포인트)입니다. |
| height | **float** | 도형 프레임의 높이(포인트)입니다. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
새 자동 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입하며,
선택적으로 기본 템플릿 스타일을 적용하여 초기화합니다.

### Returns

새로 생성된 [`IAutoShape`](/slides/python-net/ko/aspose.slides/iautoshape).



```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | 자동 도형을 삽입할 0부터 시작하는 인덱스입니다. |
| shape_type | [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype) | 삽입할 자동 도형의 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype)입니다. |
| x | **float** | 도형 프레임의 x 좌표(포인트)입니다. |
| y | **float** | 도형 프레임의 y 좌표(포인트)입니다. |
| width | **float** | 도형 프레임의 너비(포인트)입니다. |
| height | **float** | 도형 프레임의 높이(포인트)입니다. |
| create_from_template | **bool** | True인 경우 기본 템플릿 스타일(비어 있지 않은 이름, 단순 스타일, 중앙 정렬 텍스트 포함)을 적용합니다;<br/><br/>false인 경우 모든 속성을 기본값으로 설정하여 도형을 생성합니다. |



### 참고
* 클래스 [`IAutoShape`](/slides/python-net/ko/aspose.slides/iautoshape)
* 클래스 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)