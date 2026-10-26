---
title: IViewProperties
second_title: Referensi API Aspose.Slides untuk Android via Java
description: Properti tampilan seluruh presentasi.
type: docs
url: /id/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Properti tampilan seluruh presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLastView()](#getLastView--) | Specifies the view mode that was used when the presentation document was last saved. |
| [setLastView(int value)](#setLastView-int-) | Specifies the view mode that was used when the presentation document was last saved. |
| [getShowComments()](#getShowComments--) | Specifies whether the slide comments should be shown. |
| [setShowComments(byte value)](#setShowComments-byte-) | Specifies whether the slide comments should be shown. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Specifies common view properties associated with the slide view mode. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Specifies common view properties associated with the notes view mode. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Represents normal view properties. |
| [getGridSpacing()](#getGridSpacing--) | Returns or sets the grid spacing that should be used for the grid underlying the presentation document, in points. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Returns or sets the grid spacing that should be used for the grid underlying the presentation document, in points. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

Menentukan mode tampilan yang digunakan saat dokumen presentasi terakhir disimpan. Baca/tulis [ViewType](../../com.aspose.slides/viewtype).

**Mengembalikan:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

Menentukan mode tampilan yang digunakan saat dokumen presentasi terakhir disimpan. Baca/tulis [ViewType](../../com.aspose.slides/viewtype).

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

Mengembalikan atau mengatur jarak grid yang harus digunakan untuk grid dasar dokumen presentasi, dalam poin. Baca/tulis float.

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

Nilai jarak grid harus berupa angka positif. Rentang nilai tipikal adalah dari 1 mm (2.8349607 poin) hingga 2 inci (144 poin).

**Mengembalikan:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
```

Mengembalikan atau mengatur jarak grid yang harus digunakan untuk grid dasar dokumen presentasi, dalam poin. Baca/tulis float.

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

Nilai jarak grid harus berupa angka positif. Rentang nilai tipikal adalah dari 1 mm (2.8349607 poin) hingga 2 inci (144 poin).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |