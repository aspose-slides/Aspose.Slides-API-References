---
title: IChartCategory
second_title: Aspose.Slides per C++ API Reference
description: Rappresenta le categorie del grafico.
type: docs
weight: 586
url: /it/aspose.slides.charts/ichartcategory/
---
## IChartCategory classe


Represents chart categories.

```cpp
class IChartCategory : public virtual System::Object
```

## Metodi

| Method | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_AsCell](./get_ascell/)() | Restituisce l'oggetto [IChartDataCell](../ichartdatacell/). Se la categoria è a più livelli allora viene usato l'oggetto [IChartDataCell](../ichartdatacell/) per il livello "0". Leggi [IChartDataCell](../ichartdatacell/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_AsLiteral](./get_asliteral/)() | Restituisce AsLiteral se UseCell è false. Leggi [System::Object](../../system/object/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_GroupingLevel](./get_groupinglevel/)(**int32_t**) | Restituisce un livello di raggruppamento della categoria del grafico all'indice specificato. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryLevelsManager](../ichartcategorylevelsmanager/)\> [get_GroupingLevels](./get_groupinglevels/)() | Contenitore gestito dei valori dei livelli di raggruppamento della categoria del grafico. Una categoria a più livelli contiene più di un livello di raggruppamento. L'indicizzazione dei livelli di raggruppamento è basata su zero. Solo lettura [IChartCategoryLevelsManager](../ichartcategorylevelsmanager/). |
| virtual **bool** [get_UseCell](./get_usecell/)() | Se true allora la proprietà AsCell è attiva. In altre parole, il foglio di lavoro è usato per memorizzare la categoria (questo caso supporta una categoria a più livelli). Se false allora la proprietà AsLiteral è attiva. In altre parole, il foglio di lavoro NON è usato per memorizzare la categoria (e questo caso non supporta categorie a più livelli). Solo lettura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Value](./get_value/)() | Se UseCell è true allora questa proprietà rappresenta la proprietà [get_AsCell()](./get_ascell/)->get(set)_Value(). Se UseCell è false allora questa proprietà rappresenta la proprietà AsLiteral. Leggi [System::Object](../../system/object/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, ma inizializza il nuovo oggetto e consente la costruzione per copia di sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, ma inizializza il nuovo oggetto e consente la costruzione per copia di sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| virtual void [Remove](./remove/)() | Rimuove la categoria dal grafico. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| virtual void [set_AsCell](./set_ascell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | Imposta l'oggetto [IChartDataCell](../ichartdatacell/). Se la categoria è a più livelli allora viene usato l'oggetto [IChartDataCell](../ichartdatacell/) per il livello "0". Scrivi [IChartDataCell](../ichartdatacell/). |
| virtual void [set_AsLiteral](./set_asliteral/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Imposta AsLiteral se UseCell è false. Scrivi [System::Object](../../system/object/). |
| virtual void [set_Value](./set_value/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Se UseCell è true allora questa proprietà rappresenta la proprietà [get_AsCell()](./get_ascell/)->get(set)_Value(). Se UseCell è false allora questa proprietà rappresenta la proprietà AsLiteral. Scrivi [System::Object](../../system/object/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento di modello come puntatore debole (anziché condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Object](../../system/object/)
* Spazio dei nomi [Aspose::Slides::Charts](../)
* Libreria [Aspose.Slides](../../)