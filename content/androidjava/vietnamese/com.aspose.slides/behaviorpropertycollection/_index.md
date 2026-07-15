---
title: BehaviorPropertyCollection
second_title: Tham chiếu API Java Aspose.Slides cho Android
description: Biểu diễn các thuộc tính thời gian cho hành vi hiệu ứng.
type: docs
url: /vi/com.aspose.slides/behaviorpropertycollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

Biểu diễn các thuộc tính thời gian cho hành vi hiệu ứng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Trả về số lượng thuộc tính được lưu trong bộ sưu tập. |
| [isReadOnly()](#isReadOnly--) | Lấy giá trị chỉ ra liệu [IGenericCollection](../../com.aspose.slides/igenericcollection) có phải là chỉ đọc hay không. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | Thêm một thuộc tính mới vào bộ sưu tập. |
| [add(String propertyValue)](#add-java.lang.String-) | Thêm một thuộc tính mới vào bộ sưu tập. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | Xác định chỉ mục của một mục cụ thể trong List. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Xác định chỉ mục của một mục cụ thể theo giá trị thuộc tính trong List. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | Chèn một thuộc tính mới vào bộ sưu tập tại chỉ mục đã chỉ định. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Chèn một thuộc tính mới (với giá trị thuộc tính được chỉ định) vào bộ sưu tập tại chỉ mục đã chỉ định. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | Sao chép các phần tử của [IGenericCollection](../../com.aspose.slides/igenericcollection) vào một Array, bắt đầu tại một chỉ mục Array cụ thể. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | Xóa thuộc tính được chỉ định khỏi bộ sưu tập. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Xóa thuộc tính được chỉ định khỏi bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa thuộc tính tại chỉ mục đã chỉ định. |
| [clear()](#clear--) | Xóa tất cả các thuộc tính khỏi bộ sưu tập. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | Xác định xem [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa một giá trị cụ thể hay không. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Xác định xem [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa một giá trị cụ thể hay không. |
| [get_Item(int index)](#get-Item-int-) | Trả về một thuộc tính tại chỉ mục đã chỉ định. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | Đặt một thuộc tính tại chỉ mục đã chỉ định. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |

### size() {#size--}
```
public final int size()
```

Trả về số lượng thuộc tính được lưu trong bộ sưu tập. Chỉ đọc int.

**Trả về:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Lấy giá trị chỉ ra liệu [IGenericCollection](../../com.aspose.slides/igenericcollection) có phải là chỉ đọc hay không. Chỉ đọc boolean.

**Trả về:**
boolean - true nếu [IGenericCollection](../../com.aspose.slides/igenericcollection) là chỉ đọc; ngược lại, false.

### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

Thêm một thuộc tính mới vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Thuộc tính để thêm. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

Thêm một thuộc tính mới vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| propertyValue | java.lang.String | Giá trị của thuộc tính cần thêm. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```

Xác định chỉ mục của một mục cụ thể trong List.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Đối tượng cần tìm trong List. |

**Trả về:**
int - Chỉ mục của item nếu tìm thấy trong danh sách; ngược lại, -1.

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

Xác định chỉ mục của một mục cụ thể theo giá trị thuộc tính trong List.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| propertyValue | java.lang.String | Giá trị của thuộc tính |

**Trả về:**
int - Chỉ mục của thuộc tính có giá trị được chỉ định

### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

Chèn một thuộc tính mới vào bộ sưu tập tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục nơi một thuộc tính mới sẽ được chèn. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Thuộc tính để thêm. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

Chèn một thuộc tính mới (với giá trị thuộc tính được chỉ định) vào bộ sưu tập tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục nơi một thuộc tính mới sẽ được chèn. |
| propertyValue | java.lang.String | Giá trị của thuộc tính để thêm. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

Sao chép các phần tử của [IGenericCollection](../../com.aspose.slides/igenericcollection) vào một Array, bắt đầu tại một chỉ mục Array cụ thể.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | Mảng một chiều là nơi nhận các phần tử được sao chép từ [IGenericCollection](../../com.aspose.slides/igenericcollection). Mảng phải có chỉ mục bắt đầu từ 0. |
| arrayIndex | int | Chỉ mục bắt đầu từ 0 trong mảng mà việc sao chép bắt đầu. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

Xóa thuộc tính được chỉ định khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Thuộc tính cần xóa. |

**Trả về:**
boolean

### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

Xóa thuộc tính được chỉ định khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| propertyValue | java.lang.String | Giá trị của thuộc tính cần xóa. |

**Trả về:**
boolean

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa thuộc tính tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của thuộc tính sẽ bị xóa. |

### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các thuộc tính khỏi bộ sưu tập.

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```

Xác định xem [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa một giá trị cụ thể hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Thuộc tính để tìm trong [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Trả về:**
boolean - true nếu item được tìm thấy trong [IGenericCollection](../../com.aspose.slides/igenericcollection); ngược lại, false.

### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

Xác định xem [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa một giá trị cụ thể hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| propertyValue | java.lang.String | Giá trị của thuộc tính để tìm trong [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Trả về:**
boolean - true nếu propertyValue được tìm thấy trong [IGenericCollection](../../com.aspose.slides/igenericcollection); ngược lại, false.

### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

Trả về một thuộc tính tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của một thuộc tính để trả về. |

**Trả về:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - Thuộc tính hành vi hoạt hình.

### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

Đặt một thuộc tính tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của một thuộc tính để trả về. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.

### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Trả về:**
int

### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Trả về:**
boolean

### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Trả về:**
boolean

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - Một java.util.Iterator cho toàn bộ bộ sưu tập.