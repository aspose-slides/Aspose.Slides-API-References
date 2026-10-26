---
title: DateTimeOffset
second_title: Aspose.Slides voor C++ API-referentie
description: "Bevat de datum en tijd van de dag ten opzichte van de gecoördineerde wereldtijd. Objecten van deze klasse mogen alleen worden toegewezen met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wrap deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 235
url: /nl/system/datetimeoffset/
---
## DateTimeOffset klasse

Bevat de datum en tijd van de dag ten opzichte van de gecoördineerde wereldtijd. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wrap deze klasse altijd in een [System::SmartPtr](../smartptr/) pointer en gebruik deze pointer om deze als argument aan functies door te geven.

```cpp
class DateTimeOffset
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | Voegt een opgegeven tijdsinterval toe aan het [DateTimeOffset](./) object. |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | Voegt een opgegeven aantal dagen toe aan het [DateTimeOffset](./) object. |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | Voegt een opgegeven aantal uren toe aan het [DateTimeOffset](./) object. |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Voegt een opgegeven aantal milliseconden toe aan het [DateTimeOffset](./) object. |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | Voegt een opgegeven aantal minuten toe aan het [DateTimeOffset](./) object. |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | Voegt een opgegeven aantal maanden toe aan het [DateTimeOffset](./) object. |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | Voegt een opgegeven aantal seconden toe aan het [DateTimeOffset](./) object. |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | Voegt een opgegeven aantal ticks toe aan het [DateTimeOffset](./) object. |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | Voegt een opgegeven aantal jaren toe aan het [DateTimeOffset](./) object. |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Vergelijkt twee [DateTimeOffset](./) objecten. |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | Vergelijkt twee [DateTimeOffset](./) objecten. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Vergelijkt twee [DateTimeOffset](./) objecten. |
| constexpr [DateTimeOffset](./datetimeoffset/)() | Standaardconstructor. |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | Constructor. |
| [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | Constructor. |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | Constructor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | Constructor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | Constructor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | Constructor. |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Controleert of twee [DateTimeOffset](./) objecten hetzelfde tijdstip vertegenwoordigen. |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | Controleert of twee [DateTimeOffset](./) objecten hetzelfde tijdstip vertegenwoordigen. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Controleert of twee [DateTimeOffset](./) objecten hetzelfde tijdstip vertegenwoordigen. |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | Controleert of twee [DateTimeOffset](./) objecten hetzelfde tijdstip vertegenwoordigen en dezelfde offset hebben. |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Controleert of twee [DateTimeOffset](./) objecten hetzelfde tijdstip vertegenwoordigen en dezelfde offset hebben. |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) bestandstijd naar datum en tijd met lokale tijdoffset. |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix-tijd naar [DateTimeOffset](./) object. |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix-tijd naar [DateTimeOffset](./) object. |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | Haalt datumcomponent op van het huidige object. |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | Haalt [DateTime](../datetime/) waarde op. |
| int [get_Day](./get_day/)() const | Haalt dag van de maand op van het huidige object. |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Haalt dag van de week op van het huidige object. |
| int [get_DayOfYear](./get_dayofyear/)() const | Haalt dag van het jaar op van het huidige object. |
| int [get_Hour](./get_hour/)() const | Haalt uurcomponent op van het huidige object. |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | Haalt [DateTime](../datetime/) waarde op die de lokale datum en tijd vertegenwoordigt. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Haalt millisecondencomponent op van het huidige object. |
| int [get_Minute](./get_minute/)() const | Haalt minuutcomponent op van het huidige object. |
| int [get_Month](./get_month/)() const | Haalt maandcomponent op van het huidige object. |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | Haalt [DateTimeOffset](./) op waarvan datum en tijd zijn ingesteld op de huidige lokale tijd en waarvan de offset is ingesteld op de offset van de lokale tijd. |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | Haalt offset ten opzichte van UTC op. |
| constexpr int [get_Second](./get_second/)() const | Haalt secondecomponent op van het huidige object. |
| **int64_t** [get_Ticks](./get_ticks/)() const | Haalt het aantal ticks op van het huidige object. |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Haalt tijd van de dag op van het huidige object. |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | Haalt [DateTime](../datetime/) waarde op die de UTC-datum en -tijd vertegenwoordigt. |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | Haalt [DateTimeOffset](./) op waarvan datum en tijd zijn ingesteld op de huidige UTC-tijd en waarvan de offset is [TimeSpan::Zero](../timespan/zero/). |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | Haalt het aantal ticks op van het huidige object in UTC-tijd. |
| int [get_Year](./get_year/)() const | Haalt jaarcomponent op van het huidige object. |
| int [GetHashCode](./gethashcode/)() const | Haalt de hashcode op voor het huidige [DateTimeOffset](./) object. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | Bepaalt of het huidige object en het opgegeven [DateTimeOffset](./) object verschillende datum- en tijdwaarden vertegenwoordigen. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Retourneert een nieuw exemplaar van [DateTimeOffset](./) klasse die de datum- en tijdwaarde vertegenwoordigt die de som is van de waarde van het huidige object en het opgegeven tijdsinterval. |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Retourneert een nieuw exemplaar van de [DateTimeOffset](./) klasse die de datum- en tijdwaarde vertegenwoordigt die het resultaat is van aftrekken van het opgegeven tijdsinterval van de waarde van het huidige object. |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | Retourneert een exemplaar van [TimeSpan](../timespan/) klasse die het tijdsinterval vertegenwoordigt tussen de datum- en tijdwaarden die worden weergegeven door het huidige en het opgegeven object. |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | Bepaalt of het huidige object de datum- en tijdwaarde vertegenwoordigt die eerder is dan de waarde van het opgegeven [DateTimeOffset](./) object. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | Bepaalt of het huidige object de datum- en tijdwaarde vertegenwoordigt die eerder is dan of gelijk aan de waarde van het opgegeven [DateTimeOffset](./) object. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | Bepaalt of het huidige object en het opgegeven [DateTimeOffset](./) object dezelfde datum- en tijdwaarde vertegenwoordigen. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | Bepaalt of het huidige object de datum- en tijdwaarde vertegenwoordigt die later is dan de waarde van het opgegeven [DateTimeOffset](./) object. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | Bepaalt of het huidige object de datum- en tijdwaarde vertegenwoordigt die later is dan of gelijk aan de waarde van het opgegeven [DateTimeOffset](./) object. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | Converteert de opgegeven string naar het equivalent van [DateTimeOffset](./). |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converteert de opgegeven string naar een [DateTimeOffset](./) object met behulp van de opgegeven formatprovider en opmaakstijl. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converteert de opgegeven string naar een [DateTimeOffset](./) object met behulp van het opgegeven formaat, formatprovider en opmaakstijl. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converteert de opgegeven string naar een [DateTimeOffset](./) object met behulp van de opgegeven formaten, formatprovider en opmaakstijl. |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Trekt een opgegeven tijdsinterval af van het huidige object. |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | Trekt een opgegeven [DateTimeOffset](./) waarde af van het huidige object. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Converteert het huidige object naar de [Windows](../../system.windows/) bestandstijd. |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | Converteert het huidige object naar een object dat de lokale tijd vertegenwoordigt. |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | Vervangt de offset van het huidige object door de opgegeven offset. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Converteert het huidige object naar een string met het opgegeven formaat en formatprovider. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Converteert het huidige object naar een string met de opgegeven formatprovider. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Converteert het huidige object naar een string met het opgegeven formaat. |
| [String](../string/) [ToString](./tostring/)() const | Converteert het huidige object naar een string. |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | Converteert het huidige object naar een object dat de UTC-tijd vertegenwoordigt. |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Haalt milliseconden sinds het begin van de Unix-epoch op. |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Haalt seconden sinds het begin van de Unix-epoch op. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | Probeert de opgegeven string te converteren naar een [DateTimeOffset](./) object. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Probeert de opgegeven string te converteren naar een [DateTimeOffset](./) object met behulp van de opgegeven formatprovider en opmaakstijl. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Probeert de opgegeven string te converteren naar een [DateTimeOffset](./) object met behulp van de opgegeven formaten, formatprovider en opmaakstijl. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Probeert de opgegeven string te converteren naar een [DateTimeOffset](./) object met behulp van het opgegeven formaat, formatprovider en opmaakstijl. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Retourneert een [TypeInfo](../typeinfo/) object dat de [TimeSpan](../timespan/) structuur vertegenwoordigt. |

## Velden

| Veld | Beschrijving |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | Haalt maximale offset in ticks op. |
| static [MaxValue](./maxvalue/) | Haalt grootste [DateTimeOffset](./) waarde op. |
| static constexpr [MinOffset](./minoffset/) | Haalt minimale offset in ticks op. |
| static [MinValue](./minvalue/) | Haalt vroegste [DateTimeOffset](./) waarde op. |
| static [UnixEpoch](./unixepoch/) | Haalt start van de Unix-epoch op. |

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)