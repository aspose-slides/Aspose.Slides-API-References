---
title: ICameraEffectiveData
second_title: Aspose.Slides برای C++ مرجع API
description: شیء غیرقابل تغییر که ویژگی‌های مؤثر دوربین را شامل می‌شود.
type: docs
weight: 1600
url: /fa/aspose.slides/icameraeffectivedata/
---
## ICameraEffectiveData کلاس

شیء غیرقابل تغییر که دارای ویژگی‌های مؤثر دوربین است.

```cpp
class ICameraEffectiveData : public virtual System::Object
```

## متدها

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | آبجکت‌ها را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN با هیچ مقداری برابر نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر درنظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN با هیچ مقداری برابر نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای موارد داخلی. |
| virtual [CameraPresetType](../camerapresettype/) [get_CameraType](./get_cameratype/)() | [Camera](../camera/) نوع. فقط-خواندنی [CameraPresetType](../camerapresettype/). |
| virtual **float** [get_FieldOfViewAngle](./get_fieldofviewangle/)() | [Camera](../camera/) زاویه دید (۰-۱۸۰ درجه، میدان دید). فقط-خواندنی **float**. |
| virtual **float** [get_Zoom](./get_zoom/)() | [Camera](../camera/) زوم (مقدار مثبت به درصد). فقط-خواندنی **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | دریافت ساختار داده شمارنده مرجع مرتبط با آبجکت. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری آبجکت‌های سفارشی را فراهم می‌کند. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [GetRotation](./getrotation/)() | چرخش با استفاده از مختصات عرض، مختصات طول و چرخش حول محور به‌عنوان مختصات عرض و طول تعریف می‌شود. عنصر اول در آرایه برگردانده شده - عرض، دوم - طول، سوم - چرخش. اگر چرخشی تعریف نشده باشد null برمی‌گرداند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | دریافت نوع واقعی آبجکت. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا آبجکت نمونه‌ای از نوعی که توسط targetType توصیف شده است یا نه. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری دستور lock() در C#. می‌توانید مستقیماً صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | آبجکت را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط آبجکت جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر اختصاص. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط آبجکت جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | آبجکت‌ها را بر مبنای مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | آبجکت‌ها را بر مبنای مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع‌دار آبجکت نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام template را به یک اشاره‌گر ضعیف تنظیم می‌کند (به جای shared). امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | دریافت مقدار جاری شمارنده مرجع مشترک. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و باز می‌گرداند. نباید مستقیماً صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل آبجکت‌های سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی سازه typeof([System.Object](../../system/object/)) در C#. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی بازقفل‌گذاری دستور lock() در C#. می‌توانید مستقیماً صدا بزنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | آبجکت را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## توضیحات

این رابط به‌عنوان بخشی از [IThreeDFormatEffectiveData](../ithreedformateffectivedata/) استفاده می‌شود. 

## مراجع مرتبط

* کلاس [Object](../../system/object/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)