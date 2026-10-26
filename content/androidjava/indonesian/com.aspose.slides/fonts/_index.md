---
title: Fonts
second_title: Referensi API Java Aspose.Slides untuk Android
description: Koleksi font.
type: docs
url: /id/com.aspose.slides/fonts/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

Koleksi font.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Mengembalikan kamus semua definisi font skrip dalam presentasi. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Mendapatkan nama font yang terkait dengan tag skrip tertentu dari tema presentasi. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Menetapkan nama font ke tag skrip tertentu, yang menentukan bagaimana teks skrip tersebut akan dirender dalam presentasi. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Menghapus pengaturan font yang terkait dengan tag skrip tertentu dari koleksi font tema. |
| [getLatinFont()](#getLatinFont--) | Mengembalikan atau mengatur font Latin. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Mengembalikan atau mengatur font Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Mengembalikan atau mengatur font Asia Timur. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Mengembalikan atau mengatur font Asia Timur. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Mengembalikan atau mengatur font skrip kompleks. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Mengembalikan atau mengatur font skrip kompleks. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```


Mengembalikan kamus semua definisi font skrip dalam presentasi.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```


**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Sebuah kamus yang memetakan kode skrip ke nama font.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```


Mendapatkan nama font yang terkait dengan tag skrip tertentu dari tema presentasi.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| script | java.lang.String | Kode skrip BCP-47 (mis., "Latn", "Cyrl", "Jpan") yang digunakan untuk mengidentifikasi sistem penulisan. |

**Mengembalikan:**
java.lang.String - Nama font yang digunakan untuk skrip yang ditentukan, atau  null  jika skrip tidak didefinisikan.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```


Menetapkan nama font ke tag skrip tertentu, yang menentukan bagaimana teks skrip tersebut akan dirender dalam presentasi.

--------------------

> ```
> Contoh ini menunjukkan cara mengatur font untuk skrip Arab ke "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segue UI");
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| script | java.lang.String | Kode skrip BCP-47 (mis., "Arab", "Hebr", "Hans") yang mengidentifikasi sistem penulisan. |
| fontName | java.lang.String | Nama font yang akan ditetapkan ke skrip yang ditentukan. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```


Menghapus pengaturan font yang terkait dengan tag skrip tertentu dari koleksi font tema.

--------------------

> ```
> Contoh ini menunjukkan cara menghapus pemetaan font untuk skrip Ibrani:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| script | java.lang.String | Kode skrip BCP-47 yang pengaturan fontnya harus dihapus. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```


Mengembalikan atau mengatur font Latin. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```


Mengembalikan atau mengatur font Latin. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```


Mengembalikan atau mengatur font Asia Timur. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```


Mengembalikan atau mengatur font Asia Timur. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```


Mengembalikan atau mengatur font skrip kompleks. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Mengembalikan:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```


Mengembalikan atau mengatur font skrip kompleks. Baca/tulis [IFontData](../../com.aspose.slides/ifontdata).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |