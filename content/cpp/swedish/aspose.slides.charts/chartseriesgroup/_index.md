---
title: ChartSeriesGroup
second_title: Aspose.Slides för C++ API-referens
description: Representerar en grupp av serier.
type: docs
weight: 300
url: /sv/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup klass

Representerar en grupp av serier.

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | Anger hur bubbla storleksvärden representeras i bubbeldiagrammet. Läs [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | Anger skalningsfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 procent av standardstorleken). Läs **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Returnerar överordnat diagram. Skriva-endast [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | Returnerar diagramserien i gruppen på angivet index. |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | Anger storleken på hålet i ett donutdiagram (kan vara mellan 0 och 90 procent av storleken på plot-området). Läs **uint8_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | Hämtar vinkeln på den första paj- eller donutdiagram-skivan, i grader (medurs från toppen, från 0 till 360 grader). Läs **uint16_t**. |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | Returnerar avståndet, som procent av markörbredden, mellan dataserierna i ett 3D-diagram. Läs **uint16_t**. |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | Anger avståndet mellan stapel- eller kolumnkluster, som procent av stapel- eller kolumnbredden. Läs **uint16_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | Sant om diagrammet har serielinjer. Används för staplade stapeldiagram och OfPie-diagram. Läs **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | Anger HiLowLines-format. HiLowLines tillämpas med HiLowClose, OpenHiLowClose, VolumeHiLowClose och VolumeOpenHiLowClose diagramtyper. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | Anger att varje datamarkör i serien har en annan färg. Läs **bool**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | Anger hur mycket staplar och kolumner ska överlappa i 2-D-diagram, som procent (från -100 % till 100 %). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | Anger hur man avgör vilka datapunkter som finns i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Läs [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | Den anpassade delningsinformationen för ett pie-of-pie- eller bar-of-pie-diagram med en anpassad delning. Returnerar datapunkten som ska ritas i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram efter index. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | Den anpassade delningsinformationen för ett pie-of-pie- eller bar-of-pie-diagram med en anpassad delning. Innehåller datapunkter som ska ritas i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Skriva-endast [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | Anger ett värde som ska användas för att avgöra vilka datapunkter som finns i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Används tillsammans med egenskapen PieSplitBy. Läs **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | Indikerar om serierna i denna grupp plottas på sekundär axel. Skriva-endast **bool**. |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | Anger storleken på den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram, som procent av storleken på den första pajen (kan vara mellan 5 och 200 procent). Läs **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | Returnerar en samling av serier. Skriva-endast [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | Returnerar en typ av denna seriegroupp. Skriva-endast [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | Tillhandahåller åtkomst till upp/ner staplar i Linje- eller Aktiediagram. Skriva-endast [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknar-datastruktur associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog av C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog av C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | Hämtar elementet på angivet index. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog av C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-statement låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog av C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | Anger hur bubbla storleksvärden representeras i bubbeldiagrammet. Skriv [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | Anger skalningsfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 procent av standardstorleken). Skriv **int32_t**. |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | Anger storleken på hålet i ett donutdiagram (kan vara mellan 0 och 90 procent av storleken på plot-området). Skriv **uint8_t**. |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | Ställer in vinkeln på den första paj- eller donut-skivan, i grader (medurs från toppen, från 0 till 360 grader). Skriv **uint16_t**. |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | Ställer in avståndet, som procent av markörbredden, mellan dataserierna i ett 3D-diagram. Skriv **uint16_t**. |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | Anger avståndet mellan stapel- eller kolumnkluster, som procent av stapel- eller kolumnbredden. Skriv **uint16_t**. |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | Sant om diagrammet har serielinjer. Används för staplade stapeldiagram och OfPie-diagram. Skriv **bool**. |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | Anger att varje datamarkör i serien har en annan färg. Skriv **bool**. |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | Anger hur mycket staplar och kolumner ska överlappa i 2-D-diagram, som procent (från -100 % till 100 %). |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | Anger hur man avgör vilka datapunkter som finns i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Skriv [PieSplitType](../piesplittype/). |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | Anger ett värde som ska användas för att avgöra vilka datapunkter som finns i den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram. Används tillsammans med egenskapen PieSplitBy. Skriv **double**. |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | Anger storleken på den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram, som procent av storleken på den första pajen (kan vara mellan 5 och 200 procent). Skriv **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n:te mallargumentet till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog av C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-statement upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Anmärkningar

1) Se sammanfattning och kommentarer för ChartSeriesGroupCollection-klassen och CombinableSeriesTypesGroup-enumet. 2) En grupp av serier innehåller vissa serie-egenskaper som är gemensamma för varje serie i gruppen ("series group properties"). "Series group properties" i [ChartSeriesGroup](./)-klassen är läs/skriv. Varje av "series group properties" kan ha en skriv-endast projicering i [ChartSeries](../chartseries/)-klassen. 

## Se även

* Klass [IChartSeriesGroup](../ichartseriesgroup/)
* Klass [IDOMObject](../../aspose.slides/idomobject/)
* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)