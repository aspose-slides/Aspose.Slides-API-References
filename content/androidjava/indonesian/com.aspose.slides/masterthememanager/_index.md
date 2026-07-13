---
title: MasterThemeManager
second_title: Referensi API Java Aspose.Slides untuk Android
description: Menyediakan akses ke tema master presentasi.
type: docs
url: /id/com.aspose.slides/masterthememanager/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

Menyediakan akses ke tema master presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Mengembalikan objek tema yang menimpa. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | Mengembalikan objek tema yang menimpa. |
| [createThemeEffective()](#createThemeEffective--) | Mengembalikan objek tema. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Menentukan apakah OverrideTheme menimpa tema efektif yang diwarisi (Presentation.MasterTheme) atau tidak. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | Menentukan apakah OverrideTheme menimpa tema efektif yang diwarisi (Presentation.MasterTheme) atau tidak. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Menerapkan skema warna tambahan ke slide. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```

Mengembalikan objek tema yang menimpa. Baca/tulis [IMasterTheme](../../com.aspose.slides/imastertheme).

**Mengembalikan:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```

Mengembalikan objek tema yang menimpa. Baca/tulis [IMasterTheme](../../com.aspose.slides/imastertheme).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |

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

Menentukan apakah OverrideTheme menimpa tema efektif yang diwarisi (Presentation.MasterTheme) atau tidak. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```

Menentukan apakah OverrideTheme menimpa tema efektif yang diwarisi (Presentation.MasterTheme) atau tidak. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Menerapkan skema warna tambahan ke slide.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) objek. |