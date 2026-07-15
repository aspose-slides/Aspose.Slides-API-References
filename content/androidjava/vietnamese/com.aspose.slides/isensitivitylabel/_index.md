---
title: ISensitivityLabel
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the sensitivity label from Microsoft Purview Information Protection.
type: docs
url: /vi/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Biểu diễn nhãn nhạy cảm từ Microsoft Purview Information Protection.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getId()](#getId--) | Trả về hoặc đặt id của nhãn nhạy cảm. |
| [setId(String value)](#setId-java.lang.String-) | Trả về hoặc đặt id của nhãn nhạy cảm. |
| [getSiteId()](#getSiteId--) | Trả về hoặc đặt định danh site Azure Active Directory (Azure AD) tương ứng với chính sách nhãn nhạy cảm mô tả nhãn này. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Trả về hoặc đặt định danh site Azure Active Directory (Azure AD) tương ứng với chính sách nhãn nhạy cảm mô tả nhãn này. |
| [isEnabled()](#isEnabled--) | Cho biết nhãn nhạy cảm có được bật hay không. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Cho biết nhãn nhạy cảm có được bật hay không. |
| [isRemoved()](#isRemoved--) | Cho biết nhãn nhạy cảm đã bị xóa hay chưa. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Cho biết nhãn nhạy cảm đã bị xóa hay chưa. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Trả về hoặc đặt phương thức gán cho nhãn nhạy cảm. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Trả về hoặc đặt phương thức gán cho nhãn nhạy cảm. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Trả về danh sách các loại đánh dấu nội dung sẽ được áp dụng cho tệp. |
### getId() {#getId--}
```
public abstract String getId()
```


Trả về hoặc đặt id của nhãn nhạy cảm. Đọc/ghi String.

**Trả về:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


Trả về hoặc đặt id của nhãn nhạy cảm. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```


Trả về hoặc đặt định danh site Azure Active Directory (Azure AD) tương ứng với chính sách nhãn nhạy cảm mô tả nhãn này. Đọc/ghi java.util.UUID.

**Trả về:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```


Trả về hoặc đặt định danh site Azure Active Directory (Azure AD) tương ứng với chính sách nhãn nhạy cảm mô tả nhãn này. Đọc/ghi java.util.UUID.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```


Cho biết nhãn nhạy cảm có được bật hay không.

**Trả về:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```


Cho biết nhãn nhạy cảm có được bật hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```


Cho biết nhãn nhạy cảm đã bị xóa hay chưa.

**Trả về:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```


Cho biết nhãn nhạy cảm đã bị xóa hay chưa.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```


Trả về hoặc đặt phương thức gán cho nhãn nhạy cảm. Đọc/ghi [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Trả về:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```


Trả về hoặc đặt phương thức gán cho nhãn nhạy cảm. Đọc/ghi [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


Trả về danh sách các loại đánh dấu nội dung sẽ được áp dụng cho tệp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - Một danh sách các loại nội dung [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)