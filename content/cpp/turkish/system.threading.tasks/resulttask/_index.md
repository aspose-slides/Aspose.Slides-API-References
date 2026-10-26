---
title: ResultTask
second_title: Aspose.Slides for C++ API Referansı
description: Tamamlandığında bir sonuç değeri döndüren bir Task uzmanlaşması.
type: docs
weight: 40
url: /tr/system.threading.tasks/resulttask/
---
## ResultTask sınıfı


Bir [Task](../task/) uzmanlaşması, tamamlandığında bir sonuç değeri döndürür.

```cpp
template<typename T>class ResultTask : public System::Threading::Tasks::Task
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Görev tarafından döndürülen sonuç değerinin türü |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| void [Activate](../task/activate/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Görevi bir zamanlayıcıda yürütülmek üzere etkinleştirir. |
| void [AddCompletionAction](../task/addcompletionaction/)(const [Action](../../system/action/)<>\&) | Tamamlandığında yürütülecek bir devam eylemi ekler. |
| void [Cancel](../task/cancel/)() | Görevi iptal edilmiş olarak işaretler ve görevi sonlandırır. |
| void [Complete](./complete/)(const T\&) | Görev için sonuç değerini ayarlar ve görevi tamamlar. |
| void [Complete](../task/complete/)() | Görevi tamamlanmış olarak işaretler ve görevi sonlandırır. |
| [Runtime::CompilerServices::ConfiguredResultTaskAwaitable](../../system.runtime.compilerservices/configuredresulttaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | Bu sonuç görevi üzerindeki await'ların bağlam yakalama açısından nasıl davranacağını yapılandırır. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>\>\&) | Sonuç görevi tamamlandığında yürütülen bir devam oluşturur. |
| [RTaskPtr](../../system/rtaskptr/)\<TNewResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[RTaskPtr](../../system/rtaskptr/)\<T\>, TNewResult\>\&) | Sonuç görevi tamamlandığında yürütülen bir devam oluşturur. |
| [TaskPtr](../../system/taskptr/) [ContinueWith](./continuewith/)(const [Action](../../system/action/)\<[TaskPtr](../../system/taskptr/)\>\&) | Görev tamamlandığında yürütülen bir devam oluşturur. |
| [RTaskPtr](../../system/rtaskptr/)\<TResult\> [ContinueWith](./continuewith/)(const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/), TResult\>\&) | Görev tamamlandığında yürütülen bir devam oluşturur. |
| void [Deactivate](../task/deactivate/)() | Görev mevcut bir zamanlayıcıda yürütülmek üzere ise devre dışı bırakır. |
| void [Dispose](../task/dispose/)() override | Görevle ilişkili kaynakları serbest bırakır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiğiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| void [Execute](../task/execute/)() | Görevin fonksiyonunu yürütür. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& [get_AsyncState](../task/get_asyncstate/)() const | Görevle ilişkili kullanıcı tanımlı durum nesnesini alır. |
| static const [TaskPtr](../../system/taskptr/)\& [get_CompletedTask](../task/get_completedtask/)() | Tamamlanmış bir görevi (singleton) alır. |
| static [Nullable](../../system/nullable/)\<**int32_t**\> [get_CurrentId](../task/get_currentid/)() |  |
| [AggregateException](../../system/aggregateexception/) [get_Exception](../task/get_exception/)() const | Görevin kimliğini alır. |
| **int32_t** [get_Id](../task/get_id/)() const |  |
| **bool** [get_IsCanceled](../task/get_iscanceled/)() const | Görevin iptal nedeniyle tamamlanıp tamamlanmadığını alır. |
| **bool** [get_IsCompleted](../task/get_iscompleted/)() const | Görevin tamamlanıp tamamlanmadığını alır. |
| **bool** [get_IsFaulted](../task/get_isfaulted/)() const | Görevin ele alınmamış bir istisna nedeniyle tamamlanıp tamamlanmadığını alır. |
| T [get_Result](./get_result/)() | Asenkron işlemin sonucunu alır. |
| const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\& [get_Scheduler](../task/get_scheduler/)() const | Bu görevle ilişkili zamanlayıcıyı alır. |
| [TaskStatus](../taskstatus/) [get_Status](../task/get_status/)() const | Görevin geçerli durumunu alır. |
| [Runtime::CompilerServices::ResultTaskAwaiter](../../system.runtime.compilerservices/resulttaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | Await ile kullanılmak üzere bu sonuç görevi için bir awaiter alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans üzerinden karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans üzerinden karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için uzmanlaşması. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin stringler durumu için uzmanlaşması. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
|  [ResultTask](./resulttask/)(const [Func](../../system/func/)\<T\>\&) | Bir değer döndüren fonksiyonla [ResultTask](./) oluşturur. |
|  [ResultTask](./resulttask/)() | İç uygulama. Kullanıcı kodu için değildir. |
|  [ResultTask](./resulttask/)(const T\&) | Belirtilen sonuçla sonuç görevleri oluşturmak için dahili yapıcı. |
| void [RunSynchronously](../task/runsynchronously/)() | Görevi mevcut iş parçacığında senkron olarak çalıştırır. |
| void [RunSynchronously](../task/runsynchronously/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Görevi belirtilen zamanlayıcıyı kullanarak senkron olarak çalıştırır. |
| void [set_Function](../task/set_function/)(const [FunctionT](../task/functiont/)\&) | Yürütülecek iç fonksiyonu ayarlar. |
| void [set_Result](./set_result/)(const T\&) | Görev için sonuç değerini ayarlar. |
| void [set_Scheduler](../task/set_scheduler/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Bu görevle ilişkili zamanlayıcıyı ayarlar. |
| void [set_Status](../task/set_status/)([TaskStatus](../taskstatus/)) | Görev durumunu ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının geçerli değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [Start](../task/start/)() | Görev yürütmesini varsayılan zamanlayıcıyı kullanarak başlatır. |
| void [Start](../task/start/)(const [SharedPtr](../../system/sharedptr/)\<[TaskScheduler](../taskscheduler/)\>\&) | Görev yürütmesini belirtilen zamanlayıcıyı kullanarak başlatır. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&) | Yürütülecek bir eylemle [Task](../task/) oluşturur. |
|  [Task](../task/task/)(const [Action](../../system/action/)<>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Bir eylem ve iptal belirteciyle [Task](../task/) oluşturur. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Durumsal bir eylem ve durum nesnesiyle [Task](../task/) oluşturur. |
|  [Task](../task/task/)(const [Action](../../system/action/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&, const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Durumsal eylem, durum ve iptal belirteciyle [Task](../task/) oluşturur. |
|  [Task](../task/task/)() | Başlatılmamış görevler oluşturmak için dahili yapıcı. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| void [Wait](../task/wait/)(const [CancellationToken](../../system.threading/cancellationtoken/)\&) | Görevin iptal desteğiyle tamamlanmasını bekler. |
| void [Wait](../task/wait/)() | Görevin tamamlanmasını bekler. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |
|  [~Task](../task/~task/)() | Yıkıcı. |
## Açıklamalar



Sonuç üreten bir asenkron işlemi temsil eder, .NET'teki System.Threading.Tasks.Task<TResult> gibi 
## Ayrıca Bakınız

* Sınıf [Task](../task/)
* Ad alanı [System::Threading::Tasks](../)
* Kütüphane [Aspose.Slides](../../)