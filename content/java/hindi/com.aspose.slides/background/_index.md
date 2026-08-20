---
title: Background
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: एक स्लाइड की पृष्ठभूमि का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/background/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject  
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

एक स्लाइड की पृष्ठभूमि का प्रतिनिधित्व करता है।
## विधियाँ

| Method | Description |
| --- | --- |
| [getType()](#getType--) | बैकग्राउंड फ़िल का एक प्रकार लौटाता है। |
| [setType(byte value)](#setType-byte-) | बैकग्राउंड फ़िल का एक प्रकार लौटाता है। |
| [getFillFormat()](#getFillFormat--) | BackgroundType.OwnBackground फ़िल के लिए FillFormat लौटाता है। |
| [getEffectFormat()](#getEffectFormat--) | BackgroundType.OwnBackground फ़िल के लिए EffectFormat लौटाता है। |
| [getStyleColor()](#getStyleColor--) | BackgroundType.Themed फ़िल के लिए ColorFormat लौटाता है। |
| [getStyleIndex()](#getStyleIndex--) | बैकग्राउंड थीम संग्रह में BackgroundType.Themed फ़िल का इंडेक्स लौटाता है। |
| [setStyleIndex(int value)](#setStyleIndex-int-) | बैकग्राउंड थीम संग्रह में BackgroundType.Themed फ़िल का इंडेक्स लौटाता है। |
| [getEffective()](#getEffective--) | विरासत लागू होने पर प्रभावी बैकग्राउंड डेटा प्राप्त करता है। |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | एक आकार (shape) की पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | एक स्लाइड की पैरेंट प्रस्तुति लौटाता है। |
### getType() {#getType--}
```
public final byte getType()
```


बैकग्राउंड फ़िल का एक प्रकार लौटाता है। पढ़ें/लिखें [BackgroundType](../../com.aspose.slides/backgroundtype)।

**वापसी:**  
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```


बैकग्राउंड फ़िल का एक प्रकार लौटाता है। पढ़ें/लिखें [BackgroundType](../../com.aspose.slides/backgroundtype)।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


BackgroundType.OwnBackground फ़िल के लिए FillFormat लौटाता है। केवल-पढ़ने योग्य [IFillFormat](../../com.aspose.slides/ifillformat)।

**वापसी:**  
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```


BackgroundType.OwnBackground फ़िल के लिए EffectFormat लौटाता है। केवल-पढ़ने योग्य [IEffectFormat](../../com.aspose.slides/ieffectformat)।

**वापसी:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```


BackgroundType.Themed फ़िल के लिए ColorFormat लौटाता है। केवल-पढ़ने योग्य [IColorFormat](../../com.aspose.slides/icolorformat)।

**वापसी:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```


बैकग्राउंड थीम संग्रह में BackgroundType.Themed फ़िल का इंडेक्स लौटाता है। 0 का अर्थ कोई फ़िल नहीं। 1..999 - इंडेक्स। पढ़ें/लिखें int।

**वापसी:**  
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```


बैकग्राउंड थीम संग्रह में BackgroundType.Themed फ़िल का इंडेक्स लौटाता है। 0 का अर्थ कोई फ़िल नहीं। 1..999 - इंडेक्स। पढ़ें/लिखें int।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```


विरासत लागू होने पर प्रभावी बैकग्राउंड डेटा प्राप्त करता है।

--------------------

> ```
> This example demonstrates getting effective background properties.
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

**वापसी:**  
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - एक [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


संस्करण। केवल-पढ़ने योग्य long।

**वापसी:**  
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**वापसी:**  
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```


एक आकार (shape) की पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../../com.aspose.slides/ibaseslide)।

**वापसी:**  
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```


एक स्लाइड की पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**वापसी:**  
[Presentation](../../com.aspose.slides/presentation)