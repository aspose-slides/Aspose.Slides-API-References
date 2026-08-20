---
title: SensitivityLabelCollection
second_title: Aspose.Slides for Java API संदर्भ
description: दस्तावेज़ पर लागू संवेदनशीलता लेबल का एक संग्रह दर्शाता है।
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

दस्तावेज़ पर लागू संवेदनशीलता लेबल का संग्रह दर्शाता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the sensitivity label by index. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Adds the sensitivity label at the end of the collection. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Adds a SensitivityLabel to the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the sensitivity label at the specified index. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [getCount()](#getCount--) | Returns the number of elements in the collection. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | Copies all elements from the collection to the specified array. |

### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```

इंडेक्स द्वारा संवेदनशीलता लेबल लौटाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी मान:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)

### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

संग्रह के अंत में संवेदनशीलता लेबल जोड़ता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| id | java.lang.String | संवेदनशीलता लेबल का आईडी। |
| siteId | java.util.UUID | Azure Active Directory (Azure AD) साइट पहचानकर्ता। |
| isEnabled | boolean | फ़्लैग इंगित करता है कि संवेदनशीलता लेबल सक्षम है या नहीं। |
| methodType | int | संवेदनशीलता लेबल के लिए असाइनमेंट विधि। |

**वापसी मान:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)

### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```

संग्रह में एक SensitivityLabel जोड़ता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | संग्रह के अंत में जोड़ने के लिए SensitivityLabel ऑब्जेक्ट। |

**वापसी मान:**
int - वह सूचकांक जहाँ SensitivityLabel जोड़ा गया था।

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर संवेदनशीलता लेबल को हटा देता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले संवेदनशीलता लेबल का इंडेक्स। |

### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी तत्वों को हटा देता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```

संग्रह के माध्यम से इटरेट करने वाला एनीयरेटर लौटाता है।

**वापसी मान:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - एक  System.Collections.Generic.IEnumerator1  जो संग्रह के माध्यम से इटरेट करने के लिए उपयोग किया जा सकता है।

### getCount() {#getCount--}
```
public final int getCount()
```

संग्रह में तत्वों की संख्या लौटाता है। केवल-पढ़ने योग्य  int .

**वापसी मान:**
int

### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```

संग्रह से सभी तत्वों को निर्दिष्ट एरे में कॉपी करता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | लक्ष्य एरे। |
| index | int | लक्ष्य एरे में प्रारम्भिक इंडेक्स। |