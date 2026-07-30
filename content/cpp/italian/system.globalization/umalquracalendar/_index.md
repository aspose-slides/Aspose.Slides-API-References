---
title: UmAlQuraCalendar
second_title: Riferimento API Aspose.Slides per C++
description: "Calendario Um Al Qura. Non implementato. Gli oggetti di questa classe devono essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocerebbe errori di runtime e/o fallimenti di asserzione. Avvolgere sempre questa classe in un puntatore System::SmartPtr e usare questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 391
url: /it/system.globalization/umalquracalendar/
---
## UmAlQuraCalendar classe

Calendario Um Al Qura. Non implementato. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo nello stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fallimenti di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usare questo puntatore per passarlo alle funzioni come argomento.

```cpp
class UmAlQuraCalendar : public System::Globalization::Calendar
```

## Metodi

| Method | Description |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Aggiunge giorni al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Aggiunge ore al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Aggiunge millisecondi al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Aggiunge minuti al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Aggiunge mesi al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Aggiunge secondi al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Aggiunge settimane al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Aggiunge anni al punto temporale. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | Informazioni RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Crea una copia dell'oggetto corrente e restituisce un puntatore condiviso ad esso. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Ottiene il tipo di algoritmo. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Ottiene l'indice dell'era corrente. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Ottiene il valore dell'era corrente. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Ottiene l'elenco delle ere presenti nel calendario. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Verifica se il calendario è in sola lettura. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Punto di tempo massimo supportato dal calendario. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Punto di tempo minimo supportato dal calendario. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Ottiene l'ultimo anno che può essere rappresentato con 2 cifre. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Ottiene il giorno del mese per il punto temporale specificato. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Ottiene il giorno della settimana per il punto temporale specificato. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Ottiene il giorno dell'anno per il punto temporale specificato. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int) const | Ottiene il numero di giorni in un mese specifico. |
| virtual int [GetDaysInMonth](../calendar/getdaysinmonth/)(int, int, int) const | Ottiene il numero di giorni in un mese specifico. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int) const | Ottiene il numero di giorni in un anno specifico. |
| virtual int [GetDaysInYear](../calendar/getdaysinyear/)(int, int) const | Ottiene il numero di giorni in un anno specifico. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | Ottiene l'era per il punto temporale specificato. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Ottiene le ore per il punto temporale specificato. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Ottiene il mese bisestile per l'anno specificato. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Informazioni RTTI. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Informazioni RTTI. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Ottiene i millisecondi per il punto temporale specificato. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Ottiene i minuti per il punto temporale specificato. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Ottiene il mese per il punto temporale specificato. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int) const | Ottiene il numero di mesi nell'anno specificato. |
| virtual int [GetMonthsInYear](../calendar/getmonthsinyear/)(int, int) const | Ottiene il numero di mesi nell'anno specificato. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Ottiene i secondi per il punto temporale specificato. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo alla chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Ottiene la settimana dell'anno per il punto temporale specificato. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Ottiene l'anno per il punto temporale specificato. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo all'operatore C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Verifica se il giorno è bisestile. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Verifica se il giorno è bisestile. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Verifica se il giorno è bisestile. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Verifica se il mese è bisestile. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Verifica se il mese è bisestile. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Verifica se il mese è bisestile. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Verifica se l'anno è bisestile. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Verifica se l'anno è bisestile. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Verifica se l'anno è bisestile. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Verifica i valori di anno, mese, giorno e era. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Ottiene la versione in sola lettura del calendario. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| void [set_TwoDigitYearMax](./set_twodigityearmax/)(int) override | Imposta l'ultimo anno che può essere rappresentato con 2 cifre. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento modello come puntatore debole (anziché condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Costruisce l'oggetto [DateTime](../../system/datetime/) dai componenti. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Costruisce l'oggetto [DateTime](../../system/datetime/) dai componenti. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Converte l'anno in un anno a 4 cifre usando la proprietà TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
|  [UmAlQuraCalendar](./umalquracalendar/)() | Costruttore. |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Campi

| Field | Description |
| --- | --- |
| static constexpr [UmAlQuraEra](./umalquraera/) | Era corrente UmAlQura. |

## Vedi anche

* Classe [Calendar](../calendar/)
* Spazio dei nomi [System::Globalization](../)
* Libreria [Aspose.Slides](../../)