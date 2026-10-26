---
title: DateTimeOffset
second_title: Aspose.Slides pro C++ – reference API
description: "Obsahuje datum a čas během dne vzhledem ke koordinovanému světovému času. Objekty této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku nebo pomocí operátoru new, protože to může vést k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání jako argument funkcím."
type: docs
weight: 235
url: /cs/system/datetimeoffset/
---
## DateTimeOffset třída


Obsahuje datum a čas během dne vzhledem k koordinovanému světovému času. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../makeobject/). Nikdy nevytvářejte instance tohoto typu na zásobníku nebo pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../smartptr/) a použijte tento ukazatel k předání jako argument funkcím.

```cpp
class DateTimeOffset
```

## Metody

| Metoda | Popis |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | Přidá zadaný časový interval k objektu [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | Přidá zadaný počet dní k objektu [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | Přidá zadaný počet hodin k objektu [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Přidá zadaný počet milisekund k objektu [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | Přidá zadaný počet minut k objektu [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | Přidá zadaný počet měsíců k objektu [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | Přidá zadaný počet sekund k objektu [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | Přidá zadaný počet tiků k objektu [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | Přidá zadaný počet let k objektu [DateTimeOffset](./). |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Porovná dva objekty [DateTimeOffset](./). |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | Porovná dva objekty [DateTimeOffset](./). |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Porovná dva objekty [DateTimeOffset](./). |
| constexpr [DateTimeOffset](./datetimeoffset/)() | Výchozí konstruktor. |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | Konstruktor. |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Ověří, zda dva objekty [DateTimeOffset](./) představují stejný časový okamžik. |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | Ověří, zda dva objekty [DateTimeOffset](./) představují stejný časový okamžik. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Ověří, zda dva objekty [DateTimeOffset](./) představují stejný časový okamžik. |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | Ověří, zda dva objekty [DateTimeOffset](./) představují stejný časový okamžik a mají stejný posun. |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Ověří, zda dva objekty [DateTimeOffset](./) představují stejný časový okamžik a mají stejný posun. |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) souborový čas na datum a čas s lokálním posunem. |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix-time na objekt [DateTimeOffset](./). |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix-time na objekt [DateTimeOffset](./). |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | Získá komponentu data aktuálního objektu. |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | Získá hodnotu [DateTime](../datetime/). |
| int [get_Day](./get_day/)() const | Získá den v měsíci aktuálního objektu. |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Získá den v týdnu aktuálního objektu. |
| int [get_DayOfYear](./get_dayofyear/)() const | Získá den v roce aktuálního objektu. |
| int [get_Hour](./get_hour/)() const | Získá komponentu hodiny aktuálního objektu. |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | Získá hodnotu [DateTime](../datetime/) představující lokální datum a čas. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Získá komponentu milisekund aktuálního objektu. |
| int [get_Minute](./get_minute/)() const | Získá komponentu minut aktuálního objektu. |
| int [get_Month](./get_month/)() const | Získá komponentu měsíce aktuálního objektu. |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | Získá [DateTimeOffset](./), jehož datum a čas jsou nastaveny na aktuální lokální čas a jehož posun je nastaven na lokální posun. |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | Získá posun od UTC. |
| constexpr int [get_Second](./get_second/)() const | Získá komponentu sekund aktuálního objektu. |
| **int64_t** [get_Ticks](./get_ticks/)() const | Získá počet tiků aktuálního objektu. |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Získá čas dne aktuálního objektu. |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | Získá hodnotu [DateTime](../datetime/) představující UTC datum a čas. |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | Získá [DateTimeOffset](./), jehož datum a čas jsou nastaveny na aktuální UTC čas a jehož posun je [TimeSpan::Zero](../timespan/zero/). |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | Získá počet tiků aktuálního objektu v UTC čase. |
| int [get_Year](./get_year/)() const | Získá komponentu roku aktuálního objektu. |
| int [GetHashCode](./gethashcode/)() const | Získá hash kód aktuálního objektu [DateTimeOffset](./). |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | Určuje, zda aktuální objekt a zadaný objekt [DateTimeOffset](./) představují odlišné hodnoty data a času. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Vrací novou instanci třídy [DateTimeOffset](./), která představuje datum a čas jako součet hodnoty reprezentované aktuálním objektem a zadaného časového intervalu. |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Vrací novou instanci třídy [DateTimeOffset](./), která představuje datum a čas jako výsledek odečtení zadaného časového intervalu od hodnoty reprezentované aktuálním objektem. |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | Vrací instanci třídy [TimeSpan](../timespan/), která představuje časový interval mezi datumy a časy reprezentovanými aktuálním a zadaným objektem. |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | Určuje, zda aktuální objekt představuje datum a čas dříve než hodnota reprezentovaná zadaným objektem [DateTimeOffset](./). |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | Určuje, zda aktuální objekt představuje datum a čas dříve než nebo stejný jako hodnota reprezentovaná zadaným objektem [DateTimeOffset](./). |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | Určuje, zda aktuální objekt a zadaný objekt [DateTimeOffset](./) představují stejný datum a čas. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | Určuje, zda aktuální objekt představuje datum a čas později než hodnota reprezentovaná zadaným objektem [DateTimeOffset](./). |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | Určuje, zda aktuální objekt představuje datum a čas později než nebo stejný jako hodnota reprezentovaná zadaným objektem [DateTimeOffset](./). |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | Převede zadaný řetězec na ekvivalent [DateTimeOffset](./). |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Převede zadaný řetězec na objekt [DateTimeOffset](./) pomocí zadaného poskytovatele formátu a stylu formátování. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Převede zadaný řetězec na objekt [DateTimeOffset](./) pomocí zadaného formátu, poskytovatele formátu a stylu formátování. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Převede zadaný řetězec na objekt [DateTimeOffset](./) pomocí zadaných formátů, poskytovatele formátu a stylu formátování. |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Odečte zadaný časový interval od aktuálního objektu. |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | Odečte zadanou hodnotu [DateTimeOffset](./) od aktuálního objektu. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Převede aktuální objekt na souborový čas [Windows](../../system.windows/). |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | Převede aktuální objekt na objekt představující lokální čas. |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | Nahradí posun aktuálního objektu zadaným posunem. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Převede aktuální objekt na řetězec pomocí zadaného formátu a poskytovatele formátu. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Převede aktuální objekt na řetězec pomocí zadaného poskytovatele formátu. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Převede aktuální objekt na řetězec pomocí zadaného formátu. |
| [String](../string/) [ToString](./tostring/)() const | Převede aktuální objekt na řetězec. |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | Převede aktuální objekt na objekt představující UTC čas. |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Získá milisekundy uplynulé od začátku Unix epochy. |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Získá sekundy uplynulé od začátku Unix epochy. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | Zkusí převést zadaný řetězec na objekt [DateTimeOffset](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Zkusí převést zadaný řetězec na objekt [DateTimeOffset](./) pomocí zadaného poskytovatele formátu a stylu formátování. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Zkusí převést zadaný řetězec na objekt [DateTimeOffset](./) pomocí zadaných formátů, poskytovatele formátu a stylu formátování. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Zkusí převést zadaný řetězec na objekt [DateTimeOffset](./) pomocí zadaného formátu, poskytovatele formátu a stylu formátování. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Vrací objekt [TypeInfo](../typeinfo/), který představuje strukturu [TimeSpan](../timespan/). |

## Pole

| Pole | Popis |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | Získá maximální posun v tikech. |
| static [MaxValue](./maxvalue/) | Získá největší hodnotu [DateTimeOffset](./). |
| static constexpr [MinOffset](./minoffset/) | Získá minimální posun v tikech. |
| static [MinValue](./minvalue/) | Získá nejdřívější hodnotu [DateTimeOffset](./). |
| static [UnixEpoch](./unixepoch/) | Získá počátek Unix epochy. |

## Viz také

* Namespace [System](../)
* Library [Aspose.Slides](../../)