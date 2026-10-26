---
title: RectangleF
second_title: Aspose.Slides for C++ API Referansı
description: "Bir görüntünün üst sol köşesinin tek duyarlıklı kayan nokta X ve Y koordinatları ile genişlik ve yüksekliği olarak tanımlanan dikdörtgen bir alanı temsil eder. Bu tür yığıt üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu türün nesnelerini yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 248
url: /tr/system.drawing/rectanglef/
---
## RectangleF sınıfı

Bir görüntünün üst sol köşesinin tek duyarlıklı kayan nokta X ve Y koordinatları ile genişlik ve yüksekliği olarak tanımlanan dikdörtgen bir alanı temsil eder. Bu tür yığıt üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu türün nesnelerini yönetmek için [System::SmartPtr](../../system/smartptr/) sınıfını asla kullanmayın.

```cpp
class RectangleF
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| **bool** [Contains](./contains/)(**float**, **float**) | Belirtilen noktanın mevcut nesne tarafından temsil edilen dikdörtgen içinde olup olmadığını belirler. |
| **bool** [Contains](./contains/)(const [PointF](../pointf/)\&) | Belirtilen noktanın mevcut nesne tarafından temsil edilen dikdörtgen içinde olup olmadığını belirler. |
| **bool** [Contains](./contains/)(const [RectangleF](./)\&) | Belirtilen dikdörtgenin mevcut nesne tarafından temsil edilen dikdörtgen içinde olup olmadığını belirler. |
| **bool** [Equals](./equals/)(const [RectangleF](./)\&) const | Mevcut ve belirtilen nesneler tarafından temsil edilen dikdörtgenlerin aynı olup olmadığını belirler. |
| static [RectangleF](./) [FromLTRB](./fromltrb/)(**float**, **float**, **float**, **float**) | Belirtilen kenar konumlarıyla bir dikdörtgeni temsil eden yeni bir [RectangleF](./) nesnesi oluşturur. |
| **float** [get_Bottom](./get_bottom/)() const | Mevcut nesne tarafından temsil edilen dikdörtgenin alt kenarının y koordinatını döndürür. |
| **float** [get_Height](./get_height/)() const | Mevcut nesne tarafından temsil edilen dikdörtgenin yüksekliğini döndürür. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Mevcut nesne tarafından temsil edilen dikdörtgenin üst sol köşe X ve Y koordinatları ile genişlik ve yüksekliğinin 0 değerine sahip olup olmadığını belirler. |
| **float** [get_Left](./get_left/)() const | Mevcut nesne tarafından temsil edilen dikdörtgenin sol kenarının X koordinatını döndürür. |
| [PointF](../pointf/) [get_Location](./get_location/)() const | [PointF](../pointf/) sınıfının bir örneğini döndürür; bu örnek mevcut nesne tarafından temsil edilen dikdörtgenin üst sol köşe konumunu belirtir. |
| **float** [get_Right](./get_right/)() const | Mevcut nesne tarafından temsil edilen dikdörtgenin sağ kenarının X koordinatını döndürür. |
| [SizeF](../sizef/) [get_Size](./get_size/)() const | [SizeF](../sizef/) sınıfının bir örneğini döndürür; bu örnek mevcut nesne tarafından temsil edilen dikdörtgenin genişlik ve yüksekliğini belirtir. |
| **float** [get_Top](./get_top/)() const | Mevcut nesne tarafından temsil edilen dikdörtgenin üst kenarının Y koordinatını döndürür. |
| **float** [get_Width](./get_width/)() const | Mevcut nesne tarafından temsil edilen dikdörtgenin genişliğini döndürür. |
| **float** [get_X](./get_x/)() const | Mevcut nesne tarafından temsil edilen dikdörtgenin üst sol köşesinin X koordinatını döndürür. |
| **float** [get_Y](./get_y/)() const | Mevcut nesne tarafından temsil edilen dikdörtgenin üst sol köşesinin Y koordinatını döndürür. |
| int [GetHashCode](./gethashcode/)() const | Mevcut nesnenin bir karma kodunu döndürür. |
| void [Inflate](./inflate/)(**float**, **float**) | Mevcut nesne tarafından temsil edilen dikdörtgenin genişlik ve yüksekliğini, dikdörtgenin geometrik merkezinin konumunu koruyarak artırır. Genişlik ve yükseklik, belirtilen miktarlarda her iki yönde artırılır. |
| void [Inflate](./inflate/)(const [SizeF](../sizef/)\&) | Mevcut nesne tarafından temsil edilen dikdörtgenin genişlik ve yüksekliğini, geometrik merkezinin konumunu koruyarak artırır. Genişlik ve yükseklik, belirtilen boyut nesnesinin genişlik ve yükseklik değerleriyle karşılık gelen miktarlarda her iki yönde artırılır. |
| static [RectangleF](./) [Inflate](./inflate/)(const [RectangleF](./)\&, **float**, **float**) | Belirtilen nesne tarafından temsil edilen dikdörtgenin genişlik ve yüksekliğini, geometrik merkezinin konumunu koruyarak artırır. Genişlik ve yükseklik, belirtilen miktarlarda her iki yönde artırılır. |
| void [Intersect](./intersect/)(const [RectangleF](./)\&) | Mevcut nesne tarafından temsil edilen dikdörtgeni, belirtilen nesne tarafından temsil edilen dikdörtgenle kesişiminden elde edilen dikdörtgenle değiştirir. |
| static [RectangleF](./) [Intersect](./intersect/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Belirtilen dikdörtgenlerin kesişim sonucunu veren bir dikdörtgen döndürür. |
| **bool** [IntersectsWith](./intersectswith/)(const [RectangleF](./)\&) | Mevcut ve belirtilen nesneler tarafından temsil edilen dikdörtgenlerin kesişip kesişmediğini belirler. |
| void [Offset](./offset/)(const [PointF](../pointf/)\&) | Mevcut nesne tarafından temsil edilen dikdörtgenin konumunu belirtilen miktarlarda kaydırır. |
| void [Offset](./offset/)(**float**, **float**) | Mevcut nesne tarafından temsil edilen dikdörtgenin konumunu belirtilen miktarlarda kaydırır. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Her zaman true döndürür. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Her zaman false döndürür. |
| [RectangleF](./rectanglef/)() | X ve Y koordinatları ile genişlik ve yükseklik değerleri 0 olarak ayarlanmış bir dikdörtgeni temsil eden yeni bir [RectangleF](./) nesne örneği oluşturur. |
| [RectangleF](./rectanglef/)(**float**, **float**, **float**, **float**) | Belirtilen üst sol köşe koordinatları ile genişlik ve yüksekliği olan bir dikdörtgeni temsil eden yeni bir [RectangleF](./) nesne örneği oluşturur. |
| [RectangleF](./rectanglef/)(const [PointF](../pointf/)\&, const [SizeF](../sizef/)\&) | [PointF](../pointf/) sınıfının bir örneği olarak belirtilen üst sol köşe koordinatları ve [SizeF](../sizef/) sınıfının bir örneği olarak belirtilen genişlik ve yükseklik ile bir dikdörtgeni temsil eden yeni bir [RectangleF](./) nesne örneği oluşturur. |
| explicit [RectangleF](./rectanglef/)(const [Rectangle](../rectangle/)\&) | Belirtilen dikdörtgene eşdeğer bir dikdörtgeni temsil eden yeni bir [RectangleF](./) nesne örneği oluşturur. |
| void [set_Height](./set_height/)(**float**) | Mevcut nesne tarafından temsil edilen dikdörtgenin yüksekliğini ayarlar. |
| void [set_Location](./set_location/)([PointF](../pointf/)) | Mevcut nesne tarafından temsil edilen dikdörtgenin üst sol köşe konumunu ayarlar. |
| void [set_Size](./set_size/)([SizeF](../sizef/)) | Mevcut nesne tarafından temsil edilen dikdörtgenin genişlik ve yüksekliğini ayarlar. |
| void [set_Width](./set_width/)(**float**) | Mevcut nesne tarafından temsil edilen dikdörtgenin genişliğini ayarlar. |
| void [set_X](./set_x/)(**float**) | Mevcut nesne tarafından temsil edilen dikdörtgenin üst sol köşesinin X koordinatını ayarlar. |
| void [set_Y](./set_y/)(**float**) | Mevcut nesne tarafından temsil edilen dikdörtgenin üst sol köşesinin Y koordinatını ayarlar. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Mevcut nesnenin dize temsili döndürür. |
| static [RectangleF](./) [Union](./union/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Belirtilen dikdörtgenlerin birleşim sonucunu veren bir dikdörtgen döndürür. |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Empty](./empty/) | Lokasyon ve boyut değerleri sıfır olan boş bir dikdörtgen. |

## Ayrıca Bakınız

* AdAlanı [System::Drawing](../)
* Kütüphane [Aspose.Slides](../../)