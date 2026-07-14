---
title: SlideImageFormat
second_title: Aspose.Slides Android के लिए Java API Reference द्वारा
description: slide image को HTML निर्यात के लिए प्रस्तुति में सहेजे जाने वाले प्रारूप को निर्धारित करता है।
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

HTML निर्यात के लिए प्रस्तुति के दौरान स्लाइड छवि को संग्रहीत करने के लिए प्रारूप निर्धारित करता है।
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | स्लाइड को SVG प्रारूप में परिवर्तित किया जाना चाहिए। |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | स्लाइड को रास्टर छवि में परिवर्तित किया जाना चाहिए। |
### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```


### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```


स्लाइड को SVG प्रारूप में परिवर्तित किया जाना चाहिए।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | SVG निर्यात के लिए विकल्प। |

**वापसी:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - यह [SlideImageFormat](../../com.aspose.slides/slideimageformat) ऑब्जेक्ट।
### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```


स्लाइड को रास्टर छवि में परिवर्तित किया जाना चाहिए।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scale | float | आउटपुट छवि को स्केल करने का कारक। |
| imageFormat | int | परिणामी छवि का प्रारूप (उदा., PNG, JPEG)। |

**वापसी:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -