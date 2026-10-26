---
title: InkOptions
second_title: Aspose.Slides for Android عبر مرجع واجهة برمجة تطبيقات Java
description: يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المصدَّر.
type: docs
url: /ar/com.aspose.slides/inkoptions/
---
**الإرث:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
```

يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المصدَّر.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getHideInk()](#getHideInk--) | يعرض أو يخفي عناصر الحبر في المستند المصدَّر. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | يعرض أو يخفي عناصر الحبر في المستند المصدَّر. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | يستخدم عملية ROP أو الشفافية لتصيير الفرشاة. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | يستخدم عملية ROP أو الشفافية لتصيير الفرشاة. |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
```

يعرض أو يخفي عناصر الحبر في المستند المصدَّر.

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

**القيمة المرجعة:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public final void setHideInk(boolean value)
```

يعرض أو يخفي عناصر الحبر في المستند المصدَّر.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public final boolean getInterpretMaskOpAsOpacity()
```

يستخدم عملية ROP أو الشفافية لتصيير الفرشاة.

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

القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```

يستخدم عملية ROP أو الشفافية لتصيير الفرشاة.

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

القيمة الافتراضية هي true.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |