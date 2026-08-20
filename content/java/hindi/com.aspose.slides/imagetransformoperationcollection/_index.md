---
title: ImageTransformOperationCollection
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एक छवि पर लागू प्रभावों का संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/imagetransformoperationcollection/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**  
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)  
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

एक छवि पर लागू प्रभावों का संग्रह दर्शाता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | संग्रह से उसके सूचकांक द्वारा एक [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) लौटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट सूचकांक पर संग्रह से एक छवि प्रभाव हटाता है। |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | संग्रह के अंत में नया Alpha Bi-Level प्रभाव जोड़ता है। |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | संग्रह के अंत में नया Alpha Ceiling प्रभाव जोड़ता है। |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | संग्रह के अंत में नया Alpha Floor प्रभाव जोड़ता है। |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | संग्रह के अंत में नया Alpha Inverse प्रभाव जोड़ता है। |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | संग्रह के अंत में नया Alpha Modulate प्रभाव जोड़ता है। |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | संग्रह के अंत में नया Alpha Modulate Fixed प्रभाव जोड़ता है। |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | संग्रह के अंत में नया Alpha Replace प्रभाव जोड़ता है। |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | संग्रह के अंत में नया Bi-Level (काला/सफ़ेद) प्रभाव जोड़ता है। |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | संग्रह के अंत में नया Blur प्रभाव जोड़ता है। |
| [addColorChangeEffect()](#addColorChangeEffect--) | संग्रह के अंत में नया Color Change प्रभाव जोड़ता है। |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | संग्रह के अंत में नया Color Replacement प्रभाव जोड़ता है। |
| [addDuotoneEffect()](#addDuotoneEffect--) | संग्रह के अंत में नया Duotone प्रभाव जोड़ता है। |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | संग्रह के अंत में नया Fill Overlay प्रभाव जोड़ता है। |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | संग्रह के अंत में नया Gray Scale प्रभाव जोड़ता है। |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | संग्रह के अंत में नया Hue/Saturation/Luminance प्रभाव जोड़ता है। |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | संग्रह के अंत में नया Luminance प्रभाव जोड़ता है। |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | संग्रह के अंत में नया Tint प्रभाव जोड़ता है। |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | संग्रह के अंत में नया BrightnessContrast प्रभाव जोड़ता है। |
| [size()](#size--) | संग्रह में छवि प्रभावों की संख्या लौटाता है। |
| [isReadOnly()](#isReadOnly--) | एक मान प्राप्त करता है जो इंगित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है या नहीं। |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | संग्रह के अंत में नया छवि प्रभाव जोड़ता है। |
| [clear()](#clear--) | संग्रह से सभी छवि प्रभाव हटाता है। |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | निर्धारित करता है कि क्या [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान है। |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | [IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक Array में कॉपी करता है, जो एक विशिष्ट Array सूचकांक से शुरू होता है। |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | विशिष्ट वस्तु की पहली उपस्थिति को [IGenericCollection](../../com.aspose.slides/igenericcollection) से हटाता है। |
| [iterator()](#iterator--) | एक enumerator लौटाता है जो संग्रह के माध्यम से इटररेट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक java iterator लौटाता है। |

### getVersion() {#getVersion--}
```
public long getVersion()
```

संस्करण। केवल-पढ़ने योग्य लंबा।

**रिटर्न:**  
long

### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

संग्रह से उसके सूचकांक द्वारा एक [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) लौटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | तत्व का सूचकांक। |

**रिटर्न:**  
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) ऑब्जेक्ट।

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

निर्दिष्ट सूचकांक पर संग्रह से एक छवि प्रभाव हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले छवि प्रभाव का सूचकांक। |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

संग्रह के अंत में नया Alpha Bi-Level प्रभाव जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| threshold | float | Alpha Bi-Level प्रभाव के लिए थ्रेशोल्ड मान। |

**रिटर्न:**  
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - संग्रह में नए छवि प्रभाव का सूचकांक।

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

संग्रह के अंत में नया Alpha Ceiling प्रभाव जोड़ता है।

**रिटर्न:**  
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - संग्रह में नए छवि प्रभाव का सूचकांक।

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

संग्रह के अंत में नया Alpha Floor प्रभाव जोड़ता है।

**रिटर्न:**  
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - संग्रह में नए छवि प्रभाव का सूचकांक।

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

संग्रह के अंत में नया Alpha Inverse प्रभाव जोड़ता है।

**रिटर्न:**  
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - संग्रह में नए छवि प्रभाव का सूचकांक।

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

संग्रह के अंत में नया Alpha Modulate प्रभाव जोड़ता है।

**रिटर्न:**  
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - संग्रह में नए छवि प्रभाव का सूचकांक।

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

संग्रह के अंत में नया Alpha Modulate Fixed प्रभाव जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| amount | float | Alpha को स्केल करने के लिए प्रतिशत मान। |

**रिटर्न:**  
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - संग्रह में नए छवि प्रभाव का सूचकांक।

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

संग्रह के अंत में नया Alpha Replace प्रभाव जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| alpha | float | नया अपारदर्शिता मान। |

**रिटर्न:**  
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - संग्रह में नए छवि प्रभाव का सूचकांक।

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

संग्रह के अंत में नया Bi-Level (काला/सफ़ेद) प्रभाव जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| threshold | float | Bi-Level प्रभाव के लिए ल्यूमिनेंस थ्रेशोल्ड। थ्रेशोल्ड से बड़े या बराबर मान सफेद, छोटे मान काला किया जाता है। |

**रिटर्न:**  
[IBiLevel](../../com.aspose.slides/ibilevel) - संग्रह में नए छवि प्रभाव का सूचकांक।

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

संग्रह के अंत में नया Blur प्रभाव जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| radius | double | ब्लर का त्रिज्या। |
| grow | boolean | ब्लर के परिणामस्वरूप ऑब्जेक्ट की सीमाएँ बढ़ेंगी या नहीं। true होने पर सीमाएँ बढ़ेंगी, false होने पर नहीं। |

**रिटर्न:**  
[IBlur](../../com.aspose.slides/iblur) - संग्रह में नए छवि प्रभाव का सूचकांक।

### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

संग्रह के अंत में नया Color Change प्रभाव जोड़ता है।

**रिटर्न:**  
[IColorChange](../../com.aspose.slides/icolorchange) - संग्रह में नए छवि प्रभाव का सूचकांक।

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

संग्रह के अंत में नया Color Replacement प्रभाव जोड़ता है।

**रिटर्न:**  
[IColorReplace](../../com.aspose.slides/icolorreplace) - संग्रह में नए छवि प्रभाव का सूचकांक।

### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

संग्रह के अंत में नया Duotone प्रभाव जोड़ता है।

**रिटर्न:**  
[IDuotone](../../com.aspose.slides/iduotone) - संग्रह में नए छवि प्रभाव का सूचकांक।

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

संग्रह के अंत में नया Fill Overlay प्रभाव जोड़ता है।

**रिटर्न:**  
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - संग्रह में नए छवि प्रभाव का सूचकांक।

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

संग्रह के अंत में नया Gray Scale प्रभाव जोड़ता है।

**रिटर्न:**  
[IGrayScale](../../com.aspose.slides/igrayscale) - संग्रह में नए छवि प्रभाव का सूचकांक।

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

संग्रह के अंत में नया Hue/Saturation/Luminance प्रभाव जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hue | float | ह्यू को समायोजित करने के डिग्री की संख्या। |
| saturation | float | संतृप्ति को समायोजित करने का प्रतिशत। |
| luminance | float | चमक को समायोजित करने का प्रतिशत। |

**रिटर्न:**  
[IHSL](../../com.aspose.slides/ihsl) - संग्रह में नए छवि प्रभाव का सूचकांक।

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

संग्रह के अंत में नया Luminance प्रभाव जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brightness | float | चमक बदलने का प्रतिशत। |
| contrast | float | कंट्रास्ट बदलने का प्रतिशत। |

**रिटर्न:**  
[ILuminance](../../com.aspose.slides/iluminance) - संग्रह में नए छवि प्रभाव का सूचकांक।

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

संग्रह के अंत में नया Tint प्रभाव जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hue | float | वह ह्यू जिससे टिंट किया जाएगा। |
| amount | float | रंग मान के शिफ्ट का प्रतिशत। |

**रिटर्न:**  
[ITint](../../com.aspose.slides/itint) - संग्रह में नए छवि प्रभाव का सूचकांक।

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

संग्रह के अंत में नया BrightnessContrast प्रभाव जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brightness | float | चमक बदलने का प्रतिशत। |
| contrast | float | कंट्रास्ट बदलने का प्रतिशत। |

**रिटर्न:**  
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - संग्रह में नए छवि प्रभाव का सूचकांक।

### size() {#size--}
```
public final int size()
```

संग्रह में छवि प्रभावों की संख्या लौटाता है। केवल-पढ़ने योग्य int।

**रिटर्न:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

एक मान प्राप्त करता है जो इंगित करता है कि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है या नहीं। केवल-पढ़ने योग्य boolean।

**रिटर्न:**  
boolean - true यदि [IGenericCollection](../../com.aspose.slides/igenericcollection) केवल-पढ़ने योग्य है; अन्यथा false।

### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

संग्रह के अंत में नया छवि प्रभाव जोड़ता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | संग्रह के अंत में जोड़ने के लिए छवि प्रभाव। |

### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी छवि प्रभाव हटाता है।

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

निर्धारित करता है कि क्या [IGenericCollection](../../com.aspose.slides/igenericcollection) में कोई विशिष्ट मान है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection) में खोजने के लिए वस्तु। |

**रिटर्न:**  
boolean - true यदि वस्तु [IGenericCollection](../../com.aspose.slides/igenericcollection) में पाई गई; अन्यथा false।

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

[IGenericCollection](../../com.aspose.slides/igenericcollection) के तत्वों को एक Array में कॉपी करता है, जो एक विशिष्ट Array सूचकांक से शुरू होता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | वह एक-आयामी Array जो [IGenericCollection](../../com.aspose.slides/igenericcollection) से कॉपी किए गए तत्वों के लक्ष्य के रूप में कार्य करता है। Array को शून्य-आधारित अनुक्रमण होना चाहिए। |
| arrayIndex | int | वह शून्य-आधारित सूचकांक जहाँ कॉपी शुरू होती है। |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

विशिष्ट वस्तु की पहली उपस्थिति को [IGenericCollection](../../com.aspose.slides/igenericcollection) से हटाता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | [IGenericCollection](../../com.aspose.slides/igenericcollection) से हटाने के लिए वस्तु। |

**रिटर्न:**  
boolean - true यदि वस्तु [IGenericCollection](../../com.aspose.slides/igenericcollection) से सफलतापूर्वक हटाई गई; अन्यथा false। यदि वस्तु मूल [IGenericCollection](../../com.aspose.slides/igenericcollection) में नहीं मिली तो भी यह false लौटाता है।

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

एक enumerator लौटाता है जो संग्रह के माध्यम से इटररेट करता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - एक IGenericEnumerator जो संग्रह को दोहराने के लिए उपयोग किया जा सकता है।

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

पूरे संग्रह के लिए एक java iterator लौटाता है।

**रिटर्न:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - एक java.util.Iterator जो पूरे संग्रह के लिए है।