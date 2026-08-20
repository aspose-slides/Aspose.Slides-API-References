---
title: IFonts
second_title: Aspose.Slides for Java API Reference
description: Represents fonts collection.
type: docs
url: /vi/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Biểu diễn bộ sưu tập phông chữ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Trả về hoặc đặt phông Latin. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Trả về hoặc đặt phông Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | Trả về hoặc đặt phông East Asian. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Trả về hoặc đặt phông East Asian. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Trả về hoặc đặt phông complex script. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Trả về hoặc đặt phông complex script. |
| [getScriptFontMap()](#getScriptFontMap--) | Trả về một từ điển của tất cả các định nghĩa phông script trong bản trình chiếu. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Lấy tên phông liên kết với một thẻ script cụ thể từ theme của bản trình chiếu. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Gán tên phông cho một thẻ script cụ thể, xác định cách văn bản của script đó sẽ được hiển thị trong bản trình chiếu. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Xóa cài đặt phông chữ liên kết với một thẻ script cụ thể khỏi bộ sưu tập phông chữ của theme. |
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

Trả về hoặc đặt phông East Asian. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Trả về hoặc đặt phông East Asian. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Trả về hoặc đặt phông complex script. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Trả về hoặc đặt phông complex script. Đọc/ghi [IFontData](../../com.aspose.slides/ifontdata).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Trả về một từ điển của tất cả các định nghĩa phông script trong bản trình chiếu.

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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - A dictionary mapping script codes to font names.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

Lấy tên phông liên kết với một thẻ script cụ thể từ theme của bản trình chiếu.

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
| script | java.lang.String | Mã script BCP-47 (ví dụ: "Latn", "Cyrl", "Jpan") được sử dụng để xác định hệ thống viết. |

**Trả về:**
java.lang.String - Tên phông chữ được sử dụng cho script đã chỉ định, hoặc  null  nếu script không được định nghĩa.
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

Xóa cài đặt phông chữ liên kết với một thẻ script cụ thể khỏi bộ sưu tập phông chữ của theme.

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