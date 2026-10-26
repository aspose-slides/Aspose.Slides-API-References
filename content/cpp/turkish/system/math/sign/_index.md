---
title: Sign()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen imzalı bütün sayı değerinin işaretini belirler.
type: docs
weight: 274
url: /tr/system/math/sign/
---
## Math::Sign(T) metodu

Belirtilen imzalı bütün sayı değerinin işaretini belirler.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::Math::Sign(T value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İmzalı bütün sayı türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | T | İşaretinin belirlenmek istendiği değer |

### Dönüş Değeri

- 1 eğer **value** 0’dan küçüktür; 0 eğer **value** 0’a eşittir; 1 eğer **value** 0’dan büyüktür

## Math::Sign(T) metodu

Belirtilen kayan nokta değerinin işaretini belirler.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::Math::Sign(T value)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Argümanın kayan nokta türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | T | İşaretinin belirlenmek istendiği değer |

### Dönüş Değeri

- 1 eğer **value** 0’dan küçüktür; 0 eğer **value** 0’a eşittir; 1 eğer **value** 0’dan büyüktür

## Math::Sign(const Decimal\&) metodu

Belirtilen ondalık değerinin işaretini belirler.

```cpp
static int System::Math::Sign(const Decimal &value)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | İşaretinin belirlenmek istendiği değer |

### Dönüş Değeri

- 1 eğer **value** 0’dan küçüktür; 0 eğer **value** 0’a eşittir; 1 eğer **value** 0’dan büyüktür

## Ayrıca Bakınız

* Sınıf [Decimal](../../decimal/)
* Yapı [Math](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)