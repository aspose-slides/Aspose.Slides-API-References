---
title: FileStream
second_title: مرجع API Aspose.Slides برای C++
description: "نمایانگر یک جریان فایل است که از عملیات خواندن و نوشتن همزمان و ناهمزمان پشتیبانی می‌کند. اشیای این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بسته‌بندی کنید و از این اشاره‌گر برای پاس دادن به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 287
url: /fa/system.io/filestream/
---
## کلاس FileStream

نمایانگر یک جریان فایل است که از عملیات خواندن و نوشتن همزمان و ناهمزمان پشتیبانی می‌کند. اشیای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای اعتبارسنجی می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بسته‌بندی کنید و از این اشاره‌گر برای پاس دادن به توابع به عنوان آرگومان استفاده کنید.

```cpp
class FileStream : public System::IO::Stream
```

## متدها

| متد | توضیح |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک عملیات خواندن ناهمزمان را آغاز می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک عملیات نوشتن ناهمزمان را آغاز می‌کند. |
| void [Close](./close/)() override | شیء [FileStream](./) فعلی را می‌بندد. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | بایت‌ها را به جریان مشخص شده کپی می‌کند. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | بایت‌ها را به جریان مشخص شده کپی می‌کند، با استفاده از اندازه بافر مشخص. |
| void [Dispose](../stream/dispose/)() override | تمام منابع استفاده‌شده توسط شیء فعلی را آزاد می‌کند و جریان را می‌بندد. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | تا تکمیل عملیات خواندن ناهمزمان مشخص شده صبر می‌کند. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | یک عملیات نوشتن ناهمزمان را پایان می‌دهد. تا تکمیل عملیات نوشتن ناهمزمان مشخص شده صبر می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیا را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیا از نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیا از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه اعداد نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسه اعداد نقطه شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | یک نمونه جدید از کلاس [FileStream](./) را می‌سازد و آن را با پارامترهای مشخص‌شده مقداردهی اولیه می‌کند. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/), **int32_t**, [FileOptions](../fileoptions/)) | یک نمونه جدید از کلاس [FileStream](./) را می‌سازد و آن را با پارامترهای مشخص‌شده مقداردهی اولیه می‌کند. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/), **int32_t**, **bool**) | یک نمونه جدید از کلاس [FileStream](./) را می‌سازد و آن را با پارامترهای مشخص‌شده مقداردهی اولیه می‌کند. |
|  [FileStream](./filestream/)(const [FileStream](./)\&) |  |
| void [Flush](./flush/)() override | بافرهای این جریان را پاک می‌کند و تمام داده‌های بافرشده را به فایل زیرین می‌نویسد. |
| void [Flush](./flush/)(**bool**) | بافرهای این جریان را پاک می‌کند و تمام داده‌های بافرشده را به فایل زیرین می‌نویسد. مترادف متد [Flush()](./flush/). |
| [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | به‌صورت ناهمزمان تمام بافرهای این جریان را پاک می‌کند، باعث می‌شود هر داده بافرشده‌ای به دستگاه زیرین نوشته شود و درخواست‌های لغو را نظارت می‌کند. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | به‌صورت ناهمزمان تمام بافرهای این جریان را پاک می‌کند، باعث می‌شود هر داده بافرشده‌ای به دستگاه زیرین نوشته شود و درخواست‌های لغو را نظارت می‌کند. |
| **bool** [get_CanRead](./get_canread/)() const override | مشخص می‌کند آیا جریان قابل خواندن است. |
| **bool** [get_CanSeek](./get_canseek/)() const override | مشخص می‌کند آیا جریان از جستجو پشتیبانی می‌کند. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | مقداری را برمی‌گرداند که تعیین می‌کند آیا جریان فعلی می‌تواند زمان‌سنجی شود. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | مشخص می‌کند آیا جریان قابل نوشتن است. |
| **int64_t** [get_Length](./get_length/)() const override | طول جریان را بر حسب بایت برمی‌گرداند. |
| [String](../../system/string/) [get_Name](./get_name/)() const | نام فایل محصور در شیء [FileStream](./) فعلی را برمی‌گرداند. |
| **int64_t** [get_Position](./get_position/)() const override | موقعیت فعلی جریان را برمی‌گرداند. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | مقداری به میلی‌ثانیه برمی‌گرداند که تعیین می‌کند جریان چه مدت سعی می‌کند بخواند قبل از زمان‌سنجی. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | مقداری به میلی‌ثانیه برمی‌گرداند که تعیین می‌کند جریان چه مدت سعی می‌کند بنویسد قبل از زمان‌سنجی. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده شمارنده مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش‌گذاری اشیای سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را می‌سازد. تمام ساختارهای داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده‌ی کپی. واقعاً هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و سازنده‌ی کپی برای زیردست‌ها را فعال می‌سازد. |
| [FileStream](./)\& [operator=](./operator_equal/)(const [FileStream](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. واقعاً هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و سازنده‌ی کپی برای زیردست‌ها را فعال می‌سازد. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | تعداد بایت مشخص‌شده را از جریان می‌خواند و در آرایه بایت مشخص شده می‌نویسد. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | تعداد بایت مشخص‌شده را از جریان می‌خواند و در آرایه بایت مشخص شده می‌نویسد. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | تعداد بایت مشخص‌شده را از جریان می‌خواند و در آرایه بایت مشخص شده می‌نویسد. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | تعداد بایت مشخص‌شده را از جریان می‌خواند و در اسپن بایت مشخص شده می‌نویسد. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | به‌صورت ناهمزمان دنباله‌ای از بایت‌ها را از جریان فعلی می‌خواند، موقعیت را در جریان به تعداد بایت‌های خوانده‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به‌صورت ناهمزمان دنباله‌ای از بایت‌ها را از جریان فعلی می‌خواند، موقعیت را در جریان به تعداد بایت‌های خوانده‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| **int32_t** [ReadByte](./readbyte/)() override | یک بایت تک از جریان می‌خواند و مقدار عدد صحیح ۳۲ بیتی معادل مقدار بایت خوانده‌شده را برمی‌گرداند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیا را طبق مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیا را طبق مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع شیء نوع مقدار با nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد مراجع مشترک را به مقدار مشخص کاهش می‌دهد. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | موقعیت جریان نماینده توسط شیء فعلی را تنظیم می‌کند. |
| void [set_Position](./set_position/)(**int64_t**) override | جریان را تخلیه می‌کند و سپس موقعیت جریان را تنظیم می‌کند. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | مقداری را تنظیم می‌کند که تعیین می‌کند آیا جریان فعلی می‌تواند زمان‌سنجی شود. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | مقداری به میلی‌ثانیه تنظیم می‌کند که تعیین می‌کند جریان چه مدت سعی می‌کند بخواند پیش از زمان‌سنجی. |
| void [SetLength](./setlength/)(**int64_t**) override | طول جریان نماینده توسط شیء فعلی را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان قالب nth را به یک اشاره‌گر ضعیف (به‌جای مشترک) تنظیم می‌کند. امکان سوئیچ کردن اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مراجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مراجع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مراجع مشترک را کاهش داده و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیا سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری بیان lock() در C# را باز می‌کند. به‌صورت مستقیم صدا بزنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مراجع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مراجع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | بخش مشخص‌شده‌ای از بایت‌ها را از آرایه بایت مشخص‌شده به جریان می‌نویسد. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | بخش مشخص‌شده‌ای از بایت‌ها را از آرایه بایت مشخص‌شده به جریان می‌نویسد. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | بخش مشخص‌شده‌ای از بایت‌ها را از آرایه بایت مشخص‌شده به جریان می‌نویسد. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | بخش مشخص‌شده‌ای از بایت‌ها را از اسپن بایت به جریان می‌نویسد. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | به‌صورت ناهمزمان دنباله‌ای از بایت‌ها را به جریان فعلی می‌نویسد، موقعیت جاری را در این جریان به تعداد بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به‌صورت ناهمزمان دنباله‌ای از بایت‌ها را به جریان فعلی می‌نویسد، موقعیت جاری را در این جریان به تعداد بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | مقدار عدد صحیح بدون علامت ۸ بیتی مشخص‌شده را به جریان می‌نویسد. |
|  [~FileStream](./~filestream/)() | تخریب‌کننده. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از میان می‌برد. تمام ساختارهای داخلی را آزاد می‌کند. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static constexpr [DefaultBufferSize](./defaultbuffersize/) | مقدار پیش‌فرض تعداد بایت‌های بافرشده در طول عملیات خواندن و نوشتن. |
| static [Null](../stream/null/) | جریانی بدون ذخیره‌سازی زیرین. |

## موارد مرتبط

* کلاس [Stream](../stream/)
* فضای‌نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)