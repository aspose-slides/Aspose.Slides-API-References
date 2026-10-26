---
title: IViewProperties
second_title: Aspose.Slides for Java API Reference
description: Presentation wide view properties.
type: docs
url: /id/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Properti tampilan seluruh presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLastView()](#getLastView--) | Menentukan mode tampilan yang digunakan ketika dokumen presentasi terakhir disimpan. |
| [setLastView(int value)](#setLastView-int-) | Menentukan mode tampilan yang digunakan ketika dokumen presentasi terakhir disimpan. |
| [getShowComments()](#getShowComments--) | Menentukan apakah komentar slide harus ditampilkan. |
| [setShowComments(byte value)](#setShowComments-byte-) | Menentukan apakah komentar slide harus ditampilkan. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Menentukan properti tampilan umum yang terkait dengan mode tampilan slide. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Menentukan properti tampilan umum yang terkait dengan mode tampilan catatan. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Mewakili properti tampilan normal. |
| [getGridSpacing()](#getGridSpacing--) | Mengembalikan atau mengatur jarak kisi yang harus digunakan untuk kisi di bawah dokumen presentasi, dalam poin. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Mengembalikan atau mengatur jarak kisi yang harus digunakan untuk kisi di bawah dokumen presentasi, dalam poin. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

Menentukan mode tampilan yang digunakan ketika dokumen presentasi terakhir disimpan. Baca/tulis [ViewType](../../com.aspose.slides/viewtype).

**Mengembalikan:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

Menentukan mode tampilan yang digunakan ketika dokumen presentasi terakhir disimpan. Baca/tulis [ViewType](../../com.aspose.slides/viewtype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

Menentukan apakah komentar slide harus ditampilkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

Menentukan apakah komentar slide harus ditampilkan. Baca/tulis [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

Menentukan properti tampilan umum yang terkait dengan mode tampilan slide. Baca-saja [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Mengembalikan:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

Menentukan properti tampilan umum yang terkait dengan mode tampilan catatan. Baca-saja [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Mengembalikan:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

Mewakili properti tampilan normal. Tampilan normal terdiri dari tiga wilayah konten: slide itu sendiri, wilayah konten samping, dan wilayah konten bawah. Baca-saja [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Mengembalikan:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
```

Mengembalikan atau mengatur jarak kisi yang harus digunakan untuk kisi di bawah dokumen presentasi, dalam poin. Baca/tulis float.

--------------------

> ```
> Berikut contoh kode yang menunjukkan cara mengubah jarak kisi dalam presentasi PowerPoint.
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
public abstract void setGridSpacing(float value)
```

Mengembalikan atau mengatur jarak kisi yang harus digunakan untuk kisi di bawah dokumen presentasi, dalam poin. Baca/tulis float.

--------------------

> ```
> Berikut contoh kode yang menunjukkan cara mengubah jarak kisi dalam presentasi PowerPoint.
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