---
title: GroupShapeLock
second_title: مرجع API Aspose.Slides برای C++
description: عملیات‌هایی که در GroupShape والد غیرفعال هستند را تعیین می‌کند.
type: docs
weight: 1210
url: /fa/aspose.slides/groupshapelock/
---
## کلاس GroupShapeLock

Determines which operations are disabled on the parent [GroupShape](../groupshape/).

```cpp
class GroupShapeLock : public Aspose::Slides::BaseShapeLock,
                       public Aspose::Slides::IGroupShapeLock
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | آبجکت‌ها را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | آبجکت‌های نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی استفاده می‌شود. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | تعیین می‌کند آیا شکل باید نسبت ابعاد را هنگام تغییر اندازه حفظ کند. فقط خواندنی **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | تعیین می‌کند آیا افزودن این شکل به یک گروه ممنوع است. فقط خواندنی **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | در صورت غیرفعال بودن تمام پرچم‌های قفل، true برمی‌گرداند. فقط خواندنی **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | تعیین می‌کند آیا جابجایی این شکل ممنوع است. فقط خواندنی **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | تعیین می‌کند آیا تغییر زاویه چرخش این شکل ممنوع است. فقط خواندنی **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | تعیین می‌کند آیا انتخاب این شکل ممنوع است. فقط خواندنی **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | تعیین می‌کند آیا تغییر اندازه این شکل ممنوع است. فقط خواندنی **bool**. |
| **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() override | تعیین می‌کند آیا تقسیم این گروه‌شکل ممنوع است. فقط خواندنی **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با آبجکت را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌سازی آبجکت‌های سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی آبجکت را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا آبجکت نشانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل کردن با بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | آبجکت را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی کپی نمی‌کند، فقط آبجکت جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرباکس‌ها را فراهم می‌آورد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی کپی نمی‌کند، فقط آبجکت جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرباکس‌ها را فراهم می‌آورد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | آبجکت‌ها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | آبجکت‌ها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقابله مرجع بین آبجکت نوع مقدار و nullptr انجام می‌دهد. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | تعیین می‌کند آیا شکل باید نسبت ابعاد را هنگام تغییر اندازه حفظ کند. فقط نوشتنی **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | تعیین می‌کند آیا افزودن این شکل به یک گروه ممنوع است. فقط نوشتنی **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | تعیین می‌کند آیا جابجایی این شکل ممنوع است. فقط نوشتنی **bool**. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | تعیین می‌کند آیا تغییر زاویه چرخش این شکل ممنوع است. فقط نوشتنی **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | تعیین می‌کند آیا انتخاب این شکل ممنوع است. فقط نوشتنی **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | تعیین می‌کند آیا تغییر اندازه این شکل ممنوع است. فقط نوشتنی **bool**. |
| void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) override | تعیین می‌کند آیا تقسیم این گروه‌شکل ممنوع است. فقط نوشتنی **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (نه مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل آبجکت‌های سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | باز کردن قفل با بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | آبجکت را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [BaseShapeLock](../baseshapelock/)
* کلاس [IGroupShapeLock](../igroupshapelock/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)