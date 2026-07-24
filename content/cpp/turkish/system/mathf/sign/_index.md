---
title: Sign()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen imzalı tam sayı değerinin işaretini belirler.
type: docs
weight: 274
url: /tr/system/mathf/sign/
---
## MathF::Sign(T) yöntemi


Belirtilen imzalı tam sayı değerinin işaretini belirler.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::MathF::Sign(T value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Tamsayı imzalı tür |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | T | İşaretinin belirleneceği değer |

### Dönüş Değeri

- 1 eğer **value** 0'dan küçükse; 0 eğer **value** 0'a eşitse; 1 eğer **value** 0'dan büyükse

## MathF::Sign(T) yöntemi


Belirtilen kayan noktalı değerinin işaretini belirler.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::MathF::Sign(T value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Argümanın kayan nokta türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | T | İşaretinin belirleneceği değer |

### Dönüş Değeri

- 1 eğer **value** 0'dan küçükse; 0 eğer **value** 0'a eşitse; 1 eğer **value** 0'dan büyükse

## Ayrıca Bakınız

* Yapı [MathF](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)