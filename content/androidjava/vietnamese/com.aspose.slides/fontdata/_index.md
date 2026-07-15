---
title: FontData
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một định nghĩa phông chữ.
type: docs
url: /vi/com.aspose.slides/fontdata/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

Đại diện cho một định nghĩa phông chữ. Không thay đổi.
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Tạo một đối tượng FontData mới với tên phông chữ được chỉ định. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFontName()](#getFontName--) | Trả về tên phông chữ. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Trả về tên phông chữ, thay thế tham chiếu chủ đề bằng một phông chữ thực tế được sử dụng. |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem hai thể hiện FontData có bằng nhau không. |
| [hashCode()](#hashCode--) | Đóng vai trò như một hàm băm cho một kiểu nhất định, phù hợp để sử dụng trong các thuật toán băm và cấu trúc dữ liệu như bảng băm. |
| [toString()](#toString--) | Trả về biểu diễn chuỗi. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

Tạo một đối tượng FontData mới với tên phông chữ được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fontName | java.lang.String | Tên phông chữ. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

Trả về tên phông chữ. Đọc/ghi String.

**Trả về:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

Trả về tên phông chữ, thay thế tham chiếu chủ đề bằng một phông chữ thực tế được sử dụng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Chủ đề mà tên phông chữ theo chủ đề nên được lấy. Việc cung cấp giá trị đúng là trách nhiệm của người gọi. Xem [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Trả về:**
java.lang.String - Tên phông chữ.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Xác định xem hai thể hiện FontData có bằng nhau không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | FontData để so sánh với FontData hiện tại. |

**Trả về:**
boolean - **true** nếu FontData được chỉ định bằng với FontData hiện tại; nếu không, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Đóng vai trò như một hàm băm cho một kiểu nhất định, phù hợp để sử dụng trong các thuật toán băm và cấu trúc dữ liệu như bảng băm.

**Trả về:**
int - Mã băm của FontData.
### toString() {#toString--}
```
public String toString()
```

Trả về biểu diễn chuỗi.

**Trả về:**
java.lang.String - Biểu diễn chuỗi.