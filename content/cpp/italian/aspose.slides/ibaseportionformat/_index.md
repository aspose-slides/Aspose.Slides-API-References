---
title: IBasePortionFormat
second_title: Riferimento API di Aspose.Slides per C++
description: Questa classe contiene le proprietà di formattazione della porzione di testo. A differenza di IPortionFormatEffectiveData, tutte le proprietà di questa classe sono scrivibili.
type: docs
weight: 1457
url: /it/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat classe

Questa classe contiene le proprietà di formattazione della porzione di testo. A differenza di [IPortionFormatEffectiveData](../iportionformateffectivedata/), tutte le proprietà di questa classe sono scrivibili.

```cpp
class IBasePortionFormat : public virtual System::Object
```

## Metodi

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Confronta gli oggetti usando la semantica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo reference nello stile C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Confronta oggetti di tipo valore nello stile C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula il confronto in virgola mobile in stile C# dove due NaN sono considerati uguali anche se, secondo IEC 60559:1989, NaN non è uguale a nessun valore, incluso NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo per uso interno. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | Restituisce l'Id di una lingua alternativa. Leggi [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | Restituisce le informazioni sul font a script complesso. Null indica che il font è indefinito e dovrebbe essere ereditato dal Master. Leggi [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | Restituisce le informazioni sul font orientale. Null indica che il font è indefinito e dovrebbe essere ereditato dal Master. Leggi [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | Restituisce le proprietà del testo [EffectFormat](../effectformat/). Nessuna ereditarietà applicata. Solo lettura [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](./get_escapement/)() | Restituisce il testo in apice o pedice. Valore da -100% (pedice) a 100% (apice). **std::numeric_limits<float>::quiet_NaN()** indica che il valore è indefinito e dovrebbe essere ereditato dal Master. Leggi **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | Restituisce le proprietà del testo [FillFormat](../fillformat/). Nessuna ereditarietà applicata. Solo lettura [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() | Determina se il font è in grassetto. Nessuna ereditarietà applicata. Leggi [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](./get_fontheight/)() | Restituisce l'altezza del font di una porzione. **std::numeric_limits<float>::quiet_NaN()** indica che l'altezza è indefinita e dovrebbe essere ereditata dal Master. Leggi **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() | Determina se il font è italico. Nessuna ereditarietà applicata. Leggi [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | Restituisce il tipo di sottolineatura del testo. Nessuna ereditarietà applicata. Leggi [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() | Restituisce il colore usato per evidenziare un testo. Nessuna ereditarietà applicata. Solo lettura [IColorFormat](../icolorformat/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | Determina se lo stile di sottolineatura ha proprie proprietà [FillFormat](../fillformat/) o le eredita dalle proprietà [FillFormat](../fillformat/) del testo. Leggi [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | Determina se lo stile di sottolineatura ha proprie proprietà [LineFormat](../lineformat/) o le eredita dalle proprietà [LineFormat](../lineformat/) del testo. Leggi [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | Restituisce la dimensione minima del font, per la quale il kerning dovrebbe essere attivato. **std::numeric_limits<float>::quiet_NaN()** indica che il valore è indefinito e dovrebbe essere ereditato dal Master. Leggi **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() | Determina se i numeri devono ignorare il layout verticale del testo specifico per le lingue orientali. Nessuna ereditarietà applicata. Leggi [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | Restituisce l'Id di una lingua di revisione. Usata per il controllo ortografico e grammaticale. Leggi [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | Restituisce le informazioni sul font latino. Null indica che il font è indefinito e dovrebbe essere ereditato dal Master. Leggi [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | Restituisce le proprietà [LineFormat](../lineformat/) per il contorno del testo. Nessuna ereditarietà applicata. Solo lettura [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() | Determina se l'altezza del testo dovrebbe essere normalizzata. Nessuna ereditarietà applicata. Leggi [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() | Determina se il testo non deve essere revisionato. Nessuna ereditarietà applicata. Leggi [NullableBool](../nullablebool/). |
| virtual **float** [get_Spacing](./get_spacing/)() | Restituisce l'incremento della spaziatura intercarattere. **std::numeric_limits<float>::quiet_NaN()** indica che il valore è indefinito e dovrebbe essere ereditato dal Master. Leggi **float**. |
| virtual **bool** [get_SpellCheck](./get_spellcheck/)() | Ottiene un valore che indica se il controllo ortografico è abilitato per la porzione di testo. Quando questa proprietà è impostata su false, i controlli ortografici per gli elementi di testo sono soppressi. Quando è impostata su true, il controllo ortografico è consentito. Il valore predefinito è **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | Restituisce il tipo di barrato di un testo. Nessuna ereditarietà applicata. Leggi [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | Restituisce le informazioni sul font simbolico. Null indica che il font è indefinito e dovrebbe essere ereditato dal Master. Leggi [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | Restituisce il tipo di capitalizzazione del testo. Nessuna ereditarietà applicata. Leggi [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | Restituisce le proprietà della linea di sottolineatura [FillFormat](../fillformat/). Nessuna ereditarietà applicata. Solo lettura [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | Restituisce le proprietà [LineFormat](../lineformat/) usate per contornare la linea di sottolineatura. Nessuna ereditarietà applicata. Solo lettura [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ottiene la struttura dati del contatore di riferimenti associata all'oggetto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del metodo C# [Object.GetHashCode()](../../system/object/gethashcode/). Abilita l'hashing di oggetti personalizzati. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ottiene il tipo reale dell'oggetto. Analogo della chiamata C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se l'oggetto rappresenta un'istanza del tipo descritto da targetType. Analogo dell'operatore C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa il blocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del metodo C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Abilita la clonazione di tipi personalizzati. |
|  [Object](../../system/object/object/)() | Crea l'oggetto. Inizializza tutte le strutture dati interne. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Costruttore di copia. Non copia nulla, davvero, semplicemente inizializza un nuovo oggetto e abilita la costruzione per copia delle sottoclassi. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operatore di assegnazione. Non copia nulla, davvero, semplicemente inizializza un nuovo oggetto e abilita la costruzione per copia delle sottoclassi. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Confronta gli oggetti per riferimento. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Confronta per riferimento un oggetto di tipo valore con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringa e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializzazione di [Object::ReferenceEquals](../../system/object/referenceequals/) per il caso di stringhe. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminuisce il contatore di riferimenti condivisi del valore specificato. |
| virtual void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) | Imposta l'Id di una lingua alternativa. Scrivi [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Imposta le informazioni sul font a script complesso. Null indica che il font è indefinito e dovrebbe essere ereditato dal Master. Scrivi [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Imposta le informazioni sul font orientale. Null indica che il font è indefinito e dovrebbe essere ereditato dal Master. Scrivi [IFontData](../ifontdata/). |
| virtual void [set_Escapement](./set_escapement/)(**float**) | Imposta il testo in apice o pedice. Valore da -100% (pedice) a 100% (apice). **std::numeric_limits<float>::quiet_NaN()** indica che il valore è indefinito e dovrebbe essere ereditato dal Master. Scrivi **float**. |
| virtual void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) | Determina se il font è in grassetto. Nessuna ereditarietà applicata. Scrivi [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](./set_fontheight/)(**float**) | Imposta l'altezza del font di una porzione. **std::numeric_limits<float>::quiet_NaN()** indica che l'altezza è indefinita e dovrebbe essere ereditata dal Master. Scrivi **float**. |
| virtual void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) | Determina se il font è italico. Nessuna ereditarietà applicata. Scrivi [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Imposta il tipo di sottolineatura del testo. Nessuna ereditarietà applicata. Scrivi [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Determina se lo stile di sottolineatura ha proprie proprietà [FillFormat](../fillformat/) o le eredita dalle proprietà [FillFormat](../fillformat/) del testo. Scrivi [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Determina se lo stile di sottolineatura ha proprie proprietà [LineFormat](../lineformat/) o le eredita dalle proprietà [LineFormat](../lineformat/) del testo. Scrivi [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) | Imposta la dimensione minima del font, per la quale il kerning dovrebbe essere attivato. **std::numeric_limits<float>::quiet_NaN()** indica che il valore è indefinito e dovrebbe essere ereditato dal Master. Scrivi **float**. |
| virtual void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) | Determina se i numeri devono ignorare il layout verticale del testo specifico per le lingue orientali. Nessuna ereditarietà applicata. Scrivi [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) | Imposta l'Id di una lingua di revisione. Usata per il controllo ortografico e grammaticale. Scrivi [System::String](../../system/string/). |
| virtual void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Imposta le informazioni sul font latino. Null indica che il font è indefinito e dovrebbe essere ereditato dal Master. Scrivi [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) | Determina se l'altezza del testo dovrebbe essere normalizzata. Nessuna ereditarietà applicata. Scrivi [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) | Determina se il testo non deve essere revisionato. Nessuna ereditarietà applicata. Scrivi [NullableBool](../nullablebool/). |
| virtual void [set_Spacing](./set_spacing/)(**float**) | Imposta l'incremento della spaziatura intercarattere. **std::numeric_limits<float>::quiet_NaN()** indica che il valore è indefinito e dovrebbe essere ereditato dal Master. Scrivi **float**. |
| virtual void [set_SpellCheck](./set_spellcheck/)(**bool**) | Imposta un valore che indica se il controllo ortografico è abilitato per la porzione di testo. Quando questa proprietà è impostata su false, i controlli ortografici per gli elementi di testo sono soppressi. Quando è impostata su true, il controllo ortografico è consentito. Il valore predefinito è **false**. |
| virtual void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Imposta il tipo di barrato di un testo. Nessuna ereditarietà applicata. Scrivi [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Imposta le informazioni sul font simbolico. Null indica che il font è indefinito e dovrebbe essere ereditato dal Master. Scrivi [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Imposta il tipo di capitalizzazione del testo. Nessuna ereditarietà applicata. Scrivi [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Imposta il n-esimo argomento template come puntatore debole (anziché condiviso). Consente di passare i puntatori nei contenitori a modalità debole. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ottiene il valore corrente del contatore di riferimenti condivisi. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e restituisce il contatore di riferimenti condivisi. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del metodo C# [Object.ToString()](../../system/object/tostring/). Abilita la conversione di oggetti personalizzati in stringa. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la costruzione C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa lo sblocco della dichiarazione C# lock(). Chiamare direttamente o usare l'oggetto sentinella [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa il contatore di riferimenti deboli. Non dovrebbe essere chiamato direttamente; invece, usa smart pointer o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Distrugge l'oggetto. Libera tutte le strutture dati interne. |

## Osservazioni

Questa classe è usata per restituire e manipolare le proprietà di formattazione della porzione di testo definite per la specifica porzione. Ciò significa che non viene applicata alcuna ereditarietà quando si ottengono i valori, quindi nella maggior parte dei casi otterrai valori che significano "non definito".

Per ottenere i valori effettivi dei parametri di formattazione, inclusi quelli ereditati, è necessario utilizzare il metodo [IPortionFormat::GetEffective](../iportionformat/geteffective/) che restituisce un'istanza [IPortionFormatEffectiveData](../iportionformateffectivedata/).

## Vedi anche

* Classe [Object](../../system/object/)
* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)