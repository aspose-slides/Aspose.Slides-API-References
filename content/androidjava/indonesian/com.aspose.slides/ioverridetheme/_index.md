---
title: IOverrideTheme
second_title: Aspose.Slides untuk Android melalui Referensi API Java
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

| Metode | Deskripsi |
| --- | --- |
| [isEmpty()](#isEmpty--) | Nilai true berarti bahwa ColorScheme, FontScheme, FormatScheme adalah null dan setiap penimpaan dengan objek tema ini dinonaktifkan. |
| [initColorScheme()](#initColorScheme--) | Nilai true berarti bahwa ColorScheme, FontScheme, FormatScheme adalah null dan setiap penimpaan dengan objek tema ini dinonaktifkan. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | Nilai true berarti bahwa ColorScheme, FontScheme, FormatScheme adalah null dan setiap penimpaan dengan objek tema ini dinonaktifkan. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | Nilai true berarti bahwa ColorScheme, FontScheme, FormatScheme adalah null dan setiap penimpaan dengan objek tema ini dinonaktifkan. |
| [initFontScheme()](#initFontScheme--) | Nilai true berarti bahwa ColorScheme, FontScheme, FormatScheme adalah null dan setiap penimpaan dengan objek tema ini dinonaktifkan. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | Nilai true berarti bahwa ColorScheme, FontScheme, FormatScheme adalah null dan setiap penimpaan dengan objek tema ini dinonaktifkan. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | Nilai true berarti bahwa ColorScheme, FontScheme, FormatScheme adalah null dan setiap penimpaan dengan objek tema ini dinonaktifkan. |
| [initFormatScheme()](#initFormatScheme--) | Nilai true berarti bahwa ColorScheme, FontScheme, FormatScheme adalah null dan setiap penimpaan dengan objek tema ini dinonaktifkan. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | Nilai true berarti bahwa ColorScheme, FontScheme, FormatScheme adalah null dan setiap penimpaan dengan objek tema ini dinonaktifkan. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | Nilai true berarti bahwa ColorScheme, FontScheme, FormatScheme adalah null dan setiap penimpaan dengan objek tema ini dinonaktifkan. |
| [clear()](#clear--) | Set ColorScheme, FontScheme, FormatScheme to null to disable any overriding with this theme object. |

### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

Nilai true berarti bahwa ColorScheme, FontScheme, FormatScheme adalah null dan setiap penimpaan dengan objek tema ini dinonaktifkan. Boolean hanya-baca.

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
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | Data untuk diinisialisasi dari. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

Inisialisasi ColorScheme dengan objek baru untuk menimpa ColorScheme dari InheritedTheme. Dan menginisialisasi data objek baru ini dengan data dari ColorScheme dari InheritedTheme.

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
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | Data untuk diinisialisasi dari. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

Inisialisasi FontScheme dengan objek baru untuk menimpa FontScheme dari InheritedTheme. Dan menginisialisasi data objek baru ini dengan data dari FontScheme dari InheritedTheme.

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
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | Data untuk diinisialisasi dari. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

Inisialisasi FormatScheme dengan objek baru untuk menimpa FormatScheme dari InheritedTheme. Dan menginisialisasi data objek baru ini dengan data dari FormatScheme dari InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```

Set ColorScheme, FontScheme, FormatScheme to null to disable any overriding with this theme object.