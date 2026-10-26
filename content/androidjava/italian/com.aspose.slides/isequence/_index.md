---
title: ISequence
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta una collezione di effetti di sequenza.
type: docs
url: /it/com.aspose.slides/isequence/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

Rappresenta una sequenza (collezione di effetti).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCount()](#getCount--) | Restituisce il numero di effetti in una sequenza. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Rimuove l'effetto specificato da una collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove un effetto da una collezione. |
| [clear()](#clear--) | Rimuove tutti gli effetti da una collezione. |
| [get_Item(int index)](#get-Item-int-) | Restituisce un effetto all'indice specificato. |
| [getTriggerShape()](#getTriggerShape--) | Restituisce o imposta lo shape di destinazione per la sequenza INTERACTIVE. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Restituisce o imposta lo shape di destinazione per la sequenza INTERACTIVE. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Rimuove l'effetto per lo shape specificato. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Restituisce un array di effetti per lo shape specificato. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Restituisce un array di effetti per il paragrafo specificato. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Restituisce il conteggio degli effetti per lo shape specificato. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Aggiunge un nuovo effetto alla fine della sequenza. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Aggiunge un nuovo effetto di animazione per il paragrafo alla fine della sequenza. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Aggiunge il nuovo effetto di animazione del grafico per categoria o serie alla fine della sequenza. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Aggiunge il nuovo effetto di animazione del grafico per gli elementi in categoria o serie alla fine della sequenza. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Restituisce il numero di effetti in una sequenza. Solo lettura int.

**Restituisce:**
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

Rimuove l'effetto specificato da una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Effetto da rimuovere. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove un effetto da una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'effetto da rimuovere int |

### clear() {#clear--}
```
public abstract void clear()
```

Rimuove tutti gli effetti da una collezione.

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

Restituisce un effetto all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'elemento. |

**Restituisce:**
[IEffect](../../com.aspose.slides/ieffect) - The [IEffect](../../com.aspose.slides/ieffect) object.

### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

Restituisce o imposta lo shape di destinazione per la sequenza INTERACTIVE. Se la sequenza non è interattiva restituisce null. Lettura/scrittura [IShape](../../com.aspose.slides/ishape).

**Restituisce:**
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

Restituisce o imposta lo shape di destinazione per la sequenza INTERACTIVE. Se la sequenza non è interattiva restituisce null. Lettura/scrittura [IShape](../../com.aspose.slides/ishape).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

Rimuove l'effetto per lo shape specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Oggetto Shape [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

Restituisce un array di effetti per lo shape specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Oggetto Shape [IShape](../../com.aspose.slides/ishape) |

**Restituisce:**
com.aspose.slides.IEffect[] - Array di effetti [IEffect](../../com.aspose.slides/ieffect)

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Restituisce un array di effetti per il paragrafo specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Oggetto Paragraph [IParagraph](../../com.aspose.slides/iparagraph) |

**Restituisce:**
com.aspose.slides.IEffect[] - Array di effetti [IEffect](../../com.aspose.slides/ieffect)

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

Restituisce il conteggio degli effetti per lo shape specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Oggetto Shape [IShape](../../com.aspose.slides/ishape) |

**Restituisce:**
int - Conteggio degli effetti int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Aggiunge un nuovo effetto alla fine della sequenza.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Oggetto Shape [IShape](../../com.aspose.slides/ishape) per aggiungere un effetto |
| effectType | int | Tipo di un effetto di animazione [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Sottotipi di effetto di animazione [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo di attivazione dell'effetto [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Restituisce:**
[IEffect](../../com.aspose.slides/ieffect) - Nuovo oggetto effetto [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Aggiunge un nuovo effetto di animazione per il paragrafo alla fine della sequenza.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // seleziona il paragrafo a cui aggiungere l'effetto
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // aggiungi l'effetto di animazione Fly al paragrafo selezionato
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Oggetto Paragraph [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Tipo di un effetto di animazione [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Sottotipi di effetto di animazione [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo di attivazione dell'effetto [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Restituisce:**
[IEffect](../../com.aspose.slides/ieffect) - Nuovo oggetto effetto [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Aggiunge il nuovo effetto di animazione del grafico per categoria o serie alla fine della sequenza.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Oggetto Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | Tipo di un effetto di animazione [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Indice int |
| effectType | int | Tipo di un effetto di animazione [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Sottotipi di effetto di animazione [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo di attivazione dell'effetto [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Restituisce:**
[IEffect](../../com.aspose.slides/ieffect) - Nuovo oggetto effetto [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Aggiunge il nuovo effetto di animazione del grafico per gli elementi in categoria o serie alla fine della sequenza.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Oggetto Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | Tipo di un effetto di animazione [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Indice della serie del grafico int |
| categoriesIndex | int | Indice della categoria int |
| effectType | int | Tipo di un effetto di animazione [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Sottotipi di effetto di animazione [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo di attivazione dell'effetto [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Restituisce:**
[IEffect](../../com.aspose.slides/ieffect) - Nuovo oggetto effetto [IEffect](../../com.aspose.slides/ieffect)