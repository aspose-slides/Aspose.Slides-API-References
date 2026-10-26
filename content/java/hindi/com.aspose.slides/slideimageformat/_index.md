---
title: SlideImageFormat
second_title: Aspose.Slides के लिए Java API संदर्भ
description: निर्धारित करता है कि प्रस्तुति को HTML निर्यात के लिए निर्यात करते समय स्लाइड इमेज किस फ़ॉर्मेट में सहेजी जाएगी।
type: docs
url: /hi/com.aspose.slides/slideimageformat/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

निर्धारित करता है कि स्लाइड इमेज किस फ़ॉर्मेट में सहेजी जाएगी जब प्रस्तुति को HTML निर्यात के लिए निर्यात किया जाए।

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |

## विधियां

| विधि | विवरण |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | स्लाइड्स को SVG फ़ॉर्मेट में परिवर्तित किया जाना चाहिए। |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | स्लाइड्स को रास्टर इमेज में परिवर्तित किया जाना चाहिए। |

### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```

### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```

स्लाइड्स को SVG फ़ॉर्मेट में परिवर्तित किया जाना चाहिए।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | SVG निर्यात के विकल्प। |

**रिटर्न:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - [SlideImageFormat](../../com.aspose.slides/slideimageformat) ऑब्जेक्ट।

### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```

स्लाइड्स को रास्टर इमेज में परिवर्तित किया जाना चाहिए।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scale | float | आउटपुट इमेज को स्केल करने का कारक। |
| imageFormat | int | परिणामी इमेज का फ़ॉर्मेट (उदा., PNG, JPEG)। |

**रिटर्न:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -