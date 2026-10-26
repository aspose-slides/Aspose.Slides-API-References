---
title: SensitivityLabel
second_title: Aspose.Slides cho Java - Tham chiếu API
description: Biểu thị nhãn độ nhạy từ Microsoft Purview Information Protection.
type: docs
url: /vi/com.aspose.slides/sensitivitylabel/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

Biểu thị nhãn độ nhạy từ Microsoft Purview Information Protection.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getId()](#getId--) | Trả về hoặc đặt id của nhãn độ nhạy. |
| [setId(String value)](#setId-java.lang.String-) | Trả về hoặc đặt id của nhãn độ nhạy. |
| [getSiteId()](#getSiteId--) | Trả về hoặc đặt định danh trang Azure Active Directory (Azure AD) tương ứng với chính sách nhãn độ nhạy mô tả nhãn độ nhạy. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Trả về hoặc đặt định danh trang Azure Active Directory (Azure AD) tương ứng với chính sách nhãn độ nhạy mô tả nhãn độ nhạy. |
| [isEnabled()](#isEnabled--) | Chỉ ra liệu nhãn độ nhạy có được bật hay không. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Chỉ ra liệu nhãn độ nhạy có được bật hay không. |
| [isRemoved()](#isRemoved--) | Chỉ ra liệu nhãn độ nhạy đã bị xóa hay chưa. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Chỉ ra liệu nhãn độ nhạy đã bị xóa hay chưa. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Trả về hoặc đặt phương pháp gán cho nhãn độ nhạy. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Trả về hoặc đặt phương pháp gán cho nhãn độ nhạy. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Trả về danh sách các loại đánh dấu nội dung nên được áp dụng cho một tệp. |
### getId() {#getId--}
```
public final String getId()
```


Trả về hoặc đặt id của nhãn độ nhạy. Đọc/ghi String.

**Trả về:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```


Trả về hoặc đặt id của nhãn độ nhạy. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```


Trả về hoặc đặt định danh trang Azure Active Directory (Azure AD) tương ứng với chính sách nhãn độ nhạy mô tả nhãn độ nhạy. Đọc/ghi java.util.UUID.

**Trả về:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```


Trả về hoặc đặt định danh trang Azure Active Directory (Azure AD) tương ứng với chính sách nhãn độ nhạy mô tả nhãn độ nhạy. Đọc/ghi java.util.UUID.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```


Chỉ ra liệu nhãn độ nhạy có được bật hay không.

**Trả về:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Chỉ ra liệu nhãn độ nhạy có được bật hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```


Chỉ ra liệu nhãn độ nhạy đã bị xóa hay chưa.

**Trả về:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```


Chỉ ra liệu nhãn độ nhạy đã bị xóa hay chưa.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```


Trả về hoặc đặt phương pháp gán cho nhãn độ nhạy. Đọc/ghi [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Trả về:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```


Trả về hoặc đặt phương pháp gán cho nhãn độ nhạy. Đọc/ghi [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


Trả về danh sách các loại đánh dấu nội dung nên được áp dụng cho một tệp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Một danh sách các loại nội dung [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)