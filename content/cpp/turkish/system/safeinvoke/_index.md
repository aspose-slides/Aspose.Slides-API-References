---
title: SafeInvoke()
second_title: Aspose.Slides için C++ API Referansı
description: '?.' operatörünün çevirisi uygulanması.
type: docs
weight: 2653
url: /tr/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) fonksiyon


'?.' operatörünün çevirisi uygulanması.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T0 | ifade tipi. |
| T1 | ‘WhenTrue’ ifadesini kapsayan lambda tipi. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| expr | T0\&& | ifade değeri. |
| func | T1\&& | ‘WhenTrue’ ifadesi funktöre bağlanmıştır. |

### Dönüş Değeri

Eğer expr değeri null değilse, func değerini birinci argüman olarak çağırarak döndürür, aksi takdirde null döndürür.

## Ayrıca Bakınız

* AdAlanı [System](../)
* Kütüphane [Aspose.Slides](../../)