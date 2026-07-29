---
title: PortionFormat
second_title: Aspose.Slides för C++ API-referens
description: Den här klassen innehåller formateringsegenskaper för textdelar. Till skillnad från IPortionFormatEffectiveData är alla egenskaper i den här klassen skrivbara.
type: docs
weight: 4811
url: /sv/aspose.slides/portionformat/
---
## PortionFormat klass


Denna klass innehåller formateringsegenskaper för textdelar. Till skillnad från [IPortionFormatEffectiveData](../iportionformateffectivedata/) är alla egenskaper i denna klass skrivbara.

```cpp
class PortionFormat : public Aspose::Slides::BasePortionFormat,
                      public Aspose::Slides::IPortionFormat
```

## Metoder

| Method | Description |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Jämför med angivet objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt på C#-sätt. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Efterliknar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Efterliknar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om IEC 60559:1989 säger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](../baseportionformat/get_alternativelanguageid/)() override | Returnerar Id för ett alternativt språk. Läs [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() override | Returnerar bokmärkesidentifierare. Läs [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../baseportionformat/get_complexscriptfont/)() override | Returnerar teckensnittsinformation för komplexa skript. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Läs [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../baseportionformat/get_eastasianfont/)() override | Returnerar teckensnittsinformation för östasiatiskt språk. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Läs [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../baseportionformat/get_effectformat/)() override | Returnerar textens [EffectFormat](../effectformat/)-egenskaper. Ingen arvning tillämpas. Skrivskyddad [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](../baseportionformat/get_escapement/)() override | Returnerar upphöjd eller nedsänkt text. Värde från -100 % (nedsänkt) till 100 % (upphöjd). **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och ska ärvas från Master. Läs **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../baseportionformat/get_fillformat/)() override | Returnerar textens [FillFormat](../fillformat/)-egenskaper. Ingen arvning tillämpas. Skrivskyddad [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](../baseportionformat/get_fontbold/)() override | Avgör om teckensnittet är fetstil. Ingen arvning tillämpas. Läs [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](../baseportionformat/get_fontheight/)() override | Returnerar teckensnittshöjden för en del. **std::numeric_limits<float>::quiet_NaN()** betyder att höjden är odefinierad och ska ärvas från Master. Läs **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](../baseportionformat/get_fontitalic/)() override | Avgör om teckensnittet är kursivt. Ingen arvning tillämpas. Läs [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../baseportionformat/get_fontunderline/)() override | Returnerar textens understryckningstyp. Ingen arvning tillämpas. Läs [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../baseportionformat/get_highlightcolor/)() override | Returnerar färgen som används för att markera text. Ingen arvning tillämpas. Skrivskyddad [IColorFormat](../icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | Returnerar hyperlänken som definierats för musklick. Läs [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | Hanterare för hyperlänkar. Skrivskyddad [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | Returnerar hyperlänken som definierats för musöver. Läs [IHyperlink](../ihyperlink/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../baseportionformat/get_ishardunderlinefill/)() override | Avgör om understrykningsstilen har egna [FillFormat](../fillformat/)-egenskaper eller ärver dem från [FillFormat](../fillformat/)-egenskaperna i texten. Läs [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../baseportionformat/get_ishardunderlineline/)() override | Avgör om understrykningsstilen har egna [LineFormat](../lineformat/)-egenskaper eller ärver dem från [LineFormat](../lineformat/)-egenskaperna i texten. Läs [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](../baseportionformat/get_kerningminimalsize/)() override | Returnerar minimal teckensnittsstorlek för vilken kerning ska slås på. **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och ska ärvas från Master. Läs **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](../baseportionformat/get_kumimoji/)() override | Avgör om siffror ska ignorera vertikal textlayout för östasiatiskt språk. Ingen arvning tillämpas. Läs [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](../baseportionformat/get_languageid/)() override | Returnerar Id för ett korrekturläsningsspråk. Används för stavnings- och grammatikkontroll. Läs [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../baseportionformat/get_latinfont/)() override | Returnerar information om latinskt teckensnitt. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Läs [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../baseportionformat/get_lineformat/)() override | Returnerar [LineFormat](../lineformat/)-egenskaper för textkonturering. Ingen arvning tillämpas. Skrivskyddad [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](../baseportionformat/get_normaliseheight/)() override | Avgör om textens höjd ska normaliseras. Ingen arvning tillämpas. Läs [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Returnerar Parent_Immediate-objektet. Skrivskyddad [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Returnerar förälder [IPresentationComponent](../ipresentationcomponent/). Skrivskyddad [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](../baseportionformat/get_proofdisabled/)() override | Avgör om texten inte ska korrekturläsas. Ingen arvning tillämpas. Läs [NullableBool](../nullablebool/). |
| **bool** [get_SmartTagClean](./get_smarttagclean/)() override | Avgör om smart-taggen ska rensas. Ingen arvning tillämpas. Läs **bool**. |
| **float** [get_Spacing](../baseportionformat/get_spacing/)() override | Returnerar mellanrumstillägg mellan tecken. **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och ska ärvas från Master. Läs **float**. |
| **bool** [get_SpellCheck](../baseportionformat/get_spellcheck/)() override | Hämtar ett värde som indikerar om stavningskontroll är aktiverad för textdelen. När egenskapen är falsk undertrycks stavningskontroller för textelement. När den är sann tillåts stavningskontroll. Standardvärdet är **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../baseportionformat/get_strikethroughtype/)() override | Returnerar genomstrykningstyp för text. Ingen arvning tillämpas. Läs [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../baseportionformat/get_symbolfont/)() override | Returnerar symbolteckensnittsinformation. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Läs [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../baseportionformat/get_textcaptype/)() override | Returnerar typ av textversalisering. Ingen arvning tillämpas. Läs [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../baseportionformat/get_underlinefillformat/)() override | Returnerar understrykningslinjens [FillFormat](../fillformat/)-egenskaper. Ingen arvning tillämpas. Skrivskyddad [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../baseportionformat/get_underlinelineformat/)() override | Returnerar [LineFormat](../lineformat/)-egenskaper som används för att konturera understrykningslinjen. Ingen arvning tillämpas. Skrivskyddad [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräkningsdatastruktur som är associerad med objektet. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() override | Hämtar effektiva formateringsdata för delen med arv tillämpat. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Returnerar hash-kod. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog med C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typ som beskrivs av targetType. Analog med C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog med C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
|  [PortionFormat](./portionformat/)() | Initierar en ny instans av klassen [PortionFormat](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt genom referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt genom referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referens av värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_AlternativeLanguageId](../baseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) override | Sätter Id för ett alternativt språk. Skriv [System::String](../../system/string/). |
| void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) override | Sätter bokmärkesidentifierare. Skriv [System::String](../../system/string/). |
| void [set_ComplexScriptFont](../baseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Sätter teckensnittsinformation för komplexa skript. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Skriv [IFontData](../ifontdata/). |
| void [set_EastAsianFont](../baseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Sätter teckensnittsinformation för östasiatiskt språk. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Skriv [IFontData](../ifontdata/). |
| void [set_Escapement](../baseportionformat/set_escapement/)(**float**) override | Sätter upphöjd eller nedsänkt text. Värde från -100 % (nedsänkt) till 100 % (upphöjd). **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och ska ärvas från Master. Skriv **float**. |
| void [set_FontBold](../baseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) override | Avgör om teckensnittet är fetstil. Ingen arvning tillämpas. Skriv [NullableBool](../nullablebool/). |
| void [set_FontHeight](../baseportionformat/set_fontheight/)(**float**) override | Sätter teckensnittshöjd för en del. **std::numeric_limits<float>::quiet_NaN()** betyder att höjden är odefinierad och ska ärvas från Master. Skriv **float**. |
| void [set_FontItalic](../baseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) override | Avgör om teckensnittet är kursivt. Ingen arvning tillämpas. Skriv [NullableBool](../nullablebool/). |
| void [set_FontUnderline](../baseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Sätter textens understryckningstyp. Ingen arvning tillämpas. Skriv [TextUnderlineType](../textunderlinetype/). |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Sätter hyperlänken som definierats för musklick. Skriv [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Sätter hyperlänken som definierats för musöver. Skriv [IHyperlink](../ihyperlink/). |
| void [set_IsHardUnderlineFill](../baseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Avgör om understrykningsstilen har egna [FillFormat](../fillformat/)-egenskaper eller ärver dem från [FillFormat](../fillformat/)-egenskaperna i texten. Skriv [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](../baseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Avgör om understrykningsstilen har egna [LineFormat](../lineformat/)-egenskaper eller ärver dem från [LineFormat](../lineformat/)-egenskaperna i texten. Skriv [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](../baseportionformat/set_kerningminimalsize/)(**float**) override | Sätter minimal teckensnittsstorlek för vilken kerning ska slås på. **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och ska ärvas från Master. Skriv **float**. |
| void [set_Kumimoji](../baseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) override | Avgör om siffror ska ignorera vertikal textlayout för östasiatiskt språk. Ingen arvning tillämpas. Skriv [NullableBool](../nullablebool/). |
| void [set_LanguageId](../baseportionformat/set_languageid/)([System::String](../../system/string/)) override | Sätter Id för ett korrekturläsningsspråk. Används för stavnings- och grammatikkontroll. Skriv [System::String](../../system/string/). |
| void [set_LatinFont](../baseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Sätter information om latinskt teckensnitt. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Skriv [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](../baseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) override | Avgör om textens höjd ska normaliseras. Ingen arvning tillämpas. Skriv [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](../baseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) override | Avgör om texten inte ska korrekturläsas. Ingen arvning tillämpas. Skriv [NullableBool](../nullablebool/). |
| void [set_SmartTagClean](./set_smarttagclean/)(**bool**) override | Avgör om smart-taggen ska rensas. Ingen arvning tillämpas. Skriv **bool**. |
| void [set_Spacing](../baseportionformat/set_spacing/)(**float**) override | Sätter mellanrumstillägg mellan tecken. **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och ska ärvas från Master. Skriv **float**. |
| void [set_SpellCheck](../baseportionformat/set_spellcheck/)(**bool**) override | Sätter ett värde som indikerar om stavningskontroll är aktiverad för textdelen. När egenskapen är falsk undertrycks stavningskontroller för textelement. När den är sann tillåts stavningskontroll. Standardvärdet är **false**. |
| void [set_StrikethroughType](../baseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Sätter genomstrykningstyp för text. Ingen arvning tillämpas. Skriv [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](../baseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Sätter symbolteckensnittsinformation. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Skriv [IFontData](../ifontdata/). |
| void [set_TextCapType](../baseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Sätter typ av textversalisering. Ingen arvning tillämpas. Skriv [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te mallargument till en svag pekare (i stället för delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog med C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning enligt C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Anmärkningar


Denna klass används för att hämta och manipulera formateringsegenskaper för textdelar som definierats för den specifika delen. Det innebär att ingen arvning tillämpas när värden hämtas, så i de flesta fall får du värden som betyder "odefinierat".

För att få de effektiva formateringsparametervärdena inklusive ärvda måste du använda [PortionFormat::GetEffective](./geteffective/)-metoden som returnerar en [IPortionFormatEffectiveData](../iportionformateffectivedata/)-instans.

Följande exempel visar hur du tilldelar det latinska teckensnittet till en [Paragraph](../paragraph/)'s del i PowerPoint [Presentation](../presentation/).
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f);

System::SharedPtr<Paragraph> paragraph = System::MakeObject<Paragraph>();
System::SharedPtr<Portion> portion = System::MakeObject<Portion>(u"Theme text format");
paragraph->get_Portions()->Add(portion);
shape->get_TextFrame()->get_Paragraphs()->Add(paragraph);
// Aspose.Slides använder dessa speciella identifierare (liknande de som används i PowerPoint):
// +mn-lt - Kroppsteckensnitt Latin (Mindre Latin-teckensnitt)
// +mj-lt - Rubriksteckensnitt Latin (Större Latin-teckensnitt)
// +mn-ea - Kroppsteckensnitt Östasiatiskt (Mindre Östasiatiskt teckensnitt)
// +mj-ea - Kroppsteckensnitt Östasiatiskt (Mindre Östasiatiskt teckensnitt)
portion->get_PortionFormat()->set_LatinFont(System::MakeObject<FontData>(u"+mn-lt"));
```

## Se också

* Klass [BasePortionFormat](../baseportionformat/)
* Klass [IPortionFormat](../iportionformat/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)