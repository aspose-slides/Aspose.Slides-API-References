---
title: insert_connector method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ishapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
새 커넥터 모양을 생성하고 지정된 인덱스에 모양 컬렉션에 삽입하며 기본 템플릿 스타일을 적용합니다.

### 반환값

새로 만든 [`IConnector`](/slides/python-net/ko/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 커넥터 모양을 삽입할 0 기반 인덱스입니다. |
| shape_type | [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype) | 삽입할 커넥터 모양의 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype)입니다. |
| x | **float** | 커넥터 프레임의 x 좌표(포인트)입니다. |
| y | **float** | 커넥터 프레임의 y 좌표(포인트)입니다. |
| width | **float** | 커넥터 프레임의 너비(포인트)입니다. |
| height | **float** | 커넥터 프레임의 높이(포인트)입니다. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
새 커넥터 모양을 생성하고 지정된 인덱스에 모양 컬렉션에 삽입하며, 선택적으로 기본 템플릿 스타일을 적용합니다.

### 반환값

새로 만든 [`IConnector`](/slides/python-net/ko/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 커넥터 모양을 삽입할 0 기반 인덱스입니다. |
| shape_type | [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype) | 삽입할 커넥터 모양의 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype)입니다. |
| x | **float** | 커넥터 프레임의 x 좌표(포인트)입니다. |
| y | **float** | 커넥터 프레임의 y 좌표(포인트)입니다. |
| width | **float** | 커넥터 프레임의 너비(포인트)입니다. |
| height | **float** | 커넥터 프레임의 높이(포인트)입니다. |
| create_from_template | **bool** | True는 기본 템플릿 스타일(비어 있지 않은 이름, 단순 스타일)을 적용하고;<br/><br/>false는 기본 속성 값으로 커넥터를 생성합니다. |



### 참고
* 클래스 [`IConnector`](/slides/python-net/ko/aspose.slides/iconnector)
* 클래스 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection)
* 열거형 [`ShapeType`](/slides/python-net/ko/aspose.slides/shapetype)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)