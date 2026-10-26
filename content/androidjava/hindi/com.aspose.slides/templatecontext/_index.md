---
title: TemplateContext
second_title: Aspose.Slides for Android के माध्यम से Java API रेफ़रेंस
description: एक टेम्प्लेट इंजन के लिए मॉडल ऑब्जेक्ट इंटरफ़ेस का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/templatecontext/
---
**Inheritance:**  
java.lang.Object  
```
public final class TemplateContext<TObject>
```

एक टेम्प्लेट इंजन के लिए मॉडल ऑब्जेक्ट इंटरफ़ेस का प्रतिनिधित्व करता है।

## विधियां

| विधि | विवरण |
| --- | --- |
| [<TSubModel>subModel(TSubModel subModel)](#-TSubModel-subModel-TSubModel-) | एक चाइल्ड टेम्प्लेट कॉन्टेक्स्ट बनाता है। |
| [getObject()](#getObject--) | मॉडल ऑब्जेक्ट लौटाता है। |
| [getOutput()](#getOutput--) | होस्ट दस्तावेज़ के आउटपुट तत्वों का संग्रह लौटाता है। |
| [getLocal()](#getLocal--) | वर्तमान टेम्प्लेट कॉन्टेक्स्ट का स्थानीय स्टोरेज लौटाता है। |
| [getGlobal()](#getGlobal--) | होस्ट दस्तावेज़ का ग्लोबल स्टोरेज लौटाता है। |

### <TSubModel>subModel(TSubModel subModel) {#-TSubModel-subModel-TSubModel-}
```
public final TemplateContext<TSubModel> <TSubModel>subModel(TSubModel subModel)
```

एक चाइल्ड टेम्प्लेट कॉन्टेक्स्ट बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| subModel | TSubModel | चाइल्ड मॉडल ऑब्जेक्ट। |

**वापसी:**
[TemplateContext](../../com.aspose.slides/templatecontext) - दिए गए मॉडल और पैरेंट के आउटपुट संग्रह तथा ग्लोबल स्टोरेज के साथ नया टेम्प्लेट कॉन्टेक्स्ट।

### getObject() {#getObject--}
```
public final TObject getObject()
```

मॉडल ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य Object।

**वापसी:**
TObject

### getOutput() {#getOutput--}
```
public final Output getOutput()
```

होस्ट दस्तावेज़ के आउटपुट तत्वों का संग्रह लौटाता है। केवल-पढ़ने योग्य [Output](../../com.aspose.slides/output)(\#getOutput.getOutput)।

**वापसी:**
[Output](../../com.aspose.slides/output)

### getLocal() {#getLocal--}
```
public final Storage getLocal()
```

वर्तमान टेम्प्लेट कॉन्टेक्स्ट का स्थानीय स्टोरेज लौटाता है। केवल-पढ़ने योग्य [Storage](../../com.aspose.slides/storage)।

**वापसी:**
[Storage](../../com.aspose.slides/storage)

### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

होस्ट दस्तावेज़ का ग्लोबल स्टोरेज लौटाता है। केवल-पढ़ने योग्य [Storage](../../com.aspose.slides/storage)।

**वापसी:**
[Storage](../../com.aspose.slides/storage)