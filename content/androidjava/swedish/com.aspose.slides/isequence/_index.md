---
title: ISequence
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar sekvenssamling av effekter.
type: docs
url: /sv/com.aspose.slides/isequence/
---
**Alla implementerade gränssnitt:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

Representerar sekvens (samling av effekter).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCount()](#getCount--) | Returnerar antalet effekter i en sekvens. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Tar bort specificerad effekt från en samling. |
| [removeAt(int index)](#removeAt-int-) | Tar bort en effekt från en samling. |
| [clear()](#clear--) | Tar bort alla effekter från en samling. |
| [get_Item(int index)](#get-Item-int-) | Returnerar en effekt på det angivna indexet. |
| [getTriggerShape()](#getTriggerShape--) | Returnerar eller anger shape-mål för INTERACTIVE-sekvens. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Returnerar eller anger shape-mål för INTERACTIVE-sekvens. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Ta bort effekt för den specificerade shape. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Returnerar en matris av effekter för den specificerade shape. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Returnerar en matris av effekter för den specificerade paragrafen. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Returnerar antal effekter för den specificerade shape. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Lägg till ny effekt i slutet av sekvensen. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Lägg till ny animeringseffekt för paragraf i slutet av sekvensen. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Lägger till den nya diagramanimeringseffekten för kategori eller serie i slutet av sekvensen. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Lägger till den nya diagramanimeringseffekten för element i kategori eller serie i slutet av sekvensen. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Returnerar antalet effekter i en sekvens. Skrivskyddad int.

**Returnerar:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

Tar bort specificerad effekt från en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Effekt att ta bort. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort en effekt från en samling.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för effekt att ta bort int |

### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla effekter från en samling.

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

Returnerar en effekt på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för element. |

**Returnerar:**
[IEffect](../../com.aspose.slides/ieffect) - [IEffect](../../com.aspose.slides/ieffect)-objektet.
### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

Returnerar eller anger shape-mål för INTERACTIVE-sekvens. Om sekvensen inte är interaktiv returneras null. Läs/skriv [IShape](../../com.aspose.slides/ishape).

**Returnerar:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

Returnerar eller anger shape-mål för INTERACTIVE-sekvens. Om sekvensen inte är interaktiv returneras null. Läs/skriv [IShape](../../com.aspose.slides/ishape).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

Ta bort effekt för den specificerade shape.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape-objekt [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

Returnerar en matris av effekter för den specificerade shape.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape-objekt [IShape](../../com.aspose.slides/ishape) |

**Returnerar:**
com.aspose.slides.IEffect[] - Matris av effekter [IEffect](../../com.aspose.slides/ieffect)
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Returnerar en matris av effekter för den specificerade paragrafen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph-objekt [IParagraph](../../com.aspose.slides/iparagraph) |

**Returnerar:**
com.aspose.slides.IEffect[] - Matris av effekter [IEffect](../../com.aspose.slides/ieffect)
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

Returnerar antal effekter för den specificerade shape.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape-objekt [IShape](../../com.aspose.slides/ishape) |

**Returnerar:**
int - Antal effekter int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Lägg till ny effekt i slutet av sekvensen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape-objekt [IShape](../../com.aspose.slides/ishape) för att lägga till en effekt |
| effectType | int | Typ av en animeringseffekt [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Undertyper av animeringseffekt [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Utlösartyp för effekt [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returnerar:**
[IEffect](../../com.aspose.slides/ieffect) - Ny effektobjekt [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Lägg till ny animeringseffekt för paragraf i slutet av sekvensen.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // välj paragraf för att lägga till effekt
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // lägg till Fly-animeringseffekt till vald paragraf
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph-objekt [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Typ av en animeringseffekt [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Undertyper av animeringseffekt [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Utlösartyp för effekt [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returnerar:**
[IEffect](../../com.aspose.slides/ieffect) - Ny effektobjekt [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Lägger till den nya diagramanimeringseffekten för kategori eller serie i slutet av sekvensen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart-objekt [IChart](../../com.aspose.slides/ichart) |
| type | int | Typ av en animeringseffekt [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Index int |
| effectType | int | Typ av en animeringseffekt [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Undertyper av animeringseffekt [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Utlösartyp för effekt [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returnerar:**
[IEffect](../../com.aspose.slides/ieffect) - Ny effektobjekt [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Lägger till den nya diagramanimeringseffekten för element i kategori eller serie i slutet av sekvensen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Chart-objekt [IChart](../../com.aspose.slides/ichart) |
| type | int | Typ av en animeringseffekt [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Index för diagramserie int |
| categoriesIndex | int | Index för kategori int |
| effectType | int | Typ av en animeringseffekt [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Undertyper av animeringseffekt [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Utlösartyp för effekt [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Returnerar:**
[IEffect](../../com.aspose.slides/ieffect) - Ny effektobjekt [IEffect](../../com.aspose.slides/ieffect)