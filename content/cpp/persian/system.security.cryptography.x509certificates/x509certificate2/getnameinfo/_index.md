---
title: GetNameInfo()
second_title: مرجع API Aspose.Slides برای C++
description: نام صاحب یا صادرکننده را از گواهی دریافت می‌کند.
type: docs
weight: 248
url: /fa/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const متد

نام صاحب یا صادرکننده را از گواهی دریافت می‌کند.

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | گزینه‌های فرمت‌بندی نام. |
| for_issuer | **bool** | اگر true باشد، نام صادرکننده را بازمی‌گرداند، در غیر این صورت نام صاحب را بازمی‌گرداند. |

### مقدار بازگشت

نام قالب‌بندی‌شدهٔ صادرکننده یا صاحب.

## موارد مرتبط

* Enum [X509NameType](../../x509nametype/)
* کلاس [String](../../../system/string/)
* کلاس [X509Certificate2](../)
* فضای‌نام [System::Security::Cryptography::X509Certificates](../../)
* کتابخانه [Aspose.Slides](../../../)