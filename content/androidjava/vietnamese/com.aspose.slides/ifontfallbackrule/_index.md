---
title: IFontFallBackRule
second_title: Aspose.Slides for Android via Java API Reference
description: Biểu diễn quy tắc thay thế phông chữ
type: docs
url: /vi/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Biểu diễn quy tắc thay thế phông chữ
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Thêm phông chữ mới vào danh sách phông chữ FallBack. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Thêm phông chữ mới vào danh sách phông chữ FallBack. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Lấy chỉ mục đầu tiên của dải Unicode liên tục. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Lấy chỉ mục cuối cùng của dải Unicode liên tục. |
| [getCount()](#getCount--) | Lấy số lượng phông chữ thực sự được định nghĩa cho dải. |
| [get_Item(int index)](#get-Item-int-) | Lấy tên phông chữ tại chỉ mục đã chỉ định. |
| [clear()](#clear--) | Xóa tất cả phông chữ khỏi danh sách. |
| [remove(String fontName)](#remove-java.lang.String-) | Xóa lần xuất hiện đầu tiên của một phông chữ FallBack cụ thể khỏi danh sách. |
| [removeAt(int index)](#removeAt-int-) | Xóa phông chữ FallBack tại chỉ mục đã chỉ định trong danh sách. |
| [toArray()](#toArray--) | Tạo và trả về một mảng chứa tất cả phông chữ FallBack cho quy tắc này. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Tạo và trả về một mảng chứa tất cả phông chữ FallBack từ dải đã chỉ định trong danh sách. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Trả về chỉ mục của quy tắc được chỉ định trong bộ sưu tập. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

Thêm phông chữ mới vào danh sách phông chữ FallBack.

--------------------

> ```
> //Tạo một thể hiện mới của FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Thêm phông chữ thứ hai vào quy tắc 
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

Thêm phông chữ mới vào danh sách phông chữ FallBack.

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

**Trả về:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

Lấy chỉ mục cuối cùng của dải Unicode liên tục.

**Trả về:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

Lấy số lượng phông chữ thực sự được định nghĩa cho dải.

**Trả về:**
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

**Trả về:**
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

Xóa lần xuất hiện đầu tiên của một phông chữ FallBack cụ thể khỏi danh sách.

--------------------

> ```
> // Tạo một quy tắc chứa danh sách các phông chữ.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Xóa Tahoma khỏi danh sách
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

Xóa phông chữ FallBack tại chỉ mục đã chỉ định trong danh sách.

--------------------

> ```
> // Tạo một quy tắc chứa danh sách các phông chữ.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Xóa Tahoma khỏi danh sách
>  newRule.remove(2);
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên zero của phông chữ cần xóa. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

Tạo và trả về một mảng chứa tất cả phông chữ FallBack cho quy tắc này.

--------------------

> ```
> // Tạo một quy tắc chứa danh sách các phông chữ.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Lấy tất cả tên phông chữ dưới dạng mảng
>  String[] fontNames = newRule.toArray();
> ```

**Trả về:**
java.lang.String[] - Mảng các String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

Tạo và trả về một mảng chứa tất cả phông chữ FallBack từ dải đã chỉ định trong danh sách.

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
| count | int | Số lượng phông chữ cần thêm. |

**Trả về:**
java.lang.String[] - Mảng các String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

Trả về chỉ mục của quy tắc được chỉ định trong bộ sưu tập.

--------------------

> ```
> // Tạo một quy tắc chứa danh sách các phông chữ.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Lấy chỉ mục của Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fontName | java.lang.String | Tên phông chữ cần tìm. |

**Trả về:**
int - Chỉ mục của một phông chữ hoặc -1 nếu không tìm thấy phông chữ trong danh sách.