---
title: ImageFormat
second_title: مرجع API Aspose.Slides برای C++
description: "قالب فایل یک تصویر را نشان می‌دهد. اشیای این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 131
url: /fa/system.drawing.imaging/imageformat/
---
## ImageFormat کلاس

نمایانگر قالب فایل یک تصویر است. اشیای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای پاس کردن به توابع به عنوان آرگومان استفاده کنید.

```cpp
class ImageFormat : public System::Object
```

## متدها

| Method | توضیح |
| --- | --- |
| **bool** [Equals](./equals/)([ImageFormatPtr](../imageformatptr/)) const | تعیین می‌کند که آیا قالب‌های تصویر نماینده توسط اشیای جاری و مشخص‌شده برابر هستند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیا را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیا از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌ی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند حتی اگر مطابق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌ی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند حتی اگر مطابق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| static [ImageFormatPtr](../imageformatptr/) [get_Bmp](./get_bmp/)() | یک اشاره‌گر اشتراکی به شی [ImageFormat](./) که قالب تصویر بیت‌مپ را نشان می‌دهد برمی‌گرداند. |
| static [ImageFormatPtr](../imageformatptr/) [get_Emf](./get_emf/)() | یک اشاره‌گر اشتراکی به شی [ImageFormat](./) که قالب متافایل پیشرفته را نشان می‌دهد برمی‌گرداند. |
| static [ImageFormatPtr](../imageformatptr/) [get_Exif](./get_exif/)() | یک اشاره‌گر اشتراکی به شی [ImageFormat](./) که قالب فایل تبادل‌پذیر [Image](../../system.drawing/image/) (Exif) را نشان می‌دهد برمی‌گرداند. |
| static [ImageFormatPtr](../imageformatptr/) [get_Gif](./get_gif/)() | یک اشاره‌گر اشتراکی به شی [ImageFormat](./) که قالب تصویر [Graphics](../../system.drawing/graphics/) Interchange Format (GIF) را نشان می‌دهد برمی‌گرداند. |
| [System::Guid](../../system/guid/) [get_Guid](./get_guid/)() const | GUID مرتبط با قالب تصویری که توسط شی جاری نمایانده شده است را برمی‌گرداند. |
| static [ImageFormatPtr](../imageformatptr/) [get_Icon](./get_icon/)() | یک اشاره‌گر اشتراکی به شی [ImageFormat](./) که قالب تصویر آیکون [Windows](../../system.windows/) را نشان می‌دهد برمی‌گرداند. |
| static [ImageFormatPtr](../imageformatptr/) [get_Jpeg](./get_jpeg/)() | یک اشاره‌گر اشتراکی به شی [ImageFormat](./) که قالب تصویر Joint Photographic Experts Group (JPEG) را نشان می‌دهد برمی‌گرداند. |
| static [ImageFormatPtr](../imageformatptr/) [get_MemoryBmp](./get_memorybmp/)() | یک اشاره‌گر اشتراکی به شی [ImageFormat](./) که قالب یک بیت‌مپ در حافظه را نشان می‌دهد برمی‌گرداند. |
| static [ImageFormatPtr](../imageformatptr/) [get_Png](./get_png/)() | یک اشاره‌گر اشتراکی به شی [ImageFormat](./) که قالب تصویر W3C Portable Network [Graphics](../../system.drawing/graphics/) (PNG) را نشان می‌دهد برمی‌گرداند. |
| static [ImageFormatPtr](../imageformatptr/) [get_Tiff](./get_tiff/)() | یک اشاره‌گر اشتراکی به شی [ImageFormat](./) که قالب تصویر Tagged [Image](../../system.drawing/image/) File Format (TIFF) را نشان می‌دهد برمی‌گرداند. |
| static [ImageFormatPtr](../imageformatptr/) [get_Wmf](./get_wmf/)() | یک اشاره‌گر اشتراکی به شی [ImageFormat](./) که قالب تصویر متافایل [Windows](../../system.windows/) (WMF) را نشان می‌دهد برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شی را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظیر متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیای سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را دریافت می‌کند. نظیر فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ImageFormat](./imageformat/)(const [System::Guid](../../system/guid/)\&) | یک نمونه از کلاس [ImageFormat](./) را می‌سازد که قالب تصویر مرتبط با GUID مشخص‌شده را نشان می‌دهد. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شی نماینده نمونه‌ای از نوع توصیف‌شده توسط targetType است. نظیر عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری با بیان C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظیر متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شی را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی کپی نمی‌کند، فقط شی جدید را مقداردهی اولیه می‌کند و اجازه می‌دهد زیرکلاس‌ها با کپی‌سازی ساخته شوند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شی جدید را مقداردهی اولیه می‌کند و اجازه می‌دهد زیرکلاس‌ها با کپی‌سازی ساخته شوند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیا را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیا را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع مقدار شی نوع ارزش با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع اشتراکی را به مقدار مشخص کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای اشتراکی) تنظیم می‌کند. اجازه می‌دهد اشاره‌گرها در مجموعه‌ها به حالت ضعیف تغییر کنند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع اشتراکی را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع اشتراکی را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)() const | این شی [ImageFormat](./) را به رشته‌ای قابل‌خواندن برای انسان تبدیل می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری با بیان C# lock() را باز می‌کند. مستقیماً فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شی را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای نام [System::Drawing::Imaging](../)
* کتابخانه [Aspose.Slides](../../)