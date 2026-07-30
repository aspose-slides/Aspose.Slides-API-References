---
title: ICell
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta una cella in una tabella.
type: docs
weight: 1639
url: /it/aspose.slides/icell/
---
## ICell classe


Rappresenta una cella in una tabella.

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta oggetti usando la semantica [Object.Equals](../../system/object/equals/) di C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, compreso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, compreso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | Determina se la casella di testo è centrata all'interno di una cella. Leggi **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | Restituisce l'oggetto [CellFormat](../cellformat/) che contiene le proprietà di formattazione per questa cella. Sola lettura [ICellFormat](../icellformat/). |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | Restituisce il numero di colonne della griglia della tabella madre che devono essere attraversate dalla cella corrente. Questa proprietà consente alle celle di apparire unite, poiché attraversano i confini verticali di altre celle nella tabella. Sola lettura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | Ottiene la prima colonna della cella. Sola lettura [IColumn](../icolumn/). |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | Restituisce l'indice della prima colonna coperta dalla cella. Sola lettura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | Ottiene la prima riga della cella. Sola lettura [IRow](../irow/). |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | Restituisce l'indice della prima riga coperta dalla cella. Sola lettura **int32_t**. |
| virtual **double** [get_Height](./get_height/)() | Restituisce l'altezza della cella. Sola lettura **double**. |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | Restituisce true se la cella è unita a qualche altra cella regolata, false altrimenti. Sola lettura **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Restituisce il margine inferiore in un [TextFrame](../textframe/). Leggi **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Restituisce il margine sinistro in un [TextFrame](../textframe/). Leggi **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Restituisce il margine destro in un [TextFrame](../textframe/). Leggi **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Restituisce il margine superiore in un [TextFrame](../textframe/). Leggi **double**. |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | Restituisce l'altezza minima di una cella. È la somma delle altezze minime di tutte le righe coperte dalla cella. Sola lettura **double**. |
| virtual **double** [get_OffsetX](./get_offsetx/)() | Restituisce la distanza dal lato sinistro di una tabella al lato sinistro della cella. Sola lettura **double**. |
| virtual **double** [get_OffsetY](./get_offsety/)() | Restituisce la distanza dal lato superiore di una tabella al lato superiore della cella. Sola lettura **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Restituisce la presentazione. Sola lettura [IPresentation](../ipresentation/). |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | Restituisce il numero di righe che una cella unita attraversa. Questo è usato in combinazione con l'attributo vMerge su altre celle per specificare la cella di inizio di un'unione orizzontale. Sola lettura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Restituisce la diapositiva base. Sola lettura [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | Restituisce l'oggetto [Table](../table/) genitore per una cella. Sola lettura [ITable](../itable/). |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | Restituisce il tipo di ancoraggio del testo. Leggi [Slides::TextAnchorType](../textanchortype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | Restituisce il riquadro di testo di una cella. Sola lettura [ITextFrame](../itextframe/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Restituisce il tipo di testo verticale. Leggi [Slides::TextVerticalType](../textverticaltype/). |
| virtual **double** [get_Width](./get_width/)() | Restituisce la larghezza della cella. Sola lettura **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, inizializza semplicemente un nuovo oggetto e abilita la costruzione di copie per le classi derivate. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, inizializza semplicemente un nuovo oggetto e abilita la costruzione di copie per le classi derivate. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso delle stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimento condiviso del valore specificato. |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | Determina se la casella di testo è centrata all'interno di una cella. Scrivi **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Imposta il margine inferiore in un [TextFrame](../textframe/). Scrivi **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Imposta il margine sinistro in un [TextFrame](../textframe/). Scrivi **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Imposta il margine destro in un [TextFrame](../textframe/). Scrivi **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Imposta il margine superiore in un [TextFrame](../textframe/). Scrivi **double**. |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | Imposta il tipo di ancoraggio del testo. Scrivi [Slides::TextAnchorType](../textanchortype/). |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Imposta il tipo di testo verticale. Scrivi [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (invece che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare puntatori intelligenti o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare puntatori intelligenti o ThisProtector. |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | Divide la cella in due celle in base all'indice della colonna. |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | Divide la cella per altezza. |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | Divide la cella in due celle in base all'indice della riga. |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | Divide la cella per larghezza. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco del blocco lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare puntatori intelligenti o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare puntatori intelligenti o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [ISlideComponent](../islidecomponent/)
* Spazio dei nomi [Aspose::Slides](../)
* Library [Aspose.Slides](../../)