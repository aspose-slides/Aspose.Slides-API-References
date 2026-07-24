---
title: Delay()
second_title: Aspose.Slides for C++ API Referansı
description: Zaman gecikmesinden sonra tamamlanan bir görev oluşturur.
type: docs
weight: 105
url: /tr/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) fonksiyon


Belirtilen zaman gecikmesinden sonra tamamlanan bir görev oluşturur.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Dönüş görevinin tamamlanmadan önce bekleyeceği milisaniye sayısı, -1 ise süresiz bekleme. |

### Dönüş Değeri

Zaman gecikmesini temsil eden bir görev.

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) fonksiyon


Belirtilen zaman gecikmesinden sonra tamamlanan ve iptal edilebilen bir görev oluşturur.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Dönüş görevinin tamamlanmadan önce bekleyeceği milisaniye sayısı, -1 ise süresiz bekleme. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Gecikmeyi iptal etmek için kullanılabilecek iptal belirteci. |

### Dönüş Değeri

Zaman gecikmesini temsil eden bir görev.

## İlgili

* Tip Tanımı [TaskPtr](../../system/taskptr/)
* Sınıf [CancellationToken](../../system.threading/cancellationtoken/)
* Ad Alanı [System::Threading::Tasks](../)
* Kütüphane [Aspose.Slides](../../)