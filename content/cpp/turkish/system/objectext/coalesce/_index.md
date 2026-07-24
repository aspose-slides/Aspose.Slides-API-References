---
title: Coalesce()
second_title: Aspose.Slides for C++ API Referansı
description: null olmayan tipler için '??' operatörünün çevirisinin uygulanması.
type: docs
weight: 170
url: /tr/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) metot


Implementation of '??' operator translation for non-nullable types.

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T0 | LHS değer tipi. |
| T1 | RHS ifadesini kapsülleyen lambda tipi. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | T0 | LHS değeri. |
| func | T1 | RHS ifadesi. |

### Dönüş değeri

If LHS value is not null, returns LHS, otherwise calculates RHS expression and returns result.

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) metot


Implementation of '??' operator translation for nullable types.

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T0 | LHS değer tipi. |
| T1 | RHS ifadesini kapsülleyen lambda tipi. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | LHS değeri. |
| func | T1 | RHS ifadesi. |

### Dönüş değeri

If LHS value is not null, returns LHS, otherwise calculates RHS expression and returns result.

## Ayrıca bakınız

* Sınıf [ObjectExt](../)
* Sınıf [Nullable](../../nullable/)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)