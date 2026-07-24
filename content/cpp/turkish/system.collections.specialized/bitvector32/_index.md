---
title: BitVector32
second_title: Aspose.Slides for C++ API Referansı
description: 32 bit depolamaya kolay tam sayı veya Boolean erişim sağlayan basit, hafif bir bit vektörü sunar.
type: docs
weight: 1
url: /tr/system.collections.specialized/bitvector32/
---
## BitVector32 sınıfı

32 bit depolama alanına kolay tam sayı veya [Boolean](../../system/boolean/) erişimiyle basit, hafif bir bit vektörü sağlar.

```cpp
class BitVector32
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  [BitVector32](./bitvector32/)() | Yeni boş bir [BitVector32](./) örneği başlatır. |
|  [BitVector32](./bitvector32/)(**int32_t**) | Belirtilen iç veriyle [BitVector32](./) yapısının yeni bir örneğini başlatır. |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | Belirtilen değerdeki bilgilerle [BitVector32](./) yapısının yeni bir örneğini başlatır. |
| static **int32_t** [CreateMask](./createmask/)() | Bir serideki ilk maskeyi oluşturur. |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | Bir serideki sonraki maskeyi oluşturur. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | Belirtilen maksimum değerle bir serideki ilk bölümü oluşturur. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | Belirtilen maksimum değerle bir serideki sonraki bölümü oluşturur. |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | Belirtilen nesnenin mevcut nesneyle aynı olup olmadığını belirler. |
| **int32_t** [get_Data](./get_data/)() | bu bit vektöründe depolanan ham verileri döndürür... |
| **int32_t** [GetHashCode](./gethashcode/)() const | Mevcut nesne için bir karma kodu döndürür. |
| **bool** [idx_get](./idx_get/)(**int32_t**) | Belirtilen tüm bitlerin ayarlanıp ayarlanmadığını gösteren bir değeri alır. |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | Belirtilen bölümün değerini alır. |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | Belirtilen tüm bitlerin ayarlanıp ayarlanmadığını gösteren bir değeri ayarlar. |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | Belirtilen bölümün değerini ayarlar. |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | Değer parametresi tarafından temsil edilen değeri dizeye dönüştürür. |
| [String](../../system/string/) [ToString](./tostring/)() const | Mevcut nesne tarafından temsil edilen değeri dizeye dönüştürür. |

## Ayrıca Bakınız

* Ad alanı [System::Collections::Specialized](../)
* Kütüphane [Aspose.Slides](../../)