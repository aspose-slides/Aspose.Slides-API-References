---
title: IDrawingGuidesCollection
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: समायोज्य ड्रॉइंग गाइड्स के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/idrawingguidescollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

ड्राइंग गाइड को समायोज्य बनाने वाली एक संग्रह का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | इंडेक्स द्वारा ड्राइंग गाइड लौटाता है। |
| [add(byte orientation, float position)](#add-byte-float-) | कलेक्शन के अंत में ड्राइंग गाइड जोड़ता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर ड्राइंग गाइड हटाता है। |
| [clear()](#clear--) | कलेक्शन से सभी तत्व हटाता है। |
| [getCount()](#getCount--) | कलेक्शन में सभी तत्वों की संख्या प्राप्त करता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```


इंडेक्स द्वारा ड्राइंग गाइड लौटाता है। केवल-पढ़ने योग्य [IDrawingGuide](../../com.aspose.slides/idrawingguide)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```


कलेक्शन के अंत में ड्राइंग गाइड जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| orientation | byte | ड्राइंग गाइड की दिशा। |
| position | float | ड्राइंग गाइड की स्थिति बिंदुओं में। |

**रिटर्न:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


निर्दिष्ट इंडेक्स पर ड्राइंग गाइड हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले ड्राइंग गाइड का इंडेक्स। |

### clear() {#clear--}
```
public abstract void clear()
```


कलेक्शन से सभी तत्व हटाता है।

### getCount() {#getCount--}
```
public abstract int getCount()
```


कलेक्शन में सभी तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int।

**रिटर्न:**
int