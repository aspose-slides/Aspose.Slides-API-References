---
title: reorder method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/shapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
지정된 도형을 도형 컬렉션 내의 새 위치로 이동합니다.


```python
def reorder(self, index, shape):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | **int** | 도형이 배치될 0부터 시작하는 대상 인덱스입니다. |
| shape | [`IShape`](/slides/python-net/ko/aspose.slides/ishape) | 컬렉션 내에서 이동할 [`IShape`](/slides/python-net/ko/aspose.slides/ishape)입니다. |


## reorder(self, index, shapes) {#int-listishape}
지정된 도형들을 도형 컬렉션 내에서 이동하며, 지정된 인덱스부터 배치합니다.


```python
def reorder(self, index, shapes):
    ...
```


| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | **int** | 첫 번째 지정된 도형이 배치될 0부터 시작하는 대상 인덱스이며, 이후 도형들은 제공된 순서대로 뒤에 배치됩니다.<br/><br/>            |
| shapes | **List[IShape]** | 컬렉션 내에서 이동할 하나 이상의 [`IShape`](/slides/python-net/ko/aspose.slides/ishape) 인스턴스입니다. |



### 참고
* 클래스 [`IShape`](/slides/python-net/ko/aspose.slides/ishape)
* 클래스 [`ShapeCollection`](/slides/python-net/ko/aspose.slides/shapecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)