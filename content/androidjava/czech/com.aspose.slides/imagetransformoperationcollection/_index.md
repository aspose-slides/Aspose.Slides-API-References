---
title: ImageTransformOperationCollection
second_title: Aspose.Slides pro Android skrze Java API Reference
description: Představuje kolekci efektů aplikovaných na obrázek.
type: docs
url: /cs/com.aspose.slides/imagetransformoperationcollection/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

Představuje kolekci efektů aplikovaných na obrázek.
## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | Vrací [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) ze sbírky podle jeho indexu. |
| [removeAt(int index)](#removeAt-int-) | Odstraňuje efekt obrázku ze sbírky na zadaném indexu. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Přidá nový efekt Alpha Bi-Level na konec sbírky. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Přidá nový efekt Alpha Ceiling na konec sbírky. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Přidá nový efekt Alpha Floor na konec sbírky. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Přidá nový efekt Alpha Inverse na konec sbírky. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Přidá nový efekt Alpha Modulate na konec sbírky. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Přidá nový efekt Alpha Modulate Fixed na konec sbírky. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Přidá nový efekt Alpha Replace na konec sbírky. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Přidá nový efekt Bi-Level (černobílý) na konec sbírky. |
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
| [size()](#size--) | Vrací počet efektů obrázku ve sbírce. |
| [isReadOnly()](#isReadOnly--) | Získá hodnotu určující, zda je [IGenericCollection](../../com.aspose.slides/igenericcollection) jen pro čtení. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | Přidá nový efekt obrázku na konec sbírky. |
| [clear()](#clear--) | Odstraní všechny efekty obrázku ze sbírky. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | Zkopíruje prvky [IGenericCollection](../../com.aspose.slides/igenericcollection) do pole Array, počínaje konkrétním indexem pole. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | Odstraní první výskyt konkrétního objektu z [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze pro čtení, typ long.

**Vrací:**
long

### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

Vrací [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) ze sbírky podle jeho indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index prvku. |

**Vrací:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - Objekt [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odstraňuje efekt obrázku ze sbírky na určeném indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index efektu obrázku, který má být smazán. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Přidá nový efekt Alpha Bi-Level na konec sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| threshold | float | Hodnota prahu pro alpha bi-level efekt. |

**Vrací:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Index nového efektu obrázku ve sbírce.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

Přidá nový efekt Alpha Ceiling na konec sbírky.

**Vrací:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Index nového efektu obrázku ve sbírce.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

Přidá nový efekt Alpha Floor na konec sbírky.

**Vrací:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Index nového efektu obrázku ve sbírce.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

Přidá nový efekt Alpha Inverse na konec sbírky.

**Vrací:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Index nového efektu obrázku ve sbírce.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

Přidá nový efekt Alpha Modulate na konec sbírky.

**Vrací:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Index nového efektu obrázku ve sbírce.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Přidá nový efekt Alpha Modulate Fixed na konec sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| amount | float | Procentní hodnota pro škálování alfy. |

**Vrací:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Index nového efektu obrázku ve sbírce.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Přidá nový efekt Alpha Replace na konec sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| alpha | float | Nová hodnota neprůhlednosti. |

**Vrací:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Index nového efektu obrázku ve sbírce.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

Přidá nový efekt Bi-Level (černobílý) na konec sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| threshold | float | Luminanční práh pro efekt Bi-Level. Hodnoty větší nebo rovné prahu jsou nastaveny na bílou. Hodnoty menší než práh jsou nastaveny na černou. |

**Vrací:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Index nového efektu obrázku ve sbírce.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

Přidá nový efekt Blur na konec sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| radius | double | Poloměr rozostření. |
| grow | boolean | Určuje, zda mají být ohraničení objektu rozšířena v důsledku rozostření. True označuje, že ohraničení jsou rozšířena, zatímco false označuje, že ne. |

**Vrací:**
[IBlur](../../com.aspose.slides/iblur) - Index nového efektu obrázku ve sbírce.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

Přidá nový efekt Color Change na konec sbírky.

**Vrací:**
[IColorChange](../../com.aspose.slides/icolorchange) - Index nového efektu obrázku ve sbírce.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

Přidá nový efekt Color Replacement na konec sbírky.

**Vrací:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Index nového efektu obrázku ve sbírce.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

Přidá nový efekt Duotone na konec sbírky.

**Vrací:**
[IDuotone](../../com.aspose.slides/iduotone) - Index nového efektu obrázku ve sbírce.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

Přidá nový efekt Fill Overlay na konec sbírky.

**Vrací:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Index nového efektu obrázku ve sbírce.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

Přidá nový efekt Gray Scale na konec sbírky.

**Vrací:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Index nového efektu obrázku ve sbírce.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Přidá nový efekt Hue/Saturation/Luminance na konec sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hue | float | Počet stupňů, o které je odstín upraven. |
| saturation | float | Procentuální hodnota úpravy saturation. |
| luminance | float | Procentuální hodnota úpravy luminance. |

**Vrací:**
[IHSL](../../com.aspose.slides/ihsl) - Index nového efektu obrázku ve sbírce.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

Přidá nový efekt Luminance na konec sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| brightness | float | Procento pro změnu jasu. |
| contrast | float | Procento pro změnu kontrastu. |

**Vrací:**
[ILuminance](../../com.aspose.slides/iluminance) - Index nového efektu obrázku ve sbírce.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

Přidá nový efekt Tint na konec sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| hue | float | Odstín, ke kterému se má aplikovat tónování. |
| amount | float | Určuje, o kolik je hodnota barvy posunuta. |

**Vrací:**
[ITint](../../com.aspose.slides/itint) - Index nového efektu obrázku ve sbírce.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Přidá nový efekt BrightnessContrast na konec sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| brightness | float | Procento pro změnu jasu. |
| contrast | float | Procento pro změnu kontrastu. |

**Vrací:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Index nového efektu obrázku ve sbírce.

### size() {#size--}
```
public final int size()
```

Vrací počet efektů obrázku ve sbírce. Pouze pro čtení, typ int.

**Vrací:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Získá hodnotu určující, zda je [IGenericCollection](../../com.aspose.slides/igenericcollection) jen pro čtení. Pouze pro čtení, typ boolean.

**Vrací:**
boolean - true pokud je [IGenericCollection](../../com.aspose.slides/igenericcollection) jen pro čtení; jinak false.

### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

Přidá nový efekt obrázku na konec sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Efekt obrázku, který se má přidat na konec sbírky. |

### clear() {#clear--}
```
public final void clear()
```

Odstraní všechny efekty obrázku ze sbírky.

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

Určuje, zda [IGenericCollection](../../com.aspose.slides/igenericcollection) obsahuje konkrétní hodnotu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Objekt, který má být vyhledán v [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Vrací:**
boolean - true pokud je položka nalezena v [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false.

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

Zkopíruje prvky [IGenericCollection](../../com.aspose.slides/igenericcollection) do pole Array, počínaje konkrétním indexem pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | Jednorozměrné pole, které je cílem pro prvky zkopírované z [IGenericCollection](../../com.aspose.slides/igenericcollection). Pole musí mít nulové indexování. |
| arrayIndex | int | Nulový index v poli, od kterého začíná kopírování. |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

Odstraní první výskyt konkrétního objektu z [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | Objekt, který má být odstraněn z [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Vrací:**
boolean - true pokud byl objekt  item  úspěšně odstraněn z [IGenericCollection](../../com.aspose.slides/igenericcollection); jinak false. Tato metoda také vrací false, pokud objekt není nalezen v původním [IGenericCollection](../../com.aspose.slides/igenericcollection).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - IGenericEnumerator, který lze použít k iteraci přes kolekci.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - java.util.Iterator pro celou kolekci.