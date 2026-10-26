---
title: Tab
second_title: Aspose.Slides untuk Android via Java API Reference
description: Mewakili sebuah tabulasi untuk teks.
type: docs
url: /id/com.aspose.slides/tab/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

Mewakili sebuah tabulasi untuk teks.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Membuat Tab baru |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Mengembalikan atau mengatur posisi tab. |
| [setPosition(double value)](#setPosition-double-) | Mengembalikan atau mengatur posisi tab. |
| [getAlignment()](#getAlignment--) | Mengembalikan atau mengatur gaya perataan tab. |
| [setAlignment(int value)](#setAlignment-int-) | Mengembalikan atau mengatur gaya perataan tab. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Membandingkan instance saat ini dengan objek lain dari tipe yang sama. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

Membuat Tab baru

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| position | double | Posisi tab. |
| align | int | Perataan. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Hanya baca long.

**Mengembalikan:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```

Mengembalikan atau mengatur posisi tab. Menetapkan properti ini dapat mengubah indeks tab dalam koleksi dan membatalkan Enumerator. Baca/tulis double.

**Mengembalikan:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

Mengembalikan atau mengatur posisi tab. Menetapkan properti ini dapat mengubah indeks tab dalam koleksi dan membatalkan Enumerator. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Mengembalikan atau mengatur gaya perataan tab. Baca/tulis [TabAlignment](../../com.aspose.slides/tabalignment).

**Mengembalikan:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Mengembalikan atau mengatur gaya perataan tab. Baca/tulis [TabAlignment](../../com.aspose.slides/tabalignment).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```

Membandingkan instance saat ini dengan objek lain dari tipe yang sama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Sebuah objek untuk dibandingkan dengan instance ini. |

**Mengembalikan:**
int - Sebuah integer 32-bit yang menunjukkan urutan relatif dari kedua objek yang dibandingkan. Nilai balik memiliki arti berikut: 

 *  < 0 - Instance ini kurang dari obj.
 *  = 0 - Instance ini sama dengan obj.
 *  > 0 - Instance ini lebih besar dari obj.