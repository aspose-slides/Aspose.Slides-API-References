---
title: ISensitivityLabel
second_title: Aspose.Slides for Java API Reference
description: Đại diện cho nhãn nhạy cảm từ Microsoft Purview Information Protection.
type: docs
url: /vi/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

Đại diện cho nhãn nhạy cảm từ Microsoft Purview Information Protection.
## Phương thức

| Method | Mô tả |
| --- | --- |
| [getId()](#getId--) | Trả về hoặc thiết lập id của nhãn nhạy cảm. |
| [setId(String value)](#setId-java.lang.String-) | Trả về hoặc thiết lập id của nhãn nhạy cảm. |
| [getSiteId()](#getSiteId--) | Trả về hoặc thiết lập định danh site Azure Active Directory (Azure AD) tương ứng với chính sách nhãn nhạy cảm mô tả nhãn nhạy cảm. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Trả về hoặc thiết lập định danh site Azure Active Directory (Azure AD) tương ứng với chính sách nhãn nhạy cảm mô tả nhãn nhạy cảm. |
| [isEnabled()](#isEnabled--) | Cho biết liệu nhãn nhạy cảm có được bật hay không. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Cho biết liệu nhãn nhạy cảm có được bật hay không. |
| [isRemoved()](#isRemoved--) | Cho biết liệu nhãn nhạy cảm đã bị xóa hay chưa. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Cho biết liệu nhãn nhạy cảm đã bị xóa hay chưa. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Trả về hoặc thiết lập phương pháp gán cho nhãn nhạy cảm. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Trả về hoặc thiết lập phương pháp gán cho nhãn nhạy cảm. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Trả về danh sách các loại đánh dấu nội dung cần được áp dụng cho tệp. |
### getId() {#getId--}
```
public abstract String getId()
```

Trả về hoặc thiết lập id của nhãn nhạy cảm. Đọc/ghi String.

**Kết quả trả về:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

Trả về hoặc thiết lập id của nhãn nhạy cảm. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```

Trả về hoặc thiết lập định danh site Azure Active Directory (Azure AD) tương ứng với chính sách nhãn nhạy cảm mô tả nhãn nhạy cảm. Đọc/ghi java.util.UUID.

**Kết quả trả về:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```

Trả về hoặc thiết lập định danh site Azure Active Directory (Azure AD) tương ứng với chính sách nhãn nhạy cảm mô tả nhãn nhạy cảm. Đọc/ghi java.util.UUID.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```

Cho biết liệu nhãn nhạy cảm có được bật hay không.

**Kết quả trả về:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```

Cho biết liệu nhãn nhạy cảm có được bật hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```

Cho biết liệu nhãn nhạy cảm đã bị xóa hay chưa.

**Kết quả trả về:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```

Cho biết liệu nhãn nhạy cảm đã bị xóa hay chưa.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```

Trả về hoặc thiết lập phương pháp gán cho nhãn nhạy cảm. Đọc/ghi [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Kết quả trả về:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```

Trả về hoặc thiết lập phương pháp gán cho nhãn nhạy cảm. Đọc/ghi [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

Trả về danh sách các loại đánh dấu nội dung cần được áp dụng cho tệp.

**Kết quả trả về:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - A list of content types [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)