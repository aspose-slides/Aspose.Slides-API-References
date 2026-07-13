---
title: INormalViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Represents normal view properties.
type: docs
url: /id/com.aspose.slides/inormalviewproperties/
---```
public interface INormalViewProperties
```

Mewakili properti tampilan normal. Tampilan normal terdiri dari tiga wilayah konten: slide itu sendiri, wilayah konten samping, dan wilayah konten bawah.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getShowOutlineIcons()](#getShowOutlineIcons--) | Menentukan apakah aplikasi harus menampilkan ikon saat menampilkan konten outline di salah satu wilayah konten mode tampilan normal. |
| [setShowOutlineIcons(boolean value)](#setShowOutlineIcons-boolean-) | Menentukan apakah aplikasi harus menampilkan ikon saat menampilkan konten outline di salah satu wilayah konten mode tampilan normal. |
| [getSnapVerticalSplitter()](#getSnapVerticalSplitter--) | Menentukan apakah pemisah vertikal harus menempel ke keadaan diperkecil ketika wilayah samping cukup kecil. |
| [setSnapVerticalSplitter(boolean value)](#setSnapVerticalSplitter-boolean-) | Menentukan apakah pemisah vertikal harus menempel ke keadaan diperkecil ketika wilayah samping cukup kecil. |
| [getVerticalBarState()](#getVerticalBarState--) | Menentukan keadaan di mana bilah pemisah vertikal harus ditampilkan. |
| [setVerticalBarState(int value)](#setVerticalBarState-int-) | Menentukan keadaan di mana bilah pemisah vertikal harus ditampilkan. |
| [getHorizontalBarState()](#getHorizontalBarState--) | Menentukan keadaan di mana bilah pemisah horizontal harus ditampilkan. |
| [setHorizontalBarState(int value)](#setHorizontalBarState-int-) | Menentukan keadaan di mana bilah pemisah horizontal harus ditampilkan. |
| [getPreferSingleView()](#getPreferSingleView--) | Menentukan apakah pengguna lebih suka melihat satu wilayah konten layar penuh dibandingkan tampilan normal standar dengan tiga wilayah konten. |
| [setPreferSingleView(boolean value)](#setPreferSingleView-boolean-) | Menentukan apakah pengguna lebih suka melihat satu wilayah konten layar penuh dibandingkan tampilan normal standar dengan tiga wilayah konten. |
| [getRestoredLeft()](#getRestoredLeft--) | Elemen ini menentukan ukuran wilayah konten samping dari tampilan normal, ketika wilayah tersebut memiliki ukuran pulih variabel (tidak diperkecil maupun diperbesar). |
| [getRestoredTop()](#getRestoredTop--) | Elemen ini menentukan ukuran wilayah slide atas dari tampilan normal, ketika wilayah tersebut memiliki ukuran pulih variabel (tidak diperkecil maupun diperbesar). |

### getShowOutlineIcons() {#getShowOutlineIcons--}
```
public abstract boolean getShowOutlineIcons()
```

Menentukan apakah aplikasi harus menampilkan ikon saat menampilkan konten outline di salah satu wilayah konten mode tampilan normal. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setShowOutlineIcons(boolean value) {#setShowOutlineIcons-boolean-}
```
public abstract void setShowOutlineIcons(boolean value)
```

Menentukan apakah aplikasi harus menampilkan ikon saat menampilkan konten outline di salah satu wilayah konten mode tampilan normal. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSnapVerticalSplitter() {#getSnapVerticalSplitter--}
```
public abstract boolean getSnapVerticalSplitter()
```

Menentukan apakah pemisah vertikal harus menempel ke keadaan diperkecil ketika wilayah samping cukup kecil. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setSnapVerticalSplitter(boolean value) {#setSnapVerticalSplitter-boolean-}
```
public abstract void setSnapVerticalSplitter(boolean value)
```

Menentukan apakah pemisah vertikal harus menempel ke keadaan diperkecil ketika wilayah samping cukup kecil. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getVerticalBarState() {#getVerticalBarState--}
```
public abstract int getVerticalBarState()
```

Menentukan keadaan di mana bilah pemisah vertikal harus ditampilkan. Bilah pemisah vertikal memisahkan slide dari wilayah konten samping.

**Mengembalikan:**
int

### setVerticalBarState(int value) {#setVerticalBarState-int-}
```
public abstract void setVerticalBarState(int value)
```

Menentukan keadaan di mana bilah pemisah vertikal harus ditampilkan. Bilah pemisah vertikal memisahkan slide dari wilayah konten samping.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHorizontalBarState() {#getHorizontalBarState--}
```
public abstract int getHorizontalBarState()
```

Menentukan keadaan di mana bilah pemisah horizontal harus ditampilkan. Bilah pemisah horizontal memisahkan slide dari wilayah konten di bawah slide.

**Mengembalikan:**
int

### setHorizontalBarState(int value) {#setHorizontalBarState-int-}
```
public abstract void setHorizontalBarState(int value)
```

Menentukan keadaan di mana bilah pemisah horizontal harus ditampilkan. Bilah pemisah horizontal memisahkan slide dari wilayah konten di bawah slide.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPreferSingleView() {#getPreferSingleView--}
```
public abstract boolean getPreferSingleView()
```

Menentukan apakah pengguna lebih suka melihat satu wilayah konten layar penuh dibandingkan tampilan normal standar dengan tiga wilayah konten. Jika diaktifkan, aplikasi dapat memilih menampilkan salah satu wilayah konten di seluruh jendela. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setPreferSingleView(boolean value) {#setPreferSingleView-boolean-}
```
public abstract void setPreferSingleView(boolean value)
```

Menentukan apakah pengguna lebih suka melihat satu wilayah konten layar penuh dibandingkan tampilan normal standar dengan tiga wilayah konten. Jika diaktifkan, aplikasi dapat memilih menampilkan salah satu wilayah konten di seluruh jendela. Baca/tulis boolean.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRestoredLeft() {#getRestoredLeft--}
```
public abstract INormalViewRestoredProperties getRestoredLeft()
```

Elemen ini menentukan ukuran wilayah konten samping dari tampilan normal, ketika wilayah tersebut memiliki ukuran pulih variabel (tidak diperkecil maupun diperbesar). Baca saja [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Mengembalikan:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)

### getRestoredTop() {#getRestoredTop--}
```
public abstract INormalViewRestoredProperties getRestoredTop()
```

Elemen ini menentukan ukuran wilayah slide atas dari tampilan normal, ketika wilayah tersebut memiliki ukuran pulih variabel (tidak diperkecil maupun diperbesar). Baca saja [INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties).

**Mengembalikan:**
[INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)