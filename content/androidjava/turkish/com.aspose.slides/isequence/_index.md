---
title: ISequence
second_title: Aspose.Slides Android için Java API Referansı
description: Efektlerin sıralama koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/isequence/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

Sıralamayı (efekt koleksiyonunu) temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getCount()](#getCount--) | Bir sekans içindeki efekt sayısını döndürür. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Belirtilen efekti bir koleksiyondan kaldırır. |
| [removeAt(int index)](#removeAt-int-) | Bir efekti bir koleksiyondan kaldırır. |
| [clear()](#clear--) | Tüm efektleri bir koleksiyondan kaldırır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksdeki efekti döndürür. |
| [getTriggerShape()](#getTriggerShape--) | INTERACTIVE sekansı için şekil hedefini döndürür veya ayarlar. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | INTERACTIVE sekansı için şekil hedefini döndürür veya ayarlar. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Belirtilen şekil için efekti kaldırır. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Belirtilen şekil için efekt dizisini döndürür. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Belirtilen paragraf için efekt dizisini döndürür. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Belirtilen şekil için efekt sayısını döndürür. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Yeni bir efekti sekansın sonuna ekler. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Paragraf için yeni animasyon efektini sekansın sonuna ekler. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Kategori veya seriye yeni grafik animasyon efektini sekansın sonuna ekler. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Kategori veya serideki öğeler için yeni grafik animasyon efektini sekansın sonuna ekler. |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Bir sekans içindeki efekt sayısını döndürür. Yalnızca okunur int.

**Döndürür:**
int

### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

Belirtilen efekti bir koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Kaldırılacak efekt. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Bir efekti bir koleksiyondan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak efektin indeksi int |

### clear() {#clear--}
```
public abstract void clear()
```

Tüm efektleri bir koleksiyondan kaldırır.

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

Belirtilen indeksteki efekti döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Elemanın indeksi. |

**Döndürür:**
[IEffect](../../com.aspose.slides/ieffect) - [IEffect](../../com.aspose.slides/ieffect) nesnesi.

### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

INTERACTIVE sekansı için şekil hedefini döndürür veya ayarlar. Sekans etkileşimli değilse null döndürür. Okunabilir/yazılabilir [IShape](../../com.aspose.slides/ishape).

**Döndürür:**
[IShape](../../com.aspose.slides/ishape)

### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

INTERACTIVE sekansı için şekil hedefini döndürür veya ayarlar. Sekans etkileşimli değilse null döndürür. Okunabilir/yazılabilir [IShape](../../com.aspose.slides/ishape).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

Belirtilen şekil için efekti kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Şekil nesnesi [IShape](../../com.aspose.slides/ishape) |

### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

Belirtilen şekil için efekt dizisini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Şekil nesnesi [IShape](../../com.aspose.slides/ishape) |

**Döndürür:**
com.aspose.slides.IEffect[] - Efekt dizisi [IEffect](../../com.aspose.slides/ieffect)

### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Belirtilen paragraf için efekt dizisini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraf nesnesi [IParagraph](../../com.aspose.slides/iparagraph) |

**Döndürür:**
com.aspose.slides.IEffect[] - Efekt dizisi [IEffect](../../com.aspose.slides/ieffect)

### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

Belirtilen şekil için efekt sayısını döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Şekil nesnesi [IShape](../../com.aspose.slides/ishape) |

**Döndürür:**
int - Efekt sayısı int

### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Yeni bir efekti sekansın sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Efekt eklemek için [IShape](../../com.aspose.slides/ishape) şekil nesnesi |
| effectType | int | Animasyon efektinin türü [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animasyon efektinin alt türleri [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Efektin tetikleme türü [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Döndürür:**
[IEffect](../../com.aspose.slides/ieffect) - Yeni efekt nesnesi [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Paragraf için yeni animasyon efektini sekansın sonuna ekler.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // efekti eklemek için paragrafı seç
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // seçilen paragrafa Fly animasyon efekti ekle
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraf nesnesi [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Animasyon efektinin türü [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animasyon efektinin alt türleri [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Efektin tetikleme türü [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Döndürür:**
[IEffect](../../com.aspose.slides/ieffect) - Yeni efekt nesnesi [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Kategori veya seriye yeni grafik animasyon efektini sekansın sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Grafik nesnesi [IChart](../../com.aspose.slides/ichart) |
| type | int | Animasyon efektinin türü [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | İndeks int |
| effectType | int | Animasyon efektinin türü [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animasyon efektinin alt türleri [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Efektin tetikleme türü [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Döndürür:**
[IEffect](../../com.aspose.slides/ieffect) - Yeni efekt nesnesi [IEffect](../../com.aspose.slides/ieffect)

### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Kategori veya serideki öğeler için yeni grafik animasyon efektini sekansın sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | Grafik nesnesi [IChart](../../com.aspose.slides/ichart) |
| type | int | Animasyon efektinin türü [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Grafik serisinin indeksi int |
| categoriesIndex | int | Kategorinin indeksi int |
| effectType | int | Animasyon efektinin türü [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Animasyon efektinin alt türleri [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Efektin tetikleme türü [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Döndürür:**
[IEffect](../../com.aspose.slides/ieffect) - Yeni efekt nesnesi [IEffect](../../com.aspose.slides/ieffect)