---
title: ImageTransformOperationCollection
second_title: Aspose.Slides Java API referenciája
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

Képhez alkalmazott effektusok gyűjteményét képviseli.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | Visszatér egy [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)-t a gyűjteményből az index szerint. |
| [removeAt(int index)](#removeAt-int-) | Eltávolít egy képeffektust a gyűjteményből a megadott indexnél. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Az új Alpha Bi-Level effektust hozzáadja a gyűjtemény végéhez. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Az új Alpha Ceiling effektust hozzáadja a gyűjtemény végéhez. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Az új Alpha Floor effektust hozzáadja a gyűjtemény végéhez. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Az új Alpha Inverse effektust hozzáadja a gyűjtemény végéhez. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Az új Alpha Modulate effektust hozzáadja a gyűjtemény végéhez. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Az új Alpha Modulate Fixed effektust hozzáadja a gyűjtemény végéhez. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Az új Alpha Replace effektust hozzáadja a gyűjtemény végéhez. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Az új Bi-Level (fekete/fehér) effektust hozzáadja a gyűjtemény végéhez. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Az új Blur effektust hozzáadja a gyűjtemény végéhez. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Az új Color Change effektust hozzáadja a gyűjtemény végéhez. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Az új Color Replacement effektust hozzáadja a gyűjtemény végéhez. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Az új Duotone effektust hozzáadja a gyűjtemény végéhez. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Az új Fill Overlay effektust hozzáadja a gyűjtemény végéhez. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Az új Gray Scale effektust hozzáadja a gyűjtemény végéhez. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Az új Hue/Saturation/Luminance effektust hozzáadja a gyűjtemény végéhez. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Az új Luminance effektust hozzáadja a gyűjtemény végéhez. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Az új Tint effektust hozzáadja a gyűjtemény végéhez. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Az új BrightnessContrast effektust hozzáadja a gyűjtemény végéhez. |
| [size()](#size--) | Visszatér a képeffektusok számával egy gyűjteményben. |
| [isReadOnly()](#isReadOnly--) | Lekér egy értéket, amely jelzi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | Az új képeffektust hozzáadja a gyűjtemény végéhez. |
| [clear()](#clear--) | Eltávolítja az összes képeffektust egy gyűjteményből. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | Átmásolja a [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy tömbbe, egy adott tömbindexnél kezdve. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | Eltávolítja az első előfordulását egy adott objektumnak a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból. |
| [iterator()](#iterator--) | Visszatér egy enumerátorral, amely végigjárja a gyűjteményt. |
| [iteratorJava()](#iteratorJava--) | Visszatér egy java iterátorral a teljes gyűjteményhez. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszaadja:**  
long

### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

Visszatér egy [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)-t a gyűjteményből az index szerint.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az elem indexe. |

**Visszaadja:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) – A [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) objektum.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolít egy képeffektust a gyűjteményből a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó képeffektus indexe. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Az új Alpha Bi-Level effektust hozzáadja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| threshold | float | Az alfa bi-level effektus küszöbértéke. |

**Visszaadja:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) – Az új képeffektus indexe a gyűjteményben.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

Az új Alpha Ceiling effektust hozzáadja a gyűjtemény végéhez.

**Visszaadja:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) – Az új képeffektus indexe a gyűjteményben.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

Az új Alpha Floor effektust hozzáadja a gyűjtemény végéhez.

**Visszaadja:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) – Az új képeffektus indexe a gyűjteményben.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

Az új Alpha Inverse effektust hozzáadja a gyűjtemény végéhez.

**Visszaadja:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) – Az új képeffektus indexe a gyűjteményben.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

Az új Alpha Modulate effektust hozzáadja a gyűjtemény végéhez.

**Visszaadja:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) – Az új képeffektus indexe a gyűjteményben.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Az új Alpha Modulate Fixed effektust hozzáadja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| amount | float | Az alfa skálázásának százalékos értéke. |

**Visszaadja:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) – Az új képeffektus indexe a gyűjteményben.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Az új Alpha Replace effektust hozzáadja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| alpha | float | Az új átlátszóság értéke. |

**Visszaadja:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) – Az új képeffektus indexe a gyűjteményben.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

Az új Bi-Level (fekete/fehér) effektust hozzáadja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| threshold | float | A luminancia küszöbérték a Bi-Level effektushoz. A küszöbnél nagyobb vagy egyenlő értékek fehérre, a kisebbek feketére lesznek állítva. |

**Visszaadja:**
[IBiLevel](../../com.aspose.slides/ibilevel) – Az új képeffektus indexe a gyűjteményben.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

Az új Blur effektust hozzáadja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| radius | double | A blur sugara. |
| grow | boolean | Megadja, hogy a homályosítás következtében nőjenek-e a objektum határolói. true esetén nőnek, false esetén nem. |

**Visszaadja:**
[IBlur](../../com.aspose.slides/iblur) – Az új képeffektus indexe a gyűjteményben.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

Az új Color Change efektust hozzáadja a gyűjtemény végéhez.

**Visszaadja:**
[IColorChange](../../com.aspose.slides/icolorchange) – Az új képeffektus indexe a gyűjteményben.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

Az új Color Replacement efektust hozzáadja a gyűjtemény végéhez.

**Visszaadja:**
[IColorReplace](../../com.aspose.slides/icolorreplace) – Az új képeffektus indexe a gyűjteményben.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

Az új Duotone efektust hozzáadja a gyűjtemény végéhez.

**Visszaadja:**
[IDuotone](../../com.aspose.slides/iduotone) – Az új képeffektus indexe a gyűjteményben.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

Az új Fill Overlay efektust hozzáadja a gyűjtemény végéhez.

**Visszaadja:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) – Az új képeffektus indexe a gyűjteményben.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

Az új Gray Scale efektust hozzáadja a gyűjtemény végéhez.

**Visszaadja:**
[IGrayScale](../../com.aspose.slides/igrayscale) – Az új képeffektus indexe a gyűjteményben.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Az új Hue/Saturation/Luminance efektust hozzáadja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hue | float | A színárnyalat beállításához használt fokok száma. |
| saturation | float | A telítettség beállításához használt százalék. |
| luminance | float | A luminancia beállításához használt százalék. |

**Visszaadja:**
[IHSL](../../com.aspose.slides/ihsl) – Az új képeffektus indexe a gyűjteményben.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

Az új Luminance efektust hozzáadja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| brightness | float | A fényerő változtatásának százalékos értéke. |
| contrast | float | A kontraszt változtatásának százalékos értéke. |

**Visszaadja:**
[ILuminance](../../com.aspose.slides/iluminance) – Az új képeffektus indexe a gyűjteményben.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

Az új Tint efektust hozzáadja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| hue | float | A színárnyalat, amely felé a tintát alkalmazzuk. |
| amount | float | Megadja, hogy mennyivel legyen eltolva a színérték. |

**Visszaadja:**
[ITint](../../com.aspose.slides/itint) – Az új képeffektus indexe a gyűjteményben.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Az új BrightnessContrast efektust hozzáadja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| brightness | float | A fényerő változtatásának százalékos értéke. |
| contrast | float | A kontraszt változtatásának százalékos értéke. |

**Visszaadja:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) – Az új képeffektus indexe a gyűjteményben.

### size() {#size--}
```
public final int size()
```

Visszatér a képeffektusok számával egy gyűjteményben. Csak olvasható int.

**Visszaadja:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Lekér egy értéket, amely jelzi, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható-e. Csak olvasható boolean.

**Visszaadja:**
boolean – true, ha a [IGenericCollection](../../com.aspose.slides/igenericcollection) csak olvasható; egyébként false.

### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

Az új képeffektust hozzáadja a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | A hozzáadandó képeffektus. |

### clear() {#clear--}
```
public final void clear()
```

Eltávolítja az összes képeffektust egy gyűjteményből.

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

Megállapítja, hogy a [IGenericCollection](../../com.aspose.slides/igenericcollection) tartalmaz-e egy adott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | A keresett objektum a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban. |

**Visszaadja:**
boolean – true, ha az elem megtalálható a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban; egyébként false.

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

Átmásolja a [IGenericCollection](../../com.aspose.slides/igenericcollection) elemeit egy tömbbe, egy adott tömbindexnél kezdve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | Az egydimenziós tömb, amely a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ből másolt elemek célja. A tömbnek nullára indexeltnek kell lennie. |
| arrayIndex | int | A nullára indexelt hely a tömbben, ahol a másolás kezdődik. |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

Eltávolítja egy adott objektum első előfordulását a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Az eltávolítandó objektum a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban. |

**Visszaadja:**
boolean – true, ha az elem sikeresen eltávolításra került a [IGenericCollection](../../com.aspose.slides/igenericcollection)-ból; egyébként false. Ez a metódus false értéket ad vissza, ha az elem nem található az eredeti [IGenericCollection](../../com.aspose.slides/igenericcollection)-ban.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

Visszatér egy enumerátorral, amely végigjárja a gyűjteményt.

**Visszaadja:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> – Egy IGenericEnumerator, amely a gyűjtemény bejárására használható.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

Visszatér egy java iterátorral a teljes gyűjteményhez.

**Visszaadja:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> – Egy java.util.Iterator a teljes gyűjteményhez.