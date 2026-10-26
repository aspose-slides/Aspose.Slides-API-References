---
title: FileStream
second_title: Aspose.Slides for C++ API Referansı
description: "Senkrone ve asenkron okuma ve yazma işlemlerini destekleyen bir dosya akışını temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu tipin örneğini yığında veya new operatörüyle oluşturmaktan kaçının, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarın ve bu işaretçiyi işlevlere argüman olarak geçirin."
type: docs
weight: 287
url: /tr/system.io/filestream/
---
## FileStream sınıfı

Senkron ve asenkron okuma ve yazma işlemlerini destekleyen bir dosya akışını temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tür bir örnek hiçbir zaman yığına (stack) veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı daima [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirin.

```cpp
class FileStream : public System::IO::Stream
```

## Yöntemler

| Metot | Açıklama |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Asenkron bir okuma işlemini başlatır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Asenkron bir yazma işlemini başlatır. |
| void [Close](./close/)() override | Geçerli [FileStream](./) nesnesini kapatır. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Belirtilen akışa baytları kopyalar. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Belirtilen akışa baytları, belirtilen tampon boyutunu kullanarak kopyalar. |
| void [Dispose](../stream/dispose/)() override | Geçerli nesne tarafından kullanılan tüm kaynakları serbest bırakır ve akışı kapatır. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Belirtilen asenkron okuma işlemi tamamlanana kadar bekler. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Asenkron bir yazma işlemini sonlandırır. Belirtilen asenkron yazma işlemi tamamlanana kadar bekler. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) söz dizimiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmaması gerektiği halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmaması gerektiği halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | [FileStream](./) sınıfının yeni bir örneğini oluşturur ve belirtilen parametrelerle başlatır. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/), **int32_t**, [FileOptions](../fileoptions/)) | [FileStream](./) sınıfının yeni bir örneğini oluşturur ve belirtilen parametrelerle başlatır. |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/), **int32_t**, **bool**) | [FileStream](./) sınıfının yeni bir örneğini oluşturur ve belirtilen parametrelerle başlatır. |
|  [FileStream](./filestream/)(const [FileStream](./)\&) |  |
| void [Flush](./flush/)() override | Bu akışın tamponlarını temizler ve tüm tamponlanmış verileri temel dosyaya yazar. |
| void [Flush](./flush/)(**bool**) | Bu akışın tamponlarını temizler ve tüm tamponlanmış verileri temel dosyaya yazar. [Flush()](./flush/) metodunun eşanlamlısıdır. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | Bu akış için tüm tamponları asenkron olarak temizler, tamponlanmış verilerin temel aygıta yazılmasını sağlar ve iptal isteğini izler. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Bu akış için tüm tamponları asenkron olarak temizler, tamponlanmış verilerin temel aygıta yazılmasını sağlar ve iptal isteğini izler. |
| **bool** [get_CanRead](./get_canread/)() const override | Akışın okunabilir olup olmadığını belirler. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Akışın konumlandırma (seeking) destekleyip desteklemediğini belirler. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Geçerli akışın zaman aşımına uğrayıp uğramayacağını belirleyen bir değeri alır. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Akışın yazılabilir olup olmadığını belirler. |
| **int64_t** [get_Length](./get_length/)() const override | Akışın uzunluğunu bayt cinsinden döndürür. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Geçerli [FileStream](./) nesnesi tarafından kapsanan dosyanın adını döndürür. |
| **int64_t** [get_Position](./get_position/)() const override | Akışın geçerli konumunu döndürür. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Akışın zaman aşımına uğramadan önce ne kadar süreyle okuma yapacağını milisaniye cinsinden belirten bir değeri alır. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Akışın zaman aşımına uğramadan önce ne kadar süreyle yazma yapacağını milisaniye cinsinden belirten bir değeri alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) izleme nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogudur. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapısını etkinleştirir. |
| [FileStream](./)\& [operator=](./operator_equal/)(const [FileStream](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapısını etkinleştirir. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Akıştan belirtilen sayıda baytı okur ve belirtilen bayt dizisine yazar. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Akıştan belirtilen sayıda baytı okur ve belirtilen bayt dizisine yazar. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Akıştan belirtilen sayıda baytı okur ve belirtilen bayt dizisine yazar. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Akıştan belirtilen sayıda baytı okur ve belirtilen bayt aralığına yazar. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | Mevcut akıştan asenkron olarak bir bayt dizisi okur, akış içindeki konumu okunan bayt sayısı kadar ilerletir ve iptal isteklerini izler. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Mevcut akıştan asenkron olarak bir bayt dizisi okur, akış içindeki konumu okunan bayt sayısı kadar ilerletir ve iptal isteklerini izler. |
| **int32_t** [ReadByte](./readbyte/)() override | Akıştan tek bir bayt okur ve okunan baytın değerine eşdeğer 32-bit tam sayı değerini döndürür. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Geçerli nesne tarafından temsil edilen akışın konumunu ayarlar. |
| void [set_Position](./set_position/)(**int64_t**) override | Akışı boşaltır ve ardından akışın konumunu ayarlar. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Geçerli akışın zaman aşımına uğrayıp uğramayacağını belirleyen bir değeri ayarlar. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Akışın zaman aşımına uğramadan önce ne kadar süreyle okuma yapacağını milisaniye cinsinden belirten bir değeri ayarlar. |
| void [SetLength](./setlength/)(**int64_t**) override | Geçerli nesne tarafından temsil edilen akışın uzunluğunu ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kaplarda işaretçileri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogudur. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) izleme nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Belirtilen bayt dizisinden belirli bir alt aralığı akışa yazar. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Belirtilen bayt dizisinden belirli bir alt aralığı akışa yazar. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Belirtilen bayt dizisinden belirli bir alt aralığı akışa yazar. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Belirtilen bayt aralığından belirli bir alt aralığı akışa yazar. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | Mevcut akışa asenkron olarak bir bayt dizisi yazar, bu akıştaki konumu yazılan bayt sayısı kadar ilerletir ve iptal isteklerini izler. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Mevcut akışa asenkron olarak bir bayt dizisi yazar, bu akıştaki konumu yazılan bayt sayısı kadar ilerletir ve iptal isteklerini izler. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Belirtilen işaretsiz 8-bit tamsayı değerini akışa yazar. |
|  [~FileStream](./~filestream/)() | Yıkıcı. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static constexpr [DefaultBufferSize](./defaultbuffersize/) | Okuma ve yazma işlemleri sırasında tamponlanan bayt sayısının varsayılan değeri. |
| static [Null](../stream/null/) | Temel bir depolama olmaksızın bir akış. |

## İlgili

* Sınıf [Stream](../stream/)
* Ad alanı [System::IO](../)
* Kütüphane [Aspose.Slides](../../)