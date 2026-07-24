---
title: Size
second_title: Aspose.Slides for C++ API Referansı
description: "Bir görüntünün genişlik ve yükseklik değerlerini temsil eden iki tamsayı çiftini temsil eder. Bu tür yığıt üzerinde tahsis edilmeli ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu tür nesneleri yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 274
url: /tr/system.drawing/size/
---
## Boyut sınıfı

Bir görüntünün genişlik ve yükseklik değerlerini temsil eden iki tamsayı değerinin çiftini temsil eder. Bu tür yığıt üzerinde tahsis edilmeli ve fonksiyonlara değer olarak veya referansla geçirilmelidir. **[System::SmartPtr](../../system/smartptr/)** sınıfını bu tür nesneleri yönetmek için asla kullanmayın.

```cpp
class Size
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [Size](./) [Add](./add/)(const [Size](./)\&, const [Size](./)\&) | Belirtilen [Size](./) nesnesinin toplamı olan yeni bir [Size](./) nesnesi döndürür, yani genişlik değeri belirtilen nesnelerin genişlik değerlerinin toplamına ve yükseklik değeri belirtilen nesnelerin yükseklik değerlerinin toplamına eşittir. |
| static [Size](./) [Ceiling](./ceiling/)(const [SizeF](../sizef/)\&) | Belirtilen [SizeF](../sizef/) nesnesinden [Size](./) nesnesi oluşturur; [SizeF](../sizef/) nesnesinin genişlik ve yükseklik değerlerini bir sonraki üst tam sayıya yuvarlayarak. |
| **bool** [Equals](./equals/)(const [Size](./)\&) const | Geçerli nesne ile belirtilen nesnenin eşit olup olmadığını belirler, yani aynı genişlik ve yükseklik değer çiftini temsil eder. |
| int [get_Height](./get_height/)() const | Geçerli nesne tarafından temsil edilen yüksekliğin değerini döndürür. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Genişlik ve yükseklik değerlerinin her ikisinin de 0 olup olmadığını belirler. |
| int [get_Width](./get_width/)() const | Geçerli nesne tarafından temsil edilen genişliğin değerini döndürür. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Geçerli nesne için bir hash kodu döndürür. |
| [operator Point](./operator_point/)() const | [Point](../point/) nesnesinin bir örneğini oluşturur ve X ile Y koordinatlarını sırasıyla geçerli nesnenin genişlik ve yükseklik değerleriyle başlatır. |
| [operator SizeF](./operator_sizef/)() const | [SizeF](../sizef/) nesnesinin bir örneğini oluşturur ve onu geçerli [Size](./) nesnesinin genişlik ve yükseklik değerleriyle başlatır. |
| static [Size](./) [Round](./round/)(const [SizeF](../sizef/)\&) | Belirtilen [SizeF](../sizef/) nesnesinden [Size](./) nesnesi oluşturur; [SizeF](../sizef/) nesnesinin genişlik ve yükseklik değerlerini en yakın tam sayıya yuvarlayarak. |
| void [set_Height](./set_height/)(int) | Geçerli nesne tarafından temsil edilen yüksekliğin değerini ayarlar. |
| void [set_Width](./set_width/)(int) | Geçerli nesne tarafından temsil edilen genişliğin değerini ayarlar. |
| [Size](./size/)() | Yeni bir [Size](./) nesnesi oluşturur ve genişlik ve yükseklik değerlerini 0 ile başlatır. |
| [Size](./size/)(const [Point](../point/)\&) | Yeni bir [Size](./) nesnesi oluşturur ve genişlik ve yükseklik değerlerini belirtilen noktanın X ve Y koordinat değerleriyle sırasıyla başlatır. |
| [Size](./size/)(int, int) | Yeni bir [Size](./) nesnesi oluşturur ve belirtilen değerle başlatır. |
| static [Size](./) [Subtract](./subtract/)(const [Size](./)\&, const [Size](./)\&) | Yeni bir [Size](./) nesnesi döndürür; bu nesne **size1**'den **size2**'nin çıkarılması sonucudur, yani genişlik değeri **size1**'in genişlik değerinden **size2**'nin genişlik değerinin çıkarılmasıyla elde edilir ve yükseklik değeri **size1**'in yükseklik değerinden **size2**'nin yükseklik değerinin çıkarılmasıyla elde edilir. |
| [String](../../system/string/) [ToString](./tostring/)() const | Geçerli nesne tarafından temsil edilen genişlik ve yükseklik değer çiftinin string temsili döndürür. |
| static [Size](./) [Truncate](./truncate/)(const [SizeF](../sizef/)\&) | Belirtilen [SizeF](../sizef/) nesnesinden [Size](./) nesnesi oluşturur; [SizeF](../sizef/) nesnesinin genişlik ve yükseklik değerlerini bir sonraki alt tam sayıya kırparak. |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [Empty](./empty/) | Genişlik ve yükseklik değerleri 0 olan [Size](./) sınıfının boş bir örneği. |

## Ayrıca Bakınız

* Ad Alanı [System::Drawing](../)
* Kütüphane [Aspose.Slides](../../)