---
title: TextFrame
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta un TextFrame.
type: docs
weight: 5448
url: /it/aspose.slides/textframe/
---
## TextFrame classe


Rappresenta un [TextFrame](./).

```cpp
class TextFrame : public Aspose::Slides::ITextFrame,
                  public Aspose::Slides::IDOMObject
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica [Object.Equals](../../system/object/equals/) di C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo riferimento nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta gli oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() override | Fornisce un facile accesso ai collegamenti ipertestuali contenuti. Solo lettura [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraph](../iparagraph/)\> [get_Paragraph](./get_paragraph/)(**int32_t**) override | Restituisce un paragrafo in un frame all'indice specificato. |
| [System::SharedPtr](../../system/sharedptr/)\<[IParagraphCollection](../iparagraphcollection/)\> [get_Paragraphs](./get_paragraphs/)() override | Restituisce l'elenco di tutti i paragrafi in un frame. Solo lettura [IParagraphCollection](../iparagraphcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [get_ParentCell](./get_parentcell/)() override | Restituisce la cella genitore o null se l'oggetto genitore non implementa l'interfaccia [ICell](../icell/). Solo lettura [ICell](../icell/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_ParentShape](./get_parentshape/)() override | Restituisce la forma genitore o null se l'oggetto genitore non implementa l'interfaccia [IShape](../ishape/). Solo lettura [IShape](../ishape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | Restituisce la presentazione genitore di un [TextFrame](./). Solo lettura [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | Restituisce la diapositiva genitore di un [TextFrame](./). Solo lettura [IBaseSlide](../ibaseslide/). |
| [System::String](../../system/string/) [get_Text](./get_text/)() override | Ottiene il testo semplice per un [TextFrame](./). Leggi [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\> [get_TextFrameFormat](./get_textframeformat/)() override | Restituisce l'oggetto di formattazione per questo oggetto [TextFrame](./). Solo lettura [ITextFrameFormat](../itextframeformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimenti associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo [Object.GetHashCode()](../../system/object/gethashcode/) di C#. Consente l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata [System.Object.GetType()](../../system/object/gettype/) di C#. |
| void [HighlightRegex](./highlightregex/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[ITextHighlightingOptions](../itexthighlightingoptions/)\>) override | Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato. |
| void [HighlightRegex](./highlightregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato. |
| void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/)) override | Evidenzia tutte le corrispondenze del testo di esempio con il colore specificato. |
| void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[ITextHighlightingOptions](../itexthighlightingoptions/)\>) override | Evidenzia tutte le corrispondenze del testo di esempio con il colore specificato. |
| void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | Evidenzia tutte le corrispondenze del testo di esempio con il colore specificato. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore 'is' di C#. |
| void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() override | Unisce le sequenze con la stessa formattazione in tutti i paragrafi. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco lock() di C#. Chiamare direttamente o utilizzare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo [Object.MemberwiseClone()](../../system/object/memberwiseclone/) di C#. Consente la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia realmente nulla, semplicemente inizializza un nuovo oggetto e consente la copia dei sotto-classi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia realmente nulla, semplicemente inizializza un nuovo oggetto e consente la copia dei sotto-classi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| void [ReplaceRegex](./replaceregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | Sostituisce tutte le corrispondenze dell'espressione regolare con la stringa specificata. |
| void [ReplaceText](./replacetext/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | Sostituisce tutte le occorrenze del testo specificato con un altro testo specificato. |
| void [set_Text](./set_text/)([System::String](../../system/string/)) override | Imposta il testo semplice per un [TextFrame](./). Scrivi [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento di modello come puntatore debole (piuttosto che condiviso). Consente di passare i puntatori nei contenitori alla modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [SplitTextByColumns](./splittextbycolumns/)() override | Divide il contenuto testuale del [ITextFrame](../itextframe/) in un array di stringhe,\n\n dove ogni elemento corrisponde a una colonna di testo separata all'interno del frame. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo [Object.ToString()](../../system/object/tostring/) di C#. Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione typeof([System.Object](../../system/object/)) di C#. |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione lock() di C#. Chiamare direttamente o utilizzare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usare smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |
## Vedi anche

* Classe [ITextFrame](../itextframe/)
* Classe [IDOMObject](../idomobject/)
* Namespace [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)