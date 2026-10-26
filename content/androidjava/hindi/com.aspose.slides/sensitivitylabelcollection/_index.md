---
title: SensitivityLabelCollection
second_title: Aspose.Slides for Android के माध्यम से जावा API रेफ़रेंस
description: दस्तावेज़ पर लागू संवेदनशीलता लेबलों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/sensitivitylabelcollection/
---
**विरासत:**  
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)  
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

डॉक्यूमेंट पर लागू संवेदनशीलता लेबलों के संग्रह को दर्शाता है।  
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स के द्वारा संवेदनशीलता लेबल लौटाता है। |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | संग्रह के अंत में संवेदनशीलता लेबल जोड़ता है। |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | SensitivityLabel को संग्रह में जोड़ता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर संवेदनशीलता लेबल हटाता है। |
| [clear()](#clear--) | संग्रह से सभी तत्वों को हटाता है। |
| [iterator()](#iterator--) | वह enumerator लौटाता है जो संग्रह के माध्यम से इटररेट करता है। |
| [getCount()](#getCount--) | संग्रह में तत्वों की संख्या लौटाता है। |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | सभी तत्वों को संग्रह से निर्दिष्ट array में कॉपी करता है। |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```

इंडेक्स के द्वारा संवेदनशीलता लेबल लौटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

संग्रह के अंत में संवेदनशीलता लेबल जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| id | java.lang.String | संवेदनशीलता लेबल का id। |
| siteId | java.util.UUID | Azure Active Directory (Azure AD) साइट पहचानकर्ता। |
| isEnabled | boolean | संकेत करता है कि संवेदनशीलता लेबल सक्षम है या नहीं। |
| methodType | int | संवेदनशीलता लेबल के असाइनमेंट विधि। |

**वापसी:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```

संग्रह में SensitivityLabel जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | SensitivityLabel वस्तु जिसे संग्रह के अंत में जोड़ा जाना है। |

**वापसी:**
int - वह इंडेक्स जहाँ SensitivityLabel जोड़ा गया था।
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर संवेदनशीलता लेबल हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | वह इंडेक्स जिस पर संवेदनशीलता लेबल को हटाया जाना चाहिए। |

### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी तत्वों को हटाता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```

एक enumerator लौटाता है जो संग्रह के माध्यम से इटररेट करता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - A  System.Collections.Generic.IEnumerator1  that can be used to iterate through the collection.
### getCount() {#getCount--}
```
public final int getCount()
```

संग्रह में तत्वों की संख्या लौटाता है। केवल-पढ़ने-योग्य  int ।

**वापसी:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```

सभी तत्वों को संग्रह से निर्दिष्ट array में कॉपी करता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | लक्ष्य array। |
| index | int | लक्ष्य array में प्रारम्भिक इंडेक्स। |