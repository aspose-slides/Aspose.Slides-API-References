---
title: IImageTransformOperationCollection
second_title: Aspose.Slides dla Androida – dokumentacja API Java
description: Reprezentuje kolekcję efektów zastosowanych do obrazu.
type: docs
url: /pl/com.aspose.slides/iimagetransformoperationcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

Represents a collection of effects apllied to an image.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) z kolekcji według jego indeksu. |
| [removeAt(int index)](#removeAt-int-) | Usuwa efekt obrazu z kolekcji pod podanym indeksem. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Dodaje nowy efekt Alpha Bi-Level na koniec kolekcji. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Dodaje nowy efekt Alpha Ceiling na koniec kolekcji. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Dodaje nowy efekt Alpha Floor na koniec kolekcji. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Dodaje nowy efekt Alpha Inverse na koniec kolekcji. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Dodaje nowy efekt Alpha Modulate na koniec kolekcji. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Dodaje nowy efekt Alpha Modulate Fixed na koniec kolekcji. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Dodaje nowy efekt Alpha Replace na koniec kolekcji. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Dodaje nowy efekt Bi-Level (black/white) na koniec kolekcji. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Dodaje nowy efekt Blur na koniec kolekcji. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Dodaje nowy efekt Color Change na koniec kolekcji. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Dodaje nowy efekt Color Replacement na koniec kolekcji. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Dodaje nowy efekt Duotone na koniec kolekcji. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Dodaje nowy efekt Fill Overlay na koniec kolekcji. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Dodaje nowy efekt Gray Scale na koniec kolekcji. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Dodaje nowy efekt Hue/Saturation/Luminance na koniec kolekcji. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Dodaje nowy efekt Luminance na koniec kolekcji. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Dodaje nowy efekt Tint na koniec kolekcji. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Dodaje nowy efekt BrightnessContrast na koniec kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

Zwraca [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) z kolekcji według jego indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks elementu. |

**Zwraca:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - Obiekt [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa efekt obrazu z kolekcji pod podanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks efektu obrazu, który ma zostać usunięty. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Dodaje nowy efekt Alpha Bi-Level na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| threshold | float | Wartość progowa dla efektu alpha bi-level. |

**Zwraca:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Indeks nowego efektu obrazu w kolekcji.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

Dodaje nowy efekt Alpha Ceiling na koniec kolekcji.

**Zwraca:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Indeks nowego efektu obrazu w kolekcji.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

Dodaje nowy efekt Alpha Floor na koniec kolekcji.

**Zwraca:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Indeks nowego efektu obrazu w kolekcji.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

Dodaje nowy efekt Alpha Inverse na koniec kolekcji.

**Zwraca:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Indeks nowego efektu obrazu w kolekcji.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

Dodaje nowy efekt Alpha Modulate na koniec kolekcji.

**Zwraca:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Indeks nowego efektu obrazu w kolekcji.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Dodaje nowy efekt Alpha Modulate Fixed na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| amount | float | Procentowa wartość skalowania alfa. |

**Zwraca:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Indeks nowego efektu obrazu w kolekcji.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Dodaje nowy efekt Alpha Replace na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| alpha | float | Nowa wartość przezroczystości. |

**Zwraca:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Indeks nowego efektu obrazu w kolekcji.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

Dodaje nowy efekt Bi-Level (black/white) na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| threshold | float | Próg luminancji dla efektu Bi-Level. Wartości większe lub równe progowi są ustawiane na biały. Wartości mniejsze od progu są ustawiane na czarny. |

**Zwraca:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Indeks nowego efektu obrazu w kolekcji.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

Dodaje nowy efekt Blur na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| radius | double | Promień rozmycia. |
| grow | boolean | Określa, czy granice obiektu mają być powiększone w wyniku rozmycia. True oznacza, że granice są powiększane, false – że nie są. |

**Zwraca:**
[IBlur](../../com.aspose.slides/iblur) - Indeks nowego efektu obrazu w kolekcji.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

Dodaje nowy efekt Color Change na koniec kolekcji.

**Zwraca:**
[IColorChange](../../com.aspose.slides/icolorchange) - Indeks nowego efektu obrazu w kolekcji.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

Dodaje nowy efekt Color Replacement na koniec kolekcji.

**Zwraca:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Indeks nowego efektu obrazu w kolekcji.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

Dodaje nowy efekt Duotone na koniec kolekcji.

**Zwraca:**
[IDuotone](../../com.aspose.slides/iduotone) - Indeks nowego efektu obrazu w kolekcji.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

Dodaje nowy efekt Fill Overlay na koniec kolekcji.

**Zwraca:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Indeks nowego efektu obrazu w kolekcji.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

Dodaje nowy efekt Gray Scale na koniec kolekcji.

**Zwraca:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Indeks nowego efektu obrazu w kolekcji.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Dodaje nowy efekt Hue/Saturation/Luminance na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| hue | float | Liczba stopni, o które zmieniany jest odcień. |
| saturation | float | Procent, o który zmieniana jest saturacja. |
| luminance | float | Procent, o który zmieniana jest luminancja. |

**Zwraca:**
[IHSL](../../com.aspose.slides/ihsl) - Indeks nowego efektu obrazu w kolekcji.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

Dodaje nowy efekt Luminance na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| brightness | float | Procent zmiany jasności. |
| contrast | float | Procent zmiany kontrastu. |

**Zwraca:**
[ILuminance](../../com.aspose.slides/iluminance) - Indeks nowego efektu obrazu w kolekcji.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

Dodaje nowy efekt Tint na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| hue | float | Odcień, w którym ma być wykonane przyciemnienie. |
| amount | float | Określa, o ile wartość koloru jest przesunięta. |

**Zwraca:**
[ITint](../../com.aspose.slides/itint) - Indeks nowego efektu obrazu w kolekcji.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Dodaje nowy efekt BrightnessContrast na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| brightness | float | Procent zmiany jasności. |
| contrast | float | Procent zmiany kontrastu. |

**Zwraca:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Indeks nowego efektu obrazu w kolekcji.