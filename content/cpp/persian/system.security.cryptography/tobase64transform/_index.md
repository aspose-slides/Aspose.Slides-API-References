---
title: ToBase64Transform
second_title: مرجع API Aspose.Slides برای C++
description: "نمونهٔ کلاس CryptoStream را به base 64 تبدیل می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() اختصاص داده شوند. هرگز نمونهٔ این نوع را روی پشته یا با استفاده از اپراتور new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات ادعا می‌شود. همیشه این کلاس را درون اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 664
url: /fa/system.security.cryptography/tobase64transform/
---
## ToBase64Transform کلاس


نمونهٔ کلاس [CryptoStream](../cryptostream/) را به base 64 تبدیل می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) اختصاص داده شوند. هیچ‌گاه نمونهٔ این نوع را روی پشته یا با استفاده از اپراتور new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات ادعای می‌شود. همیشه این کلاس را در داخل اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپوشانید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید.

```cpp
class ToBase64Transform : public System::Security::Cryptography::ICryptoTransform
```

## متدها

| متد | توضیح |
| --- | --- |
| void [Clear](./clear/)() | تمام منابع را آزاد می‌کند. |
| void [Dispose](./dispose/)() | منابع سیستم‌عامل به‌دست‌آمده توسط شیء جاری را آزاد می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | آبجکت‌ها را با استفاده از معناهای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه‌اعشار به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه‌اعشار به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر اساس IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **bool** [get_CanReuseTransform](./get_canreusetransform/)() | یک مقدار را برمی‌گرداند که نشان می‌دهد آیا تبدیل فعلی می‌تواند دوباره استفاده شود. |
| **bool** [get_CanTransformMultipleBlocks](./get_cantransformmultipleblocks/)() | یک مقدار را برمی‌گرداند که نشان می‌دهد آیا بلوک‌های متعدد می‌توانند تبدیل شوند. |
| virtual **int32_t** [get_InputBlockSize](./get_inputblocksize/)() | اندازه بلوک ورودی. |
| virtual **int32_t** [get_OutputBlockSize](./get_outputblocksize/)() | اندازه بلوک خروجی. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارشگر مرجع مرتبط با آبجکت را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | هم‌ساز متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری آبجکت‌های سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی آبجکت را برمی‌گرداند. هم‌ساز فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا آبجکت نمونه‌ای از نوع توصیف‌شده توسط targetType است. هم‌ساز عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری با دستور C# lock(). به صورت مستقیم صدا بزنید یا از شی sentinel [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | هم‌ساز متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | آبجکت ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط آبجکت جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از زیرکلاس‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط آبجکت جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از زیرکلاس‌ها را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | آبجکت‌ها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | آبجکت‌ها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع‌وار آبجکت نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به طور مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید به طور مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | هم‌ساز متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل آبجکت‌های سفارشی به رشته را فراهم می‌کند. |
| **int32_t** [TransformBlock](./transformblock/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**) | بلوک داده را پردازش می‌کند و داده‌ها را به آرایه خروجی کپی می‌کند. |
| virtual int [TransformBlock](../icryptotransform/transformblock/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | بلوک داده را پردازش می‌کند و داده‌ها را به آرایه خروجی کپی می‌کند. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [TransformFinalBlock](./transformfinalblock/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | آخرین بلوک داده را پردازش می‌کند و مقدار خروجی را محاسبه می‌کند. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [TransformFinalBlock](../icryptotransform/transformfinalblock/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | آخرین بلوک داده را پردازش می‌کند و مقدار خروجی را محاسبه می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | اجرای سازهٔ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل با دستور C# lock(). به صورت مستقیم صدا بزنید یا از شی sentinel [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به طور مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به طور مستقیم صدا زده شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | آبجکت را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |
| virtual  [~ToBase64Transform](./~tobase64transform/)() | تخریب‌کننده. |

## مراجع

* کلاس [ICryptoTransform](../icryptotransform/)
* فضای نام [System::Security::Cryptography](../)
* کتابخانه [Aspose.Slides](../../)