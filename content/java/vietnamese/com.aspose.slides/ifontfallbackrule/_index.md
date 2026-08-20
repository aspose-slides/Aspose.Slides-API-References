---
title: IFontFallBackRule
second_title: Aspose.Slides for Java API Reference
description: Đại diện cho quy tắc dự phòng phông chữ
type: docs
url: /vi/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Đại diện cho quy tắc dự phòng phông chữ
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Adds a new font(s) to the list of FallBack fonts. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Adds a new fonts to the list of FallBack fonts. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Get first index of continuous unicode range. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Get last index of continuous unicode range. |
| [getCount()](#getCount--) | Gets the number of fonts actually defined for range. |
| [get_Item(int index)](#get-Item-int-) | Gets the font name at the specified index. |
| [clear()](#clear--) | Removes all fonts from the list. |
| [remove(String fontName)](#remove-java.lang.String-) | Removes the first occurrence of a specific FallBack font from the list. |
| [removeAt(int index)](#removeAt-int-) | Removes the FallBack font at the specified index of the list. |
| [toArray()](#toArray--) | Creates and returns an array with all FallBack fonts for this rule. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Creates and returns an array with all FallBack fonts from the specified range in list. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Returns an index of the specified rule in the collection. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

Thêm phông chữ mới vào danh sách các phông FallBack.

--------------------

> ```
> //Tạo một thể hiện mới của FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Thêm một phông chữ thứ hai vào quy tắc 
>  newRule.addFallBackFonts("MS Gothic");
>  //Thêm phông chữ thứ ba và thứ tư vào quy tắc 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fontName | java.lang.String | Tên hoặc các tên phông chữ (được phân tách bằng dấu phẩy) cho FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

Thêm phông chữ mới vào danh sách các phông FallBack.

--------------------

> ```
> //Tạo một thể hiện mới của FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Thêm ba phông chữ khác vào quy tắc 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fontNames | java.lang.String[] | Tên hoặc các tên phông chữ (được phân tách bằng dấu phẩy) cho FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

Lấy chỉ mục đầu tiên của dải Unicode liên tục.

**Giá trị trả về:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

Lấy chỉ mục cuối cùng của dải Unicode liên tục.

**Giá trị trả về:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

Lấy số lượng phông chữ thực sự được định nghĩa cho dải.

**Giá trị trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

Lấy tên phông chữ tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả phông chữ khỏi danh sách.

### remove(String fontName) {#remove-java.lang.String-}
```
public abstract void remove(String fontName)
```

Xóa lần xuất hiện đầu tiên của một phông FallBack cụ thể khỏi danh sách.

--------------------

> ```
> // Tạo một quy tắc chứa danh sách các phông chữ.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Xóa Tahoma khỏi danh sách
>  newRule.remove("Tahoma");
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fontName | java.lang.String | Tên phông chữ cần xóa khỏi danh sách. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa phông FallBack tại chỉ mục đã chỉ định trong danh sách.

--------------------

> ```
> // Tạo một quy tắc chứa danh sách các phông chữ.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Xóa Tahoma khỏi danh sách
>  newRule.remove(2);
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên số 0 của phông chữ cần xóa. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

Tạo và trả về một mảng chứa tất cả các phông FallBack cho quy tắc này.

--------------------

> ```
> // Tạo một quy tắc chứa danh sách các phông chữ.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Lấy tất cả tên phông chữ dưới dạng mảng
>  String[] fontNames = newRule.toArray();
> ```


**Giá trị trả về:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

Tạo và trả về một mảng chứa tất cả các phông FallBack từ dải đã chỉ định trong danh sách.

--------------------

> ```
> // Tạo một quy tắc chứa danh sách các phông chữ.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Lấy hai tên phông chữ cuối cùng dưới dạng mảng
>  String[] fontNames = newRule.toArray(2,2);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| startIndex | int | Chỉ mục của phông chữ đầu tiên để thêm. |
| count | int | Số lượng phông chữ để thêm. |

**Giá trị trả về:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

Trả về chỉ mục của quy tắc đã chỉ định trong bộ sưu tập.

--------------------

> ```
> // Tạo một quy tắc chứa danh sách các phông chữ.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Lấy chỉ mục của Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fontName | java.lang.String | Tên phông chữ cần tìm. |

**Giá trị trả về:**
int - Chỉ mục của phông chữ hoặc -1 nếu không tìm thấy phông trong danh sách.