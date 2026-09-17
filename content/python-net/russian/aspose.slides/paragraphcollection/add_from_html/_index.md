---
title: add_from_html method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/paragraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Добавляет текст из указанной HTML-строки в коллекцию.


```python
def add_from_html(self, text):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| text | **str** | HTML text. |


## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Добавляет текст из указанной HTML-строки в коллекцию.


```python
def add_from_html(self, text, resolver, uri):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| text | **str** | HTML text. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ru/aspose.slides.importing/iexternalresourceresolver) | Объект обратного вызова резольвера, который разрешает URI и получает ссылки на объекты. |
| uri | **str** | URI для добавления HTML-документа. Используется для разрешения относительных ссылок. |

### Замечания

Указание резольвера может потенциально привести к уязвимости. Используйте с осторожностью.



### См. также
* класс [`IExternalResourceResolver`](/slides/python-net/ru/aspose.slides.importing/iexternalresourceresolver)
* класс [`ParagraphCollection`](/slides/python-net/ru/aspose.slides/paragraphcollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)