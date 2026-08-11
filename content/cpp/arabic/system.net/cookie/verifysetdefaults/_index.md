---
title: VerifySetDefaults()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يتحقق ويضبط قيم السمات الافتراضية.
type: docs
weight: 482
url: /ar/system.net/cookie/verifysetdefaults/
---
## Cookie::VerifySetDefaults(CookieVariant, System::SharedPtr\<Uri\>, bool, String, bool, bool) طريقة

يتحقق ويضبط قيم السمات الافتراضية.

```cpp
bool System::Net::Cookie::VerifySetDefaults(CookieVariant variant, System::SharedPtr<Uri> uri, bool isLocalDomain, String localDomain, bool setDefault, bool shouldThrow)
```

### المعلمات

| معـامل | نوع | وصف |
| --- | --- | --- |
| variant | [CookieVariant](../../cookievariant/) | مواصفة الكوكي. |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | مثيل الفئة Uri الذي يُستخدم لتهيئة الحقول الداخلية. |
| isLocalDomain | **bool** | قيمة تشير إلى ما إذا كان الكوكي يُدفع إلى النطاق المحلي. |
| localDomain | [String](../../../system/string/) | اسم نطاق محلي. |
| setDefault | **bool** | قيمة تشير إلى ما إذا كان يجب تهيئة سمات الكوكي باستخدام القيم الافتراضية الخاصة بها. |
| shouldThrow | **bool** | قيمة تشير إلى ما إذا كان يجب رمية استثناء عندما تكون القيم المحددة غير صالحة. |

### القيمة المرجعة

True عندما تكون جميع القيم صالحة، وإلا false.

## انظر أيضًا

* عدد [CookieVariant](../../cookievariant/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Uri](../../../system/uri/)
* فئة [String](../../../system/string/)
* فئة [Cookie](../)
* فضاء الاسم [System::Net](../../)
* مكتبة [Aspose.Slides](../../../)