---
title: add method
second_title: Aspose.Slides для Python через .NET – справочник API
description: 
type: docs
url: /ru/aspose.slides/captionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
Добавляет закрытые субтитры WebVTT в конец коллекции.

### Возвращаемое значение

Добавленный экземпляр [`ICaptions`](/slides/python-net/ru/aspose.slides/icaptions).



```python
def add(self, label, file_path):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| label | **str** | Метка закрытых субтитров. |
| file_path | **str** | Путь к файлу WebVTT. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Выбрасывается, если `file_path` равен `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, если `file_path` пустой. |


## add(self, label, stream) {#str-iorawiobase}
Добавляет закрытые субтитры WebVTT в конец коллекции из потока.

### Возвращаемое значение

Добавленный экземпляр [`ICaptions`](/slides/python-net/ru/aspose.slides/icaptions).



```python
def add(self, label, stream):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| label | **str** | Метка закрытых субтитров. |
| stream | **io.RawIOBase** | Входной поток, содержащий данные в формате WebVTT. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Выбрасывается, если `stream` равен `None`. |
| **RuntimeError(Proxy error(ArgumentException))** | Выбрасывается, если входные данные не в формате WebVTT. |



### См. также
* класс [`CaptionsCollection`](/slides/python-net/ru/aspose.slides/captionscollection)
* класс [`ICaptions`](/slides/python-net/ru/aspose.slides/icaptions)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)