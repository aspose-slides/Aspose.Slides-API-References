---
title: SslStream
second_title: Aspose.Slides for C++ API Referansı
description: Sunucuyu ve isteğe bağlı olarak istemciyi kimlik doğrulamak için SSL protokolünü kullanan bir akış.
type: docs
weight: 14
url: /tr/system.net.security/sslstream/
---
## SslStream sınıfı

A stream that uses the SSL protocol to authenticate the server and optionally the client.

```cpp
class SslStream : public System::Net::Security::AuthenticatedStream
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/)) | Bağlantının istemci tarafını kimlik doğrular. |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>, [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/), **bool**) | Bağlantının istemci tarafını kimlik doğrular. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Asenkron bir okuma işlemi başlatır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Asenkron bir okuma işlemi başlatır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Asenkron bir yazma işlemi başlatır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Asenkron bir yazma işlemi başlatır. |
| void [Close](./close/)() override | Akışı kapatır. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Belirtilen akışa baytları kopyalar. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Belirtilen baytları, belirtilen tampon boyutunu kullanarak belirtilen akışa kopyalar. |
| void [Dispose](./dispose/)(**bool**) override | Mevcut nesne tarafından kullanılan tüm kaynakları serbest bırakır ve akışı kapatır. |
| void [Dispose](../../system.io/stream/dispose/)() override | Mevcut nesne tarafından kullanılan tüm kaynakları serbest bırakır ve akışı kapatır. |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Belirtilen asenkron okuma işlemi tamamlanana kadar bekler. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Belirtilen asenkron okuma işlemi tamamlanana kadar bekler. |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Asenkron bir yazma işlemini sonlandırır. Belirtilen asenkron yazma işlemi tamamlanana kadar bekler. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Asenkron bir yazma işlemini sonlandırır. Belirtilen asenkron yazma işlemi tamamlanana kadar bekler. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) anlambilimiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| void [Flush](./flush/)() override | Bu akışın tamponlarını temizler ve tüm tamponlanmış verileri alttaki depolama birimine yazar. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Bu akış için tüm tamponları asenkron olarak temizler, tamponlanmış verilerin alttaki aygıta yazılmasını sağlar ve iptal isteklerini izler. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Bu akış için tüm tamponları asenkron olarak temizler, tamponlanmış verilerin alttaki aygıta yazılmasını sağlar ve iptal isteklerini izler. |
| **bool** [get_CanRead](./get_canread/)() const override | Akışın okunabilir olup olmadığını belirler. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Akışın konumlandırmayı destekleyip desteklemediğini belirler. |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | Geçerli akışın zaman aşımına uğrayıp uğramayacağını belirleyen bir değer alır. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Akışın yazılabilir olup olmadığını belirler. |
| virtual **bool** [get_CheckCertRevocationStatus](./get_checkcertrevocationstatus/)() | Sertifika doğrulama sürecinde sertifika iptal listesinin kontrol edilip edilmediğini gösteren bir değer döndürür. |
| virtual [System::Security::Authentication::CipherAlgorithmType](../../system.security.authentication/cipheralgorithmtype/) [get_CipherAlgorithm](./get_cipheralgorithm/)() | Şifreleme algoritmasını döndürür. |
| virtual **int32_t** [get_CipherStrength](./get_cipherstrength/)() | Kullanılan şifreleme algoritmasının gücünü döndürür. |
| virtual [System::Security::Authentication::HashAlgorithmType](../../system.security.authentication/hashalgorithmtype/) [get_HashAlgorithm](./get_hashalgorithm/)() | Karma algoritmasını döndürür. |
| virtual **int32_t** [get_HashStrength](./get_hashstrength/)() | Kullanılan karma algoritmasının gücünü döndürür. |
| **bool** [get_IsAuthenticated](./get_isauthenticated/)() const override | Kimliğin başarıyla geçtiğini gösteren bir değer döndürür. |
| **bool** [get_IsEncrypted](./get_isencrypted/)() const override | Bu akış kullanılarak gönderilen verilerin şifrelenip şifrelenmediğini gösteren bir değer döndürür. |
| **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const override | Bir sunucu ve bir istemcinin kimlik doğrulanıp doğrulanmadığını gösteren bir değer döndürür. |
| **bool** [get_IsServer](./get_isserver/)() const override | Bağlantının yerel tarafının sunucu olup olmadığını gösteren bir değer döndürür. |
| **bool** [get_IsSigned](./get_issigned/)() const override | Bu akış kullanılarak gönderilen verilerin imzalı olup olmadığını gösteren bir değer döndürür. |
| virtual **int32_t** [get_KeyExchangeStrength](./get_keyexchangestrength/)() | Kullanılan anahtar değişim algoritmasının gücünü döndürür. |
| **bool** [get_LeaveInnerStreamOpen](../authenticatedstream/get_leaveinnerstreamopen/)() const | Gönderme ve alma verileri için mevcut sınıf örnekleri tarafından kullanılan akışı döndürür. |
| **int64_t** [get_Length](./get_length/)() const override | Akışın uzunluğunu bayt cinsinden döndürür. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_LocalCertificate](./get_localcertificate/)() | Yerel uç nokta kimlik doğrulaması için kullanılan sertifikayı döndürür. |
| **int64_t** [get_Position](./get_position/)() const override | Akışın mevcut konumunu döndürür. |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | Akışın zaman aşımına uğramadan okumaya çalışacağı sürenin milisaniye cinsinden değerini alır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_RemoteCertificate](./get_remotecertificate/)() | Uzak uç nokta kimlik doğrulaması için kullanılan sertifikayı döndürür. |
| virtual [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/) [get_SslProtocol](./get_sslprotocol/)() | SSL protokolünü döndürür. |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | Akışın zaman aşımına uğramadan yazmaya çalışacağı sürenin milisaniye cinsinden değerini alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeri. Özel nesnelerin karma değerini oluşturmayı sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin benzeri. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Yeni bir örnek oluşturur. Tüm iç veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekten hiçbir şeyi kopyalamaz; sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekten hiçbir şeyi kopyalamaz; sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Akıştan belirtilen sayıda baytı okur ve belirtilen bayt dizisine yazar. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Akıştan belirtilen sayıda baytı okur ve belirtilen bayt dizisine yazar. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Akıştan belirtilen sayıda baytı okur ve belirtilen bayt dizisine yazar. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Akıştan belirtilen sayıda baytı okur ve belirtilen bayt dilimine yazar. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Mevcut akıştan asenkron olarak bir dizi bayt okur, okunan bayt sayısı kadar akış içindeki konumu ilerletir ve iptal isteklerini izler. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Mevcut akıştan asenkron olarak bir dizi bayt okur, okunan bayt sayısı kadar akış içindeki konumu ilerletir ve iptal isteklerini izler. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Akıştan tek bir bayt okur ve okunan baytın değerine eşdeğer 32-bit tamsayı değerini döndürür. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumları için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | Mevcut nesne tarafından temsil edilen akışın konumunu ayarlar. |
| void [set_Position](./set_position/)(**int64_t**) override | Akışın konumunu ayarlar. |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | Mevcut akışın zaman aşımına uğrayıp uğramayacağını belirleyen bir değer ayarlar. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Mevcut akışın zaman aşımına uğrayıp uğramayacağını belirleyen bir değer ayarlar. |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | Akışın zaman aşımına uğramadan okumaya çalışacağı sürenin milisaniye cinsinden değerini ayarlar. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Akışın zaman aşımına uğramadan okumaya çalışacağı sürenin milisaniye cinsinden değerini ayarlar. |
| void [SetLength](./setlength/)(**int64_t**) override | Mevcut nesne tarafından temsil edilen akışın uzunluğunu ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını bir zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | Yeni bir örnek oluşturur. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**) | Yeni bir örnek oluşturur. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/)) | Yeni bir örnek oluşturur. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/)) | Yeni bir örnek oluşturur. |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/), [EncryptionPolicy](../encryptionpolicy/)) | Yeni bir örnek oluşturur. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin benzeri. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Belirtilen bayt dizisini akışa yazar. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Belirtilen bayt dizisinden belirtilen bayt alt aralığını akışa yazar. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Belirtilen bayt dizisini akışa yazar. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Belirtilen bayt dizisinden belirtilen bayt alt aralığını akışa yazar. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Belirtilen bayt dizisinden belirtilen bayt alt aralığını akışa yazar. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Belirtilen bayt diliminden belirtilen bayt alt aralığını akışa yazar. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Mevcut akışa asenkron olarak bir dizi bayt yazar, yazılan bayt sayısı kadar akış içindeki konumu ilerletir ve iptal isteklerini izler. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Mevcut akışa asenkron olarak bir dizi bayt yazar, yazılan bayt sayısı kadar akış içindeki konumu ilerletir ve iptal isteklerini izler. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Belirtilen işaretsiz 8-bit tam sayı değerini akışa yazar. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarının belleğini serbest bırakır. |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Altta bir depolama birimi olmayan bir akış. |

## Tip Tanımları

| Typedef | Açıklama |
| --- | --- |
| [AsyncResultType](./asyncresulttype/) | AsyncResultType tipinin türü. |
| [StreamImplementationPtr](./streamimplementationptr/) | Uygulamanın işaretçisinin türü. |

## Ayrıca Bakınız

* Sınıf [AuthenticatedStream](../authenticatedstream/)
* Ad alanı [System::Net::Security](../)
* Kütüphane [Aspose.Slides](../../)