---
title: ImageTransformOperationCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una collezione di effetti applicati a un'immagine.
type: docs
url: /it/com.aspose.slides/imagetransformoperationcollection/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

Rappresenta una raccolta di effetti applicati a un'immagine.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | Restituisce un [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) dalla collezione per il suo indice. |
| [removeAt(int index)](#removeAt-int-) | Rimuove un effetto immagine dalla collezione all'indice specificato. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Aggiunge il nuovo effetto Alpha Bi-Level alla fine di una collezione. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Aggiunge il nuovo effetto Alpha Ceiling alla fine di una collezione. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Aggiunge il nuovo effetto Alpha Floor alla fine di una collezione. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Aggiunge il nuovo effetto Alpha Inverse alla fine di una collezione. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Aggiunge il nuovo effetto Alpha Modulate alla fine di una collezione. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Aggiunge il nuovo effetto Alpha Modulate Fixed alla fine di una collezione. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Aggiunge il nuovo effetto Alpha Replace alla fine di una collezione. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Aggiunge il nuovo effetto Bi-Level (bianco/nero) alla fine di una collezione. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Aggiunge il nuovo effetto Blur alla fine di una collezione. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Aggiunge il nuovo effetto Color Change alla fine di una collezione. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Aggiunge il nuovo effetto Color Replacement alla fine di una collezione. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Aggiunge il nuovo effetto Duotone alla fine di una collezione. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Aggiunge il nuovo effetto Fill Overlay alla fine di una collezione. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Aggiunge il nuovo effetto Gray Scale alla fine di una collezione. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Aggiunge il nuovo effetto Hue/Saturation/Luminance alla fine di una collezione. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Aggiunge il nuovo effetto Luminance alla fine di una collezione. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Aggiunge il nuovo effetto Tint alla fine di una collezione. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Aggiunge il nuovo effetto BrightnessContrast alla fine di una collezione. |
| [size()](#size--) | Restituisce il numero di effetti immagine in una collezione. |
| [isReadOnly()](#isReadOnly--) | Ottiene un valore che indica se [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | Aggiunge il nuovo effetto immagine alla fine di una collezione. |
| [clear()](#clear--) | Rimuove tutti gli effetti immagine da una collezione. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | Determina se [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | Rimuove la prima occorrenza di un oggetto specifico dal [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versione. Long di sola lettura.

**Restituisce:**
long

### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

Restituisce un [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) dalla collezione per il suo indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'elemento. |

**Restituisce:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - L'oggetto [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove un effetto immagine da una collezione all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di un effetto immagine da eliminare. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Aggiunge il nuovo effetto Alpha Bi-Level alla fine di una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | float | Il valore di soglia per l'effetto alpha bi-level. |

**Restituisce:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Indice del nuovo effetto immagine nella collezione.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

Aggiunge il nuovo effetto Alpha Ceiling alla fine di una collezione.

**Restituisce:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Indice del nuovo effetto immagine nella collezione.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

Aggiunge il nuovo effetto Alpha Floor alla fine di una collezione.

**Restituisce:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Indice del nuovo effetto immagine nella collezione.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

Aggiunge il nuovo effetto Alpha Inverse alla fine di una collezione.

**Restituisce:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Indice del nuovo effetto immagine nella collezione.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

Aggiunge il nuovo effetto Alpha Modulate alla fine di una collezione.

**Restituisce:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Indice del nuovo effetto immagine nella collezione.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Aggiunge il nuovo effetto Alpha Modulate Fixed alla fine di una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| amount | float | La quantità percentuale per scalare l'alpha. |

**Restituisce:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Indice del nuovo effetto immagine nella collezione.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Aggiunge il nuovo effetto Alpha Replace alla fine di una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alpha | float | Il nuovo valore di opacità. |

**Restituisce:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Indice del nuovo effetto immagine nella collezione.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

Aggiunge il nuovo effetto Bi-Level (bianco/nero) alla fine di una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| threshold | float | La soglia di luminanza per l'effetto Bi-Level. I valori maggiori o uguali alla soglia vengono impostati a bianco. I valori inferiori alla soglia vengono impostati a nero. |

**Restituisce:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Indice del nuovo effetto immagine nella collezione.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

Aggiunge il nuovo effetto Blur alla fine di una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| radius | double | Il raggio della sfocatura. |
| grow | boolean | Specifica se i limiti dell'oggetto devono essere ingranditi a seguito della sfocatura. True indica che i limiti sono ingranditi, false indica che non lo sono. |

**Restituisce:**
[IBlur](../../com.aspose.slides/iblur) - Indice del nuovo effetto immagine nella collezione.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

Aggiunge il nuovo effetto Color Change alla fine di una collezione.

**Restituisce:**
[IColorChange](../../com.aspose.slides/icolorchange) - Indice del nuovo effetto immagine nella collezione.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

Aggiunge il nuovo effetto Color Replacement alla fine di una collezione.

**Restituisce:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Indice del nuovo effetto immagine nella collezione.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

Aggiunge il nuovo effetto Duotone alla fine di una collezione.

**Restituisce:**
[IDuotone](../../com.aspose.slides/iduotone) - Indice del nuovo effetto immagine nella collezione.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

Aggiunge il nuovo effetto Fill Overlay alla fine di una collezione.

**Restituisce:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Indice del nuovo effetto immagine nella collezione.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

Aggiunge il nuovo effetto Gray Scale alla fine di una collezione.

**Restituisce:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Indice del nuovo effetto immagine nella collezione.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Aggiunge il nuovo effetto Hue/Saturation/Luminance alla fine di una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hue | float | Il numero di gradi di cui viene regolato il tono. |
| saturation | float | La percentuale di cui viene regolata la saturazione. |
| luminance | float | La percentuale di cui viene regolata la luminanza. |

**Restituisce:**
[IHSL](../../com.aspose.slides/ihsl) - Indice del nuovo effetto immagine nella collezione.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

Aggiunge il nuovo effetto Luminance alla fine di una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightness | float | La percentuale per modificare la luminosità. |
| contrast | float | La percentuale per modificare il contrasto. |

**Restituisce:**
[ILuminance](../../com.aspose.slides/iluminance) - Indice del nuovo effetto immagine nella collezione.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

Aggiunge il nuovo effetto Tint alla fine di una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hue | float | Il tono verso cui tintare. |
| amount | float | Specifica di quanto il valore del colore è spostato. |

**Restituisce:**
[ITint](../../com.aspose.slides/itint) - Indice del nuovo effetto immagine nella collezione.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Aggiunge il nuovo effetto BrightnessContrast alla fine di una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| brightness | float | La percentuale per modificare la luminosità. |
| contrast | float | La percentuale per modificare il contrasto. |

**Restituisce:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Indice del nuovo effetto immagine nella collezione.

### size() {#size--}
```
public final int size()
```

Restituisce il numero di effetti immagine in una collezione. int di sola lettura.

**Restituisce:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Ottiene un valore che indica se [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura. boolean di sola lettura.

**Restituisce:**
boolean - true se [IGenericCollection](../../com.aspose.slides/igenericcollection) è di sola lettura; altrimenti, false.

### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

Aggiunge il nuovo effetto immagine alla fine di una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | L'effetto immagine da aggiungere alla fine di una collezione. |

### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti gli effetti immagine da una collezione.

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

Determina se [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | L'oggetto da individuare in [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Restituisce:**
boolean - true se l'elemento è trovato in [IGenericCollection](../../com.aspose.slides/igenericcollection); altrimenti, false.

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | L'Array monodimensionale che è la destinazione degli elementi copiati da [IGenericCollection](../../com.aspose.slides/igenericcollection). L'Array deve avere indicizzazione basata su zero. |
| arrayIndex | int | L'indice basato su zero nell'array a partire dal quale inizia la copia. |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

Rimuove la prima occorrenza di un oggetto specifico da [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | L'oggetto da rimuovere da [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Restituisce:**
boolean - true se  item  è stato rimosso con successo da [IGenericCollection](../../com.aspose.slides/igenericcollection); altrimenti, false. Questo metodo restituisce anche false se item non è trovato nell'originale [IGenericCollection](../../com.aspose.slides/igenericcollection).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - An java.util.Iterator for the entire collection.