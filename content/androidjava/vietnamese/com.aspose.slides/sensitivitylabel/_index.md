---
title: SensitivityLabel
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Biểu diễn nhãn nhạy cảm từ Microsoft Purview Information Protection.
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

Biểu diễn nhãn nhạy cảm từ Microsoft Purview Information Protection.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getId()](#getId--) | Trả về hoặc đặt id của nhãn nhạy cảm. |
| [setId(String value)](#setId-java.lang.String-) | Trả về hoặc đặt id của nhãn nhạy cảm. |
| [getSiteId()](#getSiteId--) | Trả về hoặc đặt định danh trang Azure Active Directory (Azure AD) tương ứng với chính sách nhãn nhạy cảm mô tả nhãn này. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Trả về hoặc đặt định danh trang Azure Active Directory (Azure AD) tương ứng với chính sách nhãn nhạy cảm mô tả nhãn này. |
| [isEnabled()](#isEnabled--) | Chỉ ra liệu nhãn nhạy cảm có được bật hay không. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Chỉ ra liệu nhãn nhạy cảm có được bật hay không. |
| [isRemoved()](#isRemoved--) | Chỉ ra liệu nhãn nhạy cảm đã bị xóa hay chưa. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Chỉ ra liệu nhãn nhạy cảm đã bị xóa hay chưa. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Trả về hoặc đặt phương pháp gán cho nhãn nhạy cảm. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Trả về hoặc đặt phương pháp gán cho nhãn nhạy cảm. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Trả về danh sách các loại đánh dấu nội dung cần áp dụng cho tệp. |

### getId() {#getId--}
```
public final String getId()
```

Trả về hoặc đặt id của nhãn nhạy cảm. Đọc/ghi String.

**Trả về:**  
java.lang.String

### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```

Trả về hoặc đặt id của nhãn nhạy cảm. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```

Trả về hoặc đặt định danh trang Azure Active Directory (Azure AD) tương ứng với chính sách nhãn nhạy cảm mô tả nhãn này. Đọc/ghi java.util.UUID.

**Trả về:**  
java.util.UUID

### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```

Trả về hoặc đặt định danh trang Azure Active Directory (Azure AD) tương ứng với chính sách nhãn nhạy cảm mô tả nhãn này. Đọc/ghi java.util.UUID.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```

Chỉ ra liệu nhãn nhạy cảm có được bật hay không.

**Trả về:**  
boolean

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```

Chỉ ra liệu nhãn nhạy cảm có được bật hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```

Chỉ ra liệu nhãn nhạy cảm đã bị xóa hay chưa.

**Trả về:**  
boolean

### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```

Chỉ ra liệu nhãn nhạy cảm đã bị xóa hay chưa.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```

Trả về hoặc đặt phương pháp gán cho nhãn nhạy cảm. Đọc/ghi [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Trả về:**  
int

### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```

Trả về hoặc đặt phương pháp gán cho nhãn nhạy cảm. Đọc/ghi [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

Trả về danh sách các loại đánh dấu nội dung cần áp dụng cho tệp.

**Trả về:**  
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Một danh sách các loại nội dung [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)