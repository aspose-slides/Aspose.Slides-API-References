---
title: IThemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Đối tượng không thay đổi chứa các thuộc tính chủ đề hiệu lực.
type: docs
url: /vi/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Đối tượng không thay đổi chứa các thuộc tính chủ đề hiệu lực.

--------------------

Giao diện này được sử dụng cùng với giao diện [ITheme](../../com.aspose.slides/itheme) để trả về các giá trị định dạng hiệu lực có áp dụng kế thừa.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getColorScheme(Integer styleColor)](#getColorScheme-java.lang.Integer-) | Trả về bảng màu. |
| [getFontScheme()](#getFontScheme--) | Trả về bảng phông chữ. |
| [getFormatScheme()](#getFormatScheme--) | Trả về bảng định dạng hình dạng. |
### getColorScheme(Integer styleColor) {#getColorScheme-java.lang.Integer-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Integer styleColor)
```


Trả về bảng màu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| styleColor | java.lang.Integer | Màu java.lang.Integer |

**Trả về:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - Bảng màu [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```


Trả về bảng phông chữ. Chỉ đọc [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Trả về:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```


Trả về bảng định dạng hình dạng. Chỉ đọc [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Trả về:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)