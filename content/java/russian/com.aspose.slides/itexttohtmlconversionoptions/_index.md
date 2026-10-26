---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Java API Reference
description: Options for extracting HTML from the Pptx text.
type: docs
url: /ru/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

Параметры извлечения HTML из текста Pptx.
## Методы

| Метод | Описание |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | Возвращает или задает значение, указывающее, должны ли добавляться заголовки Clipboard. |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | Возвращает или задает значение, указывающее, должны ли добавляться заголовки Clipboard. |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | Возвращает или задает наследуемую глубину для текстовых свойств. |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | Возвращает или задает наследуемую глубину для текстовых свойств. |
| [getLinkEmbedController()](#getLinkEmbedController--) | Возвращает или задает объект обратного вызова, который контролирует, как будет сохраняться внешний объект. |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | Возвращает или задает объект обратного вызова, который контролирует, как будет сохраняться внешний объект. |
| [getEncodingName()](#getEncodingName--) | Возвращает или задает имя кодировки HTML. |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | Возвращает или задает имя кодировки HTML. |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```


Возвращает или задает значение, указывающее, должны ли добавляться заголовки Clipboard. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```


Возвращает или задает значение, указывающее, должны ли добавляться заголовки Clipboard. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```


Возвращает или задает наследуемую глубину для текстовых свойств. Чтение/запись [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Возвращаемое значение:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```


Возвращает или задает наследуемую глубину для текстовых свойств. Чтение/запись [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int)).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```


Возвращает или задает объект обратного вызова, который контролирует, как будет сохраняться внешний объект. Чтение/запись [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Возвращаемое значение:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```


Возвращает или задает объект обратного вызова, который контролирует, как будет сохраняться внешний объект. Чтение/запись [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```


Возвращает или задает имя кодировки HTML. Это значение будет сохранено в сгенерированном файле HTML, но ответственность за сохранение файла в этой кодировке лежит на вызывающем. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```


Возвращает или задает имя кодировки HTML. Это значение будет сохранено в сгенерированном файле HTML, но ответственность за сохранение файла в этой кодировке лежит на вызывающем. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |