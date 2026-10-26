---
title: Sequence
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje kolekcję efektów w sekwencji.
type: docs
url: /pl/com.aspose.slides/sequence/
---
**Dziedziczenie:**  
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**  
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)  
```
public final class Sequence implements ISequence
```

Reprezentuje sekwencję (kolekcję efektów).

## Metody

| Metoda | Opis |
| --- | --- |
| [getCount()](#getCount--) | Zwraca liczbę efektów w sekwencji. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Usuwa określony efekt z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa efekt z kolekcji. |
| [clear()](#clear--) | Usuwa wszystkie efekty z kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca efekt o podanym indeksie. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
| [getTriggerShape()](#getTriggerShape--) | Zwraca lub ustawia kształt docelowy dla interaktywnej sekwencji. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Zwraca lub ustawia kształt docelowy dla interaktywnej sekwencji. |
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
public final int getCount()
```

Zwraca liczbę efektów w sekwencji. int (tylko do odczytu).

**Zwraca:**  
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

Usuwa określony efekt z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Efekt do usunięcia. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Usuwa efekt z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks efektu, który ma zostać usunięty. |

### clear() {#clear--}
```
public final void clear()
```

Usuwa wszystkie efekty z kolekcji.

### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

Zwraca efekt o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks elementu. |

**Zwraca:**  
[IEffect](../../com.aspose.slides/ieffect) – Obiekt [IEffect](../../com.aspose.slides/ieffect).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> – IGenericEnumerator, który może być użyty do iteracji po kolekcji.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

Zwraca iterator java dla całej kolekcji.

**Zwraca:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> – java.util.Iterator dla całej kolekcji.

### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

Zwraca lub ustawia kształt docelowy dla interaktywnej sekwencji. Jeśli sekwencja nie jest interaktywna, zwraca null. [IShape](../../com.aspose.slides/ishape) (odczyt/zapis).

**Zwraca:**  
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

Zwraca lub ustawia kształt docelowy dla interaktywnej sekwencji. Jeśli sekwencja nie jest interaktywna, zwraca null. [IShape](../../com.aspose.slides/ishape) (odczyt/zapis).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

Usuwa efekt dla określonego kształtu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

Zwraca tablicę efektów dla określonego kształtu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Zwraca:**  
com.aspose.slides.IEffect[]

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Zwraca tablicę efektów dla określonego akapitu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**Zwraca:**  
com.aspose.slides.IEffect[]

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

Zwraca liczbę efektów dla określonego kształtu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Zwraca:**  
int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Dodaje nowy efekt na koniec sekwencji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Obiekt kształtu [IShape](../../com.aspose.slides/ishape) do dodania efektu |
| effectType | int | Typ efektu animacji [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy efektu animacji [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ wyzwalacza efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Zwraca:**  
[IEffect](../../com.aspose.slides/ieffect) – Nowy obiekt efektu [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Dodaje nowy efekt animacji dla akapitu na koniec sekwencji.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // wybierz akapit, aby dodać efekt
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // dodaj efekt animacji Fly do wybranego akapitu
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Obiekt akapitu [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Typ efektu animacji [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy efektu animacji [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ wyzwalacza efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Zwraca:**  
[IEffect](../../com.aspose.slides/ieffect) – Nowy obiekt efektu [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Dodaje nowy efekt animacji wykresu dla kategorii lub serii na koniec sekwencji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Obiekt wykresu [IChart](../../com.aspose.slides/ichart) |
| type | int | Typ efektu animacji [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Indeks int |
| effectType | int | Typ efektu animacji [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy efektu animacji [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ wyzwalacza efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Zwraca:**  
[IEffect](../../com.aspose.slides/ieffect) – Nowy obiekt efektu [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Dodaje nowy efekt animacji wykresu dla elementów w kategorii lub serii na koniec sekwencji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Obiekt wykresu [IChart](../../com.aspose.slides/ichart) |
| type | int | Typ efektu animacji [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Indeks serii wykresu int |
| categoriesIndex | int | Indeks kategorii int |
| effectType | int | Typ efektu animacji [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Podtypy efektu animacji [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Typ wyzwalacza efektu [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Zwraca:**  
[IEffect](../../com.aspose.slides/ieffect) – Nowy obiekt efektu [IEffect](../../com.aspose.slides/ieffect)