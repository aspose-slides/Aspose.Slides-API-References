---
title: SensitivityLabelCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một tập hợp các nhãn nhạy cảm được áp dụng cho tài liệu.
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

Đại diện cho một tập hợp các nhãn nhạy cảm được áp dụng cho tài liệu.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về nhãn nhạy cảm theo chỉ mục. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | Thêm nhãn nhạy cảm vào cuối tập hợp. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | Thêm một SensitivityLabel vào tập hợp. |
| [removeAt(int index)](#removeAt-int-) | Xóa nhãn nhạy cảm tại chỉ mục đã chỉ định. |
| [clear()](#clear--) | Xóa tất cả các phần tử khỏi tập hợp. |
| [iterator()](#iterator--) | Trả về một enumerator để duyệt qua tập hợp. |
| [getCount()](#getCount--) | Trả về số lượng phần tử trong tập hợp. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | Sao chép tất cả các phần tử từ tập hợp tới mảng đã chỉ định. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```


Trả về nhãn nhạy cảm theo chỉ mục.

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


Thêm nhãn nhạy cảm vào cuối tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| id | java.lang.String | ID của nhãn nhạy cảm. |
| siteId | java.util.UUID | Định danh site Azure Active Directory (Azure AD). |
| isEnabled | boolean | Cờ cho biết nhãn nhạy cảm có được bật hay không. |
| methodType | int | Phương pháp gán cho nhãn nhạy cảm. |

**Trả về:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```


Thêm một SensitivityLabel vào tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | Đối tượng SensitivityLabel sẽ được thêm vào cuối tập hợp. |

**Trả về:**
int - Chỉ mục mà SensitivityLabel được thêm vào.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Xóa nhãn nhạy cảm tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của nhãn nhạy cảm cần xóa. |

### clear() {#clear--}
```
public final void clear()
```


Xóa tất cả các phần tử khỏi tập hợp.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```


Trả về một enumerator để duyệt qua tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - Một System.Collections.Generic.IEnumerator1 có thể được sử dụng để duyệt qua tập hợp.
### getCount() {#getCount--}
```
public final int getCount()
```


Trả về số lượng phần tử trong tập hợp. Chỉ đọc  int .

**Trả về:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```


Sao chép tất cả các phần tử từ tập hợp tới mảng đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |