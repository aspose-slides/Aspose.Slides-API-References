---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ishapecollection/insert_clone/
weight: 250
---
## insert_clone(self, index, source_shape) {#int-ishape}
지정된 모양의 복사본을 생성하고 지정된 인덱스에 모양 컬렉션에 삽입합니다.
클론된 모양은 원본의 위치와 크기를 유지합니다.

### Returns

새로 생성된 [`IShape`](/slides/python-net/ko/aspose.slides/ishape).

```python
def insert_clone(self, index, source_shape):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | **int** | 클론된 모양을 삽입할 0 기반 인덱스. |
| source_shape | [`IShape`](/slides/python-net/ko/aspose.slides/ishape) | 복제할 [`IShape`](/slides/python-net/ko/aspose.slides/ishape). |

## insert_clone(self, index, source_shape, x, y) {#int-ishape-float-float}
지정된 모양의 복사본을 생성하고 지정된 인덱스에 모양 컬렉션에 삽입합니다.
새로운 모양은 `source_shape`의 너비와 높이를 유지합니다.

### Returns

새로 생성된 [`IShape`](/slides/python-net/ko/aspose.slides/ishape).

```python
def insert_clone(self, index, source_shape, x, y):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | **int** | 클론된 모양을 삽입할 0 기반 인덱스. |
| source_shape | [`IShape`](/slides/python-net/ko/aspose.slides/ishape) | 복제할 [`IShape`](/slides/python-net/ko/aspose.slides/ishape). |
| x | **float** | 클론된 모양 프레임의 x 좌표(포인트). |
| y | **float** | 클론된 모양 프레임의 y 좌표(포인트). |

## insert_clone(self, index, source_shape, x, y, width, height) {#int-ishape-float-float-float-float}
지정된 모양의 복사본을 생성하고 지정된 인덱스에 모양 컬렉션에 삽입합니다.

### Returns

새로 생성된 [`IShape`](/slides/python-net/ko/aspose.slides/ishape).

```python
def insert_clone(self, index, source_shape, x, y, width, height):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | **int** | 클론된 모양을 삽입할 0 기반 인덱스. |
| source_shape | [`IShape`](/slides/python-net/ko/aspose.slides/ishape) | 복제할 [`IShape`](/slides/python-net/ko/aspose.slides/ishape). |
| x | **float** | 클론된 모양 프레임의 x 좌표(포인트). |
| y | **float** | 클론된 모양 프레임의 y 좌표(포인트). |
| width | **float** | 클론된 모양 프레임의 너비(포인트). |
| height | **float** | 클론된 모양 프레임의 높이(포인트). |

### See Also
* 클래스 [`IShape`](/slides/python-net/ko/aspose.slides/ishape)
* 클래스 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)