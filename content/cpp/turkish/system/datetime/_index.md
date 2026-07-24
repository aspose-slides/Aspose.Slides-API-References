---
title: DateTime
second_title: Aspose.Slides for C++ API Referansı
description: "Zaman sürekliliği üzerinde belirli bir tarih ve saat değerini temsil eder. Bu tür, yığında tahsis edilmeli ve fonksiyonlara değer olarak ya da referansla geçirilmelidir. Bu tür nesneleri yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 222
url: /tr/system/datetime/
---
## DateTime sınıfı


Belirli bir tarih ve saat değerini zaman sürekliliğinde temsil eder. Bu tür, yığını üzerinde tahsis edilmeli ve fonksiyonlara değer veya referans olarak geçirilmelidir. [System::SmartPtr](../smartptr/) sınıfını bu türdeki nesneleri yönetmek için asla kullanmayınız.

```cpp
class DateTime
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | Belirtilen zaman aralığının mevcut nesne tarafından temsil edilen tarih ve saat değerine eklenmesiyle oluşan tarih ve saat değerini temsil eden yeni bir [DateTime](./) sınıfı örneğini döndürür. |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | Mevcut nesne tarafından temsil edilen değer ile belirtilen gün sayısının toplamını temsil eden tarih ve saat değerini gösteren yeni bir [DateTime](./) sınıfı örneğini döndürür. |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | Mevcut nesne tarafından temsil edilen değer ile belirtilen saat sayısının toplamını temsil eden tarih ve saat değerini gösteren yeni bir [DateTime](./) sınıfı örneğini döndürür. |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Mevcut nesne tarafından temsil edilen değer ile belirtilen milisaniye sayısının toplamını temsil eden tarih ve saat değerini gösteren yeni bir [DateTime](./) sınıfı örneğini döndürür. |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | Mevcut nesne tarafından temsil edilen değer ile belirtilen dakika sayısının toplamını temsil eden tarih ve saat değerini gösteren yeni bir [DateTime](./) sınıfı örneğini döndürür. |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | Mevcut nesne tarafından temsil edilen değer ile belirtilen ay sayısının toplamını temsil eden tarih ve saat değerini gösteren yeni bir [DateTime](./) sınıfı örneğini döndürür. |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | Mevcut nesne tarafından temsil edilen değer ile belirtilen saniye sayısının toplamını temsil eden tarih ve saat değerini gösteren yeni bir [DateTime](./) sınıfı örneğini döndürür. |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | Mevcut nesne tarafından temsil edilen değer ile belirtilen 100 nanosanıye aralık sayısının toplamını temsil eden tarih ve saat değerini gösteren yeni bir [DateTime](./) sınıfı örneğini döndürür. |
| [DateTime](./) [AddYears](./addyears/)(int) const | Mevcut nesnenin temsil ettiği tarih ve saat değerine yıl bileşeni belirtilen sayı kadar artırılarak eşit yeni bir [DateTime](./) sınıfı örneğini döndürür. |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | Belirtilen [DateTime](./) sınıfı örnekleri tarafından temsil edilen iki değeri karşılaştırır ve değerlerin zaman çizgisi üzerindeki göreceli konumunu gösteren bir değer döndürür. |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | Mevcut nesne ve belirtilen [DateTime](./) sınıfı örneği tarafından temsil edilen iki tarih ve saat değerini karşılaştırır ve değerlerin zaman çizgisi üzerindeki göreceli konumunu gösteren bir değer döndürür. |
| constexpr [DateTime](./datetime/)() | En küçük olası tarih ve saat değerini (MinValue) temsil eden bir örnek oluşturur. |
|  [DateTime](./datetime/)(int, int, int) | Belirli bir yıl, ay ve gün olarak belirtilen tarih ve saat değerini temsil eden bir örnek oluşturur. |
|  [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Belirtilen takvimde belirli bir yıl, ay ve gün olarak belirtilen tarih ve saat değerini temsil eden bir örnek oluşturur. |
|  [DateTime](./datetime/)(int, int, int, int, int, int) | Belirli bir yıl, ay, gün, saat, dakika ve saniye olarak belirtilen tarih ve saat değerini temsil eden bir örnek oluşturur. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Belirli bir yıl, ay, gün, saat, dakika ve saniye olarak belirtilen tarih ve saat değerini temsil eden bir örnek oluşturur. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Belirtilen takvimde belirli bir yıl, ay, gün, saat, dakika ve saniye olarak belirtilen tarih ve saat değerini temsil eden bir örnek oluşturur. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Belirli bir yıl, ay, gün, saat, dakika, saniye ve milisaniye olarak belirtilen tarih ve saat değerini temsil eden bir örnek oluşturur. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | Belirtilen takvimde belirli bir yıl, ay, gün, saat, dakika, saniye ve milisaniye olarak belirtilen tarih ve saat değerini temsil eden bir örnek oluşturur. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | Tik sayısı olarak belirtilen bir tarih ve saat değerini temsil eden bir örnek oluşturur. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | Tik sayısı olarak belirtilen bir tarih ve saat değerini temsil eden bir örnek oluşturur. DAHİLİ KULLANIM İÇİN. |
|  [DateTime](./datetime/)(const [DateTime](./)\&) | Bir örneği kopya-oluşturur. |
| static int [DaysInMonth](./daysinmonth/)(int, int) | Belirtilen yılın belirtilen ayındaki gün sayısını döndürür. |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | Belirtilen [DateTime](./) sınıfı örneklerinin aynı tarih ve saat değerini temsil edip etmediğini belirler. |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | Belirtilen [DateTime](./) sınıfı örneğinin mevcut nesne ile aynı tarih ve saat değerini temsil edip etmediğini belirler. |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | Belirtilen işaretsiz 64-bit tamsayıdan tarih saat değerini ayrıştırır ve yeni [DateTime](./) sınıfı örneğini bu değere ayarlar. |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | Belirtilen Dosya zamanını yerel zamanla aynı tarih ve saat değerini temsil eden bir [DateTime](./) sınıfı örneğine dönüştürür. |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | Belirtilen Dosya zamanını UTC zamanı ile aynı tarih ve saat değerini temsil eden bir [DateTime](./) sınıfı örneğine dönüştürür. |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | Belirtilen OLE Automation Date'e eşdeğer tarih ve saat değerini temsil eden bir [DateTime](./) sınıfı örneğini döndürür. |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | Belirtilen Unix zaman değerini bir [DateTime](./) sınıfı örneğine dönüştürür. DAHİLİ KULLANIM İÇİN. |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | Mevcut nesne tarafından temsil edilen tarih ve saat değerinin tarih kısmını, zaman kısmının tüm bileşenleri 0 olacak şekilde temsil eden yeni bir [DateTime](./) sınıfı örneğini döndürür. |
| int [get_Day](./get_day/)() const | Mevcut nesne tarafından temsil edilen ay içindeki günün sıra numarasını döndürür. |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Mevcut nesne tarafından temsil edilen haftanın gününü temsil eden bir değer döndürür. |
| int [get_DayOfYear](./get_dayofyear/)() const | Mevcut nesne tarafından temsil edilen yıl içindeki günün sıra numarasını döndürür. |
| constexpr int [get_Hour](./get_hour/)() const | Mevcut nesne tarafından temsil edilen tarih ve saat değerinin saat bileşenini döndürür. |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | Mevcut nesne tarafından temsil edilen tarih ve saat değerinin yerel mi, UTC mi yoksa hiçbirine ait değil mi olduğunu temsil eden değeri döndürür. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Mevcut nesne tarafından temsil edilen tarih ve saat değerinin milisaniye bileşenini döndürür. |
| constexpr int [get_Minute](./get_minute/)() const | Mevcut nesne tarafından temsil edilen tarih ve saat değerinin dakika bileşenini döndürür. |
| int [get_Month](./get_month/)() const | Mevcut nesne tarafından temsil edilen yıldaki ayın sıra numarasını döndürür. |
| static [DateTime](./) [get_Now](./get_now/)() | Mevcut saati yerel zaman olarak temsil eden bir [DateTime](./) sınıfı örneğini döndürür. |
| constexpr int [get_Second](./get_second/)() const | Mevcut nesne tarafından temsil edilen tarih ve saat değerinin saniye bileşenini döndürür. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Mevcut nesne tarafından temsil edilen tarih ve saat değerine kadar, Gregoryen takvimde 1 Ocak 0001, 0:00:00 UTC tarihinden itibaren geçen 100 nanosanıye aralıklarının sayısını döndürür. |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Mevcut nesne tarafından temsil edilen günün başlangıcından mevcut nesnenin tarih ve saat değerine kadar olan zaman aralığını temsil eden değeri döndürür. |
| static [DateTime](./) [get_Today](./get_today/)() | Nesnenin temsil ettiği değerin zaman kısmının tüm bileşenleri 0 olacak şekilde mevcut tarihi temsil eden bir [DateTime](./) sınıfı örneğini döndürür. |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | Mevcut saati UTC olarak temsil eden bir [DateTime](./) sınıfı örneğini döndürür. |
| int [get_Year](./get_year/)() const | Mevcut nesne tarafından temsil edilen yılı döndürür. |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | Tarih bölümlerini alır. DAHİLİ KULLANIM İÇİN. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | Her bir öğesi, mevcut nesnenin standart tarih ve saat biçim belirteçlerinden biriyle biçimlendirilmiş dize temsili olan dize dizisini döndürür. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | Her bir öğesi, mevcut nesnenin belirtilen standart tarih ve saat biçim belirteciyle biçimlendirilmiş dize temsili olan dize dizisini döndürür. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Her bir öğesi, mevcut nesnenin standart tarih ve saat biçim belirteçlerinden biri ve belirtilen biçim sağlayıcı ile biçimlendirilmiş dize temsili olan dize dizisini döndürür. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Her bir öğesi, mevcut nesnenin belirtilen standart tarih ve saat biçim belirteci ve biçim sağlayıcı ile biçimlendirilmiş dize temsili olan dize dizisini döndürür. |
| int [GetHashCode](./gethashcode/)() const | Mevcut nesne için bir hash kodu döndürür. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | Mevcut nesne tarafından temsil edilen tarih ve saat değerinin, mevcut saat dilimi için daylight saving time (yaz saati) aralığına düşüp düşmediğini belirler. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Belirtilen yılın artık yıl olup olmadığını belirler. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | Mevcut nesne ve belirtilen [DateTime](./) nesnesinin farklı tarih ve saat değerlerini temsil edip etmediğini belirler. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Mevcut nesne tarafından temsil edilen değer ile belirtilen zaman aralığının toplamını temsil eden bir tarih ve saat değerini gösteren yeni bir [DateTime](./) sınıfı örneğini döndürür. |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | Mevcut nesneyi, mevcut nesne tarafından temsil edilen değer ile belirtilen zaman aralığının toplamı olan tarih ve saat değerine ayarlar. |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Mevcut nesne tarafından temsil edilen değerden belirtilen zaman aralığının çıkarılmasıyla elde edilen tarih ve saat değerini temsil eden yeni bir [DateTime](./) sınıfı örneğini döndürür. |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | Mevcut ve belirtilen nesneler tarafından temsil edilen tarih ve saat değerleri arasındaki zaman aralığını temsil eden bir [TimeSpan](../timespan/) sınıfı örneğini döndürür. |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | Mevcut nesneyi, mevcut nesnenin temsil ettiği tarih ve saat değerinden belirtilen zaman aralığının çıkarılmasıyla elde edilen tarih ve saat değerine ayarlar. |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | Mevcut nesnenin temsil ettiği tarih ve saat değerinin belirtilen [DateTime](./) nesnesi tarafından temsil edilen değerden daha erken olup olmadığını belirler. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | Mevcut nesnenin temsil ettiği tarih ve saat değerinin belirtilen [DateTime](./) nesnesi tarafından temsil edilen değerten daha erken ya da aynı olup olmadığını belirler. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | Belirtilen [DateTime](./) örneği tarafından temsil edilen değeri mevcut nesneye atar. |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | Mevcut nesne ve belirtilen [DateTime](./) nesnesinin aynı tarih ve saat değerini temsil edip etmediğini belirler. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | Mevcut nesnenin, belirtilen [DateTime](./) nesnesi tarafından temsil edilen değerden daha sonraki bir tarih ve saat değerini temsil edip etmediğini belirler. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | Mevcut nesnenin, belirtilen [DateTime](./) nesnesi tarafından temsil edilen değerden daha sonraki ya da aynı tarih ve saat değerini temsil edip etmediğini belirler. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | Belirtilen tarih ve saat değerinin dize temsiliğini eşdeğer [DateTime](./) nesnesine dönüştürür. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Belirtilen tarih ve saat değerinin dize temsiliğini kültüre özgü biçim bilgisi kullanarak eşdeğer [DateTime](./) nesnesine dönüştürür. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Belirtilen dize temsiliğini belirtilen biçim ve kültüre özgü biçim bilgisi kullanarak eşdeğer [DateTime](./) nesnesine dönüştürür. Dize temsiliğinin biçimi belirtilen biçime tam olarak uymalıdır. Dönüştürme başarısız olursa bir istisna fırlatır. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Belirtilen dize temsiliğini belirtilen biçimler, kültüre özgü biçim bilgisi ve stil kullanarak eşdeğer [DateTime](./) nesnesine dönüştürür. Dize temsiliğinin biçimi belirtilen biçimlerden bir veya daha fazlasına tam olarak uymalıdır. Dönüştürme başarısız olursa bir istisna fırlatır. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | Yeni bir [DateTime](./) nesnesi oluşturur; bu nesne belirtilen [DateTime](./) nesnesiyle aynı sayıda tik içerir ve argüman **kind** tarafından belirtilen yerel zaman, UTC zamanı veya hiçbiri olarak temsil eder. |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Belirtilen zaman aralığının, mevcut nesnenin temsil ettiği değerden çıkarılması sonucu oluşan tarih ve saat değerini temsil eden [DateTime](./) sınıfının yeni bir örneğini döndürür. |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | Mevcut ve belirtilen nesneler tarafından temsil edilen tarih ve saat değerleri arasındaki zaman aralığını temsil eden [TimeSpan](../timespan/) sınıfının bir örneğini döndürür. |
| **int64_t** [ToBinary](./tobinary/)() const | Mevcut nesneyi serileştirir. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Mevcut nesnenin temsil ettiği tarih ve saat değerini Dosya zamanı olarak temsil eden bir değer döndürür. |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | Mevcut nesnenin temsil ettiği tarih ve saat değerini Dosya zamanı UTC'ye dönüştürür. |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | Mevcut nesnenin temsil ettiği tarih ve saat değerini yerel zaman olarak temsil eden [DateTime](./) sınıfının yeni bir örneğini döndürür. |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | Mevcut nesnenin uzun tarih dizesi temsili içeren bir dize döndürür. |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | Mevcut nesnenin uzun zaman dizesi temsili içeren bir dize döndürür. |
| **double** [ToOADate](./tooadate/)() const | Mevcut nesnenin temsil ettiği tarih ve saat değerini OLE Automation Date olarak döndürür. |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | Mevcut nesnenin kısa tarih dizesi temsili içeren bir dize döndürür. |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | Mevcut nesnenin kısa zaman dizesi temsili içeren bir dize döndürür. |
| [String](../string/) [ToString](./tostring/)() const | Mevcut nesnenin temsil ettiği tarih ve saat değerinin, geçerli kültür tarafından tanımlanan biçimlendirme kurallarını kullanarak dize temsili döndürür. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Mevcut nesnenin temsil ettiği tarih ve saat değerini belirtilen biçim ve geçerli kültür tarafından tanımlanan biçimlendirme kurallarını kullanarak dize temsili döndürür. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Mevcut nesnenin temsil ettiği tarih ve saat değerini belirtilen biçim bilgisi kullanarak dize temsili döndürür. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Mevcut nesnenin temsil ettiği tarih ve saat değerini belirtilen biçim bilgisi kullanarak dize temsili döndürür. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | Yeni bir [DateTime](./) sınıfının, mevcut nesnenin temsil ettiği tarih ve saat değerini UTC olarak temsil eden bir örneğini döndürür. |
| time_t [ToUnixTime](./tounixtime/)() const | Mevcut nesnenin temsil ettiği tarih ve saat değerini Unix zamanı olarak temsil eden bir değer döndürür. FOR INTERNAL USE. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | Belirtilen tarih ve saat değerinin dize temsiliğini eşdeğer [DateTime](./) nesnesine dönüştürür. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Belirtilen tarih ve saat değerinin dize temsiliğini belirtilen kültüre özgü biçim bilgisi ve stil kullanarak eşdeğer [DateTime](./) nesnesine dönüştürür. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Belirtilen dize temsiliğini belirtilen biçim, kültüre özgü biçim bilgisi ve stil kullanarak eşdeğer [DateTime](./) nesnesine dönüştürür. Dize temsiliğinin biçimi belirtilen biçime tam olarak uymalıdır. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Belirtilen dize temsiliğini belirtilen biçimler, kültüre özgü biçim bilgisi ve stil kullanarak eşdeğer [DateTime](./) nesnesine dönüştürür. Dize temsiliğinin biçimi belirtilen biçimlerden bir veya daha fazlasına tam olarak uymalıdır. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Bu sınıf hakkında bilgi içeren bir [TypeInfo](../typeinfo/) nesnesi döndürür. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | Minimum ve maksimum olası [DateTime](./) değeri arasındaki zaman aralığında 100 nanosaniyelik birimdeki tik sayısı. |
| static [MaxValue](./maxvalue/) | [DateTime](./) sınıfının, maksimum olası tarih ve saat değerini temsil eden bir örneği. |
| static constexpr [MinTicks](./minticks/) | [DateTime](./) sınıfının bir örneğinin temsil edebileceği minimum tik sayısı. |
| static [MinValue](./minvalue/) | [DateTime](./) sınıfının, minimum olası tarih ve saat değerini temsil eden bir örneği. |
| static constexpr [TicksPerDay](./ticksperday/) | Bir günde bulunan tik sayısı. |
| static constexpr [TicksPerHour](./ticksperhour/) | Bir saatde bulunan tik sayısı. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | Bir mikrosaniyede bulunan tik sayısı. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Bir milisaniyede bulunan tik sayısı. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Bir dakikada bulunan tik sayısı. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Bir saniyede bulunan tik sayısı. |
| static [UnixEpoch](./unixepoch/) | [DateTime](./) sınıfının, Unix epoch başlangıcını (1970.01.01 00:00:00) temsil eden bir örneği. |
## Açıklamalar

```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // 'DateTime' sınıf örneğini oluştur.
  DateTime dateTime{1990, 10, 30};

  // Örneği birden fazla formatta yazdır.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## Ayrıca Bakınız

* İsim alanı [System](../)
* Kütüphane [Aspose.Slides](../../)