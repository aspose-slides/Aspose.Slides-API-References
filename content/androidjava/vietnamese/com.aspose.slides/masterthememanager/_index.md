---
title: MasterThemeManager
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Cung cấp quyền truy cập vào chủ đề master của bản trình chiếu.
type: docs
url: /vi/com.aspose.slides/masterthememanager/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
```
public class MasterThemeManager extends BaseThemeManager implements IMasterThemeManager
```

Cung cấp quyền truy cập vào chủ đề master của bản trình chiếu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Trả về đối tượng chủ đề ghi đè. |
| [setOverrideTheme(IMasterTheme value)](#setOverrideTheme-com.aspose.slides.IMasterTheme-) | Trả về đối tượng chủ đề ghi đè. |
| [createThemeEffective()](#createThemeEffective--) | Trả về đối tượng chủ đề. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Xác định xem OverrideTheme có ghi đè chủ đề hiệu lực kế thừa (Presentation.MasterTheme) hay không. |
| [setOverrideThemeEnabled(boolean value)](#setOverrideThemeEnabled-boolean-) | Xác định xem OverrideTheme có ghi đè chủ đề hiệu lực kế thừa (Presentation.MasterTheme) hay không. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Áp dụng bảng màu phụ thêm cho một slide. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IMasterTheme getOverrideTheme()
```

Trả về đối tượng chủ đề ghi đè. Đọc/ghi [IMasterTheme](../../com.aspose.slides/imastertheme).

**Trả về:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### setOverrideTheme(IMasterTheme value) {#setOverrideTheme-com.aspose.slides.IMasterTheme-}
```
public final void setOverrideTheme(IMasterTheme value)
```

Trả về đối tượng chủ đề ghi đè. Đọc/ghi [IMasterTheme](../../com.aspose.slides/imastertheme).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IMasterTheme](../../com.aspose.slides/imastertheme) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Trả về đối tượng chủ đề.

**Trả về:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

Xác định xem OverrideTheme có ghi đè chủ đề hiệu lực kế thừa (Presentation.MasterTheme) hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setOverrideThemeEnabled(boolean value) {#setOverrideThemeEnabled-boolean-}
```
public final void setOverrideThemeEnabled(boolean value)
```

Xác định xem OverrideTheme có ghi đè chủ đề hiệu lực kế thừa (Presentation.MasterTheme) hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Áp dụng bảng màu phụ thêm cho một slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) đối tượng. |