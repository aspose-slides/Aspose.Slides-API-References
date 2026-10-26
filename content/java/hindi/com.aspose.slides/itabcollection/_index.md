---
title: ITabCollection
second_title: Aspose.Slides for Java API संदर्भ
description: टैब्स का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/itabcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

Tabs का एक संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [add(double position, int align)](#add-double-int-) | संग्रह में एक Tab जोड़ता है। |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | संग्रह में एक Tab जोड़ता है। |
| [clear()](#clear--) | संग्रह से सभी तत्वों को हटाता है। |
| [removeAt(int index)](#removeAt-int-) | संग्रह में निर्दिष्ट सूचकांक पर तत्व को हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [ITab](../../com.aspose.slides/itab).

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```

संग्रह में एक Tab जोड़ता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| position | double | Tab स्थिति। |
| align | int | Tab संरेखण। |

**रिटर्न:**
[ITab](../../com.aspose.slides/itab) - जोड़ा गया Tab।
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```

संग्रह में एक Tab जोड़ता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | संग्रह के अंत में जोड़े जाने वाला Tab वस्तु। |

**रिटर्न:**
int - वह सूचकांक जिस पर Tab जोड़ा गया।
### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी तत्वों को हटाता है।

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

संग्रह में निर्दिष्ट सूचकांक पर तत्व को हटाता है।

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले तत्व का शून्य-आधारित सूचकांक। |