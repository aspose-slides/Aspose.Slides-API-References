---
title: KoreanCalendar
second_title: "Riferimento API di Aspose.Slides per C++"
description: "Calendario coreano. Gli oggetti di questa classe dovrebbero essere allocati solo utilizzando la funzione System::MakeObject() . Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 222
url: /it/system.globalization/koreancalendar/
---
## KoreanCalendar classe

Calendario coreano. Gli oggetti di questa classe dovrebbero essere allocati solo utilizzando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò comporterà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e utilizza questo puntatore per passarlo alle funzioni come argomento.

```cpp
class KoreanCalendar : public System::Globalization::Calendar
```

## Metodi

| Method | Descrizione |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Aggiunge giorni al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Aggiunge ore al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Aggiunge millisecondi al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Aggiunge minuti al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Aggiunge mesi al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Aggiunge secondi al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Aggiunge settimane al punto temporale. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Aggiunge anni al punto temporale. |
| [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | Informazioni RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Crea una copia dell'oggetto corrente e restituisce un puntatore condiviso a esso. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile nello stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile nello stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Restituisce il tipo di algoritmo. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Restituisce l'indice dell'era corrente. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Restituisce il valore dell'era corrente. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Restituisce l'elenco delle ere esistenti nel calendario. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Verifica se il calendario è in sola lettura. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Punto temporale massimo supportato dal calendario. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Punto temporale minimo supportato dal calendario. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Restituisce l'ultimo anno che può essere rappresentato con due cifre. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Restituisce la struttura dati del contatore di riferimento associata all'oggetto. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | Restituisce il giorno del mese per il punto temporale specificato. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Restituisce il giorno della settimana per il punto temporale specificato. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | Restituisce il giorno dell'anno per il punto temporale specificato. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Restituisce il numero di giorni in un mese specifico. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Restituisce il numero di giorni in un mese specifico. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Restituisce il numero di giorni in un mese specifico. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | Restituisce il numero di giorni in un anno specifico. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Restituisce il numero di giorni in un anno specifico. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Restituisce il numero di giorni in un anno specifico. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Restituisce l'era per il punto temporale specificato. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Restituisce le ore per il punto temporale specificato. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Restituisce il mese bisestile per l'anno specificato. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Restituisce il mese bisestile per l'anno specificato. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Restituisce il mese bisestile per l'anno specificato. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Restituisce i millisecondi per il punto temporale specificato. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Restituisce i minuti per il punto temporale specificato. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | Restituisce il mese per il punto temporale specificato. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Restituisce il numero di mesi nell'anno specificato. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Informazioni RTTI. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Informazioni RTTI. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Restituisce i secondi per il punto temporale specificato. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Restituisce il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Restituisce la settimana dell'anno per il punto temporale specificato. |
| int [GetYear](./getyear/)([DateTime](../../system/datetime/)) const override | Restituisce l'anno per il punto temporale specificato. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
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
| [KoreanCalendar](./koreancalendar/)() | Costruttore. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia realmente nulla, ma inizializza un nuovo oggetto e consente la copia dei sottoclasse. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia realmente nulla, ma inizializza un nuovo oggetto e consente la copia dei sottoclasse. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Restituisce la versione in sola lettura del calendario. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimenti condivisi del valore specificato. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Imposta l'ultimo anno che può essere rappresentato con due cifre. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta l'n-esimo argomento template a un puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Restituisce il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; usare smart pointers o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; usare smart pointers o ThisProtector. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Costruisce un oggetto [DateTime](../../system/datetime/) dai componenti. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Costruisce un oggetto [DateTime](../../system/datetime/) dai componenti. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Costruisce un oggetto [DateTime](../../system/datetime/) dai componenti. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Converte l'anno a un anno a 4 cifre usando la proprietà TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa il costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; usare smart pointers o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; usare smart pointers o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Campi

| Campo | Descrizione |
| --- | --- |
| static constexpr [KoreanEra](./koreanera/) | Era coreana corrente. |

## Vedi anche

* Classe [Calendar](../calendar/)
* Namespace [System::Globalization](../)
* Libreria [Aspose.Slides](../../)