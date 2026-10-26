---
title: BaseOverrideThemeManager
second_title: Tham chiếu API Aspose.Slides cho Java
description: Lớp cơ sở cho các lớp cung cấp quyền truy cập vào các loại chủ đề đã được ghi đè khác nhau.
type: docs
url: /vi/com.aspose.slides/baseoverridethememanager/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.BaseThemeManager](../../com.aspose.slides/basethememanager)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
```
public abstract class BaseOverrideThemeManager extends BaseThemeManager implements IOverrideThemeManager
```

Lớp cơ sở cho các lớp cung cấp quyền truy cập vào các loại chủ đề đã được ghi đè khác nhau.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getOverrideTheme()](#getOverrideTheme--) | Trả về đối tượng chủ đề ghi đè. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Trả về đối tượng chủ đề ghi đè. |
| [createThemeEffective()](#createThemeEffective--) | Trả về đối tượng chủ đề. |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Xác định xem OverrideTheme có ghi đè chủ đề hiệu quả kế thừa hay không. |
| [applyColorScheme(IExtraColorScheme scheme)](#applyColorScheme-com.aspose.slides.IExtraColorScheme-) | Áp dụng bảng màu phụ trợ cho một slide. |
### getOverrideTheme() {#getOverrideTheme--}
```
public final IOverrideTheme getOverrideTheme()
```

Trả về đối tượng chủ đề ghi đè. Đọc/ghi [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Giá trị trả về:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public final void setOverrideTheme(IOverrideTheme value)
```

Trả về đối tượng chủ đề ghi đè. Đọc/ghi [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Trả về đối tượng chủ đề.

**Giá trị trả về:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public final boolean isOverrideThemeEnabled()
```

Xác định xem OverrideTheme có ghi đè chủ đề hiệu quả kế thừa hay không. Để bật OverrideTheme cho việc ghi đè, sử dụng các phương thức OverrideTheme.Init*(). Để tắt OverrideTheme khỏi việc ghi đè, sử dụng phương thức OverrideTheme.Clear(). Chỉ đọc boolean.

**Giá trị trả về:**
boolean
### applyColorScheme(IExtraColorScheme scheme) {#applyColorScheme-com.aspose.slides.IExtraColorScheme-}
```
public final void applyColorScheme(IExtraColorScheme scheme)
```

Áp dụng bảng màu phụ trợ cho một slide.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| scheme | [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme) | Đối tượng [IExtraColorScheme](../../com.aspose.slides/iextracolorscheme). |