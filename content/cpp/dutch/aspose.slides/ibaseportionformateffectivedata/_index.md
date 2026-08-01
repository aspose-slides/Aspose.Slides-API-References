---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides voor C++ API-referentie
description: Basisinterface voor onveranderlijke objecten die effectieve opmaak-eigenschappen van tekstgedeelten bevatten.
type: docs
weight: 1470
url: /nl/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData klasse


Base interface for immutable objects which contain effective text portion formatting properties.

```cpp
class IBasePortionFormatEffectiveData : public virtual System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C# stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C# stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekomma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekomma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | Retourneert de Id van een alternatieve taal. Alleen-lezen [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | Retourneert de informatie over het complexe scriptlettertype. Alleen-lezen [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | Retourneert de informatie over het Oost-Aziatische lettertype. Alleen-lezen [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [get_EffectFormat](./get_effectformat/)() | Retourneert de tekst [EffectFormat](../effectformat/) eigenschappen. Alleen-lezen [IEffectFormatEffectiveData](../ieffectformateffectivedata/). |
| virtual **float** [get_Escapement](./get_escapement/)() | Retourneert de superscript- of subscript-tekst. Waarde van -100% (subscript) tot 100% (superscript). Alleen-lezen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_FillFormat](./get_fillformat/)() | Retourneert de tekst [FillFormat](../fillformat/) eigenschappen. Alleen-lezen [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual **bool** [get_FontBold](./get_fontbold/)() | Bepaalt of het lettertype vet is. Alleen-lezen **bool**. |
| virtual **float** [get_FontHeight](./get_fontheight/)() | Retourneert de lettergrootte van het tekstgedeelte, in punten. Alleen-lezen **float**. |
| virtual **bool** [get_FontItalic](./get_fontitalic/)() | Bepaalt of het lettertype cursief is. Alleen-lezen **bool**. |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | Retourneert het onderlijntype van de tekst. Alleen-lezen [TextUnderlineType](../textunderlinetype/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_HighlightColor](./get_highlightcolor/)() | Retourneert de kleur die wordt gebruikt om een tekst te markeren. Alleen-lezen [System::Drawing::Color](../../system.drawing/color/). |
| virtual **bool** [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | Bepaalt of de onderlijnstijl eigen [FillFormat](../fillformat/) eigenschappen heeft of deze erft van de [FillFormat](../fillformat/) eigenschappen van de tekst. Alleen-lezen **bool**. |
| virtual **bool** [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | Bepaalt of de onderlijnstijl eigen [LineFormat](../lineformat/) eigenschappen heeft of deze erft van de [LineFormat](../lineformat/) eigenschappen van de tekst. Alleen-lezen **bool**. |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | Retourneert de minimale lettergrootte waarvoor kerning ingeschakeld moet worden. Alleen-lezen **float**. |
| virtual **bool** [get_Kumimoji](./get_kumimoji/)() | Bepaalt of de cijfers de oosterse taalspecifieke verticale tekstindeling van de tekst moeten negeren. Alleen-lezen **bool**. |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | Retourneert de Id van een taal. Alleen-lezen [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | Retourneert de informatie over het Latijnse lettertype. Alleen-lezen [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_LineFormat](./get_lineformat/)() | Retourneert de [LineFormat](../lineformat/) eigenschappen voor tekstoplijn. Alleen-lezen [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| virtual **bool** [get_NormaliseHeight](./get_normaliseheight/)() | Bepaalt of de hoogte van een tekst genormaliseerd moet worden. Alleen-lezen **bool**. |
| virtual **bool** [get_ProofDisabled](./get_proofdisabled/)() | Bepaalt of de tekst niet moet worden gecontroleerd. Alleen-lezen **bool**. |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | Bepaalt of de slimme tag moet worden opgeschoond. Alleen-lezen **bool**. |
| virtual **float** [get_Spacing](./get_spacing/)() | Retourneert de interkarakter-spatiëringsincrement, in punten. Alleen-lezen **float**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | Retourneert het doorhalings-type van een tekst. Alleen-lezen [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | Retourneert de symbolische lettertype-informatie. Alleen-lezen [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | Retourneert het type hoofdlettergebruik van de tekst. Alleen-lezen [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | Retourneert de onderlijn [FillFormat](../fillformat/) eigenschappen. Alleen-lezen [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | Retourneert de [LineFormat](../lineformat/) eigenschappen die worden gebruikt om de onderlijn te omlijnen. Alleen-lezen [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentie-teller datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hash van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het feitelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) oproep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type dat door targetType wordt beschreven vertegenwoordigt. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert de C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-construeren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-construeren van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt het wisselen van pointers in containers naar zwakke modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |
## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)