---
title: StringBuilder
second_title: مرجع API Aspose.Slides برای C++
description: "بافر برای ترکیب رشته به‌صورت قطعه به قطعه. این نوع می‌تواند یا در پشته به‌عنوان نوع مقدار یا در هیپ با استفاده از تابع System::MakeObject() تخصیص یابد. پس از تخصیص شیء، هرگز این دو حالت استفاده را مخلوط نکنید: داشتن اشاره‌گرهای SmartPtr به اشیای تخصیص‌یافته در پشته به‌طور سفت و سخت ممنوع است."
type: docs
weight: 326
url: /fa/system.text/stringbuilder/
---
## StringBuilder کلاس


[Buffer](../../system/buffer/) برای ترکیب رشته به‌صورت قطعه به قطعه. این نوع می‌تواند یا در پشته به‌عنوان نوع مقدار یا در هیپ با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یابد. پس از تخصیص شیء، هرگز این دو حالت استفاده را مخلوط نکنید: داشتن اشاره‌گرهای [SmartPtr](../../system/smartptr/) به اشیای تخصیص‌یافته در پشته به‌طور سفت و سخت ممنوع است.

```cpp
class StringBuilder : public System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | یک کاراکتر را به سازنده اضافه می‌کند. |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | کاراکترها را به سازنده اضافه می‌کند. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | آرایه‌ای از کاراکترها را به سازنده اضافه می‌کند. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | بخش‌ای از آرایه کاراکترها را به سازنده اضافه می‌کند. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | یک رشته را به سازنده اضافه می‌کند. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | بخش‌ای از رشته را به سازنده اضافه می‌کند. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | نمایش رشته‌ای شیء را به سازنده اضافه می‌کند. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | محتوای سازنده را به سازنده اضافه می‌کند. |
| [StringBuilder](./) * [Append](./append/)(**float**) | یک مقدار عددی شناور را به سازنده اضافه می‌کند. |
| [StringBuilder](./) * [Append](./append/)(**double**) | یک مقدار عددی شناور را به سازنده اضافه می‌کند. |
| [StringBuilder](./) * [Append](./append/)(int) | یک مقدار صحیح را به سازنده اضافه می‌کند. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | یک مقدار عددی حسابی را به سازنده اضافه می‌کند. |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | نمایش رشته‌ای مقدار enum را به سازنده اضافه می‌کند. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | یک رشته قالب‌دار را به سازنده اضافه می‌کند. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | یک رشته قالب‌دار را به سازنده اضافه می‌کند. |
| [StringBuilder](./) * [AppendLine](./appendline/)() | کاراکتر خط جدید را به سازنده اضافه می‌کند. |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | یک رشته به‌همراه کاراکتر خط جدید را به سازنده اضافه می‌کند. |
| [StringBuilder](./) * [Clear](./clear/)() | تمام کاراکترها را از سازنده حذف می‌کند. |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | داده‌های سازنده را در موقعیت‌های موجود آرایه کپی می‌کند. |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | اطمینان می‌دهد که ظرفیت این نمونه از [System.Text.StringBuilder](./) حداقل مقدار مشخص شده باشد. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | شیء‌ها را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیء‌های نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیء‌های نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر طبق IEC 60559:1989 NaN برابر هیچ مقدار، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند بر طبق IEC 60559:1989 NaN برابر هیچ مقدار، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| int [get_Capacity](./get_capacity/)() const | ظرفیت فعلی سازنده رشته را دریافت می‌کند. |
| int [get_Length](./get_length/)() const | طول رشته فعلی در سازنده را دریافت می‌کند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده‌ شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری شیء‌های سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| char_t [idx_get](./idx_get/)(int) const | کاراکتر در موقعیت مشخص را دریافت می‌کند. |
| void [idx_set](./idx_set/)(int, char_t) | کاراکتر در موقعیت مشخص را تنظیم می‌کند. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | رشته را در موقعیت ثابت سازنده درج می‌کند. |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | رشته تکراری را در موقعیت ثابت سازنده درج می‌کند. |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | کاراکتر را در موقعیت ثابت سازنده درج می‌کند. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | کاراکترها را در موقعیت ثابت سازنده درج می‌کند. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | مقدار را در موقعیت ثابت سازنده درج می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیم صدا بزنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌آورد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌آورد. |
| char_t [operator[]](./operator[]/)(int) const | کاراکتر در موقعیت مشخص را دریافت می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | شیء‌ها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | شیء‌ها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr از طریق مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | بخشی از سازنده را حذف می‌کند. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | زیررشته را از طریق سازنده جایگزین می‌کند. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | زیررشته را در بازهٔ سازنده جایگزین می‌کند. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | کاراکتر را در سازنده جایگزین می‌کند. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | کاراکتر را در بازهٔ سازنده جایگزین می‌کند. |
| void [set_Capacity](./set_capacity/)(int) | ظرفیت فعلی سازنده رشته را تنظیم می‌کند. |
| void [set_Length](./set_length/)(int) | سازنده رشته را به طول مشخص کوتاه یا طولانی می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید مستقیماً صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [StringBuilder](./stringbuilder/)() | سازنده. |
|  [StringBuilder](./stringbuilder/)(int) | سازنده. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | سازنده. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | سازنده. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | سازنده. |
| [String](../../system/string/) [ToString](./tostring/)() const override | رشتهٔ فعلی موجود در سازنده را دریافت می‌کند. |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | زیررشتهٔ فعلی موجود در سازنده را دریافت می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری عبارت lock() در C# را باز می‌کند. مستقیم صدا بزنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |
|  [~StringBuilder](./~stringbuilder/)() | قالب‌ساز. |

## همچنین ببینید

* کلاس [Object](../../system/object/)
* فضای نام [System::Text](../)
* کتابخانه [Aspose.Slides](../../)