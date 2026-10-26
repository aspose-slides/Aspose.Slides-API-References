---
title: TemplateContext
second_title: Aspose.Slides for Java API संदर्भ
description: एक टेम्पलेट इंजन के लिए मॉडल ऑब्जेक्ट इंटरफ़ेस को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/templatecontext/
---
**विरासत:**  
java.lang.Object  
```
public final class TemplateContext<TObject>
```

टेम्पलेट इंजन के लिए मॉडल ऑब्जेक्ट इंटरफ़ेस को दर्शाता है।

## विधियां

| विधि | विवरण |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | एक चाइल्ड टेम्पलेट कॉन्टेक्स्ट बनाता है। |
| [getObject()](#getObject--) | मॉडल ऑब्जेक्ट को रिटर्न करता है। |
| [getOutput()](#getOutput--) | होस्ट दस्तावेज़ के आउटपुट तत्वों का संग्रह रिटर्न करता है। |
| [getLocal()](#getLocal--) | वर्तमान टेम्पलेट कॉन्टेक्स्ट के स्थानीय स्टोरेज को रिटर्न करता है। |
| [getGlobal()](#getGlobal--) | होस्ट दस्तावेज़ के ग्लोबल स्टोरेज को रिटर्न करता है। |

### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```

एक चाइल्ड टेम्पलेट कॉन्टेक्स्ट बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| subModel | TSubModel | चाइल्ड मॉडल ऑब्जेक्ट। |

**रिटर्न:**  
[TemplateContext](../../com.aspose.slides/templatecontext) - नया टेम्पलेट कॉन्टेक्स्ट जिसमें दिया गया मॉडल, पेरेंट की आउटपुट कलेक्शन तथा ग्लोबल स्टोरेज है।

### getObject() {#getObject--}
```
public final TObject getObject()
```

मॉडल ऑब्जेक्ट को रिटर्न करता है। केवल-पढ़ने योग्य Object.

**रिटर्न:**  
TObject

### getOutput() {#getOutput--}
```
public final Output getOutput()
```

होस्ट दस्तावेज़ के आउटपुट तत्वों का संग्रह रिटर्न करता है। केवल-पढ़ने योग्य [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

**रिटर्न:**  
[Output](../../com.aspose.slides/output)

### getLocal() {#getLocal--}
```
public final Storage getLocal()
```

वर्तमान टेम्पलेट कॉन्टेक्स्ट के स्थानीय स्टोरेज को रिटर्न करता है। केवल-पढ़ने योग्य [Storage](../../com.aspose.slides/storage).

**रिटर्न:**  
[Storage](../../com.aspose.slides/storage)

### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

होस्ट दस्तावेज़ के ग्लोबल स्टोरेज को रिटर्न करता है। केवल-पढ़ने योग्य [Storage](../../com.aspose.slides/storage).

**रिटर्न:**  
[Storage](../../com.aspose.slides/storage)