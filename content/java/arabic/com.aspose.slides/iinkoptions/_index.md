---
title: IInkOptions
second_title: Aspose.Slides for Java API Reference
description: يوفر خيارات تتحكم في مظهر كائنات Ink في المستند المُصدَّر.
type: docs
url: /ar/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

يوفر خيارات تتحكم في مظهر كائنات Ink في المستند المُصدَّر.
## الأساليب

| طريقة | الوصف |
| --- | --- |
| [getHideInk()](#getHideInk--) | يعرض أو يخفي عناصر Ink في المستند المُصدَّر. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | يعرض أو يخفي عناصر Ink في المستند المُصدَّر. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | يستخدم عملية ROP أو Opacity لتجسيد الفرشاة. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | يستخدم عملية ROP أو Opacity لتجسيد الفرشاة. |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
```


يعرض أو يخفي عناصر Ink في المستند المُصدَّر.

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

القيمة الافتراضية هي false.

**الإرجاع:**  
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public abstract void setHideInk(boolean value)
```


يعرض أو يخفي عناصر Ink في المستند المُصدَّر.

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

القيمة الافتراضية هي false.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public abstract boolean getInterpretMaskOpAsOpacity()
```


يستخدم عملية ROP أو Opacity لتجسيد الفرشاة.

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

القيمة الافتراضية هي true.

**الإرجاع:**  
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```


يستخدم عملية ROP أو Opacity لتجسيد الفرشاة.

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

القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |