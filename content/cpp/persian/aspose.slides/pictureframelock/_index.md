---
title: PictureFrameLock
second_title: مرجع API Aspose.Slides برای C++
description: تعیین می‌کند کدام عملیات‌ها روی شیء والد PictureFrame غیرفعال هستند.
type: docs
weight: 4746
url: /fa/aspose.slides/pictureframelock/
---
## PictureFrameLock کلاس

تعیین می‌کند کدام عملیات‌ها بر روی والد [PictureFrame](../pictureframe/) غیرفعال هستند.

```cpp
class PictureFrameLock : public Aspose::Slides::BaseShapeLock,
                         public Aspose::Slides::IPictureFrameLock
```

## متدها

| متد | توضیحات |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معناشناسی [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | تعیین می‌کند آیا تغییر مقادیر تنظیمات ممنوع است. خواندن **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | تعیین می‌کند آیا تغییر سرهای پیکان ممنوع است. خواندن **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | تعیین می‌کند آیا شکل باید نسبت ابعاد را هنگام تغییر اندازه حفظ کند. خواندن **bool**. |
| **bool** [get_CropLocked](./get_croplocked/)() override | تعیین می‌کند آیا برش تصویر ممنوع است. خواندن **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | تعیین می‌کند آیا تغییر مستقیم کانتور این شکل ممنوع است. خواندن **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | تعیین می‌کند آیا افزودن این شکل به گروه ممنوع است. خواندن **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | اگر تمام پرچم‌های قفل غیرفعال باشند true برمی‌گرداند. فقط-خواندنی **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | تعیین می‌کند آیا حرکت این شکل ممنوع است. خواندن **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | تعیین می‌کند آیا تغییر زاویه چرخش این شکل ممنوع است. خواندن **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | تعیین می‌کند آیا انتخاب این شکل ممنوع است. خواندن **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | تعیین می‌کند آیا تغییر نوع شکل ممنوع است. خواندن **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | تعیین می‌کند آیا تغییر اندازه این شکل ممنوع است. خواندن **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش [Object.GetHashCode()](../../system/object/gethashcode/) C#. امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری بیان lock() C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) C#. امکان کلون‌برداری انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع‌گونه شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع‌ اشتراکی را به مقدار مشخص کاهش می‌دهد. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | تعیین می‌کند آیا تغییر مقادیر تنظیمات ممنوع است. نوشتن **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | تعیین می‌کند آیا تغییر سرهای پیکان ممنوع است. نوشتن **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | تعیین می‌کند آیا شکل باید نسبت ابعاد را هنگام تغییر اندازه حفظ کند. نوشتن **bool**. |
| void [set_CropLocked](./set_croplocked/)(**bool**) override | تعیین می‌کند آیا برش تصویر ممنوع است. نوشتن **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | تعیین می‌کند آیا تغییر مستقیم کانتور این شکل ممنوع است. نوشتن **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | تعیین می‌کند آیا افزودن این شکل به گروه ممنوع است. نوشتن **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | تعیین می‌کند آیا حرکت این شکل ممنوع است. نوشتن **bool**. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | تعیین می‌کند آیا تغییر زاویه چرخش این شکل ممنوع است. نوشتن **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | تعیین می‌کند آیا انتخاب این شکل ممنوع است. نوشتن **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | تعیین می‌کند آیا تغییر نوع شکل ممنوع است. نوشتن **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | تعیین می‌کند آیا تغییر اندازه این شکل ممنوع است. نوشتن **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای اشاری شُراکت‌شده) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع‌ اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع‌ اشتراکی را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع‌ اشتراکی را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش [Object.ToString()](../../system/object/tostring/) C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل بیان lock() C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع‌ ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع‌ ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ به‌جای آن، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [BaseShapeLock](../baseshapelock/)
* کلاس [IPictureFrameLock](../ipictureframelock/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)