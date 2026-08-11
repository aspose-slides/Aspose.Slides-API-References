---
title: VerifySetDefaults()
second_title: Aspose.Slides برای C++ - مرجع API
description: مقادیر ویژگی پیش‌فرض را تأیید و تنظیم می‌کند.
type: docs
weight: 482
url: /fa/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) متد

مقدارهای ویژگی‌های پیش‌فرض را تأیید و تنظیم می‌کند.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | مشخصات کوکی. |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | نمونه‌ی کلاس Uri که برای مقداردهی اولیه فیلدهای داخلی استفاده می‌شود. |
| isLocalDomain | **bool** | مقداری که نشان می‌دهد آیا کوکی به دامنهٔ محلی اضافه می‌شود. |
| localDomain | [String](../../../system/string/) | نام دامنهٔ محلی. |
| setDefault | **bool** | مقداری که نشان می‌دهد آیا ویژگی‌های کوکی باید با مقادیر پیش‌فرضشان مقداردهی شوند. |
| shouldThrow | **bool** | مقداری که نشان می‌دهد آیا در صورت نامعتبر بودن مقادیر مشخص‌شده، استثنایی پرتاب شود. |

### مقدار بازگشت

True زمانی که همه مقادیر معتبر هستند، در غیر این صورت false.

## مراجع

* Enum [CookieVariant](../../cookievariant/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Uri](../../../system/uri/)
* کلاس [String](../../../system/string/)
* کلاس [Cookie](../)
* فضای نام [System::Net](../../)
* Library [Aspose.Slides](../../../)