---
title: CryptoStream
second_title: "Aspose.Slides برای C++ مرجع API"
description: "پیاده‌سازی جریان که جریان موجود را با یک تابع رمزنگاری بسته‌بندی می‌کند. اشیاء این کلاس باید تنها با استفاده از تابع System::MakeObject() اختصاص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا نقص‌های ادعا می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای انتقال به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 53
url: /fa/system.security.cryptography/cryptostream/
---
## CryptoStream کلاس

Stream implementation that wraps existing stream with a cryptographic function. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CryptoStream : public System::IO::Stream
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک عملیات خواندن ناهمزمان را آغاز می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک عملیات نوشتن ناهمزمان را آغاز می‌کند. |
| void [Close](./close/)() override | اتصال را می‌بندد. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | بایت‌ها را به جریان مشخص‌شده کپی می‌کند. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | بایت‌ها را به جریان مشخص‌شده کپی می‌کند، با استفاده از اندازه بافر مشخص‌شده. |
|  [CryptoStream](./cryptostream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\>\&, [CryptoStreamMode](../cryptostreammode/)) | سازنده. |
| void [Dispose](../../system.io/stream/dispose/)() override | تمام منابع استفاده‌شده توسط شیء فعلی را آزاد می‌کند و جریان را می‌بندد. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | تا تکمیل شدن عملیات خواندن ناهمزمان مشخص‌شده صبر می‌کند. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | یک عملیات نوشتن ناهمزمان را پایان می‌دهد. تا تکمیل شدن عملیات نوشتن ناهمزمان مشخص‌شده صبر می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | شیءها را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه‌ی نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه‌ی نقطه‌اعشاری به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر با هیچ مقدار، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| void [Flush](./flush/)() override | بافر را به جریان بسته‌شده تخلیه می‌کند. کاری انجام نمی‌دهد زیرا الگوریتم تبدیل ممکن است هنوز منتظر داده‌های بیشتری باشد. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به‌صورت ناهمزمان تمام بافرها را برای این جریان پاک می‌کند، باعث می‌شود هر داده‌ی بافر شده‌ای به دستگاه پایه نوشته شود، و درخواست‌های لغو را نظارت می‌کند. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | به‌صورت ناهمزمان تمام بافرها را برای این جریان پاک می‌کند، باعث می‌شود هر داده‌ی بافر شده‌ای به دستگاه پایه نوشته شود، و درخواست‌های لغو را نظارت می‌کند. |
| void [FlushFinalBlock](./flushfinalblock/)() | داده‌ای که هنوز در بافر است را به جریان می‌نویسد. |
| **bool** [get_CanRead](./get_canread/)() const override | بررسی می‌کند که آیا جریان قابل خواندن است. |
| **bool** [get_CanSeek](./get_canseek/)() const override | بررسی می‌کند که آیا جریان قابل جستجو است. |
| virtual **bool** [get_CanTimeout](../../system.io/stream/get_cantimeout/)() const | مقداری را برمی‌گرداند که تعیین می‌کند آیا جریان جاری می‌تواند زمان‌سلب شود. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | بررسی می‌کند که آیا جریان قابل نوشتن است. |
| **int64_t** [get_Length](./get_length/)() const override | طول جریان را برمی‌گرداند. پشتیبانی نمی‌شود. |
| **int64_t** [get_Position](./get_position/)() const override | موقعیت فعلی در جریان را برمی‌گرداند. پشتیبانی نمی‌شود. |
| virtual int [get_ReadTimeout](../../system.io/stream/get_readtimeout/)() const | مقداری بر حسب میلی‌ثانیه برمی‌گرداند که تعیین می‌کند جریان تا چه مدت سعی می‌کند پیش از زمان‌سلب بخواند. |
| virtual int [get_WriteTimeout](../../system.io/stream/get_writetimeout/)() const | مقداری بر حسب میلی‌ثانیه برمی‌گرداند که تعیین می‌کند جریان تا چه مدت سعی می‌کند پیش از زمان‌سلب بنویسد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند که آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری عبارت C# lock() را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان شبیه‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده‌ی کپی. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | داده را از جریان می‌خواند. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | داده را از جریان می‌خواند. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | تعداد بایت مشخص‌شده را از جریان می‌خواند و به آرایه بایت مشخص‌شده می‌نویسد. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | تعداد بایت مشخص‌شده را از جریان می‌خواند و به بخش بایت مشخص‌شده می‌نویسد. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به‌صورت ناهمزمان توالی‌ای از بایت‌ها را از جریان جاری می‌خواند، موقعیت درون جریان را به اندازه بایت‌های خوانده‌شده پیش می‌برد، و درخواست‌های لغو را نظارت می‌کند. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به‌صورت ناهمزمان توالی‌ای از بایت‌ها را از جریان جاری می‌خواند، موقعیت درون جریان را به اندازه بایت‌های خوانده‌شده پیش می‌برد، و درخواست‌های لغو را نظارت می‌کند. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | یک بایت واحد را از جریان میخواند و مقدار عدد صحیح ۳۲ بیتی معادل مقدار بایت خوانده‌شده را برمی‌گرداند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقداری را با nullptr به‌صورت ارجاعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | به موقعیت در جریان می‌پرد. پشتیبانی نمی‌شود. |
| void [set_Position](./set_position/)(**int64_t**) override | به موقعیت در جریان می‌پرد. پشتیبانی نمی‌شود. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | مقداری را تنظیم می‌کند که تعیین می‌کند آیا جریان جاری می‌تواند زمان‌سلب شود. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | مقدار برحسب میلی‌ثانیه تنظیم می‌کند که تعیین می‌کند جریان تا چه مدت سعی می‌کند پیش از زمان‌سلب بخواند. |
| void [SetLength](./setlength/)(**int64_t**) override | به اندازه‌ی جریان می‌پرد. پشتیبانی نمی‌شود. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام الگو را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری عبارت C# lock() را باز می‌کند. به‌صورت مستقیم فراخوانی کنید یا از شیء نگهبانی [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | داده را به جریان می‌نویسد. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | داده را به جریان می‌نویسد. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | بخش مشخص‌شده‌ای از بایت‌ها را از آرایه بایت مشخص‌شده به جریان می‌نویسد. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | بخش مشخص‌شده‌ای از بایت‌ها را از بخش بایت مشخص‌شده به جریان می‌نویسد. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به‌صورت ناهمزمان توالی‌ای از بایت‌ها را به جریان جاری می‌نویسد، موقعیت جاری در این جریان را به اندازه بایت‌های نوشته‌شده پیش می‌برد، و درخواست‌های لغو را نظارت می‌کند. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به‌صورت ناهمزمان توالی‌ای از بایت‌ها را به جریان جاری می‌نویسد، موقعیت جاری در این جریان را به اندازه بایت‌های نوشته‌شده پیش می‌برد، و درخواست‌های لغو را نظارت می‌کند. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | مقدار عدد صحیح بدون علامت ۸ بیتی مشخص‌شده را به جریان می‌نویسد. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static [Null](../../system.io/stream/null/) | یک جریان بدون ذخیره‌سازی زیرین. |

## موارد مرتبط

* کلاس [Stream](../../system.io/stream/)
* فضای‌نام [System::Security::Cryptography](../)
* کتابخانه [Aspose.Slides](../../)