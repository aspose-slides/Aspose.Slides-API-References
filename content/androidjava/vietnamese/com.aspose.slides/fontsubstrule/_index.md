---
title: FontSubstRule
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho thông tin thay thế phông chữ
type: docs
url: /vi/com.aspose.slides/fontsubstrule/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

Đại diện cho thông tin thay thế phông chữ
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Tạo một thể hiện mới. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Tạo một thể hiện mới. |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Phông chữ cần thay thế. |
| [getDestFont()](#getDestFont--) | Phông chữ dùng để thay thế. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Quy tắc áp dụng cho việc thay thế. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


Tạo một thể hiện mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Phông chữ nguồn. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Phông chữ đích. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


Tạo một thể hiện mới.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Phông chữ nguồn. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Phông chữ đích. |
| fontSubstRule | int | Quy tắc thay thế phông chữ. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


Phông chữ cần thay thế. Chỉ đọc [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


Phông chữ dùng để thay thế. Chỉ đọc [IFontData](../../com.aspose.slides/ifontdata).

**Trả về:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


Quy tắc áp dụng cho việc thay thế. Chỉ đọc [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Trả về:**
int