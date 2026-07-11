---
title: WebDocument
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет форму перехода презентации для сохранения в веб-формате.
type: docs
url: /ru/com.aspose.slides/webdocument/
---
**Наследование:**
java.lang.Object
```
public class WebDocument
```

Представляет форму перехода презентации для сохранения в веб-формате.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) конструктор. |
## Методы

| Метод | Описание |
| --- | --- |
| [save()](#save--) | Сохраняет вывод документа. |
| [getInput()](#getInput--) | Возвращает коллекцию входных элементов (шаблонов) документа. |
| [getOutput()](#getOutput--) | Возвращает коллекцию выходных элементов документа. |
| [getGlobal()](#getGlobal--) | Возвращает глобальное хранилище документа. |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```


[WebDocument](../../com.aspose.slides/webdocument) конструктор.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | Параметры, задаваемые для документа. |

### save() {#save--}
```
public final void save()
```


Сохраняет вывод документа.

### getInput() {#getInput--}
```
public final Input getInput()
```


Возвращает коллекцию входных элементов (шаблонов) документа. Только для чтения [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**Возвращаемое значение:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


Возвращает коллекцию выходных элементов документа. Только для чтения [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // задать свойство "slideMargin" для использования в шаблонах
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... настроить другие параметры документа, а затем сохранить документ
>   document.save();
> ```

**Возвращаемое значение:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


Возвращает глобальное хранилище документа. Только для чтения [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // задать свойство "slideMargin" для использования в шаблонах
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... настроить другие параметры документа, а затем сохранить документ
>   document.save();
> ```

**Возвращаемое значение:**
[Storage](../../com.aspose.slides/storage)