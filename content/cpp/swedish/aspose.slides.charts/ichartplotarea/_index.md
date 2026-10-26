---
title: IChartPlotArea
second_title: Aspose.Slides för C++ API-referens
description: Representerar diagramtitelens egenskaper.
type: docs
weight: 794
url: /sv/aspose.slides.charts/ichartplotarea/
---
## IChartPlotArea klass

Representerar diagramtitelens egenskaper.

```cpp
class IChartPlotArea : public Aspose::Slides::Charts::ILayoutable,
                       public Aspose::Slides::Charts::IActualLayout
```

## Metoder

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypsobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Anger den faktiska höjden på diagramelementet. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få faktiska värden. Läs **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Anger den faktiska bredden på diagramelementet. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få faktiska värden. Läs **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Anger den faktiska x-positionen (vänster) för diagramelementet relativt diagrammets vänstra övre hörn. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få faktiska värden. Läs **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Anger den faktiska toppen på diagramelementet relativt diagrammets vänstra övre hörn. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få faktiska värden. Läs **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Hämtar toppen på diagramelementet som en bråkdel av diagrammets höjd. Read-only **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Returnerar diagrammet. Read-only [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Returnerar formatet på ett plotområde. Read-only [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Anger höjden på diagramelementet som en bråkdel av diagrammets höjd. Läs **float**. |
| virtual [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() | Om layouten för plotområdet definierats manuellt anger den här egenskapen huruvida plotområdet ska läggas ut efter dess insida (utan axlar och axelrubriker) eller utsida (med axlar och axelrubriker). Läs [LayoutTargetType](../layouttargettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Returnerar presentationen. Read-only [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Hämtar diagramelementets högra kant som en bråkdel av diagrammets bredd. Read-only **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Returnerar grundbilden. Read-only [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Anger bredden på diagramelementet som en bråkdel av diagrammets bredd. Läs **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Anger diagramelementets x-position (vänster) som en bråkdel av diagrammets bredd. Läs **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Anger diagramelementets topp som en bråkdel av diagrammets höjd. Läs **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet är en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C#-statement lock(). Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypsobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknet med angivet värde. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Anger höjden på diagramelementet som en bråkdel av diagrammets höjd. Skriv **float**. |
| virtual void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) | Om layouten för plotområdet definierats manuellt anger den här egenskapen huruvida plotområdet ska läggas ut efter dess insida (utan axlar och axelrubriker) eller utsida (med axlar och axelrubriker). Skriv [LayoutTargetType](../layouttargettype/). |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Anger bredden på diagramelementet som en bråkdel av diagrammets bredd. Skriv **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Anger diagramelementets x-position (vänster) som en bråkdel av diagrammets bredd. Skriv **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Anger diagramelementets topp som en bråkdel av diagrammets höjd. Skriv **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te mallargument till en svag pekare (i stället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar nuvarande värde på delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C#-konstruktionen typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning enligt C#-statement lock(). Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [ILayoutable](../ilayoutable/)
* Klass [IActualLayout](../iactuallayout/)
* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)