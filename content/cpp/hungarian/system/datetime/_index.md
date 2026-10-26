---
title: DateTime
second_title: Aspose.Slides C++ API referencia
description: "Egy adott dátum- és időértéket reprezentál az idő folytonában. Ennek a típusnak a veremben kell lennie, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt az ilyen típusú objektumok kezelésére."
type: docs
weight: 222
url: /hu/system/datetime/
---
## DateTime osztály

Egy adott dátum- és időértéket képvisel az idő folytonosságában. Ezt a típust a verembe kell allokálni, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../smartptr/) osztályt ennek a típusnak az objektumainak kezelésére.

```cpp
class DateTime
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | Visszaad egy új [DateTime](./) osztálypéldányt, amely a megadott időtartam hozzáadásával a jelenlegi objektum által képviselt dátum- és időértékhez kapott dátum- és időértéket reprezentál. |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | Visszaad egy új [DateTime](./) osztálypéldányt, amely a jelenlegi objektum által képviselt dátum- és időértékhez a megadott napok számát hozzáadva kapott dátum- és időértéket ábrázol. |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | Visszaad egy új [DateTime](./) osztálypéldányt, amely a jelenlegi objektum által képviselt dátum- és időértékhez a megadott órák számát hozzáadva kapott dátum- és időértéket ábrázol. |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Visszaad egy új [DateTime](./) osztálypéldányt, amely a jelenlegi objektum által képviselt dátum- és időértékhez a megadott ezredmásodpercek számát hozzáadva kapott dátum- és időértéket ábrázol. |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | Visszaad egy új [DateTime](./) osztálypéldányt, amely a jelenlegi objektum által képviselt dátum- és időértékhez a megadott percek számát hozzáadva kapott dátum- és időértéket ábrázol. |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | Visszaad egy új [DateTime](./) osztálypéldányt, amely a jelenlegi objektum által képviselt dátum- és időértékhez a megadott hónapok számát hozzáadva kapott dátum- és időértéket ábrázol. |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | Visszaad egy új [DateTime](./) osztálypéldányt, amely a jelenlegi objektum által képviselt dátum- és időértékhez a megadott másodpercek számát hozzáadva kapott dátum- és időértéket ábrázol. |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | Visszaad egy új [DateTime](./) osztálypéldányt, amely a jelenlegi objektum által képviselt dátum- és időértékhez a megadott 100-nanomászekundumos intervallumok számát hozzáadva kapott dátum- és időértéket ábrázol. |
| [DateTime](./) [AddYears](./addyears/)(int) const | Visszaad egy új [DateTime](./) osztálypéldányt, amely a jelenlegi objektum által képviselt dátum- és időértékhez a megadott évszámot hozzáadva kapott dátum- és időértéket ábrázol. |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | Összehasonlítja a megadott [DateTime](./) osztályú példányok által képviselt két értéket, és visszaadja az értéket, amely a vonalon való relatív helyzetüket jelzi. |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | Összehasonlítja a jelenlegi objektum által képviselt dátum- és időértéket a megadott [DateTime](./) osztályú példánnyal, és visszaadja az értéket, amely a vonalon való relatív helyzetüket jelzi. |
| constexpr [DateTime](./datetime/)() | Létrehoz egy olyan példányt, amely a lehető legkisebb, a MinValue-nek megfelelő dátum- és időértéket képviseli. |
|  [DateTime](./datetime/)(int, int, int) | Létrehoz egy olyan példányt, amely egy adott év, hónap és nap által meghatározott dátum- és időértéket képvisel. |
|  [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Létrehoz egy olyan példányt, amely egy adott év, hónap és nap, valamint a megadott naptár szerint meghatározott dátum- és időértéket képvisel. |
|  [DateTime](./datetime/)(int, int, int, int, int, int) | Létrehoz egy olyan példányt, amely egy adott év, hónap, nap, óra, perc és másodperc által meghatározott dátum- és időértéket képvisel. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Létrehoz egy olyan példányt, amely egy adott év, hónap, nap, óra, perc és másodperc, valamint a megadott formátum szerint meghatározott dátum- és időértéket képvisel. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Létrehoz egy olyan példányt, amely egy adott év, hónap, nap, óra, perc és másodperc, valamint a megadott naptár szerint meghatározott dátum- és időértéket képvisel. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Létrehoz egy olyan példányt, amely egy adott év, hónap, nap, óra, perc, másodperc és ezredmásodperc által meghatározott dátum- és időértéket képvisel. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | Létrehoz egy olyan példányt, amely egy adott év, hónap, nap, óra, perc, másodperc és ezredmásodperc, valamint a megadott naptár szerint meghatározott dátum- és időértéket képvisel. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | Létrehoz egy példányt, amely a megadott tick-szám által meghatározott dátum- és időértéket képviseli. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | Létrehoz egy példányt, amely a megadott tick-szám alapján dátum- és időértéket képvisel. CSAK BELSŐ HASZNÁLATRA. |
|  [DateTime](./datetime/)(const [DateTime](./)\&) | Másoló-konstruktorral hoz létre egy példányt. |
| static int [DaysInMonth](./daysinmonth/)(int, int) | Visszaadja a megadott év adott hónapjában található napok számát. |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | Meghatározza, hogy a megadott [DateTime](./) osztályú példányok ugyanazt a dátum- és időértéket ábrázolják-e. |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | Meghatározza, hogy a megadott [DateTime](./) osztályú példány ugyanazt a dátum- és időértéket ábrázolja-e a jelenlegi objektummal. |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | A dátum- és időértéket a megadott 64-bit unsigned egészből deszerializálja, és a [DateTime](./) osztály új példányát erre az értékre állítja. |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | Átalakítja a megadott File-időpontot egy [DateTime](./) osztályú példánnyá, amely a helyi időnek megfelelő dátum- és időértéket képviseli. |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | Átalakítja a megadott File-időpontot egy [DateTime](./) osztályú példánnyá, amely az UTC-időnek megfelelő dátum- és időértéket képviseli. |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | Visszaad egy [DateTime](./) osztályú példányt, amely a megadott OLE Automation Date-nek megfelelő dátum- és időértéket képviseli. |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | Átalakítja a megadott Unix-időpontot egy [DateTime](./) osztályú példánnyá. CSAK BELSŐ HASZNÁLATRA. |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | Visszaad egy új [DateTime](./) osztályú példányt, amely a jelenlegi objektum által képviselt dátum- és időérték dátum-részét tartalmazza, az idő-rész minden komponensét 0-ra állítva. |
| int [get_Day](./get_day/)() const | Visszaadja a hónap napjainak sorszámát a jelenlegi objektum által képviselt hónapban. |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Visszaad egy értéket, amely a jelenlegi objektum által képviselt napot a hét napja szerint jelöli. |
| int [get_DayOfYear](./get_dayofyear/)() const | Visszaadja a jelenlegi objektum által képviselt év napjainak sorszámát. |
| constexpr int [get_Hour](./get_hour/)() const | Visszaadja a dátum- és időérték óra komponensét, amelyet a jelenlegi objektum képvisel. |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | Visszaadja az értéket, amely meghatározza, hogy a jelenlegi objektum által képviselt dátum- és időérték helyi, UTC vagy egyik sem. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Visszaadja a dátum- és időérték ezredmásodperc komponensét a jelenlegi objektum esetén. |
| constexpr int [get_Minute](./get_minute/)() const | Visszaadja a dátum- és időérték perc komponensét a jelenlegi objektum esetén. |
| int [get_Month](./get_month/)() const | Visszaadja a hónap sorszámát az évben a jelenlegi objektum által képviseltnek. |
| static [DateTime](./) [get_Now](./get_now/)() | Visszaad egy [DateTime](./) osztályú példányt, amely a jelenlegi időt helyi időként ábrázolja. |
| constexpr int [get_Second](./get_second/)() const | Visszaadja a dátum- és időérték másodperc komponensét a jelenlegi objektum esetén. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Visszaad egy számot, amely a 100-nanomászekundumos intervallumok számát jelzi 0:00:00 UTC, 0001-01-01 óta a Gergely-naptárban a jelenlegi objektum által képviselt dátum- és időpontig. |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Visszaadja az értéket, amely a nap elejétől a jelenlegi objektum által képviselt dátum- és időpontig terjedő időintervallumot jelöli. |
| static [DateTime](./) [get_Today](./get_today/)() | Visszaad egy [DateTime](./) osztályú példányt, amely a jelenlegi objektum által képviselt dátumot tartalmazza, az idő-rész minden komponensét 0-ra állítva. |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | Visszaad egy [DateTime](./) osztályú példányt, amely a jelenlegi időt UTC-ként ábrázolja. |
| int [get_Year](./get_year/)() const | Visszaadja a jelenlegi objektum által képviselt évet. |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | Lekéri a dátum részeit. CSAK BELSŐ HASZNÁLATRA. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | Visszaad egy karakterlánc-tömböt, ahol minden elem a jelenlegi objektum egyik szabványos dátum- és időformátum-specifikátorral formázott szöveges ábrázolása. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | Visszaad egy karakterlánc-tömböt, ahol minden elem a megadott szabványos dátum- és időformátum-specifikátorral formázott szöveges ábrázolása. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Visszaad egy karakterlánc-tömböt, ahol minden elem a szabványos dátum- és időformátum-specifikátorok egyikével, valamint a megadott formátum-szolgáltatóval formázott szöveges ábrázolása. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Visszaad egy karakterlánc-tömböt, ahol minden elem a megadott szabványos dátum- és időformátum-specifikátor és a formátum-szolgáltató által formázott szöveges ábrázolása. |
| int [GetHashCode](./gethashcode/)() const | Visszaad egy hash-kódot a jelenlegi objektumhoz. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | Meghatározza, hogy a jelenlegi objektum által képviselt dátum- és időérték a napfény-megtakarítási időszakba esik-e a jelenlegi időzóna szerint. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Meghatározza, hogy a megadott év szökőév-e. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | Meghatározza, hogy a jelenlegi objektum és a megadott [DateTime](./) objektum különböző dátum- és időértékeket képvisel-e. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Visszaad egy új [DateTime](./) osztálypéldányt, amely a jelenlegi objektum és a megadott időtartam összegeként kapott dátum- és időértéket reprezentál. |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | Beállítja a jelenlegi objektumot a jelenlegi objektum és a megadott időtartam összegeként kapott dátum- és időértékre. |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Visszaad egy új [DateTime](./) osztálypéldányt, amely a megadott időtartam kivonásával a jelenlegi objektum által képviselt dátum- és időértékből kapott dátum- és időértéket ábrázol. |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | Visszaad egy [TimeSpan](../timespan/) osztályú példányt, amely a jelenlegi és a megadott objektum által képviselt dátum- és időértékek közötti időintervallumot ábrázolja. |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | Beállítja a jelenlegi objektumot a megadott időtartam kivonásával a jelenlegi objektum által képviselt dátum- és időértékből kapott dátum- és időértékre. |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | Meghatározza, hogy a jelenlegi objektum által képviselt dátum- és időérték korábbi-e a megadott [DateTime](./) objektum által képviselt értéknél. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | Meghatározza, hogy a jelenlegi objektum által képviselt dátum- és időérték korábbi-e vagy egyenlő-e a megadott [DateTime](./) objektum által képviselt értékkel. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | A megadott [DateTime](./) példány által képviselt értéket hozzárendeli a jelenlegi objektumhoz. |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | Meghatározza, hogy a jelenlegi objektum és a megadott [DateTime](./) objektum ugyanazt a dátum- és időértéket ábrázolja-e. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | Megállapítja, hogy a jelenlegi objektum a megadott [DateTime](./) objektum által képviselt értéknél későbbi dátum- és időértéket reprezentál-e. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | Megállapítja, hogy a jelenlegi objektum a megadott [DateTime](./) objektum által képviselt értéknél későbbi vagy azzal megegyező dátum- és időértéket reprezentál-e. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | A megadott karakterlánc ábrázolást konvertálja egy dátum- és időértékre, az ekvivalens [DateTime](./) objektummá. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | A megadott karakterlánc ábrázolást konvertálja egy dátum- és időértékre, az ekvivalens [DateTime](./) objektummá kultúra-specifikus formátuminformációk felhasználásával. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Átalakítja a megadott karakterlánc ábrázolást egy dátum- és időértékre az ekvivalens [DateTime](./) objektummá a megadott formátum és kultúra-specifikus formátuminformációk használatával. A karakterlánc formátumának pontosan meg kell egyeznie a megadott formátummal. Kivételt dob, ha a konverzió sikertelen. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Átalakítja a megadott karakterlánc ábrázolást egy dátum- és időértékre az ekvivalens [DateTime](./) objektummá a megadott formátumok, kultúra-specifikus formátuminformációk és stílus használatával. A karakterlánc formátumának pontosan meg kell egyeznie egy vagy több megadott formátummal. Kivételt dob, ha a konverzió sikertelen. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | Létrehoz egy új [DateTime](./) objektumot, amely ugyanannyi ticket képvisel, mint a megadott [DateTime](./) objektum, és a **kind** argumentum alapján helyi időt, UTC időt vagy egyikét sem reprezentál. |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Visszaad egy új példányt a [DateTime](./) osztályból, amely a dátum- és időértéket reprezentálja, amely a megadott időtartam kivonásának eredménye a jelenlegi objektum által reprezentált értékből. |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | Visszaad egy példányt a [TimeSpan](../timespan/) osztályból, amely a jelenlegi és a megadott objektumok által reprezentált dátum- és időértékek közötti időintervallumot ábrázolja. |
| **int64_t** [ToBinary](./tobinary/)() const | Sorosítja a jelenlegi objektumot. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Visszaad egy értéket, amely a jelenlegi objektum által reprezentált dátum- és időértéket File-időként ábrázolja. |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | Átalakítja a jelenlegi objektum által reprezentált dátum- és időértéket File-idő UTC-re. |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | Visszaad egy új példányt a [DateTime](./) osztályból, amely a jelenlegi objektum által reprezentált dátum- és időértéket helyi időként ábrázolja. |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | Visszaad egy karakterláncot, amely a jelenlegi objektum hosszú dátumformátumú ábrázolását tartalmazza. |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | Visszaad egy karakterláncot, amely a jelenlegi objektum hosszú időformátumú ábrázolását tartalmazza. |
| **double** [ToOADate](./tooadate/)() const | Visszaadja a jelenlegi objektum által reprezentált dátum- és időértéket OLE Automation Date-ként. |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | Visszaad egy karakterláncot, amely a jelenlegi objektum rövid dátumformátumú ábrázolását tartalmazza. |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | Visszaad egy karakterláncot, amely a jelenlegi objektum rövid időformátumú ábrázolását tartalmazza. |
| [String](../string/) [ToString](./tostring/)() const | Visszaadja a dátum- és időérték karakterlánc-ábrázolását a jelenlegi kultúra által meghatározott formázási konvenciók használatával. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Visszaadja a dátum- és időérték karakterlánc-ábrázolását a jelenlegi objektum esetén a megadott formátum és a jelenlegi kultúra által definiált formázási konvenciók használatával. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Visszaadja a dátum- és időérték karakterlánc-ábrázolását a megadott formátuminformációk használatával. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Visszaadja a dátum- és időérték karakterlánc-ábrázolását a megadott formátuminformációk használatával. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | Visszaad egy új példányt a [DateTime](./) osztályból, amely a jelenlegi objektum által reprezentált dátum- és időértéket UTC-ként ábrázolja. |
| time_t [ToUnixTime](./tounixtime/)() const | Visszaad egy értéket, amely a jelenlegi objektum által reprezentált dátum- és időértéket Unix-időként ábrázolja. FOR INTERNAL USE. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | Átalakítja a megadott karakterlánc ábrázolást egy dátum- és időértékre a megfelelő [DateTime](./) objektummá. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Átalakítja a megadott karakterlánc ábrázolást egy dátum- és időértékre a megfelelő [DateTime](./) objektummá a megadott kultúra-specifikus formátuminformációk és stílus használatával. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Átalakítja a megadott karakterlánc ábrázolást egy dátum- és időértékre a megfelelő [DateTime](./) objektummá a megadott formátum, kultúra-specifikus formátuminformációk és stílus használatával. A karakterlánc formátumának pontosan meg kell egyeznie a megadott formátummal. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Átalakítja a megadott karakterlánc ábrázolást egy dátum- és időértékre a megfelelő [DateTime](./) objektummá a megadott formátumok, kultúra-specifikus formátuminformációk és stílus használatával. A karakterlánc formátumának pontosan meg kell egyeznie egy vagy több megadott formátummal. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Visszaad egy [TypeInfo](../typeinfo/) objektumot, amely információkat tartalmaz erről az osztályról. |

## Mezők

| Field | Description |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | A minimális és a maximális lehetséges [DateTime](./) érték közötti időintervallumban lévő 100 nanomásodperc egységek száma. |
| static [MaxValue](./maxvalue/) | A [DateTime](./) osztály egy példánya, amely a legnagyobb lehetséges dátum- és időértéket reprezentálja. |
| static constexpr [MinTicks](./minticks/) | A minimális tickek száma, amelyet egy [DateTime](./) osztály példánya képes reprezentálni. |
| static [MinValue](./minvalue/) | A [DateTime](./) osztály egy példánya, amely a legkisebb lehetséges dátum- és időértéket ábrázolja. |
| static constexpr [TicksPerDay](./ticksperday/) | A napban lévő tickek száma. |
| static constexpr [TicksPerHour](./ticksperhour/) | Egy óra alatt lévő tickek száma. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | Egy mikrosecond alatt lévő tickek száma. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Egy ezredmásodperc alatt lévő tickek száma. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Egy perc alatt lévő tickek száma. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Egy másodperc alatt lévő tickek száma. |
| static [UnixEpoch](./unixepoch/) | A [DateTime](./) osztály egy példánya, amely a Unix epoch kezdőpontját (1970-01-01 00:00:00) reprezentálja. |

## Megjegyzések



```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // Hozzon létre egy 'DateTime' osztálypéldányt.
  DateTime dateTime{1990, 10, 30};

  // Írja ki a példányt több formátumban.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
Ez a kódrészlet a következő kimenetet eredményezi:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## Lásd még

* Namespace [System](../)
* Library [Aspose.Slides](../../)