---
title: BasePortionFormat
second_title: Aspose.Slides för C++ API-referens
description: Vanliga formateringsegenskaper för textdelar.
type: docs
weight: 144
url: /sv/aspose.slides/baseportionformat/
---
## BasePortionFormat klass

Vanliga formateringsegenskaper för textdelar.

```cpp
class BasePortionFormat : public Aspose::Slides::PVIObject,
                          public virtual Aspose::Slides::IBasePortionFormat
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Jämför med specificerat objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden betraktas som lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden betraktas som lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() override | Returnerar Id för ett alternativt språk. Läs [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() override | Returnerar teckensnittsinformation för komplexa skript. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Läs [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() override | Returnerar teckensnittsinformation för östasiatiskt teckensnitt. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Läs [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | Returnerar textens [EffectFormat](../effectformat/)-egenskaper. Ingen ärvning tillämpas. Endast läsning [IEffectFormat](../ieffectformat/). |
| **float** [get_Escapement](./get_escapement/)() override | Returnerar upphöjd eller nedsänkt text. Värde från -100 % (nedsänkt) till 100 % (upphöjd). **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och ska ärvas från Master. Läs **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | Returnerar textens [FillFormat](../fillformat/)-egenskaper. Ingen ärvning tillämpas. Endast läsning [IFillFormat](../ifillformat/). |
| [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() override | Avgör om teckensnittet är fetstil. Ingen ärvning tillämpas. Läs [NullableBool](../nullablebool/). |
| **float** [get_FontHeight](./get_fontheight/)() override | Returnerar teckensnittshöjden för en del. **std::numeric_limits<float>::quiet_NaN()** betyder att höjden är odefinierad och ska ärvas från Master. Läs **float**. |
| [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() override | Avgör om teckensnittet är kursivt. Ingen ärvning tillämpas. Läs [NullableBool](../nullablebool/). |
| [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() override | Returnerar textens understrykningstyp. Ingen ärvning tillämpas. Läs [TextUnderlineType](../textunderlinetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() override | Returnerar färgen som används för att markera text. Ingen ärvning tillämpas. Endast läsning [IColorFormat](../icolorformat/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() override | Avgör om understrykningstilen har egna [FillFormat](../fillformat/)-egenskaper eller ärver dem från [FillFormat](../fillformat/)-egenskaperna för texten. Läs [NullableBool](../nullablebool/). |
| [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() override | Avgör om understrykningstilen har egna [LineFormat](../lineformat/)-egenskaper eller ärver dem från [LineFormat](../lineformat/)-egenskaperna för texten. Läs [NullableBool](../nullablebool/). |
| **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() override | Returnerar minsta teckensnittsstorlek för vilken kerning ska slås på. **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och ska ärvas från Master. Läs **float**. |
| [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() override | Avgör om siffror ska ignorera den östasiatiska språksspecifika vertikala textlayouten. Ingen ärvning tillämpas. Läs [NullableBool](../nullablebool/). |
| [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() override | Returnerar Id för ett korrekturläsningsspråk. Används för stavnings- och grammatikkontroll. Läs [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() override | Returnerar latinskt teckensnittsinformation. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Läs [IFontData](../ifontdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | Returnerar [LineFormat](../lineformat/)-egenskaperna för textkonturering. Ingen ärvning tillämpas. Endast läsning [ILineFormat](../ilineformat/). |
| [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() override | Avgör om textens höjd ska normaliseras. Ingen ärvning tillämpas. Läs [NullableBool](../nullablebool/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Returnerar Parent_Immediate-objekt. Endast läsning [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Returnerar föräldra-[IPresentationComponent](../ipresentationcomponent/). Endast läsning [IPresentationComponent](../ipresentationcomponent/). |
| [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() override | Avgör om texten inte ska korrekturläsas. Ingen ärvning tillämpas. Läs [NullableBool](../nullablebool/). |
| **float** [get_Spacing](./get_spacing/)() override | Returnerar avståndsökning mellan tecken. **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och ska ärvas från Master. Läs **float**. |
| **bool** [get_SpellCheck](./get_spellcheck/)() override | Hämtar ett värde som indikerar om stavningskontroll är aktiverad för textdelen. När egenskapen är falsk undertrycks stavningskontroller för textelement. När den är sann tillåts stavningskontroll. Standardvärdet är **false**. |
| [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() override | Returnerar genomstrykningstyp för text. Ingen ärvning tillämpas. Läs [TextStrikethroughType](../textstrikethroughtype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() override | Returnerar symboliska teckensnittsinformation. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Läs [IFontData](../ifontdata/). |
| [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() override | Returnerar typen av textkapitalisering. Ingen ärvning tillämpas. Läs [Slides::TextCapType](../textcaptype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() override | Returnerar understrykninglinjens [FillFormat](../fillformat/)-egenskaper. Ingen ärvning tillämpas. Endast läsning [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() override | Returnerar [LineFormat](../lineformat/)-egenskaperna som används för att konturera understrykninglinjen. Ingen ärvning tillämpas. Endast läsning [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknardatstruktur som är associerad med objektet. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Returnerar hashkod. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analogi till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analogi till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogi till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Aktiverar kloning av anpassade typer. |
| [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt med referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) override | Ställer in Id för ett alternativt språk. Skriv [System::String](../../system/string/). |
| void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Ställer in teckensnittsinformation för komplexa skript. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Skriv [IFontData](../ifontdata/). |
| void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Ställer in teckensnittsinformation för östasiatiskt teckensnitt. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Skriv [IFontData](../ifontdata/). |
| void [set_Escapement](./set_escapement/)(**float**) override | Ställer in upphöjd eller nedsänkt text. Värde från -100 % (nedsänkt) till 100 % (upphöjd). **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och ska ärvas från Master. Skriv **float**. |
| void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) override | Avgör om teckensnittet är fetstil. Ingen ärvning tillämpas. Skriv [NullableBool](../nullablebool/). |
| void [set_FontHeight](./set_fontheight/)(**float**) override | Ställer in teckensnittshöjden för en del. **std::numeric_limits<float>::quiet_NaN()** betyder att höjden är odefinierad och ska ärvas från Master. Skriv **float**. |
| void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) override | Avgör om teckensnittet är kursivt. Ingen ärvning tillämpas. Skriv [NullableBool](../nullablebool/). |
| void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) override | Ställer in textens understryknings typ. Ingen ärvning tillämpas. Skriv [TextUnderlineType](../textunderlinetype/). |
| void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) override | Avgör om understrykningsstilen har egna [FillFormat](../fillformat/)-egenskaper eller ärver dem från [FillFormat](../fillformat/)-egenskaperna för texten. Skriv [NullableBool](../nullablebool/). |
| void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) override | Avgör om understrykningsstilen har egna [LineFormat](../lineformat/)-egenskaper eller ärver dem från [LineFormat](../lineformat/)-egenskaperna för texten. Skriv [NullableBool](../nullablebool/). |
| void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) override | Ställer in minsta teckensnittsstorlek för vilken kerning ska slås på. **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och ska ärvas från Master. Skriv **float**. |
| void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) override | Avgör om siffror ska ignorera den östasiatiska språksspecifika vertikala textlayouten. Ingen ärvning tillämpas. Skriv [NullableBool](../nullablebool/). |
| void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) override | Ställer in Id för ett korrekturläsningsspråk. Används för stavnings- och grammatikkontroll. Skriv [System::String](../../system/string/). |
| void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Ställer in latinskt teckensnittsinformation. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Skriv [IFontData](../ifontdata/). |
| void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) override | Avgör om textens höjd ska normaliseras. Ingen ärvning tillämpas. Skriv [NullableBool](../nullablebool/). |
| void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) override | Avgör om texten inte ska korrekturläsas. Ingen ärvning tillämpas. Skriv [NullableBool](../nullablebool/). |
| void [set_Spacing](./set_spacing/)(**float**) override | Ställer in avståndsökning mellan tecken. **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och ska ärvas från Master. Skriv **float**. |
| void [set_SpellCheck](./set_spellcheck/)(**bool**) override | Ställer in ett värde som indikerar om stavningskontroll är aktiverad för textdelen. När egenskapen är falsk undertrycks stavningskontroller för textelement. När den är sann tillåts stavningskontroll. Standardvärdet är **false**. |
| void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) override | Ställer in genomstrykningstyp för en text. Ingen ärvning tillämpas. Skriv [TextStrikethroughType](../textstrikethroughtype/). |
| void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) override | Ställer in symbolisk teckensnittsinformation. Null betyder att teckensnittet är odefinierat och ska ärvas från Master. Skriv [IFontData](../ifontdata/). |
| void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) override | Ställer in typen av textkapitalisering. Ingen ärvning tillämpas. Skriv [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställ in n:te mallargumentet som en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogi till C# [Object.ToString()](../../system/object/tostring/)-metod. Aktiverar konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Klass [PVIObject](../pviobject/)
* Klass [IBasePortionFormat](../ibaseportionformat/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)