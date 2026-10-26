---
title: ITrendline
second_title: Aspose.Slides för C++ API-referens
description: Klassen representerar trendlinjen för en diagramserie
type: docs
weight: 1223
url: /sv/aspose.slides.charts/itrendline/
---
## ITrendline klass

Klassen representerar trendlinjen för ett diagramserie

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridingText
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Initierar TextFrameForOverriding med texten i parametern \"text\". Om TextFrameForOverriding redan är initierad ändras bara dess text. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual **double** [get_Backward](./get_backward/)() | Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig innan data för den serie som trenderas. På spridnings- och icke-spridningsdiagram ska värdet vara vilket icke-negativt värde som helst. Läs **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Returnerar diagrammet. Endast läsning [IChart](../ichart/). |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | Anger att ekvationen för trendlinjen visas på diagrammet (i samma etikett som Rsquaredvalue). Läs **bool**. |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | Anger att R-kvadrerat-värdet för trendlinjen visas på diagrammet (i samma etikett som ekvationen). Läs **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Representerar formatet för trendlinjen. Läs [IFormat](../iformat/). |
| virtual **double** [get_Forward](./get_forward/)() | Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig efter data för den serie som trenderas. På spridnings- och icke-spridningsdiagram ska värdet vara vilket icke-negativt värde som helst. Läs **double**. |
| virtual **double** [get_Intercept](./get_intercept/)() | Anger värdet där trendlinjen ska korsar y-axeln. Denna egenskap stöds endast när trendlinjetypen är exp, linear eller poly. Läs **double**. |
| virtual **uint8_t** [get_Order](./get_order/)() | Anger ordningen för den polynomiska trendlinjen. Den ignoreras för andra trendlinjetyper. Värdet måste vara mellan 2 och 6. Läs **uint8_t**. |
| virtual **uint8_t** [get_Period](./get_period/)() | Anger perioden för trendlinjen för ett glidande medelvärde. Den ignoreras för andra trendlinjevarianter. Värdet måste vara mellan 2 och 255. Läs **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Returnerar presentationen. Endast läsning [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | Representerar legendpost relaterad till denna trendlinje Endast läsning [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Returnerar grundsliden. Endast läsning [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Returnerar diagramtextformat. Endast läsning [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Kan innehålla en rik formaterad text. Om denna egenskap inte är null så åsidosätter detta formaterade textvärde den automatiskt genererade texten. Automatgenererad text är en implicit egenskap för datalabeln, displayenheten för värdeaxeln, axelrubriken, diagramrubriken, etiketten för trendlinjen. Automatgenererad text formateras med egenskapen [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Endast läsning [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | Hämtar namn på trendlinjen. Läs [System::String](../../system/string/). |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | Hämtar typ av trendlinje. Läs [TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräkningsdatastruktur associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar faktisk typ av objekt. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C# 'is'-operatorn. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, initierar bara nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, initierar bara nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt via referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt via referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräkning med angivet värde. |
| virtual void [set_Backward](./set_backward/)(**double**) | Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig innan data för den serie som trenderas. På spridnings- och icke-spridningsdiagram ska värdet vara vilket icke-negativt värde som helst. Skriv **double**. |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | Anger att ekvationen för trendlinjen visas på diagrammet (i samma etikett som Rsquaredvalue). Skriv **bool**. |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | Anger att R-kvadrerat-värdet för trendlinjen visas på diagrammet (i samma etikett som ekvationen). Skriv **bool**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Representerar formatet för trendlinjen. Skriv [IFormat](../iformat/). |
| virtual void [set_Forward](./set_forward/)(**double**) | Anger antalet kategorier (eller enheter på ett spridningsdiagram) som trendlinjen sträcker sig efter data för den serie som trenderas. På spridnings- och icke-spridningsdiagram ska värdet vara vilket icke-negativt värde som helst. Skriv **double**. |
| virtual void [set_Intercept](./set_intercept/)(**double**) | Anger värdet där trendlinjen ska korsar y-axeln. Denna egenskap stöds endast när trendlinjetypen är exp, linear eller poly. Skriv **double**. |
| virtual void [set_Order](./set_order/)(**uint8_t**) | Anger ordningen för den polynomiska trendlinjen. Den ignoreras för andra trendlinjetyper. Värdet måste vara mellan 2 och 6. Skriv **uint8_t**. |
| virtual void [set_Period](./set_period/)(**uint8_t**) | Anger perioden för trendlinjen för ett glidande medelvärde. Den ignoreras för andra trendlinjevarianter. Värdet måste vara mellan 2 och 255. Skriv **uint8_t**. |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | Ställer in namn på trendlinjen. Skriv [System::String](../../system/string/). |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | Ställer in typ av trendlinje. Skriv [TrendlineType](../trendlinetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i containrar till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräkning. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [IOverridableText](../ioverridabletext/)
* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)