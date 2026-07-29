---
title: Trendline
second_title: Aspose.Slides för C++ API-referens
description: Klassen representerar trendlinjen för diagramserie
type: docs
weight: 1366
url: /sv/aspose.slides.charts/trendline/
---
## Trendline-klass

Klassen representerar trendlinjen för diagramserie

```cpp
class Trendline : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::TrendlineCollection>>,
                  public Aspose::Slides::Charts::ITrendline
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Initierar TextFrameForOverriding med texten i parametern \"text\". Om TextFrameForOverriding redan är initierad ändras dess text helt enkelt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande jämförelse av flyttal där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande jämförelse av flyttal där två NaN-värden betraktas som lika även om NaN enligt IEC 60559:1989 inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| **double** [get_Backward](./get_backward/)() override | Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig före data för den serie som trenderas. På spridnings- och icke-spridningsdiagram ska värdet vara ett icke-negativt tal. Läs **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Returnerar det överordnade diagrammet. Skrivskyddad [IChart](../ichart/). |
| **bool** [get_DisplayEquation](./get_displayequation/)() override | Anger att ekvationen för trendlinjen visas på diagrammet (i samma etikett som Rsquaredvalue). Läs **bool**. |
| **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() override | Anger att R-kvadrerat-värdet för trendlinjen visas på diagrammet (i samma etikett som ekvationen). Läs **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Representerar formatet för trendlinjen. Läs [IFormat](../iformat/). |
| **double** [get_Forward](./get_forward/)() override | Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig efter data för den serie som trenderas. På spridnings- och icke-spridningsdiagram ska värdet vara ett icke-negativt tal. Läs **double**. |
| **double** [get_Intercept](./get_intercept/)() override | Anger värdet där trendlinjen ska korsar y-axeln. Denna egenskap stöds endast när trendlinjetypen är exp, lineär eller poly. Läs **double**. |
| **uint8_t** [get_Order](./get_order/)() override | Anger ordningen för den polynomiska trendlinjen. Ignoreras för andra trendlinjetyper. Värdet måste vara mellan 2 och 6. Läs **uint8_t**. |
| **uint8_t** [get_Period](./get_period/)() override | Anger perioden för trendlinjen för ett glidande medelvärde. Ignoreras för andra trendlinjevarianter. Värdet måste vara mellan 2 och 255. Läs **uint8_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | Representerar legendposten som är relaterad till denna trendlinje. Skrivskyddad [ILegendEntryProperties](../ilegendentryproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Returnerar textformat. Skrivskyddad [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Kan innehålla rikformaterad text. Om denna egenskap inte är null ersätter detta formaterade textvärde den automatiskt genererade texten för datalabeln. Automatgenererad text för datalabel betyder text som hanteras av egenskaperna ShowSeriesName, ShowValue, … och som formateras med TextFormatManager.TextFormat-egenskapen. Skrivskyddad [ITextFrame](../../aspose.slides/itextframe/). |
| [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() override | Hämtar namn på trendlinjen. Läs [System::String](../../system/string/). |
| [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() override | Hämtar typ av trendlinje. Läs [Charts::TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Aktiverar hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktisk typ av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn \'is\'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-sats. Anropas direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Aktiverar kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_Backward](./set_backward/)(**double**) override | Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig före data för den serie som trenderas. På spridnings- och icke-spridningsdiagram ska värdet vara ett icke-negativt tal. Skriv **double**. |
| void [set_DisplayEquation](./set_displayequation/)(**bool**) override | Anger att ekvationen för trendlinjen visas på diagrammet (i samma etikett som Rsquaredvalue). Skriv **bool**. |
| void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) override | Anger att R-kvadrerat-värdet för trendlinjen visas på diagrammet (i samma etikett som ekvationen). Skriv **bool**. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | Representerar formatet för trendlinjen. Skriv [IFormat](../iformat/). |
| void [set_Forward](./set_forward/)(**double**) override | Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig efter data för den serie som trenderas. På spridnings- och icke-spridningsdiagram ska värdet vara ett icke-negativt tal. Skriv **double**. |
| void [set_Intercept](./set_intercept/)(**double**) override | Anger värdet där trendlinjen ska korsar y-axeln. Denna egenskap stöds endast när trendlinjetypen är exp, lineär eller poly. Skriv **double**. |
| void [set_Order](./set_order/)(**uint8_t**) override | Anger ordningen för den polynomiska trendlinjen. Ignoreras för andra trendlinjetyper. Värdet måste vara mellan 2 och 6. Skriv **uint8_t**. |
| void [set_Period](./set_period/)(**uint8_t**) override | Anger perioden för trendlinjen för ett glidande medelvärde. Ignoreras för andra trendlinjevarianter. Värdet måste vara mellan 2 och 255. Skriv **uint8_t**. |
| void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) override | Ställer in namn på trendlinjen. Skriv [System::String](../../system/string/). |
| void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) override | Ställer in typ av trendlinje. Skriv [Charts::TrendlineType](../trendlinetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Ställer in n'te mallargument till en weak-pekare (i stället för shared). Tillåter att byta pekare i containrar till weak-läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Aktiverar konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning enligt C# lock()-sats för upplåsning. Anropas direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Borde inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se också

* Klassen [DomObject](../../aspose.slides/domobject/)
* Klassen [ITrendline](../itrendline/)
* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)