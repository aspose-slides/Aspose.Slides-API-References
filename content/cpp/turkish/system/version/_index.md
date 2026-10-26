---
title: Version
second_title: Aspose.Slides için C++ API Referansı
description: "Bir sürüm numarasını temsil eder. Bu tip yığıt üzerinde ayrılmalı ve fonksiyonlara değer ya da referans olarak geçilmelidir. Bu tipteki nesneleri yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 1470
url: /tr/system/version/
---
## Version sınıfı

Bir sürüm numarasını temsil eder. Bu tip yığını üzerinde ayrılmalı ve fonksiyonlara değer veya referans olarak geçilmelidir. Bu tipteki nesneleri yönetmek için [System::SmartPtr](../smartptr/) sınıfını asla kullanmayın.

```cpp
class Version
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | Geçerli nesne ve belirtilen nesne tarafından temsil edilen sürümleri karşılaştırır. |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | Geçerli ve belirtilen nesneler tarafından temsil edilen sürüm numaralarının eşit olup olmadığını belirler. |
| int [get_Build](./get_build/)() const | Derleme numarasını döndürür. |
| int [get_Major](./get_major/)() const | Ana sürümü döndürür. |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | Revizyon numarasının yüksek 16-bit değerini döndürür. |
| int [get_Minor](./get_minor/)() const | Alt sürümü döndürür. |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | Revizyon numarasının düşük 16-bit değerini döndürür. |
| int [get_Revision](./get_revision/)() const | Revizyon numarasını döndürür. |
| int [GetHashCode](./gethashcode/)() const | Geçerli nesne için bir karma kodu döndürür. |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | [Version](./) sınıfının eşdeğer örneğine bir sürüm numarasının dize temsili dönüştürür. |
| [String](../string/) [ToString](./tostring/)() const | Geçerli nesne tarafından temsil edilen sürüm numarasının dize temsili döndürür. |
| [String](../string/) [ToString](./tostring/)(int) const | Geçerli nesne tarafından temsil edilen sürüm numarasının belirtilen bölüm sayısının dize temsili döndürür. |
|  [Version](./version/)(int, int, int, int) | Belirtilen ana, alt, derleme ve revizyon değerlerini temsil eden bir örnek oluşturur. |
|  [Version](./version/)(int, int, int) | Belirtilen ana, alt ve derleme değerlerini temsil eden bir örnek oluşturur. |
|  [Version](./version/)(int, int) | Belirtilen ana ve değerleri temsil eden bir örnek oluşturur. |
|  [Version](./version/)(const [String](../string/)\&) | Dize olarak temsil edilen sürüm numarasını temsil eden bir örnek oluşturur. |
|  [Version](./version/)() | Sürüm numarası 0.0.-1.-1 olan bir örnek oluşturur. |

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)