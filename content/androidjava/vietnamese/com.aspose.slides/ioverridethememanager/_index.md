---
title: IOverrideThemeManager
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Cung cấp quyền truy cập vào các loại chủ đề đã được ghi đè khác nhau.
type: docs
url: /vi/com.aspose.slides/ioverridethememanager/
---
**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

Cung cấp quyền truy cập vào các loại chủ đề đã được ghi đè khác nhau.
## Phương thức

| Method | Mô tả |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Xác định xem OverrideTheme có ghi đè chủ đề hiệu lực được kế thừa hay không. |
| [getOverrideTheme()](#getOverrideTheme--) | Trả về đối tượng chủ đề đang ghi đè. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Trả về đối tượng chủ đề đang ghi đè. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```

Xác định xem OverrideTheme có ghi đè chủ đề hiệu lực được kế thừa hay không. Để bật OverrideTheme cho việc ghi đè, sử dụng các phương thức OverrideTheme.Init\*(). Để tắt OverrideTheme khỏi việc ghi đè, sử dụng phương thức OverrideTheme.Clear(). Boolean chỉ đọc.

**Trả về:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```

Trả về đối tượng chủ đề đang ghi đè. Đọc/ghi [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Trả về:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```

Trả về đối tượng chủ đề đang ghi đè. Đọc/ghi [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |