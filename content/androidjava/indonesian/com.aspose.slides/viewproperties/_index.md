---
title: ViewProperties
second_title: Referensi API Java Aspose.Slides untuk Android
description: Properti tampilan seluruh presentasi.
type: docs
url: /id/com.aspose.slides/viewproperties/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

Properti tampilan seluruh presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLastView()](#getLastView--) | Menentukan mode tampilan yang digunakan ketika dokumen presentasi terakhir disimpan. |
| [setLastView(int value)](#setLastView-int-) | Menentukan mode tampilan yang digunakan ketika dokumen presentasi terakhir disimpan. |
| [getShowComments()](#getShowComments--) | Menentukan apakah komentar slide harus ditampilkan. |
| [setShowComments(byte value)](#setShowComments-byte-) | Menentukan apakah komentar slide harus ditampilkan. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Mewakili properti tampilan normal. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Menentukan properti tampilan umum yang terkait dengan mode tampilan slide. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Menentukan properti tampilan umum yang terkait dengan mode tampilan catatan. |
| [getGridSpacing()](#getGridSpacing--) | Mengembalikan atau mengatur jarak kisi yang harus digunakan untuk kisi di bawah dokumen presentasi, dalam poin. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Mengembalikan atau mengatur jarak kisi yang harus digunakan untuk kisi di bawah dokumen presentasi, dalam poin. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getLastView() {#getLastView--}
```
public final int getLastView()
```

Menentukan mode tampilan yang digunakan ketika dokumen presentasi terakhir disimpan. Baca/tulis [ViewType](../../com.aspose.slides/viewtype).

**Mengembalikan:**
int
### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

Menentukan mode tampilan yang digunakan ketika dokumen presentasi terakhir disimpan. Baca/tulis [ViewType](../../com.aspose.slides/viewtype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

Menentukan apakah komentar slide harus ditampilkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

Menentukan apakah komentar slide harus ditampilkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

Mewakili properti tampilan normal. Tampilan normal terdiri dari tiga wilayah konten: slide itu sendiri, wilayah konten samping, dan wilayah konten bawah. Baca-saja [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Mengembalikan:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

Menentukan properti tampilan umum yang terkait dengan mode tampilan slide. Baca-saja [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Mengembalikan:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

Menentukan properti tampilan umum yang terkait dengan mode tampilan catatan. Baca-saja [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Mengembalikan:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

Mengembalikan atau mengatur jarak kisi yang harus digunakan untuk kisi di bawah dokumen presentasi, dalam poin. Baca/tulis float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Nilai jarak kisi harus berupa angka positif. Rentang nilai tipikal adalah dari 1 mm (2.8349607 poin) hingga 2 inci (144 poin).

**Mengembalikan:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

Mengembalikan atau mengatur jarak kisi yang harus digunakan untuk kisi di bawah dokumen presentasi, dalam poin. Baca/tulis float.

--------------------

> ```
> The following sample code shows how to change the grid spacing in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Nilai jarak kisi harus berupa angka positif. Rentang nilai tipikal adalah dari 1 mm (2.8349607 poin) hingga 2 inci (144 poin).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Baca-saja IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject