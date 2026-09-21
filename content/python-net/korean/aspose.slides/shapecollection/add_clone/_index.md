---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/shapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
지정된 모양을 복제하고 모양 컬렉션의 끝에 추가합니다.
            복제된 모양은 원본의 위치와 크기를 유지합니다.

### Returns

새로 생성된 [`IShape`](/slides/python-net/ko/aspose.slides/ishape).



```python
def add_clone(self, source_shape):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/ko/aspose.slides/ishape) | 복제할 [`IShape`](/slides/python-net/ko/aspose.slides/ishape). |


## add_clone(self, source_shape, x, y) {#ishape-float-float}
지정된 모양을 복제하고 모양 컬렉션의 끝에 추가합니다.
            새 모양은 `source_shape`의 너비와 높이를 유지합니다.

### Returns

새로 생성된 [`IShape`](/slides/python-net/ko/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/ko/aspose.slides/ishape) | 복제할 모양. |
| x | **float** | 새 모양 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 모양 프레임의 y 좌표(포인트 단위). |


## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
지정된 모양을 복제하고 모양 컬렉션의 끝에 추가합니다.

### Returns

새로 생성된 [`IShape`](/slides/python-net/ko/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/ko/aspose.slides/ishape) | 복제할 모양. |
| x | **float** | 새 모양 프레임의 x 좌표(포인트 단위). |
| y | **float** | 새 모양 프레임의 y 좌표(포인트 단위). |
| width | **float** | 새 모양 프레임의 너비(포인트 단위). |
| height | **float** | 새 모양 프레임의 높이(포인트 단위). |



### 참조
* 클래스 [`IShape`](/slides/python-net/ko/aspose.slides/ishape)
* 클래스 [`ShapeCollection`](/slides/python-net/ko/aspose.slides/shapecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)