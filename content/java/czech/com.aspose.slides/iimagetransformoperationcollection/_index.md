---
title: IImageTransformOperationCollection
second_title: Aspose.Slides pro Java – API Reference
description: Představuje kolekci efektů aplikovaných na obrázek.
type: docs
url: /cs/com.aspose.slides/iimagetransformoperationcollection/
---
**Všechny implementované rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

Představuje kolekci efektů aplikovaných na obrázek.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrátí [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) ze sbírky podle jeho indexu. |
| [removeAt(int index)](#removeAt-int-) | Odstraní efekt obrazu ze sbírky na zadaném indexu. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Přidá nový efekt Alpha Bi-Level na konec sbírky. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Přidá nový efekt Alpha Ceiling na konec sbírky. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Přidá nový efekt Alpha Floor na konec sbírky. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Přidá nový efekt Alpha Inverse na konec sbírky. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Přidá nový efekt Alpha Modulate na konec sbírky. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Přidá nový efekt Alpha Modulate Fixed na konec sbírky. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Přidá nový efekt Alpha Replace na konec sbírky. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Přidá nový efekt Bi-Level (black/white) na konec sbírky. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Přidá nový efekt Blur na konec sbírky. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Přidá nový efekt Color Change na konec sbírky. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Přidá nový efekt Color Replacement na konec sbírky. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Přidá nový efekt Duotone na konec sbírky. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Přidá nový efekt Fill Overlay na konec sbírky. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Přidá nový efekt Gray Scale na konec sbírky. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Přidá nový efekt Hue/Saturation/Luminance na konec sbírky. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Přidá nový efekt Luminance na konec sbírky. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Přidá nový efekt Tint na konec sbírky. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Přidá nový efekt BrightnessContrast na konec sbírky. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

Vrátí [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) ze sbírky podle jeho indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index položky. |

**Návratová hodnota:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) – objekt [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraní efekt obrazu ze sbírky na zadaném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index efektu obrazu, který má být smazán. |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Přidá nový efekt Alpha Bi-Level na konec sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| threshold | float | Hodnota prahu pro efekt alpha bi-level. |

**Návratová hodnota:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) – index nového efektu obrazu ve sbírce.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

Přidá nový efekt Alpha Ceiling na konec sbírky.

**Návratová hodnota:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) – index nového efektu obrazu ve sbírce.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

Přidá nový efekt Alpha Floor na konec sbírky.

**Návratová hodnota:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) – index nového efektu obrazu ve sbírce.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

Přidá nový efekt Alpha Inverse na konec sbírky.

**Návratová hodnota:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) – index nového efektu obrazu ve sbírce.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

Přidá nový efekt Alpha Modulate na konec sbírky.

**Návratová hodnota:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) – index nového efektu obrazu ve sbírce.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Přidá nový efekt Alpha Modulate Fixed na konec sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| amount | float | Procentuální hodnota pro škálování alfy. |

**Návratová hodnota:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) – index nového efektu obrazu ve sbírce.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Přidá nový efekt Alpha Replace na konec sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| alpha | float | Nová hodnota neprůhlednosti. |

**Návratová hodnota:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) – index nového efektu obrazu ve sbírce.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

Přidá nový efekt Bi-Level (black/white) na konec sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| threshold | float | Luminanční práh pro efekt Bi-Level. Hodnoty větší nebo rovné prahu jsou nastaveny na bílou, hodnoty menší než práh jsou nastaveny na černou. |

**Návratová hodnota:**
[IBiLevel](../../com.aspose.slides/ibilevel) – index nového efektu obrazu ve sbírce.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

Přidá nový efekt Blur na konec sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| radius | double | Poloměr rozostření. |
| grow | boolean | Určuje, zda mají být ohraničení objektu rozšířena v důsledku rozostření. True znamená, že ohraničení jsou rozšířena, false že ne. |

**Návratová hodnota:**
[IBlur](../../com.aspose.slides/iblur) – index nového efektu obrazu ve sbírce.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

Přidá nový efekt Color Change na konec sbírky.

**Návratová hodnota:**
[IColorChange](../../com.aspose.slides/icolorchange) – index nového efektu obrazu ve sbírce.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

Přidá nový efekt Color Replacement na konec sbírky.

**Návratová hodnota:**
[IColorReplace](../../com.aspose.slides/icolorreplace) – index nového efektu obrazu ve sbírce.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

Přidá nový efekt Duotone na konec sbírky.

**Návratová hodnota:**
[IDuotone](../../com.aspose.slides/iduotone) – index nového efektu obrazu ve sbírce.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

Přidá nový efekt Fill Overlay na konec sbírky.

**Návratová hodnota:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) – index nového efektu obrazu ve sbírce.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

Přidá nový efekt Gray Scale na konec sbírky.

**Návratová hodnota:**
[IGrayScale](../../com.aspose.slides/igrayscale) – index nového efektu obrazu ve sbírce.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Přidá nový efekt Hue/Saturation/Luminance na konec sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hue | float | Počet stupňů, o který se posune odstín. |
| saturation | float | Procento, o které se upraví sytost. |
| luminance | float | Procento, o které se upraví luminance. |

**Návratová hodnota:**
[IHSL](../../com.aspose.slides/ihsl) – index nového efektu obrazu ve sbírce.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

Přidá nový efekt Luminance na konec sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| brightness | float | Procento pro změnu jasu. |
| contrast | float | Procento pro změnu kontrastu. |

**Návratová hodnota:**
[ILuminance](../../com.aspose.slides/iluminance) – index nového efektu obrazu ve sbírce.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

Přidá nový efekt Tint na konec sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hue | float | Odstín, ke kterému se bude barva tintovat. |
| amount | float | Určuje, o kolik se posune hodnota barvy. |

**Návratová hodnota:**
[ITint](../../com.aspose.slides/itint) – index nového efektu obrazu ve sbírce.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Přidá nový efekt BrightnessContrast na konec sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| brightness | float | Procento pro změnu jasu. |
| contrast | float | Procento pro změnu kontrastu. |

**Návratová hodnota:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) – index nového efektu obrazu ve sbírce.