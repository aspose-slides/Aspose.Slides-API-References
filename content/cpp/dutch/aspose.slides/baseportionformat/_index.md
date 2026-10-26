---
title: BasePortionFormat
second_title: Aspose.Slides voor C++ API-referentie
description: Algemene opmaak eigenschappen voor tekstdelen.
type: docs
weight: 144
url: /nl/aspose.slides/baseportionformat/
---
## BasePortionFormat klasse


Common text portion formatting properties.

```cpp
class BasePortionFormat : public Aspose::Slides::PVIObject,
                          public virtual Aspose::Slides::IBasePortionFormat
```

## Methoden

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Vergelijkt met het opgegeven object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl floating-point vergelijking waarbij twee NaN’s als gelijk worden beschouwd, zelfs hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl floating-point vergelijking waarbij twee NaN’s als gelijk worden beschouwd, zelfs hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() override | Retourneert de Id van een alternatieve taal. Lees [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() override | Retourneert de complexe script-lettertype-info. Null betekent dat het lettertype niet is gedefinieerd en geërfd moet worden van de Master. Lees [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() override | Retourneert de Oost-Aziatische lettertype-info. Null betekent dat het lettertype niet is gedefinieerd en geërfd moet worden van de Master. Lees [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | Retourneert de tekst [EffectFormat](../effectformat/) eigenschappen. Geen overerving toegepast. Alleen-lezen [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](./get_escapement/)() override | Retourneert de superscript- of subscript-tekst. Waarde van -100% (subscript) tot 100% (superscript). **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en geërfd moet worden van de Master. Lees **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Retourneert de tekst [FillFormat](../fillformat/) eigenschappen. Geen overerving toegepast. Alleen-lezen [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() override | Bepaalt of het lettertype vet is. Geen overerving toegepast. Lees [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](./get_fontheight/)() override | Retourneert de letterhoogte van een gedeelte. **std::numeric_limits<float>::quiet_NaN()** betekent dat de hoogte ongedefinieerd is en geërfd moet worden van de Master. Lees **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() override | Bepaalt of het lettertype cursief is. Geen overerving toegepast. Lees [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() override | Retourneert het onderlijntype van de tekst. Geen overerving toegepast. Lees [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() override | Retourneert de kleur die wordt gebruikt om tekst te markeren. Geen overerving toegepast. Alleen-lezen [IColorFormat](../icolorformat/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() override | Bepaalt of de onderstrekstijl eigen [FillFormat](../fillformat/) eigenschappen heeft of deze erft van de [FillFormat](../fillformat/) eigenschappen van de tekst. Lees [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() override | Bepaalt of de onderstrekstijl eigen [LineFormat](../lineformat/) eigenschappen heeft of deze erft van de [LineFormat](../lineformat/) eigenschappen van de tekst. Lees [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() override | Retourneert de minimale lettergrootte waarvoor kerning moet worden ingeschakeld. **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en geërfd moet worden van de Master. Lees **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() override | Bepaalt of de cijfers de oosterse taal-specifieke verticale tekstlay-out moeten negeren. Geen overerving toegepast. Lees [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() override | Retourneert de Id van een proefleestaal. Wordt gebruikt voor spelling- en grammaticacontrole. Lees [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() override | Retourneert de Latijnse lettertype-info. Null betekent dat het lettertype niet is gedefinieerd en geërfd moet worden van de Master. Lees [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | Retourneert de [LineFormat](../lineformat/) eigenschappen voor tekstomlijning. Geen overerving toegepast. Alleen-lezen [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() override | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Geen overerving toegepast. Lees [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Retourneert Parent_Immediate object. Alleen-lezen [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Retourneert ouder [IPresentationComponent](../ipresentationcomponent/). Alleen-lezen [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() override | Bepaalt of de tekst niet moet worden proeflezen. Geen overerving toegepast. Lees [NullableBool](../nullablebool/). |
| **float** [get_Spacing](./get_spacing/)() override | Retourneert de interkarakter-spatiëringsincrement. **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en geërfd moet worden van de Master. Lees **float**. |
| **bool** [get_SpellCheck](./get_spellcheck/)() override | Krijgt een waarde die aangeeft of spellingcontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap false is, worden spellingcontroles voor tekstelementen onderdrukt. Wanneer true, is spellingcontrole toegestaan. Standaardwaarde is **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() override | Retourneert het doorhaltype van een tekst. Geen overerving toegepast. Lees [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() override | Retourneert de symbolische lettertype-info. Null betekent dat het lettertype niet is gedefinieerd en geërfd moet worden van de Master. Lees [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() override | Retourneert het type hoofdlettergebruik van de tekst. Geen overerving toegepast. Lees [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() override | Retourneert de onderlijning-lijn [FillFormat](../fillformat/) eigenschappen. Geen overerving toegepast. Alleen-lezen [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() override | Retourneert de [LineFormat](../lineformat/) eigenschappen die worden gebruikt om de onderlijning-lijn te omlijnen. Geen overerving toegepast. Alleen-lezen [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Krijgt de referentieteller-datastructuur die aan het object is gekoppeld. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Retourneert hashcode. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Krijgt het werkelijke type van het object. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) oproep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) wachtobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt kopie-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referentie-vergelijkt waarde-type object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) override | Stelt de Id van een alternatieve taal in. Schrijf [System::String](../../system/string/). |
| void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Stelt de complexe script-lettertype-info in. Null betekent dat het lettertype niet is gedefinieerd en geërfd moet worden van de Master. Schrijf [IFontData](../ifontdata/). |
| void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Stelt de Oost-Aziatische lettertype-info in. Null betekent dat het lettertype niet is gedefinieerd en geërfd moet worden van de Master. Schrijf [IFontData](../ifontdata/). |
| void [set_Escapement](./set_escapement/)(**float**) override | Stelt de superscript- of subscript-tekst in. Waarde van -100% (subscript) tot 100% (superscript). **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en geërfd moet worden van de Master. Schrijf **float**. |
| void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) override | Bepaalt of het lettertype vet is. Geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| void [set_FontHeight](./set_fontheight/)(**float**) override | Stelt de letterhoogte van een gedeelte in. **std::numeric_limits<float>::quiet_NaN()** betekent dat de hoogte ongedefinieerd is en geërfd moet worden van de Master. Schrijf **float**. |
| void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) override | Bepaalt of het lettertype cursief is. Geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Stelt het onderlijntype van de tekst in. Geen overerving toegepast. Schrijf [TextUnderlineType](../textunderlinetype/). |
| void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Bepaalt of de onderstrekstijl eigen [FillFormat](../fillformat/) eigenschappen heeft of deze erft van de [FillFormat](../fillformat/) eigenschappen van de tekst. Schrijf [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Bepaalt of de onderstrekstijl eigen [LineFormat](../lineformat/) eigenschappen heeft of deze erft van de [LineFormat](../lineformat/) eigenschappen van de tekst. Schrijf [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) override | Stelt de minimale lettergrootte in waarvoor kerning moet worden ingeschakeld. **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en geërfd moet worden van de Master. Schrijf **float**. |
| void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) override | Bepaalt of de cijfers de oosterse taal-specifieke verticale tekstlay-out moeten negeren. Geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) override | Stelt de Id van een proefleestaal in. Wordt gebruikt voor spelling- en grammaticacontrole. Schrijf [System::String](../../system/string/). |
| void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Stelt de Latijnse lettertype-info in. Null betekent dat het lettertype niet is gedefinieerd en geërfd moet worden van de Master. Schrijf [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) override | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) override | Bepaalt of de tekst niet moet worden proeflezen. Geen overerving toegepast. Schrijf [NullableBool](../nullablebool/). |
| void [set_Spacing](./set_spacing/)(**float**) override | Stelt de interkarakter-spatiëringsincrement in. **std::numeric_limits<float>::quiet_NaN()** betekent dat de waarde ongedefinieerd is en geërfd moet worden van de Master. Schrijf **float**. |
| void [set_SpellCheck](./set_spellcheck/)(**bool**) override | Stelt een waarde in die aangeeft of spellingcontrole is ingeschakeld voor het tekstgedeelte. Wanneer deze eigenschap false is, worden spellingcontroles voor tekstelementen onderdrukt. Wanneer true, is spellingcontrole toegestaan. Standaardwaarde is **false**. |
| void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Stelt het doorhaltype van een tekst in. Geen overerving toegepast. Schrijf [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Stelt de symbolische lettertype-info in. Null betekent dat het lettertype niet is gedefinieerd en geërfd moet worden van de Master. Schrijf [IFontData](../ifontdata/). |
| void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Stelt het type hoofdlettergebruik van de tekst in. Geen overerving toegepast. Schrijf [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de template-argument in als een zwakke pointer (in plaats van gedeeld). Stelt toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Krijgt de huidige waarde van de gedeelde referentieteller. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) wachtobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |
## Zie ook

* Klasse [PVIObject](../pviobject/)
* Klasse [IBasePortionFormat](../ibaseportionformat/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)