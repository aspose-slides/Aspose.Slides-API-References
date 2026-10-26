---
title: Fonts
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Bộ sưu tập phông chữ.
type: docs
url: /vi/com.aspose.slides/fonts/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

Bộ sưu tập phông chữ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Trả về một từ điển của tất cả các định nghĩa phông chữ script trong bản trình chiếu. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Lấy tên phông chữ liên kết với một thẻ script cụ thể từ giao diện trình bày. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Gán một tên phông chữ cho một thẻ script cụ thể, xác định cách văn bản của script đó sẽ được hiển thị trong bản trình chiếu. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Xóa cài đặt phông chữ liên kết với một thẻ script cụ thể khỏi bộ sưu tập phông chữ của giao diện. |
| [getLatinFont()](#getLatinFont--) | Trả về hoặc đặt phông chữ Latin. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Trả về hoặc đặt phông chữ Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Trả về hoặc đặt phông chữ Đông Á. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Trả về hoặc đặt phông chữ Đông Á. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Trả về hoặc đặt phông chữ script phức tạp. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Trả về hoặc đặt phông chữ script phức tạp. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Trả về một từ điển của tất cả các định nghĩa phông chữ script trong bản trình chiếu.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```

**Trả về:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Một từ điển ánh xạ mã script tới tên phông chữ.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```

Lấy tên phông chữ liên kết với một thẻ script cụ thể từ giao diện trình bày.

--------------------

> ```
> Ví dụ này minh họa cách lấy phông chữ được gán cho script Cyrillic trong giao diện trình bày.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
>  ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| script | java.lang.String | Mã script BCP-47 (ví dụ: "Latn", "Cyrl", "Jpan") được sử dụng để xác định một hệ thống viết. |

**Trả về:**
java.lang.String - Tên phông chữ được sử dụng cho script đã chỉ định, hoặc  null  nếu script chưa được định nghĩa.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

Gán một tên phông chữ cho một thẻ script cụ thể, xác định cách văn bản của script đó sẽ được hiển thị trong bản trình chiếu.

--------------------

> ```
> Ví dụ này cho thấy cách đặt phông chữ cho script Arabic thành "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| script | java.lang.String | Mã script BCP-47 (ví dụ: "Arab", "Hebr", "Hans") xác định hệ thống viết. |
| fontName | java.lang.String | Tên phông chữ sẽ được gán cho script đã chỉ định. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

Xóa cài đặt phông chữ liên kết với một thẻ script cụ thể khỏi bộ sưu tập phông chữ của giao diện.

--------------------

> ```
> Ví dụ này minh họa cách xóa ánh xạ phông chữ cho script Hebrew:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| script | java.lang.String | Mã script BCP-47 mà cài đặt phông chữ của nó cần được xóa. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Trả về hoặc đặt phông chữ Latin. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Trả về hoặc đặt phông chữ Latin. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Trả về hoặc đặt phông chữ Đông Á. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Trả về hoặc đặt phông chữ Đông Á. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Trả về hoặc đặt phông chữ script phức tạp. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Trả về hoặc đặt phông chữ script phức tạp. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |