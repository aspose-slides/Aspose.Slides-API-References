---
title: BasicSTDOStreamWrapper
second_title: مرجع API Aspose.Slides برای C++
description: "نمایانگر بسته‌ای شبیه System.IO.Stream برای std::basic_ostream و اشیای مشتق آن است. اشیای این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 27
url: /fa/system.io/basicstdostreamwrapper/
---
## کلاس BasicSTDOStreamWrapper

نمایانگر یک بسته مشابه [System.IO.Stream](../stream/) برای std::basic_ostream و اشیای مشتق آن است. اشیای این کلاس باید فقط با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص یابند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا خطاهای ادعا می‌شود. همیشه این کلاس را در یک اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید.

```cpp
template<typename T,typename>class BasicSTDOStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## متدها

| متد | توضیح |
| --- | --- |
|  [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(std::basic_ostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | یک نمونه جدید از [BasicSTDOStreamWrapper](./) را می‌سازد. |
|  [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(const [BasicSTDOStreamWrapper](./)\&) | سازنده کپی. حذف شده. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک عملیات خواندن ناهمزمان را آغاز می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک عملیات نوشتن ناهمزمان را آغاز می‌کند. |
| virtual void [Close](../stream/close/)() | جریان را می‌بندد. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | بایت‌ها را به جریان مشخص‌شده کپی می‌کند. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | بایت‌ها را به جریان مشخص‌شده با استفاده از اندازه بافر مشخص کپی می‌کند. |
| [Dispose](../stream/dispose/)() override | تمام منابع استفاده‌شده توسط شیء فعلی را آزاد می‌کند و جریان را می‌بندد. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | تا تکمیل عملیات خواندن ناهمزمان مشخص‌شده صبر می‌کند. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | عملیات نوشتن ناهمزمان را پایان می‌دهد. تا تکمیل عملیات نوشتن ناهمزمان مشخص‌شده صبر می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مرجع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN، نباشد. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| void [Flush](./flush/)() override | بافرهای این جریان را پاک می‌کند و تمام داده‌های بافرشده را به ذخیره‌سازی زیرین می‌نویسد. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به صورت ناهمزمان تمام بافرهای این جریان را پاک می‌کند، باعث می‌شود داده‌های بافرشده به دستگاه زیرین نوشته شوند و درخواست‌های لغو را نظارت می‌کند. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | به صورت ناهمزمان تمام بافرهای این جریان را پاک می‌کند، باعث می‌شود داده‌های بافرشده به دستگاه زیرین نوشته شوند و درخواست‌های لغو را نظارت می‌کند. |
| **bool** [get_CanRead](../stdiostreamwrapperbase/get_canread/)() const override | مشخص می‌کند آیا جریان از خواندن پشتیبانی می‌کند. |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | مشخص می‌کند آیا جریان از جستجو پشتیبانی می‌کند. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | مقداری را برمی‌گرداند که تعیین می‌کند آیا جریان فعلی می‌تواند زمان‌ساقط شود. |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | طول جریان را برمی‌گرداند. |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | موقعیت فعلی جریان را برمی‌گرداند. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | مقداری به میلی‌ثانیه برمی‌گرداند که تعیین می‌کند جریان تا چه مدت سعی می‌کند قبل از زمان‌سازگی بخواند. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | مقداری به میلی‌ثانیه برمی‌گرداند که تعیین می‌کند جریان تا چه مدت سعی می‌کند قبل از زمان‌سازگی بنویسد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل روش C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | اجرای قفل‌بندی عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل روش C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. همه ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن سازندهٔ کپی در زیرکلاس‌ها را فراهم می‌کند. |
| [BasicSTDOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDOStreamWrapper](./)\&) | اپراتور تخصیص کپی. حذف شده. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | اپراتور تخصیص کپی. حذف شده. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور تخصیص. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن سازندهٔ کپی در زیرکلاس‌ها را فراهم می‌کند. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | اگر حالت بسته‌بندی باینری باشد، تعداد بایت مشخص‌شده را از جریان می‌خواند، در غیر این صورت تعداد کاراکترهای مشخص‌شده را می‌خواند و به نوع **uint8_t** تبدیل می‌کند. نتیجهٔ خواندن را در آرایهٔ بایتی مشخص‌شده می‌نویسد. پشتیبانی نمی‌شود! |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | تعداد بایت‌های مشخص‌شده را از جریان می‌خواند و در آرایهٔ بایتی مشخص‌شده می‌نویسد. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | تعداد بایت‌های مشخص‌شده را از جریان می‌خواند و در آرایهٔ بایتی مشخص‌شده می‌نویسد. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | تعداد بایت‌های مشخص‌شده را از جریان می‌خواند و در بازهٔ بایتی مشخص‌شده می‌نویسد. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به صورت ناهمزمان دنباله‌ای از بایت‌ها را از جریان فعلی می‌خواند، موقعیت داخل جریان را به اندازهٔ بایت‌های خوانده شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به صورت ناهمزمان دنباله‌ای از بایت‌ها را از جریان فعلی می‌خواند، موقعیت داخل جریان را به اندازهٔ بایت‌های خوانده شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| int [ReadByte](./readbyte/)() override | اگر حالت بسته‌بندی باینری باشد، یک بایت تک از ذخیره‌ساز آخرین کاراکتر رمزگشایی شده می‌خواند، در غیر این صورت یک کاراکتر تک از جریان می‌خواند و به نوع **uint8_t** تبدیل می‌کند. پشتیبانی نمی‌شود! |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr به صورت مرجع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ مرجع مشترک را به میزان مقدار مشخص‌شده کاهش می‌دهد. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | اطلاعات RTTI. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | موقعیت جریان نمایان‌شده توسط شیء کنونی را تنظیم می‌کند. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | موقعیت جریان را تنظیم می‌کند. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | مقداری را تنظیم می‌کند که تعیین می‌کند آیا جریان فعلی می‌تواند زمان‌ساز باشد. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | مقداری به میلی‌ثانیه تنظیم می‌کند که تعیین می‌کند جریان تا چه مدت سعی می‌کند قبل از زمان‌سازگی بخواند. |
| void [SetLength](./setlength/)(**int64_t**) override | طول جریان نمایان‌شده توسط شیء کنونی را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان الگوئی nام را به یک اشاره‌گر ضعیف (به جای مشترک) تنظیم می‌کند. امکان تغییر اشاره‌گرها در مجموعه‌ها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ مرجع مشترک را کاهش داده و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | سازندهٔ کپی. حذف شده. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل روش C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | اجرای بازکردن قفل توسط عبارت lock() در C# را پیاده‌سازی می‌کند. مستقیماً فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | اگر حالت بسته‌بندی باینری باشد، محدودهٔ جزئی از بایت‌های مشخص‌شده را از آرایهٔ بایتی مشخص‌شده به جریان می‌نویسد، در غیر این صورت آن محدودهٔ جزئی را به نوع char_type تبدیل کرده و سپس نتیجه را به جریان می‌نویسد. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | محدودهٔ جزئی بایت‌های مشخص‌شده را از آرایهٔ بایتی مشخص‌شده به جریان می‌نویسد. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | محدودهٔ جزئی بایت‌های مشخص‌شده را از آرایهٔ بایتی مشخص‌شده به جریان می‌نویسد. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | محدودهٔ جزئی بایت‌های مشخص‌شده را از بازهٔ بایتی مشخص‌شده به جریان می‌نویسد. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به صورت ناهمزمان دنباله‌ای از بایت‌ها را به جریان فعلی می‌نویسد، موقعیت جاری در این جریان را به اندازهٔ بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به صورت ناهمزمان دنباله‌ای از بایت‌ها را به جریان فعلی می‌نویسد، موقعیت جاری در این جریان را به اندازهٔ بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | اگر حالت بسته‌بندی باینری باشد، مقدار عدد صحیح 8 بیتی بدون علامت مشخص‌شده را به جریان می‌نویسد، در غیر این صورت آن را به نوع char_type تبدیل کرده و سپس نتیجه را به جریان می‌نویسد. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static [Null](../stream/null/) | جریانی بدون ذخیره‌سازی زیرین. |

## تعاریف نوع

| تعریف نوع | توضیح |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## مراجع

* کلاس [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* فضای‌نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)