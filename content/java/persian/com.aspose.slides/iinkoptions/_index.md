---
title: IInkOptions
second_title: Aspose.Slides برای Java مرجع API
description: گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink را در سند صادر شده کنترل می‌کنند.
type: docs
url: /fa/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

گزینه‌هایی را فراهم می‌کند که ظاهر اشیای Ink را در سند صادر شده کنترل می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getHideInk()](#getHideInk--) | عناصر Ink را در سند صادر شده نشان می‌دهد یا پنهان می‌کند. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | عناصر Ink را در سند صادر شده نشان می‌دهد یا پنهان می‌کند. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | از عملیات ROP یا شفافیت برای رسم قلم‌مو استفاده می‌کند. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | از عملیات ROP یا شفافیت برای رسم قلم‌مو استفاده می‌کند. |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
```

عناصر Ink را در سند صادر شده نشان می‌دهد یا پنهان می‌کند.

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

**بازمی‌گرداند:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public abstract void setHideInk(boolean value)
```

عناصر Ink را در سند صادر شده نشان می‌دهد یا پنهان می‌کند.

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

از عملیات ROP یا شفافیت برای رسم قلم‌مو استفاده می‌کند.

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

**بازمی‌گرداند:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```

از عملیات ROP یا شفافیت برای رسم قلم‌مو استفاده می‌کند.

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