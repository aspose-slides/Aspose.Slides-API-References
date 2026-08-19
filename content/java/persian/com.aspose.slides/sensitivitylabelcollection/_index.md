---
title: SensitivityLabelCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: مجموعه‌ای از برچسب‌های حساسیتی اعمال‌شده به سند را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/sensitivitylabelcollection/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

مجموعه‌ای از برچسب‌های حساسیتی اعمال‌شده به سند را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | برچسب حساسیتی را بر اساس اندیس برمی‌گرداند. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | برچسب حساسیتی را به انتهای مجموعه اضافه می‌کند. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | یک SensitivityLabel را به مجموعه اضافه می‌کند. |
| [removeAt(int index)](#removeAt-int-) | برچسب حساسیتی را در اندیس مشخص حذف می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [iterator()](#iterator--) | یک enumerator که از مجموعه پیمایش می‌کند را برمی‌گرداند. |
| [getCount()](#getCount--) | تعداد عناصر موجود در مجموعه را برمی‌گرداند. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | تمام عناصر را از مجموعه به آرایه مشخص شده کپی می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```


برچسب حساسیتی را بر اساس اندیس برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```


برچسب حساسیتی را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | java.lang.String | شناسه برچسب حساسیتی. |
| siteId | java.util.UUID | شناسه سایت Azure Active Directory (Azure AD). |
| isEnabled | boolean | پرچمی که نشان می‌دهد آیا برچسب حساسیتی فعال است یا خیر. |
| methodType | int | روش اختصاص برای برچسب حساسیتی. |

**بازگشت:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```


یک SensitivityLabel را به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | شیء SensitivityLabel که به انتهای مجموعه اضافه می‌شود. |

**بازگشت:**
int - شاخصی که SensitivityLabel در آن اضافه شد.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


برچسب حساسیتی را در اندیس مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس برچسب حساسیتی که باید حذف شود. |

### clear() {#clear--}
```
public final void clear()
```


تمام عناصر را از مجموعه حذف می‌کند.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```


یک enumerator که از مجموعه پیمایش می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - یک System.Collections.Generic.IEnumerator1 که می‌توان برای پیمایش مجموعه استفاده کرد.
### getCount() {#getCount--}
```
public final int getCount()
```


تعداد عناصر موجود در مجموعه را برمی‌گرداند. فقط-خواندنی  int .

**بازگشت:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```


تمام عناصر را از مجموعه به آرایه مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | آرایه هدف. |
| index | int | اندیس شروع در آرایه هدف. |