---
title: "System::Runtime::Serialization"
second_title: Aspose.Slides برای C++ مرجع API
description: 
type: docs
weight: 794
url: /fa/system.runtime.serialization/
---
## کلاس‌ها

| کلاس | توضیح |
| --- | --- |
| [Details_SerializationException](./details_serializationexception/) |  |
| [FormatterConverter](./formatterconverter/) | نمایانگر یک پیاده‌سازی پایه از رابط [System::Runtime::Serialization::IFormatterConverter](./iformatterconverter/) است. |
| [IFormatterConverter](./iformatterconverter/) | اتصال بین یک نمونه از [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) و کلاسی که توسط قالب‌بند فراهم شده و بهترین تطبیق برای تجزیه داده‌های داخل [System::Runtime::Serialization::SerializationInfo](./serializationinfo/) را دارد را فراهم می‌کند. |
| [ISerializable](./iserializable/) | رابط شیئی که قابل سریالیزه شدن است. اشیاء این کلاس باید فقط با تابع [System::MakeObject()](../system/makeobject/) تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../system/smartptr/) بپیچید و از این اشاره‌گر برای پاس کردن به توابع به عنوان آرگومان استفاده کنید. |
| [SerializationInfo](./serializationinfo/) | مجموعه‌ای از فیلدهای نام‌دار که شیء سریالیزه‌شده را نمایند، نگه می‌دارد. پیاده‌سازی نشده است. اشیاء این کلاس باید فقط با تابع [System::MakeObject()](../system/makeobject/) تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../system/smartptr/) بپیچید و از این اشاره‌گر برای پاس کردن به توابع به عنوان آرگومان استفاده کنید. |
| [StreamingContext](./streamingcontext/) | کلاس ساختگی برای امکان کامپایل کلاس‌های ترجمه‌شده استفاده‌کننده از StreamingContext. از [SmartPtr](../system/smartptr/) برای مدیریت نمونه‌های این کلاس استفاده نکنید، آنها باید فقط روی پشته تخصیص یابند. |

## تعاریف نوع

| تایپ‌دِف | توضیح |
| --- | --- |
| [SerializationException](./serializationexception/) |  |