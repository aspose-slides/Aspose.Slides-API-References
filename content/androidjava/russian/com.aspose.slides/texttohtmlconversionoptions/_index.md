---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides для Android через справочник Java API
description: Параметры для извлечения HTML из текста Pptx.
type: docs
url: /ru/com.aspose.slides/texttohtmlconversionoptions/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

Параметры для извлечения HTML из текста Pptx.
## Конструкторы

| Constructor | Описание |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## Методы

| Method | Описание |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Возвращает или задает значение, указывающее, следует ли добавлять заголовки буфера обмена. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Возвращает или задает значение, указывающее, следует ли добавлять заголовки буфера обмена. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Возвращает или задает наследуемую глубину для текстовых свойств. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Возвращает или задает наследуемую глубину для текстовых свойств. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Возвращает или задает объект обратного вызова, контролирующий, как будет сохраняться внешнее объект. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Возвращает или задает объект обратного вызова, контролирующий, как будет сохраняться внешнее объект. |
| [getEncodingName()](#getEncodingName--) | Возвращает или задает имя кодировки HTML. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Возвращает или задает имя кодировки HTML. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


Возвращает или задает значение, указывающее, следует ли добавлять заголовки буфера обмена. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


Возвращает или задает значение, указывающее, следует ли добавлять заголовки буфера обмена. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


Возвращает или задает наследуемую глубину для текстовых свойств. Чтение/запись [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Возвращаемое значение:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


Возвращает или задает наследуемую глубину для текстовых свойств. Чтение/запись [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


Возвращает или задает объект обратного вызова, контролирующий, как будет сохраняться внешнее объект. Чтение/запись [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Возвращаемое значение:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


Возвращает или задает объект обратного вызова, контролирующий, как будет сохраняться внешнее объект. Чтение/запись [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


Возвращает или задает имя кодировки HTML. Это значение будет сохранено в сгенерированном HTML-файле, но ответственность за сохранение файла в этой кодировке лежит на вызывающем. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


Возвращает или задает имя кодировки HTML. Это значение будет сохранено в сгенерированном HTML-файле, но ответственность за сохранение файла в этой кодировке лежит на вызывающем. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |