---
title: IGraphicalObjectLock
second_title: Aspose.Slides برای C++ مرجع API
description: مشخص می‌کند که کدام عملیات‌ها بر روی شیء والد GraphicalObjectEx غیرفعال هستند.
type: docs
weight: 2471
url: /fa/aspose.slides/igraphicalobjectlock/
---
## IGraphicalObjectLock کلاس


مشخص می‌کند که کدام عملیات‌ها بر روی شیء والد GraphicalObjectEx غیرفعال هستند.

```cpp
class IGraphicalObjectLock : public virtual Aspose::Slides::IBaseShapeLock
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از ساختار [Object.Equals](../../system/object/equals/) زبان C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی استفاده می‌شود. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | تعیین می‌کند که آیا شکل باید نسبت ابعاد را در هنگام تغییر اندازه حفظ کند. خواندنی **bool**. |
| virtual **bool** [get_DrilldownLocked](./get_drilldownlocked/)() | تعیین می‌کند که آیا انتخاب زیرشکل‌های این شیء ممنوع است. خواندنی **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | تعیین می‌کند که آیا افزودن این شکل به یک گروه ممنوع است. خواندنی **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | در صورتی که تمام پرچم‌های قفل غیرفعال باشند، true برمی‌گرداند. فقط-خواندنی **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | تعیین می‌کند که آیا جابه‌جایی این شکل ممنوع است. خواندنی **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | تعیین می‌کند که آیا انتخاب این شکل ممنوع است. خواندنی **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | تعیین می‌کند که آیا تغییر اندازه این شکل ممنوع است. خواندنی **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیای سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نماینده نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌کردن عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. همه ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند؛ فقط شیء جدید را مقداردهی اولیه می‌نماید و امکان ساخت نسخهٔ کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند؛ فقط شیء جدید را مقداردهی اولیه می‌نماید و امکان ساخت نسخهٔ کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به‌صورت مرجعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخصی کاهش می‌دهد. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | تعیین می‌کند که آیا شکل باید نسبت ابعاد را در هنگام تغییر اندازه حفظ کند. نوشتنی **bool**. |
| virtual void [set_DrilldownLocked](./set_drilldownlocked/)(**bool**) | تعیین می‌کند که آیا انتخاب زیرشکل‌های این شیء ممنوع است. نوشتنی **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | تعیین می‌کند که آیا افزودن این شکل به یک گروه ممنوع است. نوشتنی **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | تعیین می‌کند که آیا جابه‌جایی این شکل ممنوع است. نوشتنی **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | تعیین می‌کند که آیا انتخاب این شکل ممنوع است. نوشتنی **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | تعیین می‌کند که آیا تغییر اندازه این شکل ممنوع است. نوشتنی **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیم فراخوانی شود؛ بجای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید مستقیم فراخوانی شود؛ بجای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیای سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری از عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیم فراخوانی شود؛ بجای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیم فراخوانی شود؛ بجای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## مطالب مرتبط

* کلاس [IBaseShapeLock](../ibaseshapelock/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)