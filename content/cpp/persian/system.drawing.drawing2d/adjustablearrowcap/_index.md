---
title: AdjustableArrowCap
second_title: مرجع API Aspose.Slides برای C++
description: "نمایانگر یک cap خطی به شکل پیکان قابل تنظیم است. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را بر روی stack یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های اعتبارسنجی می‌شود. همیشه این کلاس را در اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به‌عنوان آرگومان به توابع استفاده کنید."
type: docs
weight: 1
url: /fa/system.drawing.drawing2d/adjustablearrowcap/
---
## AdjustableArrowCap کلاس

یک cap خطی به شکل پیکان قابل تنظیم را نمایش می‌دهد. شیءهای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی stack یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) قرار داده و از این اشاره‌گر برای انتقال به توابع به عنوان آرگومان استفاده کنید.

```cpp
class AdjustableArrowCap : public System::Drawing::Drawing2D::CustomLineCap
```

## متدها

| متد | توضیح |
| --- | --- |
| [AdjustableArrowCap](./adjustablearrowcap/)(**float**, **float**, **bool**) | یک نمونه جدید از [AdjustableArrowCap](./) را با عرض و ارتفاع مشخص می‌سازد. |
| virtual [SharedPtr](../../system/sharedptr/)\<[CustomLineCap](../customlinecap/)\> [Clone](../customlinecap/clone/)() | یک نسخه از شیء فعلی را برمی‌گرداند. |
| [CustomLineCap](../customlinecap/customlinecap/)(const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[GraphicsPath](../graphicspath/)\>\&, [LineCap](../linecap/), **float**) | یک نمونه جدید از کلاس [CustomLineCap](../customlinecap/) که یک cap خطی تعریف‌شده توسط کاربر با ویژگی‌های مشخص را نمایش می‌دهد، می‌سازد. |
| void [Dispose](../customlinecap/dispose/)() | تمام منابع سیستم‌عامل به‌دست آمده توسط شیء فعلی را آزاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | شیءها را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیءهای نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیءهای نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه ممیز شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه ممیز شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| [LineCap](../linecap/) [get_BaseCap](../customlinecap/get_basecap/)() const | base line cap که این cap سفارشی از آن ایجاد شده است را برمی‌گرداند. |
| **float** [get_BaseInset](../customlinecap/get_baseinset/)() const | فاصله بین خط و cap را برمی‌گرداند. |
| **bool** [get_Filled](./get_filled/)() const | مقداری را برمی‌گرداند که نشان می‌دهد آیا پیکان نمایان‌شده توسط شیء فعلی پر شده است یا نه. |
| **float** [get_Height](./get_height/)() const | ارتفاع پیکان نمایان‌شده توسط شیء فعلی را برمی‌گرداند. |
| **float** [get_MiddleInset](./get_middleinset/)() const | فاصله بین خط و cap نمایان‌شده توسط شیء فعلی را تنظیم می‌کند. |
| [LineJoin](../linejoin/) [get_StrokeJoin](../customlinecap/get_strokejoin/)() const | مقدار LineJoin را برمی‌گرداند که تعیین می‌کند خطوط این cap سفارشی چگونه به هم پیوسته می‌شوند. |
| **float** [get_Width](./get_width/)() const | عرض پیکان نمایان‌شده توسط شیء فعلی را برمی‌گرداند. |
| **float** [get_WidthScale](../customlinecap/get_widthscale/)() const | مقیاس این cap سفارشی را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری شیءهای سفارشی را فراهم می‌کند. |
| void [GetStrokeCaps](../customlinecap/getstrokecaps/)([LineCap](../linecap/)\&, [LineCap](../linecap/)\&) | capهای خط شروع و پایان را که توسط شیء فعلی نمایان‌گر cap سفارشی هستند، دریافت می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایان‌گر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری توسط دستور C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی شود یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیز را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کلاس‌های فرزند از طریق کپی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیز را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کلاس‌های فرزند از طریق کپی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | شیءها را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | شیءها را بر پایه مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_BaseCap](../customlinecap/set_basecap/)([LineCap](../linecap/)) | مقدار base line cap را برای این cap سفارشی تنظیم می‌کند. |
| void [set_BaseInset](../customlinecap/set_baseinset/)(**float**) | فاصله بین خط و cap را تنظیم می‌کند. |
| void [set_Filled](./set_filled/)(**bool**) | مقدار را تنظیم می‌کند که تعیین می‌کند آیا پیکان نمایان‌شده توسط شیء فعلی پر شده است یا نه. |
| void [set_Height](./set_height/)(**float**) | ارتفاع پیکان نمایان‌شده توسط شیء فعلی را تنظیم می‌کند. |
| void [set_MiddleInset](./set_middleinset/)(**float**) | فاصله بین خط و cap نمایان‌شده توسط شیء فعلی را تنظیم می‌کند. |
| void [set_StrokeJoin](../customlinecap/set_strokejoin/)([LineJoin](../linejoin/)) | مقدار LineJoin را تنظیم می‌کند که تعیین می‌کند خطوط این cap سفارشی چگونه به هم پیوسته می‌شوند. |
| void [set_Width](./set_width/)(**float**) | عرض پیکان نمایان‌شده توسط شیء فعلی را تنظیم می‌کند. |
| void [set_WidthScale](../customlinecap/set_widthscale/)(**float**) | مقدار مقیاس این cap سفارشی را تنظیم می‌کند. |
| void [SetStrokeCaps](../customlinecap/setstrokecaps/)([LineCap](../linecap/), [LineCap](../linecap/)) | capهای خط شروع و پایان را که توسط شیء فعلی نمایان‌گر cap سفارشی هستند، تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و بر می‌گرداند. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل شیءهای سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی توسط دستور C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی شود یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [CustomLineCap](../customlinecap/)
* فضای نام [System::Drawing::Drawing2D](../)
* کتابخانه [Aspose.Slides](../../)