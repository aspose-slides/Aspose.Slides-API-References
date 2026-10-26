---
title: SetLicense()
second_title: Aspose.Slides برای مرجع API C++
description: مجوزدهی به کامپوننت.
type: docs
weight: 14
url: /fa/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) متد

مجوزدهی به کامپوننت.

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | می‌تواند نام کامل یا کوتاه فایل یا نام یک منبع تعبیه‌شده باشد. برای تغییر به حالت ارزیابی از رشته خالی استفاده کنید. |

## توضیحات

سعی می‌کند مجوز را در مکان‌های زیر پیدا کند:

1. مسیر صریح.
2. پوشه‌ای که اسمبلی کامپوننت در آن قرار دارد.
3. پوشه‌ای که اسمبلی فراخوانی‌کننده در آن قرار دارد.
4. پوشه‌ای که اسمبلی ورودی در آن قرار دارد.
5. یک منبع تعبیه‌شده در اسمبلی فراخوانی‌کننده مشتری.

**توجه:**On the .NET Compact Framework, tries to find the license only in these locations:

1. مسیر صریح.
2. یک منبع تعبیه‌شده در اسمبلی فراخوانی‌کننده مشتری.

در این مثال، سعی می‌شود فایل مجوزی به نام MyLicense.lic را در پوشه‌ای که کامپوننت در آن قرار دارد، در پوشه‌ای که اسمبلی فراخوانی‌کننده در آن قرار دارد، در پوشهٔ اسمبلی ورودی و سپس در منابع تعبیه‌شدهٔ اسمبلی فراخوانی‌کننده پیدا کند.
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) متد

مجوزدهی به کامپوننت.

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | یک جریان که شامل مجوز است. |

## توضیحات

از این متد برای بارگذاری مجوز از یک جریان استفاده کنید.

```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [License](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)