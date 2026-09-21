---
title: insert_connector method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/shapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
새 연결자 모양을 만들고 지정된 인덱스에 모양 컬렉션에 삽입하며 기본 템플릿 스타일을 적용합니다.

### 반환값

새로 만든 [`IConnector`](/slides/python-net/ko/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 연결자 모양을 삽입할 0 기반 인덱스입니다. |
| shape_type | [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype) | 삽입할 연결자 모양의 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype)입니다. |
| x | **float** | 포인트 단위의 연결자 프레임 x 좌표입니다. |
| y | **float** | 포인트 단위의 연결자 프레임 y 좌표입니다. |
| width | **float** | 포인트 단위의 연결자 프레임 너비입니다. |
| height | **float** | 포인트 단위의 연결자 프레임 높이입니다. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
새 연결자 모양을 만들고 지정된 인덱스에 모양 컬렉션에 삽입하며 옵션으로 기본 템플릿 스타일을 적용합니다.

### 반환값

새로 만든 [`IConnector`](/slides/python-net/ko/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 연결자 모양을 삽입할 0 기반 인덱스입니다. |
| shape_type | [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype) | 삽입할 연결자 모양의 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype)입니다. |
| x | **float** | 포인트 단위의 연결자 프레임 x 좌표입니다. |
| y | **float** | 포인트 단위의 연결자 프레임 y 좌표입니다. |
| width | **float** | 포인트 단위의 연결자 프레임 너비입니다. |
| height | **float** | 포인트 단위의 연결자 프레임 높이입니다. |
| create_from_template | **bool** | 기본 템플릿 스타일을 적용하려면 true (비어 있지 않은 이름, 단순 스타일);<br/><br/>            false 를 지정하면 기본 속성값으로 연결자를 생성합니다. |



### 추가 정보
* class [`IConnector`](/slides/python-net/ko/aspose.slides/iconnector)
* class [`ShapeCollection`](/slides/python-net/ko/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)