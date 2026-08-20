---
title: IInkOptions
second_title: Aspose.Slides for Java API Reference
description: एक्सपोर्ट किए गए दस्तावेज़ में Ink ऑब्जेक्ट्स की दिखावट को नियंत्रित करने के विकल्प प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

एक्सपोर्ट किए गए दस्तावेज़ में Ink ऑब्जेक्ट्स की दिखावट को नियंत्रित करने के विकल्प प्रदान करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getHideInk()](#getHideInk--) | एक्सपोर्ट किए गए दस्तावेज़ में Ink तत्वों को दिखाता या छुपाता है। |
| [setHideInk(boolean value)](#setHideInk-boolean-) | एक्सपोर्ट किए गए दस्तावेज़ में Ink तत्वों को दिखाता या छुपाता है। |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | ब्रश के रेंडरिंग के लिए ROP ऑपरेशन या अपाकिटी का उपयोग करता है। |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | ब्रश के रेंडरिंग के लिए ROP ऑपरेशन या अपाकिटी का उपयोग करता है। |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
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

**वापसी मान:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public abstract void setHideInk(boolean value)
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
public abstract boolean getInterpretMaskOpAsOpacity()
```

ब्रश के रेंडरिंग के लिए ROP ऑपरेशन या अपाकिटी का उपयोग करता है।

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

**वापसी मान:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```

ब्रश के रेंडरिंग के लिए ROP ऑपरेशन या अपाकिटी का उपयोग करता है।

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