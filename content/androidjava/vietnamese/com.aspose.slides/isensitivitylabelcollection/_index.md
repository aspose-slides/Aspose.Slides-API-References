---
title: ISensitivityLabelCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một bộ sưu tập các nhãn nhạy cảm được áp dụng cho tài liệu.
type: docs
url: /vi/com.aspose.slides/isensitivitylabelcollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

Đại diện cho một bộ sưu tập các nhãn nhạy cảm được áp dụng cho tài liệu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về nhãn nhạy cảm theo chỉ mục. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Thêm nhãn nhạy cảm vào cuối bộ sưu tập. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Thêm một SensitivityLabel vào bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa nhãn nhạy cảm tại chỉ mục được chỉ định. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi bộ sưu tập. |
| [getCount()](#getCount--) | Lấy số lượng tất cả các phần tử trong bộ sưu tập. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

Trả về nhãn nhạy cảm theo chỉ mục. Chỉ đọc [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

Thêm nhãn nhạy cảm vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| id | java.lang.String | ID của nhãn nhạy cảm. |
| siteId | java.util.UUID | Định danh site Azure Active Directory (Azure AD). |
| isEnabled | boolean | Cờ cho biết nhãn nhạy cảm có được bật hay không. |
| methodType | int | Phương thức gán cho nhãn nhạy cảm. |

**Giá trị trả về:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```

Thêm một SensitivityLabel vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Đối tượng SensitivityLabel sẽ được thêm vào cuối bộ sưu tập. |

**Giá trị trả về:**
int - Chỉ mục mà SensitivityLabel được thêm vào.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa nhãn nhạy cảm tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của nhãn nhạy cảm cần xóa. |

### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các phần tử khỏi bộ sưu tập.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Lấy số lượng tất cả các phần tử trong bộ sưu tập. Chỉ đọc  int .

**Giá trị trả về:**
int