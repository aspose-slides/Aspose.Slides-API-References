---
title: NetworkStream
second_title: Aspose.Slides için C++ API Referansı
description: "Ağ erişimi için verilerin temel akışını sağlar. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu türün örneğini yığıt (stack) üzerinde veya new operatörüyle asla oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 40
url: /tr/system.net.sockets/networkstream/
---
## NetworkStream sınıfı

Ağ erişimi için verilerin temel akışını sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu türün örneğini yığıt (stack) üzerinde veya new operatörünü kullanarak asla oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class NetworkStream : public System::IO::Stream
```

## Yöntemler

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Asenkron bir okuma işlemi başlatır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Asenkron bir okuma işlemi başlatır. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Asenkron bir yazma işlemi başlatır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Asenkron bir yazma işlemi başlatır. |
| void [Close](./close/)(int) | Belirtilen sürenin sonunda mevcut örneği kapatır. |
| virtual void [Close](../../system.io/stream/close/)() | Akışı kapatır. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Belirtilen akışa baytları kopyalar. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Belirtilen akışa baytları kopyalar, belirtilen tampon boyutunu kullanarak. |
| void [Dispose](../../system.io/stream/dispose/)() override | Mevcut nesne tarafından kullanılan tüm kaynakları serbest bırakır ve akışı kapatır. |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Belirtilen asenkron okuma işlemi tamamlanana kadar bekler. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Belirtilen asenkron okuma işlemi tamamlanana kadar bekler. |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | Asenkron bir yazma işlemini sonlandırır. Belirtilen asenkron yazma işlemi tamamlanana kadar bekler. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Asenkron bir yazma işlemini sonlandırır. Belirtilen asenkron yazma işlemi tamamlanana kadar bekler. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca iç amaçlar için. |
| void [Flush](./flush/)() override | Bu akışın tamponlarını temizler ve tüm tamponlanmış verileri temel depolamaya yazar. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Bu akış için tüm tamponları asenkron olarak temizler, tamponlanmış verilerin temel cihaza yazılmasına neden olur ve iptal isteklerini izler. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Bu akış için tüm tamponları asenkron olarak temizler, tamponlanmış verilerin temel cihaza yazılmasına neden olur ve iptal isteklerini izler. |
| **bool** [get_CanRead](./get_canread/)() const override | Akışın okunabilir olup olmadığını belirler. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Akışın konumlandırma (seek) desteği olup olmadığını belirler. |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | Mevcut akışın zaman aşımı yapıp yapmayacağını belirleyen bir değeri alır. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Akışın yazılabilir olup olmadığını belirler. |
| **bool** [get_DataAvailable](./get_dataavailable/)() const | Okunabilir mevcut veri olup olmadığını gösteren bir değer döndürür. |
| **int64_t** [get_Length](./get_length/)() const override | Akışın uzunluğunu bayt cinsinden döndürür. |
| **int64_t** [get_Position](./get_position/)() const override | Akışın mevcut konumunu döndürür. |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | Akışın zaman aşımına uğramadan önce okumayı deneyeceği süreyi milisaniye cinsinden belirleyen bir değeri alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\> [get_Socket](./get_socket/)() | Temel [Socket](../socket/)'ı alır. |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | Akışın zaman aşımına uğramadan önce yazmayı deneyeceği süreyi milisaniye cinsinden belirleyen bir değeri alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme özelliğini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>) | Yeni bir örnek oluşturur. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>, [System::IO::FileAccess](../../system.io/fileaccess/), **bool**) | Yeni bir örnek oluşturur. |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>, **bool**) | Yeni bir örnek oluşturur. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını mümkün kılar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını mümkün kılar. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Akıştan belirtilen sayıda baytı okur ve belirtilen bayt dizisine yazar. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Akıştan belirtilen sayıda baytı okur ve belirtilen bayt dizisine yazar. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Akıştan belirtilen sayıda baytı okur ve belirtilen bayt dizisine yazar. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Akıştan belirtilen sayıda baytı okur ve belirtilen bayt dizisine yazar. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Mevcut akıştan asenkron olarak bir bayt dizisi okur, akış içindeki konumu okunan bayt sayısı kadar ilerletir ve iptal isteklerini izler. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Mevcut akıştan asenkron olarak bir bayt dizisi okur, akış içindeki konumu okunan bayt sayısı kadar ilerletir ve iptal isteklerini izler. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Akıştan tek bir bayt okur ve okunan baytın değerine eşdeğer 32-bit bir tam sayı değeri döndürür. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | Mevcut nesne tarafından temsil edilen akışın konumunu ayarlar. |
| void [set_Position](./set_position/)(**int64_t**) override | Akışın konumunu ayarlar. |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | Mevcut akışın zaman aşımı yapıp yapmayacağını belirleyen bir değeri ayarlar. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Mevcut akışın zaman aşımı yapıp yapmayacağını belirleyen bir değeri ayarlar. |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | Akışın zaman aşımına uğramadan önce okumayı deneyeceği süreyi milisaniye cinsinden belirleyen bir değeri ayarlar. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Akışın zaman aşımına uğramadan önce okumayı deneyeceği süreyi milisaniye cinsinden belirleyen bir değeri ayarlar. |
| void [SetLength](./setlength/)(**int64_t**) override | Mevcut nesne tarafından temsil edilen akışın uzunluğunu ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma özelliğini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Belirtilen bayt aralığından belirtilen alt aralığı akışa yazar. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Mevcut akışa asenkron olarak bir bayt dizisi yazar, bu akıştaki mevcut konumu yazılan bayt sayısı kadar ilerletir ve iptal isteklerini izler. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Mevcut akışa asenkron olarak bir bayt dizisi yazar, bu akıştaki mevcut konumu yazılan bayt sayısı kadar ilerletir ve iptal isteklerini izler. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Belirtilen işaretsiz 8-bit tam sayı değerini akışa yazar. |
| virtual  [~NetworkStream](./~networkstream/)() | Mevcut örneği yok eder. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Alanlar

| Field | Description |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Temel depolama olmadan bir akış. |

## Ayrıca Bakınız

* Sınıf [Stream](../../system.io/stream/)
* İsim Uzayı [System::Net::Sockets](../)
* Kütüphane [Aspose.Slides](../../)