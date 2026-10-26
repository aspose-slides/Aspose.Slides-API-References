---
title: Equals()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen bölgenin, mevcut nesne tarafından temsil edilen bölgeyle belirtilen çizim yüzeyinde özdeş olup olmadığını belirler.
type: docs
weight: 157
url: /tr/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) yöntemi


Belirtilen bölgenin, mevcut nesne tarafından temsil edilen bölgeyle belirtilen çizim yüzeyinde özdeş olup olmadığını belirler.

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | Bu bölgeyle karşılaştırılacak bölge |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | Bir çizim yüzeyi |

### Dönüş Değeri

Belirtilen bölgenin iç kısmı, **g** parametresiyle ilişkili dönüşüm uygulandığında mevcut objcet tarafından temsil edilen bölgenin iç kısmıyla özdeş ise doğru; aksi takdirde - yanlış

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Region](../)
* Sınıf [Graphics](../../graphics/)
* Ad alanı [System::Drawing](../../)
* Kütüphane [Aspose.Slides](../../../)