---
title: operator<<()
second_title: Aspose.Slides for C++ API Referansı
description: Akışa UTF-8 kodlamasıyla veri ekler.
type: docs
weight: 716
url: /tr/system.collections.generic/operator_less_less/
---
## System::Collections::Generic::operator<<(std::ostream\&, const KeyValuePair\<TKey, TValue\>\&) fonksiyon


Akışa UTF-8 kodlamasıyla veri ekler.

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TKey | Anahtar tipi. |
| TValue | Değer tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | std::ostream\& | Verinin ekleneceği çıktı akışı. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) eklemek için. |

### Dönüş Değeri

**stream**.

## System::Collections::Generic::operator<<(std::wostream\&, const KeyValuePair\<TKey, TValue\>\&) fonksiyon


Akışa veri ekler.

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TKey | Anahtar tipi. |
| TValue | Değer tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | std::wostream\& | Verinin ekleneceği çıktı akışı. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) eklemek için. |

### Dönüş Değeri

**stream**.

## Ayrıca Bakınız

* Sınıf [KeyValuePair](../keyvaluepair/)
* Ad alanı [System::Collections::Generic](../)
* Kütüphane [Aspose.Slides](../../)