---
title: BasePortionFormat
second_title: Riferimento API di Aspose.Slides per C++
description: Proprietà comuni di formattazione della porzione di testo.
type: docs
weight: 144
url: /it/aspose.slides/baseportionformat/
---
## BasePortionFormat classe

Proprietà di formattazione della porzione di testo comune.

```cpp
class BasePortionFormat : public Aspose::Slides::PVIObject,
                          public virtual Aspose::Slides::IBasePortionFormat
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Confronta con l'oggetto specificato. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo riferimento in stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se secondo IEC 60559:1989 NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per scopi interni. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() override | Restituisce l'Id di una lingua alternativa. Leggi [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() override | Restituisce le informazioni sul font script complesso. Null indica che il font è indefinito e dovrebbe essere ereditato dal Master. Leggi [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() override | Restituisce le informazioni sul font East Asian. Null indica che il font è indefinito e dovrebbe essere ereditato dal Master. Leggi [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | Restituisce le proprietà del testo [EffectFormat](../effectformat/). Nessuna ereditarietà applicata. Solo lettura [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](./get_escapement/)() override | Restituisce il testo in apice o pedice. Valore da -100% (pedice) a 100% (apice). **std::numeric_limits<float>::quiet_NaN()** indica che il valore è indefinito e dovrebbe essere ereditato dal Master. Leggi **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Restituisce le proprietà del testo [FillFormat](../fillformat/). Nessuna ereditarietà applicata. Solo lettura [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() override | Determina se il font è in grassetto. Nessuna ereditarietà applicata. Leggi [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](./get_fontheight/)() override | Restituisce l'altezza del font di una porzione. **std::numeric_limits<float>::quiet_NaN()** indica che l'altezza è indefinita e dovrebbe essere ereditata dal Master. Leggi **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() override | Determina se il font è itallic. Nessuna ereditarietà applicata. Leggi [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() override | Restituisce il tipo di sottolineatura del testo. Nessuna ereditarietà applicata. Leggi [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() override | Restituisce il colore usato per evidenziare un testo. Nessuna ereditarietà applicata. Solo lettura [IColorFormat](../icolorformat/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() override | Determina se lo stile di sottolineatura ha proprie proprietà [FillFormat](../fillformat/) oppure le eredita dalle proprietà [FillFormat](../fillformat/) del testo. Leggi [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() override | Determina se lo stile di sottolineatura ha proprie proprietà [LineFormat](../lineformat/) oppure le eredita dalle proprietà [LineFormat](../lineformat/) del testo. Leggi [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() override | Restituisce la dimensione minima del font, per cui il kerning dovrebbe essere attivato. **std::numeric_limits<float>::quiet_NaN()** indica che il valore è indefinito e dovrebbe essere ereditato dal Master. Leggi **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() override | Determina se i numeri dovrebbero ignorare il layout verticale del testo specifico per lingua orientale. Nessuna ereditarietà applicata. Leggi [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() override | Restituisce l'Id di una lingua di correzione. Usato per il controllo ortografico e grammaticale. Leggi [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() override | Restituisce le informazioni sul font Latino. Null indica che il font è indefinito e dovrebbe essere ereditato dal Master. Leggi [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | Restituisce le proprietà [LineFormat](../lineformat/) per il contorno del testo. Nessuna ereditarietà applicata. Solo lettura [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() override | Determina se l'altezza di un testo dovrebbe essere normalizzata. Nessuna ereditarietà applicata. Leggi [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Restituisce l'oggetto Parent_Immediate. Solo lettura [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Restituisce il parent [IPresentationComponent](../ipresentationcomponent/). Solo lettura [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() override | Determina se il testo non dovrebbe essere corretto. Nessuna ereditarietà applicata. Leggi [NullableBool](../nullablebool/). |
| **float** [get_Spacing](./get_spacing/)() override | Restituisce l'incremento della spaziatura intercarattere. **std::numeric_limits<float>::quiet_NaN()** indica che il valore è indefinito e dovrebbe essere ereditato dal Master. Leggi **float**. |
| **bool** [get_SpellCheck](./get_spellcheck/)() override | Ottiene un valore che indica se il controllo ortografico è abilitato per la porzione di testo. Quando questa proprietà è impostata su false, i controlli ortografici sugli elementi di testo sono soppressi. Quando impostata su true, il controllo ortografico è consentito. Il valore predefinito è **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() override | Restituisce il tipo di barrato di un testo. Nessuna ereditarietà applicata. Leggi [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() override | Restituisce le informazioni sul font simbolico. Null indica che il font è indefinito e dovrebbe essere ereditato dal Master. Leggi [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() override | Restituisce il tipo di capitalizzazione del testo. Nessuna ereditarietà applicata. Leggi [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() override | Restituisce le proprietà della linea di sottolineatura [FillFormat](../fillformat/). Nessuna ereditarietà applicata. Solo lettura [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() override | Restituisce le proprietà [LineFormat](../lineformat/) usate per delineare la linea di sottolineatura. Nessuna ereditarietà applicata. Solo lettura [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimento associata all'oggetto. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Restituisce il codice hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo effettivo dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il lock() statement C# per il blocco. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Consente la clonazione di tipi personalizzati. |
| [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia realmente nulla, ma inizializza un nuovo oggetto e consente la costruzione copia delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia realmente nulla, ma inizializza un nuovo oggetto e consente la costruzione copia delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento l'oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decrementa il contatore di riferimento condiviso del valore specificato. |
| void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) override | Imposta l'Id di una lingua alternativa. Scrivi [System::String](../../system/string/). |
| void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Imposta le informazioni sul font script complesso. Null indica che il font è indefinito e dovrebbe essere ereditato dal Master. Scrivi [IFontData](../ifontdata/). |
| void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Imposta le informazioni sul font East Asian. Null indica che il font è indefinito e dovrebbe essere ereditato dal Master. Scrivi [IFontData](../ifontdata/). |
| void [set_Escapement](./set_escapement/)(**float**) override | Imposta il testo in apice o pedice. Valore da -100% (pedice) a 100% (apice). **std::numeric_limits<float>::quiet_NaN()** indica che il valore è indefinito e dovrebbe essere ereditato dal Master. Scrivi **float**. |
| void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) override | Determina se il font è in grassetto. Nessuna ereditarietà applicata. Scrivi [NullableBool](../nullablebool/). |
| void [set_FontHeight](./set_fontheight/)(**float**) override | Imposta l'altezza del font di una porzione. **std::numeric_limits<float>::quiet_NaN()** indica che l'altezza è indefinita e dovrebbe essere ereditata dal Master. Scrivi **float**. |
| void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) override | Determina se il font è itallic. Nessuna ereditarietà applicata. Scrivi [NullableBool](../nullablebool/). |
| void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Imposta il tipo di sottolineatura del testo. Nessuna ereditarietà applicata. Scrivi [TextUnderlineType](../textunderlinetype/). |
| void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Determina se lo stile di sottolineatura ha proprie proprietà [FillFormat](../fillformat/) oppure le eredita dalle proprietà [FillFormat](../fillformat/) del testo. Scrivi [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Determina se lo stile di sottolineatura ha proprie proprietà [LineFormat](../lineformat/) oppure le eredita dalle proprietà [LineFormat](../lineformat/) del testo. Scrivi [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) override | Imposta la dimensione minima del font, per cui il kerning dovrebbe essere attivato. **std::numeric_limits<float>::quiet_NaN()** indica che il valore è indefinito e dovrebbe essere ereditato dal Master. Scrivi **float**. |
| void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) override | Determina se i numeri dovrebbero ignorare il layout verticale del testo specifico per lingua orientale. Nessuna ereditarietà applicata. Scrivi [NullableBool](../nullablebool/). |
| void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) override | Imposta l'Id di una lingua di correzione. Usato per il controllo ortografico e grammaticale. Scrivi [System::String](../../system/string/). |
| void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Imposta le informazioni sul font Latino. Null indica che il font è indefinito e dovrebbe essere ereditato dal Master. Scrivi [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) override | Determina se l'altezza di un testo dovrebbe essere normalizzata. Nessuna ereditarietà applicata. Scrivi [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) override | Determina se il testo non dovrebbe essere corretto. Nessuna ereditarietà applicata. Scrivi [NullableBool](../nullablebool/). |
| void [set_Spacing](./set_spacing/)(**float**) override | Imposta l'incremento della spaziatura intercarattere. **std::numeric_limits<float>::quiet_NaN()** indica che il valore è indefinito e dovrebbe essere ereditato dal Master. Scrivi **float**. |
| void [set_SpellCheck](./set_spellcheck/)(**bool**) override | Imposta un valore che indica se il controllo ortografico è abilitato per la porzione di testo. Quando questa proprietà è impostata su false, i controlli ortografici sugli elementi di testo sono soppressi. Quando impostata su true, il controllo ortografico è consentito. Il valore predefinito è **false**. |
| void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Imposta il tipo di barrato di un testo. Nessuna ereditarietà applicata. Scrivi [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Imposta le informazioni sul font simbolico. Null indica che il font è indefinito e dovrebbe essere ereditato dal Master. Scrivi [IFontData](../ifontdata/). |
| void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Imposta il tipo di capitalizzazione del testo. Nessuna ereditarietà applicata. Scrivi [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template a un weak pointer (piuttosto che shared). Consente di passare i puntatori nei contenitori in modalità weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimento condiviso. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointers o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimento condiviso. Non dovrebbe essere chiamato direttamente; invece, usare smart pointers o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Consente la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco del lock() statement C#. Chiamare direttamente o usare l'oggetto sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointers o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimento debole. Non dovrebbe essere chiamato direttamente; invece, usare smart pointers o ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Vedi anche

* Classe [PVIObject](../pviobject/)
* Classe [IBasePortionFormat](../ibaseportionformat/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)