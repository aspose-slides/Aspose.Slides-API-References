---
title: UnmanagedMemoryStream
second_title: Aspose.Slides for C++ API Referansı
description: "Yönetilmeyen belleğe erişim sağlar. Bu sınıfa ait nesneler yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneği asla yığıt üzerinde veya new operatörüyle oluşturulmamalıdır; çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirmek için kullanın."
type: docs
weight: 456
url: /tr/system.io/unmanagedmemorystream/
---
## UnmanagedMemoryStream sınıfı

Yönetilmeyen bellek erişimi sağlar. Bu sınıfa ait nesneler yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığıt üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı daima [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin.

```cpp
class UnmanagedMemoryStream : public System::IO::Stream
```

## Metodlar

| Metod | Açıklama |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Asenkron bir okuma işlemi başlatır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Asenkron bir yazma işlemi başlatır. |
| virtual void [Close](../stream/close/)() | Akışı kapatır. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Belirtilen akışa baytları kopyalar. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Belirtilen akışa baytları, belirtilen tampon boyutunu kullanarak kopyalar. |
| void [Dispose](../stream/dispose/)() override | Geçerli nesnenin kullandığı tüm kaynakları serbest bırakır ve akışı kapatır. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Belirtilen asenkron okuma işlemi tamamlanıncaya kadar bekler. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Asenkron bir yazma işlemini sonlandırır. Belirtilen asenkron yazma işlemi tamamlanıncaya kadar bekler. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiğiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN'ın eşit kabul edildiği C#-stilinde kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN'ın eşit kabul edildiği C#-stilinde kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| void [Flush](./flush/)() override | Hiçbir şey yapmaz. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Bu akış için tüm tamponları asenkron olarak temizler, tamponlanmış verilerin altında yatan cihaza yazılmasını sağlar ve iptal isteklerini izler. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Bu akış için tüm tamponları asenkron olarak temizler, tamponlanmış verilerin altında yatan cihaza yazılmasını sağlar ve iptal isteklerini izler. |
| **bool** [get_CanRead](./get_canread/)() const override | Akışın okunabilir olup olmadığını belirler. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Akışın konumlandırmayı (seek) destekleyip desteklemediğini belirler. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Geçerli akışın zaman aşımı yapıp yapamayacağını belirleyen bir değer alır. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Akışın yazılabilir olup olmadığını belirler. |
| virtual **int64_t** [get_Capacity](./get_capacity/)() const | Altındaki bellek tamponunun geçerli kapasitesini döndürür. |
| **int64_t** [get_Length](./get_length/)() const override | Akışın uzunluğunu bayt cinsinden döndürür. |
| **int64_t** [get_Position](./get_position/)() const override | Akışın geçerli konumunu döndürür. |
| **uint8_t** * [get_PositionPointer](./get_positionpointer/)() | UYGULANMADI. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Akışın zaman aşımına uğramadan önce ne kadar süre (milisaniye) okuma yapacağını belirleyen bir değer alır. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Akışın zaman aşımına uğramadan önce ne kadar süre (milisaniye) yazma yapacağını belirleyen bir değer alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogıdır. Özel nesnelerin karma (hash) oluşturmasını sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek türünü alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogıdır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedefTür tarafından tanımlanan türün bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogıdır. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesi kilitlemesini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogıdır. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Aslında hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Akıştan belirtilen sayıda baytı okur ve belirtilen bayt dizisine yazar. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Akıştan belirtilen sayıda baytı okur ve belirtilen bayt dizisine yazar. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Akıştan belirtilen sayıda baytı okur ve belirtilen bayt dizisine yazar. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Akıştan belirtilen sayıda baytı okur ve belirtilen bayt aralığına yazar. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Geçerli akıştan asenkron olarak bir bayt dizisi okur, okunan bayt sayısı kadar akış konumunu ilerletir ve iptal isteklerini izler. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Geçerli akıştan asenkron olarak bir bayt dizisi okur, okunan bayt sayısı kadar akış konumunu ilerletir ve iptal isteklerini izler. |
| virtual int [ReadByte](../stream/readbyte/)() | Akıştan tek bir bayt okur ve okunan baytın değerine eşdeğer 32-bit tamsayı değerini döndürür. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans üzerinden karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans üzerinden karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in stringler durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Geçerli nesne tarafından temsil edilen akışın konumunu ayarlar. |
| void [set_Position](./set_position/)(**int64_t**) override | Akışın konumunu ayarlar. |
| void [set_PositionPointer](./set_positionpointer/)(**uint8_t** *) | UYGULANMADI. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Geçerli akışın zaman aşımı yapıp yapmayacağını belirleyen bir değer ayarlar. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Akışın zaman aşımına uğramadan önce ne kadar süre (milisaniye) okuma yapacağını belirleyen bir değer ayarlar. |
| void [SetLength](./setlength/)(**int64_t**) override | UYGULANMADI. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşılan yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının geçerli değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogıdır. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesi kilidini açar. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
|  [UnmanagedMemoryStream](./unmanagedmemorystream/)(**uint8_t** *, **int64_t**) | [UnmanagedMemoryStream](./)'nin yeni bir örneğini oluşturur. |
|  [UnmanagedMemoryStream](./unmanagedmemorystream/)(**uint8_t** *, **int64_t**, **int64_t**, [FileAccess](../fileaccess/)) | [UnmanagedMemoryStream](./)'nin yeni bir örneğini oluşturur. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | UYGULANMADI. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | UYGULANMADI. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Belirtilen bayt dizisinden belirtilen alt aralığı akışa yazar. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Belirtilen bayt aralığından belirtilen alt aralığı akışa yazar. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Geçerli akışa asenkron olarak bir bayt dizisi yazar, yazılan bayt sayısı kadar akış konumunu ilerletir ve iptal isteklerini izler. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Geçerli akışa asenkron olarak bir bayt dizisi yazar, yazılan bayt sayısı kadar akış konumunu ilerletir ve iptal isteklerini izler. |
| virtual void [WriteByte](../stream/writebyte/)(**uint8_t**) | Belirtilen işaretsiz 8-bit tamsayı değerini akışa yazar. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Null](../stream/null/) | Altında herhangi bir depolama olmayan bir akış. |

## Ayrıca Bakınız

* Sınıf [Stream](../stream/)
* Ad alanı [System::IO](../)
* Kütüphane [Aspose.Slides](../../)