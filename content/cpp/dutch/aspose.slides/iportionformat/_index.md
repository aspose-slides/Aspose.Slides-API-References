---
title: IPortionFormat
second_title: Aspose.Slides voor C++ API-referentie
description: Deze klasse bevat de tekstgedeelte opmaak eigenschappen. In tegenstelling tot IPortionFormatEffectiveData zijn alle eigenschappen van deze klasse schrijfbaar.
type: docs
weight: 3329
url: /nl/aspose.slides/iportionformat/
---
## IPortionFormat klasse


Deze klasse bevat de tekstgedeelte-opmaak-eigenschappen. In tegenstelling tot [IPortionFormatEffectiveData](../iportionformateffectivedata/) zijn alle eigenschappen van deze klasse schrijfbaar.

```cpp
class IPortionFormat : public virtual Aspose::Slides::IBasePortionFormat,
                       public Aspose::Slides::IHyperlinkContainer
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van referentietype in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt objecten van waardetype in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-achtige floating-point vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-achtige floating-point vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformat/get_alternativelanguageid/)() | Retourneert de Id van een alternatieve taal. Zie [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | Retourneert de bladwijzer-identificatie. Zie [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformat/get_complexscriptfont/)() | Retourneert de informatie over het complexe script-lettertype. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Zie [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformat/get_eastasianfont/)() | Retourneert de informatie over het Oost-Azatische lettertype. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Zie [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ibaseportionformat/get_effectformat/)() | Retourneert de tekst [EffectFormat](../effectformat/) eigenschappen. Er wordt geen overerving toegepast. Alleen-lezen [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](../ibaseportionformat/get_escapement/)() | Retourneert de superscript- of subscript-tekst. Waarde van -100% (subscript) tot 100% (superscript). **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Lezen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ibaseportionformat/get_fillformat/)() | Retourneert de tekst [FillFormat](../fillformat/) eigenschappen. Er wordt geen overerving toegepast. Alleen-lezen [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](../ibaseportionformat/get_fontbold/)() | Bepaalt of het lettertype vet is. Er wordt geen overerving toegepast. Zie [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](../ibaseportionformat/get_fontheight/)() | Retourneert de letterhoogte van een gedeelte. **std::numeric_limits<float>::quiet_NaN()** betekent dat de hoogte ongedefinieerd is en moet worden geërfd van de Master. Zie **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](../ibaseportionformat/get_fontitalic/)() | Bepaalt of het lettertype cursief is. Er wordt geen overerving toegepast. Zie [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformat/get_fontunderline/)() | Retourneert het type onderstreping van de tekst. Er wordt geen overerving toegepast. Zie [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../ibaseportionformat/get_highlightcolor/)() | Retourneert de kleur die wordt gebruikt om tekst te markeren. Er wordt geen overerving toegepast. Alleen-lezen [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Retourneert de hyperlink gedefinieerd voor muisklik. Zie [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlinks-manager Alleen-lezen [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Retourneert de hyperlink gedefinieerd voor muis-over. Zie [IHyperlink](../ihyperlink/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../ibaseportionformat/get_ishardunderlinefill/)() | Bepaalt of de onderstreeptstijl eigen [FillFormat](../fillformat/) eigenschappen heeft of deze erft van de [FillFormat](../fillformat/) eigenschappen van de tekst. Zie [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../ibaseportionformat/get_ishardunderlineline/)() | Bepaalt of de onderstreeptstijl eigen [LineFormat](../lineformat/) eigenschappen heeft of deze erft van de [LineFormat](../lineformat/) eigenschappen van de tekst. Zie [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformat/get_kerningminimalsize/)() | Retourneert de minimale lettergrootte waarvoor kerning moet worden ingeschakeld. **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Zie **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](../ibaseportionformat/get_kumimoji/)() | Bepaalt of de cijfers de specifieke verticale tekstlay-out van oosterse talen moeten negeren. Er wordt geen overerving toegepast. Zie [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformat/get_languageid/)() | Retourneert de Id van een proefleestaal. Wordt gebruikt voor spellings- en grammaticacontrole. Zie [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformat/get_latinfont/)() | Retourneert de informatie over het Latijnse lettertype. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Zie [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ibaseportionformat/get_lineformat/)() | Retourneert de [LineFormat](../lineformat/) eigenschappen voor tekstopvolging. Er wordt geen overerving toegepast. Alleen-lezen [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](../ibaseportionformat/get_normaliseheight/)() | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Er wordt geen overerving toegepast. Zie [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](../ibaseportionformat/get_proofdisabled/)() | Bepaalt of de tekst niet gecorrigeerd mag worden. Er wordt geen overerving toegepast. Zie [NullableBool](../nullablebool/). |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | Bepaalt of de slimme tag moet worden opgeschoond. Er wordt geen overerving toegepast. Zie **bool**. |
| virtual **float** [get_Spacing](../ibaseportionformat/get_spacing/)() | Retourneert de interkarakter-spatiëringsincrement. **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Zie **float**. |
| virtual **bool** [get_SpellCheck](../ibaseportionformat/get_spellcheck/)() | Geeft een waarde die aangeeft of spellingscontrole is ingeschakeld voor het tekstdel. Wanneer deze eigenschap false is, worden spellingscontroles voor textelementen onderdrukt. Wanneer true, is spellingscontrole toegestaan. Standaardwaarde is **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformat/get_strikethroughtype/)() | Retourneert het doorhalings-type van een tekst. Er wordt geen overerving toegepast. Zie [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformat/get_symbolfont/)() | Retourneert de symbolische lettertype-informatie. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Zie [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformat/get_textcaptype/)() | Retourneert het type tekst-hoofdlettergebruik. Er wordt geen overerving toegepast. Zie [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../ibaseportionformat/get_underlinefillformat/)() | Retourneert de onderstreeplijn [FillFormat](../fillformat/) eigenschappen. Er wordt geen overerving toegepast. Alleen-lezen [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../ibaseportionformat/get_underlinelineformat/)() | Retourneert de [LineFormat](../lineformat/) eigenschappen die worden gebruikt om de onderstreeplijn te omcirkelen. Er wordt geen overerving toegepast. Alleen-lezen [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() | Haalt de effectieve opmaakgegevens van het gedeelte op met de overerving toegepast. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hash-generatie van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets echt, initialiseert enkel een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijdingsoperator. Kopieert niets echt, initialiseert enkel een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_AlternativeLanguageId](../ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | Stelt de Id in van een alternatieve taal. Schrijf [System::String](../../system/string/). |
| virtual void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) | Stelt de bladwijzer-identificatie in. Schrijf [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](../ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Stelt de complexe script-lettertype-informatie in. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Schrijf [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](../ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Stelt de Oost-Azatische lettertype-informatie in. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Schrijf [IFontData](../ifontdata/). |
| virtual void [set_Escapement](../ibaseportionformat/set_escapement/)(**float**) | Stelt de superscript- of subscript-tekst in. Waarde van -100% (subscript) tot 100% (superscript). **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Schrijf **float**. |
| virtual void [set_FontBold](../ibaseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) | Bepaalt of het lettertype vet is. Er wordt geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](../ibaseportionformat/set_fontheight/)(**float**) | Stelt de letterhoogte van een gedeelte in. **std::numeric_limits<float>::quiet_NaN()** betekent dat de hoogte ongedefinieerd is en moet worden geërfd van de Master. Schrijf **float**. |
| virtual void [set_FontItalic](../ibaseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) | Bepaalt of het lettertype cursief is. Er wordt geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](../ibaseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Stelt het type onderstreping van de tekst in. Er wordt geen overerving toegepast. Schrijf [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Stelt de hyperlink in voor muisklik. Schrijf [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Stelt de hyperlink in voor muis-over. Schrijf [IHyperlink](../ihyperlink/). |
| virtual void [set_IsHardUnderlineFill](../ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Bepaalt of de onderstreeptstijl eigen [FillFormat](../fillformat/) eigenschappen heeft of deze erft van de [FillFormat](../fillformat/) eigenschappen van de tekst. Schrijf [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](../ibaseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Bepaalt of de onderstreeptstijl eigen [LineFormat](../lineformat/) eigenschappen heeft of deze erft van de [LineFormat](../lineformat/) eigenschappen van de tekst. Schrijf [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](../ibaseportionformat/set_kerningminimalsize/)(**float**) | Stelt de minimale lettergrootte in waarvoor kerning moet worden ingeschakeld. **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Schrijf **float**. |
| virtual void [set_Kumimoji](../ibaseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) | Bepaalt of de cijfers de specifieke verticale tekstlay-out van oosterse talen moeten negeren. Er wordt geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](../ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | Stelt de Id in van een proefleestaal. Wordt gebruikt voor spellings- en grammaticacontrole. Schrijf [System::String](../../system/string/). |
| virtual void [set_LatinFont](../ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Stelt de Latijnse lettertype-informatie in. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Schrijf [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](../ibaseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Er wordt geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](../ibaseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) | Bepaalt of de tekst niet gecorrigeerd mag worden. Er wordt geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| virtual void [set_SmartTagClean](./set_smarttagclean/)(**bool**) | Bepaalt of de slimme tag moet worden opgeschoond. Er wordt geen overerving toegepast. Schrijf **bool**. |
| virtual void [set_Spacing](../ibaseportionformat/set_spacing/)(**float**) | Stelt de interkarakter-spatiëringsincrement in. **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en moet worden geërfd van de Master. Schrijf **float**. |
| virtual void [set_SpellCheck](../ibaseportionformat/set_spellcheck/)(**bool**) | Stelt een waarde in die aangeeft of spellingscontrole is ingeschakeld voor het tekstdel. Wanneer deze eigenschap false is, worden spellingscontroles voor textelementen onderdrukt. Wanneer true, is spellingscontrole toegestaan. Standaardwaarde is **false**. |
| virtual void [set_StrikethroughType](../ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Stelt het doorhalings-type van een tekst in. Er wordt geen overerving toegepast. Schrijf [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](../ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Stelt de symbolische lettertype-informatie in. Null betekent dat het lettertype ongedefinieerd is en moet worden geërfd van de Master. Schrijf [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](../ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Stelt het type tekst-hoofdlettergebruik in. Er wordt geen overerving toegepast. Schrijf [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'th sjabloon-argument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |
## Opmerkingen


Deze klasse wordt gebruikt om de tekstgedeelte-opmaak-eigenschappen die voor het betreffende gedeelte zijn gedefinieerd, op te halen en te manipuleren. Dit betekent dat er geen overerving wordt toegepast bij het ophalen van waarden, dus in de meeste gevallen krijg je waarden die \"ongedefinieerd\" betekenen.

Om de effectieve opmaak-parameterwaarden inclusief overerving te verkrijgen, moet je de [IPortionFormat::GetEffective](./geteffective/)-methode gebruiken, die een [IPortionFormatEffectiveData](../iportionformateffectivedata/)-instantie retourneert.
## Zie ook

* Klasse [IBasePortionFormat](../ibaseportionformat/)
* Klasse [IHyperlinkContainer](../ihyperlinkcontainer/)
* Naamruimte [Aspose::Slides](../)
* Library [Aspose.Slides](../../)