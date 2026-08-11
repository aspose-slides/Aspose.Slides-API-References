---
title: ImageAttributes
second_title: مرجع API Aspose.Slides برای C++
description: "اطلاعاتی را در مورد چگونگی دستکاری رنگ‌های تصویر در طول رندر ارائه می‌دهد. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای assertion می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 105
url: /fa/system.drawing.imaging/imageattributes/
---
## ImageAttributes کلاس

اطلاعاتی را دربارهٔ نحوهٔ دستکاری رنگ‌های تصویر در طول رندر ارائه می‌دهد. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای assertion می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای پاس دادن به توابع به عنوان آرگومان استفاده کنید.

```cpp
class ImageAttributes : public System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| void [ClearBrushRemapTable](./clearbrushremaptable/)() | پیاده‌سازی نشده. |
| void [ClearColorKey](./clearcolorkey/)([ColorAdjustType](../coloradjusttype/)) | پیاده‌سازی نشده. |
| void [ClearColorMatrix](./clearcolormatrix/)([ColorAdjustType](../coloradjusttype/)) | پیاده‌سازی نشده. |
| void [ClearGamma](./cleargamma/)([ColorAdjustType](../coloradjusttype/)) | پیاده‌سازی نشده. |
| void [ClearNoOp](./clearnoop/)([ColorAdjustType](../coloradjusttype/)) | پیاده‌سازی نشده. |
| void [ClearOutputChannel](./clearoutputchannel/)([ColorAdjustType](../coloradjusttype/)) | پیاده‌سازی نشده. |
| void [ClearOutputChannelColorProfile](./clearoutputchannelcolorprofile/)([ColorAdjustType](../coloradjusttype/)) | پیاده‌سازی نشده. |
| void [ClearRemapTable](./clearremaptable/)([ColorAdjustType](../coloradjusttype/)) | پیاده‌سازی نشده. |
| void [ClearThreshold](./clearthreshold/)([ColorAdjustType](../coloradjusttype/)) | پیاده‌سازی نشده. |
| [SharedPtr](../../system/sharedptr/)\<[ImageAttributes](./)\> [Clone](./clone/)() | یک نسخهٔ کپی از شیء فعلی ایجاد می‌کند. |
| void [Dispose](./dispose/)() | تمام منابع سیستم‌عامل که توسط شیء فعلی به دست آمده‌اند را آزاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| void [GetAdjustedPalette](./getadjustedpalette/)(const [SharedPtr](../../system/sharedptr/)\<[ColorPalette](../colorpalette/)\>\&, [ColorAdjustType](../coloradjusttype/)) | پیاده‌سازی نشده. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
|  [ImageAttributes](./imageattributes/)() | سازنده پیش‌فرض. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل کردن با عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان سازندهٔ کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع شيئی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان سازندهٔ کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع‌دار شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع اشتراکی را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [SetBrushRemapTable](./setbrushremaptable/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[ColorMap](../colormap/)\>\>\&) | پیاده‌سازی نشده. |
| void [SetColorKey](./setcolorkey/)([Color](../../system.drawing/color/), [Color](../../system.drawing/color/), [ColorAdjustType](../coloradjusttype/)) | پیاده‌سازی نشده. |
| void [SetColorMatrices](./setcolormatrices/)(const [SharedPtr](../../system/sharedptr/)\<[ColorMatrix](../colormatrix/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[ColorMatrix](../colormatrix/)\>\&, [ColorMatrixFlag](../colormatrixflag/), [ColorAdjustType](../coloradjusttype/)) | پیاده‌سازی نشده. |
| void [SetColorMatrix](./setcolormatrix/)(const [SharedPtr](../../system/sharedptr/)\<[ColorMatrix](../colormatrix/)\>\&, [ColorMatrixFlag](../colormatrixflag/), [ColorAdjustType](../coloradjusttype/)) | ماتریس تنظیم رنگ را تنظیم می‌کند. |
| void [SetGamma](./setgamma/)(**float**, [ColorAdjustType](../coloradjusttype/)) | پیاده‌سازی نشده. |
| void [SetNoOp](./setnoop/)([ColorAdjustType](../coloradjusttype/)) | پیاده‌سازی نشده. |
| void [SetOutputChannel](./setoutputchannel/)([ColorChannelFlag](../colorchannelflag/), [ColorAdjustType](../coloradjusttype/)) | پیاده‌سازی نشده. |
| void [SetOutputChannelColorProfile](./setoutputchannelcolorprofile/)(const [String](../../system/string/)\&, [ColorAdjustType](../coloradjusttype/)) | پیاده‌سازی نشده. |
| void [SetRemapTable](./setremaptable/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[ColorMap](../colormap/)\>\>\&, [ColorAdjustType](../coloradjusttype/)) | پیاده‌سازی نشده. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| void [SetThreshold](./setthreshold/)(**float**, [ColorAdjustType](../coloradjusttype/)) | پیاده‌سازی نشده. |
| void [SetWrapMode](./setwrapmode/)([Drawing2D::WrapMode](../../system.drawing.drawing2d/wrapmode/), [Color](../../system.drawing/color/), **bool**) | حالت بسته‌بندی و رنگ مورد استفاده برای تصمیم‌گیری دربارهٔ چیدمان تکسچر روی یک شکل یا در مرزهای شکل را تنظیم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع اشتراکی را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع اشتراکی را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای‌نام [System::Drawing::Imaging](../)
* کتابخانه [Aspose.Slides](../../)