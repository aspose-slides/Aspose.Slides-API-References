---
title: IRotation3D
second_title: Aspose.Slides برای C++ مرجع API
description: نمایانگر چرخش 3D یک نمودار است.
type: docs
weight: 1171
url: /fa/aspose.slides.charts/irotation3d/
---
## IRotation3D کلاس

نمایانگر چرخش 3D یک نمودار است.

```cpp
class IRotation3D : public virtual System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | شبیه‌سازی مقایسه نقطه‌ی شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | شبیه‌سازی مقایسه نقطه‌ی شناور به سبک C# که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر اساس IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **uint16_t** [get_DepthPercents](./get_depthpercents/)() | عمق یک نمودار 3D را به‌عنوان درصدی از عرض نمودار برمی‌گرداند (بین 20 تا 2000 درصد). خواندنی **uint16_t**. |
| virtual **uint16_t** [get_HeightPercents](./get_heightpercents/)() | ارتفاع یک نمودار 3D را به‌عنوان درصدی از عرض نمودار تعیین می‌کند (بین 5 تا 500 درصد). خواندنی **uint16_t**. |
| virtual **uint8_t** [get_Perspective](./get_perspective/)() | مقدار پرسپکتیو (زاویه میدان دید) برای نمودارهای 3D را برمی‌گرداند (بین 0 تا 100). اگر مقدار ویژگی RightAngleAxes برابر true باشد، نادیده گرفته می‌شود. خواندنی **uint8_t**. |
| virtual **bool** [get_RightAngleAxes](./get_rightangleaxes/)() | تعیین می‌کند آیا محورها به‌صورت زاویه راست هستند یا به‌صورت پرسپکتیو رسم می‌شوند. به عبارت دیگر، این تعیین می‌کند آیا زاویه محورها مستقل از چرخش یا ارتفاع نمودار است. خواندنی **bool**. |
| virtual **int8_t** [get_RotationX](./get_rotationx/)() | درجه چرخش حول محور X را برمی‌گرداند، یعنی در جهت Y برای نمودارهای 3D (بین -90 تا 90 درجه). این ویژگی با مورد rotX (چرخش X) در ECMA-376 و گزینه "Y Rotation" در PowerPoint 2007+ مطابقت دارد. خواندنی **int8_t**. |
| virtual **uint16_t** [get_RotationY](./get_rotationy/)() | درجه چرخش حول محور Y را برمی‌گرداند، یعنی در جهت X برای نمودارهای 3D (بین 0 تا 360 درجه). این ویژگی با مورد rotY (چرخش Y) در ECMA-376 و گزینه "X Rotation" در PowerPoint 2007+ مطابقت دارد. خواندنی **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده‌ شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را می‌گیرد. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوع توصیف شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری با دستور C# lock(). به‌صورت مستقیم فراخوانی شود یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخه کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت نسخه کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع‌گونه شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) | عمق یک نمودار 3D را به‌عنوان درصدی از عرض نمودار تنظیم می‌کند (بین 20 تا 2000 درصد). نوشتنی **uint16_t**. |
| virtual void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) | ارتفاع یک نمودار 3D را به‌عنوان درصدی از عرض نمودار تنظیم می‌کند (بین 5 تا 500 درصد). نوشتنی **uint16_t**. |
| virtual void [set_Perspective](./set_perspective/)(**uint8_t**) | مقدار پرسپکتیو (زاویه میدان دید) برای نمودارهای 3D تنظیم می‌شود (بین 0 تا 100). اگر مقدار ویژگی RightAngleAxes برابر true باشد، نادیده گرفته می‌شود. نوشتنی **uint8_t**. |
| virtual void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) | تعیین می‌کند آیا محورها به‌صورت زاویه راست هستند یا به‌صورت پرسپکتیو رسم می‌شوند. به عبارت دیگر، تعیین می‌کند آیا زاویه محورها مستقل از چرخش یا ارتفاع نمودار است. نوشتنی **bool**. |
| virtual void [set_RotationX](./set_rotationx/)(**int8_t**) | درجه چرخش حول محور X را تنظیم می‌کند، یعنی در جهت Y برای نمودارهای 3D (بین -90 تا 90 درجه). این ویژگی با مورد rotX (چرخش X) در ECMA-376 و گزینه "Y Rotation" در PowerPoint 2007+ مطابقت دارد. نوشتنی **int8_t**. |
| virtual void [set_RotationY](./set_rotationy/)(**uint16_t**) | درجه چرخش حول محور Y را تنظیم می‌کند، یعنی در جهت X برای نمودارهای 3D (بین 0 تا 360 درجه). این ویژگی با مورد rotY (چرخش Y) در ECMA-376 و گزینه "X Rotation" در PowerPoint 2007+ مطابقت دارد. نوشتنی **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | اجرای سازه C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | اجرای بازقفل‌سازی با دستور C# lock(). به‌صورت مستقیم فراخوانی شود یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## همچنین ببینید

* کلاس [Object](../../system/object/)
* فضای‌نام [Aspose::Slides::Charts](../)
* کتابخانه [Aspose.Slides](../../)