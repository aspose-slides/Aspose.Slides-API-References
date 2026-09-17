---
title: add_from_html method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/iparagraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
Добавляет текст из указанной строки HTML в коллекцию.

```python
def add_from_html(self, text):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | **str** | HTML-текст. |

## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Добавляет текст из указанной строки HTML в коллекцию.

```python
def add_from_html(self, text, resolver, uri):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | **str** | HTML-текст. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ru/aspose.slides.importing/iexternalresourceresolver) | Объект обратного вызова Resolver, который разрешает URI и получает ссылочные объекты. |
| uri | **str** | URI для добавления HTML-документа. Используется для разрешения относительных ссылок. |

### Примечания

Указание resolver может потенциально создать уязвимость. Используйте с осторожностью.

### Смотрите также
* класс [`IExternalResourceResolver`](/slides/python-net/ru/aspose.slides.importing/iexternalresourceresolver)
* класс [`IParagraphCollection`](/slides/python-net/ru/aspose.slides/iparagraphcollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)