---
title: add_from_html method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/slidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
Создаёт слайды из HTML-текста и добавляет их в конец коллекции.

### Возвращаемое значение
Добавленные слайды

```python
def add_from_html(self, html_text):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| html_text | **str** | HTML для добавления. |

## add_from_html(self, html_stream) {#iorawiobase}
Создаёт слайды из HTML-текста и добавляет их в конец коллекции.

### Возвращаемое значение
Добавленные слайды

```python
def add_from_html(self, html_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Объект Stream, который будет использоваться как источник HTML-файла. |

## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
Создаёт слайды из HTML-текста и добавляет их в конец коллекции.

### Возвращаемое значение
Добавленные слайды.

```python
def add_from_html(self, html_text, resolver, uri):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| html_text | **str** | HTML для добавления. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ru/aspose.slides.importing/iexternalresourceresolver) | Объект обратного вызова, используемый для получения внешних объектов. Если этот параметр None, все внешние объекты будут игнорироваться. |
| uri | **str** | URI указанного HTML. Используется для разрешения относительных ссылок. |

## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Создаёт слайды из HTML-текста и добавляет их в конец коллекции.

### Возвращаемое значение
Добавленные слайды.

```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | Объект Stream, который будет использоваться как источник HTML-файла. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ru/aspose.slides.importing/iexternalresourceresolver) | Объект обратного вызова, используемый для получения внешних объектов. Если этот параметр None, все внешние объекты будут игнорироваться. |
| uri | **str** | URI указанного HTML. Используется для разрешения относительных ссылок. |

### См. также
* класс [`IExternalResourceResolver`](/slides/python-net/ru/aspose.slides.importing/iexternalresourceresolver)
* класс [`SlideCollection`](/slides/python-net/ru/aspose.slides/slidecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)