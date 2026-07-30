---
title: DateTimeOffset
second_title: Riferimento API di Aspose.Slides per C++
description: "Contiene la data e l'ora del giorno relative al Tempo Universale Coordinato. Gli oggetti di questa classe devono essere allocati solo utilizzando la funzione System::MakeObject(). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e utilizza questo puntatore per passarla alle funzioni come argomento."
type: docs
weight: 235
url: /it/system/datetimeoffset/
---
## DateTimeOffset classe

Contiene la data e l'ora del giorno relative al Tempo Universale Coordinato. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../makeobject/). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

```cpp
class DateTimeOffset
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | Aggiunge un intervallo di tempo specificato all'oggetto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | Aggiunge un numero specificato di giorni all'oggetto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | Aggiunge un numero specificato di ore all'oggetto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Aggiunge un numero specificato di millisecondi all'oggetto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | Aggiunge un numero specificato di minuti all'oggetto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | Aggiunge un numero specificato di mesi all'oggetto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | Aggiunge un numero specificato di secondi all'oggetto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | Aggiunge un numero specificato di tick all'oggetto [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | Aggiunge un numero specificato di anni all'oggetto [DateTimeOffset](./). |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Confronta due oggetti [DateTimeOffset](./). |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | Confronta due oggetti [DateTimeOffset](./). |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Confronta due oggetti [DateTimeOffset](./). |
| constexpr [DateTimeOffset](./datetimeoffset/)() | Costruttore predefinito. |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | Costruttore. |
| [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | Costruttore. |
| [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | Costruttore. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | Costruttore. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | Costruttore. |
| [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | Costruttore. |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Verifica se due oggetti [DateTimeOffset](./) rappresentano lo stesso istante temporale. |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | Verifica se due oggetti [DateTimeOffset](./) rappresentano lo stesso istante temporale. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Verifica se due oggetti [DateTimeOffset](./) rappresentano lo stesso istante temporale. |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | Verifica se due oggetti [DateTimeOffset](./) rappresentano lo stesso istante temporale e hanno lo stesso offset. |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Verifica se due oggetti [DateTimeOffset](./) rappresentano lo stesso istante temporale e hanno lo stesso offset. |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) da file time a data e ora con offset locale. |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix-time a oggetto [DateTimeOffset](./). |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix-time a oggetto [DateTimeOffset](./). |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | Restituisce la componente data dell'oggetto corrente. |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | Restituisce il valore [DateTime](../datetime/). |
| int [get_Day](./get_day/)() const | Restituisce il giorno del mese dell'oggetto corrente. |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Restituisce il giorno della settimana dell'oggetto corrente. |
| int [get_DayOfYear](./get_dayofyear/)() const | Restituisce il giorno dell'anno dell'oggetto corrente. |
| int [get_Hour](./get_hour/)() const | Restituisce la componente ora dell'oggetto corrente. |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | Restituisce il valore [DateTime](../datetime/) che rappresenta la data e l'ora locali. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Restituisce la componente millisecondi dell'oggetto corrente. |
| int [get_Minute](./get_minute/)() const | Restituisce la componente minuti dell'oggetto corrente. |
| int [get_Month](./get_month/)() const | Restituisce la componente mese dell'oggetto corrente. |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | Restituisce [DateTimeOffset](./) la cui data e ora sono impostate al tempo locale corrente e il cui offset è impostato all'offset del tempo locale. |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | Restituisce l'offset dal UTC. |
| constexpr int [get_Second](./get_second/)() const | Restituisce la componente secondi dell'oggetto corrente. |
| **int64_t** [get_Ticks](./get_ticks/)() const | Restituisce il numero di tick dell'oggetto corrente. |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Restituisce l'ora del giorno dell'oggetto corrente. |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | Restituisce il valore [DateTime](../datetime/) che rappresenta la data e l'ora UTC. |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | Restituisce [DateTimeOffset](./) la cui data e ora sono impostate al tempo UTC corrente e il cui offset è [TimeSpan::Zero](../timespan/zero/). |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | Restituisce il numero di tick dell'oggetto corrente in tempo UTC. |
| int [get_Year](./get_year/)() const | Restituisce la componente anno dell'oggetto corrente. |
| int [GetHashCode](./gethashcode/)() const | Restituisce il codice hash per l'oggetto [DateTimeOffset](./) corrente. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | Determina se l'oggetto corrente e l'oggetto [DateTimeOffset](./) specificato rappresentano valori di data e ora distinti. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Restituisce una nuova istanza della classe [DateTimeOffset](./) che rappresenta il valore di data e ora che è la somma del valore rappresentato dall'oggetto corrente e dell'intervallo di tempo specificato. |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Restituisce una nuova istanza della classe [DateTimeOffset](./) che rappresenta il valore di data e ora risultante dalla sottrazione dell'intervallo di tempo specificato dal valore rappresentato dall'oggetto corrente. |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | Restituisce un'istanza della classe [TimeSpan](../timespan/) che rappresenta l'intervallo di tempo tra i valori di data e ora rappresentati dall'oggetto corrente e da quello specificato. |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | Determina se l'oggetto corrente rappresenta il valore di data e ora che è precedente al valore rappresentato dall'oggetto [DateTimeOffset](./) specificato. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | Determina se l'oggetto corrente rappresenta il valore di data e ora che è precedente o uguale al valore rappresentato dall'oggetto [DateTimeOffset](./) specificato. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | Determina se l'oggetto corrente e l'oggetto [DateTimeOffset](./) specificato rappresentano lo stesso valore di data e ora. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | Determina se l'oggetto corrente rappresenta il valore di data e ora che è successivo al valore rappresentato dall'oggetto [DateTimeOffset](./) specificato. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | Determina se l'oggetto corrente rappresenta il valore di data e ora che è successivo o uguale al valore rappresentato dall'oggetto [DateTimeOffset](./) specificato. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | Converte la stringa specificata nell'equivalente [DateTimeOffset](./). |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converte la stringa specificata in un oggetto [DateTimeOffset](./) utilizzando il provider di formato e lo stile di formattazione specificati. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converte la stringa specificata in un oggetto [DateTimeOffset](./) utilizzando il formato, il provider di formato e lo stile di formattazione specificati. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Converte la stringa specificata in un oggetto [DateTimeOffset](./) utilizzando i formati, il provider di formato e lo stile di formattazione specificati. |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Sottrae un intervallo di tempo specificato dall'oggetto corrente. |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | Sottrae un valore [DateTimeOffset](./) specificato dall'oggetto corrente. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Converte l'oggetto corrente in file time [Windows](../../system.windows/). |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | Converte l'oggetto corrente in un oggetto che rappresenta l'ora locale. |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | Sostituisce l'offset dell'oggetto corrente con l'offset specificato. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Converte l'oggetto corrente in stringa usando il formato e il provider di formato specificati. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Converte l'oggetto corrente in stringa usando il provider di formato specificato. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Converte l'oggetto corrente in stringa usando il formato specificato. |
| [String](../string/) [ToString](./tostring/)() const | Converte l'oggetto corrente in stringa. |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | Converte l'oggetto corrente in un oggetto che rappresenta il tempo UTC. |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Restituisce i millisecondi trascorsi dall'inizio dell'epoch Unix. |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Restituisce i secondi trascorsi dall'inizio dell'epoch Unix. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | Tenta di convertire la stringa specificata in un oggetto [DateTimeOffset](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Tenta di convertire la stringa specificata in un oggetto [DateTimeOffset](./) usando il provider di formato e lo stile di formattazione specificati. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Tenta di convertire la stringa specificata in un oggetto [DateTimeOffset](./) usando i formati, il provider di formato e lo stile di formattazione specificati. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Tenta di convertire la stringa specificata in un oggetto [DateTimeOffset](./) usando il formato, il provider di formato e lo stile di formattazione specificati. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Restituisce un oggetto [TypeInfo](../typeinfo/) che rappresenta la struttura [TimeSpan](../timespan/). |

## Campi

| Campo | Descrizione |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | Restituisce l'offset massimo in tick. |
| static [MaxValue](./maxvalue/) | Restituisce il valore [DateTimeOffset](./) più grande. |
| static constexpr [MinOffset](./minoffset/) | Restituisce l'offset minimo in tick. |
| static [MinValue](./minvalue/) | Restituisce il valore [DateTimeOffset](./) più precoce. |
| static [UnixEpoch](./unixepoch/) | Restituisce l'inizio dell'epoch Unix. |

## Vedi anche

* Namespace [System](../)
* Libreria [Aspose.Slides](../../)