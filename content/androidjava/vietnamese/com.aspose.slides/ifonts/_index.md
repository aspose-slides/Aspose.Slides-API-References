---
title: IFonts
second_title: Aspose.Slides for Android via Java API Reference
description: Represents fonts collection.
type: docs
url: /vi/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Biểu diễn tập hợp phông chữ.
## Phương thức

| Method | Description |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Trả về hoặc đặt phông Latin. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Trả về hoặc đặt phông Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Trả về hoặc đặt phông Asian phía Đông. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Trả về hoặc đặt phông Asian phía Đông. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Trả về hoặc đặt phông script phức tạp. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Trả về hoặc đặt phông script phức tạp. |
| [getScriptFontMap()](#getScriptFontMap--) | Trả về một từ điển chứa tất cả các định nghĩa phông script trong bản trình chiếu. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Lấy tên phông chữ liên kết với một thẻ script cụ thể từ giao diện bản trình chiếu. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Gán tên phông cho một thẻ script cụ thể, xác định cách văn bản của script đó sẽ được hiển thị trong bản trình chiếu. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Xóa cài đặt phông chữ liên quan đến một thẻ script cụ thể khỏi bộ sưu tập phông của giao diện. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Trả về hoặc đặt phông Latin. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Trả về hoặc đặt phông Latin. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Trả về hoặc đặt phông Asian phía Đông. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Trả về hoặc đặt phông Asian phía Đông. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Trả về hoặc đặt phông script phức tạp. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Trả về hoặc đặt phông script phức tạp. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Trả về một từ điển chứa tất cả các định nghĩa phông script trong bản trình chiếu.

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
public abstract String getScriptFont(String script)
```

Lấy tên phông chữ liên kết với một thẻ script cụ thể từ giao diện bản trình chiếu.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| script | java.lang.String | Mã script BCP-47 (ví dụ: "Latn", "Cyrl", "Jpan") dùng để xác định hệ thống viết. |

**Trả về:**
java.lang.String - Tên phông được sử dụng cho script đã chỉ định, hoặc  null  nếu script không được định nghĩa.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

Gán tên phông cho một thẻ script cụ thể, xác định cách văn bản của script đó sẽ được hiển thị trong bản trình chiếu.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| script | java.lang.String | Mã script BCP-47 (ví dụ: "Arab", "Hebr", "Hans") xác định hệ thống viết. |
| fontName | java.lang.String | Tên phông chữ sẽ gán cho script đã chỉ định. |
### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```

Xóa cài đặt phông chữ liên quan đến một thẻ script cụ thể khỏi bộ sưu tập phông của giao diện.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| script | java.lang.String | Mã script BCP-47 mà cài đặt phông chữ cần được xóa. |