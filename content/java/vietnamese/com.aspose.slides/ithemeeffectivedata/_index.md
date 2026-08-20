---
title: IThemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective theme properties.
type: docs
url: /vi/com.aspose.slides/ithemeeffectivedata/
---```
public interface IThemeEffectiveData
```

Đối tượng bất biến chứa các thuộc tính chủ đề hiệu quả.

--------------------

Giao diện này được sử dụng cùng với giao diện [ITheme](../../com.aspose.slides/itheme) để trả về các giá trị định dạng hiệu quả có áp dụng kế thừa.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getColorScheme(Color styleColor)](#getColorScheme-java.awt.Color-) | Returns the color scheme. |
| [getFontScheme()](#getFontScheme--) | Returns the font scheme. |
| [getFormatScheme()](#getFormatScheme--) | Returns the shape format scheme. |
### getColorScheme(Color styleColor) {#getColorScheme-java.awt.Color-}
```
public abstract IColorSchemeEffectiveData getColorScheme(Color styleColor)
```

Trả về bảng màu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| styleColor | java.awt.Color | Color java.awt.Color |

**Trả về:**
[IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata) - bảng màu [IColorSchemeEffectiveData](../../com.aspose.slides/icolorschemeeffectivedata)
### getFontScheme() {#getFontScheme--}
```
public abstract IFontSchemeEffectiveData getFontScheme()
```

Trả về font scheme. Chỉ đọc [IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata).

**Trả về:**
[IFontSchemeEffectiveData](../../com.aspose.slides/ifontschemeeffectivedata)
### getFormatScheme() {#getFormatScheme--}
```
public abstract IFormatSchemeEffectiveData getFormatScheme()
```

Trả về shape format scheme. Chỉ đọc [IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata).

**Trả về:**
[IFormatSchemeEffectiveData](../../com.aspose.slides/iformatschemeeffectivedata)