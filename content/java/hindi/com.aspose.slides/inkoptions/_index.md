---
title: InkOptions
second_title: Aspose.Slides for Java API संदर्भ
description: एक्सपोर्ट किए गए दस्तावेज़ में Ink वस्तुओं की उपस्थिति को नियंत्रित करने के विकल्प प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/inkoptions/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
```

एक्सपोर्ट किए गए दस्तावेज़ में Ink वस्तुओं की उपस्थिति को नियंत्रित करने के विकल्प प्रदान करता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [getHideInk()](#getHideInk--) | एक्सपोर्ट किए गए दस्तावेज़ में Ink तत्वों को दिखाता या छुपाता है। |
| [setHideInk(boolean value)](#setHideInk-boolean-) | एक्सपोर्ट किए गए दस्तावेज़ में Ink तत्वों को दिखाता या छुपाता है। |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | ब्रश को रेंडर करने के लिए ROP ऑपरेशन या Opacity का उपयोग करता है। |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | ब्रश को रेंडर करने के लिए ROP ऑपरेशन या Opacity का उपयोग करता है। |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
```


एक्सपोर्ट किए गए दस्तावेज़ में Ink तत्वों को दिखाता या छुपाता है।

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

**रिटर्न मान:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public final void setHideInk(boolean value)
```


एक्सपोर्ट किए गए दस्तावेज़ में Ink तत्वों को दिखाता या छुपाता है।

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
public final boolean getInterpretMaskOpAsOpacity()
```


ब्रश को रेंडर करने के लिए ROP ऑपरेशन या Opacity का उपयोग करता है।

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

डिफ़ॉल्ट मान true है।

**रिटर्न मान:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```


ब्रश को रेंडर करने के लिए ROP ऑपरेशन या Opacity का उपयोग करता है।

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

डिफ़ॉल्ट मान true है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |