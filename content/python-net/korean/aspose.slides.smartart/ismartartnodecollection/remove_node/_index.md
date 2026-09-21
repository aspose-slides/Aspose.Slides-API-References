---
title: remove_node method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.smartart/ismartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
인덱스로 노드 또는 서브 노드를 제거합니다.

```python
def remove_node(self, index):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | **int** | 0부터 시작하는 노드 인덱스 |

### 예외

| 예외 | 설명 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 인덱스가 0보다 작습니다. -or- 인덱스가 형제 수와 같거나 그보다 큽니다. |

## remove_node(self, node_obj) {#ismartartnode}
노드 또는 서브 노드를 제거합니다.

```python
def remove_node(self, node_obj):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| node_obj | [`ISmartArtNode`](/slides/python-net/ko/aspose.slides.smartart/ismartartnode) | 제거할 노드. |

### 참고
* 클래스 [`ISmartArtNode`](/slides/python-net/ko/aspose.slides.smartart/ismartartnode)
* 클래스 [`ISmartArtNodeCollection`](/slides/python-net/ko/aspose.slides.smartart/ismartartnodecollection)
* 모듈 [`aspose.slides.smartart`](/slides/python-net/ko/aspose.slides.smartart)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)