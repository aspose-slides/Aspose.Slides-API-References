---
title: IInkOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Provides options that control the look of Ink objects in exported document.
type: docs
url: /hi/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

निर्यातित दस्तावेज़ में Ink वस्तुओं की दिखावट को नियंत्रित करने वाले विकल्प प्रदान करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getHideInk()](#getHideInk--) | निर्यातित दस्तावेज़ में Ink तत्वों को दिखाता या छुपाता है। |
| [setHideInk(boolean value)](#setHideInk-boolean-) | निर्यातित दस्तावेज़ में Ink तत्वों को दिखाता या छुपाता है। |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | ब्रश को रेंडर करने के लिए ROP संचालन या अपारदर्शिता का उपयोग करता है। |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | ब्रश को रेंडर करने के लिए ROP संचालन या अपारदर्शिता का उपयोग करता है। |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
```

निर्यातित दस्तावेज़ में Ink तत्वों को दिखाता या छुपाता है।

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

डिफ़ॉल्ट मान false है।

**वापसी:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public abstract void setHideInk(boolean value)
```

निर्यातित दस्तावेज़ में Ink तत्वों को दिखाता या छुपाता है।

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

डिफ़ॉल्ट मान false है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public abstract boolean getInterpretMaskOpAsOpacity()
```

ब्रश को रेंडर करने के लिए ROP संचालन या अपारदर्शिता का उपयोग करता है।

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

डिफ़ॉल्ट मान true है।

**वापसी:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```

ब्रश को रेंडर करने के लिए ROP संचालन या अपारदर्शिता का उपयोग करता है।

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

डिफ़ॉल्ट मान true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |