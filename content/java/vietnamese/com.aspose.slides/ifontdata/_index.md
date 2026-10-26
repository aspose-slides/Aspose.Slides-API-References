---
title: IFontData
second_title: Aspose.Slides for Java API Reference
description: Represents a font definition.
type: docs
url: /vi/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Biểu diễn một định nghĩa phông chữ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFontName()](#getFontName--) | Trả về tên phông chữ. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Trả về tên phông chữ, thay thế tham chiếu chủ đề bằng phông chữ thực tế được sử dụng. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Trả về tên phông chữ. Chỉ đọc String.

**Trả về:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```


Trả về tên phông chữ, thay thế tham chiếu chủ đề bằng phông chữ thực tế được sử dụng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Chủ đề mà tên phông chữ theo chủ đề sẽ được lấy. Tùy thuộc vào người gọi để cung cấp giá trị đúng. |

**Trả về:**
java.lang.String - Tên phông chữ.