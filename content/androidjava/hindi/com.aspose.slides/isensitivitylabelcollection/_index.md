---
title: ISensitivityLabelCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: दस्तावेज़ पर लागू संवेदनशीलता लेबलों का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/isensitivitylabelcollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

दस्तावेज़ पर लागू संवेदनशीलता लेबलों का संग्रह दर्शाता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the sensitivity label by index. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Adds the sensitivity label at the end of the collection. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Adds a SensitivityLabel to the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the sensitivity label at the specified index. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [getCount()](#getCount--) | Gets the number of all elements in the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

इंडेक्स द्वारा संवेदनशीलता लेबल लौटाता है। केवल-पढ़ने योग्य [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

संग्रह के अंत में संवेदनशीलता लेबल जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| id | java.lang.String | संवेदनशीलता लेबल का आईडी। |
| siteId | java.util.UUID | Azure Active Directory (Azure AD) साइट पहचानकर्ता। |
| isEnabled | boolean | फ़्लैग दर्शाता है कि संवेदनशीलता लेबल सक्षम है या नहीं। |
| methodType | int | संवेदनशीलता लेबल के लिए असाइनमेंट विधि। |

**रिटर्न:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```

संग्रह में SensitivityLabel जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | संग्रह के अंत में जोड़ने के लिए SensitivityLabel वस्तु। |

**रिटर्न:**
int - वह इंडेक्स जहाँ SensitivityLabel जोड़ा गया था।
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर संवेदनशीलता लेबल हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | Index of the sensitivity label that should be deleted. |
### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी तत्वों को हटाता है।
### getCount() {#getCount--}
```
public abstract int getCount()
```

संग्रह में सभी तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int .

**रिटर्न:**
int