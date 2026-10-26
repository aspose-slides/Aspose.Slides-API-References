---
title: IBulletFormat
second_title: Aspose.Slides برای C++ مرجع API
description: ویژگی‌های قالب‌بندی گلوله‌های پاراگراف را نمایان می‌کند.
type: docs
weight: 1561
url: /fa/aspose.slides/ibulletformat/
---
## IBulletFormat کلاس

نمایندهٔ ویژگی‌های قالب‌بندی bullet پاراگراف است.

```cpp
class IBulletFormat : public virtual System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() | مقدارهای پیش‌فرض غیر صفر را برای Indent و MarginLeft مؤثر پاراگراف تنظیم می‌کند هنگامی که bulletها فعال باشد (مانند کاری که PowerPoint انجام می‌دهد اگر در آن bulletها/شماره‌گذاری پاراگراف فعال شوند). اگر bulletها غیرفعال باشد، فقط Indent و MarginLeft پاراگراف را بازنشانی می‌کند (مانند کاری که PowerPoint انجام می‌دهد اگر bulletها/شماره‌گذاری پاراگراف را غیرفعال کند). تغییرات تورفتگی نسبت به زمینهٔ فعلی bullet – IBulletFormat::get(set)_Type، .NumberedBulletStyle و FontHeight اولین بخش – اعمال می‌شوند. مقادیر غیر صفر تغییرات تورفتگی بر روی Indent و MarginLeft مؤثر پاراگراف جاری اعمال می‌شوند (مقادیر نتیجه به‌صورت مقادیر محلی خواهند بود). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از قواعد C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌ی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌ی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual char16_t [get_Char](./get_char/)() | کاراکتر bullet یک پاراگراف بدون ارث‌بری را برمی‌گرداند. فقط خواندنی **wchar_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() | قالب رنگ یک bullet از پاراگراف بدون ارث‌بری را برمی‌گرداند. فقط خواندنی [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() | قلم bullet یک پاراگراف بدون ارث‌بری را برمی‌گرداند. فقط خواندنی [IFontData](../ifontdata/). |
| virtual **float** [get_Height](./get_height/)() | ارتفاع bullet یک پاراگراف بدون ارث‌بری را برمی‌گرداند. مقدار std::numeric_limits<float>::quiet_NaN() تعیین می‌کند که bullet ارتفاع را از اولین بخش پاراگراف ارث می‌برد. فقط خواندنی **float**. |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() | تعیین می‌کند که آیا bullet رنگ خود را دارد یا از اولین بخش پاراگراف ارث می‌برد. **[NullableBool::True](../nullablebool/)** اگر bullet رنگ خود را داشته باشد و **[NullableBool::False](../nullablebool/)** اگر رنگ را از اولین بخش ارث ببرد. فقط خواندنی [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() | تعیین می‌کند که آیا bullet قلم خود را دارد یا از اولین بخش پاراگراف ارث می‌برد. **[NullableBool::True](../nullablebool/)** اگر bullet قلم خود را داشته باشد و **[NullableBool::False](../nullablebool/)** اگر قلم را از اولین بخش ارث ببرد. فقط خواندنی [NullableBool](../nullablebool/). |
| virtual **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() | اولین عدد استفاده شده برای گروهی از bulletهای شماره‌دار بدون ارث‌بری را برمی‌گرداند. فقط خواندنی **int16_t**. |
| virtual [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() | سبک یک bullet شماره‌دار بدون ارث‌بری را برمی‌گرداند. فقط خواندنی [NumberedBulletStyle](../numberedbulletstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | تصویری که به عنوان bullet در پاراگراف بدون ارث‌بری استفاده می‌شود را برمی‌گرداند. فقط خواندنی [ISlidesPicture](../islidespicture/). |
| virtual [BulletType](../bullettype/) [get_Type](./get_type/)() | نوع bullet یک پاراگراف بدون ارث‌بری را برمی‌گرداند. فقط خواندنی [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شی را دریافت می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() | داده‌های قالب‌بندی مؤثر bullet را با اعمال ارث‌بری دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش C# [Object.GetHashCode()](../../system/object/gethashcode/) است. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/) است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شی نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is' است. |
| void [Lock](../../system/object/lock/)() | اجرای قفل کردن با عبارت C# lock() را پیاده‌سازی می‌کند. به‌طور مستقیم صدا بزنید یا از شی [LockContext](../../system/lockcontext/) sentinel استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) است. امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی کپی نمی‌کند، فقط شی جدید را مقداردهی اولیه می‌کند و امکان ساخت زیرکلاس‌های کپی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شی جدید را مقداردهی اولیه می‌کند و امکان ساخت زیرکلاس‌های کپی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_Char](./set_char/)(char16_t) | کاراکتر bullet یک پاراگراف بدون ارث‌بری را تنظیم می‌کند. نوشتنی **wchar_t**. |
| virtual void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | قلم bullet یک پاراگراف بدون ارث‌بری را تنظیم می‌کند. نوشتنی [IFontData](../ifontdata/). |
| virtual void [set_Height](./set_height/)(**float**) | ارتفاع bullet یک پاراگراف بدون ارث‌بری را تنظیم می‌کند. مقدار std::numeric_limits<float>::quiet_NaN() تعیین می‌کند که bullet ارتفاع را از اولین بخش پاراگراف ارث می‌برد. نوشتنی **float**. |
| virtual void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) | تعیین می‌کند که آیا bullet رنگ خود را دارد یا از اولین بخش پاراگراف ارث می‌برد. **[NullableBool::True](../nullablebool/)** اگر bullet رنگ خود را داشته باشد و **[NullableBool::False](../nullablebool/)** اگر رنگ را از اولین بخش ارث ببرد. نوشتنی [NullableBool](../nullablebool/). |
| virtual void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) | تعیین می‌کند که آیا bullet قلم خود را دارد یا از اولین بخش پاراگراف ارث می‌برد. **[NullableBool::True](../nullablebool/)** اگر bullet قلم خود را داشته باشد و **[NullableBool::False](../nullablebool/)** اگر قلم را از اولین بخش ارث ببرد. نوشتنی [NullableBool](../nullablebool/). |
| virtual void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) | اولین عدد استفاده شده برای گروهی از bulletهای شماره‌دار بدون ارث‌بری را تنظیم می‌کند. نوشتنی **int16_t**. |
| virtual void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) | سبک یک bullet شماره‌دار بدون ارث‌بری را تنظیم می‌کند. نوشتنی [NumberedBulletStyle](../numberedbulletstyle/). |
| virtual void [set_Type](./set_type/)([BulletType](../bullettype/)) | نوع bullet یک پاراگراف بدون ارث‌بری را تنظیم می‌کند. نوشتنی [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش C# [Object.ToString()](../../system/object/tostring/) است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای باز کردن قفل با عبارت C# lock() را پیاده‌سازی می‌کند. به‌طور مستقیم صدا بزنید یا از شی [LockContext](../../system/lockcontext/) sentinel استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شی را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)