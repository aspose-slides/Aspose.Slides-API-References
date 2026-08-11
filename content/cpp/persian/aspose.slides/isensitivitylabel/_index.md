---
title: ISensitivityLabel
second_title: Aspose.Slides برای C++ API Reference
description: برچسب حساسیت را از Microsoft Purview Information Protection نمایان می‌کند.
type: docs
weight: 3615
url: /fa/aspose.slides/isensitivitylabel/
---
## ISensitivityLabel کلاس

برچسب حساسیت را از Microsoft Purview Information Protection نمایان می‌سازد.

```cpp
class ISensitivityLabel : public virtual System::Object
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌ای شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه‌ای شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| virtual [SensitivityLabelAssignmentType](../sensitivitylabelassignmenttype/) [get_AssignmentMethodType](./get_assignmentmethodtype/)() | متد اختصاصی برای برچسب حساسیت را برمی‌گرداند. [SensitivityLabelAssignmentType](../sensitivitylabelassignmenttype/) را بخوانید. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IList](../../system.collections.generic/ilist/)\<[SensitivityLabelContentType](../sensitivitylabelcontenttype/)\>\> [get_ContentMarkTypes](./get_contentmarktypes/)() | فهرست انواع علامت‌گذاری محتوا که باید بر روی یک فایل اعمال شود را برمی‌گرداند. |
| virtual [System::String](../../system/string/) [get_Id](./get_id/)() | شناسه برچسب حساسیت را برمی‌گرداند. [System::String](../../system/string/) را بخوانید. |
| virtual **bool** [get_IsEnabled](./get_isenabled/)() | نشان می‌دهد که آیا برچسب حساسیت فعال است یا خیر. |
| virtual **bool** [get_IsRemoved](./get_isremoved/)() | نشان می‌دهد که آیا برچسب حساسیت حذف شده است یا خیر. |
| virtual [System::Guid](../../system/guid/) [get_SiteId](./get_siteid/)() | شناسه سایت Azure Active Directory (Azure AD) مربوط به سیاست برچسب حساسیتی که برچسب حساسیت را توصیف می‌کند را برمی‌گرداند. [System::Guid](../../system/guid/) را بخوانید. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده‌ی شمارنده مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌سازی اشیای سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرا کننده قفل‌گذاری بیانیه lock() در C#. به‌صورت مستقیم صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده‌ی کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء از نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual void [set_AssignmentMethodType](./set_assignmentmethodtype/)([SensitivityLabelAssignmentType](../sensitivitylabelassignmenttype/)) | متد اختصاصی برچسب حساسیت را تنظیم می‌کند. [SensitivityLabelAssignmentType](../sensitivitylabelassignmenttype/) را بنویسید. |
| virtual void [set_Id](./set_id/)([System::String](../../system/string/)) | شناسه برچسب حساسیت را تنظیم می‌کند. [System::String](../../system/string/) را بنویسید. |
| virtual void [set_IsEnabled](./set_isenabled/)(**bool**) | نشان می‌دهد که آیا برچسب حساسیت فعال است یا خیر. |
| virtual void [set_IsRemoved](./set_isremoved/)(**bool**) | نشان می‌دهد که آیا برچسب حساسیت حذف شده است یا خیر. |
| virtual void [set_SiteId](./set_siteid/)([System::Guid](../../system/guid/)) | شناسه سایت Azure Active Directory (Azure AD) مربوط به سیاست برچسب حساسیتی که برچسب حساسیت را توصیف می‌کند را تنظیم می‌کند. [System::Guid](../../system/guid/) را بنویسید. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به یک weak pointer تنظیم می‌کند (به‌جای shared). امکان تغییر اشاره‌گرها در کانتینرها به حالت weak را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ در عوض از smart pointers یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم صدا زده شود؛ در عوض از smart pointers یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیای سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرا کننده بازکردن قفل بیانیه lock() در C#. به‌صورت مستقیم صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع weak را افزایش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ در عوض از smart pointers یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع weak را کاهش می‌دهد. نباید به‌صورت مستقیم صدا زده شود؛ در عوض از smart pointers یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## موارد مرتبط

* کلاس [Object](../../system/object/)
* فضای نام [Aspose::Slides](../)
* کتابخانه [Aspose.Slides](../../)