---
title: reorder method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/ishapecollection/reorder/
weight: 370
---
## reorder(self, index, shape) {#int-ishape}
지정된 shape을 shape 컬렉션 내의 새로운 위치로 이동합니다.

```python
def reorder(self, index, shape):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | **int** | shape이 배치될 0 기반 대상 인덱스입니다. |
| shape | [`IShape`](/slides/python-net/ko/aspose.slides/ishape) | [`IShape`](/slides/python-net/ko/aspose.slides/ishape) 컬렉션 내에서 이동할 |

## reorder(self, index, shapes) {#int-listishape}
지정된 shapes를 shape 컬렉션 내에서 이동시키며, 주어진 인덱스부터 배치합니다.

```python
def reorder(self, index, shapes):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| index | **int** | 첫 번째 지정된 shape이 배치될 0 기반 대상 인덱스이며;<br/><br/>            이후 shape들은 제공된 순서대로 따라갑니다. |
| shapes | **List[IShape]** | 컬렉션 내에서 이동할 하나 이상의 [`IShape`](/slides/python-net/ko/aspose.slides/ishape) 인스턴스. |

### 참고
* 클래스 [`IShape`](/slides/python-net/ko/aspose.slides/ishape)
* 클래스 [`IShapeCollection`](/slides/python-net/ko/aspose.slides/ishapecollection)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)