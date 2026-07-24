---
title: ResultTask()
second_title: Aspose.Slides for C++ API Referansı
description: Bir değer döndüren bir fonksiyon ile bir ResultTask oluşturur.
type: docs
weight: 1
url: /tr/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) constructor

Bir değer döndüren fonksiyon ile bir [ResultTask](../) oluşturur.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | Asenkron olarak çalıştırılacak ve bir sonuç döndüren fonksiyon |

## ResultTask::ResultTask() constructor

Dahili uygulama. Kullanıcı kodu için değil.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## Açıklamalar

Başlatılmamış sonuç görevleri oluşturmak için iç yapıcı

## ResultTask::ResultTask(const T\&) constructor

Belirtilen sonuçla sonuç görevleri oluşturmak için iç yapıcı.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## Ayrıca Bakınız

* Class [Func](../../../system/func/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)