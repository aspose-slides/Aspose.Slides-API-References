---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu thị các thuộc tính thời gian cho hành vi hiệu ứng.
type: docs
url: /vi/com.aspose.slides/ibehaviorpropertycollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

Biểu thị các thuộc tính thời gian cho hành vi hiệu ứng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | Thêm một thuộc tính mới vào bộ sưu tập. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Xác định chỉ mục của một mục cụ thể dựa trên giá trị thuộc tính trong List. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Chèn một thuộc tính mới (với giá trị thuộc tính đã chỉ định) vào bộ sưu tập tại chỉ mục được chỉ định. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Xóa thuộc tính được chỉ định khỏi bộ sưu tập. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Xác định xem [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa một giá trị cụ thể hay không. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```

Thêm một thuộc tính mới vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| propertyValue | java.lang.String | Giá trị của thuộc tính cần thêm. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```

Xác định chỉ mục của một mục cụ thể dựa trên giá trị thuộc tính trong List.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| propertyValue | java.lang.String | Giá trị của thuộc tính |

**Kết quả trả về:**
int - Chỉ mục của thuộc tính có giá trị đã chỉ định
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```

Chèn một thuộc tính mới (với giá trị thuộc tính đã chỉ định) vào bộ sưu tập tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục nơi thuộc tính mới sẽ được chèn. |
| propertyValue | java.lang.String | Giá trị của thuộc tính cần thêm. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```

Xóa thuộc tính được chỉ định khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| propertyValue | java.lang.String | Giá trị của thuộc tính cần xóa. |

**Kết quả trả về:**
boolean - true nếu thuộc tính được xóa thành công
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```

Xác định xem [IGenericCollection](../../com.aspose.slides/igenericcollection) có chứa một giá trị cụ thể hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| propertyValue | java.lang.String | Giá trị của thuộc tính để tìm trong [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Kết quả trả về:**
boolean - true nếu propertyValue được tìm thấy trong [IGenericCollection](../../com.aspose.slides/igenericcollection); nếu không, false.