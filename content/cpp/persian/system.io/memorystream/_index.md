---
title: MemoryStream
second_title: Aspose.Slides برای C++ مرجع API
description: "نمایش یک جریان که از حافظه می‌خواند و به آن می‌نویسد. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچانید و از این اشاره‌گر برای پاس دادن به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 326
url: /fa/system.io/memorystream/
---
## کلاس MemoryStream

نمایش یک جریان که از حافظه می‌خواند و به آن می‌نویسد. اشیاء این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی استک یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) ببندید و از این اشاره‌گر برای پاس دادن به توابع به عنوان آرگومان استفاده کنید.

```cpp
class MemoryStream : public System::IO::Stream
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک عملیات خواندن ناهمزمان را آغاز می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک عملیات نوشتن ناهمزمان را آغاز می‌کند. |
| void [Close](./close/)() override | جریان را می‌بندد. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | بایت‌ها را به جریان مشخص شده کپی می‌کند. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | بایت‌ها را به جریان مشخص شده کپی می‌کند، با استفاده از اندازه بافر تعیین‌شده. |
| void [Dispose](../stream/dispose/)() override | تمام منابع استفاده‌شده توسط شیء فعلی را آزاد می‌کند و جریان را می‌بندد. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | تا تکمیل شدن عملیات خواندن ناهمزمان مشخص‌شده صبر می‌کند. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | یک عملیات نوشتن ناهمزمان را پایان می‌دهد. تا تکمیل شدن عملیات نوشتن ناهمزمان مشخص‌شده صبر می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | شیءها را با استفاده از سینتاکس C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه‌ نقطه‌شناسی به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند؛ اگرچه مطابق IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه‌ نقطه‌شناسی به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند؛ اگرچه مطابق IEC 60559:1989 NaN برابر با هیچ مقداری نیست، از جمله NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| void [Flush](./flush/)() override | کاری انجام نمی‌دهد. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به‌صورت ناهمزمان تمام بافرهای این جریان را پاک می‌کند، باعث می‌شود هر داده بافرشده‌ای به دستگاه پایه نوشته شود و درخواست‌های لغو را نظارت می‌کند. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | به‌صورت ناهمزمان تمام بافرهای این جریان را پاک می‌کند، باعث می‌شود هر داده بافرشده‌ای به دستگاه پایه نوشته شود و درخواست‌های لغو را نظارت می‌کند. |
| **bool** [get_CanRead](./get_canread/)() const override | تعیین می‌کند آیا جریان قابل خواندن است. |
| **bool** [get_CanSeek](./get_canseek/)() const override | تعیین می‌کند آیا جریان از جستجو پشتیبانی می‌کند. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | مقداری را برمی‌گرداند که تعیین می‌کند آیا جریان کنونی می‌تواند زمان‌سرب شود. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | تعیین می‌کند آیا جریان قابل نوشتن است. |
| int [get_Capacity](./get_capacity/)() | ظرفیت فعلی بافر حافظه پایه را برمی‌گرداند. |
| **int64_t** [get_Length](./get_length/)() const override | طول جریان را بر حسب بایت برمی‌گرداند. |
| **int64_t** [get_Position](./get_position/)() const override | موقعیت فعلی جریان را برمی‌گرداند. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | مقداری بر حسب میلی‌ثانیه بر‌می‌گرداند که تعیین می‌کند جریان چه مدت سعی می‌کند بخواند قبل از زمان‌سرب شدن. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | مقداری بر حسب میلی‌ثانیه بر‌می‌گرداند که تعیین می‌کند جریان چه مدت سعی می‌کند بنویسد قبل از زمان‌سرب شدن. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBuffer](./getbuffer/)() | یک اشاره‌گر به بافر پایه را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌کردن با عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [MemoryStream](./memorystream/)() | یک نمونه جدید از کلاس [MemoryStream](./) را با ظرفیت اولیه برابر ۰ می‌سازد. |
|  [MemoryStream](./memorystream/)(int) | یک نمونه جدید از کلاس [MemoryStream](./) را می‌سازد که نمایانگر یک جریان بر پایه بافر حافظه با اندازه مشخص است. |
|  [MemoryStream](./memorystream/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **bool**) | یک نمونه جدید از کلاس [MemoryStream](./) را می‌سازد که نمایانگر یک جریان حافظه متصل به بافر حافظه مشخص است. یک پارامتر تعیین می‌کند آیا جریان قابل نوشتن است. |
|  [MemoryStream](./memorystream/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int, **bool**, **bool**) | یک نمونه جدید از کلاس [MemoryStream](./) را می‌سازد که نمایانگر یک جریان حافظه متصل به بخشی از بافر حافظه مشخص است که از اندیس مشخص شروع شده و شامل تعداد عناصر مشخص می‌شود. پارامترها تعیین می‌کند آیا جریان قابل نوشتن است و آیا می‌توان متد GetBytes() را فراخوانی کرد. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیز را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور اختصاص. در واقع هیچ چیز را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌سازد. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | تعداد مشخصی از بایت‌ها را از جریان می‌خواند و در آرایه بایت مشخص‌شده می‌نویسد. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | تعداد مشخصی از بایت‌ها را از جریان می‌خواند و در آرایه بایت مشخص‌شده می‌نویسد. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | تعداد مشخصی از بایت‌ها را از جریان می‌خواند و در آرایه بایت مشخص‌شده می‌نویسد. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | تعداد مشخصی از بایت‌ها را از جریان می‌خواند و در بازهٔ بایتی مشخص‌شده می‌نویسد. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به‌صورت ناهمزمان یک دنباله بایت‌ها را از جریان جاری می‌خواند، موقعیت درون جریان را به اندازهٔ تعداد بایت‌های خوانده‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به‌صورت ناهمزمان یک دنباله بایت‌ها را از جریان جاری می‌خواند، موقعیت درون جریان را به اندازهٔ تعداد بایت‌های خوانده‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| int [ReadByte](./readbyte/)() override | یک بایت واحد را از جریان می‌خواند و مقدار صحیح ۳۲ بیتی معادل مقدار بایت خوانده‌شده را برمی‌گرداند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقداری را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | موقعیت جریان را که توسط شیء فعلی نمایندگی می‌شود تنظیم می‌کند. |
| void [set_Capacity](./set_capacity/)(int) | ظرفیت بافر حافظه پایه را تنظیم می‌کند. |
| void [set_Position](./set_position/)(**int64_t**) override | موقعیت جریان را تنظیم می‌کند. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | مقداری را تنظیم می‌کند که تعیین می‌کند آیا جریان فعلی می‌تواند زمان‌سرب شود. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | مقداری بر حسب میلی‌ثانیه تنظیم می‌کند که تعیین می‌کند جریان چه مدت سعی می‌کند بخواند قبل از زمان‌سرب شدن. |
| void [SetLength](./setlength/)(**int64_t**) override | طول جریان را که توسط شیء فعلی نمایندگی می‌شود تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگوی قالب را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌سازد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ToArray](./toarray/)() | یک کپی از بافر حافظه پایه به‌صورت آرایه‌ای از بایت‌ها برمی‌گرداند. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| **bool** [TryGetBuffer](./trygetbuffer/)([ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\&) | آرایه‌ای از بایت‌های بدون علامت که این جریان از آن ساخته شده است را برمی‌گرداند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌کردن معکوس عبارت C# lock() را پیاده‌سازی می‌کند. مستقیماً فراخوانی کنید یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | بخش مشخص‌شده‌ای از بایت‌ها را از آرایه بایت مشخص به جریان می‌نویسد. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | بخش مشخص‌شده‌ای از بایت‌ها را از آرایه بایت مشخص به جریان می‌نویسد. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | بخش مشخص‌شده‌ای از بایت‌ها را از آرایه بایت مشخص به جریان می‌نویسد. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | بخش مشخص‌شده‌ای از بایت‌ها را از بازه بایتی مشخص به جریان می‌نویسد. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به‌صورت ناهمزمان یک دنباله بایت‌ها را به جریان جاری می‌نویسد، موقعیت فعلی درون این جریان را به اندازهٔ تعداد بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به‌صورت ناهمزمان یک دنباله بایت‌ها را به جریان جاری می‌نویسد، موقعیت فعلی درون این جریان را به اندازهٔ تعداد بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | مقدار صحیح ۸ بیتی بدون علامت مشخص‌شده را به جریان می‌نویسد. |
| virtual void [WriteTo](./writeto/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>) | محتوای بافر پایه را به جریان مشخص‌شده می‌نویسد. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static [Null](../stream/null/) | یک جریان بدون ذخیره‌سازی پایه. |

## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [Ptr](./ptr/) | یک نام مستعار برای اشاره‌گر مشترک به خود. |

## همچنین ببینید

* کلاس [Stream](../stream/)
* فضای نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)