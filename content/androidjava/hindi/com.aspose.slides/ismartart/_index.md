---
title: ISmartArt
second_title: Aspose.Slides for Android के माध्यम से Java API रेफ़रेंस
description: एक SmartArt आरेख का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ismartart/
---
**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

एक SmartArt आरेख का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | SmartArt ऑब्जेक्ट में सभी नोड्स के संग्रह लौटाता है। |
| [getNodes()](#getNodes--) | SmartArt ऑब्जेक्ट में मूल नोड्स के संग्रह लौटाता है। |
| [getLayout()](#getLayout--) | SmartArt ऑब्जेक्ट का लेआउट लौटाएँ या सेट करें। |
| [setLayout(int value)](#setLayout-int-) | SmartArt ऑब्जेक्ट का लेआउट लौटाएँ या सेट करें। |
| [getQuickStyle()](#getQuickStyle--) | SmartArt ऑब्जेक्ट की क्विक शैली लौटाएँ या सेट करें। |
| [setQuickStyle(int value)](#setQuickStyle-int-) | SmartArt ऑब्जेक्ट की क्विक शैली लौटाएँ या सेट करें। |
| [getColorStyle()](#getColorStyle--) | SmartArt ऑब्जेक्ट की रंग शैली लौटाएँ या सेट करें। |
| [setColorStyle(int value)](#setColorStyle-int-) | SmartArt ऑब्जेक्ट की रंग शैली लौटाएँ या सेट करें। |
| [isReversed()](#isReversed--) | SmartArt आरेख की स्थिति को (बाएँ-से-दाएँ) LTR या (दाएँ-से-बाएँ) RTL के संबंध में लौटाएँ या सेट करें, यदि आरेख उलटने का समर्थन करता है। |
| [setReversed(boolean value)](#setReversed-boolean-) | SmartArt आरेख की स्थिति को (बाएँ-से-दाएँ) LTR या (दाएँ-से-बाएँ) RTL के संबंध में लौटाएँ या सेट करें, यदि आरेख उलटने का समर्थन करता है। |

### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

SmartArt ऑब्जेक्ट में सभी नोड्स के संग्रह लौटाता है। केवल-पढ़ने योग्य [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**वापसी:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

SmartArt ऑब्जेक्ट में मूल नोड्स के संग्रह लौटाता है। केवल-पढ़ने योग्य [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**वापसी:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

SmartArt ऑब्जेक्ट का लेआउट लौटाएँ या सेट करें। पढ़ने-लिखने योग्य [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**वापसी:**
int

### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

SmartArt ऑब्जेक्ट का लेआउट लौटाएँ या सेट करें। पढ़ने-लिखने योग्य [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

SmartArt ऑब्जेक्ट की क्विक शैली लौटाएँ या सेट करें। पढ़ने-लिखने योग्य [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**वापसी:**
int

### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```

SmartArt ऑब्जेक्ट की क्विक शैली लौटाएँ या सेट करें। पढ़ने-लिखने योग्य [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

SmartArt ऑब्जेक्ट की रंग शैली लौटाएँ या सेट करें। पढ़ने-लिखने योग्य [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**वापसी:**
int

### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

SmartArt ऑब्जेक्ट की रंग शैली लौटाएँ या सेट करें। पढ़ने-लिखने योग्य [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

SmartArt आरेख की स्थिति को (बाएँ-से-दाएँ) LTR या (दाएँ-से-बाएँ) RTL के संबंध में लौटाएँ या सेट करें, यदि आरेख उलटने का समर्थन करता है। पढ़ने-लिखने योग्य boolean।

**वापसी:**
boolean

### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

SmartArt आरेख की स्थिति को (बाएँ-से-दाएँ) LTR या (दाएँ-से-बाएँ) RTL के संबंध में लौटाएँ या सेट करें, यदि आरेख उलटने का समर्थन करता है। पढ़ने-लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |