---
title: Thread
second_title: Aspose.Slides for C++ API Referansı
description: "Thread uygulaması. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini asla yığıt üzerinde ya da new operatörüyle oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisi içinde sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 209
url: /tr/system.threading/thread/
---
## Thread sınıfı

[Thread](./) uygulaması. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini asla yığıt (stack) üzerinde veya new operatörüyle oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisi içinde sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class Thread : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| void [Abort](./abort/)() | İş parçacığını iptal eder. Gerçekleştirilmedi. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Sadece dahili amaçlar için. |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentCulture](./get_currentculture/)() | İş parçacığının kültürünü alır. |
| static [System::SharedPtr](../../system/sharedptr/)\<[Thread](./)\> [get_CurrentThread](./get_currentthread/)() | Geçerli iş parçacığını tanımlayan nesneyi alır. |
| [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\> [get_CurrentUICulture](./get_currentuiculture/)() | İş parçacığı tarafından kullanılan kullanıcı arayüzü kültürünü alır. |
| **bool** [get_IsAlive](./get_isalive/)() | İş parçacığının hâlâ çalışıp çalışmadığını kontrol eder. |
| **bool** [get_IsBackground](./get_isbackground/)() | İş parçacığının arka plan olup olmadığını kontrol eder. |
| **bool** [get_IsThreadPoolThread](./get_isthreadpoolthread/)() | İş parçacığının bir iş parçacığı havuzu tarafından sahiplenilip sahiplenmediğini kontrol eder. |
| int [get_ManagedThreadId](./get_managedthreadid/)() const | İş parçacığının kimliğini alır. İşletim sisteminden elde edilebilir, ancak OS iş parçacığı kimliği int sınırlarını aşarsa, iş parçacığı kimlikleri çakışabilir. |
| [System::String](../../system/string/) [get_Name](./get_name/)() | İş parçacığı adını alır. |
| [ThreadState](../threadstate/) [get_ThreadState](./get_threadstate/)() | İş parçacığı durumunu alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| static int [GetCurrentThreadId](./getcurrentthreadid/)() | Geçerli iş parçacığının kimliğini alır. |
| int [GetHashCode](./gethashcode/)() const override |  |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| void [Interrupt](./interrupt/)() | İş parçacığını kesintiye uğratır. Gerçekleştirilmedi. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneğini temsil edip etmediğini kontrol eder. C# 'is' operatörünün analoğu. |
| void [Join](./join/)() | Yönetilen iş parçacığına katılır. Gerekirse sınırsız bekleme yürütür. |
| **bool** [Join](./join/)(int) | Yönetilen iş parçacığına katılır. Sınırlı bekleme yürütür. |
| **bool** [Join](./join/)([TimeSpan](../../system/timespan/)) | Yönetilen iş parçacığına katılır. Sınırlı bekleme yürütür. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetmen nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını sağlar. |
| static void [MemoryBarrier](./memorybarrier/)() | Bellek erişimini senkronize eder. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Thread](./)\& [operator=](./operator_equal/)(const [Thread](./)\&) | Farklı bir iş parçacığından TLS verilerini kopyalar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumları için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [set_CurrentCulture](./set_currentculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | İş parçacığının kültürünü ayarlar. |
| void [set_CurrentUICulture](./set_currentuiculture/)(const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | İş parçacığı tarafından kullanılan kullanıcı arayüzü kültürünü ayarlar. |
| void [set_IsBackground](./set_isbackground/)(**bool**) | İş parçacığını arka plan ya da ön plana ayarlar. |
| void [set_Name](./set_name/)(const [System::String](../../system/string/)\&) | İş parçacığı adını ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (shared yerine) olarak ayarlar. Kapsayıcılardaki göstericileri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| static void [Sleep](./sleep/)(int) | Geçerli iş parçacığını belirtilen zaman aşımı süresi için durdurur. |
| static void [Sleep](./sleep/)([TimeSpan](../../system/timespan/)) | Geçerli iş parçacığını belirtilen zaman aşımı süresi için durdurur. |
| static void [SpinWait](./spinwait/)(int) | Belirli sayıda döngü iterasyonu için bekler. |
| void [Start](./start/)() | Boş argüman nesnesi kullanarak iş parçacığını başlatır. |
| void [Start](./start/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | İş parçacığını başlatır. |
|  [Thread](./thread/)() | Kurucu. |
|  [Thread](./thread/)([ThreadStart](../threadstart/)) | Kurucu. |
|  [Thread](./thread/)([ParameterizedThreadStart](../parameterizedthreadstart/)) | Kurucu. |
|  [Thread](./thread/)([Thread](./)\&) | Kopya kurucu. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetmen nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| static **bool** [Yield](./yield/)() | İş parçacığını devre dışı bırakır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
| virtual  [~Thread](./~thread/)() | Yıkıcı. |

## Açıklamalar

```cpp
#include "system/threading/thread.h"
#include "system/smart_ptr.h"

int main()
{
  auto thread = System::MakeObject<System::Threading::Thread>([]()
  {
    std::cout << "Child thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;
    System::Threading::Thread::Sleep(200);
  });

  std::cout << "Main thread ID: " << System::Threading::Thread::GetCurrentThreadId() << std::endl;

  thread->Start();
  thread->Join();

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
Ana iş parçacığı kimliği: 2
Çocuk iş parçacığı kimliği: 1
*/
```

## Diğer Bağlantılar

* Sınıf [Object](../../system/object/)
* Ad alanı [System::Threading](../)
* Kütüphane [Aspose.Slides](../../)