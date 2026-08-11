---
title: IAutoShapeLock
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند کدام عملیات بر روی AutoshapeEx والد غیرفعال هستند.
type: docs
weight: 1379
url: /fa/aspose.slides/iautoshapelock/
---
## IAutoShapeLock کلاس


Determines which operations are disabled on the parent AutoshapeEx.

```cpp
class IAutoShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقدارى نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقدارى نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | مشخص می‌کند آیا تغییر مقادیر تنظیم ممنوع است. **bool** را می‌خواند. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | مشخص می‌کند آیا تغییر سرهای فلش ممنوع است. **bool** را می‌خواند. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | مشخص می‌کند آیا شکل باید نسبت عرض/ارتفاع را هنگام تغییر اندازه حفظ کند. **bool** را می‌خواند. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | مشخص می‌کند آیا تغییر مستقیم مسیر این شکل ممنوع است. **bool** را می‌خواند. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | مشخص می‌کند آیا افزودن این شکل به یک گروه ممنوع است. **bool** را می‌خواند. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | اگر همهٔ پرچم‌های قفل غیرفعال باشند، true برمی‌گرداند. فقط-خواندنی **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | مشخص می‌کند آیا جابه‌جایی این شکل ممنوع است. **bool** را می‌خواند. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | مشخص می‌کند آیا تغییر زاویهٔ چرخش این شکل ممنوع است. **bool** را می‌خواند. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | مشخص می‌کند آیا انتخاب این شکل ممنوع است. **bool** را می‌خواند. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | مشخص می‌کند آیا تغییر نوع شکل ممنوع است. **bool** را می‌خواند. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | مشخص می‌کند آیا تغییر اندازهٔ این شکل ممنوع است. **bool** را می‌خواند. |
| virtual **bool** [get_TextLocked](./get_textlocked/)() | مشخص می‌کند آیا ویرایش متن ممنوع است. **bool** را می‌خواند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شی را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فعال می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شی نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل کردن توسط عبارت lock() در C# را پیاده می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون کردن انواع سفارشی را فعال می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ copy. در واقع هیچ چیزی را کپی نمی‌کند؛ فقط شیء جدید را مقداردهی می‌کند و امکان ساختن زیرکلاس‌ها با کپی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند؛ فقط شیء جدید را مقداردهی می‌کند و امکان ساختن زیرکلاس‌ها با کپی را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء از نوع مقدار را با nullptr بر اساس مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص برای حالت رشته و nullptr از [Object::ReferenceEquals](../../system/object/referenceequals/). |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص برای حالت رشته‌ها از [Object::ReferenceEquals](../../system/object/referenceequals/). |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | مشخص می‌کند آیا تغییر مقادیر تنظیم ممنوع است. **bool** را می‌نویسد. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | مشخص می‌کند آیا تغییر سرهای فلش ممنوع است. **bool** را می‌نویسد. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | مشخص می‌کند آیا شکل باید نسبت عرض/ارتفاع را هنگام تغییر اندازه حفظ کند. **bool** را می‌نویسد. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | مشخص می‌کند آیا تغییر مستقیم مسیر این شکل ممنوع است. **bool** را می‌نویسد. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | مشخص می‌کند آیا افزودن این شکل به گروه ممنوع است. **bool** را می‌نویسد. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | مشخص می‌کند آیا جابجایی این شکل ممنوع است. **bool** را می‌نویسد. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | مشخص می‌کند آیا تغییر زاویهٔ چرخش این شکل ممنوع است. **bool** را می‌نویسد. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | مشخص می‌کند آیا انتخاب این شکل ممنوع است. **bool** را می‌نویسد. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | مشخص می‌کند آیا تغییر نوع شکل ممنوع است. **bool** را می‌نویسد. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | مشخص می‌کند آیا تغییر اندازهٔ این شکل ممنوع است. **bool** را می‌نویسد. |
| virtual void [set_TextLocked](./set_textlocked/)(**bool**) | مشخص می‌کند آیا ویرایش متن ممنوع است. **bool** را می‌نویسد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان n-ام قالب را به یک weak pointer (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در آرایه‌ها به حالت weak را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده شود. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده شود. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فعال می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گشایی توسط عبارت lock() در C# را پیاده می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع weak را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده شود. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع weak را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده شود. |
| virtual  [~Object](../../system/object/~object/)() | شی را نابود می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌سازد. |

## موارد مرتبط

* کلاس [IBaseShapeLock](../ibaseshapelock/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)