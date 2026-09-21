---
title: remove_node method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.smartart/smartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
인덱스로 노드 또는 서브 노드를 제거합니다


```python
def remove_node(self, index):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 노드의 0 기반 인덱스 |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | index가 0보다 작습니다.  -or- index가 형제 노드 수보다 크거나 같습니다 |


## remove_node(self, node) {#ismartartnode}
노드 또는 서브 노드를 제거합니다


```python
def remove_node(self, node):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| node | [`ISmartArtNode`](/slides/python-net/ko/aspose.slides.smartart/ismartartnode) | 제거할 노드 |



### 참조
* 클래스 [`ISmartArtNode`](/slides/python-net/ko/aspose.slides.smartart/ismartartnode)
* 클래스 [`SmartArtNodeCollection`](/slides/python-net/ko/aspose.slides.smartart/smartartnodecollection)
* 모듈 [`aspose.slides.smartart`](/slides/python-net/ko/aspose.slides.smartart)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)