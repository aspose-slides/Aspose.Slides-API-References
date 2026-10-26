---
title: IInkOptions
second_title: Aspose.Slides for Android via Java API Reference
description: گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند صادر شده کنترل می‌کنند.
type: docs
url: /fa/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند صادر شده کنترل می‌کنند.
## متدها

| متد | توضیح |
| --- | --- |
| [getHideInk()](#getHideInk--) | نمایش یا مخفی‌سازی عناصر Ink در سند صادر شده. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | نمایش یا مخفی‌سازی عناصر Ink در سند صادر شده. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | از عملیات ROP یا Opacity برای رندر کردن قلم‌مو استفاده می‌کند. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | از عملیات ROP یا Opacity برای رندر کردن قلم‌مو استفاده می‌کند. |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
```

نمایش یا مخفی‌سازی عناصر Ink در سند صادر شده.

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

مقدار پیش‌فرض false است.

**بازگشت:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public abstract void setHideInk(boolean value)
```

نمایش یا مخفی‌سازی عناصر Ink در سند صادر شده.

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

مقدار پیش‌فرض false است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public abstract boolean getInterpretMaskOpAsOpacity()
```

از عملیات ROP یا Opacity برای رندر کردن قلم‌مو استفاده می‌کند.

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

مقدار پیش‌فرض true است.

**بازگشت:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```

از عملیات ROP یا Opacity برای رندر کردن قلم‌مو استفاده می‌کند.

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

مقدار پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |