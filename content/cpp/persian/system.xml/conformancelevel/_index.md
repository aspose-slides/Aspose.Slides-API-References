---
title: ConformanceLevel
second_title: Aspose.Slides for C++ مرجع API
description: مقدار بررسی ورودی یا خروجی که اشیاء XmlReader و XmlWriter انجام می‌دهند را مشخص می‌کند.
type: docs
weight: 625
url: /fa/system.xml/conformancelevel/
---
## ConformanceLevel enum

مقدار بررسی ورودی یا خروجی که اشیاء [XmlReader](../xmlreader/) و [XmlWriter](../xmlwriter/) انجام می‌دهند را تعیین می‌کند.

```cpp
enum class ConformanceLevel
```

### Values

| نام | مقدار | توضیح |
| --- | --- | --- |
| Auto | 0 | شیء [XmlReader](../xmlreader/) یا [XmlWriter](../xmlwriter/) به‌طور خودکار تشخیص می‌دهد که آیا بررسی در سطح سند یا سطح بخش باید انجام شود و بررسی مناسب را انجام می‌دهد. اگر شما یک شیء [XmlReader](../xmlreader/) یا [XmlWriter](../xmlwriter/) دیگر را بسته‌بندی کنید، شیء بیرونی هیچ بررسی انطباق اضافی انجام نمی‌دهد. بررسی انطباق به عهدهٔ شیء زیرین می‌ماند. |
| Fragment | 1 | داده‌های XML یک [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities) هستند، همان‌طور که W3C تعریف کرده است. این سطح انطباق نمایانگر یک سند XML است که ممکن است ریشه‌ای نداشته باشد اما به‌جز این، به‌درستی ساختاربندی شده است. این سطح بررسی تضمین می‌کند که جریان خوانده‌شده یا نوشته‌شده می‌تواند توسط هر پردازشی به‌عنوان یک [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities) مصرف شود. |
| Document | 2 | داده‌های XML با قوانین یک [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) به‌درستی ساختاربندی شده، همان‌طور که W3C تعریف کرده است، سازگار است. این سطح بررسی تضمین می‌کند که جریان خوانده‌شده یا نوشته‌شده می‌تواند توسط هر پردازشی به‌عنوان یک [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) مصرف شود. |

## موارد مرتبط

* فضای نام [System::Xml](../)
* کتابخانه [Aspose.Slides](../../)