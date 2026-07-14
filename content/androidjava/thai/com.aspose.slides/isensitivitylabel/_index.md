---
title: ISensitivityLabel
second_title: Aspose.Slides for Android via Java API Reference
description: แสดงถึงป้ายความละเอียดจาก Microsoft Purview Information Protection.
type: docs
url: /th/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

แสดงถึงป้ายความละเอียดจาก Microsoft Purview Information Protection.
## เมธอด

| Method | Description |
| --- | --- |
| [getId()](#getId--) | คืนค่า หรือกำหนดค่า id ของป้ายความละเอียด. |
| [setId(String value)](#setId-java.lang.String-) | คืนค่า หรือกำหนดค่า id ของป้ายความละเอียด. |
| [getSiteId()](#getSiteId--) | คืนค่า หรือกำหนดค่า Azure Active Directory (Azure AD) site identifier ที่สอดคล้องกับนโยบายป้ายความละเอียด. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | คืนค่า หรือกำหนดค่า Azure Active Directory (Azure AD) site identifier ที่สอดคล้องกับนโยบายป้ายความละเอียด. |
| [isEnabled()](#isEnabled--) | ระบุว่าป้ายความละเอียดถูกเปิดใช้งานหรือไม่. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | ระบุว่าป้ายความละเอียดถูกเปิดใช้งานหรือไม่. |
| [isRemoved()](#isRemoved--) | ระบุว่าป้ายความละเอียดถูกลบออกหรือไม่. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | ระบุว่าป้ายความละเอียดถูกลบออกหรือไม่. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | คืนค่า หรือกำหนดค่า วิธีการกำหนดป้ายความละเอียด. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | คืนค่า หรือกำหนดค่า วิธีการกำหนดป้ายความละเอียด. |
| [getContentMarkTypes()](#getContentMarkTypes--) | คืนรายการประเภทของการทำเครื่องหมายเนื้อหาที่ควรนำไปใช้กับไฟล์. |
### getId() {#getId--}
```
public abstract String getId()
```

คืนค่า หรือกำหนดค่า id ของป้ายความละเอียด. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

คืนค่า หรือกำหนดค่า id ของป้ายความละเอียด. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```

คืนค่า หรือกำหนดค่า Azure Active Directory (Azure AD) site identifier ที่สอดคล้องกับนโยบายป้ายความละเอียด. อ่าน/เขียน java.util.UUID.

**คืนค่า:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```

คืนค่า หรือกำหนดค่า Azure Active Directory (Azure AD) site identifier ที่สอดคล้องกับนโยบายป้ายความละเอียด. อ่าน/เขียน java.util.UUID.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```

ระบุว่าป้ายความละเอียดถูกเปิดใช้งานหรือไม่.

**คืนค่า:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```

ระบุว่าป้ายความละเอียดถูกเปิดใช้งานหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```

ระบุว่าป้ายความละเอียดถูกลบออกหรือไม่.

**คืนค่า:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```

ระบุว่าป้ายความละเอียดถูกลบออกหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```

คืนค่า หรือกำหนดค่า วิธีการกำหนดป้ายความละเอียด. อ่าน/เขียน [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**คืนค่า:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```

คืนค่า หรือกำหนดค่า วิธีการกำหนดป้ายความละเอียด. อ่าน/เขียน [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

คืนรายการประเภทของการทำเครื่องหมายเนื้อหาที่ควรนำไปใช้กับไฟล์.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - A list of content types [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)