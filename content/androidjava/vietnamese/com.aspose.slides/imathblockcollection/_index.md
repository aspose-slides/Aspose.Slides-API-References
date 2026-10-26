---
title: IMathBlockCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Bộ sưu tập các khối toán học IMathBlock
type: docs
url: /vi/com.aspose.slides/imathblockcollection/
---
**Tất cả các giao diện được thực thi:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

Bộ sưu tập các khối toán học (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
```
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | Thêm IMathBlock vào cuối bộ sưu tập. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | Chèn IMathBlock vào bộ sưu tập tại chỉ mục được chỉ định. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa một mục tại chỉ mục được chỉ định trong bộ sưu tập. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | Xác định xem bộ sưu tập có chứa một giá trị cụ thể hay không. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | Xác định chỉ mục của một IMathBlock cụ thể trong bộ sưu tập. |
| [getCount()](#getCount--) | Lấy số phần tử thực sự có trong bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Lấy mục tại chỉ mục được chỉ định. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | Lấy mục tại chỉ mục được chỉ định. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi bộ sưu tập. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

Thêm IMathBlock vào cuối bộ sưu tập.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Một khối toán học sẽ được thêm vào cuối bộ sưu tập |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

Chèn IMathBlock vào bộ sưu tập tại chỉ mục được chỉ định.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 mà một mục sẽ được chèn vào. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | IMathBlock để chèn. |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Đối tượng cần xóa khỏi bộ sưu tập. |

**Trả về:**
boolean - true nếu mục được xóa thành công khỏi bộ sưu tập; ngược lại, false. Phương thức này cũng trả về false nếu không tìm thấy mục trong bộ sưu tập gốc.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa một mục tại chỉ mục được chỉ định trong bộ sưu tập.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của mục cần xóa. |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

Xác định xem bộ sưu tập có chứa một giá trị cụ thể hay không.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Đối tượng cần tìm trong bộ sưu tập. |

**Trả về:**
boolean - true nếu tìm thấy mục trong bộ sưu tập; ngược lại, false.
### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

Xác định chỉ mục của một IMathBlock cụ thể trong bộ sưu tập.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | Mục cần tìm trong bộ sưu tập. |

**Trả về:**
int - Chỉ mục của mục nếu tìm thấy trong bộ sưu tập; ngược lại, -1.
### getCount() {#getCount--}
```
public abstract int getCount()
```

Lấy số phần tử thực sự có trong bộ sưu tập. int chỉ đọc.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```

Lấy mục tại chỉ mục được chỉ định. [IMathBlock](../../com.aspose.slides/imathblock) chỉ đọc.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của mục cần lấy. |

**Trả về:**
[IMathBlock](../../com.aspose.slides/imathblock) - Khối văn bản toán học.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

Lấy mục tại chỉ mục được chỉ định. [IMathBlock](../../com.aspose.slides/imathblock) chỉ đọc.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục bắt đầu từ 0 của mục cần đặt. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | Khối văn bản toán học. |

### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các phần tử khỏi bộ sưu tập.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```