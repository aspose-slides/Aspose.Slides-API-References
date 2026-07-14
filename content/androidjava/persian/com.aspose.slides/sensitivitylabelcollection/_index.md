---
title: SensitivityLabelCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایش‌دهندهٔ مجموعه‌ای از برچسب‌های حساسیتی است که روی سند اعمال شده‌اند.
type: docs
url: /fa/com.aspose.slides/sensitivitylabelcollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)  
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

نمایش‌دهندهٔ مجموعه‌ای از برچسب‌های حساسیتی است که روی سند اعمال شده‌اند.

## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | برچسب حساسیتی را بر اساس اندیس برمی‌گرداند. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | برچسب حساسیتی را در انتهای مجموعه اضافه می‌کند. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | یک SensitivityLabel را به مجموعه اضافه می‌کند. |
| [removeAt(int index)](#removeAt-int-) | برچسب حساسیتی را در اندیس مشخص‌شده حذف می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [iterator()](#iterator--) | یک enumerator برمی‌گرداند که مجموعه را پیمایش می‌کند. |
| [getCount()](#getCount--) | تعداد عناصر موجود در مجموعه را برمی‌گرداند. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند. |

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


برچسب حساسیتی را در انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | java.lang.String | شناسهٔ برچسب حساسیتی. |
| siteId | java.util.UUID | شناسهٔ سایت Azure Active Directory (Azure AD). |
| isEnabled | boolean | پرچمی که نشان می‌دهد آیا برچسب حساسیتی فعال است یا نه. |
| methodType | int | روش انتساب برای برچسب حساسیتی. |

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
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | شیء SensitivityLabel که در انتهای مجموعه اضافه می‌شود. |

**بازگشت:**
int - اندیس‌ایی که SensitivityLabel در آن اضافه شده است.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


برچسب حساسیتی را در اندیس مشخص‌شده حذف می‌کند.

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


یک enumerator برمی‌گرداند که مجموعه را پیمایش می‌کند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - یک IEnumerator1 از System.Collections.Generic که می‌توان از آن برای پیمایش مجموعه استفاده کرد.
### getCount() {#getCount--}
```
public final int getCount()
```


تعداد عناصر موجود در مجموعه را برمی‌گرداند. فقط‌خواندنی  int .

**بازگشت:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```


تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | آرایه هدف. |
| index | int | اندیس شروع در آرایه هدف. |