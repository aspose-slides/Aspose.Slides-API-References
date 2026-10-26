---
title: ColorMatrix
second_title: مرجع API Aspose.Slides برای C++
description: "نمایشگر یک ماتریس 5x5 است که مختصات فضای رنگ RGBAW را شامل می‌شود. اشیاء این کلاس باید تنها با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr پیچیده و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 27
url: /fa/system.drawing.imaging/colormatrix/
---
## ColorMatrix کلاس

نمایشگر یک ماتریس 5x5 است که مختصات فضای رنگ RGBAW را شامل می‌شود. اشیاء این کلاس باید تنها با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) پیچیده و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید.

```cpp
class ColorMatrix : public System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | یک نمونه جدید از کلاس [ColorMatrix](./) را می‌سازد و آن را با مقادیر ماتریس واحد مقداردهی اولیه می‌کند. |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | یک نمونه جدید از کلاس [ColorMatrix](./) را می‌سازد و آن را با مقادیر مشخص‌شده مقداردهی اولیه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌درازی سبک C# را شبیه‌سازی می‌کند؛ دو NaN را برابر در نظر می‌گیرد، هرچند طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌درازی سبک C# را شبیه‌سازی می‌کند؛ دو NaN را برابر در نظر می‌گیرد، هرچند طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **float** [get_Matrix00](./get_matrix00/)() const | مقداری در سطر 0 و ستون 0 بازمی‌گرداند. |
| **float** [get_Matrix01](./get_matrix01/)() const | مقداری در سطر 0 و ستون 1 بازمی‌گرداند. |
| **float** [get_Matrix02](./get_matrix02/)() const | مقداری در سطر 0 و ستون 2 بازمی‌گرداند. |
| **float** [get_Matrix03](./get_matrix03/)() const | مقداری در سطر 0 و ستون 3 بازمی‌گرداند. |
| **float** [get_Matrix04](./get_matrix04/)() const | مقداری در سطر 0 و ستون 4 بازمی‌گرداند. |
| **float** [get_Matrix10](./get_matrix10/)() const | مقداری در سطر 1 و ستون 0 بازمی‌گرداند. |
| **float** [get_Matrix11](./get_matrix11/)() const | مقداری در سطر 1 و ستون 1 بازمی‌گرداند. |
| **float** [get_Matrix12](./get_matrix12/)() const | مقداری در سطر 1 و ستون 2 بازمی‌گرداند. |
| **float** [get_Matrix13](./get_matrix13/)() const | مقداری در سطر 1 و ستون 3 بازمی‌گرداند. |
| **float** [get_Matrix14](./get_matrix14/)() const | مقداری در سطر 1 و ستون 4 بازمی‌گرداند. |
| **float** [get_Matrix20](./get_matrix20/)() const | مقداری در سطر 2 و ستون 0 بازمی‌گرداند. |
| **float** [get_Matrix21](./get_matrix21/)() const | مقداری در سطر 2 و ستون 1 بازمی‌گرداند. |
| **float** [get_Matrix22](./get_matrix22/)() const | مقداری در سطر 2 و ستون 2 بازمی‌گرداند. |
| **float** [get_Matrix23](./get_matrix23/)() const | مقداری در سطر 2 و ستون 3 بازمی‌گرداند. |
| **float** [get_Matrix24](./get_matrix24/)() const | مقداری در سطر 2 و ستون 4 بازمی‌گرداند. |
| **float** [get_Matrix30](./get_matrix30/)() const | مقداری در سطر 3 و ستون 0 بازمی‌گرداند. |
| **float** [get_Matrix31](./get_matrix31/)() const | مقداری در سطر 3 و ستون 1 بازمی‌گرداند. |
| **float** [get_Matrix32](./get_matrix32/)() const | مقداری در سطر 3 و ستون 2 بازمی‌گرداند. |
| **float** [get_Matrix33](./get_matrix33/)() const | مقداری در سطر 3 و ستون 3 بازمی‌گرداند. |
| **float** [get_Matrix34](./get_matrix34/)() const | مقداری در سطر 3 و ستون 4 بازمی‌گرداند. |
| **float** [get_Matrix40](./get_matrix40/)() const | مقداری در سطر 4 و ستون 0 بازمی‌گرداند. |
| **float** [get_Matrix41](./get_matrix41/)() const | مقداری در سطر 4 و ستون 1 بازمی‌گرداند. |
| **float** [get_Matrix42](./get_matrix42/)() const | مقداری در سطر 4 و ستون 2 بازمی‌گرداند. |
| **float** [get_Matrix43](./get_matrix43/)() const | مقداری در سطر 4 و ستون 3 بازمی‌گرداند. |
| **float** [get_Matrix44](./get_matrix44/)() const | مقداری در سطر 4 و ستون 4 بازمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| **float** [idx_get](./idx_get/)(int, int) | مقداری در سطر و ستون مشخص‌شده بازمی‌گرداند. |
| **float** [idx_set](./idx_set/)(int, int, **float**) | مقدار مشخص‌شده را در مکان مشخص در ماتریس تنظیم می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان نسخ‌برداری از انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را می‌دهد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_Matrix00](./set_matrix00/)(**float**) | مقداری را در سطر 0 و ستون 0 تنظیم می‌کند. |
| void [set_Matrix01](./set_matrix01/)(**float**) | مقداری را در سطر 0 و ستون 1 تنظیم می‌کند. |
| void [set_Matrix02](./set_matrix02/)(**float**) | مقداری را در سطر 0 و ستون 2 تنظیم می‌کند. |
| void [set_Matrix03](./set_matrix03/)(**float**) | مقداری را در سطر 0 و ستون 3 تنظیم می‌کند. |
| void [set_Matrix04](./set_matrix04/)(**float**) | مقداری را در سطر 0 و ستون 4 تنظیم می‌کند. |
| void [set_Matrix10](./set_matrix10/)(**float**) | مقداری را در سطر 1 و ستون 0 تنظیم می‌کند. |
| void [set_Matrix11](./set_matrix11/)(**float**) | مقداری را در سطر 1 و ستون 1 تنظیم می‌کند. |
| void [set_Matrix12](./set_matrix12/)(**float**) | مقداری را در سطر 1 و ستون 2 تنظیم می‌کند. |
| void [set_Matrix13](./set_matrix13/)(**float**) | مقداری را در سطر 1 و ستون 3 تنظیم می‌کند. |
| void [set_Matrix14](./set_matrix14/)(**float**) | مقداری را در سطر 1 و ستون 4 تنظیم می‌کند. |
| void [set_Matrix20](./set_matrix20/)(**float**) | مقداری را در سطر 2 و ستون 0 تنظیم می‌کند. |
| void [set_Matrix21](./set_matrix21/)(**float**) | مقداری را در سطر 2 و ستون 1 تنظیم می‌کند. |
| void [set_Matrix22](./set_matrix22/)(**float**) | مقداری را در سطر 2 و ستون 2 تنظیم می‌کند. |
| void [set_Matrix23](./set_matrix23/)(**float**) | مقداری را در سطر 2 و ستون 3 تنظیم می‌کند. |
| void [set_Matrix24](./set_matrix24/)(**float**) | مقداری را در سطر 2 و ستون 4 تنظیم می‌کند. |
| void [set_Matrix30](./set_matrix30/)(**float**) | مقداری را در سطر 3 و ستون 0 تنظیم می‌کند. |
| void [set_Matrix31](./set_matrix31/)(**float**) | مقداری را در سطر 3 و ستون 1 تنظیم می‌کند. |
| void [set_Matrix32](./set_matrix32/)(**float**) | مقداری را در سطر 3 و ستون 2 تنظیم می‌کند. |
| void [set_Matrix33](./set_matrix33/)(**float**) | مقداری را در سطر 3 و ستون 3 تنظیم می‌کند. |
| void [set_Matrix34](./set_matrix34/)(**float**) | مقداری را در سطر 3 و ستون 4 تنظیم می‌کند. |
| void [set_Matrix40](./set_matrix40/)(**float**) | مقداری را در سطر 4 و ستون 0 تنظیم می‌کند. |
| void [set_Matrix41](./set_matrix41/)(**float**) | مقداری را در سطر 4 و ستون 1 تنظیم می‌کند. |
| void [set_Matrix42](./set_matrix42/)(**float**) | مقداری را در سطر 4 و ستون 2 تنظیم می‌کند. |
| void [set_Matrix43](./set_matrix43/)(**float**) | مقداری را در سطر 4 و ستون 3 تنظیم می‌کند. |
| void [set_Matrix44](./set_matrix44/)(**float**) | مقداری را در سطر 4 و ستون 4 تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازقفل‌گذاری عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## مراجع

* کلاس [Object](../../system/object/)
* فضای‌نام [System::Drawing::Imaging](../)
* کتابخانه [Aspose.Slides](../../)