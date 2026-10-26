---
title: Column
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili sebuah kolom dalam tabel.
type: docs
url: /id/com.aspose.slides/column/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

Mewakili sebuah kolom dalam tabel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getWidth()](#getWidth--) | Mengembalikan atau mengatur lebar kolom. |
| [setWidth(double value)](#setWidth-double-) | Mengembalikan atau mengatur lebar kolom. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Mengatur properti format bagian yang ditentukan ke semua bagian sel kolom. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Mengatur properti format paragraf yang ditentukan ke semua paragraf sel kolom. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Mengatur properti format bingkai teks yang ditentukan ke semua bingkai teks sel kolom. |
| [getColumnFormat()](#getColumnFormat--) | Mengembalikan objek ColumnFormat yang berisi properti pemformatan untuk kolom ini. |
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Mengembalikan atau mengatur lebar kolom. Baca/tulis double.

**Mengembalikan:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Mengembalikan atau mengatur lebar kolom. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


Mengatur properti format bagian yang ditentukan ke semua bagian sel kolom.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | Objek IPortionFormat dengan properti yang diperlukan telah diatur. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


Mengatur properti format paragraf yang ditentukan ke semua paragraf sel kolom.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | Objek IParagraphFormat dengan properti yang diperlukan telah diatur. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


Mengatur properti format bingkai teks yang ditentukan ke semua bingkai teks sel kolom.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | Objek ITextFrameFormat dengan properti yang diperlukan telah diatur. |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```


Mengembalikan objek ColumnFormat yang berisi properti pemformatan untuk kolom ini. Baca-saja [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Mengembalikan:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)