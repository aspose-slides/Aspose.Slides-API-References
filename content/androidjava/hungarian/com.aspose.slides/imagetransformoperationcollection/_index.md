---
title: ImageTransformOperationCollection
second_title: Aspose.Slides Android számára Java API Referencia
description: Képhez alkalmazott effektusok gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/imagetransformoperationcollection/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

Egy képre alkalmazott effektusok gyűjteményét képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | Visszaad egy [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)-t a gyűjteményből a megadott index alapján. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy kép-effektust a gyűjteményből a megadott indexnél. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Hozzáadja az új Alpha Bi-Level effektust a gyűjtemény végéhez. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Hozzáadja az új Alpha Ceiling effektust a gyűjtemény végéhez. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Hozzáadja az új Alpha Floor effektust a gyűjtemény végéhez. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Hozzáadja az új Alpha Inverse efektust a gyűjtemény végéhez. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Hozzáadja az új Alpha Modulate efektust a gyűjtemény végéhez. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Hozzáadja az új Alpha Modulate Fixed efektust a gyűjtemény végéhez. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Hozzáadja az új Alpha Replace efektust a gyűjtemény végéhez. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Hozzáadja az új Bi-Level (fekete/fehér) efektust a gyűjtemény végéhez. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Hozzáadja az új Blur efektust a gyűjtemény végéhez. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Hozzáadja az új Color Change efektust a gyűjtemény végéhez. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Hozzáadja az új Color Replacement efektust a gyűjtemény végéhez. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Hozzáadja az új Duotone efektust a gyűjtemény végéhez. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Hozzáadja az új Fill Overlay efektust a gyűjtemény végéhez. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Hozzáadja az új Gray Scale efektust a gyűjtemény végéhez. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Hozzáadja az új Hue/Saturation/Luminance efektust a gyűjtemény végéhez. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Hozzáadja az új Luminance efektust a gyűjtemény végéhez. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Hozzáadja az új Tint efektust a gyűjtemény végéhez. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Hozzáadja az új BrightnessContrast efektust a gyűjtemény végéhez. |
| [size()](#size--) | Visszaadja a kép-effektusok számát a gyűjteményben. |
| [isReadOnly()](#isReadOnly--) | Lekérdezi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | Hozzáadja az új kép-effektust a gyűjtemény végéhez. |
| [clear()](#clear--) | Eltávolítja az összes kép-effektust a gyűjteményből. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | Meghatározza, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | Átmásolja a(z) [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy Array-ba, egy adott Array indexnél kezdve. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | Eltávolítja az első előfordulását egy adott objektusnak a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ben. |
| [iterator()](#iterator--) | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [iteratorJava()](#iteratorJava--) | Visszaad egy java enumerátort az egész gyűjteményhez. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Verzió. Csak olvasható long.

**Returns:**
long
### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```


Visszaad egy [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)-t a gyűjteményből a megadott index alapján.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe. |

**Returns:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - A [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) objektum.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Eltávolít egy kép-effektust a gyűjteményből a megadott indexnél.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó kép-effektus indexe. |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```


Hozzáadja az új Alpha Bi-Level efektust a gyűjtemény végéhez.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| threshold | float | Az alfa bi-level effektus küszöbértéke. |

**Returns:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Az új kép-effektus indexe a gyűjteményben.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```


Hozzáadja az új Alpha Ceiling efektust a gyűjtemény végéhez.

**Returns:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Az új kép-effektus indexe a gyűjteményben.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```


Hozzáadja az új Alpha Floor efektust a gyűjtemény végéhez.

**Returns:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Az új kép-effektus indexe a gyűjteményben.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```


Hozzáadja az új Alpha Inverse efektust a gyűjtemény végéhez.

**Returns:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Az új kép-effektus indexe a gyűjteményben.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```


Hozzáadja az új Alpha Modulate efektust a gyűjtemény végéhez.

**Returns:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Az új kép-effektus indexe a gyűjteményben.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```


Hozzáadja az új Alpha Modulate Fixed efektust a gyűjtemény végéhez.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| amount | float | Az alfa skálázásának százalékos értéke. |

**Returns:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Az új kép-effektus indexe a gyűjteményben.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```


Hozzáadja az új Alpha Replace efektust a gyűjtemény végéhez.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| alpha | float | Az új átlátszósági érték. |

**Returns:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Az új kép-effektus indexe a gyűjteményben.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```


Hozzáadja az új Bi-Level (fekete/fehér) efektust a gyűjtemény végéhez.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| threshold | float | A luminancia küszöbérték a Bi-Level effektushoz. A küszöbnél nagyobb vagy egyenlő értékek fehérek, a kisebbek feketék. |

**Returns:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Az új kép-effektus indexe a gyűjteményben.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```


Hozzáadja az új Blur efektust a gyűjtemény végéhez.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| radius | double | A blur sugara. |
| grow | boolean | Megadja, hogy a blur miatt növekedjen-e az objektum határa. Az igaz érték növeli, a hamis nem. |

**Returns:**
[IBlur](../../com.aspose.slides/iblur) - Az új kép-effektus indexe a gyűjteményben.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```


Hozzáadja az új Color Change efektust a gyűjtemény végéhez.

**Returns:**
[IColorChange](../../com.aspose.slides/icolorchange) - Az új kép-effektus indexe a gyűjteményben.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```


Hozzáadja az új Color Replacement efektust a gyűjtemény végéhez.

**Returns:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Az új kép-effektus indexe a gyűjteményben.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```


Hozzáadja az új Duotone efektust a gyűjtemény végéhez.

**Returns:**
[IDuotone](../../com.aspose.slides/iduotone) - Az új kép-effektus indexe a gyűjteményben.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```


Hozzáadja az új Fill Overlay efektust a gyűjtemény végéhez.

**Returns:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Az új kép-effektus indexe a gyűjteményben.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```


Hozzáadja az új Gray Scale efektust a gyűjtemény végéhez.

**Returns:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Az új kép-effektus indexe a gyűjteményben.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```


Hozzáadja az új Hue/Saturation/Luminance efektust a gyűjtemény végéhez.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hue | float | A színárnyalat eltolásának fokszáma. |
| saturation | float | A telítettség eltolásának százalékos értéke. |
| luminance | float | A luminancia eltolásának százalékos értéke. |

**Returns:**
[IHSL](../../com.aspose.slides/ihsl) - Az új kép-effektus indexe a gyűjteményben.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```


Hozzáadja az új Luminance efektust a gyűjtemény végéhez.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| brightness | float | A fényerő változtatásának százalékos értéke. |
| contrast | float | A kontraszt változtatásának százalékos értéke. |

**Returns:**
[ILuminance](../../com.aspose.slides/iluminance) - Az új kép-effektus indexe a gyűjteményben.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```


Hozzáadja az új Tint efektust a gyűjtemény végéhez.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hue | float | A színárnyalat, amely felé a tónus módosul. |
| amount | float | Megadja, mennyivel változik a színérték. |

**Returns:**
[ITint](../../com.aspose.slides/itint) - Az új kép-effektus indexe a gyűjteményben.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```


Hozzáadja az új BrightnessContrast efektust a gyűjtemény végéhez.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| brightness | float | A fényerő változtatásának százalékos értéke. |
| contrast | float | A kontraszt változtatásának százalékos értéke. |

**Returns:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Az új kép-effektus indexe a gyűjteményben.
### size() {#size--}
```
public final int size()
```


Visszaadja a kép-effektusok számát egy gyűjteményben. Csak olvasható int.

**Returns:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Lekérdezi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. Csak olvasható boolean.

**Returns:**
boolean - igaz, ha a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható; egyébként hamis.
### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```


Hozzáadja az új kép-effektust a gyűjtemény végéhez.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | A hozzáadandó kép-effektus. |
### clear() {#clear--}
```
public final void clear()
```


Eltávolítja az összes kép-effektust a gyűjteményből.
### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```


Meghatározza, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | A keresett objektum a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban. |

**Returns:**
boolean - igaz, ha az elem megtalálható a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban; egyébként hamis.
### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```


Átmásolja a(z) [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy Array-ba, egy adott Array indexnél kezdve.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | Az egydimenziós Array, amely a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból másolt elemek célja. Az Array nullától induló indexelésű. |
| arrayIndex | int | A nullától induló index, amelynél a másolás kezdődik. |
### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```


Eltávolítja az első előfordulását egy adott objektusnak a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ben.

**Parameters:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Az eltávolítandó objektum a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban. |

**Returns:**
boolean - igaz, ha az objektum sikeresen eltávolításra került a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból; egyébként hamis. Ez a metódus hamis értéket ad vissza, ha az objektum nem található az eredeti [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```


Visszaad egy enumerátort, amely végigiterál a gyűjteményen.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - Egy IGenericEnumerator, amely a gyűjteményen való iteráláshoz használható.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```


Visszaad egy java enumerátort az egész gyűjteményhez.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - Egy java.util.Iterator az egész gyűjteményhez.