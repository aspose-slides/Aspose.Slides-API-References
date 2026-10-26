---
title: LoadingStreamBehavior
second_title: Aspose.Slides برای مرجع API C++
description: "System::IO::Stream که به یک متد پاس داده می‌شود به عنوان یک Binary Large Object (BLOB) در نظر گرفته می‌شود (به توصیف IBlobManagementOptions مراجعه کنید). مقادیر این شمارش مشخص می‌کنند که System::IO::Stream چگونه باید هنگام پاس شدن به متد رفتار شود. بسته به نیازها، تصمیمات مختلفی می‌توان اتخاذ کرد تا کارآمدترین رفتار فراهم شود."
type: docs
weight: 6735
url: /fa/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enum

شی [System::IO::Stream](../../system.io/stream/) که به یک متد ارسال می‌شود به عنوان یک Binary Large Object (BLOB) در نظر گرفته می‌شود (به توصیف [IBlobManagementOptions](../iblobmanagementoptions/) مراجعه کنید). مقادیر این شمارش مشخص می‌کنند که [System::IO::Stream](../../system.io/stream/) چه‌گونه باید هنگام ارسال به متد رفتار شود. بسته به نیازها، تصمیمات مختلف می‌توانند اتخاذ شوند تا کارآمدترین رفتار فراهم شود.

```cpp
enum class LoadingStreamBehavior
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | جریان تا انتها خوانده می‌شود و سپس آزاد می‌شود - به این معنی که تضمین می‌شود این جریان در آینده توسط نمونه [IPresentation](../ipresentation/) استفاده نخواهد شد. می‌توان آن را توسط کد مشتری بسته یا به هر شکل دیگری استفاده کرد. |
| KeepLocked | 1 | جریان در داخل شیء [IPresentation](../ipresentation/) قفل خواهد شد، یعنی مالکیت جریان انتقال می‌یابد. شیء [IPresentation](../ipresentation/) مسئول خواهد بود که به‌درستی جریان را هنگام از بین رفتن خود این شیء آزاد کند. این رفتار زمانی که نیاز به سریال‌سازی یک فایل BLOB بزرگ (مانند یک ویدیو یا صدای بزرگ - به توصیف [IBlobManagementOptions](../iblobmanagementoptions/) مراجعه کنید) دارید و می‌خواهید از بارگذاری این فایل در حافظه یا مشکلات عملکردی دیگر جلوگیری کنید، بسیار مفید است. می‌توانید فقط [System::IO::FileStream](../../system.io/filestream/) را برای این فایل باز کنید و به یک متد پاس دهید، با انتخاب [LoadingStreamBehavior::KeepLocked](./) LoadingStreamBehavior. |

## مطالب مرتبط

* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)