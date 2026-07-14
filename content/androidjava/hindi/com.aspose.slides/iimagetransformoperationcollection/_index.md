---
title: IImageTransformOperationCollection
second_title: Aspose.Slides for Android के लिए जावा API संदर्भ
description: एक छवि पर लागू प्रभावों के संग्रह का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iimagetransformoperationcollection/
---
**सभी लागू इंटरफेस:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

एक छवि पर लागू प्रभावों का संग्रह दर्शाता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | संग्रह से उसके अनुक्रमांक द्वारा एक [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) लौटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट अनुक्रमांक पर संग्रह से एक इमेज इफ़ेक्ट हटाता है। |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | संग्रह के अंत में नया Alpha Bi-Level इफ़ेक्ट जोड़ता है। |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | संग्रह के अंत में नया Alpha Ceiling इफ़ेक्ट जोड़ता है। |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | संग्रह के अंत में नया Alpha Floor इफ़ेक्ट जोड़ता है। |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | संग्रह के अंत में नया Alpha Inverse इफ़ेक्ट जोड़ता है। |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | संग्रह के अंत में नया Alpha Modulate इफ़ेक्ट जोड़ता है। |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | संग्रह के अंत में नया Alpha Modulate Fixed इफ़ेक्ट जोड़ता है। |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | संग्रह के अंत में नया Alpha Replace इफ़ेक्ट जोड़ता है। |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | संग्रह के अंत में नया Bi-Level (काली/सफ़ेद) इफ़ेक्ट जोड़ता है। |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | संग्रह के अंत में नया Blur इफ़ेक्ट जोड़ता है। |
| [addColorChangeEffect()](#addColorChangeEffect--) | संग्रह के अंत में नया Color Change इफ़ेक्ट जोड़ता है। |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | संग्रह के अंत में नया Color Replacement इफ़ेक्ट जोड़ता है। |
| [addDuotoneEffect()](#addDuotoneEffect--) | संग्रह के अंत में नया Duotone इफ़ेक्ट जोड़ता है। |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | संग्रह के अंत में नया Fill Overlay इफ़ेक्ट जोड़ता है। |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | संग्रह के अंत में नया Gray Scale इफ़ेक्ट जोड़ता है। |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | संग्रह के अंत में नया Hue/Saturation/Luminance इफ़ेक्ट जोड़ता है। |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | संग्रह के अंत में नया Luminance इफ़ेक्ट जोड़ता है। |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | संग्रह के अंत में नया Tint इफ़ेक्ट जोड़ता है। |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | संग्रह के अंत में नया BrightnessContrast इफ़ेक्ट जोड़ता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

संग्रह से उसके अनुक्रमांक द्वारा एक [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | आइटम का अनुक्रमांक। |

**वापसी:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) ऑब्जेक्ट।

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

निर्दिष्ट अनुक्रमांक पर संग्रह से एक इमेज इफ़ेक्ट हटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int | हटाए जाने वाले इमेज इफ़ेक्ट का अनुक्रमांक। |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

संग्रह के अंत में नया Alpha Bi-Level इफ़ेक्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| threshold | float | Alpha Bi-Level इफ़ेक्ट के लिए थ्रेशोल्ड मान। |

**वापसी:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - संग्रह में नए इमेज इफ़ेक्ट का अनुक्रमांक।

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

संग्रह के अंत में नया Alpha Ceiling इफ़ेक्ट जोड़ता है।

**वापसी:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - संग्रह में नए इमेज इफ़ेक्ट का अनुक्रमांक।

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

संग्रह के अंत में नया Alpha Floor इफ़ेक्ट जोड़ता है।

**वापसी:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - संग्रह में नए इमेज इफ़ेक्ट का अनुक्रमांक।

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

संग्रह के अंत में नया Alpha Inverse इफ़ेक्ट जोड़ता है।

**वापसी:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - संग्रह में नए इमेज इफ़ेक्ट का अनुक्रमांक।

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

संग्रह के अंत में नया Alpha Modulate इफ़ेक्ट जोड़ता है।

**वापसी:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - संग्रह में नए इमेज इफ़ेक्ट का अनुक्रमांक।

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

संग्रह के अंत में नया Alpha Modulate Fixed इफ़ेक्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| amount | float | अल्फा को स्केल करने का प्रतिशत मान। |

**वापसी:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - संग्रह में नए इमेज इफ़ेक्ट का अनुक्रमांक।

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

संग्रह के अंत में नया Alpha Replace इफ़ेक्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| alpha | float | नया अपारदर्शिता मान। |

**वापसी:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - संग्रह में नए इमेज इफ़ेक्ट का अनुक्रमांक।

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

संग्रह के अंत में नया Bi-Level (काली/सफ़ेद) इफ़ेक्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| threshold | float | Bi-Level इफ़ेक्ट के लिए ल्यूमिनेंस थ्रेशोल्ड। थ्रेशोल्ड से अधिक या बराबर मान सफ़ेद सेट होते हैं, जबकि थ्रेशोल्ड से कम मान काले सेट होते हैं। |

**वापसी:**
[IBiLevel](../../com.aspose.slides/ibilevel) - संग्रह में नए इमेज इफ़ेक्ट का अनुक्रमांक।

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

संग्रह के अंत में नया Blur इफ़ेक्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| radius | double | ब्लर का त्रिज्या। |
| grow | boolean | ब्लर के परिणामस्वरूप वस्तु की सीमाएँ बढ़नी चाहिए या नहीं। सत्य होने पर सीमाएँ बढ़ती हैं, अन्यथा नहीं। |

**वापसी:**
[IBlur](../../com.aspose.slides/iblur) - संग्रह में नए इमेज इफ़ेक्ट का अनुक्रमांक।

### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

संग्रह के अंत में नया Color Change इफ़ेक्ट जोड़ता है।

**वापसी:**
[IColorChange](../../com.aspose.slides/icolorchange) - संग्रह में नए इमेज इफ़ेक्ट का अनुक्रमांक।

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

संग्रह के अंत में नया Color Replacement इफ़ेक्ट जोड़ता है।

**वापसी:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - संग्रह में नए इमेज इफ़ेक्ट का अनुक्रमांक।

### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

संग्रह के अंत में नया Duotone इफ़ेक्ट जोड़ता है।

**वापसी:**
[IDuotone](../../com.aspose.slides/iduotone) - संग्रह में नए इमेज इफ़ेक्ट का अनुक्रमांक।

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

संग्रह के अंत में नया Fill Overlay इफ़ेक्ट जोड़ता है।

**वापसी:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - संग्रह में नए इमेज इफ़ेक्ट का अनुक्रमांक।

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

संग्रह के अंत में नया Gray Scale इफ़ेक्ट जोड़ता है।

**वापसी:**
[IGrayScale](../../com.aspose.slides/igrayscale) - संग्रह में नए इमेज इफ़ेक्ट का अनुक्रमांक।

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

संग्रह के अंत में नया Hue/Saturation/Luminance इफ़ेक्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hue | float | ह्यू को समायोजित करने के डिग्री की संख्या। |
| saturation | float | संतृप्ति को समायोजित करने का प्रतिशत। |
| luminance | float | ल्यूमिनेंस को समायोजित करने का प्रतिशत। |

**वापसी:**
[IHSL](../../com.aspose.slides/ihsl) - संग्रह में नए इमेज इफ़ेक्ट का अनुक्रमांक।

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

संग्रह के अंत में नया Luminance इफ़ेक्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brightness | float | ब्राइटनेस को बदलने का प्रतिशत। |
| contrast | float | कंट्रास्ट को बदलने का प्रतिशत। |

**वापसी:**
[ILuminance](../../com.aspose.slides/iluminance) - संग्रह में नए इमेज इफ़ेक्ट का अनुक्रमांक।

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

संग्रह के अंत में नया Tint इफ़ेक्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hue | float | वह ह्यू जिससे टिंट किया जाता है। |
| amount | float | रंग मान किस हद तक बदलता है, यह दर्शाता है। |

**वापसी:**
[ITint](../../com.aspose.slides/itint) - संग्रह में नए इमेज इफ़ेक्ट का अनुक्रमांक।

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

संग्रह के अंत में नया BrightnessContrast इफ़ेक्ट जोड़ता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brightness | float | ब्राइटनेस को बदलने का प्रतिशत। |
| contrast | float | कंट्रास्ट को बदलने का प्रतिशत। |

**वापसी:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - संग्रह में नए इमेज इफ़ेक्ट का अनुक्रमांक।