---
title: ISensitivityLabelCollection
second_title: जावा API रेफ़रेंस हेतु Aspose.Slides
description: दस्तावेज़ पर लागू संवेदनशीलता लेबल्स के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/isensitivitylabelcollection/
---
**सभी कार्यान्वित इंटरफ़ेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

डॉक्यूमेंट पर लागू संवेदनशीलता लेबल्स का संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा संवेदनशीलता लेबल लौटाता है। |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | संग्रह के अंत में संवेदनशीलता लेबल जोड़ता है। |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | संग्रह में एक SensitivityLabel जोड़ता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर संवेदनशीलता लेबल हटाता है। |
| [clear()](#clear--) | संग्रह से सभी तत्व हटाता है। |
| [getCount()](#getCount--) | संग्रह में सभी तत्वों की संख्या प्राप्त करता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

इंडेक्स द्वारा संवेदनशीलता लेबल लौटाता है। केवल-पढ़ने योग्य [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

संग्रह के अंत में संवेदनशीलता लेबल जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| id | java.lang.String | संवेदनशीलता लेबल का id। |
| siteId | java.util.UUID | Azure Active Directory (Azure AD) साइट पहचानकर्ता। |
| isEnabled | boolean | फ्लैग दर्शाता है कि संवेदनशीलता लेबल सक्षम है या नहीं। |
| methodType | int | संवेदनशीलता लेबल के असाइनमेंट विधि। |

**वापसी:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```

संग्रह में एक SensitivityLabel जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | संग्रह के अंत में जोड़े जाने वाले SensitivityLabel ऑब्जेक्ट। |

**वापसी:**
int - वह सूचकांक जहाँ SensitivityLabel जोड़ा गया था।
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर संवेदनशीलता लेबल हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | डिलीट किए जाने वाले संवेदनशीलता लेबल का इंडेक्स। |

### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी तत्व हटाता है।

### getCount() {#getCount--}
```
public abstract int getCount()
```

संग्रह में सभी तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य  int .

**वापसी:**
int