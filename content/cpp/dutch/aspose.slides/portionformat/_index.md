---
title: PortionFormat
second_title: Aspose.Slides voor C++ API-referentie
description: Deze klasse bevat de tekstgedeelte-opmaak eigenschappen. In tegenstelling tot IPortionFormatEffectiveData zijn alle eigenschappen van deze klasse schrijfbaar.
type: docs
weight: 4811
url: /nl/aspose.slides/portionformat/
---
## PortionFormat klasse

Deze klasse bevat de tekstgedeelte-opmaak eigenschappen. In tegenstelling tot [IPortionFormatEffectiveData](../iportionformateffectivedata/) zijn alle eigenschappen van deze klasse schrijfbaar.

```cpp
class PortionFormat : public Aspose::Slides::BasePortionFormat,
                      public Aspose::Slides::IPortionFormat
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Vergelijkt met het opgegeven object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-achtige drijvende-kommagetaling waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-achtige drijvende-kommagetaling waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../baseportionformat/get_alternativelanguageid/)() override | Retourneert de Id van een alternatieve taal. Lees [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() override | Retourneert bladwijzeridentificatie. Lees [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../baseportionformat/get_complexscriptfont/)() override | Retourneert de complexe script-lettertype-info. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Lees [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../baseportionformat/get_eastasianfont/)() override | Retourneert de Oost-Aziatische lettertype-info. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Lees [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../baseportionformat/get_effectformat/)() override | Retourneert de tekst [EffectFormat](../effectformat/) eigenschappen. Geen overerving toegepast. Alleen-lezen [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](../baseportionformat/get_escapement/)() override | Retourneert de superscript- of subscript-tekst. Waarde van -100% (subscript) tot 100% (superscript). **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Lees **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../baseportionformat/get_fillformat/)() override | Retourneert de tekst [FillFormat](../fillformat/) eigenschappen. Geen overerving toegepast. Alleen-lezen [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](../baseportionformat/get_fontbold/)() override | Bepaalt of het lettertype vetgedrukt is. Geen overerving toegepast. Lees [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](../baseportionformat/get_fontheight/)() override | Retourneert de letterhoogte van een gedeelte. **std::numeric_limits<float>::quiet_NaN()** betekent dat de hoogte ongedefinieerd is en moet worden geërfd van de Master. Lees **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](../baseportionformat/get_fontitalic/)() override | Bepaalt of het lettertype cursief is. Geen overerving toegepast. Lees [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../baseportionformat/get_fontunderline/)() override | Retourneert het onderstreeptype van de tekst. Geen overerving toegepast. Lees [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../baseportionformat/get_highlightcolor/)() override | Retourneert de kleur die wordt gebruikt om een tekst te markeren. Geen overerving toegepast. Alleen-lezen [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | Retourneert de hyperlink gedefinieerd voor muisklik. Lees [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | Hyperlinksbeheerder. Alleen-lezen [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | Retourneert de hyperlink gedefinieerd voor muis-hover. Lees [IHyperlink](../ihyperlink/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../baseportionformat/get_ishardunderlinefill/)() override | Bepaalt of de onderstreele stijl eigen [FillFormat](../fillformat/) eigenschappen heeft of deze erft van de [FillFormat](../fillformat/) eigenschappen van de tekst. Lees [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../baseportionformat/get_ishardunderlineline/)() override | Bepaalt of de onderstreele stijl eigen [LineFormat](../lineformat/) eigenschappen heeft of deze erft van de [LineFormat](../lineformat/) eigenschappen van de tekst. Lees [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](../baseportionformat/get_kerningminimalsize/)() override | Retourneert de minimale lettergrootte waarvoor kerning moet worden ingeschakeld. **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Lees **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](../baseportionformat/get_kumimoji/)() override | Bepaalt of de nummers de oosterse taalspecifieke verticale lay-out van de tekst moeten negeren. Geen overerving toegepast. Lees [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](../baseportionformat/get_languageid/)() override | Retourneert de Id van een proefleestaal. Gebruikt voor spelling- en grammaticacontrole. Lees [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../baseportionformat/get_latinfont/)() override | Retourneert de Latijnse lettertype-info. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Lees [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../baseportionformat/get_lineformat/)() override | Retourneert de [LineFormat](../lineformat/) eigenschappen voor tekstomlijning. Geen overerving toegepast. Alleen-lezen [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](../baseportionformat/get_normaliseheight/)() override | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Geen overerving toegepast. Lees [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Retourneert Parent_Immediate object. Alleen-lezen [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Retourneert ouder [IPresentationComponent](../ipresentationcomponent/). Alleen-lezen [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](../baseportionformat/get_proofdisabled/)() override | Bepaalt of de tekst niet proefgelezen mag worden. Geen overerving toegepast. Lees [NullableBool](../nullablebool/). |
| **bool** [get_SmartTagClean](./get_smarttagclean/)() override | Bepaalt of de slimme tag moet worden opgeschoond. Geen overerving toegepast. Lees **bool**. |
| **float** [get_Spacing](../baseportionformat/get_spacing/)() override | Retourneert de interkarakter-spatiërings-increment. **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Lees **float**. |
| **bool** [get_SpellCheck](../baseportionformat/get_spellcheck/)() override | Krijgt een waarde die aangeeft of spellingcontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap op false wordt gezet, worden spellingcontroles voor tekstelementen onderdrukt. Wanneer deze op true wordt gezet, is spellingcontrole toegestaan. Standaardwaarde is **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../baseportionformat/get_strikethroughtype/)() override | Retourneert het doorhalings-type van een tekst. Geen overerving toegepast. Lees [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../baseportionformat/get_symbolfont/)() override | Retourneert de symbolische lettertype-info. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Lees [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../baseportionformat/get_textcaptype/)() override | Retourneert het type tekstkapitalisatie. Geen overerving toegepast. Lees [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../baseportionformat/get_underlinefillformat/)() override | Retourneert de onderstreeplijn [FillFormat](../fillformat/) eigenschappen. Geen overerving toegepast. Alleen-lezen [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../baseportionformat/get_underlinelineformat/)() override | Retourneert de [LineFormat](../lineformat/) eigenschappen die worden gebruikt om de onderstreeplijn te omranden. Geen overerving toegepast. Alleen-lezen [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Krijgt de referentieteller-datastructuur geassocieerd met het object. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() override | Krijgt effectieve gedeelte-opmaakgegevens met de toegepaste overerving. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Retourneert hash-code. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Krijgt het feitelijke type van het object. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieconstructor. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiërende te construeren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, echt, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiërende te construeren. |
|  [PortionFormat](./portionformat/)() | Initialiseert een nieuw exemplaar van [PortionFormat](./) klasse. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentiewaarde-type object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_AlternativeLanguageId](../baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | Stelt de Id van een alternatieve taal in. Schrijf [System::String](../../system/string/). |
| void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) override | Stelt bladwijzeridentificatie in. Schrijf [System::String](../../system/string/). |
| void [set_ComplexScriptFont](../baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Stelt de complexe script-lettertype-info in. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Schrijf [IFontData](../ifontdata/). |
| void [set_EastAsianFont](../baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Stelt de Oost-Aziatische lettertype-info in. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Schrijf [IFontData](../ifontdata/). |
| void [set_Escapement](../baseportionformat/set_escapement/)(**float**) override | Stelt de superscript- of subscript-tekst in. Waarde van -100% (subscript) tot 100% (superscript). **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Schrijf **float**. |
| void [set_FontBold](../baseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) override | Bepaalt of het lettertype vetgedrukt is. Geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| void [set_FontHeight](../baseportionformat/set_fontheight/)(**float**) override | Stelt de letterhoogte van een gedeelte in. **std::numeric_limits<float>::quiet_NaN()** betekent dat de hoogte ongedefinieerd is en moet worden geërfd van de Master. Schrijf **float**. |
| void [set_FontItalic](../baseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) override | Bepaalt of het lettertype cursief is. Geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| void [set_FontUnderline](../baseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Stelt het onderstreeptype van de tekst in. Geen overerving toegepast. Schrijf [TextUnderlineType](../textunderlinetype/). |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Stelt de hyperlink in gedefinieerd voor muisklik. Schrijf [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Stelt de hyperlink in gedefinieerd voor muis-hover. Schrijf [IHyperlink](../ihyperlink/). |
| void [set_IsHardUnderlineFill](../baseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Bepaalt of de onderstreele stijl eigen [FillFormat](../fillformat/) eigenschappen heeft of deze erft van de [FillFormat](../fillformat/) eigenschappen van de tekst. Schrijf [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](../baseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Bepaalt of de onderstreele stijl eigen [LineFormat](../lineformat/) eigenschappen heeft of deze erft van de [LineFormat](../lineformat/) eigenschappen van de tekst. Schrijf [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](../baseportionformat/set_kerningminimalsize/)(**float**) override | Stelt de minimale lettergrootte in waarvoor kerning moet worden ingeschakeld. **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Schrijf **float**. |
| void [set_Kumimoji](../baseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) override | Bepaalt of de nummers de oosterse taalspecifieke verticale lay-out van de tekst moeten negeren. Geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| void [set_LanguageId](../baseportionformat/set_languageid/)([System::String](../../system/string/)) override | Stelt de Id van een proefleestaal in. Gebruikt voor spelling- en grammaticacontrole. Schrijf [System::String](../../system/string/). |
| void [set_LatinFont](../baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Stelt de Latijnse lettertype-info in. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Schrijf [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](../baseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) override | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](../baseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) override | Bepaalt of de tekst niet proefgelezen mag worden. Geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| void [set_SmartTagClean](./set_smarttagclean/)(**bool**) override | Bepaalt of de slimme tag moet worden opgeschoond. Geen overerving toegepast. Schrijf **bool**. |
| void [set_Spacing](../baseportionformat/set_spacing/)(**float**) override | Stelt de interkarakter-spatiërings-increment in. **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Schrijf **float**. |
| void [set_SpellCheck](../baseportionformat/set_spellcheck/)(**bool**) override | Stelt een waarde in die aangeeft of spellingcontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap op false wordt gezet, worden spellingcontroles voor tekstelementen onderdrukt. Wanneer deze op true wordt gezet, is spellingcontrole toegestaan. Standaardwaarde is **false**. |
| void [set_StrikethroughType](../baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Stelt het doorhalings-type van een tekst in. Geen overerving toegepast. Schrijf [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](../baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Stelt de symbolische lettertype-info in. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Schrijf [IFontData](../ifontdata/). |
| void [set_TextCapType](../baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Stelt het type tekstkapitalisatie in. Geen overerving toegepast. Schrijf [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th template-argument in op een zwakke pointer (in plaats van gedeelde). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Krijgt de huidige waarde van de gedeelde referentieteller. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Opmerkingen

Deze klasse wordt gebruikt om tekstgedeelte-opmaak eigenschappen te retourneren en te manipuleren die zijn gedefinieerd voor het specifieke gedeelte. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, dus in de meeste gevallen krijg je waarden die "ongedefinieerd" betekenen.

Om de effectieve opmaak-parameterwaarden, inclusief geërfde, te krijgen, moet je de [PortionFormat::GetEffective](./geteffective/) methode gebruiken die een [IPortionFormatEffectiveData](../iportionformateffectivedata/) instantie teruggeeft.

Het volgende voorbeeld toont hoe je het Latijnse lettertype toewijst aan een [Paragraph](../paragraph/)-gedeelte van PowerPoint [Presentation](../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

System::SharedPtr<Paragraph> paragraph = System::MakeObject<Paragraph>();
System::SharedPtr<Portion> portion = System::MakeObject<Portion>(u"Theme text format");
paragraph->get_Portions()->Add(portion);
shape->get_TextFrame()->get_Paragraphs()->Add(paragraph);
// Aspose.Slides gebruikt deze speciale identificatoren (vergelijkbaar met die gebruikt in PowerPoint):
// +mn-lt - Body Lettertype Latin (Klein Latin-lettertype)
// +mj-lt - Heading Lettertype Latin (Groot Latin-lettertype)
// +mn-ea - Body Lettertype East Asian (Klein East Asian-lettertype)
// +mj-ea - Body Lettertype East Asian (Klein East Asian-lettertype)
portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"+mn-lt"));
```

## Zie ook

* Klasse [BasePortionFormat](../baseportionformat/)
* Klasse [IPortionFormat](../iportionformat/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)