---
title: Sequence
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una collezione di effetti di sequenza.
type: docs
url: /it/com.aspose.slides/sequence/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)
```
public final class Sequence implements ISequence
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
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore Java per l'intera collezione. |
| [getTriggerShape()](#getTriggerShape--) | Restituisce o imposta il bersaglio forma per la sequenza INTERACTIVE. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Restituisce o imposta il bersaglio forma per la sequenza INTERACTIVE. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Rimuove l'effetto per la forma specificata. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Restituisce un array di effetti per la forma specificata. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Restituisce un array di effetti per il paragrafo specificato. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Restituisce il conteggio degli effetti per la forma specificata. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Aggiunge un nuovo effetto alla fine della sequenza. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Aggiunge un nuovo effetto di animazione per il paragrafo alla fine della sequenza. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Aggiunge il nuovo effetto di animazione del grafico per la categoria o la serie alla fine della sequenza. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Aggiunge il nuovo effetto di animazione del grafico per gli elementi nella categoria o nella serie alla fine della sequenza. |
### getCount() {#getCount--}
```
public final int getCount()
```


Restituisce il numero di effetti in una sequenza. Sola lettura int.

**Restituisce:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```


Rimuove l'effetto specificato da una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Effetto da rimuovere. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Rimuove un effetto da una collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'effetto da eliminare. |

### clear() {#clear--}
```
public final void clear()
```


Rimuove tutti gli effetti da una collezione.

### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```


Restituisce un effetto all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dell'elemento. |

**Restituisce:**
[IEffect](../../com.aspose.slides/ieffect) - L'oggetto [IEffect](../../com.aspose.slides/ieffect).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```


Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```


Restituisce un iteratore Java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - Un java.util.Iterator per l'intera collezione.
### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```


Restituisce o imposta il bersaglio forma per la sequenza INTERACTIVE. Se la sequenza non è interattiva restituisce null. Lettura/Scrittura [IShape](../../com.aspose.slides/ishape).

**Restituisce:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```


Restituisce o imposta il bersaglio forma per la sequenza INTERACTIVE. Se la sequenza non è interattiva restituisce null. Lettura/Scrittura [IShape](../../com.aspose.slides/ishape).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```


Rimuove l'effetto per la forma specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```


Restituisce un array di effetti per la forma specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Restituisce:**
com.aspose.slides.IEffect[]
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```


Restituisce un array di effetti per il paragrafo specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**Restituisce:**
com.aspose.slides.IEffect[]
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```


Restituisce il conteggio degli effetti per la forma specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Restituisce:**
int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```


Aggiunge un nuovo effetto alla fine della sequenza.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Oggetto Shape [IShape](../../com.aspose.slides/ishape) per aggiungere un effetto |
| effectType | int | Tipo di effetto di animazione [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Sottotipi di effetto di animazione [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo di trigger dell'effetto [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Restituisce:**
[IEffect](../../com.aspose.slides/ieffect) - Nuovo oggetto effetto [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```


Aggiunge un nuovo effetto di animazione per il paragrafo alla fine della sequenza.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // seleziona il paragrafo a cui aggiungere l'effetto
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // aggiungi l'effetto di animazione Fly al paragrafo selezionato
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Oggetto Paragraph [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Tipo di effetto di animazione [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Sottotipi di effetto di animazione [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo di trigger dell'effetto [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Restituisce:**
[IEffect](../../com.aspose.slides/ieffect) - Nuovo oggetto effetto [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```


Aggiunge il nuovo effetto di animazione del grafico per la categoria o la serie alla fine della sequenza.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Oggetto Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | Tipo di effetto di animazione [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Indice int |
| effectType | int | Tipo di effetto di animazione [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Sottotipi di effetto di animazione [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo di trigger dell'effetto [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Restituisce:**
[IEffect](../../com.aspose.slides/ieffect) - Nuovo oggetto effetto [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```


Aggiunge il nuovo effetto di animazione del grafico per gli elementi nella categoria o nella serie alla fine della sequenza.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Oggetto Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | Tipo di effetto di animazione [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Indice della serie del grafico int |
| categoriesIndex | int | Indice della categoria int |
| effectType | int | Tipo di effetto di animazione [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Sottotipi di effetto di animazione [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipo di trigger dell'effetto [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Restituisce:**
[IEffect](../../com.aspose.slides/ieffect) - Nuovo oggetto effetto [IEffect](../../com.aspose.slides/ieffect)