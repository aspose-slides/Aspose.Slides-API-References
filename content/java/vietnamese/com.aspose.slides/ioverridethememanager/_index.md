---
title: IOverrideThemeManager
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cung cấp quyền truy cập vào các loại giao diện đã ghi đè khác nhau.
type: docs
url: /vi/com.aspose.slides/ioverridethememanager/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IThemeManager](../../com.aspose.slides/ithememanager)
```
public interface IOverrideThemeManager extends IThemeManager
```

Cung cấp quyền truy cập vào các loại giao diện đã ghi đè khác nhau.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [isOverrideThemeEnabled()](#isOverrideThemeEnabled--) | Xác định liệu OverrideTheme có ghi đè giao diện hiệu quả kế thừa hay không. |
| [getOverrideTheme()](#getOverrideTheme--) | Trả về đối tượng giao diện ghi đè. |
| [setOverrideTheme(IOverrideTheme value)](#setOverrideTheme-com.aspose.slides.IOverrideTheme-) | Trả về đối tượng giao diện ghi đè. |
### isOverrideThemeEnabled() {#isOverrideThemeEnabled--}
```
public abstract boolean isOverrideThemeEnabled()
```


Xác định liệu OverrideTheme có ghi đè giao diện hiệu quả kế thừa hay không. Để bật OverrideTheme để ghi đè, sử dụng các phương thức OverrideTheme.Init\*() . Để tắt OverrideTheme khỏi việc ghi đè, sử dụng phương thức OverrideTheme.Clear() . Boolean chỉ đọc.

**Trả về:**
boolean
### getOverrideTheme() {#getOverrideTheme--}
```
public abstract IOverrideTheme getOverrideTheme()
```


Trả về đối tượng giao diện ghi đè. Đọc/ghi [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Trả về:**
[IOverrideTheme](../../com.aspose.slides/ioverridetheme)
### setOverrideTheme(IOverrideTheme value) {#setOverrideTheme-com.aspose.slides.IOverrideTheme-}
```
public abstract void setOverrideTheme(IOverrideTheme value)
```


Trả về đối tượng giao diện ghi đè. Đọc/ghi [IOverrideTheme](../../com.aspose.slides/ioverridetheme).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IOverrideTheme](../../com.aspose.slides/ioverridetheme) |  |