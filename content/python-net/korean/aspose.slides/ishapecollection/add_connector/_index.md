---
title: add_connector method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
기본 템플릿 스타일이 적용된 새 연결자 모양을 생성하고 이를 모양 컬렉션의 끝에 추가합니다.

### 반환값

새로 생성된 [`IConnector`](/slides/python-net/ko/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype) | 추가할 연결자 모양의 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype). |
| x | **float** | 연결자 프레임의 x좌표(포인트 단위). |
| y | **float** | 연결자 프레임의 y좌표(포인트 단위). |
| width | **float** | 연결자 프레임의 너비(포인트 단위). |
| height | **float** | 연결자 프레임의 높이(포인트 단위). |


## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
새 연결자 모양을 생성하고 이를 모양 컬렉션의 끝에 추가합니다. 필요에 따라 기본 템플릿 스타일을 적용할 수 있습니다.

### 반환값

새로 생성된 [`IConnector`](/slides/python-net/ko/aspose.slides/iconnector).



```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype) | 생성할 연결자 모양의 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype). |
| x | **float** | 연결자 프레임의 x좌표(포인트 단위). |
| y | **float** | 연결자 프레임의 y좌표(포인트 단위). |
| width | **float** | 연결자 프레임의 너비(포인트 단위). |
| height | **float** | 연결자 프레임의 높이(포인트 단위). |
| create_from_template | **bool** | 기본 템플릿 스타일을 적용하려면 True(비어 있지 않은 이름, 단순 스타일); <br/><br/> 기본 속성값으로 연결자를 생성하려면 false. |



### 참조
* 클래스 [`IConnector`](/slides/python-net/ko/aspose.slides/iconnector)
* 클래스 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection)
* 열거형 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)