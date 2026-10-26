---
title: DateTime
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt einen spezifischen Datums- und Uhrzeitwert auf dem Zeitkontinuum dar. Dieser Typ sollte im Stack alloziert und per Wert oder Referenz an Funktionen übergeben werden. Verwenden Sie niemals die Klasse System::SmartPtr, um Objekte dieses Typs zu verwalten."
type: docs
weight: 222
url: /de/system/datetime/
---
## DateTime Klasse


Stellt einen spezifischen Datum- und Zeitwert im Zeitkontinuum dar. Dieser Typ sollte auf dem Stack zugewiesen und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die [System::SmartPtr](../smartptr/) Klasse, um Objekte dieses Typs zu verwalten.

```cpp
class DateTime
```

## Methoden

| Method | Description |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | Gibt eine neue Instanz der [DateTime](./) Klasse zurück, die einen Datum- und Zeitwert darstellt, der sich aus der Hinzufügung der angegebenen Zeitspanne zum vom aktuellen Objekt repräsentierten Datum- und Zeitwert ergibt. |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | Gibt eine neue Instanz der [DateTime](./) Klasse zurück, die den Datum- und Zeitwert darstellt, der die Summe des vom aktuellen Objekt repräsentierten Werts und der angegebenen Anzahl von Tagen ist. |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | Gibt eine neue Instanz der [DateTime](./) Klasse zurück, die den Datum- und Zeitwert darstellt, der die Summe des vom aktuellen Objekt repräsentierten Werts und der angegebenen Anzahl von Stunden ist. |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Gibt eine neue Instanz der [DateTime](./) Klasse zurück, die den Datum- und Zeitwert darstellt, der die Summe des vom aktuellen Objekt repräsentierten Werts und der angegebenen Anzahl von Millisekunden ist. |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | Gibt eine neue Instanz der [DateTime](./) Klasse zurück, die den Datum- und Zeitwert darstellt, der die Summe des vom aktuellen Objekt repräsentierten Werts und der angegebenen Anzahl von Minuten ist. |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | Gibt eine neue Instanz der [DateTime](./) Klasse zurück, die den Datum- und Zeitwert darstellt, der die Summe des vom aktuellen Objekt repräsentierten Werts und der angegebenen Anzahl von Monaten ist. |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | Gibt eine neue Instanz der [DateTime](./) Klasse zurück, die den Datum- und Zeitwert darstellt, der die Summe des vom aktuellen Objekt repräsentierten Werts und der angegebenen Anzahl von Sekunden ist. |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | Gibt eine neue Instanz der [DateTime](./) Klasse zurück, die den Datum- und Zeitwert darstellt, der die Summe des vom aktuellen Objekt repräsentierten Werts und der angegebenen Anzahl von 100-Nanosekunden-Intervallen ist. |
| [DateTime](./) [AddYears](./addyears/)(int) const | Gibt eine neue Instanz der [DateTime](./) Klasse zurück, die einen Datum- und Zeitwert darstellt, der dem vom aktuellen Objekt repräsentierten entspricht, wobei die Jahreskomponente um die angegebene Anzahl erhöht wird. |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | Vergleicht zwei von den angegebenen Instanzen der [DateTime](./) Klasse repräsentierte Werte und gibt den Wert zurück, der die relative Position der Werte auf der Zeitleiste angibt. |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | Vergleicht zwei von dem aktuellen Objekt und der angegebenen Instanz der [DateTime](./) Klasse repräsentierte Datum- und Zeitwerte und gibt den Wert zurück, der deren relative Position auf der Zeitleiste angibt. |
| constexpr [DateTime](./datetime/)() | Konstruiert eine Instanz, die den kleinstmöglichen Datum- und Zeitwert darstellt, gleich MinValue. |
|  [DateTime](./datetime/)(int, int, int) | Konstruiert eine Instanz, die einen Datum- und Zeitwert darstellt, der als bestimmtes Jahr, Monat und Tag angegeben ist. |
|  [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Konstruiert eine Instanz, die einen Datum- und Zeitwert darstellt, der als bestimmtes Jahr, Monat und Tag im angegebenen Kalender definiert ist. |
|  [DateTime](./datetime/)(int, int, int, int, int, int) | Konstruiert eine Instanz, die einen Datum- und Zeitwert darstellt, der als bestimmtes Jahr, Monat, Tag, Stunde, Minute und Sekunde angegeben ist. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Konstruiert eine Instanz, die einen Datum- und Zeitwert darstellt, der als bestimmtes Jahr, Monat, Tag, Stunde, Minute und Sekunde angegeben ist. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Konstruiert eine Instanz, die einen Datum- und Zeitwert darstellt, der als bestimmtes Jahr, Monat, Tag, Stunde, Minute und Sekunde im angegebenen Kalender definiert ist. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Konstruiert eine Instanz, die einen Datum- und Zeitwert darstellt, der als bestimmtes Jahr, Monat, Tag, Stunde, Minute, Sekunde und Millisekunde angegeben ist. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | Konstruiert eine Instanz, die einen Datum- und Zeitwert darstellt, der als bestimmtes Jahr, Monat, Tag, Stunde, Minute, Sekunde und Millisekunde im angegebenen Kalender definiert ist. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | Konstruiert eine Instanz, die einen Datum- und Zeitwert darstellt, der als Anzahl von Ticks angegeben ist. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | Konstruiert eine Instanz, die einen Datum- und Zeitwert darstellt, der als Anzahl von Ticks angegeben ist. FÜR INTERNE VERWENDUNG. |
|  [DateTime](./datetime/)(const [DateTime](./)\&) | Kopiert eine Instanz. |
| static int [DaysInMonth](./daysinmonth/)(int, int) | Gibt die Anzahl der Tage im angegebenen Monat des angegebenen Jahres zurück. |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | Bestimmt, ob die angegebenen Instanzen der [DateTime](./) Klasse denselben Datum- und Zeitwert repräsentieren. |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | Bestimmt, ob die angegebene Instanz der [DateTime](./) Klasse denselben Datum- und Zeitwert wie das aktuelle Objekt repräsentiert. |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | Deserialisiert den Datum-Zeit-Wert aus der angegebenen unsignierten 64-Bit-Ganzzahl und setzt die neue Instanz der [DateTime](./) Klasse auf diesen Wert. |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | Konvertiert die angegebene Dateizeit in eine Instanz der [DateTime](./) Klasse, die denselben Datum- und Zeitwert wie die lokale Zeit repräsentiert. |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | Konvertiert die angegebene Dateizeit in eine Instanz der [DateTime](./) Klasse, die denselben Datum- und Zeitwert wie die UTC-Zeit repräsentiert. |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | Gibt eine Instanz der [DateTime](./) Klasse zurück, die den Datum- und Zeitwert darstellt, der dem angegebenen OLE-Automation-Datum entspricht. |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | Konvertiert den angegebenen Unix-Zeitwert in eine Instanz der [DateTime](./) Klasse. FÜR INTERNE VERWENDUNG. |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | Gibt eine neue Instanz der [DateTime](./) Klasse zurück, die den Datumsteil des vom aktuellen Objekt repräsentierten Datum- und Zeitwerts darstellt, wobei jede Komponente des Zeitteils auf 0 gesetzt ist. |
| int [get_Day](./get_day/)() const | Gibt die Ordnungszahl des Tages im Monat zurück, die vom aktuellen Objekt repräsentiert wird. |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Gibt einen Wert zurück, der den Wochentag repräsentiert, der vom aktuellen Objekt dargestellt wird. |
| int [get_DayOfYear](./get_dayofyear/)() const | Gibt die Ordnungszahl des Tages im Jahr zurück, die vom aktuellen Objekt repräsentiert wird. |
| constexpr int [get_Hour](./get_hour/)() const | Gibt die Stundenkomponente des vom aktuellen Objekt repräsentierten Datum- und Zeitwerts zurück. |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | Gibt den Wert zurück, der angibt, ob das vom aktuellen Objekt repräsentierte Datum und die Zeit ein lokaler oder UTC-Zeitwert ist oder weder noch. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Gibt die Millisekundenkomponente des vom aktuellen Objekt repräsentierten Datum- und Zeitwerts zurück. |
| constexpr int [get_Minute](./get_minute/)() const | Gibt die Minutenkomponente des vom aktuellen Objekt repräsentierten Datum- und Zeitwerts zurück. |
| int [get_Month](./get_month/)() const | Gibt die Ordnungszahl des Monats im Jahr zurück, die vom aktuellen Objekt repräsentiert wird. |
| static [DateTime](./) [get_Now](./get_now/)() | Gibt eine Instanz der [DateTime](./) Klasse zurück, die die aktuelle Zeit als lokale Zeit darstellt. |
| constexpr int [get_Second](./get_second/)() const | Gibt die Sekundenkomponente des vom aktuellen Objekt repräsentierten Datum- und Zeitwerts zurück. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Gibt die Anzahl der seit dem 01.01.0001 0:00:00 UTC im gregorianischen Kalender vergangenen 100-Nanosekunden-Intervalle bis zum vom aktuellen Objekt repräsentierten Datum- und Zeitwert zurück. |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Gibt den Wert zurück, der das Zeitintervall vom Beginn des vom aktuellen Objekt repräsentierten Tages bis zum vom aktuellen Objekt dargestellten Datum- und Zeitwert darstellt. |
| static [DateTime](./) [get_Today](./get_today/)() | Gibt eine Instanz der [DateTime](./) Klasse zurück, die das aktuelle Datum darstellt, wobei jede Komponente des Zeitanteils des vom Objekt repräsentierten Werts auf 0 gesetzt ist. |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | Gibt eine Instanz der [DateTime](./) Klasse zurück, die die aktuelle Zeit als UTC darstellt. |
| int [get_Year](./get_year/)() const | Gibt das vom aktuellen Objekt repräsentierte Jahr zurück. |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | Ermittelt Datumsteile. FÜR INTERNE VERWENDUNG. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | Gibt ein Array von Zeichenketten zurück, wobei jedes Element die String-Darstellung des aktuellen Objekts ist, formatiert mit einem der standardmäßigen Datums- und Zeitformat-Spezifizierer. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | Gibt ein Array von Zeichenketten zurück, wobei jedes Element die String-Darstellung des aktuellen Objekts ist, formatiert mit dem angegebenen standardmäßigen Datums- und Zeitformat-Spezifizierer. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Gibt ein Array von Zeichenketten zurück, wobei jedes Element die String-Darstellung des aktuellen Objekts ist, formatiert mit einem der standardmäßigen Datums- und Zeitformat-Spezifizierer und dem angegebenen Format-Provider. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Gibt ein Array von Zeichenketten zurück, wobei jedes Element die String-Darstellung des aktuellen Objekts ist, formatiert mit dem angegebenen standardmäßigen Datums- und Zeitformat-Spezifizierer und dem Format-Provider. |
| int [GetHashCode](./gethashcode/)() const | Gibt einen Hash-Code für das aktuelle Objekt zurück. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | Bestimmt, ob der vom aktuellen Objekt repräsentierte Datum- und Zeitwert in den Sommerzeit-Bereich der aktuellen Zeitzone fällt. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Bestimmt, ob das angegebene Jahr ein Schaltjahr ist. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | Bestimmt, ob das aktuelle Objekt und das angegebene [DateTime](./) Objekt unterschiedliche Datum- und Zeitwerte repräsentieren. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Gibt eine neue Instanz der [DateTime](./) Klasse zurück, die den Datum- und Zeitwert darstellt, der die Summe des vom aktuellen Objekt repräsentierten Werts und der angegebenen Zeitspanne ist. |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | Setzt das aktuelle Objekt auf den Datum- und Zeitwert, der die Summe des vom aktuellen Objekt repräsentierten Werts und der angegebenen Zeitspanne ist. |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Gibt eine neue Instanz der [DateTime](./) Klasse zurück, die den Datum- und Zeitwert darstellt, der das Ergebnis der Subtraktion der angegebenen Zeitspanne vom vom aktuellen Objekt repräsentierten Wert ist. |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | Gibt eine Instanz der [TimeSpan](../timespan/) Klasse zurück, die das Zeitintervall zwischen den vom aktuellen und dem angegebenen Objekt repräsentierten Datum- und Zeitwerten darstellt. |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | Setzt das aktuelle Objekt auf den Datum- und Zeitwert, der das Ergebnis der Subtraktion der angegebenen Zeitspanne vom vom aktuellen Objekt dargestellten Datum- und Zeitwert ist. |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | Bestimmt, ob das aktuelle Objekt den Datum- und Zeitwert darstellt, der früher liegt als der von dem angegebenen [DateTime](./) Objekt repräsentierte Wert. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | Bestimmt, ob das aktuelle Objekt den Datum- und Zeitwert darstellt, der früher liegt als oder derselbe ist wie der von dem angegebenen [DateTime](./) Objekt repräsentierte Wert. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | Weist dem aktuellen Objekt den von der angegebenen [DateTime](./) Instanz repräsentierten Wert zu. |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | Bestimmt, ob das aktuelle Objekt und das angegebene [DateTime](./) Objekt denselben Datum- und Zeitwert repräsentieren. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | Bestimmt, ob das aktuelle Objekt den Datums- und Zeitwert darstellt, der später ist als der von dem angegebenen [DateTime](./)-Objekt dargestellte Wert. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | Bestimmt, ob das aktuelle Objekt den Datums- und Zeitwert darstellt, der später oder gleich dem von dem angegebenen [DateTime](./)-Objekt dargestellten Wert ist. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | Konvertiert die angegebene Zeichenkettendarstellung eines Datums- und Zeitwerts in das entsprechende [DateTime](./)-Objekt. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Konvertiert die angegebene Zeichenkettendarstellung eines Datums- und Zeitwerts in das entsprechende [DateTime](./)-Objekt unter Verwendung kulturspezifischer Formatinformationen. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Konvertiert die angegebene Zeichenkettendarstellung eines Datums- und Zeitwerts in das entsprechende [DateTime](./)-Objekt unter Verwendung des angegebenen Formats und kulturspezifischer Formatinformationen. Das Format der Zeichenkettendarstellung muss exakt dem angegebenen Format entsprechen. Wirft eine Ausnahme, wenn die Konvertierung fehlschlägt. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Konvertiert die angegebene Zeichenkettendarstellung eines Datums- und Zeitwerts in das entsprechende [DateTime](./)-Objekt unter Verwendung der angegebenen Formate, kulturspezifischer Formatinformationen und des Stils. Das Format der Zeichenkettendarstellung muss exakt einem oder mehreren der angegebenen Formate entsprechen. Wirft eine Ausnahme, wenn die Konvertierung fehlschlägt. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | Konstruiert ein neues [DateTime](./)-Objekt, das die gleiche Anzahl von Ticks wie das angegebene [DateTime](./)-Objekt darstellt und lokale Zeit, UTC-Zeit oder keine davon repräsentiert, wie durch das Argument **kind** angegeben. |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Gibt eine neue Instanz der [DateTime](./)-Klasse zurück, die den Datums- und Zeitwert darstellt, der das Ergebnis der Subtraktion des angegebenen Zeitintervalls vom vom aktuellen Objekt dargestellten Wert ist. |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | Gibt eine Instanz der [TimeSpan](../timespan/)-Klasse zurück, die das Zeitintervall zwischen den vom aktuellen und dem angegebenen Objekt dargestellten Datums- und Zeitwerten repräsentiert. |
| **int64_t** [ToBinary](./tobinary/)() const | Serialisiert das aktuelle Objekt. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Gibt einen Wert zurück, der den vom aktuellen Objekt dargestellten Datums- und Zeitwert als File-Zeit repräsentiert. |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | Konvertiert den vom aktuellen Objekt dargestellten Datums- und Zeitwert in UTC-File-Zeit. |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | Gibt eine neue Instanz der [DateTime](./)-Klasse zurück, die den vom aktuellen Objekt dargestellten Datums- und Zeitwert als lokale Zeit repräsentiert. |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | Gibt eine Zeichenkette zurück, die die Langdatums-Zeichenkettendarstellung des aktuellen Objekts enthält. |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | Gibt eine Zeichenkette zurück, die die Langzeit-Zeichenkettendarstellung des aktuellen Objekts enthält. |
| **double** [ToOADate](./tooadate/)() const | Gibt den vom aktuellen Objekt dargestellten Datums- und Zeitwert als OLE-Automation-Datum zurück. |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | Gibt eine Zeichenkette zurück, die die Kurzdatums-Zeichenkettendarstellung des aktuellen Objekts enthält. |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | Gibt eine Zeichenkette zurück, die die Kurzzeit-Zeichenkettendarstellung des aktuellen Objekts enthält. |
| [String](../string/) [ToString](./tostring/)() const | Gibt die Zeichenkettendarstellung des vom aktuellen Objekt dargestellten Datums- und Zeitwerts zurück, wobei die Formatierungskonventionen der aktuellen Kultur verwendet werden. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Gibt eine Zeichenkettendarstellung des vom aktuellen Objekt dargestellten Datums- und Zeitwerts zurück, wobei das angegebene Format und die von der aktuellen Kultur definierten Formatierungskonventionen verwendet werden. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Gibt eine Zeichenkettendarstellung des vom aktuellen Objekt dargestellten Datums- und Zeitwerts zurück, wobei die angegebenen Formatinformationen verwendet werden. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Gibt eine Zeichenkettendarstellung des vom aktuellen Objekt dargestellten Datums- und Zeitwerts zurück, wobei die angegebenen Formatinformationen verwendet werden. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | Gibt eine neue Instanz der [DateTime](./)-Klasse zurück, die den vom aktuellen Objekt dargestellten Datums- und Zeitwert als UTC repräsentiert. |
| time_t [ToUnixTime](./tounixtime/)() const | Gibt einen Wert zurück, der den vom aktuellen Objekt dargestellten Datums- und Zeitwert als Unix-Zeit repräsentiert. FÜR INTERNEN GEBRAUCH. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | Konvertiert die angegebene Zeichenkettendarstellung eines Datums- und Zeitwerts in das entsprechende [DateTime](./)-Objekt. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Konvertiert die angegebene Zeichenkettendarstellung eines Datums- und Zeitwerts in das entsprechende [DateTime](./)-Objekt unter Verwendung der angegebenen kulturspezifischen Formatinformationen und des Stils. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Konvertiert die angegebene Zeichenkettendarstellung eines Datums- und Zeitwerts in das entsprechende [DateTime](./)-Objekt unter Verwendung des angegebenen Formats, kulturspezifischer Formatinformationen und des Stils. Das Format der Zeichenkettendarstellung muss exakt dem angegebenen Format entsprechen. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Konvertiert die angegebene Zeichenkettendarstellung eines Datums- und Zeitwerts in das entsprechende [DateTime](./)-Objekt unter Verwendung der angegebenen Formate, kulturspezifischer Formatinformationen und des Stils. Das Format der Zeichenkettendarstellung muss exakt einem oder mehreren der angegebenen Formate entsprechen. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Gibt ein [TypeInfo](../typeinfo/)-Objekt zurück, das Informationen über diese Klasse enthält. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | Die Anzahl von 100-Nanosekunden im Zeitintervall zwischen dem minimal möglichen und dem maximal möglichen [DateTime](./)-Wert. |
| static [MaxValue](./maxvalue/) | Eine Instanz der [DateTime](./)-Klasse, die den maximal möglichen Datums- und Zeitwert darstellt. |
| static constexpr [MinTicks](./minticks/) | Die minimale Anzahl von Ticks, die eine Instanz der [DateTime](./)-Klasse darstellen kann. |
| static [MinValue](./minvalue/) | Eine Instanz der [DateTime](./)-Klasse, die den minimal möglichen Datums- und Zeitwert darstellt. |
| static constexpr [TicksPerDay](./ticksperday/) | Die Anzahl von Ticks in einem Tag. |
| static constexpr [TicksPerHour](./ticksperhour/) | Die Anzahl von Ticks in einer Stunde. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | Die Anzahl von Ticks in einer Mikrosekunde. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Die Anzahl von Ticks in einer Millisekunde. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Die Anzahl von Ticks in einer Minute. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Die Anzahl von Ticks in einer Sekunde. |
| static [UnixEpoch](./unixepoch/) | Eine Instanz der [DateTime](./)-Klasse, die den Start der Unix-Epoche (1970-01-01 00:00:00) darstellt. |

## Anmerkungen

```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // Erstelle die 'DateTime'-Klasseninstanz.
  DateTime dateTime{1990, 10, 30};

  // Gib die Instanz in mehreren Formaten aus.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
Dieses Codebeispiel erzeugt die folgende Ausgabe:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)