---
title: IPortionFormat
second_title: Aspose.Slides för C++ API-referens
description: Denna klass innehåller formateringsegenskaper för textavsnittet. Till skillnad från IPortionFormatEffectiveData är alla egenskaper i denna klass skrivbara.
type: docs
weight: 3329
url: /sv/aspose.slides/iportionformat/
---
## IPortionFormat klass


Denna klass innehåller textavsnittets formateringsegenskaper. Till skillnad från [IPortionFormatEffectiveData](../iportionformateffectivedata/) är alla egenskaper i denna klass skrivbara.

```cpp
class IPortionFormat : public virtual Aspose::Slides::IBasePortionFormat,
                       public Aspose::Slides::IHyperlinkContainer
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypens objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypens objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](../ibaseportionformat/get_alternativelanguageid/)() | Returnerar Id för ett alternativt språk. Läs [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_BookmarkId](./get_bookmarkid/)() | Returnerar bokmärkesidentifierare. Läs [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](../ibaseportionformat/get_complexscriptfont/)() | Returnerar information om komplex skriptfont. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](../ibaseportionformat/get_eastasianfont/)() | Returnerar information om östasiatiskt teckensnitt. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ibaseportionformat/get_effectformat/)() | Returnerar text [EffectFormat](../effectformat/) egenskaper. Ingen arv tillämpas. Skrivskyddad [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](../ibaseportionformat/get_escapement/)() | Returnerar upphöjd eller nedsänkt text. Värde från -100 % (nedsänkt) till 100 % (upphöjd). **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och bör ärvas från Master. Läs **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ibaseportionformat/get_fillformat/)() | Returnerar text [FillFormat](../fillformat/) egenskaper. Ingen arv tillämpas. Skrivskyddad [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](../ibaseportionformat/get_fontbold/)() | Bestämmer om teckensnittet är fetstil. Ingen arv tillämpas. Läs [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](../ibaseportionformat/get_fontheight/)() | Returnerar teckensnittshöjden för ett avsnitt. **std::numeric_limits<float>::quiet_NaN()** betyder att höjden är odefinierad och bör ärvas från Master. Läs **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](../ibaseportionformat/get_fontitalic/)() | Bestämmer om teckensnittet är kursivt. Ingen arv tillämpas. Läs [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](../ibaseportionformat/get_fontunderline/)() | Returnerar textunderstryknings typ. Ingen arv tillämpas. Läs [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](../ibaseportionformat/get_highlightcolor/)() | Returnerar färgen som används för att markera en text. Ingen arv tillämpas. Skrivskyddad [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Returnerar hyperlänken definierad för musklick. Läs [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlänksadministratör Skrivskyddad [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Returnerar hyperlänken definierad för musöver. Läs [IHyperlink](../ihyperlink/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](../ibaseportionformat/get_ishardunderlinefill/)() | Bestämmer om understrykningsstilen har egna [FillFormat](../fillformat/) egenskaper eller ärver dem från [FillFormat](../fillformat/) egenskaper i texten. Läs [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](../ibaseportionformat/get_ishardunderlineline/)() | Bestämmer om understrykningsstilen har egna [LineFormat](../lineformat/) egenskaper eller ärver dem från [LineFormat](../lineformat/) egenskaper i texten. Läs [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](../ibaseportionformat/get_kerningminimalsize/)() | Returnerar minimal teckensnittsstorlek för vilken kerning bör slås på. **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och bör ärvas från Master. Läs **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](../ibaseportionformat/get_kumimoji/)() | Bestämmer om siffrorna ska ignorera textens östasiatiska språk-specifika vertikala layout. Ingen arv tillämpas. Läs [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](../ibaseportionformat/get_languageid/)() | Returnerar Id för ett korrekturspråk. Används för stavnings- och grammatikkontroll. Läs [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](../ibaseportionformat/get_latinfont/)() | Returnerar latin teckensnittsinformation. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ibaseportionformat/get_lineformat/)() | Returnerar [LineFormat](../lineformat/) egenskaper för textkontur. Ingen arv tillämpas. Skrivskyddad [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](../ibaseportionformat/get_normaliseheight/)() | Bestämmer om textens höjd ska normaliseras. Ingen arv tillämpas. Läs [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](../ibaseportionformat/get_proofdisabled/)() | Bestämmer om texten inte ska korrekturläsas. Ingen arv tillämpas. Läs [NullableBool](../nullablebool/). |
| virtual **bool** [get_SmartTagClean](./get_smarttagclean/)() | Bestämmer om smart-taggen ska rensas. Ingen arv tillämpas. Läs **bool**. |
| virtual **float** [get_Spacing](../ibaseportionformat/get_spacing/)() | Returnerar interteckenavståndsökning. **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och bör ärvas från Master. Läs **float**. |
| virtual **bool** [get_SpellCheck](../ibaseportionformat/get_spellcheck/)() | Hämtar ett värde som indikerar om stavningskontroll är aktiverad för textavsnittet. När denna egenskap är satt till false undertrycks stavningskontroller för textelement. När den är satt till true tillåts stavningskontroll. Standardvärdet är **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](../ibaseportionformat/get_strikethroughtype/)() | Returnerar genomstrykningstyp för en text. Ingen arv tillämpas. Läs [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](../ibaseportionformat/get_symbolfont/)() | Returnerar symbolisk teckensnittsinformation. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](../ibaseportionformat/get_textcaptype/)() | Returnerar typ av textversalisering. Ingen arv tillämpas. Läs [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](../ibaseportionformat/get_underlinefillformat/)() | Returnerar understrykninglinje [FillFormat](../fillformat/) egenskaper. Ingen arv tillämpas. Skrivskyddad [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](../ibaseportionformat/get_underlinelineformat/)() | Returnerar [LineFormat](../lineformat/) egenskaper som används för att konturera understrykninglinje. Ingen arv tillämpas. Skrivskyddad [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormatEffectiveData](../iportionformateffectivedata/)\> [GetEffective](./geteffective/)() | Hämtar effektiv portionsformateringsdata med arv tillämpat. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/) metod. Aktiverar hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/) anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock() sats låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/) bevakningsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metod. Aktiverar kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_AlternativeLanguageId](../ibaseportionformat/set_alternativelanguageid/)([System::String](../../system/string/)) | Sätter Id för ett alternativt språk. Skriv [System::String](../../system/string/). |
| virtual void [set_BookmarkId](./set_bookmarkid/)([System::String](../../system/string/)) | Sätter bokmärkesidentifierare. Skriv [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](../ibaseportionformat/set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Sätter information om komplex skriptfont. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Skriv [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](../ibaseportionformat/set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Sätter information om östasiatiskt teckensnitt. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Skriv [IFontData](../ifontdata/). |
| virtual void [set_Escapement](../ibaseportionformat/set_escapement/)(**float**) | Sätter upphöjd eller nedsänkt text. Värde från -100 % (nedsänkt) till 100 % (upphöjd). **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och bör ärvas från Master. Skriv **float**. |
| virtual void [set_FontBold](../ibaseportionformat/set_fontbold/)([NullableBool](../nullablebool/)) | Bestämmer om teckensnittet är fetstil. Ingen arv tillämpas. Skriv [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](../ibaseportionformat/set_fontheight/)(**float**) | Sätter teckensnittshöjden för en portion. **std::numeric_limits<float>::quiet_NaN()** betyder att höjden är odefinierad och bör ärvas från Master. Skriv **float**. |
| virtual void [set_FontItalic](../ibaseportionformat/set_fontitalic/)([NullableBool](../nullablebool/)) | Bestämmer om teckensnittet är kursivt. Ingen arv tillämpas. Skriv [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](../ibaseportionformat/set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Sätter textunderstryknings typ. Ingen arv tillämpas. Skriv [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Sätter hyperlänken definierad för musklick. Skriv [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Sätter hyperlänken definierad för musöver. Skriv [IHyperlink](../ihyperlink/). |
| virtual void [set_IsHardUnderlineFill](../ibaseportionformat/set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Bestämmer om understrykningsstilen har egna [FillFormat](../fillformat/) egenskaper eller ärver dem från [FillFormat](../fillformat/) egenskaper i texten. Skriv [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](../ibaseportionformat/set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Bestämmer om understrykningsstilen har egna [LineFormat](../lineformat/) egenskaper eller ärver dem från [LineFormat](../lineformat/) egenskaper i texten. Skriv [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](../ibaseportionformat/set_kerningminimalsize/)(**float**) | Sätter minimal teckensnittsstorlek för vilken kerning bör slås på. **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och bör ärvas från Master. Skriv **float**. |
| virtual void [set_Kumimoji](../ibaseportionformat/set_kumimoji/)([NullableBool](../nullablebool/)) | Bestämmer om siffrorna ska ignorera textens östasiatiska språk-specifika vertikala layout. Ingen arv tillämpas. Skriv [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](../ibaseportionformat/set_languageid/)([System::String](../../system/string/)) | Sätter Id för ett korrekturspråk. Används för stavnings- och grammatikkontroll. Skriv [System::String](../../system/string/). |
| virtual void [set_LatinFont](../ibaseportionformat/set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Sätter latin teckensnittsinformation. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Skriv [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](../ibaseportionformat/set_normaliseheight/)([NullableBool](../nullablebool/)) | Bestämmer om textens höjd ska normaliseras. Ingen arv tillämpas. Skriv [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](../ibaseportionformat/set_proofdisabled/)([NullableBool](../nullablebool/)) | Bestämmer om texten inte ska korrekturläsas. Ingen arv tillämpas. Skriv [NullableBool](../nullablebool/). |
| virtual void [set_SmartTagClean](./set_smarttagclean/)(**bool**) | Bestämmer om smart-taggen ska rensas. Ingen arv tillämpas. Skriv **bool**. |
| virtual void [set_Spacing](../ibaseportionformat/set_spacing/)(**float**) | Sätter interteckenavståndsökning. **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och bör ärvas från Master. Skriv **float**. |
| virtual void [set_SpellCheck](../ibaseportionformat/set_spellcheck/)(**bool**) | Sätter ett värde som indikerar om stavningskontroll är aktiverad för textavsnittet. När egenskapen är satt till false undertrycks stavningskontroller för textelement. När den är satt till true tillåts stavningskontroll. Standardvärdet är **false**. |
| virtual void [set_StrikethroughType](../ibaseportionformat/set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Sätter genomstrykningstyp för en text. Ingen arv tillämpas. Skriv [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](../ibaseportionformat/set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Sätter symbolisk teckensnittsinformation. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Skriv [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](../ibaseportionformat/set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Sätter typ av textversalisering. Ingen arv tillämpas. Skriv [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i containers till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/) metod. Aktiverar konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/)) konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock() sats upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/) bevakningsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Anmärkningar

Denna klass används för att returnera och manipulera textavsnittets formateringsegenskaper som definieras för det specifika avsnittet. Detta innebär att ingen arv tillämpas vid hämtning av värden, så i de flesta fall får du värden som betyder "odefinierat".

För att få de effektiva formateringsparametervärdena inklusive ärvda måste du använda [IPortionFormat::GetEffective](./geteffective/) metoden som returnerar en [IPortionFormatEffectiveData](../iportionformateffectivedata/) instans.

## Se även

* Klass [IBasePortionFormat](../ibaseportionformat/)
* Klass [IHyperlinkContainer](../ihyperlinkcontainer/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)