---
title: IDrawingGuidesCollection
second_title: Java के लिए Aspose.Slides API संदर्भ
description: समायोज्य ड्रॉइंग गाइड्स के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/idrawingguidescollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

समायोज्य ड्रॉइंग गाइड्स का संग्रह दर्शाता है।
## विधियाँ

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the drawing guide by index. |
| [add(byte orientation, float position)](#add-byte-float-) | Adds the drawing guide at the end of the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the drawing guide at the specified index. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [getCount()](#getCount--) | Gets the number of all elements in the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```

इंडेक्स द्वारा ड्रॉइंग गाइड लौटाता है। केवल-पढ़ने योग्य [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**परामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**वापसी मान:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```

ड्रॉइंग गाइड को संग्रह के अंत में जोड़ता है।

**परामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| orientation | byte | ड्रॉइंग गाइड की अभिविन्यास। |
| position | float | ड्रॉइंग गाइड का पॉइंट्स में स्थान। |

**वापसी मान:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर ड्रॉइंग गाइड हटाता है।

**परामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ड्रॉइंग गाइड का इंडेक्स जिसे हटाया जाना चाहिए। |

### clear() {#clear--}
```
public abstract void clear()
```

सभी तत्वों को संग्रह से हटा देता है।

### getCount() {#getCount--}
```
public abstract int getCount()
```

संग्रह में सभी तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int.

**वापसी मान:**
int