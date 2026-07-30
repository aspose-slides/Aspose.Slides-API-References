---
title: PortionFormat
second_title: Riferimento API Aspose.Slides per C++
description: Questa classe contiene le proprietà di formattazione delle porzioni di testo. A differenza di IPortionFormatEffectiveData, tutte le proprietà di questa classe sono modificabili.
type: docs
weight: 4811
url: /it/aspose.slides/portionformat/
---
## PortionFormat classe


Questa classe contiene le proprietà di formattazione delle porzioni di testo. A differenza di [IPortionFormatEffectiveData](../iportionformateffectivedata/), tutte le proprietà di questa classe sono modificabili.

```cpp
class PortionFormat : public Aspose::Slides::BasePortionFormat,
                      public Aspose::Slides::IPortionFormat
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Confronta con l'oggetto specificato. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali nonostante, secondo IEC 60559:1989, NaN non sia uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali nonostante, secondo IEC 60559:1989, NaN non sia uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../baseportionformat/get_alternativelanguageid/)() override | Restituisce l'Id di una lingua alternativa. Leggi [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() override | Restituisce l'identificatore del segnalibro. Leggi [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../baseportionformat/get_complexscriptfont/)() override | Restituisce le informazioni sul carattere per script complessi. Null significa che il carattere non è definito e dovrebbe essere ereditato dal Master. Leggi [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../baseportionformat/get_eastasianfont/)() override | Restituisce le informazioni sul carattere East Asian. Null significa che il carattere non è definito e dovrebbe essere ereditato dal Master. Leggi [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../baseportionformat/get_effectformat/)() override | Restituisce le proprietà del testo [EffectFormat](../effectformat/). Nessuna eredità applicata. Solo lettura [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](../baseportionformat/get_escapement/)() override | Restituisce il testo in apice o pedice. Valore da -100% (pedice) a 100% (apice). **std::numeric_limits<float>::quiet_NaN()** indica che il valore è non definito e dovrebbe essere ereditato dal Master. Leggi **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../baseportionformat/get_fillformat/)() override | Restituisce le proprietà del testo [FillFormat](../fillformat/). Nessuna eredità applicata. Solo lettura [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](../baseportionformat/get_fontbold/)() override | Determina se il carattere è in grassetto. Nessuna eredità applicata. Leggi [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](../baseportionformat/get_fontheight/)() override | Restituisce l'altezza del carattere di una porzione. **std::numeric_limits<float>::quiet_NaN()** indica che l'altezza è non definita e dovrebbe essere ereditata dal Master. Leggi **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](../baseportionformat/get_fontitalic/)() override | Determina se il carattere è italico. Nessuna eredità applicata. Leggi [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../baseportionformat/get_fontunderline/)() override | Restituisce il tipo di sottolineatura del testo. Nessuna eredità applicata. Leggi [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../baseportionformat/get_highlightcolor/)() override | Restituisce il colore usato per evidenziare un testo. Nessuna eredità applicata. Solo lettura [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | Restituisce il collegamento ipertestuale definito per il click del mouse. Leggi [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | Gestore dei collegamenti ipertestuali. Solo lettura [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | Restituisce il collegamento ipertestuale definito per il passaggio del mouse. Leggi [IHyperlink](../ihyperlink/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../baseportionformat/get_ishardunderlinefill/)() override | Determina se lo stile di sottolineatura ha proprie proprietà [FillFormat](../fillformat/) o le eredita dalle proprietà [FillFormat](../fillformat/) del testo. Leggi [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../baseportionformat/get_ishardunderlineline/)() override | Determina se lo stile di sottolineatura ha proprie proprietà [LineFormat](../lineformat/) o le eredita dalle proprietà [LineFormat](../lineformat/) del testo. Leggi [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](../baseportionformat/get_kerningminimalsize/)() override | Restituisce la dimensione minima del carattere, per la quale l'interlinea dovrebbe essere attivata. **std::numeric_limits<float>::quiet_NaN()** indica che il valore è non definito e dovrebbe essere ereditato dal Master. Leggi **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](../baseportionformat/get_kumimoji/)() override | Determina se i numeri devono ignorare il layout verticale specifico per le lingue dell'Est del testo. Nessuna eredità applicata. Leggi [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](../baseportionformat/get_languageid/)() override | Restituisce l'Id di una lingua di correzione. Usata per il controllo ortografico e grammaticale. Leggi [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../baseportionformat/get_latinfont/)() override | Restituisce le informazioni sul carattere latino. Null significa che il carattere non è definito e dovrebbe essere ereditato dal Master. Leggi [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../baseportionformat/get_lineformat/)() override | Restituisce le proprietà [LineFormat](../lineformat/) per il contorno del testo. Nessuna eredità applicata. Solo lettura [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](../baseportionformat/get_normaliseheight/)() override | Determina se l'altezza di un testo debba essere normalizzata. Nessuna eredità applicata. Leggi [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Restituisce l'oggetto Parent_Immediate. Solo lettura [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Restituisce il genitore [IPresentationComponent](../ipresentationcomponent/). Solo lettura [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](../baseportionformat/get_proofdisabled/)() override | Determina se il testo non debba essere corretto. Nessuna eredità applicata. Leggi [NullableBool](../nullablebool/). |
| **bool** [get_SmartTagClean](./get_smarttagclean/)() override | Determina se lo smart tag debba essere pulito. Nessuna eredità applicata. Leggi **bool**. |
| **float** [get_Spacing](../baseportionformat/get_spacing/)() override | Restituisce l'incremento di spaziatura intercarattere. **std::numeric_limits<float>::quiet_NaN()** indica che il valore è non definito e dovrebbe essere ereditato dal Master. Leggi **float**. |
| **bool** [get_SpellCheck](../baseportionformat/get_spellcheck/)() override | Restituisce un valore che indica se il controllo ortografico è abilitato per la porzione di testo. Quando questa proprietà è impostata a false, i controlli ortografici per gli elementi di testo sono soppressi. Quando impostata a true, il controllo ortografico è consentito. Il valore predefinito è **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../baseportionformat/get_strikethroughtype/)() override | Restituisce il tipo di barratura di un testo. Nessuna eredità applicata. Leggi [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../baseportionformat/get_symbolfont/)() override | Restituisce le informazioni sul carattere simbolico. Null significa che il carattere non è definito e dovrebbe essere ereditato dal Master. Leggi [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../baseportionformat/get_textcaptype/)() override | Restituisce il tipo di capitalizzazione del testo. Nessuna eredità applicata. Leggi [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../baseportionformat/get_underlinefillformat/)() override | Restituisce le proprietà della linea di sottolineatura [FillFormat](../fillformat/). Nessuna eredità applicata. Solo lettura [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../baseportionformat/get_underlinelineformat/)() override | Restituisce le proprietà [LineFormat](../lineformat/) usate per delineare la linea di sottolineatura. Nessuna eredità applicata. Solo lettura [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Restituisce la struttura dati del contatore di riferimento associata all'oggetto. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() override | Restituisce i dati di formattazione della porzione effettiva con l'ereditarietà applicata. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Restituisce il codice hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Restituisce il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente il clone di tipi personalizzati. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, ma inizializza un nuovo oggetto e consente la copia di sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, ma inizializza un nuovo oggetto e consente la copia di sottoclassi. |
| [PortionFormat](./portionformat/)() | Inizializza una nuova istanza della classe [PortionFormat](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| void [set_AlternativeLanguageId](../baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | Imposta l'Id di una lingua alternativa. Scrivi [System::String](../../system/string/). |
| void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) override | Imposta l'identificatore del segnalibro. Scrivi [System::String](../../system/string/). |
| void [set_ComplexScriptFont](../baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Imposta le informazioni sul carattere per script complessi. Null significa che il carattere non è definito e dovrebbe essere ereditato dal Master. Scrivi [IFontData](../ifontdata/). |
| void [set_EastAsianFont](../baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Imposta le informazioni sul carattere East Asian. Null significa che il carattere non è definito e dovrebbe essere ereditato dal Master. Scrivi [IFontData](../ifontdata/). |
| void [set_Escapement](../baseportionformat/set_escapement/)(**float**) override | Imposta il testo in apice o pedice. Valore da -100% (pedice) a 100% (apice). **std::numeric_limits<float>::quiet_NaN()** indica che il valore è non definito e dovrebbe essere ereditato dal Master. Scrivi **float**. |
| void [set_FontBold](../baseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) override | Determina se il carattere è in grassetto. Nessuna eredità applicata. Scrivi [NullableBool](../nullablebool/). |
| void [set_FontHeight](../baseportionformat/set_fontheight/)(**float**) override | Imposta l'altezza del carattere di una porzione. **std::numeric_limits<float>::quiet_NaN()** indica che l'altezza è non definita e dovrebbe essere ereditata dal Master. Scrivi **float**. |
| void [set_FontItalic](../baseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) override | Determina se il carattere è italico. Nessuna eredità applicata. Scrivi [NullableBool](../nullablebool/). |
| void [set_FontUnderline](../baseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Imposta il tipo di sottolineatura del testo. Nessuna eredità applicata. Scrivi [TextUnderlineType](../textunderlinetype/). |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Imposta il collegamento ipertestuale definito per il click del mouse. Scrivi [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Imposta il collegamento ipertestuale definito per il passaggio del mouse. Scrivi [IHyperlink](../ihyperlink/). |
| void [set_IsHardUnderlineFill](../baseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Determina se lo stile di sottolineatura ha proprie proprietà [FillFormat](../fillformat/) o le eredita dalle proprietà [FillFormat](../fillformat/) del testo. Scrivi [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](../baseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Determina se lo stile di sottolineatura ha proprie proprietà [LineFormat](../lineformat/) o le eredita dalle proprietà [LineFormat](../lineformat/) del testo. Scrivi [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](../baseportionformat/set_kerningminimalsize/)(**float**) override | Imposta la dimensione minima del carattere, per la quale l'interlinea dovrebbe essere attivata. **std::numeric_limits<float>::quiet_NaN()** indica che il valore è non definito e dovrebbe essere ereditato dal Master. Scrivi **float**. |
| void [set_Kumimoji](../baseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) override | Determina se i numeri devono ignorare il layout verticale specifico per le lingue dell'Est del testo. Nessuna eredità applicata. Scrivi [NullableBool](../nullablebool/). |
| void [set_LanguageId](../baseportionformat/set_languageid/)([System::String](../../system/string/)) override | Imposta l'Id di una lingua di correzione. Usata per il controllo ortografico e grammaticale. Scrivi [System::String](../../system/string/). |
| void [set_LatinFont](../baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Imposta le informazioni sul carattere latino. Null significa che il carattere non è definito e dovrebbe essere ereditato dal Master. Scrivi [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](../baseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) override | Determina se l'altezza di un testo debba essere normalizzata. Nessuna eredità applicata. Scrivi [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](../baseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) override | Determina se il testo non debba essere corretto. Nessuna eredità applicata. Scrivi [NullableBool](../nullablebool/). |
| void [set_SmartTagClean](./set_smarttagclean/)(**bool**) override | Determina se lo smart tag debba essere pulito. Nessuna eredità applicata. Scrivi **bool**. |
| void [set_Spacing](../baseportionformat/set_spacing/)(**float**) override | Imposta l'incremento di spaziatura intercarattere. **std::numeric_limits<float>::quiet_NaN()** indica che il valore è non definito e dovrebbe essere ereditato dal Master. Scrivi **float**. |
| void [set_SpellCheck](../baseportionformat/set_spellcheck/)(**bool**) override | Imposta un valore che indica se il controllo ortografico è abilitato per la porzione di testo. Quando questa proprietà è impostata a false, i controlli ortografici per gli elementi di testo sono soppressi. Quando impostata a true, il controllo ortografico è consentito. Il valore predefinito è **false**. |
| void [set_StrikethroughType](../baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Imposta il tipo di barratura di un testo. Nessuna eredità applicata. Scrivi [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](../baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Imposta le informazioni sul carattere simbolico. Null significa che il carattere non è definito e dovrebbe essere ereditato dal Master. Scrivi [IFontData](../ifontdata/). |
| void [set_TextCapType](../baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Imposta il tipo di capitalizzazione del testo. Nessuna eredità applicata. Scrivi [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (invece che condiviso). Consente di cambiare i puntatori nei contenitori in modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Restituisce il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa i puntatori smart o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usa i puntatori smart o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa i puntatori smart o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usa i puntatori smart o ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Osservazioni


Questa classe è usata per restituire e manipolare le proprietà di formattazione delle porzioni di testo definite per la specifica porzione. Ciò significa che nessuna ereditarietà è applicata quando si ottengono i valori, quindi nella maggior parte dei casi otterrete valori che significano "non definito".

Per ottenere i valori dei parametri di formattazione effective, inclusa l'ereditarietà, è necessario utilizzare il metodo [PortionFormat::GetEffective](./geteffective/) che restituisce un'istanza [IPortionFormatEffectiveData](../iportionformateffectivedata/).

L'esempio seguente mostra come assegnare il carattere latino a una porzione [Paragraph](../paragraph/) di PowerPoint [Presentation](../presentation/).

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

System::SharedPtr<Paragraph> paragraph = System::MakeObject<Paragraph>();
System::SharedPtr<Portion> portion = System::MakeObject<Portion>(u"Theme text format");
paragraph->get_Portions()->Add(portion);
shape->get_TextFrame()->get_Paragraphs()->Add(paragraph);
// Aspose.Slides usa questi identificatori speciali (simili a quelli usati in PowerPoint):
// +mn-lt - Carattere del corpo Latin (Font Latin Minore)
// +mj-lt - Carattere dell'intestazione Latin (Font Latin Maggiore)
// +mn-ea - Carattere del corpo East Asian (Font East Asian Minore)
// +mj-ea - Carattere del corpo East Asian (Font East Asian Minore)
portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"+mn-lt"));
```

## Vedi anche

* Classe [BasePortionFormat](../baseportionformat/)
* Classe [IPortionFormat](../iportionformat/)
* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)