---
title: IDataLabel
second_title: Aspose.Slides för C++ API-referens
description: Representerar serietiketter.
type: docs
weight: 937
url: /sv/aspose.slides.charts/idatalabel/
---
## IDataLabel klass


Representerar serietiketter.

```cpp
class IDataLabel : public Aspose::Slides::Charts::ILayoutable,
                   public Aspose::Slides::Charts::IOverridableText,
                   public Aspose::Slides::Charts::IActualLayout
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Initierar TextFrameForOverriding med texten i parametern "text". Om TextFrameForOverriding redan är initierad ändras bara dess text. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses vara lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses vara lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Anger den faktiska höjden på diagrammet. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få faktiska värden. Läs **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Anger den faktiska bredden på diagrammet. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få faktiska värden. Läs **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Anger den faktiska x-positionen (vänster) för diagrammet relativt diagrammets övre vänstra hörn. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få faktiska värden. Läs **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Anger den faktiska överkant för diagrammet relativt diagrammets övre vänstra hörn. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få faktiska värden. Läs **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Hämtar den övre positionen för diagrammet som en andel av diagrammets höjd. Skrivar-skyddad **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Returnerar diagrammet. Skrivskyddad [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() | Returnerar formatet för dataetiketten. Skrivskyddad [IDataLabelFormat](../idatalabelformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Anger diagrammets höjd som en andel av diagrammets höjd. Läs **float**. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | False betyder att dataetiketten inte är synlig (och alla Show*-flaggor (ShowValue, ...) är falska). Skrivskyddad **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Returnerar presentationen. Skrivskyddad [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Hämtar diagrammets högra kant som en andel av diagrammets bredd. Skrivskyddad **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Returnerar grundbilden. Skrivskyddad [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Returnerar diagrammets textformat. Skrivskyddad [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Kan innehålla rik formaterad text. Om denna egenskap inte är null så åsidosätter det formaterade textvärdet den automatiskt genererade texten. Automatgenererad text är en implicit egenskap för dataetiketten, enhetsetiketten för värdeaxeln, axelrubriken, diagramrubriken, trendlinjens etikett. Automatgenererad text formateras med egenskapen [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Skrivskyddad [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() | Hämtar arbetsbokens datacell. Används om egenskapen IDataLabelFormat::get(set)_ShowLabelValueFromCell är sann. |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Anger diagrammets bredd som en andel av diagrammets bredd. Läs **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Anger diagrammets x-position (vänster) som en andel av diagrammets bredd. Läs **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Anger diagrammets överkant som en andel av diagrammets höjd. Läs **float**. |
| virtual [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() | Returnerar den faktiska etiketttexten baserat på [DataLabelFormat](../datalabelformat/)-inställningarna eller TextFrameForOverriding.Text-värdet. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referenräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual void [Hide](./hide/)() | Gör dataetiketten dold genom att sätta alla Show*-flaggor (ShowValue, ...) till falskt. IsVisible blir falskt efter detta. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsen för låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjektet. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referenräknare med angivet värde. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Anger diagrammets höjd som en andel av diagrammets höjd. Skriv **float**. |
| virtual void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | Sätter arbetsbokens datacell. Används om egenskapen IDataLabelFormat::get(set)_ShowLabelValueFromCell är sann. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Anger diagrammets bredd som en andel av diagrammets bredd. Skriv **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Anger diagrammets x-position (vänster) som en andel av diagrammets bredd. Skriv **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Anger diagrammets överkant som en andel av diagrammets höjd. Skriv **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter det n-:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar det aktuella värdet av delad referenräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referenräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referenräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-sats för upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referenräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referenräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigir alla interna datastrukturer. |

## Se även

* Klass [ILayoutable](../ilayoutable/)
* Klass [IOverridableText](../ioverridabletext/)
* Klass [IActualLayout](../iactuallayout/)
* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)