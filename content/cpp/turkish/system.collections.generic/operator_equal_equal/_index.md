---
title: operator==()
second_title: Aspose.Slides for C++ API Referansı
description: İki anahtar-değer çiftini 'equals' semantiğiyle karşılaştırır. Her iki anahtar ve değer için tanımlı olan operator == veya EqualsTo metodunu kullanır.
type: docs
weight: 690
url: /tr/system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) fonksiyon

İki anahtar-değer çiftini 'equals' semantiğiyle karşılaştırır. Hem anahtarlar hem de değerler için tanımlı olan operator == veya EqualsTo metodunu kullanır.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### Şablon parametreleri

| Parameter | Description |
| --- | --- |
| TKey | Anahtar türü. |
| TValue | Değer türü. |

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Sol operand. |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | Sağ operand. |

### Dönüş Değeri

Anahtarlar ve değerler eşleşiyorsa true, aksi takdirde false.

## Ayrıca Bakınız

* Sınıf [KeyValuePair](../keyvaluepair/)
* İsim Alanı [System::Collections::Generic](../)
* Kütüphane [Aspose.Slides](../../)