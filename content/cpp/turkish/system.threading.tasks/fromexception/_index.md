---
title: FromException()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen bir istisna ile tamamlanmış bir görev oluşturur.
type: docs
weight: 131
url: /tr/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) function

Belirtilen bir istisna ile tamamlanmış bir görev oluşturur.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | Görevi tamamlamak için kullanılacak istisna. |

### Dönüş Değeri

Hata durumunda olan bir görev.

## System::Threading::Tasks::FromException(const Exception\&) function

Belirtilen bir istisna ve sonuç türü ile tamamlanmış bir görev oluşturur.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TResult | Görevin sonucunun türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | Görevi tamamlamak için kullanılacak istisna. |

### Dönüş Değeri

Belirtilen sonuç türüne sahip hata durumunda olan bir görev.

## Ayrıca Bakınız

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* İsim Uzayı [System::Threading::Tasks](../)
* Kütüphane [Aspose.Slides](../../)