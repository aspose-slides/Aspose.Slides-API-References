---
title: CoalesceInternal()
second_title: Aspose.Slides for C++ API Referansı
description: Null olmayan tipler için '??' operatörünün çevirisinin uygulanması. RT2'nin RT1'e dönüştürülebilir olduğu durum için aşırı yük.
type: docs
weight: 157
url: /tr/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) metodu

Null olmayan tipler için '??' operatörünün çevirisinin uygulanması. RT2'nin RT1'e dönüştürülebilir olduğu durum için aşırı yük.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T0 | LHS değer tipi. |
| T1 | RHS ifadesini kapsayan lambda tipi. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | RT1 | LHS değeri. |
| func | F | RHS ifadesi. |

### Dönüş Değeri

LHS değeri null değilse, LHS döndürülür; aksi takdirde RHS ifadesi hesaplanır ve sonuç döndürülür.

## İlgili

* Sınıf [ObjectExt](../)
* İsim alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)