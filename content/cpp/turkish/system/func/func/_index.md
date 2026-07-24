---
title: Func()
second_title: Aspose.Slides for C++ API Referansı
description: null-Func oluşturan varsayılan yapıcı.
type: docs
weight: 1
url: /tr/system/func/func/
---
## Func::Func() yapıcı


Varsayılan yapıcı, null-Func oluşturur.

```cpp
System::Func<Args>::Func()
```

## Func::Func(T\&&) yapıcı


[Func](../) nesnesini oluşturan ve ona (gerçek geri çağırma ya da nullptr) değer atayan yapıcı.

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Argüman türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg | T\&& | Argüman. |

## Func::Func(const Func\&) yapıcı


Kopya yapıcı.

```cpp
System::Func<Args>::Func(const Func &func)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) veri kopyalamak için. |

## Func::Func(Func\&&) yapıcı


Taşıma yapıcı.

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) veri taşımak için. |

## Ayrıca Bakınız

* Sınıf [Func](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)