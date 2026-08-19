---
title: InkOptions
second_title: Aspose.Slides برای مرجع API جاوا
description: گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند صادر شده کنترل می‌کند.
type: docs
url: /fa/com.aspose.slides/inkoptions/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
```

گزینه‌هایی را فراهم می‌کند که ظاهر اشیاء Ink را در سند صادرشده کنترل می‌کنند.
## متدها

| متد | توضیح |
| --- | --- |
| [getHideInk()](#getHideInk--) | عناصر Ink را در سند صادرشده نشان می‌دهد یا پنهان می‌کند. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | عناصر Ink را در سند صادرشده نشان می‌دهد یا پنهان می‌کند. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | از عملیات ROP یا شفافیت برای رندر کردن قلم‌مو استفاده می‌کند. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | از عملیات ROP یا شفافیت برای رندر کردن قلم‌مو استفاده می‌کند. |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
```


عناصر Ink را در سند صادرشده نشان می‌دهد یا پنهان می‌کند.

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

**بازگرداندن:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public final void setHideInk(boolean value)
```


عناصر Ink را در سند صادرشده نشان می‌دهد یا پنهان می‌کند.

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
public final boolean getInterpretMaskOpAsOpacity()
```


از عملیات ROP یا شفافیت برای رندر کردن قلم‌مو استفاده می‌کند.

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

مقدار پیش‌فرض true است.

**بازگرداندن:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```


از عملیات ROP یا شفافیت برای رندر کردن قلم‌مو استفاده می‌کند.

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

مقدار پیش‌فرض true است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |