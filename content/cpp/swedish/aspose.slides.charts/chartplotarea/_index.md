---
title: ChartPlotArea
second_title: Aspose.Slides för C++ API-referens
description: Representerar rektangeln där diagrammet ska ritas.
type: docs
weight: 248
url: /sv/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea klass

Representerar rektangeln där diagrammet ska ritas.

```cpp
class ChartPlotArea : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                      public Aspose::Slides::Charts::IChartPlotArea
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden anses vara lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Anger den faktiska höjden på diagrammets element. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få de faktiska värdena. Läs **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Anger den faktiska bredden på diagrammets element. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få de faktiska värdena. Läs **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Anger den faktiska x-positionen (vänster) på diagrammets element relativt diagrammets vänstra övre hörn. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få de faktiska värdena. Läs **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Anger den faktiska överkant på diagrammets element relativt diagrammets vänstra övre hörn. Anropa metoden [IChart::ValidateChartLayout](../ichart/validatechartlayout/) först för att få de faktiska värdena. Läs **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Botten. Skrivskyddad **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | [Chart](../chart/). Skrivskyddad [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Returnerar formatet för ett plot-område. Skrivskyddad [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Returnerar höjden på ett plot-områdes begränsningsruta som en andel av diagrammets höjd (från 0 till 1). Läs **float**. |
| **bool** [get_IsLocationAutocalculated](./get_islocationautocalculated/)() | Definierar hur position ska beräknas: true – beräknas automatiskt; definierad av egenskaperna X, Y, Width, Height. Skrivskyddad **bool**. |
| [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() override | Om layouten för plot-området har definierats manuellt anger denna egenskap huruvida plot-området ska layoutas inifrån (utan axlar och axel-etiketter) eller utifrån (inklusive axlar och axel-etiketter). Läs [LayoutTargetType](../layouttargettype/). |
| **float** [get_Right](./get_right/)() override | Höger. Skrivskyddad **float**. |
| **float** [get_Width](./get_width/)() override | Returnerar bredden på ett plot-areas begränsningsruta som en andel av diagrammets bredd (från 0 till 1). Läs **float**. |
| **float** [get_X](./get_x/)() override | Returnerar x-koordinaten för plot-områdets övre vänstra hörn som en andel av diagrammets bredd (från 0 till 1). Läs **float**. |
| **float** [get_Y](./get_y/)() override | Returnerar y-koordinaten för plot-områdets övre vänstra hörn som en andel av diagrammets höjd (från 0 till 1). Läs **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referenskontrollens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-påvakningsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensvärdet av ett värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_Height](./set_height/)(**float**) override | Ställer in höjden på ett plot-områdes begränsningsruta som en andel av diagrammets höjd (från 0 till 1). Skriv **float**. |
| void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) override | Om layouten för plot-området har definierats manuellt anger denna egenskap huruvida plot-området ska layoutas inifrån (utan axlar och axel-etiketter) eller utifrån (inklusive axlar och axel-etiketter). Skriv [LayoutTargetType](../layouttargettype/). |
| void [set_Width](./set_width/)(**float**) override | Ställer in bredden på ett plot-områdes begränsningsruta som en andel av diagrammets bredd (från 0 till 1). Skriv **float**. |
| void [set_X](./set_x/)(**float**) override | Ställer in x-koordinaten för plot-områdets övre vänstra hörn som en andel av diagrammets bredd (från 0 till 1). Skriv **float**. |
| void [set_Y](./set_y/)(**float**) override | Ställer in y-koordinaten för plot-områdets övre vänstra hörn som en andel av diagrammets höjd (från 0 till 1). Skriv **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Ställer in det n-:de mallargumentet till en svag pekare (i stället för delad). Möjliggör att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-påvakningsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se också

* Klass [DomObject](../../aspose.slides/domobject/)
* Klass [IChartPlotArea](../ichartplotarea/)
* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)