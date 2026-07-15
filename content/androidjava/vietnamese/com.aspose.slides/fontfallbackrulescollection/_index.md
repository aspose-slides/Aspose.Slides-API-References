---
title: FontFallBackRulesCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một bộ sưu tập các quy tắc FontFallBack do người dùng định nghĩa
type: docs
url: /vi/com.aspose.slides/fontfallbackrulescollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
```
public class FontFallBackRulesCollection implements IFontFallBackRulesCollection
```

Biểu diễn một bộ sưu tập các quy tắc FontFallBack, do người dùng định nghĩa
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [FontFallBackRulesCollection()](#FontFallBackRulesCollection--) |  |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Lấy số lượng quy tắc thực sự chứa trong bộ sưu tập. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | Thêm một quy tắc FallBack được chỉ định vào cuối bộ sưu tập. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | Xóa lần xuất hiện đầu tiên của một quy tắc FallBack cụ thể khỏi bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Lấy quy tắc ở chỉ mục đã chỉ định. |
| [iterator()](#iterator--) | Trả về một enumerator cho phép duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về một giá trị cho biết liệu việc truy cập vào bộ sưu tập có được đồng bộ (an toàn đa luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về gốc đồng bộ. |
### FontFallBackRulesCollection() {#FontFallBackRulesCollection--}
```
public FontFallBackRulesCollection()
```


### size() {#size--}
```
public final int size()
```


Lấy số lượng quy tắc thực sự chứa trong bộ sưu tập. Chỉ đọc int.

**Trả về:**
int
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public final void add(IFontFallBackRule sourceRule)
```


Thêm một quy tắc FallBack được chỉ định vào cuối bộ sưu tập.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Lấy bộ sưu tập quy tắc trống hoặc đã được khởi tạo trước từ FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Thêm quy tắc mới vào bộ sưu tập
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
>  ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Quy tắc được chỉ định để thêm |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public final void remove(IFontFallBackRule targetRule)
```


Xóa lần xuất hiện đầu tiên của một quy tắc FallBack cụ thể khỏi bộ sưu tập.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Lấy bộ sưu tập quy tắc trống hoặc đã được khởi tạo trước từ FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Thêm một số quy tắc vào bộ sưu tập
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Lấy đối tượng của quy tắc đầu tiên trong bộ sưu tập
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //Xóa 
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
>  ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Quy tắc cần xóa khỏi bộ sưu tập. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontFallBackRule get_Item(int index)
```


Lấy quy tắc ở chỉ mục đã chỉ định. Chỉ đọc [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Lấy bộ sưu tập quy tắc trống hoặc đã được khởi tạo trước từ FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Thêm một số quy tắc vào bộ sưu tập
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Lấy đối tượng của quy tắc đầu tiên trong bộ sưu tập
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
>  ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iterator()
```


Trả về một enumerator cho phép duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iteratorJava()
```


Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Trả về một giá trị cho biết liệu việc truy cập vào bộ sưu tập có được đồng bộ (an toàn đa luồng) hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Trả về gốc đồng bộ. Chỉ đọc Object.

**Trả về:**
java.lang.Object