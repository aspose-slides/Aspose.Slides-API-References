---
title: IChartSeriesGroup
second_title: Aspose.Slides för C++ API-referens
description: Representerar en grupp av serier.
type: docs
weight: 846
url: /sv/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup klass

Representerar en grupp av serier.

```cpp
class IChartSeriesGroup : public Aspose::Slides::Charts::IChartComponent
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN betraktas som lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN betraktas som lika även om enligt IEC 60559:1989 NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | Anger hur bubbelstorleksvärden representeras i bubbeldiagrammet. Läs [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | Anger skalfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 procent av standardstorleken). Läs **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Returnerar diagrammet. Skrivskyddad [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | Returnerar diagramserierna i gruppen på det angivna indexet. |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | Anger storleken på hålet i ett donutsdiagram (kan vara mellan 10 och 90 procent av plotområdets storlek). Läs **uint8_t**. |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | Hämtar vinkeln för den första biten i ett paj- eller donutsdiagram, i grader (medurs från toppen, från 0 till 360 grader). Läs **uint16_t**. |
| virtual **uint16_t** [get_GapDepth](./get_gapdepth/)() | Returnerar avståndet, som en procent av markörens bredd, mellan dataserierna i ett 3D-diagram. Läs **uint16_t**. |
| virtual **uint16_t** [get_GapWidth](./get_gapwidth/)() | Anger avståndet mellan stapel- eller kolumnkluster, som en procent av stapelns eller kolumnens bredd. Läs **uint16_t**. |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | Sant om diagrammet har serielinjer. Tillämpligt på staplade stapeldiagram och OfPie-diagram. Läs **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() | Anger HiLowLines-format. HiLowLines tillämpas med HiLowClose, OpenHiLowClose, VolumeHiLowClose och VolumeOpenHiLowClose diagramtyper. |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | Anger att varje datamarkör i serien har en annan färg. Läs **bool**. |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | Anger hur mycket staplar och kolumner ska överlappa i 2D-diagram, som en procent (från -100% till 100%). |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | Anger hur man bestämmer vilka datapunkter som är i den andra pajen eller stapeln i ett pie-of-pie eller bar-of-pie-diagram. Läs [PieSplitType](../piesplittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | Den anpassade split-informationen för ett pie-of-pie eller bar-of-pie-diagram med en anpassad split. Returnerar datapunkt som ska ritas i den andra pajen eller stapeln i ett pie-of-pie eller bar-of-pie-diagram efter index. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | Den anpassade split-informationen för ett pie-of-pie eller bar-of-pie-diagram med en anpassad split. Innehåller datapunkter som ska ritas i den andra pajen eller stapeln i ett pie-of-pie eller bar-of-pie-diagram. Skrivskyddad [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/). |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | Anger ett värde som ska användas för att bestämma vilka datapunkter som är i den andra pajen eller stapeln i ett pie-of-pie eller bar-of-pie-diagram. Används tillsammans med PieSplitBy-egenskapen. Läs **double**. |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | Anger om serierna i denna grupp plottas på sekundär axel. Skrivskyddad **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Returnerar presentationen. Skrivskyddad [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | Anger storleken på den andra pajen eller stapeln i ett pie-of-pie- eller bar-of-pie-diagram, som en procent av den första pajens storlek (kan vara mellan 5 och 200 procent). Läs **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() | Returnerar en skrivskyddad samling av diagramserier. Skrivskyddad [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Returnerar grundsliden. Skrivskyddad [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() | Returnerar en typ av denna seriegrop. Skrivskyddad [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() | Tillhandahåller åtkomst till upp/ner staplar i linje- eller aktiediagram. Skrivskyddad [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Aktiverar hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) | Hämtar elementet på det angivna indexet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Aktiverar kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensvärdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar den delade referensräknaren med det angivna värdet. |
| virtual void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) | Anger hur bubbelstorleksvärden representeras i bubbeldiagrammet. Skriv [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) | Anger skalfaktorn för bubbeldiagrammet (kan vara mellan 0 och 300 procent av standardstorleken). Skriv **int32_t**. |
| virtual void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) | Anger storleken på hålet i ett donutsdiagram (kan vara mellan 10 och 90 procent av plotområdets storlek). Skriv **uint8_t**. |
| virtual void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) | Ställer in vinkeln för den första biten i ett paj- eller donutsdiagram, i grader (medurs från toppen, från 0 till 360 grader). Skriv **uint16_t**. |
| virtual void [set_GapDepth](./set_gapdepth/)(**uint16_t**) | Ställer in avståndet, som en procent av markörens bredd, mellan dataserierna i ett 3D-diagram. Skriv **uint16_t**. |
| virtual void [set_GapWidth](./set_gapwidth/)(**uint16_t**) | Anger avståndet mellan stapel- eller kolumnkluster, som en procent av stapelns eller kolumnens bredd. Skriv **uint16_t**. |
| virtual void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) | Sant om diagrammet har serielinjer. Tillämpligt på staplade stapeldiagram och OfPie-diagram. Skriv **bool**. |
| virtual void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) | Anger att varje datamarkör i serien har en annan färg. Skriv **bool**. |
| virtual void [set_Overlap](./set_overlap/)(**int8_t**) | Anger hur mycket staplar och kolumner ska överlappa i 2D-diagram, som en procent (från -100% till 100%). |
| virtual void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) | Anger hur man bestämmer vilka datapunkter som är i den andra pajen eller stapeln i ett pie-of-pie eller bar-of-pie-diagram. Skriv [PieSplitType](../piesplittype/). |
| virtual void [set_PieSplitPosition](./set_piesplitposition/)(**double**) | Anger ett värde som ska användas för att bestämma vilka datapunkter som är i den andra pajen eller stapeln i ett pie-of-pie eller bar-of-pie-diagram. Används tillsammans med PieSplitBy-egenskapen. Skriv **double**. |
| virtual void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) | Anger storleken på den andra pajen eller stapeln i ett pie-of-pie-diagram eller bar-of-pie-diagram, som en procent av den första pajens storlek (kan vara mellan 5 och 200 procent). Skriv **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te mallargument till en svag pekare (istället för delad). Möjliggör byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för den delade referensräknaren. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar den delade referensräknaren. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar den delade referensräknaren. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Aktiverar konvertering av anpassade objekt till string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar den svaga referensräknaren. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar den svaga referensräknaren. Borde inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Anmärkningar

1) Se sammanfattning och anmärkningar för ChartSeriesGroupCollection klass och CombinableSeriesTypesGroup enum. 2) Grupp av serier innehåller vissa seriegenskaper som är gemensamma för varje serie i gruppen ("series group properties"). "Series group properties" i [ChartSeriesGroup](../chartseriesgroup/) klass är Läs/skriv. Varje av "series group properties" kan ha en skrivskyddad projektion i [ChartSeries](../chartseries/) klass.

## Se även

* Klass [IChartComponent](../ichartcomponent/)
* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)