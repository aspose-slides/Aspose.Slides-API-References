---
title: MakeScopeGuard()
second_title: Aspose.Slides for C++ API Referansı
description: ScopedGuard sınıfının örneklerini oluşturan bir fabrika işlevi.
type: docs
weight: 2809
url: /tr/system/makescopeguard/
---
## System::MakeScopeGuard(F) işlevi


ScopedGuard sınıfının örneklerini oluşturan bir fabrika işlevi.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| The | oluşturulan ScopedGuard nesnesi tarafından çağrılacak işlev nesnesinin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| f | F | ScopedGuard sınıfının yapıcısına geçirilecek işlev nesnesi. |

### Dönüş Değeri

ScopedGuard sınıfının yeni bir örneği

## Diğer Bağlantılar

* Yapı [ScopeGuard](../scopeguard/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)