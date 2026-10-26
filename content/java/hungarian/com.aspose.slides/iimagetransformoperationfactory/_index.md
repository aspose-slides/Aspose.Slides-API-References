---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Java API Reference
description: Lehetővé teszi képhatások példányainak létrehozását
type: docs
url: /hu/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Lehetővé teszi a képhatások példányainak létrehozását

--------------------

COM interfészhez.
## Metódusok

| Módszer | Leírás |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Alpha BiLevel hatást hoz létre. |
| [createAlphCeiling()](#createAlphCeiling--) | Alpha Ceiling hatást hoz létre. |
| [createAlphaFloor()](#createAlphaFloor--) | Alpha floor hatást hoz létre. |
| [createAlphaInverse()](#createAlphaInverse--) | Alpha inverse hatást hoz létre. |
| [createAlphaModulate()](#createAlphaModulate--) | Alpha modulate hatást hoz létre. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Alpha modulate fixed hatást hoz létre. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Alpha replace hatást hoz létre. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | BiLevel hatást hoz létre. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Blur hatást hoz létre. |
| [createColorChange()](#createColorChange--) | Color change hatást hoz létre. |
| [createColorReplace()](#createColorReplace--) | Color replace hatást hoz létre. |
| [createDuotone()](#createDuotone--) | Duotone hatást hoz létre. |
| [createFillOverlay()](#createFillOverlay--) | Fill overlay hatást hoz létre. |
| [createGrayScale()](#createGrayScale--) | Gray scale hatást hoz létre. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Hue Saturation Luminance hatást hoz létre. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Luminance hatást hoz létre. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Tint hatást hoz létre. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Alpha BiLevel hatást hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| threshold | float | Küszöb. |

**Visszatérési érték:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel hatás.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

Alpha Ceiling hatást hoz létre.

**Visszatérési érték:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling hatás.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

Alpha floor hatást hoz létre.

**Visszatérési érték:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor hatás.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

Alpha inverse hatást hoz létre.

**Visszatérési érték:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst hatás.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

Alpha modulate hatást hoz létre.

**Visszatérési érték:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate hatás.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Alpha modulate fixed hatást hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| amount | float | Mennyiség. |

**Visszatérési érték:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed hatás.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

Alpha replace hatást hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| alpha | float | Alpha |

**Visszatérési érték:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace hatás.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

BiLevel hatást hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| threshold | float | Küszöb. |

**Visszatérési érték:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel hatás.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

Blur hatást hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| radius | double | Radius. |
| grow | boolean | Grow. |

**Visszatérési érték:**
[IBlur](../../com.aspose.slides/iblur) - Blur hatás.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

Color change hatást hoz létre.

**Visszatérési érték:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change hatás.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

Color replace hatást hoz létre.

**Visszatérési érték:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace hatás.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

Duotone hatást hoz létre.

**Visszatérési érték:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone hatás.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

Fill overlay hatást hoz létre.

**Visszatérési érték:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay hatás.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

Gray scale hatást hoz létre.

**Visszatérési érték:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Returns gray scale effect.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

Hue Saturation Luminance hatást hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hue | float | Hue. |
| saturation | float | Saturation. |
| luminance | float | Luminance. |

**Visszatérési érték:**
[IHSL](../../com.aspose.slides/ihsl) - HSL hatás.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

Luminance hatást hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| brightness | float | Brightness. |
| contrast | float | Contrast. |

**Visszatérési érték:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance hatás.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

Tint hatást hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hue | float | Hue. |
| amount | float | Mennyiség. |

**Visszatérési érték:**
[ITint](../../com.aspose.slides/itint) - Tint hatás.