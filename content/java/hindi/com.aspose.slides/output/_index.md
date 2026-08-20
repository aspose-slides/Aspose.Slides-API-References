---
title: Output
second_title: Aspose.Slides for Java API संदर्भ
description: IWebDocument के लिए आउटपुट तत्वों का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/output/
---
**विरासत:**
java.lang.Object
```
public final class Output
```

IWebDocument के लिए आउटपुट तत्वों का एक संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [<TContextObject>add(String path, String templateKey, TContextObject contextObject)](#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-) | संदर्भ वस्तु के लिए एक आउटपुट तत्व जोड़ता है। |
| [add(String path, IPPImage image)](#add-java.lang.String-com.aspose.slides.IPPImage-) | छवि के लिए एक आउटपुट तत्व जोड़ता है। |
| [add(String path, IImage image)](#add-java.lang.String-com.aspose.slides.IImage-) | छवि के लिए एक आउटपुट तत्व जोड़ता है। |
| [add(String path, IVideo video)](#add-java.lang.String-com.aspose.slides.IVideo-) | वीडियो के लिए एक आउटपुट तत्व जोड़ता है। |
| [add(String path, IAudio audio)](#add-java.lang.String-com.aspose.slides.IAudio-) | ऑडियो के लिए एक आउटपुट तत्व जोड़ता है। |
| [add(String path, IFontData fontData, int fontStyle)](#add-java.lang.String-com.aspose.slides.IFontData-int-) | निर्दिष्ट फ़ॉन्ट के लिए एक आउटपुट फ़ाइल तत्व बनाता और जोड़ता है। |
| [add(String path, String textContent)](#add-java.lang.String-java.lang.String-) | पाठ सामग्री के लिए एक आउटपुट तत्व जोड़ता है। |
| [bindResource(IOutputFile outputFile, Object obj)](#bindResource-com.aspose.slides.IOutputFile-java.lang.Object-) | संसाधन को आउटपुट फ़ाइल से बाँधता है। |
| [getResourcePath(Object obj)](#getResourcePath-java.lang.Object-) | दिए गए संसाधन के लिए पथ लौटाता है। |
### <TContextObject>add(String path, String templateKey, TContextObject contextObject) {#-TContextObject-add-java.lang.String-java.lang.String-TContextObject-}
```
public final IOutputFile <TContextObject>add(String path, String templateKey, TContextObject contextObject)
```

संदर्भ वस्तु के लिए एक आउटपुट तत्व जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | आउटपुट पथ। |
| templateKey | java.lang.String | आउटपुट से पहले संदर्भ वस्तु परिवर्तन के लिए प्रयुक्त टेम्पलेट की कुंजी। |
| contextObject | TContextObject | संदर्भ वस्तु। |

**रिटर्न मान:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) संदर्भ वस्तु के लिए ऑब्जेक्ट।
### add(String path, IPPImage image) {#add-java.lang.String-com.aspose.slides.IPPImage-}
```
public final IOutputFile add(String path, IPPImage image)
```

छवि के लिए एक आउटपुट तत्व जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | आउटपुट पथ। |
| image | [IPPImage](../../com.aspose.slides/ippimage) | आउटपुट करने की छवि। |

**रिटर्न मान:**
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
| image | [IImage](../../com.aspose.slides/iimage) | आउटपुट करने की छवि। |

**रिटर्न मान:**
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
| video | [IVideo](../../com.aspose.slides/ivideo) | आउटपुट करने का वीडियो। |

**रिटर्न मान:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) वीडियो के लिए ऑब्जेक्ट।
### add(String path, IAudio audio) {#add-java.lang.String-com.aspose.slides.IAudio-}
```
public final IOutputFile add(String path, IAudio audio)
```

ऑडियो के लिए एक आउटपुट तत्व जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | आउटपुट पथ। |
| audio | [IAudio](../../com.aspose.slides/iaudio) | आउटपुट करने का ऑडियो। |

**रिटर्न मान:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - [IOutputFile](../../com.aspose.slides/ioutputfile) ऑडियो के लिए ऑब्जेक्ट।
### add(String path, IFontData fontData, int fontStyle) {#add-java.lang.String-com.aspose.slides.IFontData-int-}
```
public final IOutputFile add(String path, IFontData fontData, int fontStyle)
```

निर्दिष्ट फ़ॉन्ट के लिए एक आउटपुट फ़ाइल तत्व बनाता और जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | फ़ॉन्ट आउटपुट जहाँ सहेजा जाएगा इसका फ़ाइल पथ। |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | आउटपुट में लिखे जाने वाले फ़ॉन्ट डेटा। |
| fontStyle | int | फ़ॉन्ट की शैली (जैसे, Regular, Bold, Italic)। |

**रिटर्न मान:**
[IOutputFile](../../com.aspose.slides/ioutputfile) - उत्पन्न फ़ॉन्ट के लिए एक [IOutputFile](../../com.aspose.slides/ioutputfile) उदाहरण।
### add(String path, String textContent) {#add-java.lang.String-java.lang.String-}
```
public final IOutputFile add(String path, String textContent)
```

पाठ सामग्री के लिए एक आउटपुट तत्व जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| path | java.lang.String | आउटपुट पथ। |
| textContent | java.lang.String | आउटपुट करने की सामग्री। |

**रिटर्न मान:**
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
| obj | java.lang.Object | संसाधन वस्तु। |
### getResourcePath(Object obj) {#getResourcePath-java.lang.Object-}
```
public final String getResourcePath(Object obj)
```

दिए गए संसाधन के लिए पथ लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | संसाधन वस्तु। |

**रिटर्न मान:**
java.lang.String - संसाधन पथ।