---
title: IBasePortionFormat
second_title: Aspose.Slides voor C++ API-referentie
description: Deze klasse bevat de opmaak-eigenschappen van tekstgedeelten. In tegenstelling tot IPortionFormatEffectiveData zijn alle eigenschappen van deze klasse schrijfbaar.
type: docs
weight: 1457
url: /nl/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat klasse


Deze klasse bevat de opmaak-eigenschappen van tekstgedeeltes. In tegenstelling tot [IPortionFormatEffectiveData](../iportionformateffectivedata/) zijn alle eigenschappen van deze klasse schrijfbaar.

```cpp
class IBasePortionFormat : public virtual System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan een waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan een waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | Retourneert de Id van een alternatieve taal. Lezen [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | Retourneert de complex script lettertype-informatie. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Lezen [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | Retourneert de Oost-Aziatische lettertype-informatie. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Lezen [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | Retourneert de tekst [EffectFormat](../effectformat/)-eigenschappen. Geen overerving toegepast. Alleen-lezen [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](./get_escapement/)() | Retourneert de superscript- of subscript-tekst. Waarde van -100% (subscript) tot 100% (superscript). **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Lezen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | Retourneert de tekst [FillFormat](../fillformat/)-eigenschappen. Geen overerving toegepast. Alleen-lezen [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() | Bepaalt of het lettertype vet is. Geen overerving toegepast. Lezen [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](./get_fontheight/)() | Retourneert de letterhoogte van een gedeelte. **std::numeric_limits<float>::quiet_NaN()** betekent dat de hoogte ongedefinieerd is en moet worden geërfd van de Master. Lezen **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() | Bepaalt of het lettertype cursief is. Geen overerving toegepast. Lezen [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | Retourneert het onderstreeptype van de tekst. Geen overerving toegepast. Lezen [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() | Retourneert de kleur die wordt gebruikt om een tekst te markeren. Geen overerving toegepast. Alleen-lezen [IColorFormat](../icolorformat/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | Bepaalt of de onderstreelestijl eigen [FillFormat](../fillformat/)-eigenschappen heeft of ze erft van de [FillFormat](../fillformat/)-eigenschappen van de tekst. Lezen [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | Bepaalt of de onderstreelestijl eigen [LineFormat](../lineformat/)-eigenschappen heeft of ze erft van de [LineFormat](../lineformat/)-eigenschappen van de tekst. Lezen [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | Retourneert de minimale lettergrootte waarvoor kerning ingeschakeld moet worden. **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Lezen **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() | Bepaalt of de cijfers de specifieke verticale tekstlay-out van oosterse talen moeten negeren. Geen overerving toegepast. Lezen [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | Retourneert de Id van een proefleestaal. Wordt gebruikt voor spellings- en grammaticacontrole. Lezen [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | Retourneert de Latijnse lettertype-informatie. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Lezen [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | Retourneert de [LineFormat](../lineformat/)-eigenschappen voor tekstcontour. Geen overerving toegepast. Alleen-lezen [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Geen overerving toegepast. Lezen [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() | Bepaalt of de tekst niet moet worden proefgelezen. Geen overerving toegepast. Lezen [NullableBool](../nullablebool/). |
| virtual **float** [get_Spacing](./get_spacing/)() | Retourneert de interkarakter-spaciëringsincrement. **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Lezen **float**. |
| virtual **bool** [get_SpellCheck](./get_spellcheck/)() | Krijgt een waarde die aangeeft of spellingcontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap op false is ingesteld, worden spellingcontroles voor textelementen onderdrukt. Wanneer ingesteld op true, is spellingcontrole toegestaan. Standaardwaarde is **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | Retourneert het doorhalings-type van een tekst. Geen overerving toegepast. Lezen [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | Retourneert de symbolische lettertype-informatie. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Lezen [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | Retourneert het type hoofdlettergebruik van de tekst. Geen overerving toegepast. Lezen [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | Retourneert de onderstrepingslijn [FillFormat](../fillformat/)-eigenschappen. Geen overerving toegepast. Alleen-lezen [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | Retourneert de [LineFormat](../lineformat/)-eigenschappen die worden gebruikt om de onderstrepingslijn te omlijnen. Geen overerving toegepast. Alleen-lezen [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Krijgt de referentieteller-datastructuur die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Stelt hashfuncties voor aangepaste objecten in staat. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Krijgt het werkelijke type van het object. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-wachtobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Stelt klonen van aangepaste typen in staat. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, echt; initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt; initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr per referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) | Stelt de Id van een alternatieve taal in. Schrijven [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Stelt de complex script lettertype-informatie in. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Schrijven [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Stelt de Oost-Aziatische lettertype-informatie in. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Schrijven [IFontData](../ifontdata/). |
| virtual void [set_Escapement](./set_escapement/)(**float**) | Stelt de superscript- of subscript-tekst in. Waarde van -100% (subscript) tot 100% (superscript). **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Schrijven **float**. |
| virtual void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) | Bepaalt of het lettertype vet is. Geen overheritance toegepast. Schrijven [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](./set_fontheight/)(**float**) | Stelt de letterhoogte van een gedeelte in. **std::numeric_limits<float>::quiet_NaN()** betekent dat de hoogte ongedefinieerd is en moet worden geërfd van de Master. Schrijven **float**. |
| virtual void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) | Bepaalt of het lettertype cursief is. Geen overerving toegepast. Schrijven [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Stelt het onderstreeptype van de tekst in. Geen overerving toegepast. Schrijven [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Bepaalt of de onderstreelestijl eigen [FillFormat](../fillformat/)-eigenschappen heeft of ze erft van de [FillFormat](../fillformat/)-eigenschappen van de tekst. Schrijven [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Bepaalt of de onderstreelestijl eigen [LineFormat](../lineformat/)-eigenschappen heeft of ze erft van de [LineFormat](../lineformat/)-eigenschappen van de tekst. Schrijven [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) | Stelt de minimale lettergrootte in waarvoor kerning moet worden ingeschakeld. **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Schrijven **float**. |
| virtual void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) | Bepaalt of de cijfers de specifieke verticale tekstlay-out van oosterse talen moeten negeren. Geen overerving toegepast. Schrijven [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) | Stelt de Id van een proefleestaal in. Wordt gebruikt voor spellings- en grammaticacontrole. Schrijven [System::String](../../system/string/). |
| virtual void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Stelt de Latijnse lettertype-informatie in. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Schrijven [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Geen overerving toegepast. Schrijven [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) | Bepaalt of de tekst niet moet worden proefgelezen. Geen overerving toegepast. Schrijven [NullableBool](../nullablebool/). |
| virtual void [set_Spacing](./set_spacing/)(**float**) | Stelt de interkarakter-spaciëringsincrement in. **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Schrijven **float**. |
| virtual void [set_SpellCheck](./set_spellcheck/)(**bool**) | Stelt een waarde in die aangeeft of spellingcontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap op false is ingesteld, worden spellingcontroles voor textelementen onderdrukt. Wanneer ingesteld op true, is spellingcontrole toegestaan. Standaardwaarde is **false**. |
| virtual void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Stelt het doorhalings-type van een tekst in. Geen overerving toegepast. Schrijven [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Stelt de symbolische lettertype-informatie in. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Schrijven [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Stelt het type hoofdlettergebruik van de tekst in. Geen overerving toegepast. Schrijven [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Staat toe dat pointers in containers naar zwakke modus worden geschakeld. |
| int [SharedCount](../../system/object/sharedcount/)() const | Krijgt de huidige waarde van de gedeelde referentieteller. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Stelt het omzetten van aangepaste objecten naar string in staat. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-wachtobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |
## Opmerkingen


Deze klasse wordt gebruikt om de opmaak-eigenschappen van een tekstgedeelte die voor het specifieke gedeelte zijn gedefinieerd op te halen en te manipuleren. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, dus in de meeste gevallen krijg je waarden die "onbepaald" betekenen.

Om de effectieve opmaakparameterwaarden inclusief geërfde waarden te verkrijgen, moet je de [IPortionFormat::GetEffective](../iportionformat/geteffective/)-methode gebruiken die een [IPortionFormatEffectiveData](../iportionformateffectivedata/)-instantie retourneert.
## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)