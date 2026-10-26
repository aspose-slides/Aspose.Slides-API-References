---
title: add_connector method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/shapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
기본 템플릿 스타일이 적용된 새로운 커넥터 모양을 생성하고, 모양 컬렉션의 끝에 추가합니다.

### 반환값

새로 생성된 [`IConnector`](/slides/python-net/ko/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype) | 추가할 커넥터 모양의 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype) |
| x | **float** | 커넥터 프레임의 x 좌표(포인트 단위) |
| y | **float** | 커넥터 프레임의 y 좌표(포인트 단위) |
| width | **float** | 커넥터 프레임의 너비(포인트 단위) |
| height | **float** | 커넥터 프레임의 높이(포인트 단위) |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
새로운 커넥터 모양을 생성하고 모양 컬렉션의 끝에 추가합니다. 기본 템플릿 스타일을 선택적으로 적용할 수 있습니다.

### 반환값

새로 생성된 [`IConnector`](/slides/python-net/ko/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype) | 생성할 커넥터 모양의 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype) |
| x | **float** | 커넥터 프레임의 x 좌표(포인트 단위) |
| y | **float** | 커넥터 프레임의 y 좌표(포인트 단위) |
| width | **float** | 커넥터 프레임의 너비(포인트 단위) |
| height | **float** | 커넥터 프레임의 높이(포인트 단위) |
| create_from_template | **bool** | 기본 템플릿 스타일을 적용하려면 true(비어 있지 않은 이름, 간단한 스타일); 기본 속성 값으로 커넥터를 생성하려면 false |



### 참조
* 클래스 [`IConnector`](/slides/python-net/ko/aspose.slides/iconnector)
* 클래스 [`ShapeCollection`](/slides/python-net/ko/aspose.slides/shapecollection)
* 열거형 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)