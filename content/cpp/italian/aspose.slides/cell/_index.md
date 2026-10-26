---
title: Cell
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta una cella di una tabella.
type: docs
weight: 300
url: /it/aspose.slides/cell/
---
## Cell classe

Rappresenta una cella di una tabella.

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento in stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | Determina se la casella di testo è centrata all'interno di una cella. Leggi **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | Restituisce l'oggetto [CellFormat](../cellformat/) che contiene le proprietà di formattazione per questa cella. Sola lettura [ICellFormat](../icellformat/). |
| **int32_t** [get_ColSpan](./get_colspan/)() override | Restituisce il numero di colonne della griglia della tabella padre che devono essere coperte dalla cella corrente. Questa proprietà consente alle celle di apparire unite, poiché attraversano i bordi verticali di altre celle nella tabella. Sola lettura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | Ottiene la prima colonna della cella. Sola lettura [IColumn](../icolumn/). |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | Restituisce l'indice della prima colonna coperta dalla cella. Sola lettura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | Ottiene la prima riga della cella. Sola lettura [IRow](../irow/). |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | Restituisce l'indice della prima riga coperta dalla cella. Sola lettura **int32_t**. |
| **double** [get_Height](./get_height/)() override | Restituisce l'altezza della cella. Sola lettura **double**. |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | Restituisce true se la cella è unita a qualsiasi cella aggiustata, false altrimenti. Sola lettura **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | Restituisce il margine inferiore in un [TextFrame](../textframe/). Leggi **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | Restituisce il margine sinistro in un [TextFrame](../textframe/). Leggi **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | Restituisce il margine destro in un [TextFrame](../textframe/). Leggi **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | Restituisce il margine superiore in un [TextFrame](../textframe/). Leggi **double**. |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | Restituisce l'altezza minima di una cella. È la somma delle altezze minime di tutte le righe coperte dalla cella. Sola lettura **double**. |
| **double** [get_OffsetX](./get_offsetx/)() override | Restituisce la distanza dal lato sinistro di una tabella al lato sinistro di una cella. Sola lettura **double**. |
| **double** [get_OffsetY](./get_offsety/)() override | Restituisce la distanza dal lato superiore di una tabella al lato superiore di una cella. Sola lettura **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Restituisce la presentazione genitore della cella. Sola lettura [IPresentation](../ipresentation/). |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | Restituisce il numero di righe che una cella unita copre. Questo è usato in combinazione con l'attributo vMerge su altre celle per specificare la cella di inizio di una fusione orizzontale. Sola lettura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | Restituisce la diapositiva genitore della cella. Sola lettura [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | Restituisce l'oggetto [Table](../table/) genitore per una cella. Sola lettura [ITable](../itable/). |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | Restituisce il tipo di ancoraggio del testo. Leggi [Slides::TextAnchorType](../textanchortype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | Restituisce il frame di testo di una cella. Sola lettura [ITextFrame](../itextframe/). |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | Restituisce il tipo di testo verticale. Leggi [Slides::TextVerticalType](../textverticaltype/). |
| **double** [get_Width](./get_width/)() override | Restituisce la larghezza della cella. Sola lettura **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco di lock() di C#. Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. In realtà non copia nulla, ma inizializza un nuovo oggetto e consente la costruzione di copie per le sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. In realtà non copia nulla, ma inizializza un nuovo oggetto e consente la costruzione di copie per le sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | Determina se la casella di testo è centrata all'interno di una cella. Scrivi **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | Imposta il margine inferiore in un [TextFrame](../textframe/). Scrivi **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | Imposta il margine sinistro in un [TextFrame](../textframe/). Scrivi **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | Imposta il margine destro in un [TextFrame](../textframe/). Scrivi **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | Imposta il margine superiore in un [TextFrame](../textframe/). Scrivi **double**. |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | Imposta il tipo di ancoraggio del testo. Scrivi [Slides::TextAnchorType](../textanchortype/). |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | Imposta il tipo di testo verticale. Scrivi [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | Dividi la cella in due celle per indice di colonna. |
| void [SplitByHeight](./splitbyheight/)(**double**) override | Dividi la cella per altezza. |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | Dividi la cella in due celle per indice di riga. |
| void [SplitByWidth](./splitbywidth/)(**double**) override | Dividi la cella per larghezza. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costrutto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, utilizzare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [IDOMObject](../idomobject/)
* Classe [ICell](../icell/)
* Namespace [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)