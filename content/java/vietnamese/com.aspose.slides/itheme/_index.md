---
title: ITheme
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một chủ đề.
type: docs
url: /vi/com.aspose.slides/itheme/
---
**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
```
public interface ITheme extends IPresentationComponent
```

Biểu diễn một chủ đề.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Trả về bảng màu. |
| [getFontScheme()](#getFontScheme--) | Trả về bảng phông chữ. |
| [getFormatScheme()](#getFormatScheme--) | Trả về bảng định dạng hình dạng. |
| [getEffective()](#getEffective--) | Lấy dữ liệu giao diện thực tế với kế thừa đã được áp dụng. |
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


Trả về bảng phông chữ. Chỉ đọc [IFontScheme](../../com.aspose.slides/ifontscheme).

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


Lấy dữ liệu giao diện thực tế với kế thừa đã được áp dụng.

**Trả về:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) - Một [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).