---
title: Font
second_title: مرجع API Aspose.Slides برای C++
description: "نمایش‌دهندهٔ قالب خاصی برای متن است که شامل ظاهر قلم، اندازه و سبک می‌شود. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات اطمینان می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای انتقال به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 79
url: /fa/system.drawing/font/
---
## کلاس Font

نمایش‌دهنده قالب خاصی برای متن است که شامل نوع قلم، اندازه و سبک می‌باشد. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات اثبات می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای انتقال به توابع به‌عنوان آرگومان استفاده کنید.

```cpp
class Font : public System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Font](./)\> [Clone](./clone/)() | یک کپی از قلم فعلی را برمی‌گرداند. |
| void [Dispose](./dispose/)() | تمام منابع سیستم‌عامل دریافت‌شده توسط شیء فعلی را آزاد می‌کند. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | تشخیص می‌دهد که آیا شیء فعلی و شیء مشخص‌شده یکسان هستند یا خیر. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | شیء‌ها را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیء‌های نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه‌ی نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر مبنای IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه‌ی نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر مبنای IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[Font](./)\>\&, [FontStyle](../fontstyle/)) | یک نمونه جدید از کلاس [Font](./) ایجاد می‌کند که نمایانگر قلم موجود مشخص‌شده با سبک قلم مشخص‌شده است. |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\>\&, **float**, [FontStyle](../fontstyle/), [GraphicsUnit](../graphicsunit/), **uint8_t**, **bool**) | یک نمونه جدید از کلاس [Font](./) ایجاد می‌کند. |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\>\&, **float**, [GraphicsUnit](../graphicsunit/)) | یک نمونه جدید از کلاس [Font](./) ایجاد می‌کند. |
|  [Font](./font/)(const [String](../../system/string/)\&, **float**, [FontStyle](../fontstyle/), [GraphicsUnit](../graphicsunit/), **uint8_t**, **bool**) | یک نمونه جدید از کلاس [Font](./) ایجاد می‌کند. |
|  [Font](./font/)(const [String](../../system/string/)\&, **float**, [GraphicsUnit](../graphicsunit/)) | یک نمونه جدید از کلاس [Font](./) ایجاد می‌کند. |
| static [SharedPtr](../../system/sharedptr/)\<[Font](./)\> [FromLogFont](./fromlogfont/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | پیاده‌سازی نشده. |
| **bool** [get_Bold](./get_bold/)() | تشخیص می‌دهد که آیا قلم نمایانگر توسط شیء فعلی، سبک بولد دارد یا خیر. |
| [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\> [get_FontFamily](./get_fontfamily/)() | خانواده‌ی قلم را که توسط شیء فعلی نمایانده شده است، برمی‌گرداند. |
| [FontStyle](../fontstyle/) [get_FontStyle](./get_fontstyle/)() | سبک قلم را که توسط شیء فعلی نمایانده شده است، برمی‌گرداند. |
| **uint8_t** [get_GdiCharSet](./get_gdicharset/)() | یک مقدار را برمی‌گرداند که مجموعه کاراکترهای GDI استفاده‌شده توسط قلم نمایانده شده توسط شیء فعلی را نشان می‌دهد. |
| int [get_Height](./get_height/)() | فاصله خطوط قلم نمایانده شده توسط شیء فعلی را به پیکسل برمی‌گرداند. |
| **bool** [get_Italic](./get_italic/)() | تشخیص می‌دهد که آیا قلم نمایانده شده توسط شیء فعلی، سبک ایتالیک دارد یا خیر. |
| [String](../../system/string/) [get_Name](./get_name/)() | نام چهره (face name) قلم نمایانده شده توسط شیء فعلی را برمی‌گرداند. |
| [String](../../system/string/) [get_OriginalFontName](./get_originalfontname/)() | نام اصلی مشخص‌شده‌ی قلم را برمی‌گرداند. |
| **float** [get_Size](./get_size/)() | اندازه‌ی em قلم نمایانده شده توسط شیء فعلی را که بر حسب واحدهای تعیین‌شده توسط ویژگی Unit اندازه‌گیری می‌شود، برمی‌گرداند. |
| **float** [get_SizeInPoints](./get_sizeinpoints/)() | اندازه‌ی em قلم نمایانده شده توسط شیء فعلی را به نکته (points) برمی‌گرداند. |
| **bool** [get_Strikeout](./get_strikeout/)() | تشخیص می‌دهد که آیا قلم نمایانده شده توسط شیء فعلی، سبک خط‌خورده دارد یا خیر. |
| [FontStyle](../fontstyle/) [get_Style](./get_style/)() | سبک قلم را که توسط شیء فعلی نمایانده شده است، برمی‌گرداند. |
| **bool** [get_Underline](./get_underline/)() | تشخیص می‌دهد که آیا قلم نمایانده شده توسط شیء فعلی، سبک زیرخط دارد یا خیر. |
| [GraphicsUnit](../graphicsunit/) [get_Unit](./get_unit/)() | واحد اندازه‌گیری قلم نمایانده شده توسط شیء فعلی را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده‌ی شمارنده‌ی مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نماد روش [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری شیء‌های سفارشی را فراهم می‌کند. |
| **float** [GetHeight](./getheight/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | فاصله خطوط قلم نمایانده شده توسط شیء فعلی را در واحد جاری یک شیء [Graphics](../graphics/) مشخص‌شده برمی‌گرداند. |
| **float** [GetHeight](./getheight/)(**float**) | ارتفاع قلم نمایانده شده توسط شیء فعلی را هنگام رسم بر روی یک دستگاه نمایش با وضوح عمودی مشخص‌شده برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است یا خیر. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری با دستور lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نماد روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده‌ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی زیرکلاس‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی زیرکلاس‌ها را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | شیء‌ها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | شیء‌ها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع‌ای شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارش مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارش مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارش مرجع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نماد روش [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل شیء‌های سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای باز کردن قفل با دستور lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارش مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارش مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## مراجع

* کلاس [Object](../../system/object/)
* فضای نام [System::Drawing](../)
* کتابخانه [Aspose.Slides](../../)