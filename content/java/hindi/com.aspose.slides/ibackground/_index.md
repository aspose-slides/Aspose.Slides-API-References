---
title: IBackground
second_title: Aspose.Slides for Java API संदर्भ
description: एक स्लाइड की पृष्ठभूमि का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/ibackground/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

एक स्लाइड की पृष्ठभूमि का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getType()](#getType--) | पृष्ठभूमि भराव का एक प्रकार लौटाता है। |
| [setType(byte value)](#setType-byte-) | पृष्ठभूमि भराव का एक प्रकार लौटाता है। |
| [getFillFormat()](#getFillFormat--) | BackgroundType.OwnBackground भराव के लिए एक FillFormat लौटाता है। |
| [getEffectFormat()](#getEffectFormat--) | BackgroundType.OwnBackground भराव के लिए एक EffectFormat लौटाता है। |
| [getStyleColor()](#getStyleColor--) | BackgroundType.Themed भराव के लिए एक ColorFormat लौटाता है। |
| [getStyleIndex()](#getStyleIndex--) | पृष्ठभूमि थीम संग्रह में BackgroundType.Themed भराव के लिए एक इंडेक्स लौटाता है। |
| [setStyleIndex(int value)](#setStyleIndex-int-) | पृष्ठभूमि थीम संग्रह में BackgroundType.Themed भराव के लिए एक इंडेक्स लौटाता है। |
| [getEffective()](#getEffective--) | विरासत लागू होने के साथ प्रभावी पृष्ठभूमि डेटा प्राप्त करता है। |
### getType() {#getType--}
```
public abstract byte getType()
```

पृष्ठभूमि भराव का एक प्रकार लौटाता है। पढ़ने/लिखने योग्य [BackgroundType](../../com.aspose.slides/backgroundtype).

**रिटर्न:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

पृष्ठभूमि भराव का एक प्रकार लौटाता है। पढ़ने/लिखने योग्य [BackgroundType](../../com.aspose.slides/backgroundtype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

BackgroundType.OwnBackground भराव के लिए एक FillFormat लौटाता है। केवल-पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat).

**रिटर्न:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

BackgroundType.OwnBackground भराव के लिए एक EffectFormat लौटाता है। केवल-पढ़ने योग्य [IEffectFormat](../../com.aspose.slides/ieffectformat).

**रिटर्न:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```

BackgroundType.Themed भराव के लिए एक ColorFormat लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```

पृष्ठभूमि थीम संग्रह में BackgroundType.Themed भराव के लिए एक इंडेक्स लौटाता है। 0 का अर्थ कोई भराव नहीं। 1..999 - इंडेक्स। पढ़ने/लिखने योग्य int.

**रिटर्न:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```

पृष्ठभूमि थीम संग्रह में BackgroundType.Themed भराव के लिए एक इंडेक्स लौटाता है। 0 का अर्थ कोई भराव नहीं। 1..999 - इंडेक्स। पढ़ने/लिखने योग्य int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```

विरासत लागू होने के साथ प्रभावी पृष्ठभूमि डेटा प्राप्त करता है।

**रिटर्न:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - एक [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).