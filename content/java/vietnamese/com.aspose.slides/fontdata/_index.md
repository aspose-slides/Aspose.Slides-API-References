---
title: FontData
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu thị một định nghĩa phông chữ.
type: docs
url: /vi/com.aspose.slides/fontdata/
---
**Kế thừa:**
java.lang.Object

**Tất cả giao diện được triển khai:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

Biểu diễn một định nghĩa phông chữ. Không thay đổi.
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Tạo một đối tượng FontData mới với tên phông chữ được chỉ định. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFontName()](#getFontName--) | Trả về tên phông chữ. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Trả về tên phông chữ, thay thế tham chiếu chủ đề bằng phông chữ thực tế được sử dụng. |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem hai đối tượng FontData có bằng nhau không. |
| [hashCode()](#hashCode--) | Đóng vai trò là hàm băm cho một kiểu cụ thể, phù hợp để sử dụng trong các thuật toán băm và cấu trúc dữ liệu như bảng băm. |
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

**Giá trị trả về:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

Trả về tên phông chữ, thay thế tham chiếu chủ đề bằng phông chữ thực tế được sử dụng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Chủ đề từ đó tên phông chữ theo chủ đề nên được lấy. Việc cung cấp giá trị đúng phụ thuộc vào người gọi. Xem [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Giá trị trả về:**
java.lang.String - Tên phông chữ.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Xác định xem hai đối tượng FontData có bằng nhau không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | Đối tượng FontData để so sánh với FontData hiện tại. |

**Giá trị trả về:**
boolean - **true** nếu FontData được chỉ định bằng với FontData hiện tại; ngược lại, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Đóng vai trò là hàm băm cho một kiểu cụ thể, phù hợp để sử dụng trong các thuật toán băm và cấu trúc dữ liệu như bảng băm.

**Giá trị trả về:**
int - Mã băm của FontData.
### toString() {#toString--}
```
public String toString()
```

Trả về biểu diễn chuỗi.

**Giá trị trả về:**
java.lang.String - Đại diện chuỗi.