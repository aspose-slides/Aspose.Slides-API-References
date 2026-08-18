---
title: IImageTransformOperationCollection
second_title: Aspose.Slides Java API referencia
description: Képhez alkalmazott effektusok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/iimagetransformoperationcollection/
---
**Minden implementált interfész:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

Egy képhez alkalmazott effektusok gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) a gyűjteményből a megadott index alapján. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy képeffektust a gyűjteményből a megadott indexnél. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Hozzáadja az új Alpha Bi-Level effektust a gyűjtemény végéhez. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Hozzáadja az új Alpha Ceiling effektust a gyűjtemény végéhez. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Hozzáadja az új Alpha Floor effektust a gyűjtemény végéhez. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Hozzáadja az új Alpha Inverse effektust a gyűjtemény végéhez. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Hozzáadja az új Alpha Modulate effektust a gyűjtemény végéhez. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Hozzáadja az új Alpha Modulate Fixed effektust a gyűjtemény végéhez. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Hozzáadja az új Alpha Replace effektust a gyűjtemény végéhez. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Hozzáadja az új Bi-Level (black/white) effektust a gyűjtemény végéhez. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Hozzáadja az új Blur effektust a gyűjtemény végéhez. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Hozzáadja az új Color Change effektust a gyűjtemény végéhez. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Hozzáadja az új Color Replacement effektust a gyűjtemény végéhez. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Hozzáadja az új Duotone effektust a gyűjtemény végéhez. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Hozzáadja az új Fill Overlay effektust a gyűjtemény végéhez. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Hozzáadja az új Gray Scale effektust a gyűjtemény végéhez. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Hozzáadja az új Hue/Saturation/Luminance effektust a gyűjtemény végéhez. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Hozzáadja az új Luminance effektust a gyűjtemény végéhez. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Hozzáadja az új Tint effektust a gyűjtemény végéhez. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Hozzáadja az új BrightnessContrast effektust a gyűjtemény végéhez. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

Visszaad egy [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) a gyűjteményből a megadott index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe. |

**Visszatérési érték:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - A [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) objektum.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolít egy képeffektust a gyűjteményből a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó képeffektus indexe. |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Hozzáadja az új Alpha Bi-Level effektust a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| threshold | float | Az alfa bi-level effektus küszöbértéke. |

**Visszatérési érték:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Az új képeffektus indexe a gyűjteményben.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

Hozzáadja az új Alpha Ceiling effektust a gyűjtemény végéhez.

**Visszatérési érték:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Az új képeffektus indexe a gyűjteményben.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

Hozzáadja az új Alpha Floor effektust a gyűjtemény végéhez.

**Visszatérési érték:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Az új képeffektus indexe a gyűjteményben.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

Hozzáadja az új Alpha Inverse effektust a gyűjtemény végéhez.

**Visszatérési érték:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Az új képeffektus indexe a gyűjteményben.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

Hozzáadja az új Alpha Modulate effektust a gyűjtemény végéhez.

**Visszatérési érték:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Az új képeffektus indexe a gyűjteményben.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Hozzáadja az új Alpha Modulate Fixed effektust a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| amount | float | Az alfa skálázásának százalékos értéke. |

**Visszatérési érték:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Az új képeffektus indexe a gyűjteményben.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Hozzáadja az új Alpha Replace effektust a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| alpha | float | Az új átlátszóságérték. |

**Visszatérési érték:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Az új képeffektus indexe a gyűjteményben.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

Hozzáadja az új Bi-Level (black/white) effektust a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| threshold | float | A Bi-Level effektus luminancia küszöbértéke. A küszöbértéknél nagyobb vagy egyenlő értékek fehérré, kisebbek feketére válnak. |

**Visszatérési érték:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Az új képeffektus indexe a gyűjteményben.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

Hozzáadja az új Blur effektust a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| radius | double | A elmosás sugara. |
| grow | boolean | Meghatározza, hogy a blur miatt a objektum határai növekedjenek-e. Az igaz érték növeli a határokat, hamis érték nem növeli. |

**Visszatérési érték:**
[IBlur](../../com.aspose.slides/iblur) - Az új képeffektus indexe a gyűjteményben.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

Hozzáadja az új Color Change effektust a gyűjtemény végéhez.

**Visszatérési érték:**
[IColorChange](../../com.aspose.slides/icolorchange) - Az új képeffektus indexe a gyűjteményben.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

Hozzáadja az új Color Replacement effektust a gyűjtemény végéhez.

**Visszatérési érték:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Az új képeffektus indexe a gyűjteményben.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

Hozzáadja az új Duotone effektust a gyűjtemény végéhez.

**Visszatérési érték:**
[IDuotone](../../com.aspose.slides/iduotone) - Az új képeffektus indexe a gyűjteményben.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

Hozzáadja az új Fill Overlay effektust a gyűjtemény végéhez.

**Visszatérési érték:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Az új képeffektus indexe a gyűjteményben.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

Hozzáadja az új Gray Scale effektust a gyűjtemény végéhez.

**Visszatérési érték:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Az új képeffektus indexe a gyűjteményben.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Hozzáadja az új Hue/Saturation/Luminance effektust a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hue | float | A színárnyalat eltolásának fokszáma. |
| saturation | float | A telítettség állandó százalékos módosítása. |
| luminance | float | A luminancia állandó százalékos módosítása. |

**Visszatérési érték:**
[IHSL](../../com.aspose.slides/ihsl) - Az új képeffektus indexe a gyűjteményben.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

Hozzáadja az új Luminance effektust a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| brightness | float | A fényerő változtatásának százalékos értéke. |
| contrast | float | A kontraszt változtatásának százalékos értéke. |

**Visszatérési érték:**
[ILuminance](../../com.aspose.slides/iluminance) - Az új képeffektus indexe a gyűjteményben.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

Hozzáadja az új Tint effektust a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hue | float | A színárnyalat, amely felé a színezés történik. |
| amount | float | Megadja, hogy mennyire legyen eltolva a színérték. |

**Visszatérési érték:**
[ITint](../../com.aspose.slides/itint) - Az új képeffektus indexe a gyűjteményben.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Hozzáadja az új BrightnessContrast effektust a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| brightness | float | A fényerő változtatásának százalékos értéke. |
| contrast | float | A kontraszt változtatásának százalékos értéke. |

**Visszatérési érték:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Az új képeffektus indexe a gyűjteményben.