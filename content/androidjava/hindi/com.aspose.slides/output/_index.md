---
title: Output
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस के माध्यम से
description: IWebDocument के लिए आउटपुट तत्वों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/output/
---
**विरासत:**
java.lang.Object
```
public final class Output
```

IWebDocument के लिए आउटपुट तत्वों का एक संग्रह दर्शाता है।

## विधियां

| विधि | विवरण |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | कॉन्टेक्स्ट ऑब्जेक्ट के लिए एक आउटपुट तत्व जोड़ता है। |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | इमेज के लिए एक आउटपुट तत्व जोड़ता है। |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | इमेज के लिए एक आउटपुट तत्व जोड़ता है। |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | वीडियो के लिए एक आउटपुट तत्व जोड़ता है। |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | ऑडियो के लिए एक आउटपुट तत्व जोड़ता है। |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | निर्दिष्ट फ़ॉन्ट के लिए एक आउटपुट फ़ाइल तत्व बनाता और जोड़ता है। |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | टेक्स्ट सामग्री के लिए एक आउटपुट तत्व जोड़ता है। |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | संसाधन को आउटपुट फ़ाइल से बाँधता है। |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | दिए गए संसाधन के लिए पथ लौटाता है। |

### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

कॉन्टेक्स्ट ऑब्जेक्ट के लिए एक आउटपुट तत्व जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | आउटपुट पथ। |
| templateKey | java.lang.String | आउटपुट से पहले कॉन्टेक्स्ट ऑब्जेक्ट ट्रांसफ़ॉर्मेशन के लिए उपयोग किए गए टेम्पलेट की कुंजी। |
| contextObject | TContextObject | कॉन्टेक्स्ट ऑब्जेक्ट। |

**रिटर्न:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) ऑब्जेक्ट कॉन्टेक्स्ट ऑब्जेक्ट के लिए।

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
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) ऑब्जेक्ट इमेज के लिए।

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
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) ऑब्जेक्ट इमेज के लिए।

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
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) ऑब्जेक्ट वीडियो के लिए।

### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```

ऑडियो के लिए एक आउटपुट तत्व जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | आउटपुट पथ। |
| audio | [IAudio](../../com.aspose.slides/iaudio) | आउटपुट करने के लिए ऑडियो। |

**रिटर्न:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) ऑब्जेक्ट ऑडियो के लिए।

### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

निर्दिष्ट फ़ॉन्ट के लिए एक आउटपुट फ़ाइल तत्व बनाता और जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | फ़ॉन्ट आउटपुट सहेजा जाएगा वाली फ़ाइल का पथ। |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | आउटपुट में लिखे जाने वाले फ़ॉन्ट डेटा। |
| fontStyle | int | फ़ॉन्ट की शैली (जैसे, Regular, Bold, Italic)। |

**रिटर्न:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - एक [IOutputFile](../../com.aspose.slides/ioutputfile) इंस्टेंस जेनरेटेड फ़ॉन्ट के लिए।

### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

टेक्स्ट सामग्री के लिए एक आउटपुट तत्व जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | आउटपुट पथ। |
| textContent | java.lang.String | आउटपुट करने के लिए सामग्री। |

**रिटर्न:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) ऑब्जेक्ट टेक्स्ट सामग्री के लिए।

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