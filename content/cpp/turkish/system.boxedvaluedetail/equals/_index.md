---
title: Equals()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen değerin eşitliğini operator==() kullanarak belirler.
type: docs
weight: 66
url: /tr/system.boxedvaluedetail/equals/
---
## System::BoxedValueDetail::Equals(T, T) fonksiyon

Belirtilen değerin eşitliğini [operator==()](../../system/operator_equal_equal/) kullanarak belirler.

```cpp
template<typename T> std::enable_if<detail::has_operator_equal<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| The | karşılaştırılan değerlerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value1 | T | ilk karşılaştırma öğesi |
| value2 | T | ikinci karşılaştırma öğesi |

### Dönüş Değeri

Belirtilen değer [operator==()](../../system/operator_equal_equal/) tarafından belirlenen eşitlik koşulunu sağlarsa True, aksi takdirde - false

## System::BoxedValueDetail::Equals(T, T) fonksiyon

Belirtilen değerin eşitliğini [System::Object::Equals()](../../system/object/equals/) yöntemi kullanarak belirler.

```cpp
template<typename T> std::enable_if<detail::has_only_method_equals<T>::value, bool>::type System::BoxedValueDetail::Equals(T value1, T value2)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| The | karşılaştırılan değerlerin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value1 | T | ilk karşılaştırma öğesi |
| value2 | T | ikinci karşılaştırma öğesi |

### Dönüş Değeri

Belirtilen değer [Equals()](./) yöntemi tarafından belirlenen eşitlik koşulunu sağlarsa True, aksi takdirde - false

## Diğer Bilgiler

* Ad Alanı [System::BoxedValueDetail](../)
* Kütüphane [Aspose.Slides](../../)