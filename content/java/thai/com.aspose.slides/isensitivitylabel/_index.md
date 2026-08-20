---
title: ISensitivityLabel
second_title: Aspose.Slides for Java API Reference
description: แสดงแท็กความอ่อนไหวจาก Microsoft Purview Information Protection.
type: docs
url: /th/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

แสดงแท็กความอ่อนไหวจาก Microsoft Purview Information Protection.
## เมธอด

| Method | Description |
| --- | --- |
| [getId()](#getId--) | คืนค่า或กำหนด id ของป้ายความอ่อนไหว. |
| [setId(String value)](#setId-java.lang.String-) | คืนค่า或กำหนด id ของป้ายความอ่อนไหว. |
| [getSiteId()](#getSiteId--) | คืนค่า或กำหนดตัวระบุไซต์ Azure Active Directory (Azure AD) ที่สอดคล้องกับนโยบายป้ายความอ่อนไหวซึ่งอธิบายป้ายความอ่อนไหว. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | คืนค่า或กำหนดตัวระบุไซต์ Azure Active Directory (Azure AD) ที่สอดคล้องกับนโยบายป้ายความอ่อนไหวซึ่งอธิบายป้ายความอ่อนไหว. |
| [isEnabled()](#isEnabled--) | บ่งชี้ว่าป้ายความอ่อนไหวได้รับการเปิดใช้งานหรือไม่. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | บ่งชี้ว่าป้ายความอ่อนไหวได้รับการเปิดใช้งานหรือไม่. |
| [isRemoved()](#isRemoved--) | บ่งชี้ว่าป้ายความอ่อนไหวถูกลบหรือไม่. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | บ่งชี้ว่าป้ายความอ่อนไหวถูกลบหรือไม่. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | คืนค่า或กำหนดวิธีการมอบหมายสำหรับป้ายความอ่อนไหว. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | คืนค่า或กำหนดวิธีการมอบหมายสำหรับป้ายความอ่อนไหว. |
| [getContentMarkTypes()](#getContentMarkTypes--) | คืนค่ารายการประเภทของการทำเครื่องหมายเนื้อหาที่ควรนำไปใช้กับไฟล์. |
### getId() {#getId--}
```
public abstract String getId()
```


คืนค่า或กำหนด id ของป้ายความอ่อนไหว. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```


คืนค่า或กำหนด id ของป้ายความอ่อนไหว. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```


คืนค่า或กำหนดตัวระบุไซต์ Azure Active Directory (Azure AD) ที่สอดคล้องกับนโยบายป้ายความอ่อนไหวซึ่งอธิบายป้ายความอ่อนไหว. อ่าน/เขียน java.util.UUID.

**คืนค่า:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```


คืนค่า或กำหนดตัวระบุไซต์ Azure Active Directory (Azure AD) ที่สอดคล้องกับนโยบายป้ายความอ่อนไหวซึ่งอธิบายป้ายความอ่อนไหว. อ่าน/เขียน java.util.UUID.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```


บ่งชี้ว่าป้ายความอ่อนไหวได้รับการเปิดใช้งานหรือไม่.

**คืนค่า:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```


บ่งชี้ว่าป้ายความอ่อนไหวได้รับการเปิดใช้งานหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```


บ่งชี้ว่าป้ายความอ่อนไหวถูกลบหรือไม่.

**คืนค่า:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```


บ่งชี้ว่าป้ายความอ่อนไหวถูกลบหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```


คืนค่า或กำหนดวิธีการมอบหมายสำหรับป้ายความอ่อนไหว. อ่าน/เขียน [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**คืนค่า:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```


คืนค่า或กำหนดวิธีการมอบหมายสำหรับป้ายความอ่อนไหว. อ่าน/เขียน [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```


คืนค่ารายการประเภทของการทำเครื่องหมายเนื้อหาที่ควรนำไปใช้กับไฟล์.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - รายการประเภทของเนื้อหา [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)