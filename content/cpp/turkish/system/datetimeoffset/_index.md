---
title: DateTimeOffset
second_title: Aspose.Slides for C++ API Referansı
description: "Koordinatlı Evrensel Zaman'a (UTC) göre tarih ve saat bilgisini içerir. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığını (stack) üzerinde veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 235
url: /tr/system/datetimeoffset/
---
## DateTimeOffset sınıfı

Koordinatlı Evrensel Zaman'a (UTC) göre tarih ve saat içerir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığına (stack) veya new operatörüyle oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class DateTimeOffset
```

## Yöntemler

| Method | Description |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | Belirtilen bir zaman aralığını [DateTimeOffset](./) nesnesine ekler. |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | Belirtilen sayıda günü [DateTimeOffset](./) nesnesine ekler. |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | Belirtilen sayıda saati [DateTimeOffset](./) nesnesine ekler. |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Belirtilen sayıda milisaniyeyi [DateTimeOffset](./) nesnesine ekler. |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | Belirtilen sayıda dakikayı [DateTimeOffset](./) nesnesine ekler. |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | Belirtilen sayıda ayı [DateTimeOffset](./) nesnesine ekler. |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | Belirtilen sayıda saniyeyi [DateTimeOffset](./) nesnesine ekler. |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | Belirtilen sayıda tik'i [DateTimeOffset](./) nesnesine ekler. |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | Belirtilen sayıda yılı [DateTimeOffset](./) nesnesine ekler. |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | İki [DateTimeOffset](./) nesnesini karşılaştırır. |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | İki [DateTimeOffset](./) nesnesini karşılaştırır. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | İki [DateTimeOffset](./) nesnesini karşılaştırır. |
| constexpr [DateTimeOffset](./datetimeoffset/)() | Varsayılan yapıcı. |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | Yapıcı. |
| [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | Yapıcı. |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | Yapıcı. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | Yapıcı. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | Yapıcı. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | Yapıcı. |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | İki [DateTimeOffset](./) nesnesinin aynı zaman noktasını temsil edip etmediğini denetler. |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | İki [DateTimeOffset](./) nesnesinin aynı zaman noktasını temsil edip etmediğini denetler. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | İki [DateTimeOffset](./) nesnesinin aynı zaman noktasını temsil edip etmediğini denetler. |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | İki [DateTimeOffset](./) nesnesinin aynı zaman noktasını ve aynı kaydırmayı temsil edip etmediğini denetler. |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | İki [DateTimeOffset](./) nesnesinin aynı zaman noktasını ve aynı kaydırmayı temsil edip etmediğini denetler. |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) dosya zamanını yerel saat kaydırmasıyla tarih ve saat'e dönüştürür. |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix zamanını [DateTimeOffset](./) nesnesine dönüştürür. |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix zamanını [DateTimeOffset](./) nesnesine dönüştürür. |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | Geçerli nesnenin tarih bileşenini alır. |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | [DateTime](../datetime/) değerini alır. |
| int [get_Day](./get_day/)() const | Geçerli nesnenin ay içindeki gününü alır. |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Geçerli nesnenin haftanın gününü alır. |
| int [get_DayOfYear](./get_dayofyear/)() const | Geçerli nesnenin yıl içindeki gününü alır. |
| int [get_Hour](./get_hour/)() const | Geçerli nesnenin saat bileşenini alır. |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | [DateTime](../datetime/) değerini alır; bu değer yerel tarih ve zamanı temsil eder. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Geçerli nesnenin milisaniye bileşenini alır. |
| int [get_Minute](./get_minute/)() const | Geçerli nesnenin dakika bileşenini alır. |
| int [get_Month](./get_month/)() const | Geçerli nesnenin ay bileşenini alır. |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | [DateTimeOffset](./) nesnesini alır; bu nesnenin tarih ve zamanı geçerli yerel zaman olarak ayarlanır ve kaydırması yerel zamanın kaydırması olur. |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | UTC'den kaydırmayı alır. |
| constexpr int [get_Second](./get_second/)() const | Geçerli nesnenin saniye bileşenini alır. |
| **int64_t** [get_Ticks](./get_ticks/)() const | Geçerli nesnenin tik sayısını alır. |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Geçerli nesnenin gün içindeki zamanını alır. |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | [DateTime](../datetime/) değerini alır; bu değer UTC tarih ve zamanını temsil eder. |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | [DateTimeOffset](./) nesnesini alır; bu nesnenin tarih ve zamanı geçerli UTC zamanına ayarlanır ve kaydırması [TimeSpan::Zero](../timespan/zero/) olur. |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | UTC zamanında geçerli nesnenin tik sayısını alır. |
| int [get_Year](./get_year/)() const | Geçerli nesnenin yıl bileşenini alır. |
| int [GetHashCode](./gethashcode/)() const | Geçerli [DateTimeOffset](./) nesnesi için karma kodunu alır. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | Geçerli nesne ve belirtilen [DateTimeOffset](./) nesnesinin farklı tarih ve zaman değerlerini temsil edip etmediğini belirler. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Geçerli nesnenin temsil ettiği değer ile belirtilen zaman aralığının toplamını temsil eden yeni bir [DateTimeOffset](./) sınıfı örneği döndürür. |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Belirtilen zaman aralığını geçerli nesnenin temsil ettiği değerden çıkararak elde edilen tarih ve zaman değerini temsil eden yeni bir [DateTimeOffset](./) sınıfı örneği döndürür. |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | Geçerli nesne ve belirtilen nesneler tarafından temsil edilen tarih ve zaman değerleri arasındaki zaman aralığını temsil eden bir [TimeSpan](../timespan/) sınıfı örneği döndürür. |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | Geçerli nesnenin temsil ettiği tarih ve zaman değerinin, belirtilen [DateTimeOffset](./) nesnesinin temsil ettiği değerden daha önce olup olmadığını belirler. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | Geçerli nesnenin temsil ettiği tarih ve zaman değerinin, belirtilen [DateTimeOffset](./) nesnesinin temsil ettiği değerden daha önce ya da aynı olup olmadığını belirler. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | Geçerli nesne ve belirtilen [DateTimeOffset](./) nesnesinin aynı tarih ve zaman değerini temsil edip etmediğini belirler. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | Geçerli nesnenin temsil ettiği tarih ve zaman değerinin, belirtilen [DateTimeOffset](./) nesnesinin temsil ettiği değerden daha sonra olup olmadığını belirler. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | Geçerli nesnenin temsil ettiği tarih ve zaman değerinin, belirtilen [DateTimeOffset](./) nesnesinin temsil ettiği değerden daha sonra ya da aynı olup olmadığını belirler. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | Belirtilen dizeyi [DateTimeOffset](./) karşılığına dönüştürür. |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Belirtilen dizeyi, belirtilen biçim sağlayıcı ve biçimlendirme stili kullanarak [DateTimeOffset](./) nesnesine dönüştürür. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Belirtilen dizeyi, belirtilen biçim, biçim sağlayıcı ve biçimlendirme stili kullanarak [DateTimeOffset](./) nesnesine dönüştürür. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Belirtilen dizeyi, belirtilen biçimler, biçim sağlayıcı ve biçimlendirme stili kullanarak [DateTimeOffset](./) nesnesine dönüştürür. |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Belirtilen bir zaman aralığını geçerli nesneden çıkarır. |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | Belirtilen [DateTimeOffset](./) değerini geçerli nesneden çıkarır. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Geçerli nesneyi [Windows](../../system.windows/) dosya zamanına dönüştürür. |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | Geçerli nesneyi yerel zamanı temsil eden bir nesneye dönüştürür. |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | Geçerli nesnenin kaydırmasını belirtilen kaydırma ile değiştirir. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Geçerli nesneyi belirtilen biçim ve biçim sağlayıcı kullanarak dizeye dönüştürür. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Geçerli nesneyi belirtilen biçim sağlayıcı kullanarak dizeye dönüştürür. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Geçerli nesneyi belirtilen biçim kullanarak dizeye dönüştürür. |
| [String](../string/) [ToString](./tostring/)() const | Geçerli nesneyi dizeye dönüştürür. |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | Geçerli nesneyi UTC zamanını temsil eden bir nesneye dönüştürür. |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Unix epoch başlangıcından itibaren geçen milisaniyeleri alır. |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Unix epoch başlangıcından itibaren geçen saniyeleri alır. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | Belirtilen dizeyi [DateTimeOffset](./) nesnesine dönüştürmeye çalışır. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Belirtilen dizeyi, belirtilen biçim sağlayıcı ve biçimlendirme stilini kullanarak [DateTimeOffset](./) nesnesine dönüştürmeye çalışır. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Belirtilen dizeyi, belirtilen biçimler, biçim sağlayıcı ve biçimlendirme stilini kullanarak [DateTimeOffset](./) nesnesine dönüştürmeye çalışır. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Belirtilen dizeyi, belirtilen biçim, biçim sağlayıcı ve biçimlendirme stilini kullanarak [DateTimeOffset](./) nesnesine dönüştürmeye çalışır. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | [TimeSpan](../timespan/) yapısını temsil eden bir [TypeInfo](../typeinfo/) nesnesi döndürür. |

## Alanlar

| Field | Description |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | Tik cinsinden maksimum kaydırmayı alır. |
| static [MaxValue](./maxvalue/) | En büyük [DateTimeOffset](./) değerini alır. |
| static constexpr [MinOffset](./minoffset/) | Tik cinsinden minimum kaydırmayı alır. |
| static [MinValue](./minvalue/) | En erken [DateTimeOffset](./) değerini alır. |
| static [UnixEpoch](./unixepoch/) | Unix epoch başlangıcını alır. |

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)