---
title: ISequence
second_title: Aspose.Slides dla Androida przy użyciu referencji API Java
description: Reprezentuje kolekcję sekwencji efektów.
type: docs
url: /pl/com.aspose.slides/isequence/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

Reprezentuje sekwencję (kolekcję efektów).
## Metody

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Zwraca liczbę efektów w sekwencji. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Usuwa określony efekt z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa efekt z kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie efekty z kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca efekt pod podanym indeksem. |
| [getTriggerShape()](#getTriggerShape--) | Zwraca lub ustawia cel kształtu dla INTERACTIVE sequence. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Zwraca lub ustawia cel kształtu dla INTERACTIVE sequence. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Usuwa efekt dla określonego kształtu. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Zwraca tablicę efektów dla określonego kształtu. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Zwraca tablicę efektów dla określonego akapitu. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Zwraca liczbę efektów dla określonego kształtu. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Dodaje nowy efekt na koniec sekwencji. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Dodaje nowy efekt animacji dla akapitu na koniec sekwencji. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Dodaje nowy efekt animacji wykresu dla kategorii lub serii na koniec sekwencji. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Dodaje nowy efekt animacji wykresu dla elementów w kategorii lub serii na koniec sekwencji. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Zwraca liczbę efektów w sekwencji. Tylko do odczytu int.

**Zwraca:**
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

Usuwa określony efekt z kolekcji.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Efekt do usunięcia. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa efekt z kolekcji.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks efektu do usunięcia. |

### clear() {#clear--}
```
public abstract void clear()
```

Usuwa wszystkie efekty z kolekcji.

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

Zwraca efekt pod podanym indeksem.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Indeks elementu. |

**Zwraca:**
[IEffect](../../com.aspose.slides/ieffect) - The [IEffect](../../com.aspose.slides/ieffect) object.

### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

Zwraca lub ustawia cel kształtu dla INTERACTIVE sequence. Jeśli sekwencja nie jest interaktywna, zwraca null. Odczyt/zapis [IShape](../../com.aspose.slides/ishape).

**Zwraca:**
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

Zwraca lub ustawia cel kształtu dla INTERACTIVE sequence. Jeśli sekwencja nie jest interaktywna, zwraca null. Odczyt/zapis [IShape](../../com.aspose.slides/ishape).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

Usuwa efekt dla określonego kształtu.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Obiekt kształtu [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

Zwraca tablicę efektów dla określonego kształtu.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Obiekt kształtu [IShape](../../com.aspose.slides/ishape) |

**Zwraca:**
com.aspose.slides.IEffect[] - Tablica efektów [IEffect](../../com.aspose.slides/ieffect)

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Zwraca tablicę efektów dla określonego akapitu.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Obiekt akapitu [IParagraph](../../com.aspose.slides/iparagraph) |

**Zwraca:**
com.aspose.slides.IEffect[] - Tablica efektów [IEffect](../../com.aspose.slides/ieffect)

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

Zwraca liczbę efektów dla określonego kształtu.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Obiekt kształtu [IShape](../../com.aspose.slides/ishape) |

**Zwraca:**
int - Liczba efektów int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Dodaje nowy efekt na koniec sekwencji.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Obiekt kształtu [IShape](../../com.aspose.slides/ishape) do dodania efektu |
| effectType | int | Typ efektu animacji [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy efektu animacji [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ wyzwalacza efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Zwraca:**
[IEffect](../../com.aspose.slides/ieffect) - Nowy obiekt efektu [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Dodaje nowy efekt animacji dla akapitu na koniec sekwencji.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // wybierz akapit, aby dodać efekt
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // dodaj efekt animacji Fly do wybranego akapitu
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Obiekt akapitu [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Typ efektu animacji [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy efektu animacji [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ wyzwalacza efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Zwraca:**
[IEffect](../../com.aspose.slides/ieffect) - Nowy obiekt efektu [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Dodaje nowy efekt animacji wykresu dla kategorii lub serii na koniec sekwencji.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Obiekt wykresu [IChart](../../com.aspose.slides/ichart) |
| type | int | Typ efektu animacji [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Indeks int |
| effectType | int | Typ efektu animacji [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy efektu animacji [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ wyzwalacza efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Zwraca:**
[IEffect](../../com.aspose.slides/ieffect) - Nowy obiekt efektu [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Dodaje nowy efekt animacji wykresu dla elementów w kategorii lub serii na koniec sekwencji.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Obiekt wykresu [IChart](../../com.aspose.slides/ichart) |
| type | int | Typ efektu animacji [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Indeks serii wykresu int |
| categoriesIndex | int | Indeks kategorii int |
| effectType | int | Typ efektu animacji [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy efektu animacji [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ wyzwalacza efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Zwraca:**
[IEffect](../../com.aspose.slides/ieffect) - Nowy obiekt efektu [IEffect](../../com.aspose.slides/ieffect)