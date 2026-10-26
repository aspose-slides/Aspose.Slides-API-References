---
title: IOverrideThemeManager
second_title: Aspose.Slides untuk Android melalui Referensi API Java
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
| [getOverrideTheme()](#getOverrideTheme--) | Mengembalikan objek tema yang ditimpa. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Mengembalikan objek tema yang ditimpa. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```


Menentukan apakah OverrideTheme menimpa tema efektif yang diwarisi atau tidak. Untuk mengaktifkan OverrideTheme untuk penimpaan gunakan OverrideTheme.Init\*() metode. Untuk menonaktifkan OverrideTheme dari penimpaan gunakan OverrideTheme.Clear() metode. Boolean hanya-baca.

**Returns:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```


Mengembalikan objek tema yang ditimpa. Baca/tulis [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Returns:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```


Mengembalikan objek tema yang ditimpa. Baca/tulis [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |