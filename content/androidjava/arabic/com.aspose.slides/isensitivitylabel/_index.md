---
title: ISensitivityLabel
second_title: Aspose.Slides لـ Android عبر مرجع API للجافا
description: يمثل علامة الحساسية من Microsoft Purview Information Protection.
type: docs
url: /ar/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

يمثل علامة الحساسية من Microsoft Purview Information Protection.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getId()](#getId--) | يقوم بإرجاع أو تعيين id لــ sensitivity label. |
| [setId(String value)](#setId-java.lang.String-) | يقوم بإرجاع أو تعيين id لــ sensitivity label. |
| [getSiteId()](#getSiteId--) | يقوم بإرجاع أو تعيين معرف موقع Azure Active Directory (Azure AD) المقابل لسياسة العلامة الحساسة التي تصف sensitivity label. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | يقوم بإرجاع أو تعيين معرف موقع Azure Active Directory (Azure AD) المقابل لسياسة العلامة الحساسة التي تصف sensitivity label. |
| [isEnabled()](#isEnabled--) | يشير إلى ما إذا كانت sensitivity label مفعلة. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | يشير إلى ما إذا كانت sensitivity label مفعلة. |
| [isRemoved()](#isRemoved--) | يشير إلى ما إذا كانت sensitivity label قد أزيلت. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | يشير إلى ما إذا كانت sensitivity label قد أزيلت. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | يقوم بإرجاع أو تعيين طريقة التعيين للـ sensitivity label. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | يقوم بإرجاع أو تعيين طريقة التعيين للـ sensitivity label. |
| [getContentMarkTypes()](#getContentMarkTypes--) | يقوم بإرجاع قائمة أنواع وضع علامات المحتوى التي ينبغي تطبيقها على ملف. |
### getId() {#getId--}
```
public abstract String getId()
```

يقوم بإرجاع أو تعيين id للـ sensitivity label. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

يقوم بإرجاع أو تعيين id للـ sensitivity label. قراءة/كتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```

يقوم بإرجاع أو تعيين معرف موقع Azure Active Directory (Azure AD) المقابل لسياسة العلامة الحساسة التي تصف sensitivity label. قراءة/كتابة java.util.UUID.

**الإرجاع:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```

يقوم بإرجاع أو تعيين معرف موقع Azure Active Directory (Azure AD) المقابل لسياسة العلامة الحساسة التي تصف sensitivity label. قراءة/كتابة java.util.UUID.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```

يشير إلى ما إذا كانت sensitivity label مفعلة.

**الإرجاع:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```

يشير إلى ما إذا كانت sensitivity label مفعلة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```

يشير إلى ما إذا كانت sensitivity label قد أزيلت.

**الإرجاع:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```

يشير إلى ما إذا كانت sensitivity label قد أزيلت.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```

يقوم بإرجاع أو تعيين طريقة التعيين للـ sensitivity label. قراءة/كتابة [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**الإرجاع:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```

يقوم بإرجاع أو تعيين طريقة التعيين للـ sensitivity label. قراءة/كتابة [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

يقوم بإرجاع قائمة أنواع وضع علامات المحتوى التي ينبغي تطبيقها على ملف.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - قائمة بأنواع المحتوى [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)