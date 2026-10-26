---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create image effects instances
type: docs
url: /hi/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

इमेज इफ़ेक्ट्स के इंस्टेंस बनाने की अनुमति देता है

--------------------

COM इंटरफ़ेस के लिए.
## विधियाँ

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
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Alpha BiLevel प्रभाव बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| threshold | float | थ्रेसहोल्ड। |

**रिटर्न:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel प्रभाव।

### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

Alpha Ceiling प्रभाव बनाता है।

**रिटर्न:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling प्रभाव।

### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

Alpha floor प्रभाव बनाता है।

**रिटर्न:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor प्रभाव।

### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

Alpha inverse प्रभाव बनाता है।

**रिटर्न:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst प्रभाव।

### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

Alpha modulate प्रभाव बनाता है।

**रिटर्न:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate प्रभाव।

### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Alpha modulate fixed प्रभाव बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| amount | float | Amount। |

**रिटर्न:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed प्रभाव।

### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

Alpha replace प्रभाव बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| alpha | float | Alpha। |

**रिटर्न:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace प्रभाव।

### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

BiLevel प्रभाव बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| threshold | float | थ्रेसहोल्ड। |

**रिटर्न:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel प्रभाव।

### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

Blur प्रभाव बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| radius | double | Radius। |
| grow | boolean | Grow। |

**रिटर्न:**
[IBlur](../../com.aspose.slides/iblur) - Blur प्रभाव।

### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

Color change प्रभाव बनाता है।

**रिटर्न:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change प्रभाव।

### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

Color replace प्रभाव बनाता है।

**रिटर्न:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace प्रभाव।

### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

Duotone प्रभाव बनाता है।

**रिटर्न:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone प्रभाव।

### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

Fill overlay प्रभाव बनाता है।

**रिटर्न:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay प्रभाव।

### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

Gray scale प्रभाव बनाता है।

**रिटर्न:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Gray scale प्रभाव लौटाता है।

### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

Hue Saturation Luminance प्रभाव बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hue | float | Hue। |
| saturation | float | Saturation। |
| luminance | float | Luminance। |

**रिटर्न:**
[IHSL](../../com.aspose.slides/ihsl) - HSL प्रभाव।

### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

Luminance प्रभाव बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| brightness | float | Brightness। |
| contrast | float | Contrast। |

**रिटर्न:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance प्रभाव।

### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

Tint प्रभाव बनाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hue | float | Hue। |
| amount | float | Amount। |

**रिटर्न:**
[ITint](../../com.aspose.slides/itint) - Tint प्रभाव।