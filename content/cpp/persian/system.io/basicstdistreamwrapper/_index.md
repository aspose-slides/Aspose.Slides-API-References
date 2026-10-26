---
title: BasicSTDIStreamWrapper
second_title: Aspose.Slides برای مرجع API زبان C++
description: "نمایانگر یک wrapper شبیه System.IO.Stream برای std::basic_istream و اشیاء مشتق‌شده آن است. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را بر روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا شکست‌های ادعا می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای انتقال به توابع به عنوان آرگومان استفاده کنید."
type: docs
weight: 14
url: /fa/system.io/basicstdistreamwrapper/
---
## BasicSTDIStreamWrapper کلاس

نمایانگر یک wrapper شبیه [System.IO.Stream](../stream/) برای std::basic_istream و اشیاء مشتق‌شده آن است. اشیاء این کلاس باید تنها با استفاده از تابع [System::MakeObject()](../../system/makeobject/) تخصیص داده شوند. هرگز نمونه‌ای از این نوع را بر روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان‌اجرای و/یا شکست‌های ادعا می‌شود. همیشه این کلاس را در اشاره‌گر [System::SmartPtr](../../system/smartptr/) بپیچید و از این اشاره‌گر برای ارسال به توابع به عنوان آرگومان استفاده کنید.
```cpp
template<typename T,typename>class BasicSTDIStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## متدها

| متد | توضیح |
| --- | --- |
|  [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(std::basic_istream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | یک نمونه جدید از [BasicSTDIStreamWrapper](./) را ایجاد می‌کند. |
|  [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(const [BasicSTDIStreamWrapper](./)\&) | سازنده کپی. حذف شد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک عملیات خواندن ناهمزمان را آغاز می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک عملیات نوشتن ناهمزمان را آغاز می‌کند. تا تکمیل عملیات نوشتن ناهمزمان مشخص شده صبر می‌کند. |
| virtual void [Close](../stream/close/)() | جریان را می‌بندد. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | بایت‌ها را به جریان تعیین‌شده کپی می‌کند. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | بایت‌ها را به جریان تعیین‌شده با استفاده از اندازه بافر مشخص شده کپی می‌کند. |
| void [Dispose](../stream/dispose/)() override | تمام منابع استفاده‌شده توسط شیء فعلی را آزاد می‌کند و جریان را می‌بندد. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | تا تکمیل عملیات خواندن ناهمزمان مشخص شده صبر می‌کند. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | یک عملیات نوشتن ناهمزمان را پایان می‌دهد. تا تکمیل عملیات نوشتن ناهمزمان مشخص شده صبر می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای [Object.Equals](../../system/object/equals/) در C# مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسه نقطه‌ی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند، حتی اگر بر اساس IEC 60559:1989 NaN برابر هیچ مقداری، از جمله NaN، نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطه‌ی شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN به‌عنوان برابر در نظر گرفته می‌شوند، حتی اگر طبق IEC 60559:1989 NaN برابر هیچ مقدار، از جمله NaN، نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| void [Flush](./flush/)() override | حافظه‌سازهای این جریان را پاک می‌کند و تمام داده‌های بافرشده را به ذخیره‌سازی زیرین می‌نویسد. پشتیبانی نمی‌شود! |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به‌صورت ناهمزمان تمام بافرهای این جریان را پاک می‌کند، باعث می‌شود هر داده‌ی بافرشده‌ای به دستگاه زیرین نوشته شود و درخواست‌های لغو را مانیتور می‌کند. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | به‌صورت ناهمزمان تمام بافرهای این جریان را پاک می‌کند، باعث می‌شود هر داده‌ی بافرشده‌ای به دستگاه زیرین نوشته شود و درخواست‌های لغو را مانیتور می‌کند. |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | مشخص می‌کند آیا جریان از جستجو پشتیبانی می‌کند. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | مقداری که تعیین می‌کند آیا جریان فعلی می‌تواند زمان‌سنجی شود را برمی‌گرداند. |
| **bool** [get_CanWrite](../stdiostreamwrapperbase/get_canwrite/)() const override | مشخص می‌کند آیا جریان از نوشتن پشتیبانی می‌کند. |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | طول جریان را برمی‌گرداند. |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | موقعیت فعلی جریان را برمی‌گرداند. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | مقداری به میلی‌ثانیه که تعیین می‌کند جریان چه مدت سعی می‌کند بخواند قبل از زمان‌سنجی را برمی‌گرداند. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | مقداری به میلی‌ثانیه که تعیین می‌کند جریان چه مدت سعی می‌کند بنویسد قبل از زمان‌سنجی را برمی‌گرداند. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار داده‌ی شمارنده‌ی مرجع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | مطابق متد [Object.GetHashCode()](../../system/object/gethashcode/) در C#. امکان هش کردن اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی [System.Object.GetType()](../../system/object/gettype/) در C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر 'is' در C#. |
| void [Lock](../../system/object/lock/)() | اجرا کننده قفل‌گذاری با عبارت lock() در C#. به‌طور مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد [Object.MemberwiseClone()](../../system/object/memberwiseclone/) در C#. امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازنده کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها از طریق کپی را فراهم می‌کند. |
| [BasicSTDIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDIStreamWrapper](./)\&) | عملگر انتساب کپی. حذف شد. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | عملگر انتساب کپی. حذف شد. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساختن زیرکلاس‌ها از طریق کپی را فراهم می‌کند. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | اگر حالت بسته‌بندی باینری باشد، تعداد بایت مشخص‌شده را از جریان می‌خواند، در غیر این صورت تعداد کاراکترهای مشخص‌شده را می‌خواند و به نوع **uint8_t** تبدیل می‌کند. نتیجهٔ خواندن را در آرایه بایت مشخص‌شده می‌نویسد. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | تعداد بایت مشخص‌شده را از جریان می‌خواند و در آرایه بایت مشخص‌شده می‌نویسد. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | تعداد بایت مشخص‌شده را از جریان می‌خواند و در آرایه بایت مشخص‌شده می‌نویسد. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | تعداد بایت مشخص‌شده را از جریان می‌خواند و در بازهٔ بایت مشخص‌شده می‌نویسد. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به‌صورت ناهمزمان دنباله‌ای از بایت‌ها را از جریان فعلی می‌خواند، موقعیت درون جریان را به میزان بایت‌های خوانده‌شده پیش می‌برد و درخواست‌های لغو را مانیتور می‌کند. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به‌صورت ناهمزمان دنباله‌ای از بایت‌ها را از جریان فعلی می‌خواند، موقعیت درون جریان را به میزان بایت‌های خوانده‌شده پیش می‌برد و درخواست‌های لغو را مانیتور می‌کند. |
| int [ReadByte](./readbyte/)() override | اگر حالت بسته‌بندی باینری باشد، یک بایت واحد را از ذخیره‌سازی آخرین کاراکتر رمزگشایی‌شده می‌خواند، در غیر این صورت یک کاراکتر واحد را از جریان می‌خواند و به نوع **uint8_t** تبدیل می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس مرجع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | مقایسه مرجع با شیء نوع مقدار نسبت به nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصیص خاص [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | شمارنده مرجع مشترک را به مقدار مشخص‌شده کاهش می‌دهد. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | اطلاعات RTTI. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | موقعیت جریان نمایان‌شده توسط شیء فعلی را تنظیم می‌کند. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | موقعیت جریان را تنظیم می‌کند. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | مقداری که تعیین می‌کند آیا جریان فعلی می‌تواند زمان‌سنجی شود را تنظیم می‌کند. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | مقداری به میلی‌ثانیه که تعیین می‌کند جریان چه مدت سعی می‌کند بخواند قبل از زمان‌سنجی را تنظیم می‌کند. |
| void [SetLength](./setlength/)(**int64_t**) override | طول جریان نمایان‌شده توسط شیء فعلی را تنظیم می‌کند. پشتیبانی نمی‌شود! |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به‌جای shared) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌آورد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارنده مرجع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارنده مرجع مشترک را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارنده مرجع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | سازنده کپی. حذف شد. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد [Object.ToString()](../../system/object/tostring/) در C#. امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | پیاده‌سازی ساختار typeof([System.Object](../../system/object/)) در C#. |
| void [Unlock](../../system/object/unlock/)() | اجرا کننده باز کردن قفل با عبارت lock() در C#. به‌طور مستقیم فراخوانی کنید یا از شیء مراقب [LockContext](../../system/lockcontext/) استفاده کنید. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارنده مرجع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارنده مرجع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ در عوض، از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | اگر حالت بسته‌بندی باینری باشد، محدوده‌ی زیرمجموعه‌ی بایت‌های مشخص‌شده از آرایه بایت را به جریان می‌نویسد، در غیر این صورت محدوده‌ی زیرمجموعه‌ی بایت‌ها را به نوع char_type تبدیل کرده و نتیجه را به جریان می‌نویسد. پشتیبانی نمی‌شود! |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | محدوده‌ی زیرمجموعه‌ی بایت‌های مشخص‌شده از آرایه بایت را به جریان می‌نویسد. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | محدوده‌ی زیرمجموعه‌ی بایت‌های مشخص‌شده از آرایه بایت را به جریان می‌نویسد. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | محدوده‌ی زیرمجموعه‌ی بایت‌های مشخص‌شده از بازه بایت را به جریان می‌نویسد. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به‌صورت ناهمزمان دنباله‌ای از بایت‌ها را به جریان فعلی می‌نویسد، موقعیت فعلی در این جریان را به میزان بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را مانیتور می‌کند. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به‌صورت ناهمزمان دنباله‌ای از بایت‌ها را به جریان فعلی می‌نویسد، موقعیت فعلی در این جریان را به میزان بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را مانیتور می‌کند. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | اگر حالت بسته‌بندی باینری باشد، مقدار 8 بیتی بدون علامت مشخص‌شده را به جریان می‌نویسد، در غیر این صورت آن را به نوع char_type تبدیل کرده و سپس نتیجه را به جریان می‌نویسد. پشتیبانی نمی‌شود! |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static [Null](../stream/null/) | جریانی بدون ذخیره‌سازی زیرین. |

## تعاریف‌نوع

| تعریف‌نوع | توضیح |
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