---
title: DataSourceTypeForErrorBarsCustomValues
second_title: Riferimento API di Aspose.Slides per C++
description: "Specifica i tipi di valori nella lista delle proprietà ChartDataPoint::get_ErrorBarsCustomValues"
type: docs
weight: 404
url: /it/aspose.slides.charts/datasourcetypeforerrorbarscustomvalues/
---
## DataSourceTypeForErrorBarsCustomValues classe


Specifica i tipi di valori nella lista delle proprietà [ChartDataPoint::get_ErrorBarsCustomValues](../chartdatapoint/get_errorbarscustomvalues/)

```cpp
class DataSourceTypeForErrorBarsCustomValues : public Aspose::Slides::Charts::IDataSourceTypeForErrorBarsCustomValues
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [DataSourceTypeForErrorBarsCustomValues](./datasourcetypeforerrorbarscustomvalues/)() |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto a punto mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto a punto mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXMinusValues](./get_datasourcetypeforxminusvalues/)() override | Specifica se la proprietà AsCell, AsLiteralString o AsLiteralDouble è effettiva nell'oggetto proprietà XMinus dei punti dati per i valori personalizzati delle barre di errore. In altre parole specifica il tipo di valore della proprietà ChartDataPoint.ErrorBarsCustomValues.XMinus.Data. Leggi [DataSourceType](../datasourcetype/). |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXPlusValues](./get_datasourcetypeforxplusvalues/)() override | Specifica se la proprietà AsCell, AsLiteralString o AsLiteralDouble è effettiva nell'oggetto proprietà XPlus dei punti dati per i valori personalizzati delle barre di errore. In altre parole specifica il tipo di valore della proprietà ChartDataPoint.ErrorBarsCustomValues.XPlus.Data. Leggi [DataSourceType](../datasourcetype/). |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYMinusValues](./get_datasourcetypeforyminusvalues/)() override | Specifica se la proprietà AsCell, AsLiteralString o AsLiteralDouble è effettiva nell'oggetto proprietà YMinus dei punti dati per i valori personalizzati delle barre di errore. In altre parole specifica il tipo di valore della proprietà ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data. Leggi [DataSourceType](../datasourcetype/). |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYPlusValues](./get_datasourcetypeforyplusvalues/)() override | Specifica se la proprietà AsCell, AsLiteralString o AsLiteralDouble è effettiva nell'oggetto proprietà YPlus dei punti dati per i valori personalizzati delle barre di errore. In altre parole specifica il tipo di valore della proprietà ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data. Leggi [DataSourceType](../datasourcetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing degli oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o utilizzare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia effettivamente nulla, inizializza solo un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia effettivamente nulla, inizializza solo un nuovo oggetto e consente la costruzione di copie delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| void [set_DataSourceTypeForXMinusValues](./set_datasourcetypeforxminusvalues/)([DataSourceType](../datasourcetype/)) override | Specifica se la proprietà AsCell, AsLiteralString o AsLiteralDouble è effettiva nell'oggetto proprietà XMinus dei punti dati per i valori personalizzati delle barre di errore. In altre parole specifica il tipo di valore della proprietà ChartDataPoint.ErrorBarsCustomValues.XMinus.Data. Scrivi [DataSourceType](../datasourcetype/). |
| void [set_DataSourceTypeForXPlusValues](./set_datasourcetypeforxplusvalues/)([DataSourceType](../datasourcetype/)) override | Specifica se la proprietà AsCell, AsLiteralString o AsLiteralDouble è effettiva nell'oggetto proprietà XPlus dei punti dati per i valori personalizzati delle barre di errore. In altre parole specifica il tipo di valore della proprietà ChartDataPoint.ErrorBarsCustomValues.XPlus.Data. Scrivi [DataSourceType](../datasourcetype/). |
| void [set_DataSourceTypeForYMinusValues](./set_datasourcetypeforyminusvalues/)([DataSourceType](../datasourcetype/)) override | Specifica se la proprietà AsCell, AsLiteralString o AsLiteralDouble è effettiva nell'oggetto proprietà YMinus dei punti dati per i valori personalizzati delle barre di errore. In altre parole specifica il tipo di valore della proprietà ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data. Scrivi [DataSourceType](../datasourcetype/). |
| void [set_DataSourceTypeForYPlusValues](./set_datasourcetypeforyplusvalues/)([DataSourceType](../datasourcetype/)) override | Specifica se la proprietà AsCell, AsLiteralString o AsLiteralDouble è effettiva nell'oggetto proprietà YPlus dei punti dati per i valori personalizzati delle barre di errore. In altre parole specifica il tipo di valore della proprietà ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data. Scrivi [DataSourceType](../datasourcetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (anziché condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; utilizzare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; utilizzare smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco dell'istruzione C# lock(). Chiamare direttamente o utilizzare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; utilizzare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; utilizzare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [IDataSourceTypeForErrorBarsCustomValues](../idatasourcetypeforerrorbarscustomvalues/)
* Namespace [Aspose::Slides::Charts](../)
* Libreria [Aspose.Slides](../../)