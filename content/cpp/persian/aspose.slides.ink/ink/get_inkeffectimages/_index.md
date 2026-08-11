---
title: get_InkEffectImages()
second_title: Aspose.Slides برای C++ مرجع API
description: مجموعه‌ای از تصاویر سفارشی که برای شبیه‌سازی اثرات بصری قلم‌موهای جوهر استفاده می‌شود را برمی‌گرداند. این تصاویر هنگام رندر کردن جوهر با مقادیر خاص InkEffectType، مانند Galaxy، Rainbow و غیره استفاده می‌شوند. با ارائه تصاویر خود می‌توانید کنترل کنید هر اثر جوهر چگونه ظاهر شود.
type: docs
weight: 14
url: /fa/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() متد

مجموعه‌ای از تصاویر سفارشی که برای شبیه‌سازی اثرات بصری قلم‌موهای جوهر استفاده می‌شوند را برمی‌گرداند. این تصاویر هنگام رندر کردن جوهر با مقادیر خاص [InkEffectType](../../inkeffecttype/)، مانند Galaxy، Rainbow و غیره استفاده می‌شوند. با ارائه تصاویر خودتان می‌توانید کنترل کنید هر اثر جوهر چگونه نمایش داده شود.

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## توضیحات

این خصوصیت امکان جایگزینی بافت‌های پیش فرض اثر جوهر را با موارد تعریف شده توسط کاربر فراهم می‌کند که به ویژه زمانی مفید است که دارایی‌های پیش فرض به دلیل مجوز محدود شوند یا در زمان اجرا در دسترس نباشند.

هر ورودی در دیکشنری باید یک مقدار [InkEffectType](../../inkeffecttype/) را با یک شیء [IImage](../../../aspose.slides/iimage/) متناظر (مثلاً Bitmap یا یک رابط تصویر **Aspose**) مرتبط کند.

```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## موارد مرتبط

* enum [InkEffectType](../../inkeffecttype/)
* typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IDictionary](../../../system.collections.generic/idictionary/)
* کلاس [IImage](../../../aspose.slides/iimage/)
* کلاس [Ink](../)
* فضای نام [Aspose::Slides::Ink](../../)
* کتابخانه [Aspose.Slides](../../../)