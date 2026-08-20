---
title: Convert
second_title: Aspose.Slides for Java API संदर्भ
description: एक समूह के मेथड्स का प्रतिनिधित्व करता है जो परिवर्तित करने के लिए अभिप्रेत हैं।
type: docs
url: /hi/com.aspose.slides/convert/
---
**विरासत:**  
java.lang.Object  
```
public class Convert
```

एक समूह के मेथड्स का प्रतिनिधित्व करता है जो [Presentation](../../com.aspose.slides/presentation) को परिवर्तित करने के लिए अभिप्रेत हैं।

--------------------

> ```
> Convert.AutoByExtension("pres.pptx", "pres.pdf");
> ```
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [Convert()](#Convert--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [autoByExtension(String presPath, String outPath)](#autoByExtension-java.lang.String-java.lang.String-) | पास किए गए आउटपुट पाथ एक्स्टेंशन का उपयोग करके आवश्यक निर्यात फॉर्मेट निर्धारित करने के लिए [Presentation](../../com.aspose.slides/presentation) को परिवर्तित करता है। |
| [toPdf(String presPath, String outPath)](#toPdf-java.lang.String-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation) को PDF में परिवर्तित करता है। |
| [toPdf(String presPath, String outPath, IPdfOptions options)](#toPdf-java.lang.String-java.lang.String-com.aspose.slides.IPdfOptions-) | [Presentation](../../com.aspose.slides/presentation) को PDF में परिवर्तित करता है। |
| [toPdf(Presentation pres, String outPath)](#toPdf-com.aspose.slides.Presentation-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation) को PDF में परिवर्तित करता है। |
| [toPdf(Presentation pres, String outPath, IPdfOptions options)](#toPdf-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.IPdfOptions-) | [Presentation](../../com.aspose.slides/presentation) को PDF में परिवर्तित करता है। |
| [toSvg(String presPath)](#toSvg-java.lang.String-) | [Presentation](../../com.aspose.slides/presentation) को SVG में परिवर्तित करता है। |
| [toSvg(String presPath, Convert.GetOutPathCallback getOutPath)](#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-) | [Presentation](../../com.aspose.slides/presentation) को SVG में परिवर्तित करता है। |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-) | [Presentation](../../com.aspose.slides/presentation) को SVG में परिवर्तित करता है। |
| [toSvg(Presentation pres, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.ISVGOptions-) | [Presentation](../../com.aspose.slides/presentation) को SVG में परिवर्तित करता है। |
| [toSvg(Presentation pres, Convert.GetOutPathCallback getOutPath, ISVGOptions options)](#toSvg-com.aspose.slides.Presentation-com.aspose.slides.Convert.GetOutPathCallback-com.aspose.slides.ISVGOptions-) | [Presentation](../../com.aspose.slides/presentation) को SVG में परिवर्तित करता है। |
| [toJpeg(Presentation pres, String outputFileName)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-) | इनपुट प्रेजेंटेशन को JPEG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। |
| [toJpeg(Presentation pres, String outputFileName, Dimension imageSize)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | इनपुट प्रेजेंटेशन को JPEG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। |
| [toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | इनपुट प्रेजेंटेशन को JPEG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। |
| [toPng(Presentation pres, String outputFileName)](#toPng-com.aspose.slides.Presentation-java.lang.String-) | इनपुट प्रेजेंटेशन को PNG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। |
| [toPng(Presentation pres, String outputFileName, Dimension imageSize)](#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-) | इनपुट प्रेजेंटेशन को PNG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। |
| [toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)](#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-) | इनपुट प्रेजेंटेशन को PNG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। |
| [toTiff(Presentation pres, String outputFileName)](#toTiff-com.aspose.slides.Presentation-java.lang.String-) | इनपुट प्रेजेंटेशन को TIFF फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। |
| [toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)](#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-) | इनपुट प्रेजेंटेशन को कस्टम विकल्पों के साथ TIFF फ़ॉर्मेट में परिवर्तित करता है। |

### Convert() {#Convert--}
```
public Convert()
```

### autoByExtension(String presPath, String outPath) {#autoByExtension-java.lang.String-java.lang.String-}
```
public static void autoByExtension(String presPath, String outPath)
```

पास किए गए आउटपुट पाथ एक्स्टेंशन का उपयोग करके आवश्यक निर्यात फॉर्मेट निर्धारित करने के लिए [Presentation](../../com.aspose.slides/presentation) को परिवर्तित करता है।

--------------------

> ```
> Convert.autoByExtension("pres.pptx", "pres.pdf");
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presPath | java.lang.String | इनपुट प्रेजेंटेशन का पथ |
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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presPath | java.lang.String | इनपुट प्रेजेंटेशन का पथ |
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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presPath | java.lang.String | इनपुट प्रेजेंटेशन का पथ |
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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रेजेंटेशन |
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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रेजेंटेशन |
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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presPath | java.lang.String | इनपुट प्रेजेंटेशन का पथ |

### toSvg(String presPath, Convert.GetOutPathCallback getOutPath) {#toSvg-java.lang.String-com.aspose.slides.Convert.GetOutPathCallback-}
```
public static void toSvg(String presPath, Convert.GetOutPathCallback getOutPath)
```

[Presentation](../../com.aspose.slides/presentation) को SVG में परिवर्तित करता है।

--------------------

> ```
> Convert.toSvg("pres.pptx", (slide, index) -> String.format("pres_%d-out.svg", index));
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presPath | java.lang.String | इनपुट प्रेजेंटेशन का पथ |
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
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रेजेंटेशन |
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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रेजेंटेशन |
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
>      Convert.toSvg(pres, (slide, index) -> String.format("pres_%d-out.svg", index), svgOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रेजेंटेशन |
| getOutPath | [GetOutPathCallback](../../com.aspose.slides/getoutpathcallback) | प्रत्येक स्लाइड के लिए SVG आउटपुट पाथ लौटाने वाला कॉलबैक |
| options | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG निर्यात विकल्प |

### toJpeg(Presentation pres, String outputFileName) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toJpeg(Presentation pres, String outputFileName)
```

इनपुट प्रेजेंटेशन को JPEG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। यदि आउटपुट फ़ाइल का नाम "myPath/myFilename.jpeg" दिया गया है, तो परिणाम को "myPath/myFilename_N.jpeg" नाम की फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड क्रमांक है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रेजेंटेशन। |
| outputFileName | java.lang.String | आउटपुट फ़ाइल नाम। |

### toJpeg(Presentation pres, String outputFileName, Dimension imageSize) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toJpeg(Presentation pres, String outputFileName, Dimension imageSize)
```

इनपुट प्रेजेंटेशन को JPEG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। यदि आउटपुट फ़ाइल का नाम "myPath/myFilename.jpeg" दिया गया है, तो परिणाम को "myPath/myFilename_N.jpeg" नाम की फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड क्रमांक है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toJpeg(pres, "presImage.jpeg", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रेजेंटेशन |
| outputFileName | java.lang.String | आउटपुट फ़ाइल नाम। |
| imageSize | java.awt.Dimension | प्रत्येक उत्पन्न छवि का आकार। |

### toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toJpeg-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toJpeg(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

इनपुट प्रेजेंटेशन को JPEG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। यदि आउटपुट फ़ाइल का नाम "myPath/myFilename.jpeg" दिया गया है, तो परिणाम को "myPath/myFilename_N.jpeg" नाम की फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड क्रमांक है।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रेजेंटेशन। |
| outputFileName | java.lang.String | आउटपुट फ़ाइल नाम। |
| scale | float | मूल स्लाइड आकार के सापेक्ष आउटपुट छवियों पर लागू स्केलिंग फैक्टर। |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |

### toPng(Presentation pres, String outputFileName) {#toPng-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toPng(Presentation pres, String outputFileName)
```

इनपुट प्रेजेंटेशन को PNG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। यदि आउटपुट फ़ाइल का नाम "myPath/myFilename.png" दिया गया है, तो परिणाम को "myPath/myFilename_N.png" नाम की फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड क्रमांक है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रेजेंटेशन। |
| outputFileName | java.lang.String | आउटपुट फ़ाइल नाम। |

### toPng(Presentation pres, String outputFileName, Dimension imageSize) {#toPng-com.aspose.slides.Presentation-java.lang.String-java.awt.Dimension-}
```
public static void toPng(Presentation pres, String outputFileName, Dimension imageSize)
```

इनपुट प्रेजेंटेशन को PNG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। यदि आउटपुट फ़ाइल का नाम "myPath/myFilename.png" दिया गया है, तो परिणाम को "myPath/myFilename_N.png" नाम की फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड क्रमांक है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toPng(pres, "presImage.png", new Dimension(720, 540));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रेजेंटेशन |
| outputFileName | java.lang.String | आउटपुट फ़ाइल नाम। |
| imageSize | java.awt.Dimension | प्रत्येक उत्पन्न छवि का आकार। |

### toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options) {#toPng-com.aspose.slides.Presentation-java.lang.String-float-com.aspose.slides.IRenderingOptions-}
```
public static void toPng(Presentation pres, String outputFileName, float scale, IRenderingOptions options)
```

इनपुट प्रेजेंटेशन को PNG फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। यदि आउटपुट फ़ाइल का नाम "myPath/myFilename.png" दिया गया है, तो परिणाम को "myPath/myFilename_N.png" नाम की फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड क्रमांक है।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रेजेंटेशन। |
| outputFileName | java.lang.String | आउटपुट फ़ाइल नाम। |
| scale | float | मूल स्लाइड आकार के सापेक्ष आउटपुट छवियों पर लागू स्केलिंग फैक्टर। |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | रेंडरिंग विकल्प। |

### toTiff(Presentation pres, String outputFileName) {#toTiff-com.aspose.slides.Presentation-java.lang.String-}
```
public static void toTiff(Presentation pres, String outputFileName)
```

इनपुट प्रेजेंटेशन को TIFF फ़ॉर्मेट की छवियों के सेट में परिवर्तित करता है। यदि आउटपुट फ़ाइल का नाम "myPath/myFilename.tiff" दिया गया है, तो परिणाम को "myPath/myFilename_N.tiff" नाम की फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड क्रमांक है।

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Convert.toTiff(pres, "presImage.tiff");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रेजेंटेशन। |
| outputFileName | java.lang.String | आउटपुट फ़ाइल नाम। |

### toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage) {#toTiff-com.aspose.slides.Presentation-java.lang.String-com.aspose.slides.ITiffOptions-boolean-}
```
public static void toTiff(Presentation pres, String outputFileName, ITiffOptions options, boolean multipage)
```

कस्टम विकल्पों के साथ इनपुट प्रेजेंटेशन को TIFF फ़ॉर्मेट में परिवर्तित करता है। यदि आउटपुट फ़ाइल नाम "myPath/myFilename.tiff" दिया गया है और multipage false है, तो परिणाम को "myPath/myFilename_N.tiff" नाम की फ़ाइलों के सेट के रूप में सहेजा जाएगा, जहाँ N स्लाइड क्रमांक है। अन्यथा, यदि multipage true है, तो परिणाम एक मल्टी-पेज "myPath/myFilename.tiff" दस्तावेज़ होगा।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | इनपुट प्रेजेंटेशन। |
| outputFileName | java.lang.String | आउटपुट फ़ाइल नाम। |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | TIFF सहेजने के विकल्प। |
| multipage | boolean | निर्धारित करता है कि उत्पन्न TIFF दस्तावेज़ मल्टी-पेज होना चाहिए या नहीं। |