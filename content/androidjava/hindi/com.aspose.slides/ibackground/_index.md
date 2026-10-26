---
title: IBackground
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
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
## विधियां

| मेथड | विवरण |
| --- | --- |
| [getType()](#getType--) | पृष्ठभूमि फ़िल का प्रकार लौटाता है। |
| [setType(byte value)](#setType-byte-) | पृष्ठभूमि फ़िल का प्रकार लौटाता है। |
| [getFillFormat()](#getFillFormat--) | FillFormat को BackgroundType.OwnBackground फ़िल के लिए लौटाता है। |
| [getEffectFormat()](#getEffectFormat--) | EffectFormat को BackgroundType.OwnBackground फ़िल के लिए लौटाता है। |
| [getStyleColor()](#getStyleColor--) | ColorFormat को BackgroundType.Themed फ़िल के लिए लौटाता है। |
| [getStyleIndex()](#getStyleIndex--) | BackgroundType.Themed फ़िल का इंडेक्स पृष्ठभूमि थीम संग्रह में लौटाता है। |
| [setStyleIndex(int value)](#setStyleIndex-int-) | BackgroundType.Themed फ़िल का इंडेक्स पृष्ठभूमि थीम संग्रह में लौटाता है। |
| [getEffective()](#getEffective--) | विरासत लागू करके प्रभावी पृष्ठभूमि डेटा प्राप्त करता है। |
### getType() {#getType--}
```
public abstract byte getType()
```

पृष्ठभूमि फ़िल का प्रकार लौटाता है। पढ़ने/लिखने [BackgroundType](../../com.aspose.slides/backgroundtype)।

**वापसी:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

पृष्ठभूमि फ़िल का प्रकार लौटाता है। पढ़ने/लिखने [BackgroundType](../../com.aspose.slides/backgroundtype)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

FillFormat को BackgroundType.OwnBackground फ़िल के लिए लौटाता है। केवल पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

**वापसी:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

EffectFormat को BackgroundType.OwnBackground फ़िल के लिए लौटाता है। केवल पढ़ने योग्य [IEffectFormat](../../com.aspose.slides/ieffectformat)।

**वापसी:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```

ColorFormat को BackgroundType.Themed फ़िल के लिए लौटाता है। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```

BackgroundType.Themed फ़िल का इंडेक्स पृष्ठभूमि थीम संग्रह में लौटाता है। 0 का मतलब कोई फ़िल नहीं। 1..999 - इंडेक्स। पढ़ने/लिखने int।

**वापसी:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```

BackgroundType.Themed फ़िल का इंडेक्स पृष्ठभूमि थीम संग्रह में लौटाता है। 0 का मतलब कोई फ़िल नहीं। 1..999 - इंडेक्स। पढ़ने/लिखने int।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```

विरासत लागू करके प्रभावी पृष्ठभूमि डेटा प्राप्त करता है।

**वापसी:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).