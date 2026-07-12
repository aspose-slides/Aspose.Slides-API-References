---
title: IImageTransformOperationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Lehetővé teszi képhatások példányainak létrehozását
type: docs
url: /hu/com.aspose.slides/iimagetransformoperationfactory/
---```
public interface IImageTransformOperationFactory
```

Lehetővé teszi képhatások példányainak létrehozását

--------------------

COM interfészhez.
## Módszerek

| Method | Leírás |
| --- | --- |
| [createAlphaBiLevel(float threshold)](#createAlphaBiLevel-float-) | Alpha BiLevel effektust hoz létre. |
| [createAlphCeiling()](#createAlphCeiling--) | Alpha Ceiling effektust hoz létre. |
| [createAlphaFloor()](#createAlphaFloor--) | Alpha floor effektust hoz létre. |
| [createAlphaInverse()](#createAlphaInverse--) | Alpha inverse effektust hoz létre. |
| [createAlphaModulate()](#createAlphaModulate--) | Alpha modulate effektust hoz létre. |
| [createAlphaModulateFixed(float amount)](#createAlphaModulateFixed-float-) | Alpha modulate fixed effektust hoz létre. |
| [createAlphaReplace(float alpha)](#createAlphaReplace-float-) | Alpha replace effektust hoz létre. |
| [createBiLevel(float threshold)](#createBiLevel-float-) | BiLevel effektust hoz létre. |
| [createBlur(double radius, boolean grow)](#createBlur-double-boolean-) | Blur effektust hoz létre. |
| [createColorChange()](#createColorChange--) | Color change effektust hoz létre. |
| [createColorReplace()](#createColorReplace--) | Color replace effektust hoz létre. |
| [createDuotone()](#createDuotone--) | Duotone effektust hoz létre. |
| [createFillOverlay()](#createFillOverlay--) | Fill overlay effektust hoz létre. |
| [createGrayScale()](#createGrayScale--) | Gray scale effektust hoz létre. |
| [createHSL(float hue, float saturation, float luminance)](#createHSL-float-float-float-) | Hue Saturation Luminance effektust hoz létre. |
| [createLuminance(float brightness, float contrast)](#createLuminance-float-float-) | Luminance effektust hoz létre. |
| [createTint(float hue, float amount)](#createTint-float-float-) | Tint effektust hoz létre. |
### createAlphaBiLevel(float threshold) {#createAlphaBiLevel-float-}
```
public abstract IAlphaBiLevel createAlphaBiLevel(float threshold)
```

Alpha BiLevel effektust hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| threshold | float | Küszöb. |

**Visszatérési érték:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Alpha BiLevel effektus.
### createAlphCeiling() {#createAlphCeiling--}
```
public abstract IAlphaCeiling createAlphCeiling()
```

Alpha Ceiling effektust hoz létre.

**Visszatérési érték:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Alpha Ceiling effektus.
### createAlphaFloor() {#createAlphaFloor--}
```
public abstract IAlphaFloor createAlphaFloor()
```

Alpha floor effektust hoz létre.

**Visszatérési érték:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Alpha floor effektus.
### createAlphaInverse() {#createAlphaInverse--}
```
public abstract IAlphaInverse createAlphaInverse()
```

Alpha inverse effektust hoz létre.

**Visszatérési érték:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Alpha inverst effektus.
### createAlphaModulate() {#createAlphaModulate--}
```
public abstract IAlphaModulate createAlphaModulate()
```

Alpha modulate effektust hoz létre.

**Visszatérési érték:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Alpha modulate effektus.
### createAlphaModulateFixed(float amount) {#createAlphaModulateFixed-float-}
```
public abstract IAlphaModulateFixed createAlphaModulateFixed(float amount)
```

Alpha modulate fixed effektust hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| amount | float | Mennyiség. |

**Visszatérési érték:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Alpha modulate fixed effektus.
### createAlphaReplace(float alpha) {#createAlphaReplace-float-}
```
public abstract IAlphaReplace createAlphaReplace(float alpha)
```

Alpha replace effektust hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| alpha | float | Alpha |

**Visszatérési érték:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Alpha replace effektus.
### createBiLevel(float threshold) {#createBiLevel-float-}
```
public abstract IBiLevel createBiLevel(float threshold)
```

BiLevel effektust hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| threshold | float | Küszöb. |

**Visszatérési érték:**
[IBiLevel](../../com.aspose.slides/ibilevel) - BiLevel effektus.
### createBlur(double radius, boolean grow) {#createBlur-double-boolean-}
```
public abstract IBlur createBlur(double radius, boolean grow)
```

Blur effektust hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| radius | double | Sugár. |
| grow | boolean | Növelés. |

**Visszatérési érték:**
[IBlur](../../com.aspose.slides/iblur) - Blur effektus.
### createColorChange() {#createColorChange--}
```
public abstract IColorChange createColorChange()
```

Color change effektust hoz létre.

**Visszatérési érték:**
[IColorChange](../../com.aspose.slides/icolorchange) - Color change effektus.
### createColorReplace() {#createColorReplace--}
```
public abstract IColorReplace createColorReplace()
```

Color replace effektust hoz létre.

**Visszatérési érték:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Color replace effektus.
### createDuotone() {#createDuotone--}
```
public abstract IDuotone createDuotone()
```

Duotone effektust hoz létre.

**Visszatérési érték:**
[IDuotone](../../com.aspose.slides/iduotone) - Duotone effektus.
### createFillOverlay() {#createFillOverlay--}
```
public abstract IFillOverlay createFillOverlay()
```

Fill overlay effektust hoz létre.

**Visszatérési érték:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Fill overlay effektus.
### createGrayScale() {#createGrayScale--}
```
public abstract IGrayScale createGrayScale()
```

Gray scale effektust hoz létre.

**Visszatérési érték:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Gray scale effektus.
### createHSL(float hue, float saturation, float luminance) {#createHSL-float-float-float-}
```
public abstract IHSL createHSL(float hue, float saturation, float luminance)
```

Hue Saturation Luminance effektust hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hue | float | Árnyalat. |
| saturation | float | Telítettség. |
| luminance | float | Fénysűrűség. |

**Visszatérési érték:**
[IHSL](../../com.aspose.slides/ihsl) - HSL effektus.
### createLuminance(float brightness, float contrast) {#createLuminance-float-float-}
```
public abstract ILuminance createLuminance(float brightness, float contrast)
```

Luminance effektust hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| brightness | float | Fényerő. |
| contrast | float | Kontraszt. |

**Visszatérési érték:**
[ILuminance](../../com.aspose.slides/iluminance) - Luminance effektus.
### createTint(float hue, float amount) {#createTint-float-float-}
```
public abstract ITint createTint(float hue, float amount)
```

Tint effektust hoz létre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hue | float | Árnyalat. |
| amount | float | Mennyiség. |

**Visszatérési érték:**
[ITint](../../com.aspose.slides/itint) - Tint effektus.