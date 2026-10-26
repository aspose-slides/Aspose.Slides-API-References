---
title: operator==()
second_title: Aspose.Slides for C++ API Referansı
description: ResultValueTask için eşitlik operatörü.
type: docs
weight: 131
url: /tr/system.threading.tasks/resultvaluetask/operator_equal_equal/
---
## ResultValueTask::operator==(const ResultValueTask\&) const metodu

Eşitlik operatörü [ResultValueTask](../) için.

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | const [ResultValueTask](../)\& | Bu örnekle karşılaştırmak için diğer [ResultValueTask](../). |

### Dönüş Değeri

bool True eğer her iki görev de aynı sonuç değerine sahipse ya da aynı temel göreve referans veriyorsa; aksi takdirde, false.

## Açıklamalar

Eğer herhangi bir örnek doğrudan bir sonuç değeri içeriyorsa, sonuçları doğrudan karşılaştırır. Aksi takdirde, temel görev işaretçilerini karşılaştırır.

## Ayrıca Bakınız

* Sınıf [ResultValueTask](../)
* Ad alanı [System::Threading::Tasks](../../)
* Kütüphane [Aspose.Slides](../../../)