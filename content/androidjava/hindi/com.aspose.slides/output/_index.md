---
title: Output
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: IWebDocument के लिए आउटपुट तत्वों का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/output/
---
**Inheritance:**
java.lang.Object
```
public final class Output
```

IWebDocument के लिए आउटपुट तत्वों का संग्रह दर्शाता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | Adds an output element for the context object. |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | Adds an output element for the image. |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | Adds an output element for the image. |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | Adds an output element for the video. |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | Creates and adds an output file element for the specified font. |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | Adds an output element for the text content. |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | Binds resource to output file. |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | Returns the path for a given resource. |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

कॉंटेक्स्ट ऑब्जेक्ट के लिए एक आउटपुट तत्व जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | आउटपुट पथ। |
| templateKey | java.lang.String | आउटपुट से पहले कॉंटेक्स्ट ऑब्जेक्ट रूपांतरण के लिए प्रयुक्त टेम्पलेट की कुंजी। |
| contextObject | TContextObject | कॉंटेक्स्ट ऑब्जेक्ट। |

**रिटर्न:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) कॉंटेक्स्ट ऑब्जेक्ट के लिए ऑब्जेक्ट।
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

छवि के लिए एक आउटपुट तत्व जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | आउटपुट पथ। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | आउटपुट करने के लिए छवि। |

**रिटर्न:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) छवि के लिए ऑब्जेक्ट।
### add(String path, IImage image) {#add-java.lang.String-com.aspose.slides.IImage-}
```
public final IOutputFile add(String path, IImage image)
```

छवि के लिए एक आउटपुट तत्व जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | आउटपुट पथ। |
| image | [IImage](../../com.aspose.slides/iimage) | आउटपुट करने के लिए छवि। |

**रिटर्न:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) छवि के लिए ऑब्जेक्ट।
### add(String path, IVideo video) {#add-java.lang.String-com.aspose.slides.IVideo-}
```
public final IOutputFile add(String path, IVideo video)
```

वीडियो के लिए एक आउटपुट तत्व जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | आउटपुट पथ। |
| video | [IVideo](../../com.aspose.slides/ivideo) | आउटपुट करने के लिए वीडियो। |

**रिटर्न:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) वीडियो के लिए ऑब्जेक्ट।
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

निर्दिष्ट फ़ॉन्ट के लिए एक आउटपुट फ़ाइल तत्व बनाता और जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | वह फ़ाइल पथ जहाँ फ़ॉन्ट आउटपुट सहेजा जाएगा। |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | आउटपुट में लिखने हेतु फ़ॉन्ट डेटा। |
| fontStyle | int | फ़ॉन्ट की शैली (उदा., Regular, Bold, Italic)। |

**रिटर्न:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - निर्मित फ़ॉन्ट के लिए एक [IOutputFile](../../com.aspose.slides/ioutputfile) इंस्टेंस।
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

पाठ सामग्री के लिए एक आउटपुट तत्व जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | आउटपुट पथ। |
| textContent | java.lang.String | आउटपुट करने हेतु सामग्री। |

**रिटर्न:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) पाठ सामग्री के लिए ऑब्जेक्ट।
### bindResource(IOutputFile outputFile, Object obj) {#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-}
```
public final void bindResource(IOutputFile outputFile, Object obj)
```

संसाधन को आउटपुट फ़ाइल से बाँधता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| outputFile | [IOutputFile](../../com.aspose.slides/ioutputfile) | आउटपुट फ़ाइल। |
| obj | java.lang.Object | संसाधन ऑब्जेक्ट। |
### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```

दिए गए संसाधन के लिए पथ लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | संसाधन ऑब्जेक्ट। |

**रिटर्न:**
java.lang.String - संसाधन पथ।