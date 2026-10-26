---
title: TryParse()
second_title: مرجع API Aspose.Slides برای C++
description: رشتهٔ مشخص‌شده که نمایانگر عددی است را به مقدار معادل Decimal تبدیل می‌کند.
type: docs
weight: 482
url: /fa/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) متد


رشتهٔ مشخص‌شده که نمایانگر عددی است را به مقدار معادل [Decimal](../) تبدیل می‌کند.

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود |
| result | [Decimal](../)\& | مرجع به متغیر [Decimal](../) که نتیجهٔ تبدیل در آن قرار می‌گیرد |

### مقدار بازگشتی

درست اگر تبدیل موفق باشد، در غیر اینصورت - نادرست

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) متد


رشتهٔ مشخص‌شده که نمایانگر عددی است را با استفاده از اطلاعات قالب‌بندی و سبک عددی ارائه‌شده به مقدار معادل [Decimal](../) تبدیل می‌کند.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | const [String](../../string/)\& | رشته‌ای که باید تبدیل شود |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | ترکیبی بیتی از مقادیر enum NumberStyles که سبک مجاز نمایانگر رشتهٔ عددی را مشخص می‌کند |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | اشاره‌گری به شیئی که اطلاعات قالب‌بندی رشته را شامل می‌شود |
| result | [Decimal](../)\& | یک آرگومان خروجی؛ شامل نتیجهٔ تبدیل است |

### مقدار بازگشتی

درست اگر تبدیل موفق باشد، در غیر اینصورت - نادرست

## موارد مرتبط

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Decimal](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)