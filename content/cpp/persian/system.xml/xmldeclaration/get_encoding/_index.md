---
title: get_Encoding()
second_title: مرجع API Aspose.Slides برای C++
description: سطح رمزگذاری سند XML را برمی‌گرداند.
type: docs
weight: 14
url: /fa/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() متد

سطح رمزگذاری سند XML را برمی‌گرداند.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```

### مقدار بازگشتی

نام رمزگذاری کاراکتر معتبر.

## توضیحات



پراست‌ترین نام‌های رمزگذاری کاراکتر پشتیبانی‌شده برای XML به صورت زیر هستند: 

| دسته‌بندی | نام‌های رمزگذاری |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (where "n" is a digit from 1 to 9) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |


این مقدار اختیاری است. اگر مقداری تنظیم نشود، این متد [String::Empty](../../../system/string/empty/) را برمی‌گرداند. اگر خصوصیت رمزگذاری گنجانده نشده باشد، هنگام نوشتن یا ذخیرهٔ سند، رمزگذاری UTF-8 در نظر گرفته می‌شود. 
## مراجع

* کلاس [String](../../../system/string/)
* کلاس [XmlDeclaration](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)