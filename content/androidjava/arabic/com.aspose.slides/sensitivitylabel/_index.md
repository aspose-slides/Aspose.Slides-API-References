---
title: SensitivityLabel
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: يمثل تسمية الحساسية من Microsoft Purview Information Protection.
type: docs
url: /ar/com.aspose.slides/sensitivitylabel/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
```
public final class SensitivityLabel implements ISensitivityLabel
```

يمثل تسمية الحساسية من Microsoft Purview Information Protection.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getId()](#getId--) | إرجاع أو تعيين id لتسمية الحساسية. |
| [setId(String value)](#setId-java.lang.String-) | إرجاع أو تعيين id لتسمية الحساسية. |
| [getSiteId()](#getSiteId--) | إرجاع أو تعيين معرف موقع Azure Active Directory (Azure AD) المقابل لسياسة تسمية الحساسية التي تصف تسمية الحساسية. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | إرجاع أو تعيين معرف موقع Azure Active Directory (Azure AD) المقابل لسياسة تسمية الحساسية التي تصف تسمية الحساسية. |
| [isEnabled()](#isEnabled--) | يشير إلى ما إذا كانت تسمية الحساسية مفعّلة. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | يشير إلى ما إذا كانت تسمية الحساسية مفعّلة. |
| [isRemoved()](#isRemoved--) | يشير إلى ما إذا تمت إزالة تسمية الحساسية. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | يشير إلى ما إذا تمت إزالة تسمية الحساسية. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | إرجاع أو تعيين طريقة التعيين لتسمية الحساسية. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | إرجاع أو تعيين طريقة التعيين لتسمية الحساسية. |
| [getContentMarkTypes()](#getContentMarkTypes--) | إرجاع قائمة بأنواع وضع العلامات على المحتوى التي يجب تطبيقها على ملف. |
### getId() {#getId--}
```
public final String getId()
```

إرجاع أو تعيين id لتسمية الحساسية. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public final void setId(String value)
```

إرجاع أو تعيين id لتسمية الحساسية. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public final UUID getSiteId()
```

إرجاع أو تعيين معرف موقع Azure Active Directory (Azure AD) المقابل لسياسة تسمية الحساسية التي تصف تسمية الحساسية. قراءة/كتابة java.util.UUID.

**الإرجاع:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public final void setSiteId(UUID value)
```

إرجاع أو تعيين معرف موقع Azure Active Directory (Azure AD) المقابل لسياسة تسمية الحساسية التي تصف تسمية الحساسية. قراءة/كتابة java.util.UUID.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```

يشير إلى ما إذا كانت تسمية الحساسية مفعّلة.

**الإرجاع:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```

يشير إلى ما إذا كانت تسمية الحساسية مفعّلة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public final boolean isRemoved()
```

يشير إلى ما إذا تمت إزالة تسمية الحساسية.

**الإرجاع:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public final void setRemoved(boolean value)
```

يشير إلى ما إذا تمت إزالة تسمية الحساسية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public final int getAssignmentMethodType()
```

إرجاع أو تعيين طريقة التعيين لتسمية الحساسية. قراءة/كتابة [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**الإرجاع:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public final void setAssignmentMethodType(int value)
```

إرجاع أو تعيين طريقة التعيين لتسمية الحساسية. قراءة/كتابة [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public final System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

إرجاع قائمة بأنواع وضع العلامات على المحتوى التي يجب تطبيقها على ملف.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - A list of content types [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)