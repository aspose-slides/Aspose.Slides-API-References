---
title: FontFallBackRule
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili aturan fallback font
type: docs
url: /id/com.aspose.slides/fontfallbackrule/
---
**Inheritance:** 
java.lang.Object

**All Implemented Interfaces:** 
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

Mewakili aturan fallback font
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Membuat instance baru. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Membuat instance baru. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Menambahkan font baru ke daftar font FallBack. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Menambahkan font baru ke daftar font FallBack. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Mendapatkan indeks pertama dari rentang unicode kontinu. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Mendapatkan indeks pertama dari rentang unicode kontinu. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Mendapatkan indeks terakhir dari rentang unicode kontinu. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Mendapatkan indeks terakhir dari rentang unicode kontinu. |
| [getCount()](#getCount--) | Mendapatkan jumlah font yang sebenarnya didefinisikan untuk rentang. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan nama font pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua font dari daftar. |
| [remove(String fontName)](#remove-java.lang.String-) | Menghapus kemunculan pertama dari font FallBack tertentu dari daftar. |
| [removeAt(int index)](#removeAt-int-) | Menghapus font FallBack pada indeks yang ditentukan dalam daftar. |
| [toArray()](#toArray--) | Membuat dan mengembalikan array dengan semua font FallBack untuk aturan ini. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Membuat dan mengembalikan array dengan semua font FallBack dari rentang yang ditentukan dalam daftar. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Mengembalikan indeks dari aturan yang ditentukan dalam koleksi. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```


Membuat instance baru.

--------------------

> ```
> // Buat instance baru dari FantFallBackRule dengan satu font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Buat instance baru dari FantFallBackRule dengan beberapa font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | long | Indeks awal rentang unicode |
| endIndex | long | Indeks akhir rentang unicode |
| fontNames | java.lang.String | Nama atau nama-nama font (dipisahkan koma) untuk FallBack |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```


Membuat instance baru.

--------------------

> ```
> // Buat instance baru dari FantFallBackRule dengan dua font
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Buat instance baru dari FantFallBackRule dengan beberapa font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | long | Indeks awal rentang unicode |
| endIndex | long | Indeks akhir rentang unicode |
| fontNames | java.lang.String[] | Nama atau nama-nama font (dipisahkan koma) untuk FallBack |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```


Menambahkan font baru ke daftar font FallBack.

--------------------

> ```
> // Buat instance baru dari FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Tambahkan font kedua ke aturan 
>  newRule.addFallBackFonts("MS Gothic");
>  //Tambahkan font ketiga dan keempat ke aturan 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | java.lang.String | Nama atau nama-nama font (dipisahkan koma) untuk FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```


Menambahkan font baru ke daftar font FallBack.

--------------------

> ```
> //Buat instance baru dari FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Tambahkan tiga font lainnya ke aturan 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontNames | java.lang.String[] | Nama atau nama-nama font (dipisahkan koma) untuk FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```


Mendapatkan indeks pertama dari rentang unicode kontinu.

**Mengembalikan:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```


Mendapatkan indeks pertama dari rentang unicode kontinu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```


Mendapatkan indeks terakhir dari rentang unicode kontinu.

**Mengembalikan:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```


Mendapatkan indeks terakhir dari rentang unicode kontinu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```


Mendapatkan jumlah font yang sebenarnya didefinisikan untuk rentang. int hanya-baca.

**Mengembalikan:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```


Mendapatkan nama font pada indeks yang ditentukan. int hanya-baca [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```


Menghapus semua font dari daftar.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```


Menghapus kemunculan pertama dari font FallBack tertentu dari daftar.

--------------------

> ```
> // Buat aturan yang berisi daftar font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Hapus Tahoma dari daftar.
>  newRule.remove("Tahoma");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | java.lang.String | Nama font yang akan dihapus dari daftar. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Menghapus font FallBack pada indeks yang ditentukan dalam daftar.

--------------------

> ```
> // Buat aturan yang berisi daftar font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Menghapus Tahoma dari daftar.
>  newRule.remove(2);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari font yang akan dihapus. |

### toArray() {#toArray--}
```
public final String[] toArray()
```


Membuat dan mengembalikan array dengan semua font FallBack untuk aturan ini.

--------------------

> ```
> // Buat aturan yang berisi daftar font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Dapatkan semua nama font sebagai array.
>  String[] fontNames = newRule.toArray();
> ```


**Mengembalikan:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```


Membuat dan mengembalikan array dengan semua font FallBack dari rentang yang ditentukan dalam daftar.

```
// Buat aturan yang berisi daftar font.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Dapatkan dua nama font terakhir sebagai array.
 String[] fontNames = newRule.toArray(2, 2);
```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | int | Indeks pertama font yang akan ditambahkan. |
| count | int | Jumlah font yang akan ditambahkan. |

**Mengembalikan:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```


Mengembalikan indeks dari aturan yang ditentukan dalam koleksi.

--------------------

> ```
> // Buat aturan yang berisi daftar font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Dapatkan indeks Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | java.lang.String | Nama font yang dicari. |

**Mengembalikan:**
int - Indeks font atau -1 jika font tidak ditemukan dalam daftar.