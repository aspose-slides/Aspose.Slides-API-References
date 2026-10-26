---
title: SaveOptions
second_title: Aspose.Slides для Android через справочник Java API
description: Абстрактный класс с параметрами, управляющими тем, как сохраняется презентация.
type: docs
url: /ru/com.aspose.slides/saveoptions/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

Абстрактный класс с параметрами, которые управляют тем, как презентация сохраняется.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Возвращает или задает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или прерван. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Возвращает или задает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или прерван. |
| [getProgressCallback()](#getProgressCallback--) | Представляет объект обратного вызова для обновления прогресса сохранения в процентах. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Представляет объект обратного вызова для обновления прогресса сохранения в процентах. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Возвращает или задает шрифт, используемый в случае, если исходный шрифт не найден. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Возвращает или задает шрифт, используемый в случае, если исходный шрифт не найден. |
| [getGradientStyle()](#getGradientStyle--) | Возвращает или задает визуальный стиль градиента. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Возвращает или задает визуальный стиль градиента. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


Возвращает или задает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или прерван. Чтение/запись [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Возвращаемое значение:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


Возвращает или задает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или прерван. Чтение/запись [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```


Представляет объект обратного вызова для обновления прогресса сохранения в процентах. См. [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Возвращаемое значение:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```


Представляет объект обратного вызова для обновления прогресса сохранения в процентах. См. [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


Возвращает или задает шрифт, используемый в случае, если исходный шрифт не найден. Чтение/запись String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```


Возвращает или задает шрифт, используемый в случае, если исходный шрифт не найден. Чтение/запись String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getGradientStyle() {#getGradientStyle--}
```
public final int getGradientStyle()
```


Возвращает или задает визуальный стиль градиента. Чтение/запись [GradientStyle](../../com.aspose.slides/gradientstyle).

**Возвращаемое значение:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```


Возвращает или задает визуальный стиль градиента. Чтение/запись [GradientStyle](../../com.aspose.slides/gradientstyle).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```


Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Чтение/запись boolean. Значение по умолчанию — false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Когда это свойство установлено в true, гиперссылки с вызовами JavaScript будут игнорироваться при сохранении.

Когда это свойство установлено в false, все гиперссылки будут сохранены.

**Возвращаемое значение:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```


Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Чтение/запись boolean. Значение по умолчанию — false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Когда это свойство установлено в true, гиперссылки с вызовами JavaScript будут игнорироваться при сохранении.

Когда это свойство установлено в false, все гиперссылки будут сохранены.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |