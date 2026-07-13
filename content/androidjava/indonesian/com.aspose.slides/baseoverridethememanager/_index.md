---
title: BaseOverrideThemeManager
second_title: Referensi API Java Aspose.Slides untuk Android
description: Kelas dasar untuk kelas yang menyediakan akses ke berbagai jenis tema yang ditimpa.
type: docs
url: /id/com.aspose.slides/baseoverridethememanager/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Kelas dasar untuk kelas yang menyediakan akses ke berbagai jenis tema yang ditimpa.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Mengembalikan objek tema yang ditimpa. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Mengembalikan objek tema yang ditimpa. |
| [createThemeEffective()](#createThemeEffective--) | Mengembalikan objek tema. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Menentukan apakah OverrideTheme menggantikan tema efektif yang diwarisi atau tidak. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Menerapkan skema warna tambahan ke slide. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```


Mengembalikan objek tema yang ditimpa. Baca/tulis [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Mengembalikan:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```


Mengembalikan objek tema yang ditimpa. Baca/tulis [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


Mengembalikan objek tema.

**Mengembalikan:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```


Menentukan apakah OverrideTheme menggantikan tema efektif yang diwarisi atau tidak. Untuk mengaktifkan OverrideTheme untuk penimpaan gunakan metode OverrideTheme.Init*(). Untuk menonaktifkan OverrideTheme dari penimpaan gunakan metode OverrideTheme.Clear(). Baca-saja boolean.

**Mengembalikan:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```


Menerapkan skema warna tambahan ke slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | Objek [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme). |