---
title: "System::Threading::Tasks"
second_title: Aspose.Slides için C++ API Referansı
description: 
type: docs
weight: 1015
url: /tr/system.threading.tasks/
---
## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [Parallel](./parallel/) | Paralel döngüler ve bölgeler için destek sağlar. |
| [ParallelLoopResult](./parallelloopresult/) | Bir [Parallel](./parallel/) döngüsünün tamamlama durumunu sağlar. |
| [ParallelOptions](./paralleloptions/) | [Parallel](./parallel/) sınıfındaki yöntemlerin çalışma şeklini yapılandıran seçenekleri saklar. |
| [ResultTask](./resulttask/) | Tamamlandığında bir sonuç değeri döndüren bir [Task](./task/) özelleştirmesi. |
| [ResultValueTask](./resultvaluetask/) | Doğrudan bir sonuç değeri veya bir ResultTask<T> sarabilen hibrit görev benzeri bir türü temsil eder. |
| [Task](./task/) | Await edilebilen ve diğer görevlerle birleştirilebilen bir asenkron işlemi temsil eder. |
| [TaskScheduler](./taskscheduler/) | Görevleri iş parçacıklarına kuyruğa ekleme işinin düşük seviyeli işini yöneten bir nesneyi temsil eder. |
| [ValueTask](./valuetask/) | Asenkron bir işlemin await edilebilen sonucunu sağlar. |
## Fonksiyonlar

| Fonksiyon | Açıklama |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | Bir zaman gecikmesinden sonra tamamlanan bir görev oluşturur. |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Bir zaman gecikmesinden sonra tamamlanan ve iptal edilebilen bir görev oluşturur. |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | Belirtilen token ile iptal edilerek tamamlanmış bir görev oluşturur. |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Belirtilen bir istisna ile tamamlanmış bir görev oluşturur. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | Belirtilen bir istisna ve sonuç türüyle tamamlanmış bir görev oluşturur. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | Belirtilen sonuç ile başarıyla tamamlanmış bir görev oluşturur. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | Belirtilen işi iş parçacığı havuzunda çalıştırmak üzere kuyruğa ekler ve bu iş için bir [Task](./task/) tanıtıcısı döndürür. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Belirtilen işi iş parçacığı havuzunda çalıştırmak üzere kuyruğa ekler ve bu iş için bir [Task](./task/) tanıtıcısı döndürür. |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | Belirtilen işi iş parçacığı havuzunda çalıştırmak üzere kuyruğa ekler ve işlev tarafından döndürülen [Task](./task/) için bir vekil nesne döndürür. |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | Belirtilen işi iş parçacığı havuzunda çalıştırmak üzere kuyruğa ekler ve bu iş için bir Task<TResult> tanıtıcısı döndürür. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Sağlanan tüm [Task](./task/) nesnelerinin yürütmesini tamamlamasını bekler. |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Sağlanan tüm [Task](./task/) nesnelerinin yürütmesini tamamlamasını bekler. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | Sağlanan [Task](./task/) nesnelerinden herhangi birinin yürütmesini tamamlamasını bekler. |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Sağlanan [Task](./task/) nesnelerinden herhangi birinin yürütmesini tamamlamasını bekler. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Sağlanan tüm görevler tamamlandığında sona erecek bir görev oluşturur. |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Sağlanan tüm görevler tamamlandığında sona erecek bir görev oluşturur. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Sağlanan tüm görevler tamamlandığında sona erecek bir görev oluşturur. |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Sağlanan tüm görevler tamamlandığında sona erecek bir görev oluşturur. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | Sağlanan görevlerden herhangi biri tamamlandığında sona erecek bir görev oluşturur. |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | Sağlanan görevlerden herhangi biri tamamlandığında sona erecek bir görev oluşturur. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | Sağlanan görevlerden herhangi biri tamamlandığında sona erecek bir görev oluşturur. |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | Sağlanan görevlerden herhangi biri tamamlandığında sona erecek bir görev oluşturur. |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | Await edildiğinde mevcut bağlama asenkron olarak geri veren bir await edilebilir görev oluşturur. |
## Enumlar

| Enum | Açıklama |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |