---
title: AutoShapeLock
second_title: مرجع API Aspose.Slides برای C++
description: تعیین می‌کند که کدام عملیات بر روی AutoshapeEx والد غیرفعال هستند.
type: docs
weight: 79
url: /fa/aspose.slides/autoshapelock/
---
## AutoShapeLock کلاس

Determines which operations are disabled on the parent AutoshapeEx.

```cpp
class AutoShapeLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IAutoShapeLock
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معانی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، شامل NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، شامل NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | تعیین می‌کند که آیا تغییر مقادیر تنظیم ممنوع است. فقط خواندنی **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | تعیین می‌کند که آیا تغییر سرهای پیکان ممنوع است. فقط خواندنی **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | تعیین می‌کند که آیا شکل باید نسبت ابعاد را هنگام تغییر اندازه حفظ کند. فقط خواندنی **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | تعیین می‌کند که آیا تغییر مستقیم کانتور این شکل ممنوع است. فقط خواندنی **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | تعیین می‌کند که آیا افزودن این شکل به گروه ممنوع است. فقط خواندنی **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | در صورتی که همهٔ پرچم‌های قفل غیرفعال باشند true برمی‌گرداند. فقط خواندنی **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | تعیین می‌کند که آیا جابجایی این شکل ممنوع است. فقط خواندنی **bool**. |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | تعیین می‌کند که آیا تغییر زاویهٔ چرخش این شکل ممنوع است. فقط خواندنی **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | تعیین می‌کند که آیا انتخاب این شکل ممنوع است. فقط خواندنی **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | تعیین می‌کند که آیا تغییر نوع شکل ممنوع است. فقط خواندنی **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | تعیین می‌کند که آیا تغییر اندازه این شکل ممنوع است. فقط خواندنی **bool**. |
| **bool** [get_TextLocked](./get_textlocked/)() override | تعیین می‌کند که آیا ویرایش متن ممنوع است. فقط خواندنی **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل اپراتور 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌کردن دستور lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. همهٔ ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ ارجاعی شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ ارجاع مشترک را با مقدار مشخص کاهش می‌دهد. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | تعیین می‌کند که آیا تغییر مقادیر تنظیم ممنوع است. نوشتنی **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | تعیین می‌کند که آیا تغییر سرهای پیکان ممنوع است. نوشتنی **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | تعیین می‌کند که آیا شکل باید نسبت ابعاد را هنگام تغییر اندازه حفظ کند. نوشتنی **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | تعیین می‌کند که آیا تغییر مستقیم کانتور این شکل ممنوع است. نوشتنی **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | تعیین می‌کند که آیا افزودن این شکل به گروه ممنوع است. نوشتنی **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | تعیین می‌کند که آیا جابجایی این شکل ممنوع است. نوشتنی **bool**. |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | تعیین می‌کند که آیا تغییر زاویهٔ چرخش این شکل ممنوع است. نوشتنی **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | تعیین می‌کند که آیا انتخاب این شکل ممنوع است. نوشتنی **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | تعیین می‌کند که آیا تغییر نوع شکل ممنوع است. نوشتنی **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | تعیین می‌کند که آیا تغییر اندازه این شکل ممنوع است. نوشتنی **bool**. |
| void [set_TextLocked](./set_textlocked/)(**bool**) override | تعیین می‌کند که آیا ویرایش متن ممنوع است. نوشتنی **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش می‌دهد و مقدار آن را بازمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری دستور lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. همهٔ ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [BaseShapeLock](../baseshapelock/)
* کلاس [IAutoShapeLock](../iautoshapelock/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)