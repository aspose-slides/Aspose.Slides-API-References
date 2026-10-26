---
title: IBasePortionFormat
second_title: Aspose.Slides för C++ API-referens
description: Denna klass innehåller format-egenskaperna för textdelar. Till skillnad från IPortionFormatEffectiveData är alla egenskaper i denna klass skrivbara.
type: docs
weight: 1457
url: /sv/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat klass


Denna klass innehåller formatinställningarna för textdelar. Till skillnad från [IPortionFormatEffectiveData](../iportionformateffectivedata/) är alla egenskaper i denna klass skrivbara.

```cpp
class IBasePortionFormat : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypsobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual [System::String](../../system/string/) [get_AlternativeLanguageId](./get_alternativelanguageid/)() | Returnerar Id-t för ett alternativt språk. Läs [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_ComplexScriptFont](./get_complexscriptfont/)() | Returnerar information om teckensnitt för komplexa skript. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_EastAsianFont](./get_eastasianfont/)() | Returnerar information om östasiatiskt teckensnitt. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | Returnerar textens [EffectFormat](../effectformat/)-egenskaper. Ingen ärvning tillämpas. Skrivskyddad [IEffectFormat](../ieffectformat/). |
| virtual **float** [get_Escapement](./get_escapement/)() | Returnerar upphöjd eller nedsänkt text. Värde från -100 % (nedsänkt) till 100 % (upphöjd). **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och bör ärvas från Master. Läs **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | Returnerar textens [FillFormat](../fillformat/)-egenskaper. Ingen ärvning tillämpas. Skrivskyddad [IFillFormat](../ifillformat/). |
| virtual [NullableBool](../nullablebool/) [get_FontBold](./get_fontbold/)() | Avgör om teckensnittet är fetstil. Ingen ärvning tillämpas. Läs [NullableBool](../nullablebool/). |
| virtual **float** [get_FontHeight](./get_fontheight/)() | Returnerar teckensnittshöjden för en del. **std::numeric_limits<float>::quiet_NaN()** betyder att höjden är odefinierad och bör ärvas från Master. Läs **float**. |
| virtual [NullableBool](../nullablebool/) [get_FontItalic](./get_fontitalic/)() | Avgör om teckensnittet är kursivt. Ingen ärvning tillämpas. Läs [NullableBool](../nullablebool/). |
| virtual [TextUnderlineType](../textunderlinetype/) [get_FontUnderline](./get_fontunderline/)() | Returnerar textens understrykningstyp. Ingen ärvning tillämpas. Läs [TextUnderlineType](../textunderlinetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_HighlightColor](./get_highlightcolor/)() | Returnerar färgen som används för att markera text. Ingen ärvning tillämpas. Skrivskyddad [IColorFormat](../icolorformat/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineFill](./get_ishardunderlinefill/)() | Avgör om understrykningsstilen har egna [FillFormat](../fillformat/)-egenskaper eller ärver dem från textens [FillFormat](../fillformat/)-egenskaper. Läs [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsHardUnderlineLine](./get_ishardunderlineline/)() | Avgör om understrykningsstilen har egna [LineFormat](../lineformat/)-egenskaper eller ärver dem från textens [LineFormat](../lineformat/)-egenskaper. Läs [NullableBool](../nullablebool/). |
| virtual **float** [get_KerningMinimalSize](./get_kerningminimalsize/)() | Returnerar minimal teckensnittsstorlek för vilken kerning bör slås på. **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och bör ärvas från Master. Läs **float**. |
| virtual [NullableBool](../nullablebool/) [get_Kumimoji](./get_kumimoji/)() | Avgör om siffrorna ska ignorera specifik vertikal textlayout för östliga språk. Ingen ärvning tillämpas. Läs [NullableBool](../nullablebool/). |
| virtual [System::String](../../system/string/) [get_LanguageId](./get_languageid/)() | Returnerar Id-t för ett korrekturspråk. Används för stavnings- och grammatikkontroll. Läs [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_LatinFont](./get_latinfont/)() | Returnerar information om latinskt teckensnitt. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs [IFontData](../ifontdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | Returnerar [LineFormat](../lineformat/)-egenskaper för textomrissning. Ingen ärvning tillämpas. Skrivskyddad [ILineFormat](../ilineformat/). |
| virtual [NullableBool](../nullablebool/) [get_NormaliseHeight](./get_normaliseheight/)() | Avgör om textens höjd ska normaliseras. Ingen ärvning tillämpas. Läs [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_ProofDisabled](./get_proofdisabled/)() | Avgör om texten inte ska korrekturläsas. Ingen ärvning tillämpas. Läs [NullableBool](../nullablebool/). |
| virtual **float** [get_Spacing](./get_spacing/)() | Returnerar ökningen av teckenavstånd. **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och bör ärvas från Master. Läs **float**. |
| virtual **bool** [get_SpellCheck](./get_spellcheck/)() | Hämtar ett värde som indikerar om stavningskontroll är aktiverad för textdelen. När denna egenskap är satt till false undertrycks stavningskontroller för textelement. När den är satt till true tillåts stavningskontroll. Standardvärdet är **false**. |
| virtual [TextStrikethroughType](../textstrikethroughtype/) [get_StrikethroughType](./get_strikethroughtype/)() | Returnerar genomstrykningstypen för en text. Ingen ärvning tillämpas. Läs [TextStrikethroughType](../textstrikethroughtype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_SymbolFont](./get_symbolfont/)() | Returnerar symbolisk teckensnittsinformation. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Läs [IFontData](../ifontdata/). |
| virtual [Aspose::Slides::TextCapType](../textcaptype/) [get_TextCapType](./get_textcaptype/)() | Returnerar typen av textkapitalisering. Ingen ärvning tillämpas. Läs [Slides::TextCapType](../textcaptype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_UnderlineFillFormat](./get_underlinefillformat/)() | Returnerar understrykninglinjens [FillFormat](../fillformat/)-egenskaper. Ingen ärvning tillämpas. Skrivskyddad [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_UnderlineLineFormat](./get_underlinelineformat/)() | Returnerar [LineFormat](../lineformat/)-egenskaper som används för att omrissa understrykninglinjen. Ingen ärvning tillämpas. Skrivskyddad [ILineFormat](../ilineformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-statement. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referens för värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_AlternativeLanguageId](./set_alternativelanguageid/)([System::String](../../system/string/)) | Sätter Id-t för ett alternativt språk. Skriv [System::String](../../system/string/). |
| virtual void [set_ComplexScriptFont](./set_complexscriptfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Sätter information om teckensnitt för komplexa skript. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Skriv [IFontData](../ifontdata/). |
| virtual void [set_EastAsianFont](./set_eastasianfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Sätter information om östasiatiskt teckensnitt. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Skriv [IFontData](../ifontdata/). |
| virtual void [set_Escapement](./set_escapement/)(**float**) | Sätter upphöjd eller nedsänkt text. Värde från -100 % (nedsänkt) till 100 % (upphöjd). **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och bör ärvas från Master. Skriv **float**. |
| virtual void [set_FontBold](./set_fontbold/)([NullableBool](../nullablebool/)) | Bestämmer om teckensnittet är fetstil. Ingen ärvning tillämpas. Skriv [NullableBool](../nullablebool/). |
| virtual void [set_FontHeight](./set_fontheight/)(**float**) | Sätter teckensnittshöjden för en del. **std::numeric_limits<float>::quiet_NaN()** betyder att höjden är odefinierad och bör ärvas från Master. Skriv **float**. |
| virtual void [set_FontItalic](./set_fontitalic/)([NullableBool](../nullablebool/)) | Bestämmer om teckensnittet är kursivt. Ingen ärvning tillämpas. Skriv [NullableBool](../nullablebool/). |
| virtual void [set_FontUnderline](./set_fontunderline/)([TextUnderlineType](../textunderlinetype/)) | Sätter textens understrykningstyp. Ingen ärvning tillämpas. Skriv [TextUnderlineType](../textunderlinetype/). |
| virtual void [set_IsHardUnderlineFill](./set_ishardunderlinefill/)([NullableBool](../nullablebool/)) | Bestämmer om understrykningsstilen har egna [FillFormat](../fillformat/)-egenskaper eller ärver dem från textens [FillFormat](../fillformat/)-egenskaper. Skriv [NullableBool](../nullablebool/). |
| virtual void [set_IsHardUnderlineLine](./set_ishardunderlineline/)([NullableBool](../nullablebool/)) | Bestämmer om understrykningsstilen har egna [LineFormat](../lineformat/)-egenskaper eller ärver dem från textens [LineFormat](../lineformat/)-egenskaper. Skriv [NullableBool](../nullablebool/). |
| virtual void [set_KerningMinimalSize](./set_kerningminimalsize/)(**float**) | Sätter minimal teckensnittsstorlek för vilken kerning bör slås på. **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och bör ärvas från Master. Skriv **float**. |
| virtual void [set_Kumimoji](./set_kumimoji/)([NullableBool](../nullablebool/)) | Avgör om siffrorna ska ignorera specifik vertikal textlayout för östliga språk. Ingen ärvning tillämpas. Skriv [NullableBool](../nullablebool/). |
| virtual void [set_LanguageId](./set_languageid/)([System::String](../../system/string/)) | Sätter Id-t för ett korrekturspråk. Används för stavnings- och grammatikkontroll. Skriv [System::String](../../system/string/). |
| virtual void [set_LatinFont](./set_latinfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Sätter information om latinskt teckensnitt. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Skriv [IFontData](../ifontdata/). |
| virtual void [set_NormaliseHeight](./set_normaliseheight/)([NullableBool](../nullablebool/)) | Avgör om textens höjd ska normaliseras. Ingen ärvning tillämpas. Skriv [NullableBool](../nullablebool/). |
| virtual void [set_ProofDisabled](./set_proofdisabled/)([NullableBool](../nullablebool/)) | Avgör om texten inte ska korrekturläsas. Ingen ärvning tillämpas. Skriv [NullableBool](../nullablebool/). |
| virtual void [set_Spacing](./set_spacing/)(**float**) | Sätter ökningen av teckenavstånd. **std::numeric_limits<float>::quiet_NaN()** betyder att värdet är odefinierat och bör ärvas från Master. Skriv **float**. |
| virtual void [set_SpellCheck](./set_spellcheck/)(**bool**) | Sätter ett värde som indikerar om stavningskontroll är aktiverad för textdelen. När denna egenskap är satt till false undertrycks stavningskontroller för textelement. När den är satt till true tillåts stavningskontroll. Standardvärdet är **false**. |
| virtual void [set_StrikethroughType](./set_strikethroughtype/)([TextStrikethroughType](../textstrikethroughtype/)) | Sätter genomstrykningstypen för en text. Ingen ärvning tillämpas. Skriv [TextStrikethroughType](../textstrikethroughtype/). |
| virtual void [set_SymbolFont](./set_symbolfont/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Sätter symbolisk teckensnittsinformation. Null betyder att teckensnittet är odefinierat och bör ärvas från Master. Skriv [IFontData](../ifontdata/). |
| virtual void [set_TextCapType](./set_textcaptype/)([Aspose::Slides::TextCapType](../textcaptype/)) | Sätter typen av textkapitalisering. Ingen ärvning tillämpas. Skriv [Slides::TextCapType](../textcaptype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsningens upplåsning enligt C# lock()-statement. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Anmärkningar


Denna klass används för att hämta och manipulera formatinställningar för textdelar som definierats för den specifika delen. Detta innebär att ingen ärvning tillämpas vid hämtning av värden, så i de flesta fall får du värden som betyder "odefinierad".

För att få de effektiva formateringsparametervärdena, inklusive ärvda, måste du använda [IPortionFormat::GetEffective](../iportionformat/geteffective/)-metoden som returnerar en [IPortionFormatEffectiveData](../iportionformateffectivedata/)-instans.

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)