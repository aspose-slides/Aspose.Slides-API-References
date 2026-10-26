---
title: add_auto_shape method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/shapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
기본 서식을 가진 새 자동 도형을 생성하고 도형 컬렉션 끝에 추가합니다.

### 반환값

새로 생성된 [`IAutoShape`](/slides/python-net/ko/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype) | 추가할 자동 도형의 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype). |
| x | **float** | 도형 프레임의 x 좌표(포인트 단위). |
| y | **float** | 도형 프레임의 y 좌표(포인트 단위). |
| width | **float** | 도형 프레임의 너비(포인트 단위). |
| height | **float** | 도형 프레임의 높이(포인트 단위). |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
새 자동 도형을 생성하고 도형 컬렉션 끝에 추가합니다. 필요에 따라 기본 템플릿 서식으로 초기화할 수 있습니다.

### 반환값

새로 생성된 [`IAutoShape`](/slides/python-net/ko/aspose.slides/iautoshape).



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype) | 추가할 자동 도형의 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype). |
| x | **float** | 도형 프레임의 x 좌표(포인트 단위). |
| y | **float** | 도형 프레임의 y 좌표(포인트 단위). |
| width | **float** | 도형 프레임의 너비(포인트 단위). |
| height | **float** | 도형 프레임의 높이(포인트 단위). |
| create_from_template | **bool** | True: 새 도형에 기본 템플릿 스타일(단순 스타일, 중앙 정렬 텍스트, 비어 있지 않은 이름)을 적용합니다.<br/><br/>false: 모든 속성을 기본값으로 설정하여 도형을 생성합니다. |



### 또한 보기
* 클래스 [`IAutoShape`](/slides/python-net/ko/aspose.slides/iautoshape)
* 클래스 [`ShapeCollection`](/slides/python-net/ko/aspose.slides/shapecollection)
* 열거형 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)