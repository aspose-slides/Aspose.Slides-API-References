---
title: BasicSTDIOStreamWrapper
second_title: Aspose.Slides برای C++ مرجع API
description: "نمایانگر یک wrapper شبیه System.IO.Stream برای std::basic_iostream و اشیاء مشتق‌شدهٔ آن است. اشیاء این کلاس باید فقط با استفاده از تابع System::MakeObject() تخصیص داده شوند. هرگز نمونه‌ای از این نوع را روی پشته یا با استفاده از عملگر new ایجاد نکنید، زیرا منجر به خطاهای زمان اجرا و/یا اشکالات ادعایی می‌شود. همیشه این کلاس را در یک اشاره‌گر System::SmartPtr بپیچید و از این اشاره‌گر برای عبور به عنوان آرگومان به توابع استفاده کنید."
type: docs
weight: 1
url: /fa/system.io/basicstdiostreamwrapper/
---
## کلاس BasicSTDIOStreamWrapper

Represents a [System.IO.Stream](../stream/)-like wrapper for std::basic_iostream and its derived objects. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T,typename>class BasicSTDIOStreamWrapper : public System::IO::BasicSTDIStreamWrapper<T>,
                                                             public System::IO::BasicSTDOStreamWrapper<T>
```

## متدها

| متد | توضیح |
| --- | --- |
|  [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/)(std::basic_iostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/), [STDIOStreamPositionPreference](../stdiostreampositionpreference/)) | یک نمونهٔ جدید از [BasicSTDIOStreamWrapper](./) را می‌سازد. |
|  [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/)(const [BasicSTDIOStreamWrapper](./)\&) | سازندهٔ کپی. حذف شده. |
|  [BasicSTDIStreamWrapper](../basicstdistreamwrapper/basicstdistreamwrapper/)(std::basic_istream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | یک نمونهٔ جدید از [BasicSTDIStreamWrapper](../basicstdistreamwrapper/) را می‌سازد. |
|  [BasicSTDIStreamWrapper](../basicstdistreamwrapper/basicstdistreamwrapper/)(const [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)\&) | سازندهٔ کپی. حذف شده. |
|  [BasicSTDOStreamWrapper](../basicstdostreamwrapper/basicstdostreamwrapper/)(std::basic_ostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | یک نمونهٔ جدید از [BasicSTDOStreamWrapper](../basicstdostreamwrapper/) را می‌سازد. |
|  [BasicSTDOStreamWrapper](../basicstdostreamwrapper/basicstdostreamwrapper/)(const [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)\&) | سازندهٔ کپی. حذف شده. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک عملیات خواندن ناهمگام را آغاز می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | یک عملیات نوشتن ناهمگام را آغاز می‌کند. |
| virtual void [Close](../stream/close/)() | جریان را می‌بندد. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | بایت‌ها را به جریان مشخص‌شده کپی می‌کند. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | بایت‌ها را به جریان مشخص‌شده کپی می‌کند، با استفاده از اندازهٔ بافر مشخص شده. |
| void [Dispose](../stream/dispose/)() override | تمام منابع مورد استفادهٔ شیء جاری را آزاد می‌کند و جریان را می‌بندد. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | تا تکمیل عملیات خواندن ناهمگام مشخص‌شده صبر می‌کند. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | عملیات نوشتن ناهمگام را پایان می‌دهد. تا تکمیل عملیات نوشتن ناهمگام مشخص‌شده صبر می‌کند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از معنای C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع ارجاعی را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، اگرچه بر طبق IEC 60559:1989 NaN برابر با هیچ مقداری، از جمله NaN نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای مقاصد داخلی. |
| void [Flush](./flush/)() override | بافرهای این جریان را پاک می‌کند و تمام داده‌های بافرشده را به ذخیره‌سازی زیرین می‌نویسد. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به صورت ناهمگام تمام بافرهای این جریان را پاک می‌کند، باعث می‌شود هر دادهٔ بافرشده به دستگاه زیرین نوشته شود و درخواست‌های لغو را نظارت می‌کند. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | به صورت ناهمگام تمام بافرهای این جریان را پاک می‌کند، باعث می‌شود هر دادهٔ بافرشده به دستگاه زیرین نوشته شود و درخواست‌های لغو را نظارت می‌کند. |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | تشخیص می‌دهد آیا جریان از جستجو پشتیبانی می‌کند. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | مقداری را برمی‌گرداند که تعیین می‌کند آیا جریان جاری می‌تواند زمان‌سنجی شود. |
| **bool** [get_CanWrite](../stdiostreamwrapperbase/get_canwrite/)() const override | تشخیص می‌دهد آیا جریان از نوشتن پشتیبانی می‌کند. |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | طول جریان را برمی‌گرداند. |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | موقعیت فعلی جریان را برمی‌گرداند. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | مقداری را برمی‌گرداند، بر حسب میلی‌ثانیه، که تعیین می‌کند جریان تا چه مدت سعی می‌کند بخواند قبل از زمان‌سنجی. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | مقداری را برمی‌گرداند، بر حسب میلی‌ثانیه، که تعیین می‌کند جریان تا چه مدت سعی می‌کند بنویسد قبل از زمان‌سنجی. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ ارجاع مرتبط با شیء را برمی‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شیء را برمی‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شیء نمایانگر یک نمونه از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان lock() در C# را پیاده‌سازی می‌کند. به‌طور مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌سازی انواع سفارشی را فراهم می‌کند. |
|  [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای دادهٔ داخلی را مقداردهی اولیه می‌کند. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [BasicSTDIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDIOStreamWrapper](./)\&) | اپراتور انتساب کپی. حذف شده. |
| [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)\& [operator=](../basicstdistreamwrapper/operator_equal/)(const [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)\&) | اپراتور انتساب کپی. حذف شده. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | اپراتور انتساب کپی. حذف شده. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | اپراتور انتساب. در واقع هیچ چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی اولیه می‌کند و امکان ساخت کپی برای زیرکلاس‌ها را فراهم می‌کند. |
| [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)\& [operator=](../basicstdostreamwrapper/operator_equal/)(const [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)\&) | اپراتور انتساب کپی. حذف شده. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | اگر حالت بسته‌بندی باینری باشد، تعداد بایت‌های مشخص‌شده را از جریان می‌خواند، در غیر این صورت تعداد کاراکترهای مشخص‌شده را می‌خواند و به نوع **uint8_t** تبدیل می‌کند. نتیجه خواندن را در آرایه بایت مشخص شده می‌نویسد. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | تعداد بایت‌های مشخص‌شده را از جریان می‌خواند و در آرایه بایت مشخص‌شده می‌نویسد. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | تعداد بایت‌های مشخص‌شده را از جریان می‌خواند و در آرایه بایت مشخص‌شده می‌نویسد. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | تعداد بایت‌های مشخص‌شده را از جریان می‌خواند و در بازه بایت (span) مشخص‌شده می‌نویسد. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به صورت ناهمگام توالی بایت‌ها را از جریان جاری می‌خواند، موقعیت در جریان را به اندازهٔ بایت‌های خوانده‌شده جلو می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به صورت ناهمگام توالی بایت‌ها را از جریان جاری می‌خواند، موقعیت در جریان را به اندازهٔ بایت‌های خوانده‌شده جلو می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| int [ReadByte](./readbyte/)() override | اگر حالت بسته‌بندی باینری باشد، یک بایت واحد را از ذخیره‌ساز آخرین کاراکتر کشف‌شده می‌خواند، در غیر این صورت یک کاراکتر واحد را از جریان می‌خواند و به نوع **uint8_t** تبدیل می‌کند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر حسب ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر حسب ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | شیء نوع مقدار را با nullptr از نظر ارجاع مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ ارجاع مشترک را به اندازهٔ مقدار مشخص‌شده کاهش می‌دهد. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | اطلاعات RTTI. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | موقعیت جریان را که توسط شیء جاری نمایانده می‌شود، تنظیم می‌کند. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | موقعیت جریان را تنظیم می‌کند. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | مقداری را تنظیم می‌کند که تعیین می‌کند آیا جریان جاری می‌تواند زمان‌سنجی شود. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | مقداری را بر حسب میلی‌ثانیه تنظیم می‌کند که تعیین می‌کند جریان تا چه مدت سعی می‌کند بخواند قبل از زمان‌سنجی. |
| void [SetLength](./setlength/)(**int64_t**) override | طول جریان را که توسط شیء جاری نمایانده می‌شود، تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام قالب را به یک اشاره‌گر ضعیف (به جای اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را فراهم می‌کند. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را برمی‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش می‌دهد و برمی‌گرداند. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | سازندهٔ کپی. حذف شده. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌گذاری معکوس بیان lock() در C# را پیاده‌سازی می‌کند. به‌صورت مستقیم فراخوانی شود یا از شیء نگهبان [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید مستقیماً فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده کنید. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | اگر حالت بسته‌بندی باینری باشد، زیرمحدودهٔ بایت‌های مشخص‌شده از آرایه بایت مشخص‌شده را به جریان می‌نویسد، در غیر این صورت زیرمحدودهٔ بایت‌های مشخص‌شده را به نوع char_type تبدیل می‌کند و سپس نتیجه را به جریان می‌نویسد. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | زیرمحدودهٔ بایت‌های مشخص‌شده از آرایه بایت مشخص‌شده را به جریان می‌نویسد. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | زیرمحدودهٔ بایت‌های مشخص‌شده از آرایه بایت مشخص‌شده را به جریان می‌نویسد. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | زیرمحدودهٔ بایت‌های مشخص‌شده از بازه بایت (span) مشخص‌شده را به جریان می‌نویسد. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به صورت ناهمگام توالی بایت‌ها را به جریان جاری می‌نویسد، موقعیت فعلی در این جریان را به اندازهٔ بایت‌های نوشته‌شده جلو می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به صورت ناهمگام توالی بایت‌ها را به جریان جاری می‌نویسد، موقعیت فعلی در این جریان را به اندازهٔ بایت‌های نوشته‌شده جلو می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | اگر حالت بسته‌بندی باینری باشد، مقدار عدد صحیح بدون علامت 8-بیتی مشخص‌شده را به جریان می‌نویسد، در غیر این صورت آن را به نوع char_type تبدیل کرده و سپس نتیجه را به جریان می‌نویسد. |
| virtual  [~Object](../../system/object/~object/)() | شیء را نابود می‌کند. تمام ساختارهای دادهٔ داخلی را آزاد می‌سازد. |

## فیلدها

| فیلد | توضیح |
| --- | --- |
| static [Null](../stream/null/) | جریانی بدون ذخیره‌سازی زیرین. |

## تعاریف‌نوع

| تعریف‌نوع | توضیح |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [BaseIType](./baseitype/) |  |
| [BaseOType](./baseotype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## همچنین ببینید

* کلاس [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)
* کلاس [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)
* فضای‌نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)