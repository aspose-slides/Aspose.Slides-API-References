---
title: TimeZone
second_title: Riferimento API Aspose.Slides per C++
description: "Rappresenta un fuso orario. Gli oggetti di questa classe dovrebbero essere allocati solo utilizzando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e usa questo puntatore per passarlo alle funzioni come argomento."
type: docs
weight: 1327
url: /it/system/timezone/
---
## TimeZone classe

Rappresenta un fuso orario. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

```cpp
class TimeZone : public System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| static [TimeZonePtr](../timezoneptr/) [get_CurrentTimeZone](./get_currenttimezone/)() | Restituisce una nuova istanza della classe [TimeZone](./) che rappresenta il fuso orario corrente. |
| virtual [String](../string/) [get_DaylightName](./get_daylightname/)() const | Restituisce un nome per l'ora legale del fuso orario rappresentato dall'oggetto corrente. |
| virtual [String](../string/) [get_StandardName](./get_standardname/)() const | Restituisce un nome per l'ora standard del fuso orario rappresentato dall'oggetto corrente. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual [Globalization::DaylightTimePtr](../../system.globalization/daylighttimeptr/) [GetDaylightChanges](./getdaylightchanges/)(**int32_t**) | Restituisce il periodo dell'ora legale per un anno particolare. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogo al metodo C# [Object.GetHashCode()](../object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo alla chiamata C# [System.Object.GetType()](../object/gettype/). |
| virtual [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)([DateTime](../datetime/)) | Restituisce l'offset UTC per l'ora locale specificata. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo all'operatore C# 'is'. |
| virtual **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)([DateTime](../datetime/)) | Determina se il valore data e ora rappresentato dall'oggetto [DateTime](../datetime/) specificato rientra nell'intervallo dell'ora legale per il fuso orario rappresentato dall'oggetto corrente [TimeZone](./). |
| void [Lock](../object/lock/)() | Implementa la dichiarazione lock() di C#. Chiamare direttamente o utilizzare l'oggetto sentinella [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogo al metodo C# [Object.MemberwiseClone()](../object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../object/object/)([Object](../object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza un nuovo oggetto e consente la copia dei sottoclasse. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza un nuovo oggetto e consente la copia dei sottoclasse. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Specializzazione di [Object::ReferenceEquals](../object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (anziché condiviso). Permette di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analogo al metodo C# [Object.ToString()](../object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa la costruzione C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementa la dichiarazione lock() di C# sbloccando. Chiamare direttamente o utilizzare l'oggetto sentinella [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Object](../object/)
* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)