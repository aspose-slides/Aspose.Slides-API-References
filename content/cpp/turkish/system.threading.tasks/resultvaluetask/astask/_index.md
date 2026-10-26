---
title: AsTask()
second_title: Aspose.Slides C++ için API Referansı
description: Bu ResultValueTask öğesini ResultTask<T>'ye ortak bir işaretçiye dönüştürür.
type: docs
weight: 79
url: /tr/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const yöntemi

Bu [ResultValueTask](../) öğesini ResultTask<T>'ye ortak bir işaretçiye dönüştürür.

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```

### Dönüş Değeri

RTaskPtr<T> Bu işlemi temsil eden ResultTask<T>'ye işaret eden ortak bir işaretçi.

## Açıklamalar

Eğer [ResultValueTask](../) doğrudan bir sonuç içeriyorsa, bu sonuçla tamamlanmış bir görev oluşturur. Eğer bir görev içeriyorsa, o göreve işaret eden bir ortak işaretçi döndürür.

## Ayrıca Bakınız

* Tip Tanımı [RTaskPtr](../../../system/rtaskptr/)
* Sınıf [ResultValueTask](../)
* Ad alanı [System::Threading::Tasks](../../)
* Kütüphane [Aspose.Slides](../../../)