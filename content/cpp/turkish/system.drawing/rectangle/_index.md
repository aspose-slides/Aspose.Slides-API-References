---
title: Rectangle
second_title: Aspose.Slides C++ API Referansı
description: "Bir görüntünün sol üst köşesinin tam sayı X ve Y koordinatları ile genişlik ve yüksekliği olarak tanımlanan dikdörtgen bir alanı temsil eder. Bu tür yığın üzerinde tahsis edilmeli ve fonksiyonlara değer olarak ya da referans ile gönderilmelidir. Bu tür nesneleri yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 235
url: /tr/system.drawing/rectangle/
---
## Rectangle sınıfı

Represents a rectangular area of an image defined as integer X and Y coordinates of its upper left corner and its width and height. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
class Rectangle
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [Rectangle](./) [Ceiling](./ceiling/)(const [RectangleF](../rectanglef/)\&) | Belirtilen [RectangleF](../rectanglef/) nesnesinden [Rectangle](./) nesnesi oluşturur ve [RectangleF](../rectanglef/) nesnesinin konum ve boyut değerlerini bir sonraki üst tam sayıya yuvarlar. |
| **bool** [Contains](./contains/)(int, int) const | Belirtilen noktanın, geçerli nesne tarafından temsil edilen dikdörtgenin içinde olup olmadığını belirler. |
| **bool** [Contains](./contains/)(const [Point](../point/)\&) const | Belirtilen noktanın, geçerli nesne tarafından temsil edilen dikdörtgenin içinde olup olmadığını belirler. |
| **bool** [Contains](./contains/)(const [Rectangle](./)\&) const | Belirtilen dikdörtgenin, geçerli nesne tarafından temsil edilen dikdörtgenin içinde olup olmadığını belirler. |
| **bool** [Equals](./equals/)(const [Rectangle](./)\&) const | Geçerli ve belirtilen nesneler tarafından temsil edilen dikdörtgenlerin aynı olup olmadığını belirler. |
| static [Rectangle](./) [FromLTRB](./fromltrb/)(int, int, int, int) | Belirtilen kenar konumlarıyla bir dikdörtgeni temsil eden yeni bir [Rectangle](./) nesnesi oluşturur. |
| int [get_Bottom](./get_bottom/)() const | Geçerli nesne tarafından temsil edilen dikdörtgenin alt kenarının y koordinatını döndürür. |
| int [get_Height](./get_height/)() const | Geçerli nesne tarafından temsil edilen dikdörtgenin yüksekliğini döndürür. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Geçerli nesne tarafından temsil edilen dikdörtgenin sol üst köşesinin X ve Y koordinatları ile genişlik ve yüksekliğinin 0 olup olmadığını belirler. |
| int [get_Left](./get_left/)() const | Geçerli nesne tarafından temsil edilen dikdörtgenin sol kenarının X koordinatını döndürür. |
| [Point](../point/) [get_Location](./get_location/)() const | [Point](../point/) sınıfının bir örneğini döndürür; bu örnek geçerli nesne tarafından temsil edilen dikdörtgenin sol üst köşe konumunu belirtir. |
| int [get_Right](./get_right/)() const | Geçerli nesne tarafından temsil edilen dikdörtgenin sağ kenarının X koordinatını döndürür. |
| [Size](../size/) [get_Size](./get_size/)() const | [Size](../size/) sınıfının bir örneğini döndürür; bu örnek geçerli nesne tarafından temsil edilen dikdörtgenin genişlik ve yüksekliğini belirtir. |
| int [get_Top](./get_top/)() const | Geçerli nesne tarafından temsil edilen dikdörtgenin üst kenarının Y koordinatını döndürür. |
| int [get_Width](./get_width/)() const | Geçerli nesne tarafından temsil edilen dikdörtgenin genişliğini döndürür. |
| int [get_X](./get_x/)() const | Geçerli nesne tarafından temsil edilen dikdörtgenin sol üst köşesinin X koordinatını döndürür. |
| int [get_Y](./get_y/)() const | Geçerli nesne tarafından temsil edilen dikdörtgenin sol üst köşesinin Y koordinatını döndürür. |
| int [GetHashCode](./gethashcode/)() const | Geçerli nesnenin bir karma kodunu döndürür. |
| void [Inflate](./inflate/)(int, int) | Geçerli nesne tarafından temsil edilen dikdörtgenin genişlik ve yüksekliğini artırır; geometrik merkez konumu korunur. Genişlik ve yükseklik, belirtilen miktarlarda her iki yönde artırılır. |
| void [Inflate](./inflate/)(const [Size](../size/)\&) | Geçerli nesne tarafından temsil edilen dikdörtgenin genişlik ve yüksekliğini artırır; geometrik merkez konumu korunur. Genişlik ve yükseklik, belirtilen boyut nesnesinin genişlik ve yükseklik değerleriyle eşleşen miktarlarda her iki yönde artırılır. |
| static [Rectangle](./) [Inflate](./inflate/)(const [Rectangle](./)\&, int, int) | Belirtilen nesne tarafından temsil edilen dikdörtgenin genişlik ve yüksekliğini artırır; geometrik merkez konumu korunur. Genişlik ve yükseklik, belirtilen miktarlarda her iki yönde artırılır. |
| void [Intersect](./intersect/)(const [Rectangle](./)\&) | Geçerli nesne tarafından temsil edilen dikdörtgeni, belirtilen nesne tarafından temsil edilen dikdörtgenle kesişimi sonucu oluşan dikdörtgenle değiştirir. |
| static [Rectangle](./) [Intersect](./intersect/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Belirtilen dikdörtgenlerin kesişiminin sonucu olan bir dikdörtgen döndürür. |
| **bool** [IntersectsWith](./intersectswith/)(const [Rectangle](./)\&) | Geçerli ve belirtilen nesneler tarafından temsil edilen dikdörtgenlerin kesişip kesişmediğini belirler. |
| void [Offset](./offset/)(const [Point](../point/)\&) | Geçerli nesne tarafından temsil edilen dikdörtgenin konumunu belirtilen miktarlarda kaydırır. |
| void [Offset](./offset/)(int, int) | Geçerli nesne tarafından temsil edilen dikdörtgenin konumunu belirtilen miktarlarda kaydırır. |
| [operator RectangleF](./operator_rectanglef/)() const | Geçerli nesne tarafından temsil edilen dikdörtgene eşdeğer bir dikdörtgeni temsil eden [RectangleF](../rectanglef/) nesnesini döndürür. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Her zaman true döndürür. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Her zaman false döndürür. |
| [Rectangle](./rectangle/)() | X ve Y koordinatları ile genişlik ve yükseklik değerleri 0 olan bir dikdörtgeni temsil eden yeni bir [Rectangle](./) nesnesi oluşturur. |
| [Rectangle](./rectangle/)(int, int, int, int) | Sol üst köşesinin belirtilen koordinatları ve genişlik-yükseklik değerleri ile bir dikdörtgeni temsil eden yeni bir [Rectangle](./) nesnesi oluşturur. |
| [Rectangle](./rectangle/)(const [Point](../point/)\&, const [Size](../size/)\&) | Sol üst köşenin koordinatlarını [Point](../point/) sınıfının bir örneği ve genişlik-yüksekliği [Size](../size/) sınıfının bir örneği olarak belirten yeni bir [Rectangle](./) nesnesi oluşturur. |
| [Rectangle](./rectangle/)(const **System::Windows::Forms::Screen::Rectangle_**\&) | Belirtilen dikdörtgene eşdeğer bir dikdörtgeni temsil eden yeni bir [Rectangle](./) nesnesi oluşturur. |
| static [Rectangle](./) [Round](./round/)(const [RectangleF](../rectanglef/)\&) | Belirtilen [RectangleF](../rectanglef/) nesnesinden, [RectangleF](../rectanglef/) nesnesinin konum ve boyut değerlerini en yakın tam sayıya yuvarlayarak bir [Rectangle](./) nesnesi oluşturur. |
| void [set_Height](./set_height/)(int) | Geçerli nesne tarafından temsil edilen dikdörtgenin yüksekliğini ayarlar. |
| void [set_Location](./set_location/)([Point](../point/)) | Geçerli nesne tarafından temsil edilen dikdörtgenin sol üst köşe konumunu ayarlar. |
| void [set_Size](./set_size/)([Size](../size/)) | Geçerli nesne tarafından temsil edilen dikdörtgenin genişlik ve yüksekliğini ayarlar. |
| void [set_Width](./set_width/)(int) | Geçerli nesne tarafından temsil edilen dikdörtgenin genişliğini ayarlar. |
| void [set_X](./set_x/)(int) | Geçerli nesne tarafından temsil edilen dikdörtgenin sol üst köşesinin X koordinatını ayarlar. |
| void [set_Y](./set_y/)(int) | Geçerli nesne tarafından temsil edilen dikdörtgenin sol üst köşesinin Y koordinatını ayarlar. |
| [String](../../system/string/) [ToString](./tostring/)() const | Geçerli nesnenin string temsilini döndürür. |
| static [Rectangle](./) [Truncate](./truncate/)(const [RectangleF](../rectanglef/)\&) | Belirtilen [RectangleF](../rectanglef/) nesnesinden, [RectangleF](../rectanglef/) nesnesinin konum ve boyut değerlerini bir alt tam sayıya kırparak bir [Rectangle](./) nesnesi oluşturur. |
| static [Rectangle](./) [Union](./union/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Belirtilen dikdörtgenlerin birleştirilmesinin sonucu olan bir dikdörtgen döndürür. |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Empty](./empty/) | Boş bir dikdörtgen; yani konum ve boyut değerleri sıfır olan bir dikdörtgen. |

## Ayrıca Bakınız

* Ad alanı [System::Drawing](../)
* Kütüphane [Aspose.Slides](../../)