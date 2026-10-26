---
title: Background
second_title: Aspose.Slides Android के लिए Java API संदर्भ
description: एक स्लाइड की पृष्ठभूमि का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/background/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू किए गए इंटरफ़ेस:**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

स्लाइड की पृष्ठभूमि का प्रतिनिधित्व करता है.
## विधाएँ

| मेथड | विवरण |
| --- | --- |
| [getType()](#getType--) | पृष्ठभूमि भराई का प्रकार लौटाता है। |
| [setType(byte value)](#setType-byte-) | पृष्ठभूमि भराई का प्रकार लौटाता है। |
| [getFillFormat()](#getFillFormat--) | BackgroundType.OwnBackground भराई के लिए एक FillFormat लौटाता है। |
| [getEffectFormat()](#getEffectFormat--) | BackgroundType.OwnBackground भराई के लिए एक EffectFormat लौटाता है। |
| [getStyleColor()](#getStyleColor--) | BackgroundType.Themed भराई के लिए एक ColorFormat लौटाता है। |
| [getStyleIndex()](#getStyleIndex--) | BackgroundType.Themed भराई का इंडेक्स पृष्ठभूमि थीम संग्रह में लौटाता है। |
| [setStyleIndex(int value)](#setStyleIndex-int-) | BackgroundType.Themed भराई का इंडेक्स पृष्ठभूमि थीम संग्रह में लौटाता है। |
| [getEffective()](#getEffective--) | विरासत लागू करके प्रभावी पृष्ठभूमि डेटा प्राप्त करता है। |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | एक आकार का पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | स्लाइड की पैरेंट प्रेज़ेंटेशन लौटाता है। |
### getType() {#getType--}
```
public final byte getType()
```


पृष्ठभूमि भराई का प्रकार लौटाता है। पढ़ें/लिखें [BackgroundType](../../com.aspose.slides/backgroundtype).

**रिटर्न:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```


पृष्ठभूमि भराई का प्रकार लौटाता है। पढ़ें/लिखें [BackgroundType](../../com.aspose.slides/backgroundtype).

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


BackgroundType.OwnBackground भराई के लिए एक FillFormat लौटाता है। केवल पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat).

**रिटर्न:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```


BackgroundType.OwnBackground भराई के लिए एक EffectFormat लौटाता है। केवल पढ़ने योग्य [IEffectFormat](../../com.aspose.slides/ieffectformat).

**रिटर्न:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```


BackgroundType.Themed भराई के लिए एक ColorFormat लौटाता है। केवल पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat).

**रिटर्न:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```


BackgroundType.Themed भराई का इंडेक्स पृष्ठभूमि थीम संग्रह में लौटाता है। 0 का अर्थ कोई भराई नहीं। 1..999 - इंडेक्स। पढ़ें/लिखें int.

**रिटर्न:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```


BackgroundType.Themed भराई का इंडेक्स पृष्ठभूमि थीम संग्रह में लौटाता है। 0 का अर्थ कोई भराई नहीं। 1..999 - इंडेक्स। पढ़ें/लिखें int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```


विरासत लागू करके प्रभावी पृष्ठभूमि डेटा प्राप्त करता है।

--------------------

> ``` 
> यह उदाहरण प्रभावी पृष्ठभूमि गुण प्राप्त करने को दर्शाता है।
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IBackgroundEffectiveData effectiveBackground = pres.getSlides().get_Item(0).getBackground().getEffective();
>  	System.out.println("Background fill type: " + effectiveBackground.getFillFormat().getFillType());
>  	System.out.println("Any effects applied: " + !effectiveBackground.getEffectFormat().isNoEffects());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - एक [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


संस्करण। केवल पढ़ने योग्य long.

**रिटर्न:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate ऑब्जेक्ट लौटाता है। केवल पढ़ने योग्य IDOMObject.

**रिटर्न:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```


एक आकार का पैरेंट स्लाइड लौटाता है। केवल पढ़ने योग्य [IBaseSlide](../../com.aspose.slides/ibaseslide).

**रिटर्न:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```


स्लाइड की पैरेंट प्रेज़ेंटेशन लौटाता है। केवल पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation).

**रिटर्न:**
[Presentation](../../com.aspose.slides/presentation)