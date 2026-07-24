---
title: TimerQueue
second_title: Aspose.Slides for C++ API Referansı
description: Timer nesnelerini işleyen kuyruk. Bu sadece bir uygulamadır. Timer nesneleri kendiliğinden orada kaydolur, onları kullanmak için bunu yapmanız gerekmez - bunun yerine Timer sınıfı API'sini kullanın. Bu, erişim işlev(ler)i tarafından bellek yönetimi yapılan bir tek örnek tipidir. Onu doğrudan örneklememeniz gerekir.
type: docs
weight: 261
url: /tr/system.threading/timerqueue/
---
## TimerQueue sınıfı

[Timer](../timer/) nesnelerini işleyen kuyruk. Bu sadece bir uygulamadır. [Timer](../timer/) nesneleri kendiliğinden kayıt olur, onları kullanmak için bunu yapmanız gerekmez - bunun yerine [Timer](../timer/) sınıf API'sini kullanın. Bu, bellek yönetimi erişim işlev(ler)i tarafından yapılan bir tek örnek tipi. Onu doğrudan örneklememeniz gerekir.

```cpp
class TimerQueue
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | Kuyruktaki zamanlayıcıyı kaydeder. |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | Kuyruktan zamanlayıcıyı siler. |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | Uygulama tek örnek. |
| static void [JoinWorkerThread](./joinworkerthread/)() | İşçi iş parçacığına katılır. Gerektiğinde sonsuz bekler. |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | Kopyalama yok. |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | Kopyalama yok. |
## Ayrıca Bakınız

* Ad alanı [System::Threading](../)
* Kütüphane [Aspose.Slides](../../)