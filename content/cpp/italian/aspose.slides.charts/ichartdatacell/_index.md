---
title: IChartDataCell
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta una cella per i dati del grafico.
type: docs
weight: 664
url: /it/aspose.slides.charts/ichartdatacell/
---
## IChartDataCell classe


Rappresenta una cella per i dati del grafico.

```cpp
class IChartDataCell : public virtual System::Object
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual void [Calculate](./calculate/)(**bool**) | Se la cella contiene una formula, il valore verrà aggiornato in base a quella formula. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorksheet](../ichartdataworksheet/)\> [get_ChartDataWorksheet](./get_chartdataworksheet/)() | Ottiene il foglio di lavoro. [IChartDataWorksheet](../ichartdataworksheet/) di sola lettura. |
| virtual **int32_t** [get_Column](./get_column/)() | Restituisce l'indice della colonna del foglio di lavoro in cui si trova la cella. **int32_t** di sola lettura. |
| virtual [System::String](../../system/string/) [get_CustomNumberFormat](./get_customnumberformat/)() | Ottiene il formato di visualizzazione personalizzato di numeri e date. Se il valore è vuoto verrà usato il valore PresetNumberFormat. [System::String](../../system/string/) di sola lettura. |
| virtual [System::String](../../system/string/) [get_Formula](./get_formula/)() | Ottiene la formula in stile A1. |
| virtual **bool** [get_IsHidden](./get_ishidden/)() | Determina se la cella è nascosta. **bool** di sola lettura. |
| virtual **uint8_t** [get_PresetNumberFormat](./get_presetnumberformat/)() | Ottiene il formato di visualizzazione integrato di numeri e date. Il numero predefinito deve essere in [0..22] o [37..49]. **uint8_t** di sola lettura. |
| virtual [System::String](../../system/string/) [get_R1C1Formula](./get_r1c1formula/)() | Ottiene la formula in stile R1C1. |
| virtual **int32_t** [get_Row](./get_row/)() | Restituisce l'indice della riga del foglio di lavoro in cui si trova la cella. **int32_t** di sola lettura. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Value](./get_value/)() | Ottiene il valore di una cella. [System::Object](../../system/object/) di lettura. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o utilizzare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, in realtà, semplicemente inizializza un nuovo oggetto e consente la copia nelle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, in realtà, semplicemente inizializza un nuovo oggetto e consente la copia nelle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| virtual void [set_CustomNumberFormat](./set_customnumberformat/)([System::String](../../system/string/)) | Imposta il formato di visualizzazione personalizzato di numeri e date. Se il valore è vuoto verrà usato il valore PresetNumberFormat. Scrivi [System::String](../../system/string/). |
| virtual void [set_Formula](./set_formula/)([System::String](../../system/string/)) | Imposta la formula in stile A1. |
| virtual void [set_PresetNumberFormat](./set_presetnumberformat/)(**uint8_t**) | Imposta il formato di visualizzazione integrato di numeri e date. Il numero predefinito deve essere in [0..22] o [37..49]. Scrivi **uint8_t**. |
| virtual void [set_R1C1Formula](./set_r1c1formula/)([System::String](../../system/string/)) | Imposta la formula in stile R1C1. |
| virtual void [set_Value](./set_value/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Imposta il valore di una cella. Scrivi [System::Object](../../system/object/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n'th argomento template a un puntatore debole (invece di condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione lock() di C#. Chiamare direttamente o utilizzare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [Object](../../system/object/)
* Spazio dei nomi [Aspose::Slides::Charts](../)
* Libreria [Aspose.Slides](../../)