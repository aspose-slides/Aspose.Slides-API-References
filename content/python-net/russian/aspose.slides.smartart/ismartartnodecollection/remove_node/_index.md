---
title: remove_node method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.smartart/ismartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Удалить узел или дочерний узел по индексу.


```python
def remove_node(self, index):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Индекс узла, исчисляемый с нуля |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | index меньше 0.  -or- index равен или больше количества соседних узлов. |


## remove_node(self, node_obj) {#ismartartnode}
Удалить узел или дочерний узел.


```python
def remove_node(self, node_obj):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| node_obj | [`ISmartArtNode`](/slides/python-net/ru/aspose.slides.smartart/ismartartnode) | Узел для удаления. |



### См. также
* класс [`ISmartArtNode`](/slides/python-net/ru/aspose.slides.smartart/ismartartnode)
* класс [`ISmartArtNodeCollection`](/slides/python-net/ru/aspose.slides.smartart/ismartartnodecollection)
* модуль [`aspose.slides.smartart`](/slides/python-net/ru/aspose.slides.smartart)
* библиотека [`Aspose.Slides`](/slides/python-net)