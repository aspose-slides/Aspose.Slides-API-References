---
title: Sequence
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa una colección de efectos de secuencia.
type: docs
url: /es/com.aspose.slides/sequence/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)
```
public final class Sequence implements ISequence
```

Representa una secuencia (colección de efectos).
## Métodos

| Método | Descripción |
| --- | --- |
| [getCount()](#getCount--) | Devuelve el número de efectos en una secuencia. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Elimina el efecto especificado de una colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina el efecto especificado de una colección. |
| [clear()](#clear--) | Elimina todos los efectos de una colección. |
| [get_Item(int index)](#get-Item-int-) | Devuelve un efecto en el índice especificado. |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [getTriggerShape()](#getTriggerShape--) | Devuelve o establece el objetivo de forma para la secuencia INTERACTIVA. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Devuelve o establece el objetivo de forma para la secuencia INTERACTIVA. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Elimina el efecto para la forma especificada. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Devuelve una matriz de efectos para la forma especificada. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Devuelve una matriz de efectos para el párrafo especificado. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Devuelve el recuento de efectos para la forma especificada. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Añade un nuevo efecto al final de la secuencia. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Añade un nuevo efecto de animación para el párrafo al final de la secuencia. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Añade el nuevo efecto de animación de gráfico para la categoría o serie al final de la secuencia. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Añade el nuevo efecto de animación de gráfico para los elementos en la categoría o serie al final de la secuencia. |
### getCount() {#getCount--}
```
public final int getCount()
```

Devuelve el número de efectos en una secuencia. int de solo lectura.

**Devuelve:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

Elimina el efecto especificado de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Efecto a eliminar. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Elimina un efecto de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del efecto que debe eliminarse. |

### clear() {#clear--}
```
public final void clear()
```

Elimina todos los efectos de una colección.

### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

Devuelve un efecto en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del elemento. |

**Devuelve:**
[IEffect](../../com.aspose.slides/ieffect) - El objeto [IEffect](../../com.aspose.slides/ieffect).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - Un java.util.Iterator para toda la colección.
### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

Devuelve o establece el objetivo de forma para la secuencia INTERACTIVA. Si la secuencia no es interactiva entonces devuelve null. Lectura/escritura [IShape](../../com.aspose.slides/ishape).

**Devuelve:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

Devuelve o establece el objetivo de forma para la secuencia INTERACTIVA. Si la secuencia no es interactiva entonces devuelve null. Lectura/escritura [IShape](../../com.aspose.slides/ishape).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

Elimina el efecto para la forma especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

Devuelve una matriz de efectos para la forma especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Devuelve:**
com.aspose.slides.IEffect[]
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Devuelve una matriz de efectos para el párrafo especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**Devuelve:**
com.aspose.slides.IEffect[]
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

Devuelve el recuento de efectos para la forma especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Devuelve:**
int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Añade un nuevo efecto al final de la secuencia.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objeto Shape [IShape](../../com.aspose.slides/ishape) para añadir un efecto |
| effectType | int | Tipo de efecto de animación [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtipos de efecto de animación [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo de activación del efecto [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Devuelve:**
[IEffect](../../com.aspose.slides/ieffect) - Nuevo objeto de efecto [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Añade un nuevo efecto de animación para el párrafo al final de la secuencia.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // seleccionar párrafo para añadir efecto
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // añadir efecto de animación Fly al párrafo seleccionado
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Objeto Paragraph [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Tipo de efecto de animación [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtipos de efecto de animación [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo de activación del efecto [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Devuelve:**
[IEffect](../../com.aspose.slides/ieffect) - Nuevo objeto de efecto [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Añade el nuevo efecto de animación de gráfico para la categoría o serie al final de la secuencia.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Objeto Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | Tipo de efecto de animación [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Índice int |
| effectType | int | Tipo de efecto de animación [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtipos de efecto de animación [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo de activación del efecto [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Devuelve:**
[IEffect](../../com.aspose.slides/ieffect) - Nuevo objeto de efecto [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Añade el nuevo efecto de animación de gráfico para los elementos en la categoría o serie al final de la secuencia.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Objeto Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | Tipo de efecto de animación [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Índice de serie del gráfico int |
| categoriesIndex | int | Índice de categoría int |
| effectType | int | Tipo de efecto de animación [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtipos de efecto de animación [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo de activación del efecto [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Devuelve:**
[IEffect](../../com.aspose.slides/ieffect) - Nuevo objeto de efecto [IEffect](../../com.aspose.slides/ieffect)