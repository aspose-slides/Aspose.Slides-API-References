---
title: ISequence
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili koleksi urutan efek.
type: docs
url: /id/com.aspose.slides/isequence/
---
**Semua Antarmuka yang Diimplementasikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequence extends System.Collections.Generic.IGenericEnumerable<IEffect>
```

Mewakili urutan (koleksi efek).
## Metode

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Mengembalikan jumlah efek dalam urutan. |
| [remove(IEffect item)](#remove-com.aspose.slides.IEffect-) | Menghapus efek yang ditentukan dari koleksi. |
| [removeAt(int index)](#removeAt-int-) | Menghapus sebuah efek dari koleksi. |
| [clear()](#clear--) | Menghapus semua efek dari koleksi. |
| [get_Item(int index)](#get-Item-int-) | Mengembalikan sebuah efek pada indeks yang ditentukan. |
| [getTriggerShape()](#getTriggerShape--) | Mengembalikan atau menetapkan target shape untuk urutan INTERACTIVE. |
| [setTriggerShape(IShape value)](#setTriggerShape-com.aspose.slides.IShape-) | Mengembalikan atau menetapkan target shape untuk urutan INTERACTIVE. |
| [removeByShape(IShape shape)](#removeByShape-com.aspose.slides.IShape-) | Menghapus efek untuk shape yang ditentukan. |
| [getEffectsByShape(IShape shape)](#getEffectsByShape-com.aspose.slides.IShape-) | Mengembalikan array efek untuk shape yang ditentukan. |
| [getEffectsByParagraph(IParagraph paragraph)](#getEffectsByParagraph-com.aspose.slides.IParagraph-) | Mengembalikan array efek untuk paragraf yang ditentukan. |
| [getCount(IShape shape)](#getCount-com.aspose.slides.IShape-) | Mengembalikan jumlah efek untuk shape yang ditentukan. |
| [addEffect(IShape shape, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IShape-int-int-int-) | Menambahkan efek baru ke akhir urutan. |
| [addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IParagraph-int-int-int-) | Menambahkan efek animasi baru untuk paragraf ke akhir urutan. |
| [addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-) | Menambahkan efek animasi chart baru untuk kategori atau seri ke akhir urutan. |
| [addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)](#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-) | Menambahkan efek animasi chart baru untuk elemen dalam kategori atau seri ke akhir urutan. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

Mengembalikan jumlah efek dalam urutan. Hanya-baca int.

**Mengembalikan:**
int
### remove(IEffect item) {#remove-com.aspose.slides.IEffect-}
```
public abstract void remove(IEffect item)
```

Menghapus efek yang ditentukan dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | [IEffect](../../com.aspose.slides/ieffect) | Efek yang akan dihapus. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Menghapus sebuah efek dari koleksi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks efek yang akan dihapus int |
### clear() {#clear--}
```
public abstract void clear()
```

Menghapus semua efek dari koleksi.

### get_Item(int index) {#get-Item-int-}
```
public abstract IEffect get_Item(int index)
```

Mengembalikan sebuah efek pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks elemen. |

**Mengembalikan:**
[IEffect](../../com.aspose.slides/ieffect) - The [IEffect](../../com.aspose.slides/ieffect) object.
### getTriggerShape() {#getTriggerShape--}
```
public abstract IShape getTriggerShape()
```

Mengembalikan atau menetapkan target shape untuk urutan INTERACTIVE. Jika urutan tidak interaktif maka mengembalikan null. Baca/tulis [IShape](../../com.aspose.slides/ishape).

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape)
### setTriggerShape(IShape value) {#setTriggerShape-com.aspose.slides.IShape-}
```
public abstract void setTriggerShape(IShape value)
```

Mengembalikan atau menetapkan target shape untuk urutan INTERACTIVE. Jika urutan tidak interaktif maka mengembalikan null. Baca/tulis [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### removeByShape(IShape shape) {#removeByShape-com.aspose.slides.IShape-}
```
public abstract void removeByShape(IShape shape)
```

Menghapus efek untuk shape yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape object [IShape](../../com.aspose.slides/ishape) |
### getEffectsByShape(IShape shape) {#getEffectsByShape-com.aspose.slides.IShape-}
```
public abstract IEffect[] getEffectsByShape(IShape shape)
```

Mengembalikan array efek untuk shape yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape object [IShape](../../com.aspose.slides/ishape) |

**Mengembalikan:**
com.aspose.slides.IEffect[] - Array efek [IEffect](../../com.aspose.slides/ieffect)
### getEffectsByParagraph(IParagraph paragraph) {#getEffectsByParagraph-com.aspose.slides.IParagraph-}
```
public abstract IEffect[] getEffectsByParagraph(IParagraph paragraph)
```

Mengembalikan array efek untuk paragraf yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph object [IParagraph](../../com.aspose.slides/iparagraph) |

**Mengembalikan:**
com.aspose.slides.IEffect[] - Array efek [IEffect](../../com.aspose.slides/ieffect)
### getCount(IShape shape) {#getCount-com.aspose.slides.IShape-}
```
public abstract int getCount(IShape shape)
```

Mengembalikan jumlah efek untuk shape yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape object [IShape](../../com.aspose.slides/ishape) |

**Mengembalikan:**
int - Jumlah efek int
### addEffect(IShape shape, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IShape-int-int-int-}
```
public abstract IEffect addEffect(IShape shape, int effectType, int subtype, int triggerType)
```

Menambahkan efek baru ke akhir urutan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape object [IShape](../../com.aspose.slides/ishape) untuk menambahkan efek |
| effectType | int | Tipe efek animasi [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtipe efek animasi [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipe pemicu efek [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Mengembalikan:**
[IEffect](../../com.aspose.slides/ieffect) - Objek efek baru [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IParagraph-int-int-int-}
```
public abstract IEffect addEffect(IParagraph paragraph, int effectType, int subtype, int triggerType)
```

Menambahkan efek animasi baru untuk paragraf ke akhir urutan.

--------------------

> ```
> Presentation presentation = new Presentation(path + "input.pptx");
>  try
>  {
>     // pilih paragraf untuk menambahkan efek
>     IAutoShape autoShape = (IAutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>     IParagraph paragraph = autoShape.getTextFrame().getParagraphs().get_Item(0);
>     // tambahkan efek animasi Fly ke paragraf yang dipilih
>     IEffect effect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().addEffect(
>     paragraph, EffectType.Fly, EffectSubtype.Left, EffectTriggerType.OnClick);
>  } finally {
>     if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| paragraph | [IParagraph](../../com.aspose.slides/iparagraph) | objek Paragraph [IParagraph](../../com.aspose.slides/iparagraph) |
| effectType | int | Tipe efek animasi [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtipe efek animasi [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipe pemicu efek [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Mengembalikan:**
[IEffect](../../com.aspose.slides/ieffect) - Objek efek baru [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int index, int effectType, int subtype, int triggerType)
```

Menambahkan efek animasi chart baru untuk kategori atau seri ke akhir urutan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | objek Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | Tipe efek animasi [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| index | int | Indeks int |
| effectType | int | Tipe efek animasi [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtipe efek animasi [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipe pemicu efek [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Mengembalikan:**
[IEffect](../../com.aspose.slides/ieffect) - Objek efek baru [IEffect](../../com.aspose.slides/ieffect)
### addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType) {#addEffect-com.aspose.slides.IChart-int-int-int-int-int-int-}
```
public abstract IEffect addEffect(IChart chart, int type, int seriesIndex, int categoriesIndex, int effectType, int subtype, int triggerType)
```

Menambahkan efek animasi chart baru untuk elemen dalam kategori atau seri ke akhir urutan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chart | [IChart](../../com.aspose.slides/ichart) | objek Chart [IChart](../../com.aspose.slides/ichart) |
| type | int | Tipe efek animasi [EffectChartMinorGroupingType](../../com.aspose.slides/effectchartminorgroupingtype) |
| seriesIndex | int | Indeks seri chart int |
| categoriesIndex | int | Indeks kategori int |
| effectType | int | Tipe efek animasi [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Subtipe efek animasi [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Tipe pemicu efek [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Mengembalikan:**
[IEffect](../../com.aspose.slides/ieffect) - Objek efek baru [IEffect](../../com.aspose.slides/ieffect)