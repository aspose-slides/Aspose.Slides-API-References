---
title: DateTimeOffset
second_title: Aspose.Slides für C++ API-Referenz
description: "Enthält das Datum und die Uhrzeit relativ zur koordinierten Weltzeit (UTC). Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse stets in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 235
url: /de/system/datetimeoffset/
---
## DateTimeOffset Klasse

Enthält das Datum und die Uhrzeit relativ zur koordinierten Weltzeit. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../makeobject/)-Funktion zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class DateTimeOffset
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | Fügt dem [DateTimeOffset](./)-Objekt ein angegebenes Zeitintervall hinzu. |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | Fügt dem [DateTimeOffset](./)-Objekt eine angegebene Anzahl von Tagen hinzu. |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | Fügt dem [DateTimeOffset](./)-Objekt eine angegebene Anzahl von Stunden hinzu. |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Fügt dem [DateTimeOffset](./)-Objekt eine angegebene Anzahl von Millisekunden hinzu. |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | Fügt dem [DateTimeOffset](./)-Objekt eine angegebene Anzahl von Minuten hinzu. |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | Fügt dem [DateTimeOffset](./)-Objekt eine angegebene Anzahl von Monaten hinzu. |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | Fügt dem [DateTimeOffset](./)-Objekt eine angegebene Anzahl von Sekunden hinzu. |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | Fügt dem [DateTimeOffset](./)-Objekt eine angegebene Anzahl von Ticks hinzu. |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | Fügt dem [DateTimeOffset](./)-Objekt eine angegebene Anzahl von Jahren hinzu. |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Vergleicht zwei [DateTimeOffset](./)-Objekte. |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | Vergleicht zwei [DateTimeOffset](./)-Objekte. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Vergleicht zwei [DateTimeOffset](./)-Objekte. |
| constexpr [DateTimeOffset](./datetimeoffset/)() | Standardkonstruktor. |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | Konstruktor. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | Konstruktor. |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Prüft, ob zwei [DateTimeOffset](./)-Objekte denselben Zeitpunkt darstellen. |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | Prüft, ob zwei [DateTimeOffset](./)-Objekte denselben Zeitpunkt darstellen. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Prüft, ob zwei [DateTimeOffset](./)-Objekte denselben Zeitpunkt darstellen. |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | Prüft, ob zwei [DateTimeOffset](./)-Objekte denselben Zeitpunkt darstellen und denselben Offset besitzen. |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Prüft, ob zwei [DateTimeOffset](./)-Objekte denselben Zeitpunkt darstellen und denselben Offset besitzen. |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) Dateizeit in Datum und Uhrzeit mit lokaler Zeitverschiebung umwandeln. |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix-Zeit in ein [DateTimeOffset](./)-Objekt umwandeln. |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix-Zeit in ein [DateTimeOffset](./)-Objekt umwandeln. |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | Ermittelt die Datumskomponente des aktuellen Objekts. |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | Ermittelt den [DateTime](../datetime/)-Wert. |
| int [get_Day](./get_day/)() const | Ermittelt den Tag des Monats des aktuellen Objekts. |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Ermittelt den Wochentag des aktuellen Objekts. |
| int [get_DayOfYear](./get_dayofyear/)() const | Ermittelt den Tag im Jahr des aktuellen Objekts. |
| int [get_Hour](./get_hour/)() const | Ermittelt die Stunden-Komponente des aktuellen Objekts. |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | Ermittelt den [DateTime](../datetime/)-Wert, der das lokale Datum und die lokale Uhrzeit repräsentiert. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Ermittelt die Millisekunden-Komponente des aktuellen Objekts. |
| int [get_Minute](./get_minute/)() const | Ermittelt die Minuten-Komponente des aktuellen Objekts. |
| int [get_Month](./get_month/)() const | Ermittelt die Monats-Komponente des aktuellen Objekts. |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | Ermittelt ein [DateTimeOffset](./), dessen Datum und Uhrzeit auf die aktuelle lokale Zeit gesetzt sind und dessen Offset auf den Offset der lokalen Zeit gesetzt ist. |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | Ermittelt den Offset von UTC. |
| constexpr int [get_Second](./get_second/)() const | Ermittelt die Sekunden-Komponente des aktuellen Objekts. |
| **int64_t** [get_Ticks](./get_ticks/)() const | Ermittelt die Anzahl der Ticks des aktuellen Objekts. |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Ermittelt die Tageszeit des aktuellen Objekts. |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | Ermittelt den [DateTime](../datetime/)-Wert, der das UTC-Datum und die UTC-Uhrzeit repräsentiert. |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | Ermittelt ein [DateTimeOffset](./), dessen Datum und Uhrzeit auf die aktuelle UTC-Zeit gesetzt sind und dessen Offset [TimeSpan::Zero](../timespan/zero/) ist. |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | Ermittelt die Anzahl der Ticks des aktuellen Objekts in UTC-Zeit. |
| int [get_Year](./get_year/)() const | Ermittelt die Jahres-Komponente des aktuellen Objekts. |
| int [GetHashCode](./gethashcode/)() const | Ermittelt den Hash-Code für das aktuelle [DateTimeOffset](./)-Objekt. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | Bestimmt, ob das aktuelle Objekt und das angegebene [DateTimeOffset](./)-Objekt unterschiedliche Datum- und Uhrzeitwerte darstellen. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Gibt eine neue Instanz der [DateTimeOffset](./)-Klasse zurück, die den Datum- und Uhrzeitwert darstellt, der die Summe des durch das aktuelle Objekt dargestellten Werts und des angegebenen Zeitintervalls ist. |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Gibt eine neue Instanz der [DateTimeOffset](./)-Klasse zurück, die den Datum- und Uhrzeitwert darstellt, der sich aus der Subtraktion des angegebenen Zeitintervalls vom durch das aktuelle Objekt dargestellten Wert ergibt. |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | Gibt eine Instanz der [TimeSpan](../timespan/)-Klasse zurück, die das Zeitintervall zwischen den von dem aktuellen und dem angegebenen Objekt dargestellten Datum- und Uhrzeitwerten repräsentiert. |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | Bestimmt, ob das aktuelle Objekt den Datum- und Uhrzeitwert darstellt, der früher ist als der vom angegebenen [DateTimeOffset](./)-Objekt dargestellte Wert. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | Bestimmt, ob das aktuelle Objekt den Datum- und Uhrzeitwert darstellt, der früher oder gleich dem vom angegebenen [DateTimeOffset](./)-Objekt dargestellten Wert ist. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | Bestimmt, ob das aktuelle Objekt und das angegebene [DateTimeOffset](./)-Objekt denselben Datum- und Uhrzeitwert darstellen. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | Bestimmt, ob das aktuelle Objekt den Datum- und Uhrzeitwert darstellt, der später ist als der vom angegebenen [DateTimeOffset](./)-Objekt dargestellte Wert. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | Bestimmt, ob das aktuelle Objekt den Datum- und Uhrzeitwert darstellt, der später oder gleich dem vom angegebenen [DateTimeOffset](./)-Objekt dargestellten Wert ist. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | Konvertiert den angegebenen String in das [DateTimeOffset](./)-Äquivalent. |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Konvertiert den angegebenen String in ein [DateTimeOffset](./)-Objekt unter Verwendung des angegebenen Format-Providers und des Formatierungsstils. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Konvertiert den angegebenen String in ein [DateTimeOffset](./)-Objekt unter Verwendung des angegebenen Formats, des Format-Providers und des Formatierungsstils. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Konvertiert den angegebenen String in ein [DateTimeOffset](./)-Objekt unter Verwendung der angegebenen Formate, des Format-Providers und des Formatierungsstils. |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Subtrahiert ein angegebenes Zeitintervall vom aktuellen Objekt. |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | Subtrahiert einen angegebenen [DateTimeOffset](./)-Wert vom aktuellen Objekt. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Konvertiert das aktuelle Objekt in die [Windows](../../system.windows/)-Dateizeit. |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | Konvertiert das aktuelle Objekt in ein Objekt, das die lokale Zeit darstellt. |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | Ersetzt den Offset des aktuellen Objekts durch den angegebenen Offset. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Konvertiert das aktuelle Objekt in einen String unter Verwendung des angegebenen Formats und des Format-Providers. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Konvertiert das aktuelle Objekt in einen String unter Verwendung des angegebenen Format-Providers. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Konvertiert das aktuelle Objekt in einen String unter Verwendung des angegebenen Formats. |
| [String](../string/) [ToString](./tostring/)() const | Konvertiert das aktuelle Objekt in einen String. |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | Konvertiert das aktuelle Objekt in ein Objekt, das die UTC-Zeit darstellt. |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Ermittelt die seit Beginn der Unix-Epoche vergangenen Millisekunden. |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Ermittelt die seit Beginn der Unix-Epoche vergangenen Sekunden. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | Versucht, den angegebenen String in ein [DateTimeOffset](./)-Objekt zu konvertieren. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Versucht, den angegebenen String in ein [DateTimeOffset](./)-Objekt unter Verwendung des angegebenen Format-Providers und des Formatierungsstils zu konvertieren. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Versucht, den angegebenen String in ein [DateTimeOffset](./)-Objekt unter Verwendung der angegebenen Formate, des Format-Providers und des Formatierungsstils zu konvertieren. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Versucht, den angegebenen String in ein [DateTimeOffset](./)-Objekt unter Verwendung des angegebenen Formats, des Format-Providers und des Formatierungsstils zu konvertieren. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Gibt ein [TypeInfo](../typeinfo/)-Objekt zurück, das die [TimeSpan](../timespan/)-Struktur repräsentiert. |

## Felder

| Feld | Beschreibung |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | Gibt den maximalen Offset in Ticks zurück. |
| static [MaxValue](./maxvalue/) | Gibt den größten [DateTimeOffset](./)-Wert zurück. |
| static constexpr [MinOffset](./minoffset/) | Gibt den minimalen Offset in Ticks zurück. |
| static [MinValue](./minvalue/) | Gibt den frühesten [DateTimeOffset](./)-Wert zurück. |
| static [UnixEpoch](./unixepoch/) | Gibt den Beginn der Unix-Epoche zurück. |

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)