---
title: NormalViewProperties
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili properti tampilan normal.
type: docs
url: /id/com.aspose.slides/normalviewproperties/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
```
public class NormalViewProperties implements INormalViewProperties
```

Mewakili properti tampilan normal. Tampilan normal terdiri dari tiga wilayah konten: slide itu sendiri, wilayah konten samping, dan wilayah konten bawah.

--------------------

> ```
> The following example shows how to configure ViewProperties.NormalViewProperties properties of a PowerPoint Presentation.
>  
>  //Membuat instance objek presentasi yang mewakili file presentasi
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      pres.getViewProperties().getNormalViewProperties().setHorizontalBarState(SplitterBarStateType.Restored);
>      pres.getViewProperties().getNormalViewProperties().setVerticalBarState(SplitterBarStateType.Maximized);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setAutoAdjust(true);
>      pres.getViewProperties().getNormalViewProperties().getRestoredTop().setDimensionSize(80);
>      pres.getViewProperties().getNormalViewProperties().setShowOutlineIcons(true);
>      pres.save("presentation_normal_view_state.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Menentukan apakah aplikasi harus menampilkan ikon saat menampilkan konten outline di salah satu wilayah konten mode tampilan normal. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Menentukan apakah aplikasi harus menampilkan ikon saat menampilkan konten outline di salah satu wilayah konten mode tampilan normal. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Menentukan apakah pemisah vertikal harus menempel pada keadaan terkecil ketika wilayah samping cukup kecil. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Menentukan apakah pemisah vertikal harus menempel pada keadaan terkecil ketika wilayah samping cukup kecil. |
| [getVerticalBarState()](#getVerticalBarState--) | Menentukan keadaan di mana bar pemisah vertikal harus ditampilkan. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Menentukan keadaan di mana bar pemisah vertikal harus ditampilkan. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Menentukan keadaan di mana bar pemisah horizontal harus ditampilkan. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Menentukan keadaan di mana bar pemisah horizontal harus ditampilkan. |
| [getPreferSingleView()](#getPreferSingleView--) | Menentukan apakah pengguna lebih suka melihat wilayah konten tunggal penuh jendela dibandingkan tampilan normal standar dengan tiga wilayah konten. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Menentukan apakah pengguna lebih suka melihat wilayah konten tunggal penuh jendela dibandingkan tampilan normal standar dengan tiga wilayah konten. |
| [getRestoredLeft()](#getRestoredLeft--) | Elemen ini menentukan ukuran wilayah konten samping tampilan normal, ketika wilayah tersebut berukuran variabel yang dipulihkan (tidak diperkecil maupun diperbesar). |
| [getRestoredTop()](#getRestoredTop--) | Elemen ini menentukan ukuran wilayah slide atas tampilan normal, ketika wilayah tersebut berukuran variabel yang dipulihkan (tidak diperkecil maupun diperbesar). |
### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public final boolean getShowOutlineIcons()
```

Menentukan apakah aplikasi harus menampilkan ikon saat menampilkan konten outline di salah satu wilayah konten mode tampilan normal. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public final void setShowOutlineIcons(boolean value)
```

Menentukan apakah aplikasi harus menampilkan ikon saat menampilkan konten outline di salah satu wilayah konten mode tampilan normal. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public final boolean getSnapVerticalSplitter()
```

Menentukan apakah pemisah vertikal harus menempel pada keadaan terkecil ketika wilayah samping cukup kecil. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public final void setSnapVerticalSplitter(boolean value)
```

Menentukan apakah pemisah vertikal harus menempel pada keadaan terkecil ketika wilayah samping cukup kecil. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public final int getVerticalBarState()
```

Menentukan keadaan di mana bar pemisah vertikal harus ditampilkan. Bar pemisah vertikal memisahkan slide dari wilayah konten samping.

**Mengembalikan:**
int
### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public final void setVerticalBarState(int value)
```

Menentukan keadaan di mana bar pemisah vertikal harus ditampilkan. Bar pemisah vertikal memisahkan slide dari wilayah konten samping.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public final int getHorizontalBarState()
```

Menentukan keadaan di mana bar pemisah horizontal harus ditampilkan. Bar pemisah horizontal memisahkan slide dari wilayah konten di bawah slide.

**Mengembalikan:**
int
### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public final void setHorizontalBarState(int value)
```

Menentukan keadaan di mana bar pemisah horizontal harus ditampilkan. Bar pemisah horizontal memisahkan slide dari wilayah konten di bawah slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public final boolean getPreferSingleView()
```

Menentukan apakah pengguna lebih suka melihat wilayah konten tunggal penuh jendela dibandingkan tampilan normal standar dengan tiga wilayah konten. Jika diaktifkan, aplikasi dapat memilih menampilkan salah satu wilayah konten di seluruh jendela. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public final void setPreferSingleView(boolean value)
```

Menentukan apakah pengguna lebih suka melihat wilayah konten tunggal penuh jendela dibandingkan tampilan normal standar dengan tiga wilayah konten. Jika diaktifkan, aplikasi dapat memilih menampilkan salah satu wilayah konten di seluruh jendela. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public final INormalViewRestoredProperties getRestoredLeft()
```

Elemen ini menentukan ukuran wilayah konten samping tampilan normal, ketika wilayah tersebut berukuran variabel yang dipulihkan (tidak diperkecil maupun diperbesar). Baca saja [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Mengembalikan:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
### getRestoredTop() {#getRestoredTop--}
```
public final INormalViewRestoredProperties getRestoredTop()
```

Elemen ini menentukan ukuran wilayah slide atas tampilan normal, ketika wilayah tersebut berukuran variabel yang dipulihkan (tidak diperkecil maupun diperbesar). Baca saja [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Mengembalikan:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)