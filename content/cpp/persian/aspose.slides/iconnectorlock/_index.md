---
title: IConnectorLock
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند کدام عملیات‌ها بر روی Connector والد غیرفعال هستند.
type: docs
weight: 1860
url: /fa/aspose.slides/iconnectorlock/
---
## IConnectorLock کلاس

مشخص می‌کند کدام عملیات‌ها بر روی والد [Connector](../connector/) غیرفعال هستند.

```cpp
class IConnectorLock : public virtual Aspose::Slides::IBaseShapeLock
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | مشخص می‌کند آیا تغییر مقادیر تنظیم ممنوع است. خواندنی **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | مشخص می‌کند آیا تغییر سرهای فلش ممنوع است. خواندنی **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | مشخص می‌کند آیا شکل باید نسبت ابعاد را در هنگام تغییر اندازه حفظ کند. خواندنی **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | مشخص می‌کند آیا تغییر مستقیم خطوط بیرونی این شکل ممنوع است. خواندنی **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | مشخص می‌کند آیا افزودن این شکل به گروه ممنوع است. خواندنی **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | در صورتی که تمام پرچم‌های قفل غیرفعال باشند true برمی‌گرداند. فقط‌خواندنی **bool**. |
| virtual **bool** [get_PositionMove](./get_positionmove/)() | مشخص می‌کند آیا جابه‌جایی این شکل ممنوع است. خواندنی **bool**. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | مشخص می‌کند آیا تغییر زاویه چرخش این شکل ممنوع است. خواندنی **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | مشخص می‌کند آیا انتخاب این شکل ممنوع است. خواندنی **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | مشخص می‌کند آیا تغییر نوع شکل ممنوع است. خواندنی **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | مشخص می‌کند آیا تغییر اندازه این شکل ممنوع است. خواندنی **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان lock() C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) C#. امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده‌ی کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد ارجاع مشترک را به مقدار مشخص کاهش می‌دهد. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | مشخص می‌کند آیا تغییر مقادیر تنظیم ممنوع است. نوشتنی **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | مشخص می‌کند آیا تغییر سرهای فلش ممنوع است. نوشتنی **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | مشخص می‌کند آیا شکل باید نسبت ابعاد را در هنگام تغییر اندازه حفظ کند. نوشتنی **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | مشخص می‌کند آیا تغییر مستقیم خطوط بیرونی این شکل ممنوع است. نوشتنی **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | مشخص می‌کند آیا افزودن این شکل به گروه ممنوع است. نوشتنی **bool**. |
| virtual void [set_PositionMove](./set_positionmove/)(**bool**) | مشخص می‌کند آیا جابه‌جایی این شکل ممنوع است. نوشتنی **bool**. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | مشخص می‌کند آیا تغییر زاویه چرخش این شکل ممنوع است. نوشتنی **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | مشخص می‌کند آیا انتخاب این شکل ممنوع است. نوشتنی **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | مشخص می‌کند آیا تغییر نوع شکل ممنوع است. نوشتنی **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | مشخص می‌کند آیا تغییر اندازه این شکل ممنوع است. نوشتنی **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده ارجاع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | بازکردن قفل بیان lock() C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده ارجاع ضعیف را افزایش‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده ارجاع ضعیف را کاهش‌دهد. نباید مستقیماً فراخوانی شود؛ به جای آن از هوشمند‌اشاره‌گرها یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [IBaseShapeLock](../ibaseshapelock/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)