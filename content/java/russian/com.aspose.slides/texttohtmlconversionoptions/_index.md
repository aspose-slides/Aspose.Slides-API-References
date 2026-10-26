---
title: TextToHtmlConversionOptions
second_title: Справочник API Aspose.Slides для Java
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

Параметры извлечения HTML из текста Pptx.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Возвращает или задает значение, указывающее, следует ли добавлять заголовки буфера обмена. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Возвращает или задает значение, указывающее, следует ли добавлять заголовки буфера обмена. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Возвращает или задает глубину наследования для текстовых свойств. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Возвращает или задает глубину наследования для текстовых свойств. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Возвращает или задает объект обратного вызова, который контролирует, как будет сохраняться внешний объект. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Возвращает или задает объект обратного вызова, который контролирует, как будет сохраняться внешний объект. |
| [getEncodingName()](#getEncodingName--) | Возвращает или задает название кодировки HTML. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Возвращает или задает название кодировки HTML. |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


Возвращает или задает значение, указывающее, следует ли добавлять заголовки буфера обмена. Чтение/запись boolean.

**Возвращает:**
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


Возвращает или задает глубину наследования для текстовых свойств. Чтение/запись [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Возвращает:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


Возвращает или задает глубину наследования для текстовых свойств. Чтение/запись [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


Возвращает или задает объект обратного вызова, который контролирует, как будет сохраняться внешний объект. Чтение/запись [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Возвращает:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


Возвращает или задает объект обратного вызова, который контролирует, как будет сохраняться внешний объект. Чтение/запись [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


Возвращает или задает название кодировки HTML. Это значение будет сохранено в сгенерированном HTML-файле, но его контроль за тем, чтобы файл сохранялся в этой кодировке, лежит на вызывающем. Чтение/запись String.

**Возвращает:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


Возвращает или задает название кодировки HTML. Это значение будет сохранено в сгенерированном HTML-файле, но его контроль за тем, чтобы файл сохранялся в этой кодировке, лежит на вызывающем. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |