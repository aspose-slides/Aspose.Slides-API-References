---
title: ISensitivityLabelCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một tập hợp các nhãn nhạy cảm được áp dụng cho tài liệu.
type: docs
url: /vi/com.aspose.slides/isensitivitylabelcollection/
---
**Tất cả các giao diện được thực thi:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

Biểu diễn một tập hợp các nhãn nhạy cảm được áp dụng cho tài liệu.
## Phương thức

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về nhãn nhạy cảm theo chỉ mục. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Thêm nhãn nhạy cảm vào cuối tập hợp. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Thêm một SensitivityLabel vào tập hợp. |
| [removeAt(int index)](#removeAt-int-) | Xóa nhãn nhạy cảm tại chỉ mục được chỉ định. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi tập hợp. |
| [getCount()](#getCount--) | Lấy số lượng tất cả các phần tử trong tập hợp. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```


Trả về nhãn nhạy cảm theo chỉ mục. Chỉ đọc [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```


Thêm nhãn nhạy cảm vào cuối tập hợp.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | ID của nhãn nhạy cảm. |
| siteId | java.util.UUID | Mã định danh site của Azure Active Directory (Azure AD). |
| isEnabled | boolean | Cờ cho biết nhãn nhạy cảm có được bật hay không. |
| methodType | int | Phương pháp gán cho nhãn nhạy cảm. |

**Trả về:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```


Thêm một SensitivityLabel vào tập hợp.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Đối tượng SensitivityLabel sẽ được thêm vào cuối tập hợp. |

**Trả về:**
int - Chỉ mục mà SensitivityLabel được thêm vào.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Xóa nhãn nhạy cảm tại chỉ mục được chỉ định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục của nhãn nhạy cảm cần xóa. |

### clear() {#clear--}
```
public abstract void clear()
```


Xóa tất cả các phần tử khỏi tập hợp.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Lấy số lượng tất cả các phần tử trong tập hợp. Chỉ đọc  int .

**Trả về:**
int