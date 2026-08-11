---
title: SslStream
second_title: مرجع واجهة برمجة التطبيقات لـ Aspose.Slides للغة C++
description: دفق يستخدم بروتوكول SSL لمصادقة الخادم واختياريًا العميل.
type: docs
weight: 14
url: /ar/system.net.security/sslstream/
---
## SslStream فئة

دفق يستخدم بروتوكول SSL لمصادقة الخادم واختياريًا العميل.

```cpp
class SslStream : public System::Net::Security::AuthenticatedStream
```

## الطرق

| طريقة | الوصف |
| --- | --- |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/)) | يقوم بمصادقة جانب العميل من الاتصال. |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>, [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/), **bool**) | يقوم بمصادقة جانب العميل من الاتصال. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يبدأ عملية قراءة غير متزامنة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | يبدأ عملية قراءة غير متزامنة. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | يبدأ عملية كتابة غير متزامنة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | يبدأ عملية كتابة غير متزامنة. |
| void [Close](./close/)() override | يغلق الدفق. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | ينسخ البايتات إلى الدفق المحدد. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | ينسخ البايتات إلى الدفق المحدد، باستخدام حجم المخزن المؤقت المحدد. |
| void [Dispose](./dispose/)(**bool**) override | يطلق جميع الموارد المستخدمة من قبل الكائن الحالي ويغلق الدفق. |
| void [Dispose](../../system.io/stream/dispose/)() override | يطلق جميع الموارد المستخدمة من قبل الكائن الحالي ويغلق الدفق. |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | ينتظر حتى تكتمل عملية القراءة غير المتزامنة المحددة. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | ينتظر حتى تكتمل عملية القراءة غير المتزامنة المحددة. |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | ينهي عملية كتابة غير متزامنة. ينتظر حتى تكتمل عملية الكتابة غير المتزامنة المحددة. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | ينهي عملية كتابة غير متزامنة. ينتظر حتى تكتمل عملية الكتابة غير المتزامنة المحددة. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | يقارن الكائنات باستخدام قواعد C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع المرجعي بأسلوب C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | يقارن كائنات النوع القيمي بأسلوب C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان مساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | يحاكي مقارنة النقطة العائمة بأسلوب C# حيث يُعتبر NaNانان مساويين بالرغم من أن معيار IEC 60559:1989 يحدد أن NaN غير مساوي لأي قيمة، بما في ذلك NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | لأغراض داخلية فقط. |
| void [Flush](./flush/)() override | يمسح مخازن هذا الدفق ويكتب جميع البيانات المخزنة مؤقتًا إلى التخزين الأساسي. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يمسح بشكل غير متزامن جميع المخازن لهذا الدفق، ويؤدي إلى كتابة أي بيانات مخزنة مؤقتًا إلى الجهاز الأساسي، ويراقب طلبات الإلغاء. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | يمسح بشكل غير متزامن جميع المخازن لهذا الدفق، ويؤدي إلى كتابة أي بيانات مخزنة مؤقتًا إلى الجهاز الأساسي، ويراقب طلبات الإلغاء. |
| **bool** [get_CanRead](./get_canread/)() const override | يحدد ما إذا كان الدفق قابلًا للقراءة. |
| **bool** [get_CanSeek](./get_canseek/)() const override | يحدد ما إذا كان الدفق يدعم السعي. |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | يحصل على قيمة تحدد ما إذا كان الدفق الحالي يمكن أن ينتهي مهله. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | يحدد ما إذا كان الدفق قابلًا للكتابة. |
| virtual **bool** [get_CheckCertRevocationStatus](./get_checkcertrevocationstatus/)() | يرجع قيمة تشير إلى ما إذا تم فحص قائمة إلغاء شهادة خلال عملية التحقق من صحة الشهادة. |
| virtual [System::Security::Authentication::CipherAlgorithmType](../../system.security.authentication/cipheralgorithmtype/) [get_CipherAlgorithm](./get_cipheralgorithm/)() | يرجع خوارزمية التشفير. |
| virtual **int32_t** [get_CipherStrength](./get_cipherstrength/)() | يرجع قوة خوارزمية التشفير المستخدمة. |
| virtual [System::Security::Authentication::HashAlgorithmType](../../system.security.authentication/hashalgorithmtype/) [get_HashAlgorithm](./get_hashalgorithm/)() | يرجع خوارزمية التجزئة. |
| virtual **int32_t** [get_HashStrength](./get_hashstrength/)() | يرجع قوة خوارزمية التجزئة المستخدمة. |
| **bool** [get_IsAuthenticated](./get_isauthenticated/)() const override | يرجع قيمة تشير إلى ما إذا تم تمرير المصادقة بنجاح. |
| **bool** [get_IsEncrypted](./get_isencrypted/)() const override | يرجع قيمة تشير إلى ما إذا كان البيانات المرسلة باستخدام هذا الدفق مشفرة. |
| **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const override | يرجع قيمة تشير إلى ما إذا تم مصادقة الخادم والعميل. |
| **bool** [get_IsServer](./get_isserver/)() const override | يرجع قيمة تشير إلى ما إذا كان الجانب المحلي للاتصال هو الخادم. |
| **bool** [get_IsSigned](./get_issigned/)() const override | يرجع قيمة تشير إلى ما إذا كانت البيانات المرسلة باستخدام هذا الدفق موقعة. |
| virtual **int32_t** [get_KeyExchangeStrength](./get_keyexchangestrength/)() | يرجع قوة خوارزمية تبادل المفاتيح المستخدمة. |
| **bool** [get_LeaveInnerStreamOpen](../authenticatedstream/get_leaveinnerstreamopen/)() const | يرجع الدفق الذي يستخدمه كائنات الفئة الحالية لإرسال واستقبال البيانات. |
| **int64_t** [get_Length](./get_length/)() const override | يرجع طول الدفق بالبايتات. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_LocalCertificate](./get_localcertificate/)() | يرجع الشهادة المستخدمة لمصادقة الطرف المحلي. |
| **int64_t** [get_Position](./get_position/)() const override | يرجع الموضع الحالي للدفق. |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | يحصل على قيمة بالمليثانية تحدد مدة محاولة الدفق للقراءة قبل انتهاء المهلة. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_RemoteCertificate](./get_remotecertificate/)() | يرجع الشهادة المستخدمة لمصادقة الطرف البعيد. |
| virtual [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/) [get_SslProtocol](./get_sslprotocol/)() | يرجع بروتوكول SSL. |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | يحصل على قيمة بالمليثانية تحدد مدة محاولة الدفق للكتابة قبل انتهاء المهلة. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | يحصل على هيكل بيانات عداد المرجع المرتبط بالكائن. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | نظير طريقة C# [Object.GetHashCode()](../../system/object/gethashcode/). يتيح تجزئة الكائنات المخصصة. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | يحصل على النوع الفعلي للكائن. نظير استدعاء C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | يتحقق مما إذا كان الكائن يمثل نسخة من النوع الموصوف بـ targetType. نظير عامل C# 'is'. |
| void [Lock](../../system/object/lock/)() | يطبق قفل جملة C# lock(). استدعِ مباشرةً أو استخدم الكائن [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | نظير طريقة C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). يتيح استنساخ الأنواع المخصصة. |
|  [Object](../../system/object/object/)() | ينشئ كائنًا. يهيئ جميع هياكل البيانات الداخلية. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | منشئ نسخة. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ من الفئات الفرعية. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | عامل الإسناد. لا ينسخ أي شيء فعليًا، فقط يهيئ كائنًا جديدًا ويمكّن من إنشاء نسخ من الفئات الفرعية. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | يقرأ عدد البايتات المحدد من الدفق ويكتبها إلى مصفوفة البايتات المحددة. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | يقرأ عدد البايتات المحدد من الدفق ويكتبها إلى مصفوفة البايتات المحددة. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | يقرأ عدد البايتات المحدد من الدفق ويكتبها إلى مصفوفة البايتات المحددة. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | يقرأ عدد البايتات المحدد من الدفق ويكتبها إلى نطاق البايتات المحدد. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يقرأ بشكل غير متزامن تسلسلًا من البايتات من الدفق الحالي، يقدّم الموضع داخل الدفق بعدد البايتات المقروءة، ويراقب طلبات الإلغاء. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يقرأ بشكل غير متزامن تسلسلًا من البايتات من الدفق الحالي، يقدّم الموضع داخل الدفق بعدد البايتات المقروءة، ويراقب طلبات الإلغاء. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | يقرأ بايتًا واحدًا من الدفق ويعيد قيمة عددية 32 بت مساوية لقيمة البايت المقروء. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | يقارن الكائنات بالمرجع. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | يقارن كائن النوع القيمي بالمرجع مع nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلسلة و nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | تخصيص [Object::ReferenceEquals](../../system/object/referenceequals/) لحالة السلاسل. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | يقلل عداد المرجع المشترك بالقيمة المحددة. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override |يضبط موضع الدفق الممثل بواسطة الكائن الحالي. |
| void [set_Position](./set_position/)(**int64_t**) override | يضبط موضع الدفق. |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | يضبط قيمة تحدد ما إذا كان الدفق الحالي يمكن أن ينتهي مهله. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | يضبط قيمة تحدد ما إذا كان الدفق الحالي يمكن أن ينتهي مهله. |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | يضبط قيمة بالمليثانية تحدد مدة محاولة الدفق للقراءة قبل انتهاء المهلة. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | يضبط قيمة بالمليثانية تحدد مدة محاولة الدفق للقراءة قبل انتهاء المهلة. |
| void [SetLength](./setlength/)(**int64_t**) override | يضبط طول الدفق الممثل بالكائن الحالي. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | يضبط الوسيط القالب الـ n إلى مؤشر ضعيف (بدلاً من مشترك). يسمح بتحويل المؤشرات في الحاويات إلى الوضع الضعيف. |
| int [SharedCount](../../system/object/sharedcount/)() const | يحصل على القيمة الحالية لعداد المرجع المشترك. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | يزيد عداد المرجع المشترك. يجب ألا تُستدعى مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | يقلل ويعيد عداد المرجع المشترك. يجب ألا تُستدعى مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | ينشئ نسخة جديدة. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**) | ينشئ نسخة جديدة. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/)) | ينشئ نسخة جديدة. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/)) | ينشئ نسخة جديدة. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/), [EncryptionPolicy](../encryptionpolicy/)) | ينشئ نسخة جديدة. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | نظير طريقة C# [Object.ToString()](../../system/object/tostring/). يتيح تحويل الكائنات المخصصة إلى سلسلة. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | يطبق بنية C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | يطبق إلغاء قفل جملة C# lock(). استدعِ مباشرةً أو استخدم الكائن [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | يزيد عداد المرجع الضعيف. يجب ألا تُستدعى مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | يقلل عداد المرجع الضعيف. يجب ألا تُستدعى مباشرةً؛ استخدم المؤشرات الذكية أو ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | يكتب مصفوفة البايتات المحددة إلى الدفق. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | يكتب النطاق المحدد من البايتات من مصفوفة البايتات المحددة إلى الدفق. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&) | يكتب مصفوفة البايتات المحددة إلى الدفق. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | يكتب النطاق المحدد من البايتات من مصفوفة البايتات المحددة إلى الدفق. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | يكتب النطاق المحدد من البايتات من مصفوفة البايتات المحددة إلى الدفق. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | يكتب النطاق المحدد من البايتات من نطاق البايتات المحدد إلى الدفق. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | يكتب بشكل غير متزامن تسلسلًا من البايتات إلى الدفق الحالي، يقدّم الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة، ويراقب طلبات الإلغاء. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | يكتب بشكل غير متزامن تسلسلًا من البايتات إلى الدفق الحالي، يقدّم الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة، ويراقب طلبات الإلغاء. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | يكتب قيمة عدد صحيح غير موقع 8-بت إلى الدفق. |
| virtual  [~Object](../../system/object/~object/)() | يدمر الكائن. يحرر جميع هياكل البيانات الداخلية. |

## الحقول

| حقل | الوصف |
| --- | --- |
| static [Null](../../system.io/stream/null/) | دفق لا يحتوي على تخزين أساسي. |

## تعريفات الأنواع

| معرّف نوع | الوصف |
| --- | --- |
| [AsyncResultType](./asyncresulttype/) | نوع AsyncResultType. |
| [StreamImplementationPtr](./streamimplementationptr/) | نوع المؤشر إلى التنفيذ. |

## أنظر أيضًا

* الفئة [AuthenticatedStream](../authenticatedstream/)
* النطاق [System::Net::Security](../)
* المكتبة [Aspose.Slides](../../)