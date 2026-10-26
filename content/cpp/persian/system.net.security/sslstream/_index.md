---
title: SslStream
second_title: Aspose.Slides برای C++ مرجع API
description: یک جریان که از پروتکل SSL برای احراز هویت سرور و به‌صورت اختیاری کلاینت استفاده می‌کند.
type: docs
weight: 14
url: /fa/system.net.security/sslstream/
---
## SslStream کلاس


یک جریان که از پروتکل SSL برای احراز هویت سرور و به‌صورت اختیاری کلاینت استفاده می‌کند.

```cpp
class SslStream : public System::Net::Security::AuthenticatedStream
```

## متدها

| Method | Description |
| --- | --- |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/)) | احراز هویت سمت کلاینت اتصال. |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>, [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/), **bool**) | احراز هویت سمت کلاینت اتصال. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | عملیات خواندن ناهمزمان را آغاز می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | عملیات خواندن ناهمزمان را آغاز می‌کند. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | عملیات نوشتن ناهمزمان را آغاز می‌کند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | عملیات نوشتن ناهمزمان را آغاز می‌کند. |
| void [Close](./close/)() override | جریان را می‌بندد. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | بایت‌ها را به جریان مشخص‌شده کپی می‌کند. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | بایت‌ها را به جریان مشخص‌شده کپی می‌کند، با استفاده از اندازهٔ بافر مشخص‌شده. |
| void [Dispose](./dispose/)(**bool**) override | تمام منابع مورد استفادهٔ شی جاری را آزاد می‌کند و جریان را می‌بندد. |
| void [Dispose](../../system.io/stream/dispose/)() override | تمام منابع مورد استفادهٔ شی جاری را آزاد می‌کند و جریان را می‌بندد. |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | تا تکمیل عملیات خواندن ناهمزمان مشخص‌شده منتظر می‌ماند. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | تا تکمیل عملیات خواندن ناهمزمان مشخص‌شده منتظر می‌ماند. |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | عملیات نوشتن ناهمزمان را پایان می‌دهد. تا تکمیل عملیات نوشتن ناهمزمان مشخص‌شده منتظر می‌ماند. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | عملیات نوشتن ناهمزمان را پایان می‌دهد. تا تکمیل عملیات نوشتن ناهمزمان مشخص‌شده منتظر می‌ماند. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | اشیاء را با استفاده از قواعد C# [Object.Equals](../../system/object/equals/) مقایسه می‌کند. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع ارجاع را به سبک C# مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | اشیاء از نوع مقدار را به سبک C# مقایسه می‌کند. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | مقایسهٔ نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | مقایسهٔ نقطهٔ شناور به سبک C# را شبیه‌سازی می‌کند که در آن دو NaN برابر در نظر گرفته می‌شوند، هرچند طبق IEC 60559:1989 NaN با هیچ مقداری، از جمله NaN، برابر نیست. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | فقط برای استفاده داخلی. |
| void [Flush](./flush/)() override | بافرهای این جریان را پاک می‌کند و تمام داده‌های بافرشده را به ذخیره‌سازی پایه می‌نویسد. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به صورت ناهمزمان تمام بافرهای این جریان را پاک می‌کند، باعث نوشتن داده‌های بافرشده به دستگاه پایه می‌شود و درخواست‌های لغو را نظارت می‌کند. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | به صورت ناهمزمان تمام بافرهای این جریان را پاک می‌کند، باعث نوشتن داده‌های بافرشده به دستگاه پایه می‌شود و درخواست‌های لغو را نظارت می‌کند. |
| **bool** [get_CanRead](./get_canread/)() const override | مشخص می‌کند آیا جریان قابل خواندن است. |
| **bool** [get_CanSeek](./get_canseek/)() const override | مشخص می‌کند آیا جریان از جستجو پشتیبانی می‌کند. |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | مقداری را بر می‌گرداند که تعیین می‌کند آیا جریان جاری می‌تواند زمان‌سرب شود. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | مشخص می‌کند آیا جریان قابل نوشتن است. |
| virtual **bool** [get_CheckCertRevocationStatus](./get_checkcertrevocationstatus/)() | مقداری را بر می‌گرداند که نشان می‌دهد آیا فهرست ابطال گواهی در طول فرآیند اعتبارسنجی گواهی بررسی می‌شود. |
| virtual [System::Security::Authentication::CipherAlgorithmType](../../system.security.authentication/cipheralgorithmtype/) [get_CipherAlgorithm](./get_cipheralgorithm/)() | الگوریتم رمزنگاری را بر می‌گرداند. |
| virtual **int32_t** [get_CipherStrength](./get_cipherstrength/)() | قدرت الگوریتم رمزنگاری استفاده‌شده را بر می‌گرداند. |
| virtual [System::Security::Authentication::HashAlgorithmType](../../system.security.authentication/hashalgorithmtype/) [get_HashAlgorithm](./get_hashalgorithm/)() | الگوریتم هش را بر می‌گرداند. |
| virtual **int32_t** [get_HashStrength](./get_hashstrength/)() | قدرت الگوریتم هش استفاده‌شده را بر می‌گرداند. |
| **bool** [get_IsAuthenticated](./get_isauthenticated/)() const override | مقداری را بر می‌گرداند که نشان می‌دهد آیا احراز هویت با موفقیت انجام شده است. |
| **bool** [get_IsEncrypted](./get_isencrypted/)() const override | مقداری را بر می‌گرداند که نشان می‌دهد آیا داده‌های ارسال‌شده با این جریان رمزنگاری شده‌اند. |
| **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const override | مقداری را بر می‌گرداند که نشان می‌دهد آیا سرور و کلاینت احراز هویت شده‌اند. |
| **bool** [get_IsServer](./get_isserver/)() const override | مقداری را بر می‌گرداند که نشان می‌دهد آیا سمت محلی اتصال، سرور است. |
| **bool** [get_IsSigned](./get_issigned/)() const override | مقداری را بر می‌گرداند که نشان می‌دهد آیا داده‌های ارسال‌شده با این جریان امضا شده‌اند. |
| virtual **int32_t** [get_KeyExchangeStrength](./get_keyexchangestrength/)() | قدرت الگوریتم تبادل کلید استفاده‌شده را بر می‌گرداند. |
| **bool** [get_LeaveInnerStreamOpen](../authenticatedstream/get_leaveinnerstreamopen/)() const | جریانی را که نمونه‌های کلاس جاری برای ارسال و دریافت داده استفاده می‌کنند بر می‌گرداند. |
| **int64_t** [get_Length](./get_length/)() const override | طول جریان بر حسب بایت را بر می‌گرداند. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_LocalCertificate](./get_localcertificate/)() | گواهی‌ای که برای احراز هویت نقطهٔ انتهایی محلی استفاده می‌شود را بر می‌گرداند. |
| **int64_t** [get_Position](./get_position/)() const override | موقعیت جاری جریان را بر می‌گرداند. |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | مقداری به میلی‌ثانیه بر می‌گرداند که تعیین می‌کند جریان چه مدت سعی در خواندن قبل از زمان‌سرب شدن خواهد کرد. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_RemoteCertificate](./get_remotecertificate/)() | گواهی‌ای که برای احراز هویت نقطهٔ انتهایی دور استفاده می‌شود را بر می‌گرداند. |
| virtual [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/) [get_SslProtocol](./get_sslprotocol/)() | پروتکل SSL را بر می‌گرداند. |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | مقداری به میلی‌ثانیه بر می‌گرداند که تعیین می‌کند جریان چه مدت سعی در نوشتن قبل از زمان‌سرب شدن خواهد کرد. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ساختار دادهٔ شمارندهٔ مرجع مرتبط با شی را بر می‌گرداند. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | معادل متد C# [Object.GetHashCode()](../../system/object/gethashcode/). امکان هش‌گذاری اشیاء سفارشی را فراهم می‌کند. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | نوع واقعی شی را بر می‌گرداند. معادل فراخوانی C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | بررسی می‌کند آیا شی نمونه‌ای از نوع توصیف‌شده توسط targetType است. معادل عملگر C# 'is'. |
| void [Lock](../../system/object/lock/)() | قفل‌گذاری بیان C# lock() را پیاده‌سازی می‌کند. مستقیم فراخوانی شود یا از شیء مراقبت [LockContext](../../system/lockcontext/) استفاده شود. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | معادل متد C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). امکان کلون‌کردن انواع سفارشی را فراهم می‌کند. |
| [Object](../../system/object/object/)() | شیء را ایجاد می‌کند. تمام ساختارهای داده داخلی را مقداردهی اولیه می‌کند. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | سازندهٔ کپی. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای کلاس‌های مشتق را فراهم می‌کند. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عملگر انتساب. واقعاً چیزی را کپی نمی‌کند، فقط شیء جدید را مقداردهی می‌کند و امکان ساخت کپی برای کلاس‌های مشتق را فراهم می‌کند. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | تعداد بایت مشخص‌شده را از جریان می‌خواند و در آرایه بایتی مشخص می‌نویسد. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | تعداد بایت مشخص‌شده را از جریان می‌خواند و در آرایه بایتی مشخص می‌نویسد. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | تعداد بایت مشخص‌شده را از جریان می‌خواند و در آرایه بایتی مشخص می‌نویسد. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | تعداد بایت مشخص‌شده را از جریان می‌خواند و در بازهٔ بایتی مشخص می‌نویسد. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به‌صورت ناهمزمان دنباله‌ای از بایت‌ها را از جریان فعلی می‌خواند، موقعیت در جریان را به اندازهٔ بایت‌های خوانده‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به‌صورت ناهمزمان دنباله‌ای از بایت‌ها را از جریان فعلی می‌خواند، موقعیت در جریان را به اندازهٔ بایت‌های خوانده‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | یک بایت واحد از جریان می‌خواند و مقدار عدد صحیح ۳۲ بیتی معادل مقدار بایت خوانده‌شده را بر می‌گرداند. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | اشیاء را بر اساس ارجاع مقایسه می‌کند. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | اشیاء نوع مقدار را با nullptr به‌صورت ارجاعی مقایسه می‌کند. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصصی از [Object::ReferenceEquals](../../system/object/referenceequals/) برای حالت رشته‌ها. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | تعداد شمارندهٔ ارجاع مشترک را برحسب مقدار مشخص‌شده کاهش می‌دهد. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | موقعیت جریانی که توسط شی جاری نمایان شده است را تنظیم می‌کند. |
| void [set_Position](./set_position/)(**int64_t**) override | موقعیت جریان را تنظیم می‌کند. |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | مقداری را تنظیم می‌کند که تعیین می‌کند آیا جریان جاری می‌تواند زمان‌سرب شود. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | مقداری را تنظیم می‌کند که تعیین می‌کند آیا جریان جاری می‌تواند زمان‌سرب شود. |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | مقداری به میلی‌ثانیه تنظیم می‌کند که تعیین می‌کند جریان چه مدت سعی در خواندن قبل از زمان‌سرب شدن خواهد کرد. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | مقداری به میلی‌ثانیه تنظیم می‌کند که تعیین می‌کند جریان چه مدت سعی در خواندن قبل از زمان‌سرب شدن خواهد کرد. |
| void [SetLength](./setlength/)(**int64_t**) override | طول جریانی که توسط شی جاری نمایان شده است را تنظیم می‌کند. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | آرگومان nام تمپلیت را به یک اشاره‌گر ضعیف (نه اشتراکی) تنظیم می‌کند. امکان تغییر اشاره‌گرها در کانتینرها به حالت ضعیف را می‌دهد. |
| int [SharedCount](../../system/object/sharedcount/)() const | مقدار فعلی شمارندهٔ ارجاع مشترک را بر می‌گرداند. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | شمارندهٔ ارجاع مشترک را افزایش می‌دهد. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده شود. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | شمارندهٔ ارجاع مشترک را کاهش می‌دهد و بر می‌گرداند. نباید به‌طور مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده شود. |
| [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | یک نمونهٔ جدید می‌سازد. |
| [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**) | یک نمونهٔ جدید می‌سازد. |
| [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/)) | یک نمونهٔ جدید می‌سازد. |
| [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/)) | یک نمونهٔ جدید می‌سازد. |
| [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/), [EncryptionPolicy](../encryptionpolicy/)) | یک نمونهٔ جدید می‌سازد. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | معادل متد C# [Object.ToString()](../../system/object/tostring/). امکان تبدیل اشیاء سفارشی به رشته را فراهم می‌کند. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ساختار typeof([System.Object](../../system/object/)) در C# را پیاده‌سازی می‌کند. |
| void [Unlock](../../system/object/unlock/)() | قفل‌برداری بیان C# lock() را پیاده‌سازی می‌کند. مستقیم فراخوانی شود یا از شیء مراقبت [LockContext](../../system/lockcontext/) استفاده شود. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | شمارندهٔ ارجاع ضعیف را افزایش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده شود. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | شمارندهٔ ارجاع ضعیف را کاهش می‌دهد. نباید به‌صورت مستقیم فراخوانی شود؛ به‌جای آن از اشاره‌گرهای هوشمند یا ThisProtector استفاده شود. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | آرایه بایتی مشخص‌شده را به جریان می‌نویسد. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | بخش مشخص‌شده‌ای از بایت‌ها را از آرایه بایتی مشخص به جریان می‌نویسد. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&) | آرایه بایتی مشخص‌شده را به جریان می‌نویسد. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | بخش مشخص‌شده‌ای از بایت‌ها را از آرایه بایتی مشخص به جریان می‌نویسد. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | بخش مشخص‌شده‌ای از بایت‌ها را از آرایه بایتی مشخص به جریان می‌نویسد. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | بخش مشخص‌شده‌ای از بایت‌ها را از بازهٔ بایتی مشخص به جریان می‌نویسد. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | به‌صورت ناهمزمان دنباله‌ای از بایت‌ها را به جریان فعلی می‌نویسد، موقعیت جاری در این جریان را به اندازهٔ بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | به‌صورت ناهمزمان دنباله‌ای از بایت‌ها را به جریان فعلی می‌نویسد، موقعیت جاری در این جریان را به اندازهٔ بایت‌های نوشته‌شده پیش می‌برد و درخواست‌های لغو را نظارت می‌کند. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | مقدار عدد صحیح بدون علامت ۸ بیتی مشخص‌شده را به جریان می‌نویسد. |
| virtual  [~Object](../../system/object/~object/)() | شیء را از بین می‌برد. تمام ساختارهای داده داخلی را آزاد می‌کند. |

## فیلدها

| فیلد | Description |
| --- | --- |
| static [Null](../../system.io/stream/null/) | جریانی بدون ذخیره‌سازی زیرین. |

## تعاریف‌نوع

| تعریف‌نوع | Description |
| --- | --- |
| [AsyncResultType](./asyncresulttype/) | نوع AsyncResultType. |
| [StreamImplementationPtr](./streamimplementationptr/) | نوع اشاره‌گر به پیاده‌سازی. |

## موارد مرتبط

* کلاس [AuthenticatedStream](../authenticatedstream/)
* فضای نام [System::Net::Security](../)
* کتابخانه [Aspose.Slides](../../)