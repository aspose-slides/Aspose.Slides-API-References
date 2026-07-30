---
title: Calendar
second_title: Riferimento API Aspose.Slides per C++
description: "Calendario che definisce come le date vengono gestite, calcolate, formattate, ecc. Le operazioni di impostazione sono abilitate solo su oggetti non di sola lettura. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di assert. Avvolgi sempre questa classe in un puntatore System::SmartPtr e usa questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 1
url: /it/system.globalization/calendar/
---
## Calendar classe

[Calendar](./) che definisce come le date vengono gestite, calcolate, formattate, ecc. Le operazioni setter sono abilitate solo su oggetti non di sola lettura. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di assert. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

```cpp
class Calendar : public System::ICloneable
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](./adddays/)([DateTime](../../system/datetime/), int) const | Aggiunge giorni al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddHours](./addhours/)([DateTime](../../system/datetime/), int) const | Aggiunge ore al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](./addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Aggiunge millisecondi al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](./addminutes/)([DateTime](../../system/datetime/), int) const | Aggiunge minuti al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddMonths](./addmonths/)([DateTime](../../system/datetime/), int) const | Aggiunge mesi al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](./addseconds/)([DateTime](../../system/datetime/), int) const | Aggiunge secondi al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](./addweeks/)([DateTime](../../system/datetime/), int) const | Aggiunge settimane al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddYears](./addyears/)([DateTime](../../system/datetime/), int) const | Aggiunge anni al punto temporale. |
|  [Calendar](./calendar/)(const [Calendar](./)\&) | Informazioni RTTI. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](../../system/icloneable/clone/)() | Crea una copia dell'oggetto corrente e restituisce un puntatore condiviso ad esso. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| virtual [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const | Ottiene il tipo di algoritmo. |
| int [get_CurrentEra](./get_currentera/)() const | Ottiene l'indice dell'era corrente. |
| int [get_CurrentEraValue](./get_currenteravalue/)() const | Ottiene il valore dell'era corrente. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const | Ottiene l'elenco delle ere esistenti nel calendario. |
| virtual [Details::CalendarId](../../system.globalization.details/calendarid/) [get_ID](./get_id/)() const | Ottiene l'identificatore del calendario. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Verifica se il calendario è di sola lettura. |
| virtual [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const | Punto temporale massimo supportato dal calendario. |
| virtual [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const | Punto temporale minimo supportato dal calendario. |
| virtual int [get_TwoDigitYearMax](./get_twodigityearmax/)() const | Ottiene l'ultimo anno che può essere rappresentato con 2 cifre. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const | Ottiene il giorno del mese per il punto temporale specificato. |
| virtual [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const | Ottiene il giorno della settimana per il punto temporale specificato. |
| virtual int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const | Ottiene il giorno dell'anno per il punto temporale specificato. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Ottiene il numero di giorni nel mese specifico. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Ottiene il numero di giorni nel mese specifico. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Ottiene il numero di giorni nell'anno specifico. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Ottiene il numero di giorni nell'anno specifico. |
| virtual int [GetEra](./getera/)([DateTime](../../system/datetime/)) const | Ottiene l'era per il punto temporale specificato. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual int [GetHour](./gethour/)([DateTime](../../system/datetime/)) const | Ottiene le ore per il punto temporale specificato. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Ottiene il mese bisestile per l'anno specificato. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Ottiene il mese bisestile per l'anno specificato. |
| virtual **double** [GetMilliseconds](./getmilliseconds/)([DateTime](../../system/datetime/)) const | Ottiene i millisecondi per il punto temporale specificato. |
| virtual int [GetMinute](./getminute/)([DateTime](../../system/datetime/)) const | Ottiene i minuti per il punto temporale specificato. |
| virtual int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const | Ottiene il mese per il punto temporale specificato. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Ottiene il numero di mesi nell'anno specificato. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Ottiene il numero di mesi nell'anno specificato. |
| virtual int [GetSecond](./getsecond/)([DateTime](../../system/datetime/)) const | Ottiene i secondi per il punto temporale specificato. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](./getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Ottiene la settimana dell'anno per il punto temporale specificato. |
| virtual int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const | Ottiene l'anno per il punto temporale specificato. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Verifica se il giorno è bisestile. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Verifica se il giorno è bisestile. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Verifica se il mese è bisestile. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Verifica se il mese è bisestile. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Verifica se l'anno è bisestile. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Verifica se l'anno è bisestile. |
| **bool** [IsValidDay](./isvalidday/)(int, int, int, int) const | Verifica i valori di anno, mese, giorno e era. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione di copie per le sottoclassi. |
| [Calendar](./)\& [operator=](./operator_equal/)(const [Calendar](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) |  |
| static [CalendarPtr](../calendarptr/) [ReadOnly](./readonly/)(const [CalendarPtr](../calendarptr/)\&) | Ottiene la versione di sola lettura del calendario. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento l'oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| virtual void [set_TwoDigitYearMax](./set_twodigityearmax/)(int) | Imposta l'ultimo anno che può essere rappresentato con 2 cifre. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore weak (piuttosto che shared). Consente di cambiare i puntatori nei contenitori in modalità weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Costruisce l'oggetto [DateTime](../../system/datetime/) dai componenti. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Costruisce l'oggetto [DateTime](../../system/datetime/) dai componenti. |
| virtual int [ToFourDigitYear](./tofourdigityear/)(int) const | Converte l'anno in anno a 4 cifre usando la proprietà TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento weak. Non dovrebbe essere chiamato direttamente; utilizzare invece smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [ICloneable](../../system/icloneable/)
* Spazio dei nomi [System::Globalization](../)
* Libreria [Aspose.Slides](../../)