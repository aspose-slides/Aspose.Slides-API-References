---
title: set_embedded_data method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/ioleobjectframe/set_embedded_data/
weight: 50
---
## set_embedded_data(self, embedded_data) {#ioleembeddeddatainfo}
Устанавливает информацию о встроенных OLE-данных.


```python
def set_embedded_data(self, embedded_data):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/ru/aspose.slides/ioleembeddeddatainfo) | Встроенные данные [`IOleEmbeddedDataInfo`](/slides/python-net/ru/aspose.slides/ioleembeddeddatainfo) |

### Примечания

Этот метод изменяет свойства объекта, чтобы отразить новые данные и 
            устанавливает флаг IsObjectLink в false, указывая, что OLE-объект встроен.

### Исключения

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Когда параметр embeddedData равен None. |



### См. также
* класс [`IOleEmbeddedDataInfo`](/slides/python-net/ru/aspose.slides/ioleembeddeddatainfo)
* класс [`IOleObjectFrame`](/slides/python-net/ru/aspose.slides/ioleobjectframe)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)