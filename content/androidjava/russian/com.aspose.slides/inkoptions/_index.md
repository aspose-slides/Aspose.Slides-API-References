---
title: InkOptions
second_title: Aspose.Slides для Android через справочник Java API
description: Предоставляет параметры, управляющие внешним видом объектов Ink в экспортируемом документе.
type: docs
url: /ru/com.aspose.slides/inkoptions/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
```

Предоставляет параметры, управляющие внешним видом объектов Ink в экспортируемом документе.
## Методы

| Метод | Описание |
| --- | --- |
| [getHideInk()](#getHideInk--) | Отображает или скрывает элементы Ink в экспортируемом документе. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Отображает или скрывает элементы Ink в экспортируемом документе. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Использует операцию ROP или непрозрачность для рендеринга кисти. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Использует операцию ROP или непрозрачность для рендеринга кисти. |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
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
public final void setHideInk(boolean value)
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
public final boolean getInterpretMaskOpAsOpacity()
```

Использует операцию ROP или непрозрачность для рендеринга кисти.

--------------------

> ```
> Next example demonstrates how to set using ROP for expotring Ink elements:
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
public final void setInterpretMaskOpAsOpacity(boolean value)
```

Использует операцию ROP или непрозрачность для рендеринга кисти.

--------------------

> ```
> Next example demonstrates how to set using ROP for expotring Ink elements:
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