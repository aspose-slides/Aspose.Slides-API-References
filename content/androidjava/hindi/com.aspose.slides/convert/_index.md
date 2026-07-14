---
title: Convert
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: परिवर्तित करने के लिए अभिप्रेत विधियों का एक समूह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/convert/
---
**विरासत:**  
java.lang.Object  
```
public class Convert
```

[Presentation](../../com.aspose.slides/presentation) को परिवर्तित करने के लिए अभिप्रेत विधियों का एक समूह दर्शाता है।

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [Convert()](#Convert--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation) को पास किए गए आउटपुट पाथ एक्सटेंशन का उपयोग करके आवश्यक निर्यात प्रारूप निर्धारित करने के लिए परिवर्तित करता है। |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation) को PDF में परिवर्तित करता है। |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | [Presentation](../../com.aspose.slides/presentation) को PDF में परिवर्तित करता है। |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation) को PDF में परिवर्तित करता है। |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | [Presentation](../../com.aspose.slides/presentation) को PDF में परिवर्तित करता है। |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation) को SVG में परिवर्तित करता है। |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | [Presentation](../../com.aspose.slides/presentation) को SVG में परिवर्तित करता है। |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | [Presentation](../../com.aspose.slides/presentation) को SVG में परिवर्तित करता है। |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | [Presentation](../../com.aspose.slides/presentation) को SVG में परिवर्तित करता है। |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | [Presentation](../../com.aspose.slides/presentation) को SVG में परिवर्तित करता है। |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | इनपुट प्रस्तुति को JPEG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। |
| [toJpeg(Presentation pres, String outputFileName, Size imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | इनपुट प्रस्तुति को JPEG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | इनपुट प्रस्तुति को JPEG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | इनपुट प्रस्तुति को PNG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। |
| [toPng(Presentation pres, String outputFileName, Size imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-) | इनपुट प्रस्तुति को PNG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | इनपुट प्रस्तुति को PNG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | इनपुट प्रस्तुति को TIFF फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | इनपुट प्रस्तुति को कस्टम विकल्पों के साथ TIFF फ़ॉर्मेट में परिवर्तित करता है। |
### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

[Presentation](../../com.aspose.slides/presentation) को पास किए गए आउटपुट पाथ एक्सटेंशन का उपयोग करके आवश्यक निर्यात प्रारूप निर्धारित करने के लिए परिवर्तित करता है।

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presPath | java.lang.String | इनपुट प्रस्तुति का पाथ |
| outPath | java.lang.String | आउटपुट पाथ |
### toPdf(String presPath, String outPath) {#toPdf-java.lang.String-java.lang.String-}
```
public static void toPdf(String presPath, String outPath)
```

[Presentation](../../com.aspose.slides/presentation) को PDF में परिवर्तित करता है।

--------------------

> ```
> Convert.toPdf("pres.pptx", "pres.pdf");
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presPath | java.lang.String | इनपुट प्रस्तुति का पाथ |
| outPath | java.lang.String | आउटपुट पाथ |
### toPdf(String presPath, String outPath, IPdfOptions options) {#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(String presPath, String outPath, IPdfOptions options)
```

[Presentation](../../com.aspose.slides/presentation) को PDF में परिवर्तित करता है।

--------------------

> ```
> PdfOptions pdfOptions = new PdfOptions();
>  pdfOptions.setCompliance(PdfCompliance.PdfUa);
>  Convert.toPdf("pres.pptx", "pres.pdf", pdfOptions);
> ```


**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presPath | java.lang.String | इनपुट प्रस्तुति का पाथ |
| outPath | java.lang.String | आउटपुट पाथ |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | आउटपुट PDF विकल्प |
### toPdf(Presentation pres, String outPath) {#toPdf-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPdf(Presentation pres, String outPath)
```

[Presentation](../../com.aspose.slides/presentation) को PDF में परिवर्तित करता है।

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toPdf(pres, "output.pdf");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रस्तुति |
| outPath | java.lang.String | आउटपुट पाथ |
### toPdf(Presentation pres, String outPath, IPdfOptions options) {#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-}
```
public static void toPdf(Presentation pres, String outPath, IPdfOptions options)
```

[Presentation](../../com.aspose.slides/presentation) को PDF में परिवर्तित करता है।

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.setCompliance(PdfCompliance.PdfUa);
>      Convert.toPdf(pres, "output.pdf", pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रस्तुति |
| outPath | java.lang.String | आउटपुट पाथ |
| options | [IPdfOptions](../../com.aspose.slides/ipdfoptions) | आउटपुट PDF विकल्प |
### toSvg(String presPath) {#toSvg-java.lang.String-}
```
public static void toSvg(String presPath)
```

[Presentation](../../com.aspose.slides/presentation) को SVG में परिवर्तित करता है।

--------------------

> ```
> Convert.toSvg("pres.pptx");
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presPath | java.lang.String | इनपुट प्रस्तुति का पाथ |
### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

[Presentation](../../com.aspose.slides/presentation) को SVG में परिवर्तित करता है।

--------------------

> ```
> Convert.toSvg("pres.pptx", new Convert.GetOutPathCallback() {
>      public String invoke(Slide slide, int index) {
>          return String.format("pres_%d-out.svg", index);
>      }
>  });
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presPath | java.lang.String | इनपुट प्रस्तुति का पाथ |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | प्रत्येक स्लाइड के लिए SVG आउटपुट पाथ लौटाने वाला कॉलबैक |
### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)
```

[Presentation](../../com.aspose.slides/presentation) को SVG में परिवर्तित करता है।

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      Convert.toSvg(pres, new Convert.GetOutPathCallback() {
>          public String invoke(Slide slide, int index) {
>              return String.format("pres_%d-out.svg", index);
>          }
>      });
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रस्तुति |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | प्रत्येक स्लाइड के लिए SVG आउटपुट पाथ लौटाने वाला कॉलबैक |
### toSvg(Presentation pres, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, ISVGOptions options)
```

[Presentation](../../com.aspose.slides/presentation) को SVG में परिवर्तित करता है।

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      SVGOptions svgOptions = new SVGOptions();
>      svgOptions.setVectorizeText(true);
>      Convert.toSvg(pres, svgOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रस्तुति |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG निर्यात विकल्प |
### toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options) {#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-}
```
public static void toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)
```

[Presentation](../../com.aspose.slides/presentation) को SVG में परिवर्तित करता है।

--------------------

> ```
> Presentation pres = new Presentation("input.pptx");
>  try {
>      SVGOptions svgOptions = new SVGOptions();
>      svgOptions.setVectorizeText(true);
>      Convert.toSvg(pres, new Convert.GetOutPathCallback() {
>          public String invoke(Slide slide, int index) {
>              return String.format("pres_%d-out.svg", index);
>          }
>      }, svgOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रस्तुति |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | प्रत्येक स्लाइड के लिए SVG आउटपुट पाथ लौटाने वाला कॉलबैक |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG निर्यात विकल्प |
### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

इनपुट प्रस्तुति को JPEG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। यदि आउटपुट फ़ाइल नाम को "myPath/myFilename.jpeg" के रूप में दिया जाता है, तो परिणाम "myPath/myFilename\_N.jpeg" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रस्तुति। |
| outputFileName | java.lang.String | आउटपुट फ़ाइल नाम। |
### toJpeg(Presentation pres, String outputFileName, Size imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toJpeg(Presentation pres, String outputFileName, Size imageSize)
```

इनपुट प्रस्तुति को JPEG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। यदि आउटपुट फ़ाइल नाम को "myPath/myFilename.jpeg" के रूप में दिया जाता है, तो परिणाम "myPath/myFilename\_N.jpeg" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रस्तुति |
| outputFileName | java.lang.String | आउटपुट फ़ाइल नाम। |
| imageSize | [Size](../../com.aspose.slides.android/size) | प्रत्येक उत्पन्न छवि का आकार। |
### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

इनपुट प्रस्तुति को JPEG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। यदि आउटपुट फ़ाइल नाम को "myPath/myFilename.jpeg" के रूप में दिया जाता है, तो परिणाम "myPath/myFilename\_N.jpeg" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।

--------------------

> ```
> NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>  notesOptions.setNotesPosition(NotesPositions.BottomTruncated);
>  IRenderingOptions options = new RenderingOptions();
>  options.setSlidesLayoutOptions(notesOptions);
> 
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", 2f, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रस्तुति। |
| outputFileName | java.lang.String | आउटपुट फ़ाइल नाम। |
| scale | float | मूल स्लाइड आकार के सापेक्ष आउटपुट छवियों पर लागू स्केलिंग फ़ैक्टर। |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |
### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

इनपुट प्रस्तुति को PNG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। यदि आउटपुट फ़ाइल नाम को "myPath/myFilename.png" के रूप में दिया जाता है, तो परिणाम "myPath/myFilename\_N.png" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रस्तुति। |
| outputFileName | java.lang.String | आउटपुट फ़ाइल नाम। |
### toPng(Presentation pres, String outputFileName, Size imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.android.Size-}
```
public static void toPng(Presentation pres, String outputFileName, Size imageSize)
```

इनपुट प्रस्तुति को PNG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। यदि आउटपुट फ़ाइल नाम को "myPath/myFilename.png" के रूप में दिया जाता है, तो परिणाम "myPath/myFilename\_N.png" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new com.aspose.slides.android.Size(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रस्तुति |
| outputFileName | java.lang.String | आउटपुट फ़ाइल नाम। |
| imageSize | [Size](../../com.aspose.slides.android/size) | प्रत्येक उत्पन्न छवि का आकार। |
### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

इनपुट प्रस्तुति को PNG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। यदि आउटपुट फ़ाइल नाम को "myPath/myFilename.png" के रूप में दिया जाता है, तो परिणाम "myPath/myFilename\_N.png" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।

--------------------

> ```
> NotesCommentsLayoutingOptions notesOptions= new NotesCommentsLayoutingOptions();
>  notesOptions.setNotesPosition(NotesPositions.BottomTruncated);
>  IRenderingOptions options = new RenderingOptions();
>  options.setSlidesLayoutOptions(notesOptions);
> 
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", 2f, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रस्तुति। |
| outputFileName | java.lang.String | आउटपुट फ़ाइल नाम। |
| scale | float | मूल स्लाइड आकार के सापेक्ष आउटपुट छवियों पर लागू स्केलिंग फ़ैक्टर। |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |
### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

इनपुट प्रस्तुति को TIFF फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। यदि आउटपुट फ़ाइल नाम को "myPath/myFilename.tiff" के रूप में दिया जाता है, तो परिणाम "myPath/myFilename\_N.tiff" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रस्तुति। |
| outputFileName | java.lang.String | आउटपुट फ़ाइल नाम। |
### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

इनपुट प्रस्तुति को कस्टम विकल्पों के साथ TIFF फ़ॉर्मेट में परिवर्तित करता है। यदि आउटपुट फ़ाइल नाम को "myPath/myFilename.tiff" और multipage false है, तो परिणाम "myPath/myFilename\_N.tiff" फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड संख्या है। अन्यथा, यदि multipage true है, तो परिणाम एक बहु-पृष्ठ "myPath/myFilename.tiff" दस्तावेज़ होगा।

--------------------

> ```
> NotesCommentsLayoutingOptions notesOptions= new NotesCommentsLayoutingOptions();
>  notesOptions.setNotesPosition(NotesPositions.BottomTruncated);
>  ITiffOptions options = new TiffOptions();
>  options.setCompressionType(TiffCompressionTypes.CCITT3);
>  options.setSlidesLayoutOptions(notesOptions);
> 
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "pres.tiff", options, false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रस्तुति। |
| outputFileName | java.lang.String | आउटपुट फ़ाइल नाम। |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | TIFF सहेजने के विकल्प। |
| multipage | boolean | यह निर्धारित करता है कि उत्पन्न TIFF दस्तावेज़ बहु-पृष्ठ होना चाहिए या नहीं। |