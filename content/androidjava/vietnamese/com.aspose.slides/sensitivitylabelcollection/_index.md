---
title: SensitivityLabelCollection
second_title: Tham khảo API Java của Aspose.Slides cho Android
description: Đại diện cho một bộ sưu tập các nhãn độ nhạy được áp dụng cho tài liệu.
type: docs
url: /vi/com.aspose.slides/sensitivitylabelcollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

Đại diện cho một bộ sưu tập các nhãn độ nhạy được áp dụng cho tài liệu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về nhãn độ nhạy theo chỉ mục. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Thêm nhãn độ nhạy vào cuối bộ sưu tập. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Thêm một SensitivityLabel vào bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa nhãn độ nhạy tại chỉ mục được chỉ định. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi bộ sưu tập. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [getCount()](#getCount--) | Trả về số lượng phần tử trong bộ sưu tập. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```

Trả về nhãn độ nhạy theo chỉ mục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

Thêm nhãn độ nhạy vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| id | java.lang.String | ID của nhãn độ nhạy. |
| siteId | java.util.UUID | Định danh trang Azure Active Directory (Azure AD). |
| isEnabled | boolean | Cờ cho biết nhãn độ nhạy có được bật hay không. |
| methodType | int | Phương pháp gán cho nhãn độ nhạy. |

**Trả về:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```

Thêm một SensitivityLabel vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Đối tượng SensitivityLabel sẽ được thêm vào cuối bộ sưu tập. |

**Trả về:**
int - Chỉ mục mà SensitivityLabel được thêm vào.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa nhãn độ nhạy tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của nhãn độ nhạy cần xóa. |

### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các phần tử khỏi bộ sưu tập.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```

Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - Một System.Collections.Generic.IEnumerator1 có thể được sử dụng để duyệt qua bộ sưu tập.
### getCount() {#getCount--}
```
public final int getCount()
```

Trả về số lượng phần tử trong bộ sưu tập. Chỉ đọc int.

**Trả về:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```

Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |