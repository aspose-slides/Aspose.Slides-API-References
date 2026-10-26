---
title: DateTime
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un valore specifico di data e ora sul continuum temporale. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe System::SmartPtr per gestire oggetti di questo tipo."
type: docs
weight: 222
url: /it/system/datetime/
---
## classe DateTime


Rappresenta un valore specifico di data e ora sulla continuità temporale. Questo tipo dovrebbe essere allocato nello stack e passato alle funzioni per valore o per riferimento. Non utilizzare mai la classe [System::SmartPtr](../smartptr/) per gestire oggetti di questo tipo.

```cpp
class DateTime
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | Restituisce una nuova istanza della classe [DateTime](./) che rappresenta un valore di data e ora risultante dall'aggiunta dell'intervallo di tempo specificato al valore di data e ora rappresentato dall'oggetto corrente. |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | Restituisce una nuova istanza della classe [DateTime](./) che rappresenta il valore di data e ora ottenuto dalla somma del valore rappresentato dall'oggetto corrente e del numero specificato di giorni. |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | Restituisce una nuova istanza della classe [DateTime](./) che rappresenta il valore di data e ora ottenuto dalla somma del valore rappresentato dall'oggetto corrente e del numero specificato di ore. |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Restituisce una nuova istanza della classe [DateTime](./) che rappresenta il valore di data e ora ottenuto dalla somma del valore rappresentato dall'oggetto corrente e del numero specificato di millisecondi. |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | Restituisce una nuova istanza della classe [DateTime](./) che rappresenta il valore di data e ora ottenuto dalla somma del valore rappresentato dall'oggetto corrente e del numero specificato di minuti. |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | Restituisce una nuova istanza della classe [DateTime](./) che rappresenta il valore di data e ora ottenuto dalla somma del valore rappresentato dall'oggetto corrente e del numero specificato di mesi. |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | Restituisce una nuova istanza della classe [DateTime](./) che rappresenta il valore di data e ora ottenuto dalla somma del valore rappresentato dall'oggetto corrente e del numero specificato di secondi. |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | Restituisce una nuova istanza della classe [DateTime](./) che rappresenta il valore di data e ora ottenuto dalla somma del valore rappresentato dall'oggetto corrente e del numero specificato di intervalli di 100 nanosecondi. |
| [DateTime](./) [AddYears](./addyears/)(int) const | Restituisce una nuova istanza della classe [DateTime](./) che rappresenta il valore di data e ora pari a quello rappresentato dall'oggetto corrente con la componente dell'anno aumentata del numero specificato. |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | Confronta due valori rappresentati dalle istanze specificate della classe [DateTime](./) e restituisce il valore che indica le posizioni relative dei valori sulla linea temporale. |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | Confronta due valori di data e ora rappresentati dall'oggetto corrente e dall'istanza specificata della classe [DateTime](./) e restituisce il valore che indica le posizioni relative dei valori sulla linea temporale. |
| constexpr [DateTime](./datetime/)() | Costruisce un'istanza che rappresenta il più piccolo valore possibile di data e ora, uguale a MinValue. |
|  [DateTime](./datetime/)(int, int, int) | Costruisce un'istanza che rappresenta un valore di data e ora specificato come un determinato anno, mese e giorno. |
|  [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Costruisce un'istanza che rappresenta un valore di data e ora specificato come un determinato anno, mese e giorno nel calendario specificato. |
|  [DateTime](./datetime/)(int, int, int, int, int, int) | Costruisce un'istanza che rappresenta un valore di data e ora specificato come un determinato anno, mese, giorno, ora, minuto e secondo. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Costruisce un'istanza che rappresenta un valore di data e ora specificato come un determinato anno, mese, giorno, ora, minuto e secondo. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Costruisce un'istanza che rappresenta un valore di data e ora specificato come un determinato anno, mese, giorno, ora, minuto e secondo nel calendario specificato. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Costruisce un'istanza che rappresenta un valore di data e ora specificato come un determinato anno, mese, giorno, ora, minuto, secondo e millisecondo. |
|  [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | Costruisce un'istanza che rappresenta un valore di data e ora specificato come un determinato anno, mese, giorno, ora, minuto, secondo e millisecondo nel calendario specificato. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | Costruisce un'istanza che rappresenta un valore di data e ora specificato come un numero di tick. |
|  [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | Costruisce un'istanza che rappresenta un valore di data e ora specificato come un numero di tick. PER USO INTERNO. |
|  [DateTime](./datetime/)(const [DateTime](./)\&) | Copia-costruisce un'istanza. |
| static int [DaysInMonth](./daysinmonth/)(int, int) | Restituisce il numero di giorni nel mese specificato dell'anno specificato. |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | Determina se le istanze specificate della classe [DateTime](./) rappresentano lo stesso valore di data e ora. |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | Determina se l'istanza specificata della classe [DateTime](./) rappresenta lo stesso valore di data e ora dell'oggetto corrente. |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | Deserializza il valore di data e ora dal intero non firmato a 64 bit specificato e imposta la nuova istanza della classe [DateTime](./) su quel valore. |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | Converte il file time specificato in un'istanza della classe [DateTime](./) che rappresenta lo stesso valore di data e ora dell'ora locale. |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | Converte il file time specificato in un'istanza della classe [DateTime](./) che rappresenta lo stesso valore di data e ora dell'ora UTC. |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | Restituisce un'istanza della classe [DateTime](./) che rappresenta il valore di data e ora equivalente alla OLE Automation Date specificata. |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | Converte il valore di tempo Unix specificato in un'istanza della classe [DateTime](./). PER USO INTERNO. |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | Restituisce una nuova istanza della classe [DateTime](./) che rappresenta la parte data della data e ora rappresentata dall'oggetto corrente con ogni componente della parte ora impostato a 0. |
| int [get_Day](./get_day/)() const | Restituisce il numero ordinale del giorno nel mese rappresentato dall'oggetto corrente. |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Restituisce un valore che rappresenta il giorno della settimana rappresentato dall'oggetto corrente. |
| int [get_DayOfYear](./get_dayofyear/)() const | Restituisce il numero ordinale del giorno nell'anno rappresentato dall'oggetto corrente. |
| constexpr int [get_Hour](./get_hour/)() const | Restituisce la componente ora del valore di data e ora rappresentato dall'oggetto corrente. |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | Restituisce il valore che indica se la data e ora rappresentata dall'oggetto corrente è locale, UTC o nessuna delle due. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Restituisce la componente millisecondo del valore di data e ora rappresentato dall'oggetto corrente. |
| constexpr int [get_Minute](./get_minute/)() const | Restituisce la componente minuto del valore di data e ora rappresentato dall'oggetto corrente. |
| int [get_Month](./get_month/)() const | Restituisce il numero ordinale del mese nell'anno rappresentato dall'oggetto corrente. |
| static [DateTime](./) [get_Now](./get_now/)() | Restituisce un'istanza della classe [DateTime](./) che rappresenta l'ora corrente come ora locale. |
| constexpr int [get_Second](./get_second/)() const | Restituisce la componente secondo del valore di data e ora rappresentato dall'oggetto corrente. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Restituisce un numero di intervalli di 100 nanosecondi trascorsi dal 0:00:00 UTC, 1 gennaio 0001, nel calendario gregoriano fino al valore di data e ora rappresentato dall'oggetto corrente. |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Restituisce il valore che rappresenta l'intervallo di tempo dall'inizio della giornata rappresentata dall'oggetto corrente fino al valore di data e ora rappresentato dall'oggetto corrente. |
| static [DateTime](./) [get_Today](./get_today/)() | Restituisce un'istanza della classe [DateTime](./) che rappresenta la data corrente con ogni componente della parte ora del valore rappresentato dall'oggetto impostata a 0. |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | Restituisce un'istanza della classe [DateTime](./) che rappresenta l'ora corrente come UTC. |
| int [get_Year](./get_year/)() const | Restituisce l'anno rappresentato dall'oggetto corrente. |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | Recupera le parti della data. PER USO INTERNO. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | Restituisce un array di stringhe in cui ogni elemento è la rappresentazione testuale dell'oggetto corrente formattata con uno dei specificatori di formato standard per data e ora. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | Restituisce un array di stringhe in cui ogni elemento è la rappresentazione testuale dell'oggetto corrente formattata con lo specificatore di formato standard per data e ora specificato. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Restituisce un array di stringhe in cui ogni elemento è la rappresentazione testuale dell'oggetto corrente formattata con uno dei specificatori di formato standard per data e ora e con il provider di formato specificato. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Restituisce un array di stringhe in cui ogni elemento è la rappresentazione testuale dell'oggetto corrente formattata con lo specificatore di formato standard per data e ora specificato e con il provider di formato. |
| int [GetHashCode](./gethashcode/)() const | Restituisce un codice hash per l'oggetto corrente. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | Determina se il valore di data e ora rappresentato dall'oggetto corrente rientra nell'intervallo dell'ora legale per il fuso orario corrente. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Determina se l'anno specificato è un anno bisestile. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | Determina se l'oggetto corrente e l'oggetto [DateTime](./) specificato rappresentano valori di data e ora distinti. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Restituisce una nuova istanza della classe [DateTime](./) che rappresenta il valore di data e ora ottenuto dalla somma del valore rappresentato dall'oggetto corrente e dell'intervallo di tempo specificato. |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | Imposta l'oggetto corrente al valore di data e ora ottenuto dalla somma del valore rappresentato dall'oggetto corrente e dell'intervallo di tempo specificato. |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Restituisce una nuova istanza della classe [DateTime](./) che rappresenta il valore di data e ora risultato dalla sottrazione dell'intervallo di tempo specificato dal valore rappresentato dall'oggetto corrente. |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | Restituisce un'istanza della classe [TimeSpan](../timespan/) che rappresenta l'intervallo di tempo tra i valori di data e ora rappresentati dall'oggetto corrente e dall'oggetto specificato. |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | Imposta l'oggetto corrente al valore di data e ora risultante dalla sottrazione dell'intervallo di tempo specificato dal valore di data e ora rappresentato dall'oggetto corrente. |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | Determina se l'oggetto corrente rappresenta il valore di data e ora che è precedente al valore rappresentato dall'oggetto [DateTime](./) specificato. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | Determina se l'oggetto corrente rappresenta il valore di data e ora che è precedente o uguale al valore rappresentato dall'oggetto [DateTime](./) specificato. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | Assegna il valore rappresentato dall'istanza [DateTime](./) specificata all'oggetto corrente. |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | Determina se l'oggetto corrente e l'oggetto [DateTime](./) specificato rappresentano lo stesso valore di data e ora. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | Determina se l'oggetto corrente rappresenta il valore di data e ora che è successivo al valore rappresentato dall'oggetto [DateTime](./) specificato. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | Determina se l'oggetto corrente rappresenta il valore di data e ora che è successivo o uguale al valore rappresentato dall'oggetto [DateTime](./) specificato. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | Converti la rappresentazione stringa specificata di un valore di data e ora nell'oggetto [DateTime](./) equivalente. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converti la rappresentazione stringa specificata di un valore di data e ora nell'oggetto [DateTime](./) equivalente usando informazioni di formato specifiche della cultura. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converti la rappresentazione stringa specificata di un valore di data e ora nell'oggetto [DateTime](./) equivalente usando il formato specificato e le informazioni di formato specifiche della cultura. Il formato della rappresentazione stringa deve corrispondere esattamente al formato specificato. Lancia un'eccezione se la conversione fallisce. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converti la rappresentazione stringa specificata di un valore di data e ora nell'oggetto [DateTime](./) equivalente usando i formati specificati, le informazioni di formato specifiche della cultura e lo stile. Il formato della rappresentazione stringa deve corrispondere esattamente a uno o più dei formati specificati. Lancia un'eccezione se la conversione fallisce. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | Costruisce un nuovo oggetto [DateTime](./) che rappresenta lo stesso numero di tick dell'oggetto [DateTime](./) specificato e rappresenta l'ora locale, l'ora UTC o nessuna delle due come specificato dall'argomento **kind**. |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Restituisce una nuova istanza della classe [DateTime](./) che rappresenta il valore di data e ora risultante dalla sottrazione dell'intervallo di tempo specificato dal valore rappresentato dall'oggetto corrente. |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | Restituisce un'istanza della classe [TimeSpan](../timespan/) che rappresenta l'intervallo di tempo tra i valori di data e ora rappresentati dall'oggetto corrente e da quello specificato. |
| **int64_t** [ToBinary](./tobinary/)() const | Serializza l'oggetto corrente. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Restituisce un valore che rappresenta il valore di data e ora dell'oggetto corrente come File time. |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | Converte il valore di data e ora rappresentato dall'oggetto corrente in File time UTC. |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | Restituisce una nuova istanza della classe [DateTime](./) che rappresenta il valore di data e ora dell'oggetto corrente come ora locale. |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | Restituisce una stringa che contiene la rappresentazione in data lunga dell'oggetto corrente. |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | Restituisce una stringa che contiene la rappresentazione in ora lunga dell'oggetto corrente. |
| **double** [ToOADate](./tooadate/)() const | Restituisce il valore di data e ora rappresentato dall'oggetto corrente come OLE Automation Date. |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | Restituisce una stringa che contiene la rappresentazione in data breve dell'oggetto corrente. |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | Restituisce una stringa che contiene la rappresentazione in ora breve dell'oggetto corrente. |
| [String](../string/) [ToString](./tostring/)() const | Restituisce la rappresentazione stringa del valore di data e ora rappresentato dall'oggetto corrente usando le convenzioni di formattazione definite dalla cultura corrente. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Restituisce una rappresentazione stringa del valore di data e ora rappresentato dall'oggetto corrente usando il formato specificato e le convenzioni di formattazione definite dalla cultura corrente. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Restituisce una rappresentazione stringa del valore di data e ora rappresentato dall'oggetto corrente usando le informazioni di formato specificate. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Restituisce una rappresentazione stringa del valore di data e ora rappresentato dall'oggetto corrente usando le informazioni di formato specificate. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | Restituisce una nuova istanza della classe [DateTime](./) che rappresenta il valore di data e ora dell'oggetto corrente come UTC. |
| time_t [ToUnixTime](./tounixtime/)() const | Restituisce un valore che rappresenta il valore di data e ora dell'oggetto corrente come tempo Unix. PER USO INTERNO. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | Converti la rappresentazione stringa specificata di un valore di data e ora nell'oggetto [DateTime](./) equivalente. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Converti la rappresentazione stringa specificata di un valore di data e ora nell'oggetto [DateTime](./) equivalente usando le informazioni di formato specifiche della cultura e lo stile specificati. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Converti la rappresentazione stringa specificata di un valore di data e ora nell'oggetto [DateTime](./) equivalente usando il formato specificato, le informazioni di formato specifiche della cultura e lo stile. Il formato della rappresentazione stringa deve corrispondere esattamente al formato specificato. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Converti la rappresentazione stringa specificata di un valore di data e ora nell'oggetto [DateTime](./) equivalente usando i formati specificati, le informazioni di formato specifiche della cultura e lo stile. Il formato della rappresentazione stringa deve corrispondere esattamente a uno o più dei formati specificati. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Restituisce un oggetto [TypeInfo](../typeinfo/) che contiene informazioni su questa classe. |

## Campi

| Campo | Descrizione |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | Il numero di 100 nanosecondi nell'intervallo di tempo tra il valore [DateTime](./) minimo possibile e quello massimo possibile. |
| static [MaxValue](./maxvalue/) | Un'istanza della classe [DateTime](./) che rappresenta il valore di data e ora massimo possibile. |
| static constexpr [MinTicks](./minticks/) | Il numero minimo di tick che un'istanza della classe [DateTime](./) può rappresentare. |
| static [MinValue](./minvalue/) | Un'istanza della classe [DateTime](./) che rappresenta il valore di data e ora minimo possibile. |
| static constexpr [TicksPerDay](./ticksperday/) | Il numero di tick in un giorno. |
| static constexpr [TicksPerHour](./ticksperhour/) | Il numero di tick in un'ora. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | Il numero di tick in un microsecondo. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Il numero di tick in un millisecondo. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Il numero di tick in un minuto. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Il numero di tick in un secondo. |
| static [UnixEpoch](./unixepoch/) | Un'istanza della classe [DateTime](./) che rappresenta l'inizio dell'epoch Unix (1970.01.01 00:00:00). |

## Osservazioni



```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // Crea l'istanza della classe 'DateTime'.
  DateTime dateTime{1990, 10, 30};

  // Stampa l'istanza nei vari formati.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
Questo esempio di codice produce il seguente output:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)