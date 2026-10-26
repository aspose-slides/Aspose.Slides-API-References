---
title: IFontData
second_title: Aspose.Slides for Android via Java API Reference
description: Đại diện cho một định nghĩa phông chữ.
type: docs
url: /vi/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Đại diện cho một định nghĩa phông chữ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFontName()](#getFontName--) | Trả về tên phông chữ. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Trả về tên phông chữ, thay thế tham chiếu chủ đề bằng phông chữ thực tế được sử dụng. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

Trả về tên phông chữ. Chuỗi chỉ đọc.

### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

Trả về tên phông chữ, thay thế tham chiếu chủ đề bằng phông chữ thực tế được sử dụng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Chủ đề mà từ đó tên phông chữ có chủ đề sẽ được lấy. Việc cung cấp giá trị đúng là trách nhiệm của người gọi. |

**Trả về:**
java.lang.String - Tên phông chữ.