---
title: AuthenticatedStream
second_title: مرجع API Aspose.Slides برای C++
description: "متدهایی را برای ارسال اعتبارنامه‌ها از طریق یک جریان فراهم می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای ارسال به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 1
url: /fa/system.net.security/authenticatedstream/
---
## کلاس AuthenticatedStream

متدهایی را برای ارسال اعتبارنامه‌ها در یک جریان فراهم می‌کند. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را بر روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید.

```cpp
class AuthenticatedStream : public System::IO::Stream
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک عملیات خواندن ناهمزمان را آغاز می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک عملیات نوشتن ناهمزمان را آغاز می‌کند. |
| virtual void [Close](../../system.io/stream/close/)() | جریان را می‌بندد. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | بایت‌ها را به جریان مشخص شده کپی می‌کند. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | بایت‌ها را به جریان مشخص شده کپی می‌کند، با استفاده از اندازهٔ بافر مشخص شده. |
| void [Dispose](../../system.io/stream/dispose/)() override | تمام منابع استفاده‌شده توسط شی جاری را آزاد می‌کند و جریان را می‌بندد. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | تا تکمیل عملیات خواندن ناهمزمان مشخص‌شده صبر می‌کند. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | یک عملیات نوشتن ناهمزمان را پایان می‌دهد. تا تکمیل عملیات نوشتن ناهمزمان مشخص‌شده صبر می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنی‌گذاری [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ عددی ممیز شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ عددی ممیز شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| virtual void [Flush](../../system.io/stream/flush/)() | بافرهای این جریان را پاک می‌کند و تمام داده‌های بافرشده را به ذخیره‌سازی زیرین می‌نویسد. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به صورت ناهمزمان تمام بافرهای این جریان را پاک می‌کند، باعث می‌شود هر دادهٔ بافرشده‌ای به دستگاه زیرین نوشته شود و درخواست‌های لغو را نظارت می‌کند. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | به صورت ناهمزمان تمام بافرهای این 흐원 را پاک می‌کند، باعث می‌شود هر دادهٔ بافرشده‌ای به دستگاه زیرین نوشته شود و درخواست‌های لغو را نظارت می‌کند. |
| virtual **bool** [get_CanRead](../../system.io/stream/get_canread/)() const | تعیین می‌کند آیا جریان قابل خواندن است. |
| virtual **bool** [get_CanSeek](../../system.io/stream/get_canseek/)() const | تعیین می‌کند آیا جریان از جستجو (seeking) پشتیبانی می‌کند. |
| virtual **bool** [get_CanTimeout](../../system.io/stream/get_cantimeout/)() const | مقداری را برمی‌گرداند که تعیین می‌کند آیا جریان جاری می‌تواند زمان‌اتمام داشته باشد. |
| virtual **bool** [get_CanWrite](../../system.io/stream/get_canwrite/)() const | تعیین می‌کند آیا جریان قابل نوشتن است. |
| virtual **bool** [get_IsAuthenticated](./get_isauthenticated/)() const | مقداری را برمی‌گرداند که نشان می‌دهد آیا احراز هویت با موفقیت انجام شده است. |
| virtual **bool** [get_IsEncrypted](./get_isencrypted/)() const | مقداری را برمی‌گرداند که نشان می‌دهد آیا داده‌های ارسال‌شده با استفاده از این جریان رمزنگاری شده‌اند. |
| virtual **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const | مقداری را برمی‌گرداند که نشان می‌دهد آیا سرور و کلاینت احراز هویت شده‌اند. |
| virtual **bool** [get_IsServer](./get_isserver/)() const | مقداری را برمی‌گرداند که نشان می‌دهد آیا طرف محلی اتصال سرور است. |
| virtual **bool** [get_IsSigned](./get_issigned/)() const | مقداری را برمی‌گرداند که نشان می‌دهد آیا داده‌های ارسال‌شده با استفاده از این جریان امضا شده‌اند. |
| **bool** [get_LeaveInnerStreamOpen](./get_leaveinnerstreamopen/)() const | جریانی که توسط نمونه‌های فعلی کلاس برای ارسال و دریافت داده‌ها استفاده می‌شود را برمی‌گرداند. |
| virtual **int64_t** [get_Length](../../system.io/stream/get_length/)() const | طول جریانی را که بر حسب بایت است برمی‌گرداند. |
| virtual **int64_t** [get_Position](../../system.io/stream/get_position/)() const | موقعیت جاری جریاند را برمی‌گرداند. |
| virtual int [get_ReadTimeout](../../system.io/stream/get_readtimeout/)() const | مقداری به میلی‌ثانیه برمی‌گرداند که تعیین می‌کند جریان چه مدت سعی می‌کند بخواند پیش از اینکه زمان‌اتمام شود. |
| virtual int [get_WriteTimeout](../../system.io/stream/get_writetimeout/)() const | مقداری به میلی‌ثانیه برمی‌گرداند که تعیین می‌کند جریان چه مدت سعی می‌کند بنویسد پیش از اینکه زمان‌اتمام شود. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شی را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد [Object.GetHashCode()](../../system/object/gethashcode/) در C# است. امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را برمی‌گرداند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C# است. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شی نمونه‌ای از نوعی است که توسط targetType توصیف شده. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌کنندهٔ بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء مراقبت [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C# است. امکان تکثیر انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را می‌دهد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را می‌دهد. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | تعداد بایت مشخص‌شده را از جریان می‌خواند و آن‌ها را در آرایهٔ بایتی مشخص شده می‌نویسد. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | تعداد بایت مشخص‌شده را از جریان می‌خواند و آن‌ها را در آرایهٔ بایتی مشخص شده می‌نویسد. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | تعداد بایت مشخص‌شده را از جریان می‌خواند و آن‌ها را در آرایهٔ بایتی مشخص شده می‌نویسد. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | تعداد بایت مشخص‌شده را از جریان می‌خواند و آن‌ها را در بازهٔ بایتی مشخص شده می‌نویسد. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به صورت ناهمزمان توالی‌ای از بایت‌ها را از جریان جاری می‌خواند، موقعیت جاری در جریان را به تعداد بایت‌های خوانده‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به صورت ناهمزمان توالی‌ای از بایت‌ها را از جریان جاری می‌خواند، موقعیت جاری در جریان را به تعداد بایت‌های خوانده‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | یک بایت تک از جریان می‌خواند و مقدار عدد صحیح ۳۲ بیتی معادل مقدار بایت خوانده‌شده را برمی‌گرداند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr از نظر مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص ویژهٔ [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| virtual **int64_t** [Seek](../../system.io/stream/seek/)(**int64_t**, [SeekOrigin](../../system.io/seekorigin/)) | موقعیت جریان نمایانده‌شده توسط شی جاری را تنظیم می‌کند. |
| virtual void [set_Position](../../system.io/stream/set_position/)(**int64_t**) | موقعیت جریان را تنظیم می‌کند. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | مقداری را تنظیم می‌کند که تعیین می‌کند آیا جریان جاری می‌تواند زمان‌اتمام داشته باشد. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | مقدارانی به میلی‌ثانیه تنظیم می‌کند که تعیین می‌کند جریان چه مدت سعی می‌کند بخواند پیش از زمان‌اتمام. |
| virtual void [SetLength](../../system.io/stream/setlength/)(**int64_t**) | طول جریان نمایانده‌شده توسط شی جاری را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالبی nام را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C# است. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | غیرفعال‌سازی قفل بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء مراقبت [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual void [Write](../../system.io/stream/write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | بخش مشخص‌شده‌ای از بایت‌ها را از آرایهٔ بایتی مشخص به جریان می‌نویسد. |
| virtual void [Write](../../system.io/stream/write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | بخش مشخص‌شده‌ای از بایت‌ها را از آرایهٔ بایتی مشخص به جریان می‌نویسد. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | بخش مشخص‌شده‌ای از بایت‌ها را از آرایهٔ بایتی مشخص به جریان می‌نویسد. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | بخش مشخص‌شده‌ای از بایت‌ها را از بازهٔ بایتی مشخص به جریان می‌نویسد. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به صورت ناهمزمان توالی‌ای از بایت‌ها را به جریان جاری می‌نویسد، موقعیت جاری در این جریان را به تعداد بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به صورت ناهمزمان توالی‌ای از بایت‌ها را به جریان جاری می‌نویسد، موقعیت جاری در این جریان را به تعداد بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | مقدار صحیح بدون علامت ۸-بیتی مشخص‌شده را در جریان می‌نویسد. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static [Null](../../system.io/stream/null/) | جریانی بدون ذخیره‌سازی زیرین. |

## مراجع

* کلاس [Stream](../../system.io/stream/)
* فضای نام [System::Net::Security](../)
* کتابخانه [Aspose.Slides](../../)