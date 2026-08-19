---
title: Row
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili baris dalam tabel.
type: docs
url: /id/com.aspose.slides/row/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

Mewakili baris dalam tabel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getHeight()](#getHeight--) | Mengembalikan tinggi baris. |
| [getMinimalHeight()](#getMinimalHeight--) | Mengembalikan atau mengatur tinggi minimal yang mungkin untuk baris. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Mengembalikan atau mengatur tinggi minimal yang mungkin untuk baris. |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | Mengatur properti format bagian yang ditentukan ke semua bagian sel baris. |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | Mengatur properti format paragraf yang ditentukan ke semua paragraf sel baris. |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | Mengatur properti format bingkai teks yang ditentukan ke semua bingkai teks sel baris. |
| [getRowFormat()](#getRowFormat--) | Mengembalikan objek RowFormat yang berisi properti format untuk baris ini. |
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Mengembalikan tinggi baris. Baca-saja double.

**Mengembalikan:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Mengembalikan atau mengatur tinggi minimal yang mungkin untuk baris. Baca/tulis double.

**Mengembalikan:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```

Mengembalikan atau mengatur tinggi minimal yang mungkin untuk baris. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

Mengatur properti format bagian yang ditentukan ke semua bagian sel baris.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | objek IPortionFormat dengan properti yang diperlukan sudah diatur. |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

Mengatur properti format paragraf yang ditentukan ke semua paragraf sel baris.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | objek IParagraphFormat dengan properti yang diperlukan sudah diatur. |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

Mengatur properti format bingkai teks yang ditentukan ke semua bingkai teks sel baris.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | objek ITextFrameFormat dengan properti yang diperlukan sudah diatur. |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```

Mengembalikan objek RowFormat yang berisi properti format untuk baris ini. Baca-saja [IRowFormat](../../com.aspose.slides/irowformat).

**Mengembalikan:**
[IRowFormat](../../com.aspose.slides/irowformat)