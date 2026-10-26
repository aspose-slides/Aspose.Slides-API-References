---
title: NetworkStream
second_title: مرجع API Aspose.Slides برای C++
description: "جریان پایه داده‌ها را برای دسترسی شبکه فراهم می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونهٔ این نوع را روی پشته یا با عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا شکست‌های اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 40
url: /fa/system.net.sockets/networkstream/
---
## NetworkStream کلاس

Provides the underlying stream of the data for the network access. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class NetworkStream : public System::IO::Stream
```

## متدها

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | یک عملیات خواندن ناهمزمان را آغاز می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک عملیات خواندن ناهمزمان را آغاز می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | یک عملیات نوشتن ناهمزمان را آغاز می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک عملیات نوشتن ناهمزمان را آغاز می‌کند. |
| void [Close](./close/)(int) | نمونهٔ فعلی را پس از انقضای زمان مشخص‌شده می‌بندد. |
| virtual void [Close](../../system.io/stream/close/)() | استریم را می‌بندد. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | بایت‌ها را به استریم مشخص‌شده کپی می‌کند. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | بایت‌ها را به استریم مشخص‌شده کپی می‌کند، با استفاده از اندازهٔ بافر مشخص‌شده. |
| void [Dispose](../../system.io/stream/dispose/)() override | تمام منابع استفاده‌شده توسط شیء فعلی را آزاد می‌کند و استریم را می‌بندد. |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | تا تکمیل عملیات خواندن ناهمزمان مشخص‌شده منتظر می‌ماند. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | تا تکمیل عملیات خواندن ناهمزمان مشخص‌شده منتظر می‌ماند. |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | یک عملیات نوشتن ناهمزمان را پایان می‌دهد. تا تکمیل عملیات نوشتن ناهمزمان مشخص‌شده منتظر می‌ماند. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | یک عملیات نوشتن ناهمزمان را پایان می‌دهد. تا تکمیل عملیات نوشتن ناهمزمان مشخص‌شده منتظر می‌ماند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ عدد شناور مشابه C# را شبیه‌سازی می‌کند که دو NaN برابر در نظر گرفته می‌شوند حتی با وجود اینکه طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ عدد شناور مشابه C# را شبیه‌سازی می‌کند که دو NaN برابر در نظر گرفته می‌شوند حتی با وجود اینکه طبق IEC 60559:1989 NaN برابر هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| void [Flush](./flush/)() override | بافرهای این استریم را پاک می‌کند و تمام دادهٔ بافری را به ذخیره‌سازی پایه می‌نویسد. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به‌صورت ناهمزمان تمام بافرهای این استریم را پاک می‌کند، باعث می‌شود هر دادهٔ بافری به دستگاه پایه نوشته شود و درخواست‌های لغو را مانیتور می‌کند. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | به‌صورت ناهمزمان تمام بافرهای این استریم را پاک می‌کند، باعث می‌شود هر دادهٔ بافری به دستگاه پایه نوشته شود و درخواست‌های لغو را مانیتور می‌کند. |
| **bool** [get_CanRead](./get_canread/)() const override | تعیین می‌کند آیا استریم قابل خواندن است. |
| **bool** [get_CanSeek](./get_canseek/)() const override | تعیین می‌کند آیا استریم از جستجو پشتیبانی می‌کند. |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | مقداری را دریافت می‌کند که تعیین می‌کند آیا استریم فعلی می‌تواند زمان‌اتمام داشته باشد. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | تعیین می‌کند آیا استریم قابل نوشتن است. |
| **bool** [get_DataAvailable](./get_dataavailable/)() const | مقداری را برمی‌گرداند که نشان می‌دهد آیا دادهٔ قابل خواندن موجود است. |
| **int64_t** [get_Length](./get_length/)() const override | طول استریم را به بایت برمی‌گرداند. |
| **int64_t** [get_Position](./get_position/)() const override | موقعیت فعلی استریم را برمی‌گرداند. |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | مقداری به میلی‌ثانیه دریافت می‌کند که تعیین می‌کند چه مدت استریم سعی می‌کند قبل از زمان‌اتمام بخواند. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\> [get_Socket](./get_socket/)() | دریافت [Socket](../socket/) پایه. |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | مقداری به میلی‌ثانیه دریافت می‌کند که تعیین می‌کند چه مدت استریم سعی می‌کند قبل از زمان‌اتمام بنویسید. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مشابه متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را دریافت می‌کند. مشابه فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمونه‌ای از نوع توصیف‌شده توسط targetType است. مشابه عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری عبارت lock() در C#. مستقیم صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | مشابه متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>) | یک نمونهٔ جدید می‌سازد. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>, [System::IO::FileAccess](../../system.io/fileaccess/), **bool**) | یک نمونهٔ جدید می‌سازد. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>, **bool**) | یک نمونهٔ جدید می‌سازد. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن زیرکلاس‌ها با کپی را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساختن زیرکلاس‌ها با کپی را فراهم می‌کند. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | تعداد مشخصی بایت را از استریم می‌خواند و به آرایهٔ بایت مشخص‌شده می‌نویسد. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | تعداد مشخصی بایت را از استریم می‌خواند و به آرایهٔ بایت مشخص‌شده می‌نویسد. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | تعداد مشخصی بایت را از استریم می‌خواند و به آرایهٔ بایت مشخص‌شده می‌نویسد. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | تعداد مشخصی بایت را از استریم می‌خواند و به اسلایس بایت مشخص‌شده می‌نویسد. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به‌صورت ناهمزمان یک توالی بایت را از استریم فعلی می‌خواند، موقعیت در استریم را به اندازه بایت‌های خوانده‌شده پیش می‌برد و درخواست‌های لغو را مانیتور می‌کند. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به‌صورت ناهمزمان یک توالی بایت را از استریم فعلی می‌خواند، موقعیت در استریم را به اندازه بایت‌های خوانده‌شده پیش می‌برد و درخواست‌های لغو را مانیتور می‌کند. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | یک بایت تک را از استریم می‌خواند و مقدار عدد صحیح 32-بیتی معادل مقدار بایت خوانده‌شده را برمی‌گرداند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسهٔ مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارندهٔ مرجع‌اشتراکی را به مقدار مشخص‌شده کاهش می‌دهد. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | موقعیت استریم نمایندهٔ شیء فعلی را تنظیم می‌کند. |
| void [set_Position](./set_position/)(**int64_t**) override | موقعیت استریم را تنظیم می‌کند. |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | مقداری که تعیین می‌کند آیا استریم فعلی می‌تواند زمان‌اتمام داشته باشد را تنظیم می‌کند. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | مقداری که تعیین می‌کند آیا استریم فعلی می‌تواند زمان‌اتمام داشته باشد را تنظیم می‌کند. |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | مقداری به میلی‌ثانیه که تعیین می‌کند استریم چه مدت سعی می‌کند قبل از زمان‌اتمام بخواند را تنظیم می‌کند. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | مقداری به میلی‌ثانیه که تعیین می‌کند استریم چه مدت سعی می‌کند قبل از زمان‌اتمام بخواند را تنظیم می‌کند. |
| void [SetLength](./setlength/)(**int64_t**) override | طول استریم نمایندهٔ شیء فعلی را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nام را به یک اشاره‌گر ضعیف (نه اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع‌اشتراکی را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع‌اشتراکی را افزایش می‌دهد. نباید مستقیم صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع‌اشتراکی را کاهش می‌دهد و مقدار آن را برمی‌گرداند. نباید مستقیم صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | مشابه متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساختار typeof([System.Object](../../system/object/)) در C#. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی باز کردن قفل عبارت lock() در C#. مستقیم صدا بزنید یا از شیء sentry [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیم صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیم صدا زده شود؛ به جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | زیرمحدودیت مشخص‌شده‌ای از بایت‌ها را از آرایهٔ بایت مشخص‌شده به استریم می‌نویسد. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | زیرمحدودیت مشخص‌شده‌ای از بایت‌ها را از آرایهٔ بایت مشخص‌شده به استریم می‌نویسد. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | زیرمحدودیت مشخص‌شده‌ای از بایت‌ها را از آرایهٔ بایت مشخص‌شده به استریم می‌نویسد. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | زیرمحدودیت مشخص‌شده‌ای از بایت‌ها را از اسلایس بایت مشخص‌شده به استریم می‌نویسد. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به‌صورت ناهمزمان یک توالی بایت را به استریم فعلی می‌نویسد، موقعیت جاری در این استریم را به اندازه بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را مانیتور می‌کند. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به‌صورت ناهمزمان یک توالی بایت را به استریم فعلی می‌نویسد، موقعیت جاری در این استریم را به اندازه بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را مانیتور می‌کند. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | مقدار عدد صحیح بی‌علامت 8-بیتی مشخص‌شده را به استریم می‌نویسد. |
| virtual  [~NetworkStream](./~networkstream/)() | نمونهٔ فعلی را تخریب می‌کند. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای دادهٔ داخلی را آزاد می‌کند. |

## فیلدها

| Field | Description |
| --- | --- |
| static [Null](../../system.io/stream/null/) | استریمی بدون ذخیره‌سازی پایه. |

## موارد مرتبط

* Class [Stream](../../system.io/stream/)
* Namespace [System::Net::Sockets](../)
* Library [Aspose.Slides](../../)