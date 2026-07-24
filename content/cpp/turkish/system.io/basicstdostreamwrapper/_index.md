---
title: BasicSTDOStreamWrapper
second_title: Aspose.Slides için C++ API Referansı
description: "std::basic_ostream ve türetilmiş nesneler için System.IO.Stream benzeri bir sarmalayıcı temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu tip bir örnek asla yığıtta veya operator new kullanılarak oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçmek için kullanın."
type: docs
weight: 27
url: /tr/system.io/basicstdostreamwrapper/
---
## BasicSTDOStreamWrapper sınıf

[System.IO.Stream](../stream/) benzeri bir std::basic_ostream ve türetilmiş nesneler için bir sarmalayıcı temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) fonksiyonu kullanılarak tahsis edilmelidir. Bu tip bir örnek asla yığıt üzerinde veya operator new kullanılarak oluşturulmamalıdır; aksi takdirde çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
template<typename T,typename>class BasicSTDOStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(std::basic_ostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | [BasicSTDOStreamWrapper](./)'in yeni bir örneğini oluşturur. |
|  [BasicSTDOStreamWrapper](./basicstdostreamwrapper/)(const [BasicSTDOStreamWrapper](./)\&) | Kopya yapıcı. Silinmiştir. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Asenkron bir okuma işlemi başlatır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Asenkron bir yazma işlemi başlatır. |
| virtual void [Close](../stream/close/)() | Akışı kapatır. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Belirtilen akıma baytları kopyalar. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Belirtilen akıma baytları kopyalar, belirtilen tampon boyutunu kullanarak. |
| void [Dispose](../stream/dispose/)() override | Mevcut nesne tarafından kullanılan tüm kaynakları serbest bırakır ve akışı kapatır. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Belirtilen asenkron okuma işlemi tamamlanana kadar bekler. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Asenkron bir yazma işlemini sonlandırır. Belirtilen asenkron yazma işlemi tamamlanana kadar bekler. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiğiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN'ın eşit kabul edildiği C# tarzı çift noktalı karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| void [Flush](./flush/)() override | Bu akışın tamponlarını temizler ve tüm tamponlanmış verileri temel depolamaya yazar. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Bu akışın tüm tamponlarını asenkron olarak temizler, tamponlanmış verilerin temel cihaza yazılmasını sağlar ve iptal isteklerini izler. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Bu akışın tüm tamponlarını asenkron olarak temizler, tamponlanmış verilerin temel cihaza yazılmasını sağlar ve iptal isteklerini izler. |
| **bool** [get_CanRead](../stdiostreamwrapperbase/get_canread/)() const override | Akışın okuma destekleyip desteklemediğini belirler. |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | Akışın konumlandırma (seeking) destekleyip desteklemediğini belirler. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Mevcut akışın zaman aşımına uğrayıp uğrayamayacağını belirleyen bir değeri alır. |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | Akışın uzunluğunu döndürür. |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | Akışın geçerli konumunu döndürür. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Akışın zaman aşımına uğramadan önce okuma denemesi yapacağı süreyi milisaniye cinsinden alır. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Akışın zaman aşımına uğramadan önce yazma denemesi yapacağı süreyi milisaniye cinsinden alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesne ile ilişkili referans sayaç veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin karmalanmasını sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipe bir örnek olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini gerçekleştirir. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözcüsü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcılarını etkinleştirir. |
| [BasicSTDOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDOStreamWrapper](./)\&) | Kopya atama operatörü. Silinmiştir. |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Kopya atama operatörü. Silinmiştir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcılarını etkinleştirir. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Sarma modu ikili ise, akıştan belirtilen sayıda baytı okur, aksi takdirde belirtilen sayıda karakteri okuyup **uint8_t** tipine dönüştürür. Okumanın sonucunu belirtilen bayt dizisine yazar. Desteklenmez! |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Akıştan belirtilen sayıda baytı okur ve belirtilen bayt dizisine yazar. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Akıştan belirtilen sayıda baytı okur ve belirtilen bayt dizisine yazar. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Akıştan belirtilen sayıda baytı okur ve belirtilen bayt aralığına yazar. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Mevcut akıştan asenkron olarak bir bayt dizisi okur, akıştaki konumu okunan bayt sayısı kadar ilerletir ve iptal isteklerini izler. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Mevcut akıştan asenkron olarak bir bayt dizisi okur, akıştaki konumu okunan bayt sayısı kadar ilerletir ve iptal isteklerini izler. |
| int [ReadByte](./readbyte/)() override | Sarma modu ikili ise, son çözümlenen karakter depolamasından tek bir bayt okur, aksi takdirde akıştan tek bir karakter okur ve **uint8_t** tipine dönüştürür. Desteklenmez! |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirilmiş hali. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirilmiş hali. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | RTTI bilgisi. |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Mevcut nesne tarafından temsil edilen akışın konumunu ayarlar. |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | Akışın konumunu ayarlar. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Mevcut akışın zaman aşımı yapıp yapmayacağını belirleyen bir değeri ayarlar. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Milisaniye cinsinden bir değer ayarlar; bu değer akışın zaman aşımına uğramadan önce ne kadar okuma denemesi yapacağını belirler. |
| void [SetLength](./setlength/)(**int64_t**) override | Mevcut nesne tarafından temsil edilen akışın uzunluğunu ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının geçerli değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | Kopya yapıcı. Silinmiştir. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını gerçekleştirir. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini gerçekleştirir. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözcüsü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Sarma modu ikili ise, belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar; aksi takdirde belirtilen bayt dizisinden alt aralığı char_type tipine dönüştürür ve ardından sonucu akışa yazar. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Belirtilen bayt aralığından belirtilen alt aralığı akışa yazar. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Mevcut akışa asenkron olarak bir bayt dizisi yazar, bu akıştaki konumu yazılan bayt sayısı kadar ilerletir ve iptal isteklerini izler. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Mevcut akışa asenkron olarak bir bayt dizisi yazar, bu akıştaki konumu yazılan bayt sayısı kadar ilerletir ve iptal isteklerini izler. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Sarma modu ikili ise, belirtilen unsigned 8-bit tam sayı değerini akışa yazar; aksi takdirde char_type tipine dönüştürür ve sonucu akışa yazar. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapıları serbest bırakılır. |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Null](../stream/null/) | Altta yatan bir depolama olmadan bir akış. |

## Typedef'ler

| Typedef | Açıklama |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## Bakınız

* Sınıf [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* Ad Alanı [System::IO](../)
* Kütüphane [Aspose.Slides](../../)