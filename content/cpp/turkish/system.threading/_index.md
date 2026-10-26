---
title: "System::Threading"
second_title: Aspose.Slides for C++ API Referansı
description: 
type: docs
weight: 1002
url: /tr/system.threading/
---
## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | Otomatik olarak sıfırlanan, bekleyen iş parçacığını bildiren olay. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tipin örneğini yığıt üzerinde ya da new operatörüyle asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [CancellationToken](./cancellationtoken/) | İşlemlerin iptal edilmesi gerektiğine ilişkin bildirimi yayar. Bu sınıf, iş parçacıkları arasında iş birliğine dayalı iptal mekanizması sağlar ve bir iş parçacığının diğerlerine bir işlemin iptal edilmesi gerektiğini bildirmesine olanak tanır. |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | İptal tokeni geri çağırma kaydını temsil eder. |
| [CancellationTokenSource](./cancellationtokensource/) | İptal bildirimlerini tetiklemek için kullanılabilen bir iptal token kaynağı. |
| [Details_SemaphoreFullException](./details_semaphorefullexception/) |  |
| [Details_SynchronizationLockException](./details_synchronizationlockexception/) |  |
| [Details_ThreadAbortException](./details_threadabortexception/) |  |
| [Details_ThreadInterruptedException](./details_threadinterruptedexception/) |  |
| [Details_ThreadStateException](./details_threadstateexception/) |  |
| [EventWaitHandle](./eventwaithandle/) | Bekleyen iş parçacığına gönderilebilen olay. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tipin örneğini yığıt üzerinde ya da new operatörüyle asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [Interlocked](./interlocked/) | İş parçacığı güvenli işlemler için API sağlar. Bu, örnek hizmeti olmayan statik bir türdür. Onun örneklerini hiçbir şekilde oluşturmayın. |
| [ManualResetEvent](./manualresetevent/) | Otomatik olarak sıfırlamayan, bekleyen iş parçacığını bildiren olay. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tipin örneğini yığıt üzerinde ya da new operatörüyle asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [Monitor](./monitor/) | [Monitor](./monitor/) sınıfı nesnelere erişimi senkronize eden bir mekanizma sağlar. |
| [Mutex](./mutex/) | [Mutex](./mutex/) uygulaması. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tipin örneğini yığıt üzerinde ya da new operatörüyle asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [Semaphore](./semaphore/) | [Semaphore](./semaphore/) uygulaması. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tipin örneğini yığıt üzerinde ya da new operatörüyle asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [SynchronizationContext](./synchronizationcontext/) | Çeşitli senkronizasyon işlemleri arasında bir senkronizasyon bağlamını yaymak için temel işlevselliği sağlar. |
| [Thread](./thread/) | [Thread](./thread/) uygulaması. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tipin örneğini yığıt üzerinde ya da new operatörüyle asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [ThreadPool](./threadpool/) | [Thread](./thread/) havuzu, işleri kuyruğa iterek çalışan iş parçacığı havuzunun okumasına izin veren bir API sağlar. Bu, örnek hizmeti olmayan bir statik türdür. Onun örneklerini hiçbir şekilde oluşturmayın. |
| [ThreadPoolImpl](./threadpoolimpl/) | [Thread](./thread/) havuzunun iç verileri. Bu, erişim işlev(leri) aracılığıyla bellek yönetimi yapılan bir tek örnek (singleton) türdür. Onun örneklerini doğrudan oluşturmayın. |
| [Timer](./timer/) | [Timer](./timer/) sınıfı, gecikmeden sonra işi ayrı bir iş parçacığında çalıştırır. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tipin örneğini yığıt üzerinde ya da new operatörüyle asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |
| [TimerQueue](./timerqueue/) | [Timer](./timer/) nesnelerini yöneten kuyruk. Bu sadece bir uygulamadır. [Timer](./timer/) nesneleri kendileri kaydolur, bunları kullanmak için bir şey yapmanız gerekmez - bunun yerine [Timer](./timer/) sınıf API'sini kullanın. Bu, erişim işlev(leri) aracılığıyla bellek yönetimi yapılan bir tek örnek (singleton) türdür. Onun örneklerini doğrudan oluşturmayın. |
| [WaitHandle](./waithandle/) | Bekleme ilkel temel sınıfı. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tipin örneğini yığıt üzerinde ya da new operatörüyle asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. |

## Yapılar

| Yapı | Açıklama |
| --- | --- |
| [Timeout](./timeout/) | [Threading](./) zaman aşımı özel değerleri. Bu, örnek hizmeti olmayan statik bir türdür. Onun örneklerini hiçbir şekilde oluşturmayın. |

## Numaralandırmalar

| Enum | Açıklama |
| --- | --- |
| [ApartmentState](./apartmentstate/) | İş parçacığının apartman durumunu ayarlar. |
| [EventResetMode](./eventresetmode/) | Olay durumunun nasıl sıfırlandığını gösterir. |
| [ThreadState](./threadstate/) | İş parçacığının durumu. |

## Tip Tanımları

| Typedef | Açıklama |
| --- | --- |
| [ThreadStateException](./threadstateexception/) |  |
| [SemaphoreFullException](./semaphorefullexception/) |  |
| [SynchronizationLockException](./synchronizationlockexception/) |  |
| [ThreadAbortException](./threadabortexception/) |  |
| [ThreadInterruptedException](./threadinterruptedexception/) |  |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | [Thread](./thread/) tek parametreli fonksiyon. |
| [ThreadStart](./threadstart/) | [Thread](./thread/) parametresiz fonksiyon. |
| [WaitCallback](./waitcallback/) | Yer olduğunda yürütülecek geri çağırma öğesi. |
| [TimerCallback](./timercallback/) | Zamanlayıcı tarafından çağrılacak geri çağırma fonksiyonu. |
| [wait_handle_t](./wait_handle_t/) | Handle türü. |