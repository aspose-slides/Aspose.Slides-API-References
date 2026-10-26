---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/ishapecollection/add_clone/
weight: 60
---
## add_clone(self, source_shape) {#ishape}
Creates a copy of the specified shape and adds it to the end of the shape collection.
            The cloned shape retains the original’s position and size.

### 반환값

The newly created [`IShape`](/slides/python-net/ko/aspose.slides/ishape).



```python
def add_clone(self, source_shape):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/ko/aspose.slides/ishape) | 복제할 [`IShape`](/slides/python-net/ko/aspose.slides/ishape). |


## add_clone(self, source_shape, x, y) {#ishape-float-float}
Creates a copy of the specified shape and adds it to the end of the shape collection.
            The new shape retains the width and height of the `source_shape`.

### 반환값

The newly created [`IShape`](/slides/python-net/ko/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/ko/aspose.slides/ishape) | 복제할 [`IShape`](/slides/python-net/ko/aspose.slides/ishape). |
| x | **float** | 복제된 모양 프레임의 x 좌표(포인트). |
| y | **float** | 복제된 모양 프레임의 y 좌표(포인트). |


## add_clone(self, source_shape, x, y, width, height) {#ishape-float-float-float-float}
Creates a copy of the specified shape and adds it to the end of the shape collection.

### 반환값

The newly created [`IShape`](/slides/python-net/ko/aspose.slides/ishape).



```python
def add_clone(self, source_shape, x, y, width, height):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_shape | [`IShape`](/slides/python-net/ko/aspose.slides/ishape) | 복제할 모양. |
| x | **float** | 복제된 모양 프레임의 x 좌표(포인트). |
| y | **float** | 복제된 모양 프레임의 y 좌표(포인트). |
| width | **float** | 복제된 모양 프레임의 너비(포인트). |
| height | **float** | 복제된 모양 프레임의 높이(포인트). |



### 참고
* 클래스 [`IShape`](/slides/python-net/ko/aspose.slides/ishape)
* 클래스 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)