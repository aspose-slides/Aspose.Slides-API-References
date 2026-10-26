---
title: FontFallBackRule
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu thị quy tắc dự phòng phông chữ
type: docs
url: /vi/com.aspose.slides/fontfallbackrule/
---
**Kế thừa:**  
java.lang.Object

**Tất cả giao diện được triển khai:**  
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)  
```
public class FontFallBackRule implements IFontFallBackRule
```

Biểu thị quy tắc dự phòng phông chữ
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Tạo một thể hiện mới. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Tạo một thể hiện mới. |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Thêm một (các) phông chữ mới vào danh sách phông chữ FallBack. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Thêm một (các) phông chữ mới vào danh sách phông chữ FallBack. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Lấy chỉ mục đầu tiên của phạm vi unicode liên tục. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Lấy chỉ mục đầu tiên của phạm vi unicode liên tục. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Lấy chỉ mục cuối cùng của phạm vi unicode liên tục. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Lấy chỉ mục cuối cùng của phạm vi unicode liên tục. |
| [getCount()](#getCount--) | Lấy số lượng phông chữ thực sự được định nghĩa cho phạm vi. |
| [get_Item(int index)](#get-Item-int-) | Lấy tên phông chữ tại chỉ mục được chỉ định. |
| [clear()](#clear--) | Xóa tất cả phông chữ khỏi danh sách. |
| [remove(String fontName)](#remove-java.lang.String-) | Xóa lần xuất hiện đầu tiên của một phông chữ FallBack cụ thể khỏi danh sách. |
| [removeAt(int index)](#removeAt-int-) | Xóa phông chữ FallBack tại chỉ mục được chỉ định trong danh sách. |
| [toArray()](#toArray--) | Tạo và trả về một mảng chứa tất cả phông chữ FallBack cho quy tắc này. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Tạo và trả về một mảng chứa tất cả phông chữ FallBack từ phạm vi được chỉ định trong danh sách. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Trả về chỉ mục của quy tắc được chỉ định trong tập hợp. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```

Tạo một thể hiện mới.

--------------------

> ```
> // Tạo một thể hiện mới của FantFallBackRule với một phông chữ.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Tạo một thể hiện mới của FantFallBackRule với nhiều phông chữ.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| startIndex | long | Chỉ mục bắt đầu của phạm vi unicode |
| endIndex | long | Chỉ mục kết thúc của phạm vi unicode |
| fontNames | java.lang.String | Tên hoặc các tên phông chữ (được phân tách bằng dấu phẩy) cho FallBack |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```

Tạo một thể hiện mới.

--------------------

> ```
> // Tạo một thể hiện mới của FantFallBackRule với hai phông chữ
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Tạo một thể hiện mới của FantFallBackRule với nhiều phông chữ.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| startIndex | long | Chỉ mục bắt đầu của phạm vi unicode |
| endIndex | long | Chỉ mục kết thúc của phạm vi unicode |
| fontNames | java.lang.String[] | Tên hoặc các tên phông chữ (được phân tách bằng dấu phẩy) cho FallBack |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```

Thêm một (các) phông chữ mới vào danh sách phông chữ FallBack.

--------------------

> ```
> // Tạo một thể hiện mới của FontFallBackRule
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
public final void addFallBackFonts(String[] fontNames)
```

Thêm một (các) phông chữ mới vào danh sách phông chữ FallBack.

--------------------

> ```
> //Tạo một thể hiện mới của FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Thêm ba phông chữ nữa vào quy tắc 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fontNames | java.lang.String[] | Tên hoặc các tên phông chữ (được phân tách bằng dấu phẩy) cho FallBack |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```

Lấy chỉ mục đầu tiên của phạm vi unicode liên tục.

**Trả về:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```

Lấy chỉ mục đầu tiên của phạm vi unicode liên tục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```

Lấy chỉ mục cuối cùng của phạm vi unicode liên tục.

**Trả về:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```

Lấy chỉ mục cuối cùng của phạm vi unicode liên tục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```

Lấy số lượng phông chữ thực sự được định nghĩa cho phạm vi. Đọc-chỉ int.

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```

Lấy tên phông chữ tại chỉ mục được chỉ định. Đọc-chỉ [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả phông chữ khỏi danh sách.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```

Xóa lần xuất hiện đầu tiên của một phông chữ FallBack cụ thể khỏi danh sách.

--------------------

> ```
> // Tạo một quy tắc chứa danh sách các phông chữ.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Xóa Tahoma khỏi danh sách.
>  newRule.remove("Tahoma");
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fontName | java.lang.String | Tên phông chữ cần xóa khỏi danh sách. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa phông chữ FallBack tại chỉ mục được chỉ định trong danh sách.

--------------------

> ```
> // Tạo một quy tắc chứa danh sách các phông chữ.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Xóa Tahoma khỏi danh sách.
>  newRule.remove(2);
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục dựa trên số 0 của phông chữ cần xóa. |

### toArray() {#toArray--}
```
public final String[] toArray()
```

Tạo và trả về một mảng chứa tất cả phông chữ FallBack cho quy tắc này.

--------------------

> ```
> // Tạo một quy tắc chứa danh sách các phông chữ.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Lấy tất cả các tên phông chữ dưới dạng mảng.
>  String[] fontNames = newRule.toArray();
> ```


**Trả về:**
java.lang.String[] - Array of String
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```

Tạo và trả về một mảng chứa tất cả phông chữ FallBack từ phạm vi được chỉ định trong danh sách.

```
// Tạo một quy tắc chứa danh sách các phông chữ.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Lấy hai tên phông chữ cuối cùng dưới dạng mảng.
 String[] fontNames = newRule.toArray(2, 2);
```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| startIndex | int | Chỉ mục của phông chữ đầu tiên cần thêm. |
| count | int | Số lượng phông chữ cần thêm. |

**Trả về:**
java.lang.String[] - Array of String
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```

Trả về chỉ mục của quy tắc được chỉ định trong tập hợp.

--------------------

> ```
> // Tạo một quy tắc chứa danh sách các phông chữ.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Lấy chỉ mục của Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| fontName | java.lang.String | Tên phông chữ cần tìm. |

**Trả về:**
int - Chỉ mục của phông chữ hoặc -1 nếu không tìm thấy phông chữ trong danh sách.