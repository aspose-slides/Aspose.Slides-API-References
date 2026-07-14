---
title: ISensitivityLabelCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر مجموعه‌ای از برچسب‌های حساسیتی اعمال‌شده بر سند است.
type: docs
url: /fa/com.aspose.slides/isensitivitylabelcollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

نمایانگر مجموعه‌ای از برچسب‌های حساسیتی اعمال‌شده به سند است.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | برچسب حساسیتی را بر اساس اندیس برمی‌گرداند. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | برچسب حساسیتی را در انتهای مجموعه اضافه می‌کند. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | یک SensitivityLabel را به مجموعه اضافه می‌کند. |
| [removeAt(int index)](#removeAt-int-) | برچسب حساسیتی را در اندیس مشخص حذف می‌کند. |
| [clear()](#clear--) | تمام عناصر موجود در مجموعه را حذف می‌کند. |
| [getCount()](#getCount--) | تعداد تمام عناصر موجود در مجموعه را برمی‌گرداند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```


برچسب حساسیتی را بر اساس اندیس برمی‌گرداند. فقط-خواندنی [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```


برچسب حساسیتی را در انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | java.lang.String | شناسه برچسب حساسیتی. |
| siteId | java.util.UUID | شناسه سایت Azure Active Directory (Azure AD). |
| isEnabled | boolean | پرچم نشان می‌دهد که آیا برچسب حساسیتی فعال است یا خیر. |
| methodType | int | روش تخصیص برای برچسب حساسیتی. |

**بازگشت:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```


یک SensitivityLabel را به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | شیء SensitivityLabel برای اضافه شدن در انتهای مجموعه. |

**بازگشت:**
int - اندیسی که SensitivityLabel در آن اضافه شد.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


برچسب حساسیتی را در اندیس مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس برچسب حساسیتی که باید حذف شود. |

### clear() {#clear--}
```
public abstract void clear()
```


تمام عناصر موجود در مجموعه را حذف می‌کند.

### getCount() {#getCount--}
```
public abstract int getCount()
```


تعداد تمام عناصر موجود در مجموعه را برمی‌گرداند. فقط-خواندنی int .

**بازگشت:**
int