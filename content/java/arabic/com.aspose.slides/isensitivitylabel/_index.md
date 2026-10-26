---
title: ISensitivityLabel
second_title: Aspose.Slides for Java API Reference
description: تمثّل علامة الحساسية من Microsoft Purview Information Protection.
type: docs
url: /ar/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

تمثّل علامة الحساسية من Microsoft Purview Information Protection.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getId()](#getId--) | Returns or sets the id of sensitivity label. |
| [setId(String value)](#setId-java.lang.String-) | Returns or sets the id of sensitivity label. |
| [getSiteId()](#getSiteId--) | Returns or sets the Azure Active Directory (Azure AD) site identifier corresponding to the sensitivity label policy which describes the sensitivity label. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | Returns or sets the Azure Active Directory (Azure AD) site identifier corresponding to the sensitivity label policy which describes the sensitivity label. |
| [isEnabled()](#isEnabled--) | Indicates whether the sensitivity label is enabled. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Indicates whether the sensitivity label is enabled. |
| [isRemoved()](#isRemoved--) | Indicates whether the sensitivity label was removed. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | Indicates whether the sensitivity label was removed. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | Returns or sets the assignment method for the sensitivity label. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | Returns or sets the assignment method for the sensitivity label. |
| [getContentMarkTypes()](#getContentMarkTypes--) | Returns the list of types of content marking that ought to be applied to a file. |
### getId() {#getId--}
```
public abstract String getId()
```

تُعيد أو تُعيّن معرف علامة الحساسية. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

تُعيد أو تُعيّن معرف علامة الحساسية. قراءة/كتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```

تُعيد أو تُعيّن معرف موقع Azure Active Directory (Azure AD) المت对应 لسياسة علامة الحساسية التي تصف علامة الحساسية. قراءة/كتابة java.util.UUID.

**الإرجاع:**
java.util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```

تُعيد أو تُعيّن معرف موقع Azure Active Directory (Azure AD) المت对应 لسياسة علامة الحساسية التي تصف علامة الحساسية. قراءة/كتابة java.util.UUID.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```

يُشير إلى ما إذا كانت علامة الحساسية مُفعَّلة.

**الإرجاع:**
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```

يُشير إلى ما إذا كانت علامة الحساسية مُفعَّلة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```

يُشير إلى ما إذا تمت إزالة علامة الحساسية.

**الإرجاع:**
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```

يُشير إلى ما إذا تمت إزالة علامة الحساسية.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```

تُعيد أو تُعيّن طريقة التعيين لعلامة الحساسية. قراءة/كتابة [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**الإرجاع:**
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```

تُعيد أو تُعيّن طريقة التعيين لعلامة الحساسية. قراءة/كتابة [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

تُعيد قائمة بأنواع تعليم المحتوى التي يجب تطبيقها على الملف.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - A list of content types [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)