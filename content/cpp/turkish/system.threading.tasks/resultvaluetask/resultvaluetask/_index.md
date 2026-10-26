---
title: ResultValueTask()
second_title: Aspose.Slides için C++ API Referansı
description: Boş, başlatılmamış bir ResultValueTask oluşturur.
type: docs
weight: 1
url: /tr/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() yapıcı

Boş, başlatılmamış bir [ResultValueTask](../) oluşturur.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## Açıklamalar

Görev tamamlanmamış ve sonuç içermez. Sonucu almaya çalışmak bir istisna fırlatır. 

## ResultValueTask::ResultValueTask(const T\&) yapıcı

Belirtilen sonuçla tamamlanmış bir [ResultValueTask](../) oluşturur.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| result | const T\& | Tamamlanmış bir göreve sarmalanacak sonuç değeri. |
## Açıklamalar

Bu, değeri hemen döndüren başarılı bir şekilde tamamlanmış bir görev oluşturur. 

## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) yapıcı

ResultTask<T> için paylaşımlı bir işaretçiden bir [ResultValueTask](../) oluşturur.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| task | const [RTaskPtr](../../../system/rtaskptr/)\<T\>\& | Sarılan görev. Boş bir görev için null olabilir. |
## Açıklamalar

[ResultValueTask](../) verilen görevin durumunu ve sonucunu temsil eder. 

## İlgili

* Tip Tanımı [RTaskPtr](../../../system/rtaskptr/)
* Sınıf [ResultValueTask](../)
* İsim Alanı [System::Threading::Tasks](../../)
* Kütüphane [Aspose.Slides](../../../)