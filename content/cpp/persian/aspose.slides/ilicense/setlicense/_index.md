---
title: SetLicense()
second_title: راهنمای API Aspose.Slides برای C++
description: مجوزدهی به کامپوننت.
type: docs
weight: 1
url: /fa/aspose.slides/ilicense/setlicense/
---
## ILicense::SetLicense(System::String) متد

مجوزدهی به کامپوننت.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::String licenseName)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | می‌تواند نام کامل یا کوتاه فایل یا نام یک منبع جاسازی‌شده باشد. برای تغییر به حالت ارزیابی، یک رشته خالی استفاده کنید. |

## ملاحظات

سعی می‌کند مجوز را در مکان‌های زیر پیدا کند:

1. مسیر صریح.
2. پوشهٔ اسمبلی کامپوننت.
3. پوشهٔ اسمبلی فراخوانی‌کنندهٔ مشتری.
4. پوشهٔ اسمبلی ورودی.
5. یک منبع جاسازی‌شده در اسمبلی فراخوانی‌کنندهٔ مشتری.

**توجه:** در .NET Compact Framework، سعی می‌کند مجوز را فقط در این مکان‌ها پیدا کند:

1. مسیر صریح.
2. یک منبع جاسازی‌شده در اسمبلی فراخوانی‌کنندهٔ مشتری.

در این مثال، سعی خواهد شد تا فایلی به نام MyLicense.lic که حاوی مجوز است در پوشه‌ای که کامپوننت را شامل می‌شود، در پوشه‌ای که اسمبلی فراخوانی‌کننده را شامل می‌شود، در پوشهٔ اسمبلی ورودی و سپس در منابع جاسازی‌شدهٔ اسمبلی فراخوانی‌کننده پیدا شود.
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## ILicense::SetLicense(System::SharedPtr\<System::IO::Stream\>) متد

مجوزدهی به کامپوننت.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::SharedPtr<System::IO::Stream> stream)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | یک جریان که شامل مجوز است. |

## ملاحظات

از این متد برای بارگذاری مجوز از یک جریان استفاده کنید.

```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [String](../../../system/string/)
* کلاس [ILicense](../)
* کلاس [Stream](../../../system.io/stream/)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)