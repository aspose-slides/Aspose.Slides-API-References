---
title: Match
second_title: Riferimento API Aspose.Slides per C++
description: "Singola corrispondenza di espressione regolare su stringa. Gli oggetti di questa classe devono essere allocati solo usando la funzione System::MakeObject(). Non creare mai un'istanza di questo tipo sullo stack o utilizzando l'operatore new, poiché ciò può causare errori di runtime e/o fallimenti di asserzione. Avvolgi sempre questa classe in un puntatore System::SmartPtr e usa questo puntatore per passarla alle funzioni come argomento."
type: docs
weight: 66
url: /it/system.text.regularexpressions/match/
---
## Match classe

[Single](../../system/single/) corrispondenza di regexp su stringa. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../../system/makeobject/). Non creare mai istanze di questo tipo sullo stack o usando l'operatore new, poiché ciò può provocare errori di runtime e/o fault di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../../system/smartptr/) e usa questo puntatore per passarlo alle funzioni come argomento.

```cpp
class Match : public System::Text::RegularExpressions::Group
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [AddCapture](./addcapture/)(const [CapturePtr](../captureptr/)\&) | Aggiunge la cattura al match. |
| void [AddGroup](./addgroup/)(const [GroupPtr](../groupptr/)\&) | Aggiunge il gruppo al match. |
|  [Capture](../capture/capture/)(const [UStringPtr](../ustringptr/)\&, int, int) | Costruttore. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto di numeri in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto di numeri in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [CaptureCollectionPtr](../capturecollectionptr/) [get_Captures](../group/get_captures/)() | Ottiene le catture disponibili. |
| static [MatchPtr](../matchptr/) [get_Empty](./get_empty/)() | Accessor del match vuoto. |
| [GroupCollectionPtr](../groupcollectionptr/) [get_Groups](./get_groups/)() | Ottiene l'elenco dei gruppi. |
| int [get_Index](../capture/get_index/)() const | Ottiene l'indice della sottostringa catturata. |
| int [get_Length](../capture/get_length/)() const | Ottiene la lunghezza della sottostringa catturata. |
| **bool** [get_Success](../group/get_success/)() | Verifica se la cattura è riuscita per questo gruppo. |
| [String](../../system/string/) [get_Value](../capture/get_value/)() const | Recupera la sottostringa catturata. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Recupera la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Recupera il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
|  [Group](../group/group/)(const [UStringPtr](../ustringptr/)\&, int, int) | Costruttore. |
|  [Group](../group/group/)() | Costruttore del gruppo vuoto. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
|  [Match](./match/)(const [UStringPtr](../ustringptr/)\&, int, int) | Costruttore. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
| [MatchPtr](../matchptr/) [NextMatch](./nextmatch/)() | Iterazione sui match. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, inizializza solo il nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| virtual [String](../../system/string/) [Result](./result/)(const [String](../../system/string/)\&) | Formatta la stringa sostituendo i riferimenti ai sotto-match con i loro valori. |
| void [SetMappedIndexes](./setmappedindexes/)(const std::vector\<int\>\&) |  |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (anziché condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| [String](../../system/string/) [ToString](../capture/tostring/)() const override | Recupera la sottostringa catturata. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Group](../group/)
* Spazio dei nomi [System::Text::RegularExpressions](../)
* Libreria [Aspose.Slides](../../)