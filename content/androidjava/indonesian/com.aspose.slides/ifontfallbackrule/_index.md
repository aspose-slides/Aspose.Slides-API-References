---
title: IFontFallBackRule
second_title: Aspose.Slides for Android via Java API Reference
description: Mewakili aturan fallback font
type: docs
url: /id/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Mewakili aturan fallback font
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Menambahkan font baru ke dalam daftar font FallBack. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Menambahkan font baru ke dalam daftar font FallBack. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Mendapatkan indeks pertama dari rentang unicode berkelanjutan. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Mendapatkan indeks terakhir dari rentang unicode berkelanjutan. |
| [getCount()](#getCount--) | Mendapatkan jumlah font yang sebenarnya didefinisikan untuk rentang. |
| [get_Item(int index)](#get-Item-int-) | Mendapatkan nama font pada indeks yang ditentukan. |
| [clear()](#clear--) | Menghapus semua font dari daftar. |
| [remove(String fontName)](#remove-java.lang.String-) | Menghapus kemunculan pertama dari font FallBack tertentu dari daftar. |
| [removeAt(int index)](#removeAt-int-) | Menghapus font FallBack pada indeks yang ditentukan dalam daftar. |
| [toArray()](#toArray--) | Membuat dan mengembalikan array dengan semua font FallBack untuk aturan ini. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Membuat dan mengembalikan array dengan semua font FallBack dari rentang yang ditentukan dalam daftar. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Mengembalikan indeks dari aturan yang ditentukan dalam koleksi. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```


Menambahkan font baru ke dalam daftar font FallBack.

--------------------

> ```
> //Membuat instance baru dari FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Menambahkan font kedua ke aturan 
>  newRule.addFallBackFonts("MS Gothic");
>  //Menambahkan font ketiga dan keempat ke aturan 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | java.lang.String | Nama font atau nama-nama (dipisahkan dengan koma) untuk FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```


Menambahkan font baru ke dalam daftar font FallBack.

--------------------

> ```
> //Membuat instance baru dari FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Menambahkan tiga font lain ke aturan 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontNames | java.lang.String[] | Nama font atau nama-nama (dipisahkan dengan koma) untuk FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```


Mendapatkan indeks pertama dari rentang unicode berkelanjutan.

**Mengembalikan:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```


Mendapatkan indeks terakhir dari rentang unicode berkelanjutan.

**Mengembalikan:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```


Mendapatkan jumlah font yang sebenarnya didefinisikan untuk rentang.

**Mengembalikan:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```


Mendapatkan nama font pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int |  |

**Mengembalikan:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```


Menghapus semua font dari daftar.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```


Menghapus kemunculan pertama dari font FallBack tertentu dari daftar.

--------------------

> ```
> // Buat aturan yang berisi daftar font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Menghapus Tahoma dari daftar
>  newRule.remove("Tahoma");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | java.lang.String | Nama font yang akan dihapus dari daftar. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Menghapus font FallBack pada indeks yang ditentukan dalam daftar.

--------------------

> ```
> // Buat aturan yang berisi daftar font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Menghapus Tahoma dari daftar
>  newRule.remove(2);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari font yang akan dihapus. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```


Membuat dan mengembalikan array dengan semua font FallBack untuk aturan ini.

--------------------

> ```
> // Buat aturan yang berisi daftar font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Dapatkan semua nama font sebagai array
>  String[] fontNames = newRule.toArray();
> ```

**Mengembalikan:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```


Membuat dan mengembalikan array dengan semua font FallBack dari rentang yang ditentukan dalam daftar.

--------------------

> ```
> // Buat aturan yang berisi daftar font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Dapatkan dua nama font terakhir sebagai array
>  String[] fontNames = newRule.toArray(2,2);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | int | Indeks font pertama yang akan ditambahkan. |
| count | int | Jumlah font yang akan ditambahkan. |

**Mengembalikan:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```


Mengembalikan indeks dari aturan yang ditentukan dalam koleksi.

--------------------

> ```
> // Buat aturan yang berisi daftar font.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Dapatkan indeks Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | java.lang.String | Nama font yang dicari. |

**Mengembalikan:**
int - Indeks sebuah font atau -1 jika font tidak ditemukan dalam daftar.