---
title: FontsLoader
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Lớp để tải phông chữ tùy chỉnh do người dùng xác định.
type: docs
url: /vi/com.aspose.slides/fontsloader/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

Lớp để tải phông chữ tùy chỉnh do người dùng xác định. Nên được sử dụng trước khi tạo bất kỳ đối tượng trình chiếu nào.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Thêm các thư mục bổ sung để tìm phông chữ. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Thêm phông chữ từ dữ liệu nhị phân |
| [getFontFolders()](#getFontFolders--) | Lấy các thư mục phông chữ. |
| [clearCache()](#clearCache--) | Giải phóng tất cả phông chữ tùy chỉnh do người dùng xác định |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```

Thêm các thư mục bổ sung để tìm phông chữ.

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // các thư mục để tìm phông chữ
>  String[] folders = new String[] { dataDir };
>  // Tải các phông chữ từ thư mục tùy chỉnh
>  FontsLoader.loadExternalFonts(folders);
>  // Thực hiện một số công việc và render bài trình bày/slide
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // Xóa bộ nhớ đệm phông chữ
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| directories | java.lang.String[] | Các thư mục để đọc phông chữ bổ sung. |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```

Thêm phông chữ từ dữ liệu nhị phân

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| data | byte[] | Dữ liệu phông chữ |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```

Lấy các thư mục phông chữ. Trả về các thư mục đã được thêm bằng phương thức LoadExternalFonts cũng như các thư mục phông chữ hệ thống

**Giá trị trả về:**
java.lang.String[] - mảng chứa tên thư mục
### clearCache() {#clearCache--}
```
public static void clearCache()
```

Giải phóng tất cả phông chữ tùy chỉnh do người dùng xác định

--------------------

Phương thức này cần xóa bộ nhớ đệm với các phông chữ tùy chỉnh do người dùng xác định.