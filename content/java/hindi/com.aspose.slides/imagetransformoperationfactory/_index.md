---
title: ImageTransformOperationFactory
second_title: Aspose.Slides for Java API संदर्भ
description: इमेज ट्रांसफ़ॉर्म ऑपरेशन्स बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/imagetransformoperationfactory/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)
```
public class ImageTransformOperationFactory implements IImageTransformOperationFactory
```

इमेज ट्रांसफ़ॉर्म ऑपरेशन्स बनाने की अनुमति देता है

--------------------

COM संगतता के लिए।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Alpha BiLevel प्रभाव बनाता है। |
| [createAlphCeiling()](#createAlphCeiling--) | Alpha Ceiling प्रभाव बनाता है। |
| [createAlphaFloor()](#createAlphaFloor--) | Alpha floor प्रभाव बनाता है। |
| [createAlphaInverse()](#createAlphaInverse--) | Alpha inverse प्रभाव बनाता है। |
| [createAlphaModulate()](#createAlphaModulate--) | Alpha modulate प्रभाव बनाता है। |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Alpha modulate fixed प्रभाव बनाता है। |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Alpha replace प्रभाव बनाता है। |
| [createBiLevel(float threshold)](#createBiLevel-float-) | BiLevel प्रभाव बनाता है। |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Blur प्रभाव बनाता है। |
| [createColorChange()](#createColorChange--) | Color change प्रभाव बनाता है। |
| [createColorReplace()](#createColorReplace--) | Color replace प्रभाव बनाता है। |
| [createDuotone()](#createDuotone--) | Duotone प्रभाव बनाता है। |
| [createFillOverlay()](#createFillOverlay--) | Fill overlay प्रभाव बनाता है। |
| [createGrayScale()](#createGrayScale--) | Gray scale प्रभाव बनाता है। |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Hue Saturation Luminance प्रभाव बनाता है। |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Luminance प्रभाव बनाता है। |
| [createTint(float hue, float amount)](#createTint-float-float-) | Tint प्रभाव बनाता है। |
### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```


### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```


Alpha BiLevel प्रभाव बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| threshold | float | थ्रेशहोल्ड। |

**रिटर्न:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel प्रभाव।

### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```


Alpha Ceiling प्रभाव बनाता है।

**रिटर्न:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling प्रभाव।

### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```


Alpha floor प्रभाव बनाता है।

**रिटर्न:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor प्रभाव।

### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```


Alpha inverse प्रभाव बनाता है।

**रिटर्न:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst effect।

### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```


Alpha modulate प्रभाव बनाता है।

**रिटर्न:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate प्रभाव।

### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```


Alpha modulate fixed प्रभाव बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| amount | float | राशि। |

**रिटर्न:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed प्रभाव।

### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```


Alpha replace प्रभाव बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| alpha | float | Alpha |

**रिटर्न:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace प्रभाव।

### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```


BiLevel प्रभाव बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| threshold | float | थ्रेशहोल्ड। |

**रिटर्न:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel प्रभाव।

### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```


Blur प्रभाव बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| radius | double | त्रिज्या। |
| grow | boolean | बढ़ाना। |

**रिटर्न:**
[IBlur](../../com.aspose.slides/iblur) - Blur प्रभाव।

### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```


Color change प्रभाव बनाता है।

**रिटर्न:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change प्रभाव।

### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```


Color replace प्रभाव बनाता है।

**रिटर्न:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace प्रभाव।

### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```


Duotone प्रभाव बनाता है।

**रिटर्न:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone प्रभाव।

### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```


Fill overlay प्रभाव बनाता है।

**रिटर्न:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay प्रभाव।

### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```


Gray scale प्रभाव बनाता है।

**रिटर्न:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Gray scale प्रभाव लौटाता है।

### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```


Hue Saturation Luminance प्रभाव बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hue | float | ह्यू। |
| saturation | float | सैचुरेशन। |
| luminance | float | ल्यूमिनेंस। |

**रिटर्न:**
[IHSL](../../com.aspose.slides/ihsl) - HSL प्रभाव।

### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```


Luminance प्रभाव बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brightness | float | ब्राइटनेस। |
| contrast | float | कॉन्ट्रास्ट। |

**रिटर्न:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance प्रभाव।

### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```


Tint प्रभाव बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hue | float | ह्यू। |
| amount | float | राशि। |

**रिटर्न:**
[ITint](../../com.aspose.slides/itint) - Tint प्रभाव।