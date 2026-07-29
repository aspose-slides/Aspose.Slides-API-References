---
title: IPortionFormatEffectiveData
second_title: Aspose.Slides för C++ API-referens
description: Oföränderligt objekt som innehåller effektiva formateringsegenskaper för textdelar.
type: docs
weight: 3342
url: /sv/aspose.slides/iportionformateffectivedata/
---
## IPortionFormatEffectiveData klass

Oföränderligt objekt som innehåller effektiva formateringsegenskaper för textdelar.

```cpp
class IPortionFormatEffectiveData : public virtual Aspose::Slides::IBasePortionFormatEffectiveData
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför objekt av referenstyp i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför objekt av värdetyp i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformateffectivedata/get_alternativelanguageid/)() | Returnerar Id för ett alternativt språk. Skrivskyddad [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | Returnerar bokmärkesidentifierare. Skrivskyddad [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformateffectivedata/get_complexscriptfont/)() | Returnerar information om teckensnitt för komplex skript. Skrivskyddad [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformateffectivedata/get_eastasianfont/)() | Returnerar information om teckensnitt för Östasien. Skrivskyddad [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [get_EffectFormat](../ibaseportionformateffectivedata/get_effectformat/)() | Returnerar textens [EffectFormat](../effectformat/) egenskaper. Skrivskyddad [IEffectFormatEffectiveData](../ieffectformateffectivedata/). |
| virtual **float** [get_Escapement](../ibaseportionformateffectivedata/get_escapement/)() | Returnerar upphöjd eller nedsänkt text. Värde från -100 % (nedsänkt) till 100 % (upphöjd). Skrivskyddad **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_FillFormat](../ibaseportionformateffectivedata/get_fillformat/)() | Returnerar textens [FillFormat](../fillformat/) egenskaper. Skrivskyddad [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual **bool** [get_FontBold](../ibaseportionformateffectivedata/get_fontbold/)() | Avgör om teckensnittet är fetstil. Skrivskyddad **bool**. |
| virtual **float** [get_FontHeight](../ibaseportionformateffectivedata/get_fontheight/)() | Returnerar teckensnittshöjden för textdelen, i punkt. Skrivskyddad **float**. |
| virtual **bool** [get_FontItalic](../ibaseportionformateffectivedata/get_fontitalic/)() | Avgör om teckensnittet är kursivt. Skrivskyddad **bool**. |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformateffectivedata/get_fontunderline/)() | Returnerar typen av understrykning för texten. Skrivskyddad [TextUnderlineType](../textunderlinetype/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_HighlightColor](../ibaseportionformateffectivedata/get_highlightcolor/)() | Returnerar färgen som används för att markera text. Skrivskyddad [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() | Returnerar hyperlänken definierad för musklick. Skrivskyddad [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() | Returnerar hyperlänken definierad för musövergång. Skrivskyddad [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsHardUnderlineFill](../ibaseportionformateffectivedata/get_ishardunderlinefill/)() | Avgör om understrykningstilen har egna [FillFormat](../fillformat/) egenskaper eller ärver dem från textens [FillFormat](../fillformat/) egenskaper. Skrivskyddad **bool**. |
| virtual **bool** [get_IsHardUnderlineLine](../ibaseportionformateffectivedata/get_ishardunderlineline/)() | Avgör om understrykningstilen har egna [LineFormat](../lineformat/) egenskaper eller ärver dem från textens [LineFormat](../lineformat/) egenskaper. Skrivskyddad **bool**. |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformateffectivedata/get_kerningminimalsize/)() | Returnerar minimal teckensnittsstorlek för vilken kerning ska slås på. Skrivskyddad **float**. |
| virtual **bool** [get_Kumimoji](../ibaseportionformateffectivedata/get_kumimoji/)() | Avgör om siffror ska ignorera vertikal textlayout specifik för östliga språk. Skrivskyddad **bool**. |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformateffectivedata/get_languageid/)() | Returnerar Id för ett språk. Skrivskyddad [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformateffectivedata/get_latinfont/)() | Returnerar information om latinofont. Skrivskyddad [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_LineFormat](../ibaseportionformateffectivedata/get_lineformat/)() | Returnerar [LineFormat](../lineformat/) egenskaper för textkontur. Skrivskyddad [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| virtual **bool** [get_NormaliseHeight](../ibaseportionformateffectivedata/get_normaliseheight/)() | Avgör om höjden på texten ska normaliseras. Skrivskyddad **bool**. |
| virtual **bool** [get_ProofDisabled](../ibaseportionformateffectivedata/get_proofdisabled/)() | Avgör om texten inte ska korrekturläsas. Skrivskyddad **bool**. |
| virtual **bool** [get_SmartTagClean](../ibaseportionformateffectivedata/get_smarttagclean/)() | Avgör om smart-taggen ska rensas. Skrivskyddad **bool**. |
| virtual **float** [get_Spacing](../ibaseportionformateffectivedata/get_spacing/)() | Returnerar ökningen av teckenavstånd, i punkt. Skrivskyddad **float**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformateffectivedata/get_strikethroughtype/)() | Returnerar genomstrykningstyp för en text. Skrivskyddad [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformateffectivedata/get_symbolfont/)() | Returnerar symbolteckensnittsinformation. Skrivskyddad [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformateffectivedata/get_textcaptype/)() | Returnerar typ av textversalisering. Skrivskyddad [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormatEffectiveData](../ifillformateffectivedata/)\> [get_UnderlineFillFormat](../ibaseportionformateffectivedata/get_underlinefillformat/)() | Returnerar understrykninglinjens [FillFormat](../fillformat/) egenskaper. Skrivskyddad [IFillFormatEffectiveData](../ifillformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [get_UnderlineLineFormat](../ibaseportionformateffectivedata/get_underlinelineformat/)() | Returnerar [LineFormat](../lineformat/) egenskaper som används för att konturera understrykninglinjen. Skrivskyddad [ILineFormatEffectiveData](../ilineformateffectivedata/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/) anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknaren med angivet värde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av den delade referensräknaren. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar den delade referensräknaren. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräknaren. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsningupphävning enligt C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |
## Anmärkningar

Det här gränssnittet används tillsammans med [IPortionFormat](../iportionformat/) gränssnitt för att returnera effektiva formateringsvärden med ärftlighet tillämpad. 
## Se även

* Klass [IBasePortionFormatEffectiveData](../ibaseportionformateffectivedata/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)