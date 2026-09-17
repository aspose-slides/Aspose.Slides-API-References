---
title: remove_node method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.smartart/smartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
Удалить узел или подузел по индексу


```python
def remove_node(self, index):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Индекс узла, начиная с нуля |


### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | index меньше 0.  -or- index равен или больше количества соседних узлов |


## remove_node(self, node) {#ismartartnode}
Удалить узел или подузел


```python
def remove_node(self, node):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| node | [`ISmartArtNode`](/slides/python-net/ru/aspose.slides.smartart/ismartartnode) | Узел для удаления |



### См. также
* класс [`ISmartArtNode`](/slides/python-net/ru/aspose.slides.smartart/ismartartnode)
* класс [`SmartArtNodeCollection`](/slides/python-net/ru/aspose.slides.smartart/smartartnodecollection)
* модуль [`aspose.slides.smartart`](/slides/python-net/ru/aspose.slides.smartart)
* библиотека [`Aspose.Slides`](/slides/python-net)