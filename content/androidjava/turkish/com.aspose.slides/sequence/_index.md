---
title: Sequence
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: Efektlerin dizi koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/sequence/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ISequence](../../com.aspose.slides/isequence)
```
public final class Sequence implements ISequence
```

Bir dizi (efekt koleksiyonu) temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getCount()](#getCount--) | Bir dizideki efekt sayısını döndürür. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Belirtilen efekti bir koleksiyondan kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Bir efekti bir koleksiyondan kaldırır. |
| [clear()](#clear--) | Tüm efektleri bir koleksiyondan kaldırır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki bir efekti döndürür. |
| [iterator()](#iterator--) | Koleksiyon içinde dolaşan bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [getTriggerShape()](#getTriggerShape--) | INTERACTIVE sırası için şekil hedefini döndürür veya ayarlar. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | INTERACTIVE sırası için şekil hedefini döndürür veya ayarlar. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Belirtilen şekil için efekti kaldırır. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Belirtilen şekil için efekt dizisini döndürür. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Belirtilen paragraf için efekt dizisini döndürür. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Belirtilen şekil için efekt sayısını döndürür. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Dizinin sonuna yeni bir efekt ekler. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Paragraf için yeni bir animasyon efektini dizinin sonuna ekler. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Kategori veya seri için yeni bir grafik animasyon efektini dizinin sonuna ekler. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Kategori veya serideki öğeler için yeni bir grafik animasyon efektini dizinin sonuna ekler. |

### getCount() {#getCount--}
```
public final int getCount()
```

Bir dizideki efekt sayısını döndürür. Yalnızca okunur int.

**Döndürür:**
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public final void remove(IEffect item)
```

Belirtilen efekti bir koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Kaldırılacak efekt. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Bir efekti bir koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Silinmesi gereken bir efektin indeksi. |

### clear() {#clear--}
```
public final void clear()
```

Tüm efektleri bir koleksiyondan kaldırır.

### get_Item(int index) {#get-Item-int-}
```
public final IEffect get_Item(int index)
```

Belirtilen indeksteki bir efekti döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Elemanın indeksi. |

**Döndürür:**
[IEffect](../../com.aspose.slides/ieffect) - The [IEffect](../../com.aspose.slides/ieffect) object.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iterator()
```

Koleksiyon içinde dolaşan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - Koleksiyon içinde dolaşmak için kullanılabilen bir IGenericEnumerator.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffect> iteratorJava()
```

Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffect> - Tüm koleksiyon için bir java.util.Iterator.

### getTriggerShape() {#getTriggerShape--}
```
public final IShape getTriggerShape()
```

INTERACTIVE sırası için şekil hedefini döndürür veya ayarlar. Sıra etkileşimli değilse null döndürür. Okunabilir/Yazılabilir [IShape](../../com.aspose.slides/ishape).

**Döndürür:**
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public final void setTriggerShape(IShape value)
```

INTERACTIVE sırası için şekil hedefini döndürür veya ayarlar. Sıra etkileşimli değilse null döndürür. Okunabilir/Yazılabilir [IShape](../../com.aspose.slides/ishape).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public final void removeByShape(IShape shape)
```

Belirtilen şekil için efekti kaldır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public final IEffect[] getEffectsByShape(IShape shape)
```

Belirtilen şekil için efekt dizisini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Döndürür:**
com.aspose.slides.IEffect[]

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public final IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Belirtilen paragraf için efekt dizisini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) |  |

**Döndürür:**
com.aspose.slides.IEffect[]

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public final int getCount(IShape shape)
```

Belirtilen şekil için efekt sayısını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

**Döndürür:**
int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public final IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Dizinin sonuna yeni bir efekt ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Efekt eklemek için [IShape](../../com.aspose.slides/ishape) şekil nesnesi |
| effectType | int | Bir animasyon efektinin tipi [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animasyon efektinin alt tipleri [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Efektin tetikleme tipi [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Döndürür:**
[IEffect](../../com.aspose.slides/ieffect) - Yeni efekt nesnesi [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public final IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Paragraf için yeni bir animasyon efektini dizinin sonuna ekler.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>   try
>   {        
>      // efekti eklemek için paragrafı seç
>      IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>      // seçilen paragrafa Fly animasyon efekti ekle
>      IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>      paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>   }  finally {
>      if (presentation != null) presentation.dispose();
>   }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | [IParagraph](../../com.aspose.slides/iparagraph) paragraf nesnesi |
| effectType | int | Bir animasyon efektinin tipi [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animasyon efektinin alt tipleri [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Efektin tetikleme tipi [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Döndürür:**
[IEffect](../../com.aspose.slides/ieffect) - Yeni efekt nesnesi [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Kategori veya seri için yeni bir grafik animasyon efektini dizinin sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | [IChart](../../com.aspose.slides/ichart) grafik nesnesi |
| type | int | Bir animasyon efektinin tipi [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | İndeks int |
| effectType | int | Bir animasyon efektinin tipi [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animasyon efektinin alt tipleri [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Efektin tetikleme tipi [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Döndürür:**
[IEffect](../../com.aspose.slides/ieffect) - Yeni efekt nesnesi [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public final IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Kategori veya serideki öğeler için yeni bir grafik animasyon efektini dizinin sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | [IChart](../../com.aspose.slides/ichart) grafik nesnesi |
| type | int | Bir animasyon efektinin tipi [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Grafik serisinin indeksi int |
| categoriesIndex | int | Kategori indeks int |
| effectType | int | Bir animasyon efektinin tipi [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animasyon efektinin alt tipleri [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Efektin tetikleme tipi [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Döndürür:**
[IEffect](../../com.aspose.slides/ieffect) - Yeni efekt nesnesi [IEffect](../../com.aspose.slides/ieffect)