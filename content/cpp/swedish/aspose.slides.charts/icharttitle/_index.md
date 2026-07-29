---
title: IChartTitle
second_title: Aspose.Slides för C++ API-referens
description: Representerar egenskaper för diagramtitel.
type: docs
weight: 911
url: /sv/aspose.slides.charts/icharttitle/
---
## IChartTitle klass

Representerar egenskaper för diagramtitel.

```cpp
class IChartTitle : public Aspose::Slides::Charts::ILayoutable,
                    public Aspose::Slides::Charts::IOverridableText,
                    public Aspose::Slides::Charts::IActualLayout
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Initierar TextFrameForOverriding med texten i parametern \"text\". Om TextFrameForOverriding redan är initierad ändras dess text. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses vara lika även om IEC 60559:1989 specificerar att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses vara lika även om IEC 60559:1989 specificerar att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Anger den faktiska höjden på diagramelementet. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få faktiska värden. Läs **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Anger den faktiska bredden på diagramelementet. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få faktiska värden. Läs **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Anger den faktiska x-positionen (vänster) för diagramelementet relativt diagrammets vänstra övre hörn. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få faktiska värden. Läs **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Anger det faktiska övre värdet på diagramelementet relativt diagrammets vänstra övre hörn. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få faktiska värden. Läs **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Hämtar diagramelementets övre kant som en bråkdel av diagrammets höjd. Endast läs-**float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Returnerar diagrammet. Endast läs [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Returnerar fyllnings-, linje- och effektstilar för en titel. Endast läs [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Anger diagramelementets höjd som en bråkdel av diagrammets höjd. Läs **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | Bestämmer om andra diagramelement får överlappa titeln. Läs **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Returnerar presentationen. Endast läs [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Hämtar diagramelementets högra kant som en bråkdel av diagrammets bredd. Endast läs **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Returnerar grundbilden. Endast läs [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Returnerar diagramtextformatet. Endast läs [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Kan innehålla rikligt formaterad text. Om den här egenskapen inte är null så åsidosätter detta formaterade textvärde den automatiskt genererade texten. Den automatiskt genererade texten är en implicit egenskap för datamärkning, displayenhetens etikett för värdeaxeln, axelrubriken, diagramtiteln, trendlinjens etikett. Den automatiskt genererade texten är formaterad med egenskapen [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). Endast läs [ITextFrame](../../aspose.slides/itextframe/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Anger diagramelementets bredd som en bråkdel av diagrammets bredd. Läs **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Anger diagramelementets x-position (vänster) som en bråkdel av diagrammets bredd. Läs **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Anger diagramelementets övre kant som en bråkdel av diagrammets höjd. Läs **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt genom referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt genom referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetypobjekt med nullptr via referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Anger diagramelementets höjd som en bråkdel av diagrammets höjd. Skriv **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | Bestämmer om andra diagramelement får överlappa titeln. Skriv **bool**. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Anger diagramelementets bredd som en bråkdel av diagrammets bredd. Skriv **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Anger diagramelementets x-position (vänster) som en bråkdel av diagrammets bredd. Skriv **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Anger diagramelementets övre kant som en bråkdel av diagrammets höjd. Skriv **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n:te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning upp enligt C# lock()-satsen. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se också

* Klass [ILayoutable](../ilayoutable/)
* Klass [IOverridableText](../ioverridabletext/)
* Klass [IActualLayout](../iactuallayout/)
* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)