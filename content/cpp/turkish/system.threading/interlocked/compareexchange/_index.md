---
title: CompareExchange()
second_title: Aspose.Slides for C++ API Referansı
description: "Değişken üzerindeki değeri karşılıklı değiştirir: değişkenin belirli bir değere eşit olup olmadığını kontrol eder ve yalnızca saklanan değer beklenenle eşleşiyorsa yeni değeri depolar."
type: docs
weight: 79
url: /tr/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(T&, T, T) metodu

Değişken üzerindeki değeri karşılıklı değiştirir: değişkenin belirli bir değere eşit olup olmadığını kontrol eder ve yalnızca saklanan değer beklenenle eşleşiyorsa yeni değeri depolar.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Değişken tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| location1 | T& | Değiştirilecek değişken referansı. |
| value | T | Depolanacak değer. |
| comparand | T | Değiş tokuş öncesinde değişkenin değeriyle karşılaştırılacak değer. |

### Dönen Değer

Değişimin başında değişkenin değeri, değiştirildiği ya da edilmediği fark etmeksizin.

## Interlocked::CompareExchange(T&, T, T) metodu

Değişken üzerindeki değeri karşılıklı değiştirir: değişkenin belirli bir değere eşit olup olmadığını kontrol eder ve yalnızca saklanan değer beklenenle eşleşiyorsa yeni değeri depolar. Henüz uygulanmadı.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Değişken tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| location1 | T& | Değiştirilecek değişken referansı. |
| value | T | Depolanacak değer. |
| comparand | T | Değiş tokuş öncesinde değişkenin değeriyle karşılaştırılacak değer. |

### Dönen Değer

Değişimin başında değişkenin değeri, değiştirildiği ya da edilmediği fark etmeksizin.

## Interlocked::CompareExchange(int32_t&, int32_t, int32_t, bool&) metodu

Değişken üzerindeki değeri karşılıklı değiştirir: değişkenin belirli bir değere eşit olup olmadığını kontrol eder ve yalnızca saklanan değer beklenenle eşleşiyorsa yeni değeri depolar.

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| location1 | **int32_t**& | Değiştirilecek değişken referansı. |
| value | **int32_t** | Depolanacak değer. |
| comparand | **int32_t** | Değiş tokuş öncesinde değişkenin değeriyle karşılaştırılacak değer. |
| succeeded | **bool**& | Değiş tokuş gerçekleştiyse true, aksi takdirde false olarak ayarlanan değişken referansı. |

### Dönen Değer

Değişimin başında değişkenin değeri, değiştirildiği ya da edilmediği fark etmeksizin.

## Ayrıca Bakınız

* Sınıf [Interlocked](../)
* İsim Alanı [System::Threading](../../)
* Kütüphane [Aspose.Slides](../../../)