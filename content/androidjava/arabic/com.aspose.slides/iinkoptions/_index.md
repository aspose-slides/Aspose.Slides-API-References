---
title: IInkOptions
second_title: Aspose.Slides for Android via Java API Reference
description: يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدَّر.
type: docs
url: /ar/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدَّر.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getHideInk()](#getHideInk--) | Shows or hides Ink elements in exported document. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Shows or hides Ink elements in exported document. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Uses ROP operation or Opacity for rendering brush. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Uses ROP operation or Opacity for rendering brush. |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
```

يعرض أو يخفي عناصر الحبر في المستند المُصدَّر.

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

**القيمة المرتجعة:**  
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public abstract void setHideInk(boolean value)
```

يعرض أو يخفي عناصر الحبر في المستند المُصدَّر.

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

يستخدم عملية ROP أو Opacity لتجسيد brush.

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

**القيمة المرتجعة:**  
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```

يستخدم عملية ROP أو Opacity لتجسيد brush.

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