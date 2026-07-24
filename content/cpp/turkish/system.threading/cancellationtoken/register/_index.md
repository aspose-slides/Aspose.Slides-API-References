---
title: Register()
second_title: Aspose.Slides for C++ API Referansı
description: İptal istendiğinde çalıştırılacak bir geri aramayı kaydeder.
type: docs
weight: 40
url: /tr/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const method


İptal istenildiğinde çağrılacak bir geri arama (callback) kaydeder.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | İptal istendiğinde yürütülecek Action<>. |

### Dönüş Değeri

callback'i kaldırmak için kullanılabilecek bir [CancellationTokenRegistration](../../cancellationtokenregistration/) nesnesi.
## Açıklamalar



İptal zaten istenmişse, geri arama (callback) hemen çağrılır. 

[CancellationTokenSource](../../cancellationtokensource/) üzerinde Cancel() çağıran iş parçacığında yürütüleceği için geri arama kısa ömürlü ve engelleyici olmamalıdır. 

## İlgili

* Typedef [Action](../../../system/action/)
* Sınıf [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Sınıf [CancellationToken](../)
* Ad Alanı [System::Threading](../../)
* Kütüphane [Aspose.Slides](../../../)