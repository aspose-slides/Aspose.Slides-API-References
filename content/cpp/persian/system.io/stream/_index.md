---
title: Stream
second_title: مرجع API Aspose.Slides برای C++
description: "یک کلاس پایه برای انواع پیاده‌سازی‌های جریان. شیء‌های این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای assert می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 365
url: /fa/system.io/stream/
---
## کلاس Stream

یک کلاس پایه برای انواع پیاده‌سازی‌های جریان. نمونه‌های این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/ یا خطاهای assert می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید.

```cpp
class Stream : public System::IDisposable
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک عملیات خواندن ناهمزمان را آغاز می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک عملیات نوشتن ناهمزمان را آغاز می‌کند. |
| virtual void [Close](./close/)() | جریان را می‌بندد. |
| void [CopyTo](./copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](./)\>\&) | بایت‌ها را به جریان مشخص‌شده کپی می‌کند. |
| void [CopyTo](./copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](./)\>\&, **int32_t**) | بایت‌ها را به جریان مشخص‌شده کپی می‌کند، با استفاده از اندازه بافر مشخص. |
| void [Dispose](./dispose/)() override | تمام منابع استفاده‌شده توسط شیء جاری را آزاد می‌کند و جریان را می‌بندد. |
| virtual int [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | تا زمان تکمیل عملیات خواندن ناهمزمان مشخص‌شده صبر می‌کند. |
| virtual void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | عملیات نوشتن ناهمزمان را پایان می‌دهد. تا زمان تکمیل عملیات نوشتن ناهمزمان مشخص‌شده صبر می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقداری را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN مساوی در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN مساوی در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای اهداف داخلی. |
| virtual void [Flush](./flush/)() | بافرهای این جریان را پاک می‌کند و تمام داده‌های بافرشده را به ذخیره‌سازی زیرین می‌نویسد. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به‌صورت ناهمزمان تمام بافرهای این جریان را پاک می‌کند، باعث می‌شود هر داده‌ی بافرشده‌ای به دستگاه زیرین نوشته شود و درخواست‌های لغو را مانیتور می‌کند. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)() | به‌صورت ناهمزمان تمام بافرهای این جریان را پاک می‌کند، باعث می‌شود هر داده‌ی بافرشده‌ای به دستگاه زیرین نوشته شود و درخواست‌های لغو را مانیتور می‌کند. |
| virtual **bool** [get_CanRead](./get_canread/)() const | تشخیص می‌دهد آیا جریان قابل خواندن است. |
| virtual **bool** [get_CanSeek](./get_canseek/)() const | تشخیص می‌دهد آیا جریان از جستجو (seek) پشتیبانی می‌کند. |
| virtual **bool** [get_CanTimeout](./get_cantimeout/)() const | مقداری را دریافت می‌کند که تعیین می‌کند آیا جریان جاری می‌تواند منقضی شود. |
| virtual **bool** [get_CanWrite](./get_canwrite/)() const | تشخیص می‌دهد آیا جریان قابل نوشتن است. |
| virtual **int64_t** [get_Length](./get_length/)() const | طول جریان را بر حسب بایت برمی‌گرداند. |
| virtual **int64_t** [get_Position](./get_position/)() const | موقعیت فعلی جریان را برمی‌گرداند. |
| virtual int [get_ReadTimeout](./get_readtimeout/)() const | مقداری به میلی‌ثانیه دریافت می‌کند که تعیین می‌کند جریان تا چه مدت سعی می‌کند قبل از انقضا بخواند. |
| virtual int [get_WriteTimeout](./get_writetimeout/)() const | مقداری به میلی‌ثانیه دریافت می‌کند که تعیین می‌کند جریان تا چه مدت سعی می‌کند قبل از انقضا بنویسد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارشگر ارجاع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' C#. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء مراقبت [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ‌ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ‌ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن کپی از زیرکلاس‌ها را فراهم می‌کند. |
| virtual **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | تعداد بایت مشخص‌شده را از جریان می‌خواند و به آرایه بایت مشخص‌شده می‌نویسد. |
| virtual **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | تعداد بایت مشخص‌شده را از جریان می‌خواند و به آرایه بایت مشخص‌شده می‌نویسد. |
| **int32_t** [Read](./read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | تعداد بایت مشخص‌شده را از جریان می‌خواند و به آرایه بایت مشخص‌شده می‌نویسد. |
| virtual **int32_t** [Read](./read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | تعداد بایت مشخص‌شده را از جریان می‌خواند و به بازه بایت مشخص‌شده می‌نویسد. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به‌صورت ناهمزمان دنباله‌ای از بایت‌ها را از جریان جاری می‌خواند، موقعیت درون جریان را به اندازهٔ بایت‌های خوانده‌شده جلو می‌برد و درخواست‌های لغو را مانیتور می‌کند. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به‌صورت ناهمزمان دنباله‌ای از بایت‌ها را از جریان جاری می‌خواند، موقعیت درون جریان را به اندازهٔ بایت‌های خوانده‌شده جلو می‌برد و درخواست‌های لغو را مانیتور می‌کند. |
| virtual int [ReadByte](./readbyte/)() | یک بایت واحد را از جریان می‌خواند و مقدار عدد صحیح 32-بیتی معادل مقدار بایت خوانده‌شده را برمی‌گرداند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را به‌صورت ارجاعی مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را به‌صورت ارجاعی مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه ارجاعی شیء نوع مقداری با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارشگر ارجاع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) | موقعیت جریانی که توسط شیء جاری نمایانده می‌شود را تنظیم می‌کند. |
| virtual void [set_Position](./set_position/)(**int64_t**) | موقعیت جریان را تنظیم می‌کند. |
| virtual void [set_ReadTimeout](./set_readtimeout/)(int) | مقداری را تنظیم می‌کند که تعیین می‌کند آیا جریان جاری می‌تواند منقضی شود. |
| virtual void [set_WriteTimeout](./set_writetimeout/)(int) | مقداری به میلی‌ثانیه تنظیم می‌کند که تعیین می‌کند جریان تا چه مدت سعی می‌کند قبل از انقضا بخواند. |
| virtual void [SetLength](./setlength/)(**int64_t**) | طول جریانی که توسط شیء جاری نمایانده می‌شود را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارشگر ارجاع مشترک را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارشگر ارجاع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارشگر ارجاع مشترک را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). تبدیل اشیاء سفارشی به رشته را امکان‌پذیر می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل (unlock) بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء مراقبت [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارشگر ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارشگر ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | بخش مشخص‌شده‌ای از بایت‌ها را از آرایه بایت مشخص‌شده به جریان می‌نویسد. |
| virtual void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | بخش مشخص‌شده‌ای از بایت‌ها را از آرایه بایت مشخص‌شده به جریان می‌نویسد. |
| void [Write](./write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | بخش مشخص‌شده‌ای از بایت‌ها را از آرایه بایت مشخص‌شده به جریان می‌نویسد. |
| virtual void [Write](./write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | بخش مشخص‌شده‌ای از بایت‌ها را از بازه بایت مشخص‌شده به جریان می‌نویسد. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به‌صورت ناهمزمان دنباله‌ای از بایت‌ها را به جریان جاری می‌نویسد، موقعیت جاری در این جریان را به اندازهٔ بایت‌های نوشته‌شده جلو می‌برد و درخواست‌های لغو را مانیتور می‌کند. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به‌صورت ناهمزمان دنباله‌ای از بایت‌ها را به جریان جاری می‌نویسد، موقعیت جاری در این جریان را به اندازهٔ بایت‌های نوشته‌شده جلو می‌برد و درخواست‌های لغو را مانیتور می‌کند. |
| virtual void [WriteByte](./writebyte/)(**uint8_t**) | مقدار عدد صحیح بدون علامت 8-بیتی مشخص‌شده را به جریان می‌نویسد. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static [Null](./null/) | یک جریان بدون ذخیره‌سازی زیرین. |

## تعریف‌نوع

| تعریف‌نوع | توضیح |
| --- | --- |
| [Ptr](./ptr/) | یک نام مستعار برای اشاره‌گر shared به این کلاس. |

## همچنین نگاه کنید

* کلاس [IDisposable](../../system/idisposable/)
* فضای‌نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)