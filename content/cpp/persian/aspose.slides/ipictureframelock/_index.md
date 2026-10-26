---
title: IPictureFrameLock
second_title: مرجع API Aspose.Slides برای C++
description: تعیین می‌کند که کدام عملیات‌ها در PictureFrameEx والد غیرفعال هستند.
type: docs
weight: 3264
url: /fa/aspose.slides/ipictureframelock/
---
## IPictureFrameLock کلاس

تعیین می‌کند که کدام عملیات‌ها در PictureFrameEx والد غیرفعال هستند.

```cpp
class IPictureFrameLock : public virtual Aspose::Slides::IBaseShapeLock
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معانی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ‌مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ‌مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | تعیین می‌کند که آیا تغییر مقادیر تنظیمات ممنوع است. خواندن **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | تعیین می‌کند که آیا تغییر سرهای پیکان ممنوع است. خواندن **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | تعیین می‌کند که آیا شکل باید نسبت تصویر را هنگام تغییر اندازه حفظ کند. خواندن **bool**. |
| virtual **bool** [get_CropLocked](./get_croplocked/)() | تعیین می‌کند که آیا برش تصویر ممنوع است. خواندن **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | تعیین می‌کند که آیا تغییر مستقیم کانتور این شکل ممنوع است. خواندن **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | تعیین می‌کند که آیا افزودن این شکل به یک گروه ممنوع است. خواندن **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | در صورت غیرفعال بودن تمام پرچم‌های قفل، true باز می‌گرداند. فقط-خواندنی **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | تعیین می‌کند که آیا حرکت این شکل ممنوع است. خواندن **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | تعیین می‌کند که آیا تغییر زاویه چرخش این شکل ممنوع است. خواندن **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | تعیین می‌کند که آیا انتخاب این شکل ممنوع است. خواندن **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | تعیین می‌کند که آیا تغییر نوع شکل ممنوع است. خواندن **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | تعیین می‌کند که آیا تغییر اندازه این شکل ممنوع است. خواندن **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/) است. امکان هش‌گذاری اشیاء سفارشی را می‌دهد. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/) است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | عملیات قفل‌گذاری عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) است. امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع به‌اشتراک‌گذاری‌شده را با مقدار مشخص کاهش می‌دهد. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | تعیین می‌کند که آیا تغییر مقادیر تنظیمات ممنوع است. نوشتن **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | تعیین می‌کند که آیا تغییر سرهای پیکان ممنوع است. نوشتن **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | تعیین می‌کند که آیا شکل باید نسبت تصویر را هنگام تغییر اندازه حفظ کند. نوشتن **bool**. |
| virtual void [set_CropLocked](./set_croplocked/)(**bool**) | تعیین می‌کند که آیا برش تصویر ممنوع است. نوشتن **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | تعیین می‌کند که آیا تغییر مستقیم کانتور این شکل ممنوع است. نوشتن **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | تعیین می‌کند که آیا افزودن این شکل به یک گروه ممنوع است. نوشتن **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | تعیین می‌کند که آیا حرکت این شکل ممنوع است. نوشتن **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | تعیین می‌کند که آیا تغییر زاویه چرخش این شکل ممنوع است. نوشتن **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | تعیین می‌کند که آیا انتخاب این شکل ممنوع است. نوشتن **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | تعیین می‌کند که آیا تغییر نوع شکل ممنوع است. نوشتن **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | تعیین می‌کند که آیا تغییر اندازه این شکل ممنوع است. نوشتن **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف تنظیم می‌کند (به‌جای shared). امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع به‌اشتراک‌گذاری‌شده را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع به‌اشتراک‌گذاری‌شده را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع به‌اشتراک‌گذاری‌شده را کاهش می‌دهد و بازمی‌گرداند. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/) است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | عملیات بازقفل‌گذاری عبارت lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را تخریب می‌کند. تمام ساختارهای داده داخلی را آزاد می‌سازد. |

## موارد مرتبط

* کلاس [IBaseShapeLock](../ibaseshapelock/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)