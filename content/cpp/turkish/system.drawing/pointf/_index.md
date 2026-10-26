---
title: PointF
second_title: Aspose.Slides for C++ API Referansı
description: "2 boyutlu bir düzlemdeki bir noktanın tek duyarlıklı kayan nokta X ve Y koordinat çiftini temsil eder. Bu tip yığında allocate edilmeli ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu tipin nesnelerini yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 222
url: /tr/system.drawing/pointf/
---
## PointF sınıf

2 boyutlu bir düzlemdeki bir noktanın tek duyarlıklı kayan nokta X ve Y koordinat çiftini temsil eder. Bu tip yığıt üzerinde allocate edilmeli ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Asla [System::SmartPtr](../../system/smartptr/) sınıfını bu tipin nesnelerini yönetmek için kullanmayın.

```cpp
class PointF
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Belirtilen [SizeF](../sizef/) nesnesinin genişlik ve yükseklik değerlerini, belirtilen [PointF](./) nesnesinin X ve Y koordinat değerlerine karşılık gelen şekilde ekler. |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [Size](../size/)\&) | Belirtilen [Size](../size/) nesnesinin genişlik ve yükseklik değerlerini, belirtilen [PointF](./) nesnesinin X ve Y koordinat değerlerine karşılık gelen şekilde ekler. |
| **bool** [Equals](./equals/)(const [PointF](./)\&) const | Geçerli nesnenin ve belirtilen nesnenin eşit olup olmadığını belirler, yani aynı X ve Y koordinat çiftini temsil edip etmediklerini. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Hem X hem de Y koordinat değerlerinin 0'a eşit olup olmadığını belirler. |
| **float** [get_X](./get_x/)() const | Geçerli nesne tarafından temsil edilen X koordinatının değerini döndürür. |
| **float** [get_Y](./get_y/)() const | Geçerli nesne tarafından temsil edilen Y koordinatının değerini döndürür. |
| int [GetHashCode](./gethashcode/)() const | Geçerli nesne için bir hash kodu döndürür. |
| **bool** [IsNull](./isnull/)() const | Her zaman false döndürür. |
| explicit  [operator bool](./operator_bool/)() | Her zaman true döndürür. |
|  [PointF](./pointf/)() | Yeni bir [PointF](./) nesnesi oluşturur ve X ve Y koordinat değerlerini 0 ile başlatır. |
|  [PointF](./pointf/)(**float**, **float**) | Yeni bir [PointF](./) nesnesi oluşturur ve belirtilen değerlerle başlatır. |
|  [PointF](./pointf/)(const [SizeF](../sizef/)\&) | Yeni bir [PointF](./) nesnesi oluşturur ve X ve Y koordinat değerlerini, belirtilen [SizeF](../sizef/) nesnesinin genişlik ve yükseklik değerleriyle karşılık gelen şekilde başlatır. |
| void [set_X](./set_x/)(**float**) | Geçerli nesne tarafından temsil edilen X koordinatının değerini ayarlar. |
| void [set_Y](./set_y/)(**float**) | Geçerli nesne tarafından temsil edilen Y koordinatının değerini ayarlar. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Belirtilen [SizeF](../sizef/) nesnesinin genişlik ve yükseklik değerlerini, belirtilen [PointF](./) nesnesinin X ve Y koordinat değerlerinden karşılık gelen şekilde çıkarır. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [Size](../size/)\&) | Belirtilen [Size](../size/) nesnesinin genişlik ve yükseklik değerlerini, belirtilen [PointF](./) nesnesinin X ve Y koordinat değerlerinden karşılık gelen şekilde çıkarır. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Geçerli nesne tarafından temsil edilen X ve Y koordinat çiftinin dize temsili döndürür. |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Empty](./empty/) | X ve Y koordinat değerleri 0 olan [PointF](./) sınıfının boş bir örneği. |

## İlgili

* Ad alanı [System::Drawing](../)
* Kütüphane [Aspose.Slides](../../)