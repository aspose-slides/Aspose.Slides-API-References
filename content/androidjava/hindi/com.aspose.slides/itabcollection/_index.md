---
title: ITabCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: टैब का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/itabcollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

tabs का एक संग्रह दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [add(double position, int align)](#add-double-int-) | संग्रह में एक Tab जोड़ता है। |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | संग्रह में एक Tab जोड़ता है। |
| [clear()](#clear--) | संग्रह से सभी तत्व हटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह में निर्दिष्ट सूचकांक पर तत्व को हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [ITab](../../com.aspose.slides/itab)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न मान:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```

संग्रह में एक Tab जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | double | Tab स्थिति। |
| align | int | Tab संरेखण। |

**रिटर्न मान:**
[ITab](../../com.aspose.slides/itab) - जोड़या गया tab।
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```

संग्रह में एक Tab जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | संग्रह के अंत में जोड़ी जाने वाली Tab वस्तु। |

**रिटर्न मान:**
int - वह सूचकांक जहाँ tab जोड़ा गया था।
### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी तत्व हटाता है।

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

संग्रह में निर्दिष्ट सूचकांक पर तत्व को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले तत्व का शून्य-आधारित सूचकांक। |