---
title: CoalesceAssign()
second_title: Aspose.Slides for C++ API Referansı
description: "'??=' operatörünün uygulama çevirisi."
type: docs
weight: 183
url: /tr/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) metodu

‘??=’ operatörünün uygulama çevirisi.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T0 | LHS değer tipi. |
| T1 | RHS ifadesini kapsülleyen lambda tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | T0\& | LHS değeri. |
| func | T1 | RHS ifadesi. |

### Dönüş değeri

LHS değeri null değilse, LHS'yi döndürür; aksi takdirde RHS ifadesini hesaplar ve sonucu döndürür.

## Ayrıca bakınız

* Sınıf [ObjectExt](../)
* İsim alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)