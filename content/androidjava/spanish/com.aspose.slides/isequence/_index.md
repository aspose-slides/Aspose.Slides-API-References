---
title: ISequence
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Representa una colección de secuencias de efectos.
type: docs
url: /es/com.aspose.slides/isequence/
---
**Todas las interfaces implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

Representa una secuencia (colección de efectos).
## Métodos

| Método | Descripción |
| --- | --- |
| [getCount()](#getCount--) | Devuelve el número de efectos en una secuencia. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Elimina el efecto especificado de una colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina un efecto de una colección. |
| [clear()](#clear--) | Elimina todos los efectos de una colección. |
| [get_Item(int index)](#get-Item-int-) | Devuelve un efecto en el índice especificado. |
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
public abstract int getCount()
```

Devuelve el número de efectos en una secuencia. Solo lectura int.

**Devuelve:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

Elimina el efecto especificado de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Efecto a eliminar. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Elimina un efecto de una colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del efecto a eliminar int |
### clear() {#clear--}
```
public abstract void clear()
```

Elimina todos los efectos de una colección.
### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

Devuelve un efecto en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del elemento. |

**Devuelve:**
[IEffect](../../com.aspose.slides/ieffect) - El objeto [IEffect](../../com.aspose.slides/ieffect).
### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

Devuelve o establece el objetivo de forma para la secuencia INTERACTIVA. Si la secuencia no es interactiva, devuelve null. Lectura/escritura [IShape](../../com.aspose.slides/ishape).

**Devuelve:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

Devuelve o establece el objetivo de forma para la secuencia INTERACTIVA. Si la secuencia no es interactiva, devuelve null. Lectura/escritura [IShape](../../com.aspose.slides/ishape).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

Elimina el efecto para la forma especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objeto Shape [IShape](../../com.aspose.slides/ishape) |
### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

Devuelve una matriz de efectos para la forma especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objeto Shape [IShape](../../com.aspose.slides/ishape) |

**Devuelve:**
com.aspose.slides.IEffect[] - Matriz de efectos [IEffect](../../com.aspose.slides/ieffect)
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Devuelve una matriz de efectos para el párrafo especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Objeto Paragraph [IParagraph](../../com.aspose.slides/iparagraph) |

**Devuelve:**
com.aspose.slides.IEffect[] - Matriz de efectos [IEffect](../../com.aspose.slides/ieffect)
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

Devuelve el recuento de efectos para la forma especificada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Objeto Shape [IShape](../../com.aspose.slides/ishape) |

**Devuelve:**
int - Recuento de efectos int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
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
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Añade un nuevo efecto de animación para el párrafo al final de la secuencia.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // select paragraph to add effect
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // add Fly animation effect to selected paragraph
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
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
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
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
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Añade el nuevo efecto de animación de gráfico para los elementos en la categoría o serie al final de la secuencia.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Objeto Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | Tipo de efecto de animación [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Índice de la serie del gráfico int |
| categoriesIndex | int | Índice de la categoría int |
| effectType | int | Tipo de efecto de animación [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtipos de efecto de animación [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo de activación del efecto [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Devuelve:**
[IEffect](../../com.aspose.slides/ieffect) - Nuevo objeto de efecto [IEffect](../../com.aspose.slides/ieffect)