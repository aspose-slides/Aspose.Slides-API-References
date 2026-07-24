---
title: Range
second_title: Aspose.Slides for C++ API Referansı
description: "Bir başlangıç ve bitiş dizini olan bir aralığı temsil eder. Bu tip yığıt üzerinde tahsis edilmeli ve fonksiyonlara değer olarak veya referans olarak geçirilmelidir. Bu tipteki nesneleri yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 1197
url: /tr/system/range/
---
## Range sınıfı

Başlangıç ve bitiş dizini olan bir aralığı temsil eder. Bu tip yığıt üzerinde tahsis edilmeli ve fonksiyonlara değer olarak veya referans olarak geçirilmelidir. [System::SmartPtr](../smartptr/) sınıfını bu tür nesneleri yönetmek için asla kullanmayın.

```cpp
class Range : public System::Details::BoxableObjectBase
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static constexpr [Range](./) [EndAt](./endat/)(const [Index](../index/)\&) | Koleksiyonun başlangıcında başlayan ve belirtilen bitiş dizininde sona eren bir aralık oluşturur. |
| **bool** [Equals](./equals/)(const [Range](./)\&) const | Mevcut aralığın belirtilen aralığa eşit olup olmadığını belirler. |
| static constexpr [Range](./) [get_All](./get_all/)() | Tüm koleksiyonu temsil eden bir [Range](./) döndürür. |
| const [Index](../index/)\& [get_End](./get_end/)() const | End dizinini alır. |
| const [Index](../index/)\& [get_Start](./get_start/)() const | Start dizinini alır. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Mevcut aralık için bir hash kodu döndürür. |
| [System::ValueTuple](../valuetuple/)\<**int32_t**, **int32_t**\> [GetOffsetAndLength](./getoffsetandlength/)(**int32_t**) const | Belirtilen koleksiyon uzunluğu için sıfır tabanlı başlangıç ofseti ve uzunluğu hesaplar. |
| constexpr [Range](./range/)() | Boş bir aralık oluşturur. |
| constexpr [Range](./range/)(const [Index](../index/)\&, const [Index](../index/)\&) | Belirtilen başlangıç ve bitiş dizinlerinden bir [Range](./) oluşturur. |
| static constexpr [Range](./) [StartAt](./startat/)(const [Index](../index/)\&) | Belirtilen başlangıç dizininde başlayan ve koleksiyonun sonuna kadar uzanan bir aralık oluşturur. |

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)