---
title: IInkOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Предоставляет параметры, которые управляют внешним видом объектов Ink в экспортируемом документе.
type: docs
url: /ru/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

Предоставляет параметры, которые управляют внешним видом объектов Ink в экспортируемом документе.
## Методы

| Метод | Описание |
| --- | --- |
| [getHideInk()](#getHideInk--) | Отображает или скрывает элементы Ink в экспортируемом документе. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Отображает или скрывает элементы Ink в экспортируемом документе. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Использует операцию ROP или непрозрачность для отрисовки кисти. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Использует операцию ROP или непрозрачность для отрисовки кисти. |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
```


Отображает или скрывает элементы Ink в экспортируемом документе.

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

Значение по умолчанию — false.

**Возвращаемое значение:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public abstract void setHideInk(boolean value)
```


Отображает или скрывает элементы Ink в экспортируемом документе.

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

Значение по умолчанию — false.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public abstract boolean getInterpretMaskOpAsOpacity()
```


Использует операцию ROP или непрозрачность для отрисовки кисти.

--------------------

> ```
> Следующий пример демонстрирует, как установить использование ROP для экспорта элементов Ink:
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

Значение по умолчанию — true.

**Возвращаемое значение:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```


Использует операцию ROP или непрозрачность для отрисовки кисти.

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

Значение по умолчанию — true.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |