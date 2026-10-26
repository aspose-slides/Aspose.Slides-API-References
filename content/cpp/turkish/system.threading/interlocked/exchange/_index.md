---
title: Exchange()
second_title: Aspose.Slides için C++ API Referansı
description: "Değişkenin değerini değiştirir: yeni değeri depolar ve depolanmadan hemen önce değişkenin sahip olduğu değeri döndürür."
type: docs
weight: 66
url: /tr/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) method

Değişkenin değerini değiştirir: yeni değeri depolar ve depolanmadan hemen önce değişkenin sahip olduğu değeri döndürür.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Değişken türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| location1 | T\& | Değiştirilecek değişken referansı. |
| value | T | Depolanacak değer. |

### Dönüş Değeri

Değişiklikten hemen önceki değişkenin değeri.

## Interlocked::Exchange(T\&, T) method

Değişkenin değerini değiştirir: yeni değeri depolar ve depolanmadan hemen önce değişkenin sahip olduğu değeri döndürür. Uygulanmadı.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Değişken türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| location1 | T\& | Değiştirilecek değişken referansı. |
| value | T | Depolanacak değer. |

### Dönüş Değeri

Değişiklikten hemen önceki değişkenin değeri.

## Ayrıca Bakınız

* Sınıf [Interlocked](../)
* Ad alanı [System::Threading](../../)
* Kütüphane [Aspose.Slides](../../../)