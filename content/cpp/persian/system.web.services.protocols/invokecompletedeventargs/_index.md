---
title: InvokeCompletedEventArgs
second_title: مرجع API Aspose.Slides برای C++
description: "یک نمونه از این کلاس به‌عنوان آرگومان به نماینده InvokeCompletedEventHandler ارسال می‌شود. اشیای این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا شکست‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای ارسال به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 27
url: /fa/system.web.services.protocols/invokecompletedeventargs/
---
## InvokeCompletedEventArgs کلاس

یک نمونه از این کلاس به‌عنوان آرگومان به نماینده InvokeCompletedEventHandler ارسال می‌شود. اشیای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا شکست در اعتبارسنجی می‌شود. همیشه این کلاس را در یک نشانگر [System::SmartPtr](../../system/smartptr/) بپیچید و از این نشانگر برای ارسال به توابع به‌عنوان آرگومان استفاده کنید.

```cpp
class InvokeCompletedEventArgs : public System::ComponentModel::AsyncCompletedEventArgs
```

## متدها

| Method | Description |
| --- | --- |
|  [AsyncCompletedEventArgs](../../system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/)() | سازنده. |
|  [AsyncCompletedEventArgs](../../system.componentmodel/asynccompletedeventargs/asynccompletedeventargs/)(const [System::Exception](../../system/exception/)\&, **bool**, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | یک نمونه جدید از کلاس [System.ComponentModel.AsyncCompletedEventArgs](../../system.componentmodel/asynccompletedeventargs/) را مقداردهی اولیه می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نیست. |
|  [EventArgs](../../system/eventargs/eventargs/)() | سازنده. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| **bool** [get_Cancelled](../../system.componentmodel/asynccompletedeventargs/get_cancelled/)() const | یک مقدار که نشان می‌دهد آیا عملیات ناهمزمان لغو شده است را برمی‌گرداند. اگر عملیات پس‌زمینه لغو شده باشد true؛ در غیر این صورت false. مقدار پیش‌فرض false است. |
| const [System::Exception](../../system/exception/)\& [get_Error](../../system.componentmodel/asynccompletedeventargs/get_error/)() const | مقداری را برمی‌گرداند که نشان می‌دهد کدام خطا در حین عملیات ناهمزمان رخ داده است. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [get_Results](./get_results/)() | یک مجموعه از نتایج عملیات ناهمزمان را برمی‌گرداند. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UserState](../../system.componentmodel/asynccompletedeventargs/get_userstate/)() const | شناسه یکتای کار ناهمزمان را برمی‌گرداند. یک ارجاع شیء که به‌طور یکتا کار ناهمزمان را شناسایی می‌کند؛ در غیر این صورت، اگر هیچ مقداری تنظیم نشده باشد null برمی‌گردد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارندهٔ مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
|  [InvokeCompletedEventArgs](./invokecompletedeventargs/)([Exception](../../system/exception/), **bool**, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>) | یک نمونه جدید را ایجاد می‌کند. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر یک نمونه از نوع توصیف شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل کردن توسط بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند؛ فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر اختصاص. در واقع هیچ چیزی را کپی نمی‌کند؛ فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از زیرکلاس‌ها را فراهم می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر پایهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر پایهٔ مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقدار شیء نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | خصوصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | خصوصی‌سازی [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع مشترک را به مقدار مشخصی کاهش می‌دهد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک پوینتر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر پوینترها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از پوینترهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از پوینترهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | عبارت typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل را با استفاده از بیان lock() در C# باز می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از پوینترهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از پوینترهای هوشمند یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | یک عضو static که یک اشاره‌گر shared \"empty\" [EventArgs](../../system/eventargs/) (null-pointer) را نشان می‌دهد. |

## موارد مرتبط

* کلاس [AsyncCompletedEventArgs](../../system.componentmodel/asynccompletedeventargs/)
* فضای نام [System::Web::Services::Protocols](../)
* کتابخانه [Aspose.Slides](../../)