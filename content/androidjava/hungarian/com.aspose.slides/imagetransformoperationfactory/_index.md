---
title: ImageTransformOperationFactory
second_title: Aspose.Slides Android számára a Java API hivatkozás segítségével
description: Lehetővé teszi képtranszformációs műveletek létrehozását
type: docs
url: /hu/com.aspose.slides/imagetransformoperationfactory/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IImageTransformOperationFactory](../../com.aspose.slides/iimagetransformoperationfactory)
```
public class ImageTransformOperationFactory implements IImageTransformOperationFactory
```

Lehetővé teszi képtranszformációs műveletek létrehozását

--------------------

COM kompatibilitáshoz.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [ImageTransformOperationFactory()](#ImageTransformOperationFactory--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Létrehozza az Alpha BiLevel hatást. |
| [createAlphCeiling()](#createAlphCeiling--) | Létrehozza az Alpha Ceiling hatást. |
| [createAlphaFloor()](#createAlphaFloor--) | Létrehozza az Alpha floor hatást. |
| [createAlphaInverse()](#createAlphaInverse--) | Létrehozza az Alpha inverse hatást. |
| [createAlphaModulate()](#createAlphaModulate--) | Létrehozza az Alpha modulate hatást. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Létrehozza az Alpha modulate fixed hatást. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Létrehozza az Alpha replace hatást. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | Létrehozza a BiLevel hatást. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Létrehozza a Blur hatást. |
| [createColorChange()](#createColorChange--) | Létrehozza a Color change hatást. |
| [createColorReplace()](#createColorReplace--) | Létrehozza a Color replace hatást. |
| [createDuotone()](#createDuotone--) | Létrehozza a Duotone hatást. |
| [createFillOverlay()](#createFillOverlay--) | Létrehozza a Fill overlay hatást. |
| [createGrayScale()](#createGrayScale--) | Létrehozza a Gray scale hatást. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Létrehozza a Hue Saturation Luminance hatást. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Létrehozza a Luminance hatást. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Létrehozza a Tint hatást. |
### ImageTransformOperationFactory() {#ImageTransformOperationFactory--}
```
public ImageTransformOperationFactory()
```


### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public final IAlphaBiLevel createAlphaBiLevel(float threshold)
```


Létrehozza az Alpha BiLevel hatást.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| threshold | float | Küszöb. |

**Visszatér:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel hatás.
### createAlphCeiling() {#createAlphCeiling--}
```
public final IAlphaCeiling createAlphCeiling()
```


Létrehozza az Alpha Ceiling hatást.

**Visszatér:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling hatás.
### createAlphaFloor() {#createAlphaFloor--}
```
public final IAlphaFloor createAlphaFloor()
```


Létrehozza az Alpha floor hatást.

**Visszatér:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor hatás.
### createAlphaInverse() {#createAlphaInverse--}
```
public final IAlphaInverse createAlphaInverse()
```


Létrehozza az Alpha inverse hatást.

**Visszatér:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst hatás.
### createAlphaModulate() {#createAlphaModulate--}
```
public final IAlphaModulate createAlphaModulate()
```


Létrehozza az Alpha modulate hatást.

**Visszatér:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate hatás.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public final IAlphaModulateFixed createAlphaModulateFixed(float amount)
```


Létrehozza az Alpha modulate fixed hatást.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| amount | float | Mennyiség. |

**Visszatér:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed hatás.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public final IAlphaReplace createAlphaReplace(float alpha)
```


Létrehozza az Alpha replace hatást.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| alpha | float | Alpha |

**Visszatér:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace hatás.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public final IBiLevel createBiLevel(float threshold)
```


Létrehozza a BiLevel hatást.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| threshold | float | Küszöb. |

**Visszatér:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel hatás.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public final IBlur createBlur(double radius, boolean grow)
```


Létrehozza a Blur hatást.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| radius | double | Sugár. |
| grow | boolean | Növekedés. |

**Visszatér:**
[IBlur](../../com.aspose.slides/iblur) - Blur hatás.
### createColorChange() {#createColorChange--}
```
public final IColorChange createColorChange()
```


Létrehozza a Color change hatást.

**Visszatér:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change hatás.
### createColorReplace() {#createColorReplace--}
```
public final IColorReplace createColorReplace()
```


Létrehozza a Color replace hatást.

**Visszatér:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace hatás.
### createDuotone() {#createDuotone--}
```
public final IDuotone createDuotone()
```


Létrehozza a Duotone hatást.

**Visszatér:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone hatás.
### createFillOverlay() {#createFillOverlay--}
```
public final IFillOverlay createFillOverlay()
```


Létrehozza a Fill overlay hatást.

**Visszatér:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay hatás.
### createGrayScale() {#createGrayScale--}
```
public final IGrayScale createGrayScale()
```


Létrehozza a Gray scale hatást.

**Visszatér:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Returns gray scale effect.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public final IHSL createHSL(float hue, float saturation, float luminance)
```


Létrehozza a Hue Saturation Luminance hatást.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Visszatér:**
[IHSL](../../com.aspose.slides/ihsl) - HSL hatás.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public final ILuminance createLuminance(float brightness, float contrast)
```


Létrehozza a Luminance hatást.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| brightness | float | Brightness. |
| contrast | float | Contrast. |

**Visszatér:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance hatás.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public final ITint createTint(float hue, float amount)
```


Létrehozza a Tint hatást.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Amount. |

**Visszatér:**
[ITint](../../com.aspose.slides/itint) - Tint hatás.