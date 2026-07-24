---
title: ThreadPool
second_title: Aspose.Slides for C++ API Referansı
description: İş parçacığı havuzu tarafından okunmak üzere işleri kuyruğa itmeye izin veren thread pool API'si. Bu, örnek hizmetleri olmayan statik bir türdür. Herhangi bir şekilde örneklerini oluşturmayın.
type: docs
weight: 222
url: /tr/system.threading/threadpool/
---
## ThreadPool sınıf


[Thread](../thread/) havuz API'si, işlerin kuyruğa itilerek işçi iş parçacığı havuzu tarafından okunmasını sağlar. Bu, örnek hizmetleri olmayan statik bir türdür. Herhangi bir şekilde örneklerini oluşturmayın.

```cpp
class ThreadPool : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN da dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN da dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| static void [GetAvailableThreads](./getavailablethreads/)(int\&, int\&) | Kullanılabilir iş parçacığı sayısını alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini sağlar. |
| static [ThreadPoolImpl](../threadpoolimpl/)\& [GetInstance](./getinstance/)() | İşlerin listesini ve diğer parametreleri tutan uygulama örneği. |
| static void [GetMaxThreads](./getmaxthreads/)(int\&, int\&) | Maksimum eşzamanlı iş parçacığı sayısını alır. |
| static void [GetMinThreads](./getminthreads/)(int\&, int\&) | Havuz tarafından oluşturulan minimum iş parçacığı sayısını alır. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| static void [JoinAllThreads](./joinallthreads/)() | Tüm sahip olunan iş parçacıklarını birleştirir. Sonsuza kadar bekler. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını (klonlanmasını) sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| void [operator=](./operator_equal/)(const [ThreadPool](./)\&) | Kopyalama yok. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/)) | Parametresiz geri çağrımı olan iş öğesini kuyruğa ekler. |
| static **bool** [QueueUserWorkItem](./queueuserworkitem/)([WaitCallback](../waitcallback/), const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Parametresiz geri çağrımı olan iş öğesini kuyruğa ekler. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşımlı referans sayacını azaltır. |
| static **bool** [SetMaxThreads](./setmaxthreads/)(int, int) | Havuzun sahip olduğu iş parçacığı sayısını ayarlar. |
| static **bool** [SetMinThreads](./setminthreads/)(int, int) | Havuzun sahip olduğu minimum iş parçacığı sayısını ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n.'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
|  [ThreadPool](./threadpool/)(const [ThreadPool](./)\&) | Kopyalama yok. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |
## Açıklamalar



```cpp
#include "system/threading/thread_pool.h"
#include "system/threading/thread.h"
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>
#include <mutex>
#include <string>
#include <thread>

const std::string &BooleanToString(bool value)
{
  static const std::string True = "True";
  static const std::string False = "False";

  return value ? True : False;
}

int main()
{
  using namespace System::Threading;
  std::mutex m;

  const auto threadsCount = std::thread::hardware_concurrency();

  for (unsigned int i = 0; i < threadsCount; ++i)
  {
    ThreadPool::QueueUserWorkItem([&m](System::SharedPtr<System::Object> object) -> void {
      auto thread = Thread::get_CurrentThread();
      m.lock();
      std::cout << "Background: " << BooleanToString(thread->get_IsBackground()) <<
        ", Thread pool: " << BooleanToString(thread->get_IsThreadPoolThread()) <<
        ", Thread ID: " << thread->get_ManagedThreadId() << std::endl;
      m.unlock();
    });
  }

  ThreadPool::JoinAllThreads();

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
Arka plan: True, İş parçacığı havuzu: True, İş parçacığı ID: 1
Arka plan: True, İş parçacığı havuzu: True, İş parçacığı ID: 3
Arka plan: True, İş parçacığı havuzu: True, İş parçacığı ID: 5
Arka plan: True, İş parçacığı havuzu: True, İş parçacığı ID: 6
Arka plan: True, İş parçacığı havuzu: True, İş parçacığı ID: 9
Arka plan: True, İş parçacığı havuzu: True, İş parçacığı ID: 1
Arka plan: True, İş parçacığı havuzu: True, İş parçacığı ID: 7
Arka plan: True, İş parçacığı havuzu: True, İş parçacığı ID: 2
Arka plan: True, İş parçacığı havuzu: True, İş parçacığı ID: 4
Arka plan: True, İş parçacığı havuzu: True, İş parçacığı ID: 3
Arka plan: True, İş parçacığı havuzu: True, İş parçacığı ID: 12
Arka plan: True, İş parçacığı havuzu: True, İş parçacığı ID: 8
Arka plan: True, İş parçacığı havuzu: True, İş parçacığı ID: 5
Arka plan: True, İş parçacığı havuzu: True, İş parçacığı ID: 6
Arka plan: True, İş parçacığı havuzu: True, İş parçacığı ID: 16
Arka plan: True, İş parçacığı havuzu: True, İş parçacığı ID: 11
*/
```

## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* İsim Uzayı [System::Threading](../)
* Kütüphane [Aspose.Slides](../../)