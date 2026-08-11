---
title: ConnectorLock
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند کدام عملیات‌ها بر روی والد Connector غیرفعال هستند.
type: docs
weight: 495
url: /fa/aspose.slides/connectorlock/
---
## ConnectorLock کلاس

مشخص می‌کند کدام عملیات بر روی والد [Connector](../connector/) غیرفعال هستند.

```cpp
class ConnectorLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IConnectorLock
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | مشخص می‌کند آیا تغییر مقادیر تنظیم ممنوع است یا خیر. خواندن **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | مشخص می‌کند آیا تغییر سرهای پیکان ممنوع است یا خیر. خواندن **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | مشخص می‌کند آیا شکل باید نسبت ابعاد را هنگام تغییر اندازه حفظ کند یا خیر. خواندن **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | مشخص می‌کند آیا تغییر مستقیم محدوده این شکل ممنوع است یا خیر. خواندن **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | مشخص می‌کند آیا افزودن این شکل به یک گروه ممنوع است یا خیر. خواندن **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | اگر تمام پرچم‌های قفل غیرفعال باشند true برمی‌گرداند. فقط-خواندنی **bool**. |
| **bool** [get_PositionMove](./get_positionmove/)() override | مشخص می‌کند آیا حرکت این شکل ممنوع است یا خیر. خواندن **bool**. |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | مشخص می‌کند آیا تغییر زاویه چرخش این شکل ممنوع است یا خیر. خواندن **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | مشخص می‌کند آیا انتخاب این شکل ممنوع است یا خیر. خواندن **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | مشخص می‌کند آیا تغییر نوع شکل ممنوع است یا خیر. خواندن **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | مشخص می‌کند آیا تغییر اندازه این شکل ممنوع است یا خیر. خواندن **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌سازی اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است یا خیر. معادل اپراتور 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌کردن دستور lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها را با کپی فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها را با کپی فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr از نظر مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | مشخص می‌کند آیا تغییر مقادیر تنظیم ممنوع است یا خیر. نوشتن **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | مشخص می‌کند آیا تغییر سرهای پیکان ممنوع است یا خیر. نوشتن **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | مشخص می‌کند آیا شکل باید نسبت ابعاد را هنگام تغییر اندازه حفظ کند یا خیر. نوشتن **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | مشخص می‌کند آیا تغییر مستقیم محدوده این شکل ممنوع است یا خیر. نوشتن **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | مشخص می‌کند آیا افزودن این شکل به یک گروه ممنوع است یا خیر. نوشتن **bool**. |
| void [set_PositionMove](./set_positionmove/)(**bool**) override | مشخص می‌کند آیا حرکت این شکل ممنوع است یا خیر. نوشتن **bool**. |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | مشخص می‌کند آیا تغییر زاویه چرخش این شکل ممنوع است یا خیر. نوشتن **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | مشخص می‌کند آیا انتخاب این شکل ممنوع است یا خیر. نوشتن **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | مشخص می‌کند آیا تغییر نوع شکل ممنوع است یا خیر. نوشتن **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | مشخص می‌کند آیا تغییر اندازه این شکل ممنوع است یا خیر. نوشتن **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند‌پوینترها یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند‌پوینترها یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | بازکردن قفل دستور lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند‌پوینترها یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از هوشمند‌پوینترها یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داخلی را آزاد می‌سازد. |

## مشاهده کنید

* کلاس [BaseShapeLock](../baseshapelock/)
* کلاس [IConnectorLock](../iconnectorlock/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)