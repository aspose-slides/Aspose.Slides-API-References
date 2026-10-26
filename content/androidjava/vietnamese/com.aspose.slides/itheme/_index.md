---
title: ITheme
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một chủ đề.
type: docs
url: /vi/com.aspose.slides/itheme/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Đại diện cho một chủ đề.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Trả về bảng màu. |
| [getFontScheme()](#getFontScheme--) | Trả về bảng font. |
| [getFormatScheme()](#getFormatScheme--) | Trả về bảng định dạng hình dạng. |
| [getEffective()](#getEffective--) | Lấy dữ liệu chủ đề hiệu quả với kế thừa được áp dụng. |
### getColorScheme() {#getColorScheme--}
```
public abstract IColorScheme getColorScheme()
```

Trả về bảng màu. Chỉ đọc [IColorScheme](../../com.aspose.slides/icolorscheme).

**Trả về:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontScheme getFontScheme()
```

Trả về bảng font. Chỉ đọc [IFontScheme](../../com.aspose.slides/ifontscheme).

**Trả về:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatScheme getFormatScheme()
```

Trả về bảng định dạng hình dạng. Chỉ đọc [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Trả về:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getEffective() {#getEffective--}
```
public abstract IThemeEffectiveData getEffective()
```

Lấy dữ liệu chủ đề hiệu quả với kế thừa được áp dụng.

**Trả về:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - Một [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).