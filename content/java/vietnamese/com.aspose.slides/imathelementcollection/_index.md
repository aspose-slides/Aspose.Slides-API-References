---
title: IMathElementCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một tập hợp các phần tử toán học MathElement.
type: docs
url: /vi/com.aspose.slides/imathelementcollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

Biểu diễn một tập hợp các phần tử toán học (MathElement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ số xác định. |
| [getCount()](#getCount--) | Lấy số phần tử thực tế chứa trong tập hợp. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | Thêm một phần tử toán học vào cuối tập hợp. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | Xác định chỉ số của một phần tử toán học cụ thể trong tập hợp. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | Chèn một phần tử toán học vào tập hợp tại chỉ số xác định. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi tập hợp. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | Xác định xem tập hợp có chứa một giá trị cụ thể hay không. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi tập hợp. |
| [removeAt(int index)](#removeAt-int-) | Xóa phần tử tại chỉ số xác định của tập hợp. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | Sao chép vào mảng được chỉ định. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```

Lấy phần tử tại chỉ số xác định. Chỉ đọc [IMathElement](../../com.aspose.slides/imathelement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số bắt đầu từ 0 của mục cần lấy |

**Trả về:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Lấy số phần tử thực tế chứa trong tập hợp. Chỉ đọc int.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**Trả về:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```

Thêm một phần tử toán học vào cuối tập hợp.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement sẽ được thêm vào cuối tập hợp. |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```

Xác định chỉ số của một phần tử toán học cụ thể trong tập hợp.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = collection.indexOf(plusElement);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Phần tử cần tìm trong tập hợp. |

**Trả về:**
int - Chỉ số của mục nếu tìm thấy trong tập hợp; nếu không, -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```

Chèn một phần tử toán học vào tập hợp tại chỉ số xác định.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số bắt đầu từ 0 mà IMathElement sẽ được chèn vào. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement sẽ được chèn. |

### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các phần tử khỏi tập hợp.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public abstract boolean contains(IMathElement item)
```

Xác định xem tập hợp có chứa một giá trị cụ thể hay không.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  bool contains = collection.contains(plusElement);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Đối tượng cần tìm trong tập hợp. |

**Trả về:**
boolean - true nếu mục được tìm thấy trong tập hợp; nếu không, false.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```

Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi tập hợp.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.remove(plusElement);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | Đối tượng cần xóa khỏi tập hợp. |

**Trả về:**
boolean - true nếu mục đã được xóa thành công khỏi tập hợp; nếu không, false. Phương thức này cũng trả về false nếu mục không được tìm thấy trong tập hợp gốc.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa phần tử tại chỉ số xác định của tập hợp.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.removeAt(2);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số bắt đầu từ 0 của phần tử cần xóa. |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```

Sao chép vào mảng được chỉ định.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[collection.Count];
>  collection.copyTo(destinationArray, 0);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | Mảng để sao chép vào. |
| arrayIndex | int | Chỉ mục để bắt đầu sao chép. |