---
title: CryptoStream
second_title: Aspose.Slides for C++ API Referansı
description: "Mevcut akışı kriptografik bir işlevle saran akış uygulaması. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak allocate edilmelidir. Yığın üzerinde veya operator new kullanılarak bu tipin örneği oluşturulmamalıdır, çünkü bu çalışma zamanı hatalarına ve/veya assert hatalarına yol açar. Her zaman bu sınıfı System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 53
url: /tr/system.security.cryptography/cryptostream/
---
## CryptoStream sınıfı

Stream implementation that wraps existing stream with a cryptographic function. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CryptoStream : public System::IO::Stream
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Asenkron bir okuma işlemini başlatır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Asenkron bir yazma işlemini başlatır. |
| void [Close](./close/)() override | Bağlantıyı kapatır. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | Belirtilen akışa baytları kopyalar. |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | Belirtilen akışa baytları, belirtilen tampon boyutunu kullanarak kopyalar. |
|  [CryptoStream](./cryptostream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\>\&, [CryptoStreamMode](../cryptostreammode/)) | Yapıcı. |
| void [Dispose](../../system.io/stream/dispose/)() override | Geçerli nesne tarafından kullanılan tüm kaynakları serbest bırakır ve akışı kapatır. |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Belirtilen asenkron okuma işlemi tamamlanana kadar bekler. |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Asenkron bir yazma işlemini sonlandırır. Belirtilen asenkron yazma işlemi tamamlanana kadar bekler. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiği kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmaması gerektiği halde, iki NaN'in eşit kabul edildiği C#-style kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmaması gerektiği halde, iki NaN'in eşit kabul edildiği C#-style kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| void [Flush](./flush/)() override | Sarmalanmış akışa tamponu boşaltır. Dönüştürme algoritması hâlâ daha fazla veri bekleyebileceği için hiçbir şey yapmaz. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Bu akış için tüm tamponları asenkron olarak temizler, tamponlanmış verilerin temel aygıta yazılmasını sağlar ve iptal isteklerini izler. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | Bu akış için tüm tamponları asenkron olarak temizler, tamponlanmış verilerin temel aygıta yazılmasını sağlar ve iptal isteklerini izler. |
| void [FlushFinalBlock](./flushfinalblock/)() | Tampondaki kalan verileri akışa yazar. |
| **bool** [get_CanRead](./get_canread/)() const override | Akışın okunabilir olup olmadığını denetler. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Akışın konumlandırılabilir olup olmadığını denetler. |
| virtual **bool** [get_CanTimeout](../../system.io/stream/get_cantimeout/)() const | Geçerli akışın zaman aşımına uğrayıp uğrayamayacağını belirleyen bir değer alır. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Akışın yazılabilir olup olmadığını denetler. |
| **int64_t** [get_Length](./get_length/)() const override | Akış uzunluğunu alır. Desteklenmez. |
| **int64_t** [get_Position](./get_position/)() const override | Akıştaki geçerli konumu alır. Desteklenmez. |
| virtual int [get_ReadTimeout](../../system.io/stream/get_readtimeout/)() const | Akışın zaman aşımına uğramadan önce ne kadar süre okuma yapacağını milisaniye cinsinden belirten bir değer alır. |
| virtual int [get_WriteTimeout](../../system.io/stream/get_writetimeout/)() const | Akışın zaman aşımına uğramadan önce ne kadar süre yazma yapacağını milisaniye cinsinden belirten bir değer alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkilendirilmiş referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yöntemi analogudur. Özel nesnelerin hashlemesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneğini temsil edip etmediğini denetler. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analogudur. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapısını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturulmasını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturulmasını etkinleştirir. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Akıştan veri okur. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Akıştan veri okur. |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Belirtilen sayıda baytı akıştan okur ve belirtilen bayt dizisine yazar. |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Belirtilen sayıda baytı akıştan okur ve belirtilen bayt aralığına yazar. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Mevcut akıştan bir bayt dizisini asenkron olarak okur, okunan bayt sayısı kadar akış içindeki konumu ilerletir ve iptal isteklerini izler. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Mevcut akıştan bir bayt dizisini asenkron olarak okur, okunan bayt sayısı kadar akış içindeki konumu ilerletir ve iptal isteklerini izler. |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | Akıştan tek bir bayt okur ve okunan baytın değerine eşdeğer 32-bit tamsayı değerini döndürür. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) öğesinin dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) öğesinin dize durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | Akışta konumu arar. Desteklenmez. |
| void [set_Position](./set_position/)(**int64_t**) override | Akışta konumu arar. Desteklenmez. |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | Geçerli akışın zaman aşımına uğrayıp uğrayamayacağını belirleyen bir değer ayarlar. |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | Akışın zaman aşımına uğramadan önce ne kadar süre okuma yapacağını milisaniye cinsinden belirleyen bir değer ayarlar. |
| void [SetLength](./setlength/)(**int64_t**) override | Akışın boyutunu arar. Desteklenmez. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf bir işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının geçerli değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analogudur. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Akışa veri yazar. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Akışa veri yazar. |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar. |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Belirtilen bayt aralığından belirtilen alt aralığı akışa yazar. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Mevcut akışa bir bayt dizisini asenkron olarak yazar, yazılan bayt sayısı kadar bu akıştaki konumu ilerletir ve iptal isteklerini izler. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Mevcut akışa bir bayt dizisini asenkron olarak yazar, yazılan bayt sayısı kadar bu akıştaki konumu ilerletir ve iptal isteklerini izler. |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | Belirtilen işaretsiz 8-bit tamsayı değerini akışa yazar. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Null](../../system.io/stream/null/) | Altta yatan bir depolama olmadan bir akış. |

## Bakınız

* Sınıf [Stream](../../system.io/stream/)
* Ad alanı [System::Security::Cryptography](../)
* Kütüphane [Aspose.Slides](../../)