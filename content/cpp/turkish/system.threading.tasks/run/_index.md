---
title: Run()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen işi iş parçacığı havuzunda çalıştırmak için kuyruğa ekler ve bu iş için bir Task tutamağı döndürür.
type: docs
weight: 157
url: /tr/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) fonksiyon

Belirtilen işi iş parçacığı havuzunda çalıştırmak için kuyruğa ekler ve bu iş için bir [Task](../task/) tutamağı döndürür.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Asenkron olarak yürütülecek iş. |

### Dönüş Değeri

İş parçacığı havuzunda yürütülmek üzere kuyruğa eklenen işi temsil eden bir [Task](../task/).

## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) fonksiyon

Belirtilen işi iş parçacığı havuzunda çalıştırmak için kuyruğa ekler ve bu iş için bir [Task](../task/) tutamağı döndürür.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| action | const [Action](../../system/action/)<>\& | Asenkron olarak yürütülecek iş. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Henüz başlamamışsa işi iptal etmek için kullanılabilecek bir iptal belirteci. |

### Dönüş Değeri

İş parçacığı havuzunda yürütülmek üzere kuyruğa eklenen işi temsil eden bir [Task](../task/).

## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) fonksiyon

Belirtilen işi iş parçacığı havuzunda çalıştırmak için kuyruğa ekler ve işlevin döndürdüğü [Task](../task/) için bir proxy döndürür.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<[TaskPtr](../../system/taskptr/)\>\& | Asenkron olarak yürütülecek iş, bir [Task](../task/) döndürür. |

### Dönüş Değeri

İşlevin döndürdüğü [Task](../task/) için bir proxy temsil eden bir [Task](../task/).

## System::Threading::Tasks::Run(const Func\<TResult\>\&) fonksiyon

Belirtilen işi iş parçacığı havuzunda çalıştırmak için kuyruğa ekler ve bu iş için bir Task<TResult> tutamağı döndürür.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TResult | Görev tarafından döndürülen sonucun türü. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| function | const [Func](../../system/func/)\<TResult\>\& | Asenkron olarak yürütülecek iş. |

### Dönüş Değeri

İş parçacığı havuzunda yürütülmek üzere kuyruğa eklenen işi temsil eden bir Task<TResult>.

## İlgili

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Sınıf [CancellationToken](../../system.threading/cancellationtoken/)
* Sınıf [Func](../../system/func/)
* Ad alanı [System::Threading::Tasks](../)
* Kütüphane [Aspose.Slides](../../)