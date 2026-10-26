---
title: IOverrideThemeManager
second_title: Referensi API Aspose.Slides untuk Java
description: Menyediakan akses ke berbagai jenis tema yang ditimpa.
type: docs
url: /id/com.aspose.slides/ioverridethememanager/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

Menyediakan akses ke berbagai jenis tema yang ditimpa.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Menentukan apakah OverrideTheme menimpa tema efektif yang diwarisi atau tidak. |
| [getOverrideTheme()](#getOverrideTheme--) | Mengembalikan objek tema yang menimpa. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Mengembalikan objek tema yang menimpa. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

Menentukan apakah OverrideTheme menimpa tema efektif yang diwarisi atau tidak. Untuk mengaktifkan OverrideTheme untuk penimpaan gunakan metode OverrideTheme.Init*(). Untuk menonaktifkan OverrideTheme dari penimpaan gunakan metode OverrideTheme.Clear(). Boolean baca-saja.

**Mengembalikan:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

Mengembalikan objek tema yang menimpa. Baca/tulis [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Mengembalikan:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

Mengembalikan objek tema yang menimpa. Baca/tulis [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |