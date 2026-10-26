---
title: BufferedStream
second_title: Aspose.Slides برای مرجع API C++
description: "یک لایه بافر بر روی یک جریان دیگر اضافه می‌کند. اشیای این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات ادعا می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به توابع به‌عنوان آرگومان استفاده کنید."
type: docs
weight: 118
url: /fa/system.io/bufferedstream/
---
## BufferedStream کلاس

یک لایهٔ بافرینگ در بالای یک جریان دیگر اضافه می‌کند. اشیای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات ادعایی خواهد شد. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بلافاصله بپیچید و از این اشاره‌گر برای عبور به توابع به عنوان آرگومان استفاده کنید.

```cpp
class BufferedStream : public System::IO::Stream
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک عملیات خواندن ناهمزمان را آغاز می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک عملیات نوشتن ناهمزمان را آغاز می‌کند. |
|  [BufferedStream](./bufferedstream/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | یک شیٔ [BufferedStream](./) می‌سازد که جریان مشخص‌شده را می‌پیچه و از یک بافر 4096 بایتی استفاده می‌کند. |
|  [BufferedStream](./bufferedstream/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, int) | یک شیٔ [BufferedStream](./) می‌سازد که جریان مشخص‌شده را می‌پیچه و از یک بافر با اندازهٔ تعیین‌شده استفاده می‌کند. |
| virtual void [Close](../stream/close/)() | جریان را می‌بندد. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | بایت‌ها را به جریان مشخص‌شده کپی می‌کند. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | بایت‌ها را به جریان مشخص‌شده کپی می‌کند، با استفاده از اندازهٔ بافر تعیین‌شده. |
| void [Dispose](../stream/dispose/)() override | تمام منابع استفاده‌شده توسط شیٔ فعلی را آزاد می‌کند و جریان را می‌بندد. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | تا تکمیل عملیات خواندن ناهمزمان مشخص‌شده صبر می‌کند. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | یک عملیات نوشتن ناهمزمان را خاتمه می‌دهد. تا تکمیل عملیات نوشتن ناهمزمان مشخص‌شده صبر می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیای را با استفاده از معانی C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیای نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیای نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| void [Flush](./flush/)() override | محتوای بافر را به جریان زیربنایی می‌نویسد. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به صورت ناهمزمان تمام بافرها را برای این جریان پاک می‌کند، باعث می‌شود هر دادهٔ بافرشده به دستگاه زیربنایی نوشته شود و درخواست‌های لغو را پایش می‌کند. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | به صورت ناهمزمان تمام بافرها را برای این جریان پاک می‌کند، باعث می‌شود هر دادهٔ بافرشده به دستگاه زیربنایی نوشته شود و درخواست‌های لغو را پایش می‌کند. |
| **bool** [get_CanRead](./get_canread/)() const override | تشخیص می‌دهد آیا جریان قابل خواندن است. |
| **bool** [get_CanSeek](./get_canseek/)() const override | تشخیص می‌دهد آیا جریان از جستجو پشتیبانی می‌کند. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | مقداری را دریافت می‌کند که تعیین می‌کند آیا جریان جاری می‌تواند زمان‌سنجی شود. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | تشخیص می‌دهد آیا جریان قابل نوشتن است. |
| **int64_t** [get_Length](./get_length/)() const override | طول جریان را برمی‌گرداند. |
| **int64_t** [get_Position](./get_position/)() const override | موقعیت فعلی جریان را برمی‌گرداند. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | مقدار را به میلی‌ثانیه دریافت می‌کند که تعیین می‌کند جریان چه مدت سعی می‌کند بخواند پیش از زمان‌سنجی. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | مقدار را به میلی‌ثانیه دریافت می‌کند که تعیین می‌کند جریان چه مدت سعی می‌کند بنویسد پیش از زمان‌سنجی. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیٔ را دریافت می‌کند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌کردن اشیای سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیٔ را دریافت می‌کند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیٔ نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | پیاده‌سازی قفل‌گذاری بیان lock() در C#. مستقیم فراخوانی کنید یا از شیٔ محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی از زیرکلاس‌ها را فراهم می‌کند. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | تعداد مشخص‌شده بایت‌ها را از جریان زیرین می‌خواند و به آرایه بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | تعداد مشخص‌شده بایت‌ها را از جریان زیرین می‌خواند و به آرایه بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | تعداد مشخص‌شده بایت‌ها را از جریان می‌خواند و به آرایه بایتی مشخص‌شده می‌نویسد. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | تعداد مشخص‌شده بایت‌ها را از جریان می‌خواند و به بازهٔ بایتی مشخص‌شده می‌نویسد. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به صورت ناهمزمان دنباله‌ای از بایت‌ها را از جریان جاری می‌خواند، موقعیت داخل جریان را به اندازهٔ بایت‌های خوانده‌شده پیش می‌برد و درخواست‌های لغو را پایش می‌کند. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به صورت ناهمزمان دنباله‌ای از بایت‌ها را از جریان جاری می‌خواند، موقعیت داخل جریان را به اندازهٔ بایت‌های خوانده‌شده پیش می‌برد و درخواست‌های لغو را پایش می‌کند. |
| int [ReadByte](./readbyte/)() override | یک بایت واحد را از جریان زیرین می‌خواند و مقدار عدد صحیح ۳۲ بیتی معادل مقدار بایت خوانده‌شده را بر می‌گرداند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیٔ نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای مورد رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع اشتراک‌گذاری‌شده را با مقدار مشخص‌شده کاهش می‌دهد. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | موقعیت جریان نمایانده‌شده توسط شیٔ فعلی را تنظیم می‌کند. |
| void [set_Position](./set_position/)(**int64_t**) override | بافر را به جریان زیربنایی تخلیه می‌کند و سپس موقعیت جریان را تنظیم می‌کند. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | مقدار را تنظیم می‌کند که تعیین می‌کند آیا جریان جاری می‌تواند زمان‌سنجی شود. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | مقدار را به میلی‌ثانیه تنظیم می‌کند که تعیین می‌کند جریان چه مدت سعی می‌کند بخواند پیش از زمان‌سنجی. |
| void [SetLength](./setlength/)(**int64_t**) override | طول جریان نمایانده‌شده توسط شیٔ فعلی را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع اشتراک‌گذاری‌شده را دریافت می‌کند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع اشتراک‌گذاری‌شده را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع اشتراک‌گذاری‌شده را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیای سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | پیاده‌سازی باز کردن قفل بیان lock() در C#. مستقیم فراخوانی کنید یا از شیء محافظ [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | بخش مشخص‌شده‌ای از بایت‌ها را از آرایه بایتی مشخص‌شده به جریان زیربنایی می‌نویسد. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | بخش مشخص‌شده‌ای از بایت‌ها را از آرایه بایتی مشخص‌شده به جریان زیربنایی می‌نویسد. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | بخش مشخص‌شده‌ای از بایت‌ها را از آرایه بایتی مشخص‌شده به جریان می‌نویسد. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | بخش مشخص‌شده‌ای از بایت‌ها را از بازهٔ بایتی مشخص‌شده به جریان می‌نویسد. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به صورت ناهمزمان دنباله‌ای از بایت‌ها را به جریان جاری می‌نویسد، موقعیت جاری داخل این جریان را به اندازهٔ بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را پایش می‌کند. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به صورت ناهمزمان دنباله‌ای از بایت‌ها را به جریان جاری می‌نویسد، موقعیت جاری داخل این جریان را به اندازهٔ بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را پایش می‌کند. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | مقدار صحیح بدون علامت 8 بیتی مشخص‌شده را به جریان زیربنایی می‌نویسد. |
| virtual  [~BufferedStream](./~bufferedstream/)() | دست‌نایست. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌سازد. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static [Null](../stream/null/) | جریانی بدون ذخیره‌سازی زیرین. |

## موارد مرتبط

* کلاس [Stream](../stream/)
* فضای نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)