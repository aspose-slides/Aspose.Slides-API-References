---
title: IImageTransformOperationCollection
second_title: Aspose.Slides for Android Java API referenciája
description: Képre alkalmazott effektusok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/iimagetransformoperationcollection/
---
**Összes megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

Egy képre alkalmazott effektusok gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszatér egy [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) a gyűjteményből az index alapján. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy képeffektust a gyűjteményből a megadott indexnél. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Hozzáad egy új Alpha Bi-Level effektust a gyűjtemény végéhez. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Hozzáad egy új Alpha Ceiling effektust a gyűjtemény végéhez. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Hozzáad egy új Alpha Floor effektust a gyűjtemény végéhez. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Hozzáad egy új Alpha Inverse effektust a gyűjtemény végéhez. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Hozzáad egy új Alpha Modulate effektust a gyűjtemény végéhez. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Hozzáad egy új Alpha Modulate Fixed effektust a gyűjtemény végéhez. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Hozzáad egy új Alpha Replace effektust a gyűjtemény végéhez. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Hozzáad egy új Bi-Level (black/white) effektust a gyűjtemény végéhez. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Hozzáad egy új Blur effektust a gyűjtemény végéhez. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Hozzáad egy új Color Change effektust a gyűjtemény végéhez. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Hozzáad egy új Color Replacement effektust a gyűjtemény végéhez. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Hozzáad egy új Duotone efektust a gyűjtemény végéhez. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Hozzáad egy új Fill Overlay effektust a gyűjtemény végéhez. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Hozzáad egy új Gray Scale effektust a gyűjtemény végéhez. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Hozzáad egy új Hue/Saturation/Luminance effektust a gyűjtemény végéhez. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Hozzáad egy új Luminance effektust a gyűjtemény végéhez. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Hozzáad egy új Tint effektust a gyűjtemény végéhez. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Hozzáad egy új BrightnessContrast effektust a gyűjtemény végéhez. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

Visszatér egy [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) a gyűjteményből az index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe. |

**Visszatér:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - A [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) objektum.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolít egy képeffektust a gyűjteményből a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő képeffektus indexe. |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Hozzáad egy új Alpha Bi-Level effektust a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| threshold | float | Az Alpha Bi-Level effektus küszöbértéke. |

**Visszatér:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Az új képeffektus indexe a gyűjteményben.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

Hozzáad egy új Alpha Ceiling effektust a gyűjtemény végéhez.

**Visszatér:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Az új képeffektus indexe a gyűjteményben.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

Hozzáad egy új Alpha Floor effektust a gyűjtemény végéhez.

**Visszatér:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Az új képeffektus indexe a gyűjteményben.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

Hozzáad egy új Alpha Inverse effektust a gyűjtemény végéhez.

**Visszatér:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Az új képeffektus indexe a gyűjteményben.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

Hozzáad egy új Alpha Modulate effektust a gyűjtemény végéhez.

**Visszatér:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Az új képeffektus indexe a gyűjteményben.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Hozzáad egy új Alpha Modulate Fixed effektust a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| amount | float | Az alfa skálázás százalékos értéke. |

**Visszatér:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Az új képeffektus indexe a gyűjteményben.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Hozzáad egy új Alpha Replace effektust a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| alpha | float | Az új átlátszóságérték. |

**Visszatér:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Az új képeffektus indexe a gyűjteményben.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

Hozzáad egy új Bi-Level (black/white) effektust a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| threshold | float | A Bi-Level effektus fényerő küszöbértéke. A küszöbértéknél nagyobb vagy egyenlő értékek fehérré válnak, míg az alatta lévők feketék. |

**Visszatér:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Az új képeffektus indexe a gyűjteményben.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

Hozzáad egy új Blur effektust a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| radius | double | A elmosás sugara. |
| grow | boolean | Meghatározza, hogy a homályosítás következtében a objektum határai növekedjenek-e. Az igaz érték növeli a határokat, a hamis érték nem növeli. |

**Visszatér:**
[IBlur](../../com.aspose.slides/iblur) - Az új képeffektus indexe a gyűjteményben.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

Hozzáad egy új Color Change effektust a gyűjtemény végéhez.

**Visszatér:**
[IColorChange](../../com.aspose.slides/icolorchange) - Az új képeffektus indexe a gyűjteményben.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

Hozzáad egy új Color Replacement effektust a gyűjtemény végéhez.

**Visszatér:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Az új képeffektus indexe a gyűjteményben.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

Hozzáad egy új Duotone effektust a gyűjtemény végéhez.

**Visszatér:**
[IDuotone](../../com.aspose.slides/iduotone) - Az új képeffektus indexe a gyűjteményben.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

Hozzáad egy új Fill Overlay effektust a gyűjtemény végéhez.

**Visszatér:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Az új képeffektus indexe a gyűjteményben.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

Hozzáad egy új Gray Scale effektust a gyűjtemény végéhez.

**Visszatér:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Az új képeffektus indexe a gyűjteményben.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Hozzáad egy új Hue/Saturation/Luminance effektust a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hue | float | A színárnyalat eltolásának fokszáma. |
| saturation | float | A telítettség százalékos módosítása. |
| luminance | float | A fényerő százalékos módosítása. |

**Visszatér:**
[IHSL](../../com.aspose.slides/ihsl) - Az új képeffektus indexe a gyűjteményben.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

Hozzáad egy új Luminance effektust a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| brightness | float | A fényerő módosításának százalékos értéke. |
| contrast | float | A kontraszt módosításának százalékos értéke. |

**Visszatér:**
[ILuminance](../../com.aspose.slides/iluminance) - Az új képeffektus indexe a gyűjteményben.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

Hozzáad egy új Tint effektust a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hue | float | A színárnyalat, amely felé színezni kell. |
| amount | float | Megadja, hogy mennyire legyen eltolva a színérték. |

**Visszatér:**
[ITint](../../com.aspose.slides/itint) - Az új képeffektus indexe a gyűjteményben.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Hozzáad egy új BrightnessContrast effektust a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| brightness | float | A fényerő módosításának százalékos értéke. |
| contrast | float | A kontraszt módosításának százalékos értéke. |

**Visszatér:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Az új képeffektus indexe a gyűjteményben.