---
title: DateTimeOffset
second_title: Aspose.Slides C++ API referencia
description: "Tartalmazza a Coordinated Universal Time-hez viszonyított dátumot és időt. Ennek az osztálynak az objektumait csak a System::MakeObject() függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt erről a típusról a stacken vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy System::SmartPtr mutatóba, és használja ezt a mutatót az objektum függvények argumentumaként való átadásához."
type: docs
weight: 235
url: /hu/system/datetimeoffset/
---
## DateTimeOffset osztály

Tartalmazza a dátumot és az órát a Koordinált Univerzális Időhöz viszonyítva. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt erről a típusról a stacken vagy az operator new használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../smartptr/) mutatóba, és használja ezt a mutatót az osztály függvények argumentumaként történő átadásához.

```cpp
class DateTimeOffset
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | Hozzáad egy meghatározott időintervallumot a [DateTimeOffset](./) objektumhoz. |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | Hozzáad egy meghatározott számú napot a [DateTimeOffset](./) objektumhoz. |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | Hozzáad egy meghatározott számú órát a [DateTimeOffset](./) objektumhoz. |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Hozzáad egy meghatározott számú ezredmásodpercet a [DateTimeOffset](./) objektumhoz. |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | Hozzáad egy meghatározott számú percet a [DateTimeOffset](./) objektumhoz. |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | Hozzáad egy meghatározott számú hónapot a [DateTimeOffset](./) objektumhoz. |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | Hozzáad egy meghatározott számú másodpercet a [DateTimeOffset](./) objektumhoz. |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | Hozzáad egy meghatározott számú tick-et a [DateTimeOffset](./) objektumhoz. |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | Hozzáad egy meghatározott számú évet a [DateTimeOffset](./) objektumhoz. |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Összehasonlít két [DateTimeOffset](./) objektumot. |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | Összehasonlít két [DateTimeOffset](./) objektumot. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Összehasonlít két [DateTimeOffset](./) objektumot. |
| constexpr [DateTimeOffset](./datetimeoffset/)() | Alapértelmezett konstruktor. |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | Konstruktor. |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Ellenőrzi, hogy két [DateTimeOffset](./) objektum ugyanazt az időpontot ábrázolja-e. |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | Ellenőrzi, hogy két [DateTimeOffset](./) objektum ugyanazt az időpontot ábrázolja-e. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Ellenőrzi, hogy két [DateTimeOffset](./) objektum ugyanazt az időpontot ábrázolja-e. |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | Ellenőrzi, hogy két [DateTimeOffset](./) objektum ugyanazt az időpontot ábrázolja-e, és ugyanazzal az eltolással rendelkezik. |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Ellenőrzi, hogy két [DateTimeOffset](./) objektum ugyanazt az időpontot ábrázolja-e, és ugyanazzal az eltolással rendelkezik. |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) fájlidő átalakítása dátummá és idővé helyi időeltolással. |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix-idő átalakítása [DateTimeOffset](./) objektummá. |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix-idő átalakítása [DateTimeOffset](./) objektummá. |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | Lekéri a jelenlegi objektum dátum komponensét. |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | Lekéri a [DateTime](../datetime/) értéket. |
| int [get_Day](./get_day/)() const | Lekéri a jelenlegi objektum hónap napját. |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Lekéri a jelenlegi objektum hét napját. |
| int [get_DayOfYear](./get_dayofyear/)() const | Lekéri a jelenlegi objektum év napját. |
| int [get_Hour](./get_hour/)() const | Lekéri a jelenlegi objektum órakomponensét. |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | Lekéri a [DateTime](../datetime/) értéket, amely a helyi dátumot és időt jelenti. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Lekéri a jelenlegi objektum ezredmásodperc komponensét. |
| int [get_Minute](./get_minute/)() const | Lekéri a jelenlegi objektum perc komponensét. |
| int [get_Month](./get_month/)() const | Lekéri a jelenlegi objektum hónap komponensét. |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | Lekéri a [DateTimeOffset](./)-t, amelynek dátuma és ideje a jelenlegi helyi időre van állítva, és amelynek eltolása a helyi idő eltolása. |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | Lekéri az UTC-hez képest az eltolást. |
| constexpr int [get_Second](./get_second/)() const | Lekéri a jelenlegi objektum másodperc komponensét. |
| **int64_t** [get_Ticks](./get_ticks/)() const | Lekéri a jelenlegi objektum tick-ek számát. |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Lekéri a jelenlegi objektum napnak az időpontját. |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | Lekéri a [DateTime](../datetime/) értéket, amely az UTC dátumot és időt jelenti. |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | Lekéri a [DateTimeOffset](./)-t, amelynek dátuma és ideje a jelenlegi UTC-időre van állítva, és amelynek eltolása [TimeSpan::Zero](../timespan/zero/). |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | Lekéri a jelenlegi objektum tick-ek számát UTC időben. |
| int [get_Year](./get_year/)() const | Lekéri a jelenlegi objektum év komponensét. |
| int [GetHashCode](./gethashcode/)() const | Lekéri a jelenlegi [DateTimeOffset](./) objektum hash kódját. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | Meghatározza, hogy a jelenlegi objektum és a megadott [DateTimeOffset](./) objektum különböző dátum- és időértékeket ábrázol-e. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Visszaad egy új [DateTimeOffset](./) osztálypéldányt, amely a jelenlegi objektum által képviselt dátum- és időérték, valamint a megadott időtartam összegét jelenti. |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Visszaad egy új [DateTimeOffset](./) osztálypéldányt, amely a megadott időtartam jelenlegi objektumtól való kivonásával kapott dátum- és időértéket jelenti. |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | Visszaad egy [TimeSpan](../timespan/) osztálypéldányt, amely a jelenlegi és a megadott objektumok által képviselt dátum- és időértékek közötti időintervallumot ábrázolja. |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | Meghatározza, hogy a jelenlegi objektum a megadott [DateTimeOffset](./) objektum által képviselt dátum- és időértéknél korábbi értéket ábrázol-e. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | Meghatározza, hogy a jelenlegi objektum a megadott [DateTimeOffset](./) objektum által képviselt dátum- és időértéknél korábbi vagy azzal megegyező értéket ábrázol-e. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | Meghatározza, hogy a jelenlegi objektum és a megadott [DateTimeOffset](./) objektum ugyanazt a dátum- és időértéket ábrázolja-e. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | Meghatározza, hogy a jelenlegi objektum a megadott [DateTimeOffset](./) objektum által képviselt dátum- és időértéknél későbbi értéket ábrázol-e. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | Meghatározza, hogy a jelenlegi objektum a megadott [DateTimeOffset](./) objektum által képviselt dátum- és időértéknél későbbi vagy azzal megegyező értéket ábrázol-e. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | Átalakítja a megadott karakterláncot [DateTimeOffset](./) megfelelőjévé. |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Átalakítja a megadott karakterláncot [DateTimeOffset](./) objektummá a megadott formátum szolgáltató és formázási stílus használatával. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Átalakítja a megadott karakterláncot [DateTimeOffset](./) objektummá a megadott formátum, formátum szolgáltató és formázási stílus használatával. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Átalakítja a megadott karakterláncot [DateTimeOffset](./) objektummá a megadott formátumok, formátum szolgáltató és formázási stílus használatával. |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Kivon egy megadott időintervallumot a jelenlegi objektumból. |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | Kivon egy megadott [DateTimeOffset](./) értéket a jelenlegi objektumból. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Átalakítja a jelenlegi objektumot [Windows](../../system.windows/) fájlidővé. |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | Átalakítja a jelenlegi objektumot egy olyan objektummá, amely a helyi időt ábrázolja. |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | A jelenlegi objektum eltolását a megadott eltolással helyettesíti. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Átalakítja a jelenlegi objektumot karakterlánccá a megadott formátummal és formátum szolgáltatóval. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Átalakítja a jelenlegi objektumot karakterlánccá a megadott formátum szolgáltató használatával. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Átalakítja a jelenlegi objektumot karakterlánccá a megadott formátummal. |
| [String](../string/) [ToString](./tostring/)() const | Átalakítja a jelenlegi objektumot karakterlánccá. |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | Átalakítja a jelenlegi objektumot egy olyan objektummá, amely az UTC időt ábrázolja. |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Lekéri a Unix epoch kezdete óta eltelt ezredmásodpercet. |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Lekéri a Unix epoch kezdete óta eltelt másodperceket. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | Megpróbálja a megadott karakterláncot [DateTimeOffset](./) objektummá alakítani. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Megpróbálja a megadott karakterláncot [DateTimeOffset](./) objektummá alakítani a megadott formátum szolgáltató és formázási stílus használatával. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Megpróbálja a megadott karakterláncot [DateTimeOffset](./) objektummá alakítani a megadott formátumok, formátum szolgáltató és formázási stílus használatával. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Megpróbálja a megadott karakterláncot [DateTimeOffset](./) objektummá alakítani a megadott formátum, formátum szolgáltató és formázási stílus használatával. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Visszaad egy [TypeInfo](../typeinfo/) objektumot, amely a [TimeSpan](../timespan/) struktúrát képviseli. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | Lekéri a maximális eltolást tick-ekben. |
| static [MaxValue](./maxvalue/) | Lekéri a legnagyobb [DateTimeOffset](./) értéket. |
| static constexpr [MinOffset](./minoffset/) | Lekéri a minimális eltolást tick-ekben. |
| static [MinValue](./minvalue/) | Lekéri a legrégebbi [DateTimeOffset](./) értéket. |
| static [UnixEpoch](./unixepoch/) | Lekéri a Unix epoch kezdőpontját. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)