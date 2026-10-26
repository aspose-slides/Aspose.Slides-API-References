---
title: IOverrideTheme
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili tema yang menimpa.
type: docs
url: /id/com.aspose.slides/ioverridetheme/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

Mewakili tema yang menimpa.
## Metode

| Method | Description |
| --- | --- |
| [isEmpty()](#isEmpty--) | Nilai true berarti bahwa ColorScheme, FontScheme, FormatScheme bernilai null dan setiap penimpaan dengan objek tema ini dinonaktifkan. |
| [initColorScheme()](#initColorScheme--) | Inisialisasi ColorScheme dengan objek baru untuk menimpa ColorScheme dari InheritedTheme. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Inisialisasi ColorScheme dengan objek baru untuk menimpa ColorScheme dari InheritedTheme. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Inisialisasi ColorScheme dengan objek baru untuk menimpa ColorScheme dari InheritedTheme. |
| [initFontScheme()](#initFontScheme--) | Inisialisasi FontScheme dengan objek baru untuk menimpa FontScheme dari InheritedTheme. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Inisialisasi FontScheme dengan objek baru untuk menimpa FontScheme dari InheritedTheme. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Inisialisasi FontScheme dengan objek baru untuk menimpa FontScheme dari InheritedTheme. |
| [initFormatScheme()](#initFormatScheme--) | Inisialisasi FormatScheme dengan objek baru untuk menimpa FormatScheme dari InheritedTheme. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Inisialisasi FormatScheme dengan objek baru untuk menimpa FormatScheme dari InheritedTheme. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Inisialisasi FormatScheme dengan objek baru untuk menimpa FormatScheme dari InheritedTheme. |
| [clear()](#clear--) | Tetapkan ColorScheme, FontScheme, FormatScheme menjadi null untuk menonaktifkan setiap penimpaan dengan objek tema ini. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

Nilai true berarti bahwa ColorScheme, FontScheme, FormatScheme bernilai null dan setiap penimpaan dengan objek tema ini dinonaktifkan. Boolean hanya-baca.

**Mengembalikan:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

Inisialisasi ColorScheme dengan objek baru untuk menimpa ColorScheme dari InheritedTheme.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

Inisialisasi ColorScheme dengan objek baru untuk menimpa ColorScheme dari InheritedTheme.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Data untuk menginisialisasi dari. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

Inisialisasi ColorScheme dengan objek baru untuk menimpa ColorScheme dari InheritedTheme. Dan menginisialisasi data objek baru ini dengan data dari ColorScheme milik InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

Inisialisasi FontScheme dengan objek baru untuk menimpa FontScheme dari InheritedTheme.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

Inisialisasi FontScheme dengan objek baru untuk menimpa FontScheme dari InheritedTheme.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Data untuk menginisialisasi dari. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

Inisialisasi FontScheme dengan objek baru untuk menimpa FontScheme dari InheritedTheme. Dan menginisialisasi data objek baru ini dengan data dari FontScheme milik InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

Inisialisasi FormatScheme dengan objek baru untuk menimpa FormatScheme dari InheritedTheme.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

Inisialisasi FormatScheme dengan objek baru untuk menimpa FormatScheme dari InheritedTheme.

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Data untuk menginisialisasi dari. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

Inisialisasi FormatScheme dengan objek baru untuk menimpa FormatScheme dari InheritedTheme. Dan menginisialisasi data objek baru ini dengan data dari FormatScheme milik InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```

Tetapkan ColorScheme, FontScheme, FormatScheme menjadi null untuk menonaktifkan setiap penimpaan dengan objek tema ini.