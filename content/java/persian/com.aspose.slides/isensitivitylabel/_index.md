---
title: ISensitivityLabel
second_title: Aspose.Slides for Java API Reference
description: برچسب حساسیت را از Microsoft Purview Information Protection نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/isensitivitylabel/
---```
public interface ISensitivityLabel
```

برچسب حساسیت را از Microsoft Purview Information Protection نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getId()](#getId--) | شناسه‌ی برچسب حساسیت را بازمی‌گرداند یا تنظیم می‌کند. |
| [setId(String value)](#setId-java.lang.String-) | شناسه‌ی برچسب حساسیت را بازمی‌گرداند یا تنظیم می‌کند. |
| [getSiteId()](#getSiteId--) | شناسه‌ی سایت Azure Active Directory (Azure AD) مرتبط با سیاست برچسب حساسیتی که برچسب حساسیت را توصیف می‌کند را بازمی‌گرداند یا تنظیم می‌کند. |
| [setSiteId(UUID value)](#setSiteId-java.util.UUID-) | شناسه‌ی سایت Azure Active Directory (Azure AD) مرتبط با سیاست برچسب حساسیتی که برچسب حساسیت را توصیف می‌کند را بازمی‌گرداند یا تنظیم می‌کند. |
| [isEnabled()](#isEnabled--) | نشان می‌دهد آیا برچسب حساسیت فعال است یا نه. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | نشان می‌دهد آیا برچسب حساسیت فعال است یا نه. |
| [isRemoved()](#isRemoved--) | نشان می‌دهد آیا برچسب حساسیت حذف شده است یا نه. |
| [setRemoved(boolean value)](#setRemoved-boolean-) | نشان می‌دهد آیا برچسب حساسیت حذف شده است یا نه. |
| [getAssignmentMethodType()](#getAssignmentMethodType--) | روش تخصیص برچسب حساسیت را بازمی‌گرداند یا تنظیم می‌کند. |
| [setAssignmentMethodType(int value)](#setAssignmentMethodType-int-) | روش تخصیص برچسب حساسیت را بازمی‌گرداند یا تنظیم می‌کند. |
| [getContentMarkTypes()](#getContentMarkTypes--) | فهرست انواع علامت‌گذاری محتوا که باید بر روی یک فایل اعمال شود را بازمی‌گرداند. |

### getId() {#getId--}
```
public abstract String getId()
```

شناسه‌ی برچسب حساسیت را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String.

**بازمی‌گرداند:**  
java.lang.String

### setId(String value) {#setId-java.lang.String-}
```
public abstract void setId(String value)
```

شناسه‌ی برچسب حساسیت را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getSiteId() {#getSiteId--}
```
public abstract UUID getSiteId()
```

شناسه‌ی سایت Azure Active Directory (Azure AD) مرتبط با سیاست برچسب حساسیتی که برچسب حساسیت را توصیف می‌کند را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن java.util.UUID.

**بازمی‌گرداند:**  
java.util.UUID

### setSiteId(UUID value) {#setSiteId-java.util.UUID-}
```
public abstract void setSiteId(UUID value)
```

شناسه‌ی سایت Azure Active Directory (Azure AD) مرتبط با سیاست برچسب حساسیتی که برچسب حساسیت را توصیف می‌کند را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن java.util.UUID.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.util.UUID |  |

### isEnabled() {#isEnabled--}
```
public abstract boolean isEnabled()
```

نشان می‌دهد آیا برچسب حساسیت فعال است یا نه.

**بازمی‌گرداند:**  
boolean

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public abstract void setEnabled(boolean value)
```

نشان می‌دهد آیا برچسب حساسیت فعال است یا نه.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isRemoved() {#isRemoved--}
```
public abstract boolean isRemoved()
```

نشان می‌دهد آیا برچسب حساسیت حذف شده است یا نه.

**بازمی‌گرداند:**  
boolean

### setRemoved(boolean value) {#setRemoved-boolean-}
```
public abstract void setRemoved(boolean value)
```

نشان می‌دهد آیا برچسب حساسیت حذف شده است یا نه.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getAssignmentMethodType() {#getAssignmentMethodType--}
```
public abstract int getAssignmentMethodType()
```

روش تخصیص برچسب حساسیت را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**بازمی‌گرداند:**  
int

### setAssignmentMethodType(int value) {#setAssignmentMethodType-int-}
```
public abstract void setAssignmentMethodType(int value)
```

روش تخصیص برچسب حساسیت را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/قابل نوشتن [SensitivityLabelAssignmentType](../../com.aspose.slides/sensitivitylabelassignmenttype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getContentMarkTypes() {#getContentMarkTypes--}
```
public abstract System.Collections.Generic.IGenericList<Integer> getContentMarkTypes()
```

فهرست انواع علامت‌گذاری محتوا که باید بر روی یک فایل اعمال شود را بازمی‌گرداند.

**بازمی‌گرداند:**  
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Integer> - فهرستی از انواع محتوا [SensitivityLabelContentType](../../com.aspose.slides/sensitivitylabelcontenttype)