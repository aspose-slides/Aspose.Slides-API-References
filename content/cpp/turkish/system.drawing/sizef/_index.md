---
title: SizeF
second_title: Aspose.Slides for C++ API Referansı
description: "Bir görüntünün genişlik ve yüksekliğini temsil eden tek duyarlıklı kayan nokta değer çiftini temsil eder. Bu tip yığıt (stack) üzerinde allocate edilmeli ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu tipin nesnelerini yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 287
url: /tr/system.drawing/sizef/
---
## SizeF sınıfı

Represents a pair of single-precision floating point values that represent width and height of an image. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) class to manage objects of this type.

```cpp
class SizeF
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [SizeF](./) [Add](./add/)(const [SizeF](./)\&, const [SizeF](./)\&) | Belirtilen [SizeF](./) nesnelerinin toplamı olan yeni bir [SizeF](./) nesnesi döndürür, yani genişlik değeri belirtilen nesnelerin genişlik değerlerinin toplamına, yükseklik değeri ise belirtilen nesnelerin yükseklik değerlerinin toplamına eşittir. |
| **bool** [Equals](./equals/)(const [SizeF](./)\&) const | Mevcut nesne ile belirtilen nesnenin eşit olup olmadığını belirler, yani aynı genişlik ve yükseklik değer çiftini temsil edip etmediklerini. |
| **float** [get_Height](./get_height/)() const | Mevcut nesne tarafından temsil edilen yüksekliğin değerini döndürür. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Genişlik ve yükseklik değerlerinin her ikisinin de 0 olup olmadığını belirler. |
| **float** [get_Width](./get_width/)() const | Mevcut nesne tarafından temsil edilen genişliğin değerini döndürür. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Mevcut nesne için bir karma kodu (hash code) döndürür. |
|  [operator PointF](./operator_pointf/)() const | Mevcut nesneyi [Point](../point/) nesnesinin bir örneğine dönüştürür; X ve Y koordinatlarını sırasıyla mevcut nesnenin genişlik ve yüksekliğ değerleriyle başlatır. |
| [SizeF](./)\& [operator+=](./operator_plus_equal/)(const [SizeF](./)\&) | Belirtilen [SizeF](./) nesnesinin genişlik ve yükseklik değerlerini, mevcut [SizeF](./) nesnesinin genişlik ve yükseklik değerlerine sırasıyla ekler. |
| void [set_Height](./set_height/)(**float**) | Mevcut nesne tarafından temsil edilen yüksekliğin değerini ayarlar. |
| void [set_Width](./set_width/)(**float**) | Mevcut nesne tarafından temsil edilen genişliğin değerini ayarlar. |
|  [SizeF](./sizef/)() | Yeni bir [SizeF](./) nesnesi oluşturur ve genişlik ve yükseklik değerlerini 0 ile başlatır. |
|  [SizeF](./sizef/)(const [PointF](../pointf/)\&) | Yeni bir [SizeF](./) nesnesi oluşturur ve genişlik ile yükseklik değerlerini belirtilen noktanın X ve Y koordinat değerleriyle sırasıyla başlatır. |
|  [SizeF](./sizef/)(**float**, **float**) | Yeni bir [SizeF](./) nesnesi oluşturur ve belirtilen değerle başlatır. |
| static [SizeF](./) [Subtract](./subtract/)(const [SizeF](./)\&, const [SizeF](./)\&) | Yeni bir [SizeF](./) nesnesi döndürür; bu nesne **size1**'den **size2**'nin çıkarılması sonucudur, yani genişlik değeri **size1**'in genişlik değerinden **size2**'nin genişlik değerinin çıkarılması, yükseklik değeri ise **size1**'in yüksekliğinden **size2**'nin yüksekliğinin çıkarılmasıyla elde edilir. |
| [PointF](../pointf/) [ToPointF](./topointf/)() const | Mevcut nesneyi [Point](../point/) nesnesinin bir örneğine dönüştürür; X ve Y koordinatlarını sırasıyla mevcut nesnenin genişlik ve yüksekliğ değerleriyle başlatır. |
| [Size](../size/) [ToSize](./tosize/)() const | Mevcut [SizeF](./) nesnesinden bir [Size](../size/) nesnesi oluşturur; [SizeF](./) nesnesinin genişlik ve yüksekliğ değerlerini bir alt tam sayıya kırparak. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Mevcut nesne tarafından temsil edilen genişlik ve yükseklik değer çiftinin metin temsili döndürür. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Empty](./empty/) | [SizeF](./) sınıfının genişlik ve yüksekliği 0 olan boş bir örneği. |
## Ayrıca Bakınız

* AdAlanı [System::Drawing](../)
* Kütüphane [Aspose.Slides](../../)