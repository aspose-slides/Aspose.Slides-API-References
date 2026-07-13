---
title: ImageTransformOperationCollection
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje kolekcję efektów zastosowanych do obrazu.
type: docs
url: /pl/com.aspose.slides/imagetransformoperationcollection/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

Reprezentuje kolekcję efektów zastosowanych do obrazu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | Zwraca [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) z kolekcji według jego indeksu. |
| [removeAt(int index)](#removeAt-int-) | Usuwa efekt obrazu z kolekcji podanym indeksem. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Dodaje nowy efekt Alpha Bi-Level na koniec kolekcji. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Dodaje nowy efekt Alpha Ceiling na koniec kolekcji. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Dodaje nowy efekt Alpha Floor na koniec kolekcji. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Dodaje nowy efekt Alpha Inverse na koniec kolekcji. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Dodaje nowy efekt Alpha Modulate na koniec kolekcji. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Dodaje nowy efekt Alpha Modulate Fixed na koniec kolekcji. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Dodaje nowy efekt Alpha Replace na koniec kolekcji. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Dodaje nowy efekt Bi-Level (czarno-biały) na koniec kolekcji. |
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
| [size()](#size--) | Zwraca liczbę efektów obrazu w kolekcji. |
| [isReadOnly()](#isReadOnly--) | Pobiera wartość wskazującą, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) jest tylko do odczytu. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | Dodaje nowy efekt obrazu na koniec kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie efekty obrazu z kolekcji. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | Kopiuje elementy [IGenericCollection](../../com.aspose.slides/igenericcollection) do Array, zaczynając od określonego indeksu Array. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | Usuwa pierwsze wystąpienie określonego obiektu z [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |

### getVersion() {#getVersion--}
```
public long getVersion()
```


Wersja. Tylko do odczytu, typ long.

**Zwraca:**
long
### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```


Zwraca [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) z kolekcji według jego indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks elementu. |

**Zwraca:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - Obiekt [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Usuwa efekt obrazu z kolekcji podanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks efektu obrazu, który ma zostać usunięty. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
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
public final IAlphaCeiling addAlphaCeilingEffect()
```


Dodaje nowy efekt Alpha Ceiling na koniec kolekcji.

**Zwraca:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Indeks nowego efektu obrazu w kolekcji.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```


Dodaje nowy efekt Alpha Floor na koniec kolekcji.

**Zwraca:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Indeks nowego efektu obrazu w kolekcji.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```


Dodaje nowy efekt Alpha Inverse na koniec kolekcji.

**Zwraca:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Indeks nowego efektu obrazu w kolekcji.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```


Dodaje nowy efekt Alpha Modulate na koniec kolekcji.

**Zwraca:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Indeks nowego efektu obrazu w kolekcji.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```


Dodaje nowy efekt Alpha Modulate Fixed na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| amount | float | Procentowa wartość skalująca alfa. |

**Zwraca:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Indeks nowego efektu obrazu w kolekcji.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```


Dodaje nowy efekt Alpha Replace na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| alpha | float | Nowa wartość nieprzezroczystości. |

**Zwraca:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Indeks nowego efektu obrazu w kolekcji.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```


Dodaje nowy efekt Bi-Level (czarno-biały) na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| threshold | float | Wartość progowa luminancji dla efektu Bi-Level. Wartości większe lub równe progowi są ustawiane na biały. Wartości mniejsze od progu są ustawiane na czarny. |

**Zwraca:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Indeks nowego efektu obrazu w kolekcji.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```


Dodaje nowy efekt Blur na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| radius | double | Promień rozmycia. |
| grow | boolean | Określa, czy granice obiektu powinny być powiększane w wyniku rozmycia. True oznacza, że granice są powiększane, false że nie. |

**Zwraca:**
[IBlur](../../com.aspose.slides/iblur) - Indeks nowego efektu obrazu w kolekcji.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```


Dodaje nowy efekt Color Change na koniec kolekcji.

**Zwraca:**
[IColorChange](../../com.aspose.slides/icolorchange) - Indeks nowego efektu obrazu w kolekcji.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```


Dodaje nowy efekt Color Replacement na koniec kolekcji.

**Zwraca:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Indeks nowego efektu obrazu w kolekcji.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```


Dodaje nowy efekt Duotone na koniec kolekcji.

**Zwraca:**
[IDuotone](../../com.aspose.slides/iduotone) - Indeks nowego efektu obrazu w kolekcji.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```


Dodaje nowy efekt Fill Overlay na koniec kolekcji.

**Zwraca:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Indeks nowego efektu obrazu w kolekcji.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```


Dodaje nowy efekt Gray Scale na koniec kolekcji.

**Zwraca:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Indeks nowego efektu obrazu w kolekcji.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```


Dodaje nowy efekt Hue/Saturation/Luminance na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| hue | float | Liczba stopni, o którą zmieniany jest hue. |
| saturation | float | Procent, o który zmieniana jest saturacja. |
| luminance | float | Procent, o który zmieniana jest luminancja. |

**Zwraca:**
[IHSL](../../com.aspose.slides/ihsl) - Indeks nowego efektu obrazu w kolekcji.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
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
public final ITint addTintEffect(float hue, float amount)
```


Dodaje nowy efekt Tint na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| hue | float | Hue, w którym ma być wykonane tintowanie. |
| amount | float | Określa, o ile wartość koloru jest przesunięta. |

**Zwraca:**
[ITint](../../com.aspose.slides/itint) - Indeks nowego efektu obrazu w kolekcji.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```


Dodaje nowy efekt BrightnessContrast na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| brightness | float | Procent zmiany jasności. |
| contrast | float | Procent zmiany kontrastu. |

**Zwraca:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Indeks nowego efektu obrazu w kolekcji.
### size() {#size--}
```
public final int size()
```


Zwraca liczbę efektów obrazu w kolekcji. Tylko do odczytu, typ int.

**Zwraca:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Pobiera wartość wskazującą, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) jest tylko do odczytu. Tylko do odczytu, typ boolean.

**Zwraca:**
boolean - prawda, jeśli [IGenericCollection](../../com.aspose.slides/igenericcollection) jest tylko do odczytu; w przeciwnym razie fałsz.
### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```


Dodaje nowy efekt obrazu na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Efekt obrazu do dodania na koniec kolekcji. |

### clear() {#clear--}
```
public final void clear()
```


Usuwa wszystkie efekty obrazu z kolekcji.

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```


Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Obiekt do znalezienia w [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Zwraca:**
boolean - prawda, jeśli element został znaleziony w [IGenericCollection](../../com.aspose.slides/igenericcollection); w przeciwnym razie fałsz.

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```


Kopiuje elementy [IGenericCollection](../../com.aspose.slides/igenericcollection) do Array, zaczynając od określonego indeksu Array.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | Jednowymiarowa tablica będąca miejscem docelowym elementów kopiowanych z [IGenericCollection](../../com.aspose.slides/igenericcollection). Tablica musi mieć indeksowanie od zera. |
| arrayIndex | int | Indeks zerowy w tablicy, od którego rozpoczyna się kopiowanie. |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```


Usuwa pierwsze wystąpienie określonego obiektu z [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Obiekt do usunięcia z [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Zwraca:**
boolean - prawda, jeśli  item  został pomyślnie usunięty z [IGenericCollection](../../com.aspose.slides/igenericcollection); w przeciwnym razie fałsz. Ta metoda również zwraca fałsz, jeśli element nie został znaleziony w pierwotnym [IGenericCollection](../../com.aspose.slides/igenericcollection).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```


Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - IGenericEnumerator, który może być użyty do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```


Zwraca iterator java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - java.util.Iterator dla całej kolekcji.