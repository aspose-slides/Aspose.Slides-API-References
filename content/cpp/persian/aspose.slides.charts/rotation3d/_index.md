---
title: Rotation3D
second_title: Aspose.Slides برای C++ مرجع API
description: چرخش سه‌بعدی یک نمودار را نشان می‌دهد.
type: docs
weight: 1327
url: /fa/aspose.slides.charts/rotation3d/
---
## Rotation3D کلاس

Represents 3D rotation of a chart.

```cpp
class Rotation3D : public Aspose::Slides::Charts::IRotation3D,
                   public Aspose::Slides::IDOMObject
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **uint16_t** [get_DepthPercents](./get_depthpercents/)() override | عمق یک نمودار سه‌بعدی را به‌عنوان درصدی از عرض نمودار (بین 20 تا 2000 درصد) برمی‌گرداند. خواندن **uint16_t**. |
| **uint16_t** [get_HeightPercents](./get_heightpercents/)() override | ارتفاع یک نمودار سه‌بعدی را به‌عنوان درصدی از عرض نمودار (بین 5 تا 500 درصد) تعیین می‌کند. خواندن **uint16_t**. |
| **uint8_t** [get_Perspective](./get_perspective/)() override | مقدار پرسپکتیو (زاویه میدان دید) برای نمودارهای سه‌بعدی (بین 0 تا 240) را برمی‌گرداند. اگر مقدار ویژگی RightAngleAxes برابر true باشد، نادیده گرفته می‌شود. خواندن **uint8_t**. |
| **bool** [get_RightAngleAxes](./get_rightangleaxes/)() override | تشخیص می‌دهد که آیا محورهای نمودار به‌صورت زاویه‌دار (right angles) هستند یا در پرسپکتیو رسم می‌شوند. به عبارت دیگر، تعیین می‌کند که آیا زوایای محورهای نمودار مستقل از چرخش یا ارتفاع نمودار هستند. خواندن **bool**. |
| **int8_t** [get_RotationX](./get_rotationx/)() override | درجه چرخش حول محور X (در جهت Y) برای نمودارهای سه‌بعدی (بین -90 تا 90 درجه) را برمی‌گرداند. این ویژگی با مورد 21.2.2.157 rotX (X Rotation) در ECMA-376 و گزینه «Y Rotation» در PowerPoint 2007+ مطابقت دارد. خواندن **int8_t**. |
| **uint16_t** [get_RotationY](./get_rotationy/)() override | درجه چرخش حول محور Y (در جهت X) برای نمودارهای سه‌بعدی (بین 0 تا 360 درجه) را برمی‌گرداند. این ویژگی با مورد 21.2.2.158 rotY (Y Rotation) در ECMA-376 و گزینه «X Rotation» در PowerPoint 2007+ مطابقت دارد. خواندن **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نشان‌دهنده‌ی نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری با عبارت C# lock(). می‌توانید مستقیماً فراخوانی کنید یا از شیء نظارتی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده نسخه‌برداری. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدیدی را مقداردهی اولیه می‌کند و اجازه می‌دهد زیرکلاس‌ها به‌صورت نسخه‌برداری ساخته شوند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدیدی را مقداردهی اولیه می‌کند و اجازه می‌دهد زیرکلاس‌ها به‌صورت نسخه‌برداری ساخته شوند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه ارجاعی شیء از نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای موارد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده‌ی ارجاع مشترک را به میزان مشخص یافته کاهش می‌دهد. |
| void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) override | عمق یک نمودار سه‌بعدی را به‌عنوان درصدی از عرض نمودار (بین 20 تا 2000 درصد) تنظیم می‌کند. نوشتن **uint16_t**. |
| void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) override | ارتفاع یک نمودار سه‌بعدی را به‌عنوان درصدی از عرض نمودار (بین 5 تا 500 درصد) تعیین می‌کند. نوشتن **uint16_t**. |
| void [set_Perspective](./set_perspective/)(**uint8_t**) override | مقدار پرسپکتیو (زاویه میدان دید) برای نمودارهای سه‌بعدی (بین 0 تا 240) را تنظیم می‌کند. اگر مقدار ویژگی RightAngleAxes برابر true باشد، نادیده گرفته می‌شود. نوشتن **uint8_t**. |
| void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) override | تشخیص می‌دهد که آیا محورهای نمودار به‌صورت زاویه‌دار هستند یا در پرسپکتیو رسم می‌شوند. به عبارت دیگر، تعیین می‌کند که آیا زوایای محورهای نمودار مستقل از چرخش یا ارتفاع نمودار هستند. نوشتن **bool**. |
| void [set_RotationX](./set_rotationx/)(**int8_t**) override | درجه چرخش حول محور X (در جهت Y) برای نمودارهای سه‌بعدی (بین -90 تا 90 درجه) را تنظیم می‌کند. این ویژگی با مورد 21.2.157 rotX (X Rotation) در ECMA-376 و گزینه «Y Rotation» در PowerPoint 2007+ مطابقت دارد. نوشتن **int8_t**. |
| void [set_RotationY](./set_rotationy/)(**uint16_t**) override | درجه چرخش حول محور Y (در جهت X) برای نمودارهای سه‌بعدی (بین 0 تا 360 درجه) را تنظیم می‌کند. این ویژگی با مورد 21.2.158 rotY (Y Rotation) در ECMA-376 و گزینه «X Rotation» در PowerPoint 2007+ مطابقت دارد. نوشتن **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک پوینتر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر پوینترها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده‌ی ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده‌ی ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمند پوینترها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده‌ی ارجاع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمند پوینترها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای باز کردن قفل با عبارت C# lock(). می‌توانید مستقیماً فراخوانی کنید یا از شیء نظارتی [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده‌ی ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمند پوینترها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده‌ی ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از هوشمند پوینترها یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [IRotation3D](../irotation3d/)
* کلاس [IDOMObject](../../aspose.slides/idomobject/)
* فضای‌نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)