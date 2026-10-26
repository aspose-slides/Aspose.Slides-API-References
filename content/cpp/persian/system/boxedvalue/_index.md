---
title: BoxedValue
second_title: مرجع API Aspose.Slides برای C++
description: "نمایش یک مقدار جعبه‌بندی‌شده. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا قطع‌نظر می‌شود. همواره این کلاس را درون اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای ارسال به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 105
url: /fa/system/boxedvalue/
---
## BoxedValue کلاس

نمایش یک مقدار جعبه‌بندی‌شده. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../makeobject/) تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا قطع‌نظر می‌شود. همیشه این کلاس را درون اشاره‌گر [System::SmartPtr](../smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به‌عنوان آرگومان استفاده کنید.

```cpp
template<class T>class BoxedValue : public System::BoxedValueBase,
                                    public std::conditional_t<BoxedValueDetail::ImplementsInterface_v<T, IComparable<T>>, BoxedValueDetail::Comparable<T, BoxedValue<T>>, BoxedValueDetail::NonComparable>
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T | نوع مقدار جعبه‌بندی‌شده که توسط کلاس نمایان می‌شود |

## متدها

| متد | توضیح |
| --- | --- |
|  [BoxedValue](./boxedvalue/)(const T\&) | یک شیء را می‌سازد که مقدار مشخص شده را به صورت جعبه‌بندی شده نشان می‌دهد. |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | برابری مقادیر جعبه‌بندی‌شده نمایان‌شده توسط شیء جاری و شیء مشخص‌شده را تعیین می‌کند. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که دو NaN را برابر در نظر می‌گیرد، هرچند طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که دو NaN را برابر در نظر می‌گیرد، هرچند طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | ساختار دادهٔ شمارنده ارجاع مرتبط با شیء را برمی‌گرداند. |
| int [GetHashCode](./gethashcode/)() const override | یک کد هش برای شیء جاری برمی‌گرداند. |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | نوع واقعی شیء را برمی‌گرداند. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const override | مقداری که نوع مقدار جعبه‌بندی‌شدهٔ نمایان‌شده توسط شیء جاری را نشان می‌دهد، برمی‌گرداند. |
| **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | مقدار عددی شیء جعبه‌بندی‌شده را در صورت امکان به‌نوع‌تبدیل می‌کند، در غیر این صورت صفر برمی‌گرداند. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه عملگر C# `is`. |
| **bool** [is](./is/)() const | تعیین می‌کند آیا نوع مقدار جعبه‌بندی‌شدهٔ نمایان‌شده توسط شیء جاری **V** است. |
| **bool** [IsBoxedEnum](./isboxedenum/)() override | تعیین می‌کند آیا شیء جاری مقدار جعبه‌بندی‌شده‌ای از نوع enum است. |
| void [Lock](../object/lock/)() | اجرای قفل‌گذاری عبارت C# `lock()` را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهدارندهٔ [LockContext](../lockcontext/) استفاده کنید. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | مشابه روش C# [Object.MemberwiseClone()](../object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../object/object/)() | شیء را می‌سازد. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../object/object/)([Object](../object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | عملگر انتساب. در واقع هیچ چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | مقدار ثابت شمارشی از enumeration مشخص‌شده را با نام مشخص‌شده جعبه‌بندی می‌کند. پارامتری مشخص می‌کند آیا هنگام تفسیر رشتهٔ نام ثابت شمارشی حروف بزرگ و کوچک نادیده گرفته شوند یا نه. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../boxedvaluebase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | مقدار ثابت شمارشی از enumeration مشخص‌شده را با نام مشخص‌شده جعبه‌بندی می‌کند. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | اشیاء را به‌صورت ارجاعی مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | اشیاء را به‌صورت ارجاعی مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه ارجاعی شیء از نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | تخصص [Object::ReferenceEquals](../object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | شمارش ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به یک اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مخازن به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را برمی‌گرداند. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| [String](../string/) [ToString](./tostring/)() const override | مقدار جعبه‌بندی‌شدهٔ نمایان‌شده توسط شیء جاری را به رشته تبدیل می‌کند. |
| [System::String](../string/) [ToString](../boxedvaluebase/tostring/)(const [System::String](../string/)\&) const | شیء جعبه‌بندی‌شده را با استفاده از رشتهٔ قالب‌گیری مشخص‌شده به رشته تبدیل می‌کند. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ساختار C# `typeof([System.Object](../object/))` را پیاده‌سازی می‌کند. |
| const T\& [unbox](./unbox/)() const | مقدار نمایان‌شده توسط شیء جاری را از جعبه خارج می‌کند. |
| void [Unlock](../object/unlock/)() | اجرای بازقفل‌گذاری عبارت C# `lock()` را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهدارندهٔ [LockContext](../lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## مراجع

* کلاس [BoxedValueBase](../boxedvaluebase/)
* فضای‌نام [System](../)
* کتابخانه [Aspose.Slides](../../)