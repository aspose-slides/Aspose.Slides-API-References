---
title: ResultValueTask
second_title: مرجع API Aspose.Slides برای C++
description: نمایش‌دهندهٔ یک نوع ترکیبی شبیه به وظیفه است که می‌تواند یا مقدار نتیجه مستقیم یا یک ResultTask<T> را بپیچد.
type: docs
weight: 53
url: /fa/system.threading.tasks/resultvaluetask/
---
## ResultValueTask کلاس

نمایش‌دهنده یک نوع ترکیبی شبیه به وظیفه است که می‌تواند یا مقدار نتیجه مستقیم یا یک ResultTask<T> را بپیچد.

```cpp
template<typename T>class ResultValueTask : public System::IEquatable<ResultValueTask<T>>,
                                            public System::Details::BoxableObjectBase
```

### پارامترهای الگو

| پارامتر | توضیح |
| --- | --- |
| T | نوع نتیجه‌ای که توسط وظیفه تولید می‌شود. |
## متدها

| متد | توضیح |
| --- | --- |
| [RTaskPtr](../../system/rtaskptr/)\<T\> [AsTask](./astask/)() const | این [ResultValueTask](./) را به یک shared pointer به ResultTask<T> تبدیل می‌کند. |
| [Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable](../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | یک awaiter برای این وظیفه پیکربندی می‌کند. |
| **bool** [Equals](./equals/)([ResultValueTask](./)) override | مشخص می‌کند آیا این نمونه برابر با نمونه دیگر [ResultValueTask](./) است. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | مشخص می‌کند آیا این نمونه برابر با شیء دیگر است. |
| virtual **bool** [Equals](../../system/iequatable/equals/)(T) | مشخص می‌کند آیا شیء فعلی و شیء مشخص شده برابر هستند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | شیء‌ها را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | شیء‌های نوع مرجع را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به عنوان برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به عنوان برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | مقداری را برمی‌گرداند که نشان می‌دهد آیا وظیفه به دلیل لغو شدن تکمیل شده است. |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | مقداری را برمی‌گرداند که نشان می‌دهد آیا وظیفه تکمیل شده است. |
| **bool** [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | مقداری را برمی‌گرداند که نشان می‌دهد آیا وظیفه با موفقیت تکمیل شده است. |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | مقداری را برمی‌گرداند که نشان می‌دهد آیا وظیفه به دلیل استثنای بدون پردازش تکمیل شده است. |
| T [get_Result](./get_result/)() | نتیجهٔ وظیفهٔ تکمیل‌شده را برمی‌گرداند. |
| [Runtime::CompilerServices::ResultValueTaskAwaiter](../../system.runtime.compilerservices/resultvaluetaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | یک awaiter برای این وظیفه به منظور پشتیبانی از عبارات await برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارندهٔ مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری شیء‌های سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل کردن بیان C# lock(). مستقیماً فراخوانی شود یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده‌ی کپی. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| **bool** [operator!=](./operator_not_equal/)(const [ResultValueTask](./)\&) const | عملگر نابرابری برای [ResultValueTask](./). |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| **bool** [operator==](./operator_equal_equal/)(const [ResultValueTask](./)\&) const | عملگر برابری برای [ResultValueTask](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | شیء‌ها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | شیء‌ها را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع مشترک را به مقدار مشخص کاهش می‌دهد. |
|  [ResultValueTask](./resultvaluetask/)() | یک [ResultValueTask](./) خالی و بدون مقداردهی اولیه می‌سازد. |
|  [ResultValueTask](./resultvaluetask/)(const T\&) | یک [ResultValueTask](./) تکمیل‌شده با نتیجهٔ مشخص شده می‌سازد. |
|  [ResultValueTask](./resultvaluetask/)(const [RTaskPtr](../../system/rtaskptr/)\<T\>\&) | یک [ResultValueTask](./) را از یک shared pointer به ResultTask<T> می‌سازد. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک weak pointer (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در محفظه‌ها به حالت weak را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل شیء‌های سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازقفل کردن بیان C# lock(). مستقیماً فراخوانی شود یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع weak را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع weak را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از smart pointers یا ThisProtector استفاده کنید. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |
## توضیحات

[ResultValueTask](./) مزایای [ValueTask](../valuetask/) (کاهش تخصیص‌ها برای نتایج همزمان) را با قابلیت بستن اشیاء ResultTask<T> موجود ترکیب می‌کند. این رابط قابل await را فراهم می‌کند و انواع روش‌های بازرسی وضعیت وظیفه را ارائه می‌دهد. 
## مراجع

* کلاس [IEquatable](../../system/iequatable/)
* فضای نام [System::Threading::Tasks](../)
* کتابخانه [Aspose.Slides](../../)