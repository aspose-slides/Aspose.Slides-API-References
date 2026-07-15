---
title: IBehaviorCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn tập hợp các hiệu ứng hành vi.
type: docs
url: /vi/com.aspose.slides/ibehaviorcollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

Biểu diễn tập hợp các hiệu ứng hành vi.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về một hành vi tại chỉ mục đã chỉ định. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Trả về một hành vi tại chỉ mục đã chỉ định. |
| [getCount()](#getCount--) | Trả về số lượng hành vi trong một tập hợp. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Thêm hành vi mới vào một tập hợp. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Xác định chỉ mục của một mục cụ thể trong List. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Chèn hành vi mới vào một tập hợp tại chỉ mục đã chỉ định. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Xóa hành vi đã chỉ định khỏi một tập hợp. |
| [removeAt(int index)](#removeAt-int-) | Xóa hành vi khỏi một tập hợp tại chỉ mục đã chỉ định. |
| [clear()](#clear--) | Xóa tất cả các hành vi khỏi một tập hợp. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Xác định liệu [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa một giá trị cụ thể hay không. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```

Trả về một hành vi tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của một hành vi để trả về. |

**Giá trị trả về:**
[IBehavior](../../com.aspose.slides/ibehavior) - Hành vi hoạt hình.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```

Trả về một hành vi tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của một hành vi để trả về. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Trả về số lượng hành vi trong một tập hợp. int chỉ đọc.

**Giá trị trả về:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

Thêm hành vi mới vào một tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Hành vi cần thêm. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

Xác định chỉ mục của một mục cụ thể trong List.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Đối tượng cần tìm trong List. |

**Giá trị trả về:**
int - Chỉ mục của mục nếu được tìm thấy trong danh sách; nếu không, -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

Chèn hành vi mới vào một tập hợp tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục nơi hành vi mới sẽ được chèn. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Hành vi cần chèn. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

Xóa hành vi đã chỉ định khỏi một tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Hành vi cần xóa. |

**Giá trị trả về:**
boolean - True nếu hành vi được xóa thành công boolean
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa hành vi khỏi một tập hợp tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của một hành vi để xóa. |

### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các hành vi khỏi một tập hợp.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

Xác định liệu [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa một giá trị cụ thể hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Đối tượng cần tìm trong [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Giá trị trả về:**
boolean - true nếu mục được tìm thấy trong [IGenericCollection](../../com.aspose.slides/igenericcollection); nếu không, false.