---
title: Sequence
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en sekvens av effekter.
type: docs
url: /sv/com.aspose.slides/sequence/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)
```
public final class Sequence implements ISequence
```

Representerar sekvens (samling av effekter).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCount()](#getCount--) | Returnerar antalet effekter i en sekvens. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Tar bort angiven effekt från en samling. |
| [removeAt(int index)](#removeAt-int-) | Tar bort en effekt från en samling. |
| [clear()](#clear--) | Tar bort alla effekter från en samling. |
| [get_Item(int index)](#get-Item-int-) | Returnerar en effekt på det angivna indexet. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [getTriggerShape()](#getTriggerShape--) | Returnerar eller anger shape target för INTERACTIVE-sekvensen. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Returnerar eller anger shape target för INTERACTIVE-sekvensen. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Ta bort effekt för den angivna shape. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Returnerar array av effekter för den angivna shape. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Returnerar array av effekter för det angivna stycket. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Returnerar antalet effekter för den angivna shape. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Lägg till ny effekt i slutet av sekvensen. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Lägg till ny animeringseffekt för stycke i slutet av sekvensen. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Lägg till ny diagram-animeringseffekt för kategori eller serie i slutet av sekvensen. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Lägg till ny diagram-animeringseffekt för element i kategori eller serie i slutet av sekvensen. |
### getCount() {#getCount--}
```
public final int getCount()
```


Returnerar antalet effekter i en sekvens. Skrivskyddad int.

**Returnerar:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```


Tar bort angiven effekt från en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Effekt att ta bort. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Tar bort en effekt från en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en effekt som ska tas bort. |

### clear() {#clear--}
```
public final void clear()
```


Tar bort alla effekter från en samling.

### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```


Returnerar en effekt på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för elementet. |

**Returnerar:**
[IEffect](../../com.aspose.slides/ieffect) - [IEffect](../../com.aspose.slides/ieffect)-objektet.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```


Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```


Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - En java.util.Iterator för hela samlingen.
### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```


Returnerar eller anger shape target för INTERACTIVE-sekvensen. Om sekvensen inte är interaktiv returneras null. Läs/skriv [IShape](../../com.aspose.slides/ishape).

**Returnerar:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```


Returnerar eller anger shape target för INTERACTIVE-sekvensen. Om sekvensen inte är interaktiv returneras null. Läs/skriv [IShape](../../com.aspose.slides/ishape).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```


Ta bort effekt för den angivna shape.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```


Returnerar array av effekter för den angivna shape.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Returnerar:**
com.aspose.slides.IEffect[]
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```


Returnerar array av effekter för det angivna stycket.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**Returnerar:**
com.aspose.slides.IEffect[]
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```


Returnerar antalet effekter för den angivna shape.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Returnerar:**
int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```


Lägg till ny effekt i slutet av sekvensen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape-objekt [IShape](../../com.aspose.slides/ishape) för att lägga till en effekt |
| effectType | int | Typ av animeringseffekt [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Underklasser av animeringseffekt [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Utlösartyp för effekt [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returnerar:**
[IEffect](../../com.aspose.slides/ieffect) - Ny effekt-objekt [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```


Lägg till ny animeringseffekt för stycke i slutet av sekvensen.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // välj stycke för att lägga till effekt
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // lägg till Fly-animeringseffekt till markerat stycke
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph-objekt [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Typ av animeringseffekt [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Underklasser av animeringseffekt [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Utlösartyp för effekt [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returnerar:**
[IEffect](../../com.aspose.slides/ieffect) - Ny effekt-objekt [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```


Lägg till ny diagram-animeringseffekt för kategori eller serie i slutet av sekvensen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart-objekt [IChart](../../com.aspose.slides/ichart) |
| type | int | Typ av animeringseffekt [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Index-int |
| effectType | int | Typ av animeringseffekt [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Underklasser av animeringseffekt [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Utlösartyp för effekt [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returnerar:**
[IEffect](../../com.aspose.slides/ieffect) - Ny effekt-objekt [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```


Lägg till ny diagram-animeringseffekt för element i kategori eller serie i slutet av sekvensen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart-objekt [IChart](../../com.aspose.slides/ichart) |
| type | int | Typ av animeringseffekt [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Index för diagramserie-int |
| categoriesIndex | int | Index för kategori-int |
| effectType | int | Typ av animeringseffekt [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Underklasser av animeringseffekt [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Utlösartyp för effekt [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returnerar:**
[IEffect](../../com.aspose.slides/ieffect) - Ny effekt-objekt [IEffect](../../com.aspose.slides/ieffect)