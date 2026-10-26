---
title: ImageTransformOperationCollection
second_title: Aspose.Slides के लिए Android, Java API रेफ़रेंस के माध्यम से
description: एक छवि पर लागू प्रभावों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/imagetransformoperationcollection/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

किसी छवि पर लागू प्रभावों के संग्रह का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | कलेक्शन से उसके इंडेक्स द्वारा एक [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) लौटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर संग्रह से एक छवि प्रभाव हटाता है। |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | नए Alpha Bi-Level प्रभाव को संग्रह के अंत में जोड़ता है। |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | नए Alpha Ceiling प्रभाव को संग्रह के अंत में जोड़ता है। |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | नए Alpha Floor प्रभाव को संग्रह के अंत में जोड़ता है। |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | नए Alpha Inverse प्रभाव को संग्रह के अंत में जोड़ता है। |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | नए Alpha Modulate प्रभाव को संग्रह के अंत में जोड़ता है। |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | नए Alpha Modulate Fixed प्रभाव को संग्रह के अंत में जोड़ता है। |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | नए Alpha Replace प्रभाव को संग्रह के अंत में जोड़ता है। |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | नए Bi-Level (black/white) प्रभाव को संग्रह के अंत में जोड़ता है। |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | नए Blur प्रभाव को संग्रह के अंत में जोड़ता है। |
| [addColorChangeEffect()](#addColorChangeEffect--) | नए Color Change प्रभाव को संग्रह के अंत में जोड़ता है। |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | नए Color Replacement प्रभाव को संग्रह के अंत में जोड़ता है। |
| [addDuotoneEffect()](#addDuotoneEffect--) | नए Duotone प्रभाव को संग्रह के अंत में जोड़ता है। |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | नए Fill Overlay प्रभाव को संग्रह के अंत में जोड़ता है। |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | नए Gray Scale प्रभाव को संग्रह के अंत में जोड़ता है। |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | नए Hue/Saturation/Luminance प्रभाव को संग्रह के अंत में जोड़ता है। |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | नए Luminance प्रभाव को संग्रह के अंत में जोड़ता है। |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | नए Tint प्रभाव को संग्रह के अंत में जोड़ता है। |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | नए BrightnessContrast प्रभाव को संग्रह के अंत में जोड़ता है। |
| [size()](#size--) | संग्रह में छवि प्रभावों की संख्या लौटाता है। |
| [isReadOnly()](#isReadOnly--) | यह निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है या नहीं। |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | नए छवि प्रभाव को संग्रह के अंत में जोड़ता है। |
| [clear()](#clear--) | संग्रह से सभी छवि प्रभावों को हटाता है। |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में विशिष्ट मूल्य मौजूद है या नहीं। |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक Array में कॉपी करता है, एक विशेष Array इंडेक्स से शुरू करते हुए। |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) से एक विशिष्ट ऑब्जेक्ट की पहली घटना को हटाता है। |
| [iterator()](#iterator--) | एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से इटरेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरी संग्रह के लिए एक java इटरेटर लौटाता है। |
### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने योग्य long।

**वापसी:**
long
### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

इंडेक्स द्वारा संग्रह से एक [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | तत्व का इंडेक्स। |

**वापसी:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) ऑब्जेक्ट।
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट इंडेक्स पर संग्रह से एक छवि प्रभाव हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले छवि प्रभाव का इंडेक्स। |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

नए Alpha Bi-Level प्रभाव को संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| threshold | float | Alpha Bi-Level प्रभाव के लिए थ्रेशहोल्ड मान। |

**वापसी:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - संग्रह में नए छवि प्रभाव का इंडेक्स।
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

नए Alpha Ceiling प्रभाव को संग्रह के अंत में जोड़ता है।

**वापसी:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - संग्रह में नए छवि प्रभाव का इंडेक्स।
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

नए Alpha Floor प्रभाव को संग्रह के अंत में जोड़ता है।

**वापसी:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - संग्रह में नए छवि प्रभाव का इंडेक्स।
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

नए Alpha Inverse प्रभाव को संग्रह के अंत में जोड़ता है।

**वापसी:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - संग्रह में नए छवि प्रभाव का इंडेक्स।
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

नए Alpha Modulate प्रभाव को संग्रह के अंत में जोड़ता है।

**वापसी:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - संग्रह में नए छवि प्रभाव का इंडेक्स।
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

नए Alpha Modulate Fixed प्रभाव को संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| amount | float | Alpha को स्केल करने के लिए प्रतिशत मात्रा। |

**वापसी:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - संग्रह में नए छवि प्रभाव का इंडेक्स।
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

नए Alpha Replace प्रभाव को संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| alpha | float | नई अपारदर्शिता मान। |

**वापसी:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - संग्रह में नए छवि प्रभाव का इंडेक्स।
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

नए Bi-Level (black/white) प्रभाव को संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| threshold | float | Bi-Level प्रभाव के लिए ल्यूमिनेंस थ्रेशहोल्ड। थ्रेशहोल्ड से अधिक या बराबर मान को सफेद सेट किया जाता है, कम मान को काला। |

**वापसी:**
[IBiLevel](../../com.aspose.slides/ibilevel) - संग्रह में नए छवि प्रभाव का इंडेक्स।
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

नए Blur प्रभाव को संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| radius | double | ब्लर का त्रिज्या। |
| grow | boolean | ब्लर के परिणामस्वरूप ऑब्जेक्ट की सीमाएँ बढ़ानी हैं या नहीं। true होने पर सीमाएँ बढ़ती हैं, false होने पर नहीं। |

**वापसी:**
[IBlur](../../com.aspose.slides/iblur) - संग्रह में नए छवि प्रभाव का इंडेक्स।
### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

नए Color Change प्रभाव को संग्रह के अंत में जोड़ता है।

**वापसी:**
[IColorChange](../../com.aspose.slides/icolorchange) - संग्रह में नए छवि प्रभाव का इंडेक्स।
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

नए Color Replacement प्रभाव को संग्रह के अंत में जोड़ता है।

**वापसी:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - संग्रह में नए छवि प्रभाव का इंडेक्स।
### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

नए Duotone प्रभाव को संग्रह के अंत में जोड़ता है।

**वापसी:**
[IDuotone](../../com.aspose.slides/iduotone) - संग्रह में नए छवि प्रभाव का इंडेक्स।
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

नए Fill Overlay प्रभाव को संग्रह के अंत में जोड़ता है।

**वापसी:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - संग्रह में नए छवि प्रभाव का इंडेक्स।
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

नए Gray Scale प्रभाव को संग्रह के अंत में जोड़ता है।

**वापसी:**
[IGrayScale](../../com.aspose.slides/igrayscale) - संग्रह में नए छवि प्रभाव का इंडेक्स।
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

नए Hue/Saturation/Luminance प्रभाव को संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hue | float | ह्यू को समायोजित करने के डिग्री की संख्या। |
| saturation | float | सैचुरेशन को समायोजित करने का प्रतिशत। |
| luminance | float | ल्यूमिनेंस को समायोजित करने का प्रतिशत। |

**वापसी:**
[IHSL](../../com.aspose.slides/ihsl) - संग्रह में नए छवि प्रभाव का इंडेक्स।
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

नए Luminance प्रभाव को संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brightness | float | चमक बदलने का प्रतिशत। |
| contrast | float | कंट्रास्ट बदलने का प्रतिशत। |

**वापसी:**
[ILuminance](../../com.aspose.slides/iluminance) - संग्रह में नए छवि प्रभाव का इंडेक्स।
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

नए Tint प्रभाव को संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hue | float | वह ह्यू जिससे टिंट किया जाता है। |
| amount | float | यह निर्धारित करता है कि रंग मान कितना शिफ्ट किया गया है। |

**वापसी:**
[ITint](../../com.aspose.slides/itint) - संग्रह में नए छवि प्रभाव का इंडेक्स।
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

नए BrightnessContrast प्रभाव को संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brightness | float | चमक बदलने का प्रतिशत। |
| contrast | float | कंट्रास्ट बदलने का प्रतिशत। |

**वापसी:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - संग्रह में नए छवि प्रभाव का इंडेक्स।
### size() {#size--}
```
public final int size()
```

संग्रह में छवि प्रभावों की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**वापसी:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) के केवल-पढ़ने योग्य होने का मान प्राप्त करता है। केवल-पढ़ने योग्य boolean।

**वापसी:**
boolean - true यदि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है; अन्यथा false।
### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

नए छवि प्रभाव को संग्रह के अंत में जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | संग्रह के अंत में जोड़ने के लिए छवि प्रभाव। |
### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी छवि प्रभावों को हटाता है।
### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

निर्धारित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) में विशिष्ट मान मौजूद है या नहीं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection) में खोजा जाने वाला ऑब्जेक्ट। |

**वापसी:**
boolean - true यदि आइटम [IGenericCollection](../../com.aspose.slides/igenericcollection) में मिला; अन्यथा false।
### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक Array में कॉपी करता है, एक विशेष Array इंडेक्स से शुरू करते हुए।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | वह एक-आयामी Array जो [IGenericCollection](../../com.aspose.slides/igenericcollection) से कॉपी किए गए तत्वों का लक्ष्य है। Array में शून्य-आधारित अनुक्रमणिका होनी चाहिए। |
| arrayIndex | int | शून्य-आधारित इंडेक्स जहाँ कॉपी शुरू होती है। |
### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) से एक विशिष्ट ऑब्जेक्ट की पहली घटना को हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection) से हटाने के लिए ऑब्जेक्ट। |

**वापसी:**
boolean - true यदि आइटम [IGenericCollection](../../com.aspose.slides/igenericcollection) से सफलतापूर्वक हटाया गया; अन्यथा false। यदि आइटम मूल [IGenericCollection](../../com.aspose.slides/igenericcollection) में नहीं मिला तो यह मेथड भी false लौटाता है।
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

संग्रह के माध्यम से इटरेट करने वाला एक एन्यूमरेटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - एक IGenericEnumerator जो संग्रह के माध्यम से इटरेट करने के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

पूरे संग्रह के लिए एक java इटरेटर लौटाता है।

**वापसी:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - एक java.util.Iterator जो पूरे संग्रह के लिए है।