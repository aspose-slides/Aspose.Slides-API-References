---
title: ISensitivityLabel
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر برچسب حساسیت از Microsoft Purview Information Protection.
type: docs
url: /fa/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

نمایانگر برچسب حساسیت از Microsoft Purview Information Protection.
## روش‌ها

| متد | توضیح |
| --- | --- |
| [getId()](#getId--) | مقدار بازده یا تنظیم id برچسب حساسیت. |
| [setId(String value)](#setId-java.lang.String-) | مقدار بازده یا تنظیم id برچسب حساسیت. |
| [getSiteId()](#getSiteId--) | مقدار بازده یا تنظیم Azure Active Directory (Azure AD) site identifier مربوط به سیاست برچسب حساسیت که برچسب حساسیت را توصیف می‌کند. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | مقدار بازده یا تنظیم Azure Active Directory (Azure AD) site identifier مربوط به سیاست برچسب حساسیت که برچسب حساسیت را توصیف می‌کند. |
| [isEnabled()](#isEnabled--) | نشان می‌دهد آیا برچسب حساسیت فعال است. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | نشان می‌دهد آیا برچسب حساسیت فعال است. |
| [isRemoved()](#isRemoved--) | نشان می‌دهد آیا برچسب حساسیت حذف شده است. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | نشان می‌دهد آیا برچسب حساسیت حذف شده است. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | مقدار بازده یا تنظیم روش تخصیص برای برچسب حساسیت. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | مقدار بازده یا تنظیم روش تخصیص برای برچسب حساسیت. |
| [getContentMarkTypes()](#getContentMarkTypes--) | لیست انواع علامت‌گذاری محتوا که باید بر روی یک فایل اعمال شود را باز می‌گرداند. |
### getId() {#getId--}
```
public abstract String getId()
```

مقدار بازده یا تنظیم id برچسب حساسیت. Read/write String.

**بازگشت:**  
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

مقدار بازده یا تنظیم id برچسب حساسیت. Read/write String.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```

مقدار بازده یا تنظیم Azure Active Directory (Azure AD) site identifier مربوط به سیاست برچسب حساسیت که برچسب حساسیت را توصیف می‌کند. Read/write java.util.UUID.

**بازگشت:**  
java util.UUID
### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```

مقدار بازده یا تنظیم Azure Active Directory (Azure AD) site identifier مربوط به سیاست برچسب حساسیت که برچسب حساسیت را توصیف می‌کند. Read/write java.util.UUID.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.util.UUID |  |
### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```

نشان می‌دهد آیا برچسب حساسیت فعال است.

**بازگشت:**  
boolean
### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```

نشان می‌دهد آیا برچسب حساسیت فعال است.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```

نشان می‌دهد آیا برچسب حساسیت حذف شده است.

**بازگشت:**  
boolean
### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```

نشان می‌دهد آیا برچسب حساسیت حذف شده است.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```

مقدار بازده یا تنظیم روش تخصیص برای برچسب حساسیت. Read/write [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**بازگشت:**  
int
### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```

مقدار بازده یا تنظیم روش تخصیص برای برچسب حساسیت. Read/write [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

لیست انواع علامت‌گذاری محتوا که باید بر روی یک فایل اعمال شود را باز می‌گرداند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - لیستی از انواع محتوا [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)