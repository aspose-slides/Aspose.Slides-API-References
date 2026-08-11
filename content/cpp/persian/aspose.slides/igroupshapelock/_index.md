---
title: IGroupShapeLock
second_title: مرجع API Aspose.Slides برای C++
description: تعیین می‌کند که کدام عملیات‌ها بر روی GroupShape والد غیرفعال هستند.
type: docs
weight: 2497
url: /fa/aspose.slides/igroupshapelock/
---
## IGroupShapeLock کلاس

عملیات‌هایی که بر روی والد [GroupShape](../groupshape/) غیرفعال هستند را تعیین می‌کند.

```cpp
class IGroupShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معانی [Object.Equals](../../system/object/equals/) C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌شناور به-سبک C# را شبیه‌سازی می‌کند که دو NaN را برابر می‌داند، اگرچه طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌شناور به-سبک C# را شبیه‌سازی می‌کند که دو NaN را برابر می‌داند، اگرچه طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | تعیین می‌کند آیا شکل باید نسبت عرض-به-ارتفاع را هنگام تغییر اندازه حفظ کند. فقط‌خواندنی **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | تعیین می‌کند افزودن این شکل به یک گروه ممنوع است یا نه. فقط‌خواندنی **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | اگر تمام پرچم‌های قفل غیرفعال باشند true بر می‌گرداند. فقط‌خواندنی **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | تعیین می‌کند آیا جابجایی این شکل ممنوع است یا نه. فقط‌خواندنی **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | تعیین می‌کند آیا تغییر زاویه چرخش این شکل ممنوع است یا نه. فقط‌خواندنی **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | تعیین می‌کند آیا انتخاب این شکل ممنوع است یا نه. فقط‌خواندنی **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | تعیین می‌کند آیا تغییر اندازه این شکل ممنوع است یا نه. فقط‌خواندنی **bool**. |
| virtual **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() | تعیین می‌کند آیا تقسیم این گروه-شکل ممنوع است یا نه. فقط‌خواندنی **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). هش‌گذاری اشیاء سفارشی را فعال می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوعی است که توسط targetType توصیف شده است. معادل عملگر 'is' C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری توسط عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهدارنده [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فعال می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان کپی‌سازی زیرکلاس‌ها را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان کپی‌سازی زیرکلاس‌ها را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر مبنای مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر مبنای مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به‌صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | تعیین می‌کند آیا شکل باید نسبت عرض-به-ارتفاع را هنگام تغییر اندازه حفظ کند. نوشتنی **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | تعیین می‌کند افزودن این شکل به یک گروه ممنوع است یا نه. نوشتنی **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | تعیین می‌کند جابجایی این شکل ممنوع است یا نه. نوشتنی **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | تعیین می‌کند تغییر زاویه چرخش این شکل ممنوع است یا نه. نوشتنی **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | تعیین می‌کند انتخاب این شکل ممنوع است یا نه. نوشتنی **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | تعیین می‌کند تغییر اندازه این شکل ممنوع است یا نه. نوشتنی **bool**. |
| virtual void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) | تعیین می‌کند تقسیم این گروه-شکل ممنوع است یا نه. نوشتنی **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک weak pointer تنظیم می‌کند (به‌جای shared). امکان تغییر اشاره‌گرها در کانتینرها به حالت weak را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش داده و مقدار آن را بر می‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فعال می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساختار C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی بازگشایی قفل توسط عبارت C# lock() را فراهم می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهدارنده [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده weak pointer را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده weak pointer را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [IBaseShapeLock](../ibaseshapelock/)
* فضای‌نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)