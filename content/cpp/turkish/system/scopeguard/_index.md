---
title: ScopeGuard
second_title: Aspose.Slides için C++ API Referansı
description: Bir sınıf örneği kapsam dışına çıktığında belirli bir fonksiyon nesnesini çalıştırmak için hizmet sağlayan servis sınıfı.
type: docs
weight: 1886
url: /tr/system/scopeguard/
---
## ScopeGuard struct

Bir sınıf örneği kapsam dışına çıktığında belirli bir fonksiyon nesnesini çalıştırmak için hizmet sağlayan servis sınıfı.

```cpp
template<typename F>class ScopeGuard
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| F | ScopedGuard sınıfının örnekleri tarafından çağrılan fonksiyon nesnesinin türü |

## Metotlar

| Metot | Açıklama |
| --- | --- |
| void [Disable](./disable/)() | Koruma çağrısını devre dışı bırakır. |
| [ScopeGuard](./scopeguard/)(F) | Belirtilen fonksiyon nesnesini çağırmak üzere ayarlanmış bir örnek oluşturur. |
| [~ScopeGuard](./~scopeguard/)() | Yapıcıya geçirilen fonksiyon nesnesini çağırır. |

## Ayrıca Bakınız

* AdAlanı [System](../)
* Kütüphane [Aspose.Slides](../../)