---
title: Random
second_title: مرجع API Aspose.Slides برای C++
description: "نمایش‌گر یک ژنراتور عدد تصادفی شبه‌تصادفی است. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 1184
url: /fa/system/random/
---
## کلاس Random


نمایش‌گر یک ژنراتور عدد تصادفی شبه‌تصادفی است. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../makeobject/) تخصیص یابند. هرگز نمونه‌ای از این نوع را بر روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../smartptr/) بپیچانید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید.

```cpp
class Random : public System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسه عددهای شناور به سبک C# که در آن دو NaN برابر درنظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN با هیچ مقداری برابر نیست، حتی NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسه عددهای شناور به سبک C# که در آن دو NaN برابر درنظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN با هیچ مقداری برابر نیست، حتی NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../object/gethashcode/). امکان هش کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوعی است که توسط targetType توصیف شده است. معادل عملگر C# 'is'. |
| **bool** [IsNull](./isnull/)() const | همیشه مقدار false را برمی‌گرداند. |
| void [Lock](../object/lock/)() | عملگر قفل‌گذاری (lock) در C# را پیاده‌سازی می‌کند. مستقیماً صدا زده شود یا از شیء نگهبان [LockContext](../lockcontext/) استفاده کنید. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| virtual **int32_t** [Next](./next/)() | یک عدد تصادفی غیرمنفی کمتر از حداکثر مقدار int32 را برمی‌گرداند. |
| virtual **int32_t** [Next](./next/)(**int32_t**) | یک عدد تصادفی غیرمنفی کمتر از حداکثر مشخص‌شده را برمی‌گرداند. |
| virtual **int32_t** [Next](./next/)(**int32_t**, **int32_t**) | یک عدد تصادفی در بازه مشخص‌شده برمی‌گرداند. |
| virtual void [NextBytes](./nextbytes/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | عناصر آرایه بایت مشخص‌شده را با اعداد تصادفی پر می‌کند. |
| virtual **double** [NextDouble](./nextdouble/)() | یک عدد تصادفی بین 0.0 و 1.0 برمی‌گرداند. |
|  [Object](../object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../object/object/)([Object](../object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی را کپی نمی‌کند؛ فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند؛ فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
|  [Random](./random/)() | یک نمونهٔ جدید را مقداردهی اولیه می‌کند، با استفاده از مقدار بذر پیش‌فرض وابسته به زمان. |
|  [Random](./random/)(**int32_t**) | یک نمونهٔ جدید از کلاس [System.Random](./) را با مقدار بذر مشخص‌شده مقداردهی اولیه می‌کند. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | مقدارشیء نوع مقدار را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصص‌سازی [Object::ReferenceEquals](../object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصص‌سازی [Object::ReferenceEquals](../object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | شمارنده مرجع‌اشتراکی را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../object/sharedcount/)() const | مقدار فعلی شمارنده مرجع‌اشتراکی را دریافت می‌کند. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | شمارنده مرجع‌اشتراکی را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | شمارنده مرجع‌اشتراکی را کاهش داده و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | معادل متد C# [Object.ToString()](../object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ساختار typeof([System.Object](../object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../object/unlock/)() | عملگر بازقفل‌گذاری (unlock) در C# را پیاده‌سازی می‌کند. مستقیماً صدا زده شود یا از شیء نگهبان [LockContext](../lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## ملاحظات



```cpp
#include "system/random.h"
#include "system/smart_ptr.h"
#include <iostream>

int main()
{
  const auto rnd = System::MakeObject<System::Random>();

  // دریافت یک عدد ماه تصادفی و چاپ آن.
  auto monthNumber = rnd->Next(1, 13);
  std::cout << "Month: " << monthNumber << std::endl;

  // پر کردن آرایه با اعداد تصادفی.
  auto arr = System::MakeObject<System::Array<uint8_t>>(12);
  rnd->NextBytes(arr);

  // چاپ آرایه.
  for (auto i = 0; i < arr->get_Length(); ++i)
  {
    std::cout << static_cast<int>(arr[i]) << ' ';
  }
  std::cout << std::endl;

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
Month: 4
177 213 89 240 68 182 18 96 109 131 1 78
*/
```

## مراجع

* کلاس [Object](../object/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)