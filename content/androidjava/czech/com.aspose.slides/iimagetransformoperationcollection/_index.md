---
title: IImageTransformOperationCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje kolekci efektů aplikovaných na obrázek.
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
| [get_Item(int index)](#get-Item-int-) | Vrací [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) z kolekce podle jeho indexu. |
| [removeAt(int index)](#removeAt-int-) | Odstraní efekt obrázku z kolekce na uvedeném indexu. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Přidá nový efekt Alpha Bi-Level na konec kolekce. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Přidá nový efekt Alpha Ceiling na konec kolekce. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Přidá nový efekt Alpha Floor na konec kolekce. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Přidá nový efekt Alpha Inverse na konec kolekce. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Přidá nový efekt Alpha Modulate na konec kolekce. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Přidá nový efekt Alpha Modulate Fixed na konec kolekce. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Přidá nový efekt Alpha Replace na konec kolekce. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Přidá nový efekt Bi-Level (černobílý) na konec kolekce. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Přidá nový efekt Blur na konec kolekce. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Přidá nový efekt Color Change na konec kolekce. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Přidá nový efekt Color Replacement na konec kolekce. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Přidá nový efekt Duotone na konec kolekce. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Přidá nový efekt Fill Overlay na konec kolekce. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Přidá nový efekt Gray Scale na konec kolekce. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Přidá nový efekt Hue/Saturation/Luminance na konec kolekce. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Přidá nový efekt Luminance na konec kolekce. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Přidá nový efekt Tint na konec kolekce. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Přidá nový efekt BrightnessContrast na konec kolekce. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

Vrací [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) z kolekce podle jeho indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index položky. |

**Návratová hodnota:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - Objekt [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraní efekt obrázku z kolekce na uvedeném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index efektu obrázku, který má být smazán. |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Přidá nový efekt Alpha Bi-Level na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| threshold | float | Hodnota prahu pro efekt alpha bi-level. |

**Návratová hodnota:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Index nového efektu obrázku v kolekci.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

Přidá nový efekt Alpha Ceiling na konec kolekce.

**Návratová hodnota:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Index nového efektu obrázku v kolekci.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

Přidá nový efekt Alpha Floor na konec kolekce.

**Návratová hodnota:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Index nového efektu obrázku v kolekci.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

Přidá nový efekt Alpha Inverse na konec kolekce.

**Návratová hodnota:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Index nového efektu obrázku v kolekci.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

Přidá nový efekt Alpha Modulate na konec kolekce.

**Návratová hodnota:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Index nového efektu obrázku v kolekci.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Přidá nový efekt Alpha Modulate Fixed na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| amount | float | Procentuální hodnota pro škálování alfy. |

**Návratová hodnota:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Index nového efektu obrázku v kolekci.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Přidá nový efekt Alpha Replace na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| alpha | float | Nová hodnota neprůhlednosti. |

**Návratová hodnota:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Index nového efektu obrázku v kolekci.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

Přidá nový efekt Bi-Level (černobílý) na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| threshold | float | Luminanční práh pro efekt Bi-Level. Hodnoty větší nebo rovné prahu jsou nastaveny na bílou. Hodnoty menší než práh jsou nastaveny na černou. |

**Návratová hodnota:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Index nového efektu obrázku v kolekci.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

Přidá nový efekt Blur na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| radius | double | Poloměr rozostření. |
| grow | boolean | Určuje, zda mají být hranice objektu rozšířeny v důsledku rozostření. True označuje, že jsou hranice rozšířeny, zatímco false označuje, že nejsou. |

**Návratová hodnota:**
[IBlur](../../com.aspose.slides/iblur) - Index nového efektu obrázku v kolekci.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

Přidá nový efekt Color Change na konec kolekce.

**Návratová hodnota:**
[IColorChange](../../com.aspose.slides/icolorchange) - Index nového efektu obrázku v kolekci.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

Přidá nový efekt Color Replacement na konec kolekce.

**Návratová hodnota:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Index nového efektu obrázku v kolekci.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

Přidá nový efekt Duotone na konec kolekce.

**Návratová hodnota:**
[IDuotone](../../com.aspose.slides/iduotone) - Index nového efektu obrázku v kolekci.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

Přidá nový efekt Fill Overlay na konec kolekce.

**Návratová hodnota:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Index nového efektu obrázku v kolekci.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

Přidá nový efekt Gray Scale na konec kolekce.

**Návratová hodnota:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Index nového efektu obrázku v kolekci.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Přidá nový efekt Hue/Saturation/Luminance na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hue | float | Počet stupňů, o které se upravuje odstín. |
| saturation | float | Procento, o které se upravuje sytost. |
| luminance | float | Procento, o které se upravuje luminance. |

**Návratová hodnota:**
[IHSL](../../com.aspose.slides/ihsl) - Index nového efektu obrázku v kolekci.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

Přidá nový efekt Luminance na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| brightness | float | Procento změny jasu. |
| contrast | float | Procento změny kontrastu. |

**Návratová hodnota:**
[ILuminance](../../com.aspose.slides/iluminance) - Index nového efektu obrázku v kolekci.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

Přidá nový efekt Tint na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hue | float | Odstín, na který se má aplikovat tónování. |
| amount | float | Určuje, o kolik se hodnota barvy posune. |

**Návratová hodnota:**
[ITint](../../com.aspose.slides/itint) - Index nového efektu obrázku v kolekci.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Přidá nový efekt BrightnessContrast na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| brightness | float | Procento změny jasu. |
| contrast | float | Procento změny kontrastu. |

**Návratová hodnota:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Index nového efektu obrázku v kolekci.