---
title: TimeSpan
second_title: Aspose.Slides for C++ API Referansı
description: "Bir zaman aralığını temsil eder. Bu tür yığında allocate edilmeli ve fonksiyonlara değer veya referans olarak geçirilmelidir. Bu tür nesneleri yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 1314
url: /tr/system/timespan/
---
## TimeSpan sınıfı


Bir zaman aralığını temsil eder. Bu tür, yığında (stack) allocate edilmeli ve fonksiyonlara değer veya referans olarak geçirilmelidir. Bu tür nesneleri yönetmek için [System::SmartPtr](../smartptr/) sınıfını asla kullanmayın.

```cpp
class TimeSpan
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | Mevcut ve belirtilen nesneler tarafından temsil edilen zaman aralıklarının toplamı olan bir zaman aralığını temsil eden yeni bir [TimeSpan](./) sınıfı örneği döndürür. |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | İki [TimeSpan](./) nesnesini karşılaştırır. |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | Mevcut ve belirtilen nesneleri karşılaştırır. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Mevcut ve belirtilen nesneleri karşılaştırır. |
| [TimeSpan](./) [Duration](./duration/)() const | Mevcut nesnenin mutlak değerini temsil eden yeni bir [TimeSpan](./) nesnesi döndürür. |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | Mevcut nesne tarafından temsil edilen zaman aralığının, belirtilen nesne tarafından temsil edilen zaman aralığına eşit olup olmadığını belirler. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Mevcut nesne tarafından temsil edilen zaman aralığının, belirtilen nesne tarafından temsil edilen zaman aralığına eşit olup olmadığını belirler. |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | Belirtilen nesneler aynı zaman aralığını temsil ediyorsa true, aksi takdirde false döndürür. |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | Belirtilen aralığı temsil eden yeni bir [TimeSpan](./) nesnesi döndürür. |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | Belirtilen aralığı temsil eden yeni bir [TimeSpan](./) nesnesi döndürür. |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | Belirtilen aralığı temsil eden yeni bir [TimeSpan](./) nesnesi döndürür. |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | Belirtilen aralığı temsil eden yeni bir [TimeSpan](./) nesnesi döndürür. |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | Belirtilen aralığı temsil eden yeni bir [TimeSpan](./) nesnesi döndürür. |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | Belirtilen aralığı temsil eden yeni bir [TimeSpan](./) nesnesi döndürür. |
| constexpr int [get_Days](./get_days/)() const | Mevcut [TimeSpan](./) nesnesi tarafından temsil edilen zaman aralığının gün bileşenini döndürür. |
| constexpr int [get_Hours](./get_hours/)() const | Mevcut [TimeSpan](./) nesnesi tarafından temsil edilen zaman aralığının saat bileşenini döndürür. |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | Mevcut [TimeSpan](./) nesnesi tarafından temsil edilen zaman aralığının milisaniye bileşenini döndürür. |
| constexpr int [get_Minutes](./get_minutes/)() const | Mevcut [TimeSpan](./) nesnesi tarafından temsil edilen zaman aralığının dakika bileşenini döndürür. |
| constexpr int [get_Seconds](./get_seconds/)() const | Mevcut [TimeSpan](./) nesnesi tarafından temsil edilen zaman aralığının saniye bileşenini döndürür. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Mevcut [TimeSpan](./) nesnesi tarafından temsil edilen zaman aralığını oluşturan 100 nanosanlik periyotların sayısını döndürür. |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | Mevcut [TimeSpan](./) nesnesinin değeri, tam ve kesirli günler cinsinden döndürülür. |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | Mevcut [TimeSpan](./) nesnesinin değeri, tam ve kesirli saatler cinsinden döndürülür. |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | Mevcut [TimeSpan](./) nesnesinin değeri, tam ve kesirli milisaniyeler cinsinden döndürülür. |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | Mevcut [TimeSpan](./) nesnesinin değeri, tam ve kesirli dakika cinsinden döndürülür. |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | Mevcut [TimeSpan](./) nesnesinin değeri, tam ve kesirli saniyeler cinsinden döndürülür. |
| int [GetHashCode](./gethashcode/)() const | Mevcut nesne için bir hash kodu döndürür. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | Mevcut [TimeSpan](./) nesnesi tarafından temsil edilen değerin negatifini temsil eden yeni bir [TimeSpan](./) nesnesi döndürür. |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | Mevcut nesne tarafından temsil edilen zaman aralığının, belirtilen nesne tarafından temsil edilen zaman aralığına eşit olmamasını belirler. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | Mevcut ve belirtilen nesneler tarafından temsil edilen zaman aralıklarının toplamı olan bir zaman aralığını temsil eden yeni bir [TimeSpan](./) sınıfı örneği döndürür. |
| [TimeSpan](./) [operator+](./operator_plus/)() const | Kendisini döndürür. |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | Mevcut nesneye, mevcut ve belirtilen nesneler tarafından temsil edilen zaman aralıklarının toplamı olan zaman aralığını atar. |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | Mevcut nesne tarafından temsil edilen zaman aralığından, belirtilen nesne tarafından temsil edilen zaman aralığının çıkarılmasıyla elde edilen zaman aralığını temsil eden yeni bir [TimeSpan](./) sınıfı örneği döndürür. |
| [TimeSpan](./) [operator-](./operator_minus/)() const | Mevcut [TimeSpan](./) nesnesi tarafından temsil edilen değerin negatifini temsil eden yeni bir [TimeSpan](./) nesnesi döndürür. |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | Mevcut nesneye, mevcut nesne tarafından temsil edilen zaman aralığından belirtilen nesne tarafından temsil edilen zaman aralığının çıkarılmasıyla elde edilen zaman aralığını atar. |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | Mevcut nesne tarafından temsil edilen zaman aralığının, belirtilen nesne tarafından temsil edilen zaman aralığından daha kısa olup olmadığını belirler. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | Mevcut nesne tarafından temsil edilen zaman aralığının, belirtilen nesne tarafından temsil edilen zaman aralığından daha kısa veya eşit olup olmadığını belirler. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | Belirtilen [TimeSpan](./) nesnesi tarafından temsil edilen zaman aralığını mevcut [TimeSpan](./) nesnesine ayarlar. |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | Mevcut nesne tarafından temsil edilen zaman aralığının, belirtilen nesne tarafından temsil edilen zaman aralığına eşit olup olmadığını belirler. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | Mevcut nesne tarafından temsil edilen zaman aralığının, belirtilen nesne tarafından temsil edilen zaman aralığından daha uzun olup olmadığını belirler. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | Mevcut nesne tarafından temsil edilen zaman aralığının, belirtilen nesne tarafından temsil edilen zaman aralığından daha uzun veya eşit olup olmadığını belirler. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | Dizeyi eşdeğer bir [TimeSpan](./) nesnesine dönüştürür. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Dizeyi belirtilen format sağlayıcısını kullanarak eşdeğer bir [TimeSpan](./) nesnesine dönüştürür. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Dizeyi belirtilen biçimler, format sağlayıcı ve stilleri kullanarak eşdeğer bir [TimeSpan](./) nesnesine dönüştürür. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Dizeyi belirtilen format, format sağlayıcı ve stilleri kullanarak eşdeğer bir [TimeSpan](./) nesnesine dönüştürür. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | Mevcut nesne tarafından temsil edilen zaman aralığından belirtilen nesne tarafından temsil edilen zaman aralığının çıkarılmasıyla elde edilen zaman aralığını temsil eden yeni bir [TimeSpan](./) sınıfı örneği döndürür. |
| constexpr [TimeSpan](./timespan/)() | Sıfır zaman aralığını temsil eden bir [TimeSpan](./) nesnesi oluşturur. |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | Belirtilen zaman aralığını temsil eden bir [TimeSpan](./) sınıfı örneği oluşturur. |
|  [TimeSpan](./timespan/)(int, int, int) | Belirtilen saat, dakika ve saniye sayısının toplamına eşit bir zaman aralığını temsil eden bir [TimeSpan](./) sınıfı örneği oluşturur. |
|  [TimeSpan](./timespan/)(int, int, int, int, int) | Belirtilen saat, dakika, saniye ve milisaniye sayısının toplamına eşit bir zaman aralığını temsil eden bir [TimeSpan](./) sınıfı örneği oluşturur. |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | Belirtilen [TimeSpan](./) nesnesi tarafından temsil edilen zaman aralığına eşit bir zaman aralığını temsil eden bir [TimeSpan](./) nesnesi oluşturur. |
| [String](../string/) [ToString](./tostring/)() const | Mevcut nesne tarafından temsil edilen zaman aralığının dize temsilini döndürür. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Mevcut nesnenin değerini belirtilen formatı kullanarak eşdeğer dize temsiline dönüştürür. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Mevcut nesnenin değerini belirtilen format ve format sağlayıcı kullanarak eşdeğer dize temsiline dönüştürür. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | Dizeyi eşdeğer bir [TimeSpan](./) nesnesine dönüştürür ve dönüşüm sonucunu döndürür. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Dizeyi belirtilen format sağlayıcısını kullanarak eşdeğer bir [TimeSpan](./) nesnesine dönüştürür ve dönüşüm sonucunu döndürür. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Dizeyi belirtilen biçimler ve format sağlayıcı kullanarak eşdeğer bir [TimeSpan](./) nesnesine dönüştürür ve dönüşüm sonucunu döndürür. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Dizeyi belirtilen format, format sağlayıcı ve stilleri kullanarak eşdeğer bir [TimeSpan](./) nesnesine dönüştürür ve dönüşüm sonucunu döndürür. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Dizeyi belirtilen biçimler, format sağlayıcı ve stilleri kullanarak eşdeğer bir [TimeSpan](./) nesnesine dönüştürür ve dönüşüm sonucunu döndürür. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Dizeyi belirtilen format ve format sağlayıcıyı kullanarak eşdeğer bir [TimeSpan](./) nesnesine dönüştürür ve dönüşüm sonucunu döndürür. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Bir [TypeInfo](../typeinfo/) nesnesi döndürür; bu nesne [TimeSpan](./) yapısını temsil eder. |

## Alanlar

| Alan | Açıklama |
| --- | --- |
| static [MaxValue](./maxvalue/) | [TimeSpan](./) nesnesi, mümkün olan en uzun aralığı temsil eder. |
| static [MinValue](./minvalue/) | /// [TimeSpan](./) nesnesi, mümkün olan en kısa aralığı temsil eder. |
| static constexpr [TicksPerDay](./ticksperday/) | Bir günde (24 saat) bulunan 100 nanosanlık periyotların sayısı. |
| static constexpr [TicksPerHour](./ticksperhour/) | Bir saat içinde bulunan 100 nanosanlık periyotların sayısı. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Bir milisaniye içinde bulunan 100 nanosanlık periyotların sayısı. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Bir dakika içinde bulunan 100 nanosanlık periyotların sayısı. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Bir saniye içinde bulunan 100 nanosanlık periyotların sayısı. |
| static [Zero](./zero/) | [TimeSpan](./) nesnesi, sıfır aralığını temsil eder. |

## Açıklamalar



```cpp
#include "system/datetime.h"
#include "system/timespan.h"
#include <iostream>

int main()
{
  const auto date1 = System::DateTime(2021, 01, 01);
  const auto date2 = System::DateTime(2021, 10, 30);

  const auto interval = date2 - date1;

  std::cout << "Number of ticks: " << interval.get_Ticks() << std::endl;
  std::cout << "Number of milliseconds: " << interval.get_Milliseconds() << std::endl;
  std::cout << "Total number of milliseconds: " << interval.get_TotalMilliseconds() << std::endl;
  std::cout << "Number of minutes: " << interval.get_Minutes() << std::endl;
  std::cout << "Total number of minutes: " << interval.get_TotalMinutes() << std::endl;
  std::cout << "Number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Total number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Number of days: " << interval.get_Days() << std::endl;
  std::cout << "Total number of days: " << interval.get_TotalDays() << std::endl;

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
Tik sayısı: 260928000000000
Milisaniye sayısı: 0
Toplam milisaniye sayısı: 2.60928e+10
Dakika sayısı: 0
Toplam dakika sayısı: 434880
Saat sayısı: 0
Toplam saat sayısı: 0
Gün sayısı: 302
Toplam gün sayısı: 302
*/
```

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)