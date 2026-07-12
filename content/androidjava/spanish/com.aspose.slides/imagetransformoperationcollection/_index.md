---
title: ImageTransformOperationCollection
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Representa una colección de efectos aplicados a una imagen.
type: docs
url: /es/com.aspose.slides/imagetransformoperationcollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

Representa una colección de efectos aplicados a una imagen.
## Métodos

| Método | Descripción |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | Devuelve un [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) de la colección por su índice. |
| [removeAt(int index)](#removeAt-int-) | Elimina un efecto de imagen de una colección en el índice especificado. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Agrega el nuevo efecto Alpha Bi-Level al final de una colección. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Agrega el nuevo efecto Alpha Ceiling al final de una colección. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Agrega el nuevo efecto Alpha Floor al final de una colección. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Agrega el nuevo efecto Alpha Inverse al final de una colección. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Agrega el nuevo efecto Alpha Modulate al final de una colección. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Agrega el nuevo efecto Alpha Modulate Fixed al final de una colección. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Agrega el nuevo efecto Alpha Replace al final de una colección. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Agrega el nuevo efecto Bi-Level (black/white) al final de una colección. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Agrega el nuevo efecto Blur al final de una colección. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Agrega el nuevo efecto Color Change al final de una colección. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Agrega el nuevo efecto Color Replacement al final de una colección. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Agrega el nuevo efecto Duotone al final de una colección. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Agrega el nuevo efecto Fill Overlay al final de una colección. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Agrega el nuevo efecto Gray Scale al final de una colección. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Agrega el nuevo efecto Hue/Saturation/Luminance al final de una colección. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Agrega el nuevo efecto Luminance al final de una colección. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Agrega el nuevo efecto Tint al final de una colección. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Agrega el nuevo efecto BrightnessContrast al final de una colección. |
| [size()](#size--) | Devuelve el número de efectos de imagen en una colección. |
| [isReadOnly()](#isReadOnly--) | Obtiene un valor que indica si el [IGenericCollection](../../com.aspose.slides/igenericcollection) es de solo lectura. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | Agrega el nuevo efecto de imagen al final de una colección. |
| [clear()](#clear--) | Elimina todos los efectos de imagen de una colección. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | Determina si el [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | Copia los elementos del [IGenericCollection](../../com.aspose.slides/igenericcollection) a un Array, comenzando en un índice de Array particular. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | Elimina la primera aparición de un objeto específico del [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versión. Sólo lectura long.

**Devuelve:**
long

### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

Devuelve un [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) de la colección por su índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del elemento. |

**Devuelve:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - El objeto [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Elimina un efecto de imagen de una colección en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de un efecto de imagen que debe ser eliminado. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

Agrega el nuevo efecto Alpha Bi-Level al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | float | El valor de umbral para el efecto alpha bi-level. |

**Devuelve:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Índice del nuevo efecto de imagen en la colección.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

Agrega el nuevo efecto Alpha Ceiling al final de una colección.

**Devuelve:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Índice del nuevo efecto de imagen en la colección.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

Agrega el nuevo efecto Alpha Floor al final de una colección.

**Devuelve:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Índice del nuevo efecto de imagen en la colección.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

Agrega el nuevo efecto Alpha Inverse al final de una colección.

**Devuelve:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Índice del nuevo efecto de imagen en la colección.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

Agrega el nuevo efecto Alpha Modulate al final de una colección.

**Devuelve:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Índice del nuevo efecto de imagen en la colección.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

Agrega el nuevo efecto Alpha Modulate Fixed al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| amount | float | La cantidad porcentual para escalar el alpha. |

**Devuelve:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Índice del nuevo efecto de imagen en la colección.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

Agrega el nuevo efecto Alpha Replace al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alpha | float | El nuevo valor de opacidad. |

**Devuelve:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Índice del nuevo efecto de imagen en la colección.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

Agrega el nuevo efecto Bi-Level (black/white) al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| threshold | float | El umbral de luminancia para el efecto Bi-Level. Los valores mayores o iguales al umbral se establecen en blanco. Los valores menores que el umbral se establecen en negro. |

**Devuelve:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Índice del nuevo efecto de imagen en la colección.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

Agrega el nuevo efecto Blur al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| radius | double | El radio del desenfoque. |
| grow | boolean | Especifica si los límites del objeto deben ampliarse como resultado del desenfoque. True indica que los límites se amplían, false indica que no. |

**Devuelve:**
[IBlur](../../com.aspose.slides/iblur) - Índice del nuevo efecto de imagen en la colección.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

Agrega el nuevo efecto Color Change al final de una colección.

**Devuelve:**
[IColorChange](../../com.aspose.slides/icolorchange) - Índice del nuevo efecto de imagen en la colección.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

Agrega el nuevo efecto Color Replacement al final de una colección.

**Devuelve:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Índice del nuevo efecto de imagen en la colección.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

Agrega el nuevo efecto Duotone al final de una colección.

**Devuelve:**
[IDuotone](../../com.aspose.slides/iduotone) - Índice del nuevo efecto de imagen en la colección.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

Agrega el nuevo efecto Fill Overlay al final de una colección.

**Devuelve:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Índice del nuevo efecto de imagen en la colección.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

Agrega el nuevo efecto Gray Scale al final de una colección.

**Devuelve:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Índice del nuevo efecto de imagen en la colección.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

Agrega el nuevo efecto Hue/Saturation/Luminance al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hue | float | El número de grados por los que se ajusta el tono. |
| saturation | float | El porcentaje por el que se ajusta la saturación. |
| luminance | float | El porcentaje por el que se ajusta la luminancia. |

**Devuelve:**
[IHSL](../../com.aspose.slides/ihsl) - Índice del nuevo efecto de imagen en la colección.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

Agrega el nuevo efecto Luminance al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightness | float | El porcentaje para cambiar el brillo. |
| contrast | float | El porcentaje para cambiar el contraste. |

**Devuelve:**
[ILuminance](../../com.aspose.slides/iluminance) - Índice del nuevo efecto de imagen en la colección.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

Agrega el nuevo efecto Tint al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hue | float | El tono hacia el que se tiñe. |
| amount | float | Especifica cuánto se desplaza el valor del color. |

**Devuelve:**
[ITint](../../com.aspose.slides/itint) - Índice del nuevo efecto de imagen en la colección.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

Agrega el nuevo efecto BrightnessContrast al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| brightness | float | El porcentaje para cambiar el brillo. |
| contrast | float | El porcentaje para cambiar el contraste. |

**Devuelve:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Índice del nuevo efecto de imagen en la colección.

### size() {#size--}
```
public final int size()
```

Devuelve el número de efectos de imagen en una colección. Sólo lectura int.

**Devuelve:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Obtiene un valor que indica si el [IGenericCollection](../../com.aspose.slides/igenericcollection) es de solo lectura. Sólo lectura boolean.

**Devuelve:**
boolean - true si el [IGenericCollection](../../com.aspose.slides/igenericcollection) es de solo lectura; de lo contrario, false.

### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

Agrega el nuevo efecto de imagen al final de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | El efecto de imagen que se agrega al final de una colección. |

### clear() {#clear--}
```
public final void clear()
```

Elimina todos los efectos de imagen de una colección.

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

Determina si el [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valor específico.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | El objeto que se busca en el [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Devuelve:**
boolean - true si el elemento se encuentra en el [IGenericCollection](../../com.aspose.slides/igenericcollection); de lo contrario, false.

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

Copia los elementos del [IGenericCollection](../../com.aspose.slides/igenericcollection) a un Array, comenzando en un índice de Array particular.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | El Array unidimensional que es el destino de los elementos copiados de [IGenericCollection](../../com.aspose.slides/igenericcollection). El Array debe tener indexación basada en cero. |
| arrayIndex | int | El índice basado en cero en el array donde comienza la copia. |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

Elimina la primera aparición de un objeto específico del [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | El objeto que se elimina del [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Devuelve:**
boolean - true si el  item  se eliminó correctamente del [IGenericCollection](../../com.aspose.slides/igenericcollection); de lo contrario, false. Este método también devuelve false si el elemento no se encuentra en el [IGenericCollection](../../com.aspose.slides/igenericcollection) original.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - Un java.util.Iterator para toda la colección.