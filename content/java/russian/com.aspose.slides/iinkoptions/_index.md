---
title: IInkOptions
second_title: Aspose.Slides for Java API Reference
description: Provides options that control the look of Ink objects in exported document.
type: docs
url: /ru/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

Предоставляет параметры, управляющие внешним видом объектов Ink в экспортированном документе.
## Методы

| Метод | Описание |
| --- | --- |
| [getHideInk()](#getHideInk--) | Показывает или скрывает элементы Ink в экспортированном документе. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Показывает или скрывает элементы Ink в экспортированном документе. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Использует операцию ROP или непрозрачность для рендеринга кисти. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Использует операцию ROP или непрозрачность для рендеринга кисти. |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
```


Показывает или скрывает элементы Ink в экспортированном документе.

--------------------

> ```
> Next example demonstrates how to hide Ink elements in exported PDF document:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setHideInk(true);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Значение по умолчанию: false.

**Возвращаемое значение:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public abstract void setHideInk(boolean value)
```


Показывает или скрывает элементы Ink в экспортированном документе.

--------------------

> ```
> Next example demonstrates how to hide Ink elements in exported PDF document:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setHideInk(true);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Значение по умолчанию: false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public abstract boolean getInterpretMaskOpAsOpacity()
```


Использует операцию ROP или непрозрачность для рендеринга кисти.

--------------------

> ```
> Next example demonstrates how to set using ROP for exporting Ink elements:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setInterpretMaskOpAsOpacity(false);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Значение по умолчанию: true.

**Возвращаемое значение:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```


Использует операцию ROP или непрозрачность для рендеринга кисти.

--------------------

> ```
> Next example demonstrates how to set using ROP for exporting Ink elements:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setInterpretMaskOpAsOpacity(false);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Значение по умолчанию: true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |