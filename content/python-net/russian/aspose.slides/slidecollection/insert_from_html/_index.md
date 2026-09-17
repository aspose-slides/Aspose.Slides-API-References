---
title: insert_from_html method
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides/slidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

### Возвращаемое значение

Добавленные слайды



```python
def insert_from_html(self, index, html_text):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Позиция для вставки. |
| html_text | **str** | HTML для добавления. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

### Возвращаемое значение

Добавленные слайды



```python
def insert_from_html(self, index, html_stream):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Позиция для вставки. |
| html_stream | **io.RawIOBase** | Объект Stream, который будет использоваться как источник HTML-файла. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

### Возвращаемое значение

Добавленные слайды



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Позиция для вставки. |
| html_text | **str** | HTML для добавления. |
| use_slide_with_index_as_start | **bool** | Этот флаг определяет, как начинать вставку: с нового слайда или со слайда с указанным индексом.<br/><br/>            Если **true**, то вставка данных начнётся с пустого пространства на слайде с указанным индексом.<br/><br/>            Если **false**, то данные будут добавлены к созданным слайдам. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

### Возвращаемое значение

Добавленные слайды



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Позиция для вставки. |
| html_stream | **io.RawIOBase** | Объект Stream, который будет использоваться как источник HTML-файла. |
| use_slide_with_index_as_start | **bool** | Этот флаг определяет, как начинать вставку: с нового слайда или со слайда с указанным индексом.<br/><br/>            Если **true**, то вставка данных начнётся с пустого пространства на слайде с указанным индексом.<br/><br/>            Если **false**, то данные будут добавлены к созданным слайдам. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

### Возвращаемое значение

Добавленные слайды.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Позиция для вставки. |
| html_text | **str** | HTML для добавления. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ru/aspose.slides.importing/iexternalresourceresolver) | Объект-колбэк, используемый для получения внешних объектов. Если этот параметр равен None, все внешние объекты будут игнорироваться. |
| uri | **str** | URI указанного HTML. Используется для разрешения относительных ссылок. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

### Возвращаемое значение

Добавленные слайды.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Позиция для вставки. |
| html_stream | **io.RawIOBase** | Объект Stream, который будет использоваться как источник HTML-файла. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ru/aspose.slides.importing/iexternalresourceresolver) | Объект-колбэк, используемый для получения внешних объектов. Если этот параметр равен None, все внешние объекты будут игнорироваться. |
| uri | **str** | URI указанного HTML. Используется для разрешения относительных ссылок. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

### Возвращаемое значение

Добавленные слайды.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Позиция для вставки. |
| html_text | **str** | HTML для добавления. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ru/aspose.slides.importing/iexternalresourceresolver) | Объект-колбэк, используемый для получения внешних объектов. Если этот параметр равен None, все внешние объекты будут игнорироваться. |
| uri | **str** | URI указанного HTML. Используется для разрешения относительных ссылок. |
| use_slide_with_index_as_start | **bool** | Этот флаг определяет, как начинать вставку: с нового слайда или со слайда с указанным индексом.<br/><br/>            Если **true**, то вставка данных начнётся с пустого пространства на слайде с указанным индексом.<br/><br/>            Если **false**, то данные будут добавлены к созданным слайдам. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

### Возвращаемое значение

Добавленные слайды.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Позиция для вставки. |
| html_stream | **io.RawIOBase** | Объект Stream, который будет использоваться как источник HTML-файла. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ru/aspose.slides.importing/iexternalresourceresolver) | Объект-колбэк, используемый для получения внешних объектов. Если этот параметр равен None, все внешние объекты будут игнорироваться. |
| uri | **str** | URI указанного HTML. Используется для разрешения относительных ссылок. |
| use_slide_with_index_as_start | **bool** | Этот флаг определяет, как начинать вставку: с нового слайда или со слайда с указанным индексом.<br/><br/>            Если **true**, то вставка данных начнётся с пустого пространства на слайде с указанным индексом.<br/><br/>            Если **false**, то данные будут добавлены к созданным слайдам. |



### См. также
* класс [`IExternalResourceResolver`](/slides/python-net/ru/aspose.slides.importing/iexternalresourceresolver)
* класс [`SlideCollection`](/slides/python-net/ru/aspose.slides/slidecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)