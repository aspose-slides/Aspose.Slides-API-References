---
title: ChartSeries
second_title: Aspose.Slides pro C++ API Reference
description: Reprezentuje sérii grafu.
type: docs
weight: 274
url: /cs/aspose.slides.charts/chartseries/
---
## ChartSeries třída

Zastupuje sérii grafu.

```cpp
class ChartSeries : public Aspose::Slides::Charts::IChartSeries,
                    public Aspose::Slides::IDOMObject
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání floating-point ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání floating-point ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| [ChartShapeType](../chartshapetype/) [get_Bar3DShape](./get_bar3dshape/)() override | Určuje tvar série 3-D sloupcového grafu. Změna hodnoty této vlastnosti může způsobit automatickou změnu typu série. Read [ChartShapeType](../chartshapetype/). |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | Určuje, jak jsou hodnoty velikosti bublin zobrazovány v bublinovém grafu. Tato vlastnost není jen pro tuto sérii, ale pro všechny série v nadřazené skupině sérií – jedná se o projekci příslušné vlastnosti skupiny. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeRepresentation() čtení/zápis pro změnu hodnoty. |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | Určuje škálovací faktor pro bublinový graf (může být mezi 0 a 300 % výchozí velikosti). Tato vlastnost není jen pro tuto sérii, ale pro všechny série v nadřazené skupině sérií – jedná se o projekci příslušné vlastnosti skupiny. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte vlastnost [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeScale() čtení/zápis pro změnu hodnoty. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Vrací nadřazený graf. Pouze pro čtení [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_DataPoint](./get_datapoint/)(**int32_t**) override | Vrací datový bod této série na zadaném indexu. |
| **int32_t** [get_DataPoint](./get_datapoint/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointCollection](../ichartdatapointcollection/)\> [get_DataPoints](./get_datapoints/)() override | Vrací kolekci datových bodů této série. Pouze pro čtení [IChartDataPointCollection](../ichartdatapointcollection/). |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | Určuje velikost díry v donutovém grafu (může být mezi 10 a 90 % velikosti oblasti vykreslování). Tato vlastnost není jen pro tuto sérii, ale pro všechny série v nadřazené skupině sérií – jedná se o projekci příslušné vlastnosti skupiny. Tato vlastnost je pouze pro čtení. Použijte vlastnost ParentSeriesGroup pro přístup k nadřazené skupině sérií. Použijte [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_DoughnutHoleSize() čtení/zápis pro změnu hodnoty. Pouze pro čtení **uint8_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsXFormat](./get_errorbarsxformat/)() override | Reprezentuje ErrorBars série s orientací X. |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsYFormat](./get_errorbarsyformat/)() override | Reprezentuje ErrorBars série s orientací Y. |
| **int32_t** [get_Explosion](./get_explosion/)() override | Vzdálenost výseku otevřeného koláče od středu koláčového grafu je vyjádřena v procentech průměru koláče. Číst **int32_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | Určuje úhel první výseky koláčového nebo donutového grafu ve stupních (ve směru hodinových ručiček od horního směru, od 0 do 360 stupňů). Tato vlastnost je pouze pro čtení. Použijte ParentSeriesGroup ... Použijte [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_FirstSliceAngle() čtení/zápis pro změnu hodnoty. Pouze pro čtení **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Vrací formát série. Pouze pro čtení [IFormat](../iformat/). |
| **int32_t** [get_GapDepth](./get_gapdepth/)() override | Vrací vzdálenost, vyjádřenou v procentech šířky značky, mezi datovými sériemi ve 3D grafu. Tato vlastnost je pouze pro čtení. Použijte ParentSeriesGroup ... Použijte [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapDepth() čtení/zápis pro změnu hodnoty. Pouze pro čtení **int32_t**. |
| **int32_t** [get_GapWidth](./get_gapwidth/)() override | Určuje prostor mezi clustery sloupců nebo sloupčků, jako procento šířky sloupce nebo sloupčků. Tato vlastnost je pouze pro čtení. Použijte ParentSeriesGroup ... Použijte [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapWidth() čtení/zápis pro změnu hodnoty. Pouze pro čtení **int32_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | Určuje, zda existují čáry sérií pro tuto sérii a související série. Tato vlastnost je pouze pro čtení. Použijte ParentSeriesGroup ... Použijte [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_HasSeriesLines() čtení/zápis pro změnu hodnoty. Použijte ParentSeriesGroup.SeriesLinesFormat pro formát čar sérií. Pouze pro čtení **bool**. |
| **bool** [get_HasUpDownBars](./get_hasupdownbars/)() override | Určuje, zda má Line- nebo Stock-graf svislé/rozpadové pruhy. Tato vlastnost je pouze pro čtení. Použijte ParentSeriesGroup ... Použijte [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars()->get(set)_HasUpDownBars() čtení/zápis pro změnu hodnoty. Použijte [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars() pro formát svislých/rozpadových pruhů. Pouze pro čtení **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_InvertedSolidFillColor](./get_invertedsolidfillcolor/)() override | Určuje invertovanou plnou barvu pro sérii. Pro aplikaci nastavení barvy nastavte FillType formátu série na [FillType::Solid](../../aspose.slides/filltype/). Číst [ColorFormat](../../aspose.slides/colorformat/). |
| **bool** [get_InvertIfNegative](./get_invertifnegative/)() override | Určuje, že sloupcová, sloupcová nebo bublinová série má invertovat své barvy, pokud je hodnota záporná. Číst **bool**. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | Určuje, že každý datový marker v sérii má jinou barvu. Tato vlastnost je pouze pro čtení. Použijte ParentSeriesGroup ... Použijte [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_IsColorVaried() čtení/zápis pro změnu hodnoty. Pouze pro čtení **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)(**int32_t**) override | Vrací popisek datového bodu této série na zadaném indexu. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelCollection](../idatalabelcollection/)\> [get_Labels](./get_labels/)() override | Vrací štítky série. Pouze pro čtení [IDataLabelCollection](../idatalabelcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() override | [Marker](../marker/). Pouze pro čtení [IMarker](../imarker/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IStringChartValue](../istringchartvalue/)\> [get_Name](./get_name/)() override | Vrátí název série. Pouze pro čtení [IStringChartValue](../istringchartvalue/). |
| [System::String](../../system/string/) [get_NumberFormatOfBubbleSizes](./get_numberformatofbubblesizes/)() override | NumberFormatOfBubbleSizes. Read [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_NumberFormatOfValues](./get_numberformatofvalues/)() override | NumberFormatOfValues. Read [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_NumberFormatOfXValues](./get_numberformatofxvalues/)() override | NumberFormatOfXValues. Read [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_NumberFormatOfYValues](./get_numberformatofyvalues/)() override | NumberFormatOfYValues. Read [System::String](../../system/string/). |
| **int32_t** [get_Order](./get_order/)() override | Vrací pořadí série. Číst **int32_t**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | Určuje, jak moc se sloupce a sloupčci překrývají v 2-D grafech, jako procento (od -100 % do 100 %). Tato vlastnost není jen pro tuto sérii, ale pro všechny série v nadřazené skupině sérií. Jedná se o projekci příslušné vlastnosti v nadřazené skupině sérií, a proto je tato vlastnost pouze pro čtení. Pro změnu hodnoty použijte vlastnost [get_ParentSeriesGroup()->Overlap()](./get_parentseriesgroup/) čtení/zápis. Pouze pro čtení **int8_t**. |
| [ParentLabelLayoutType](../parentlabellayouttype/) [get_ParentLabelLayout](./get_parentlabellayout/)() override | Reprezentuje rozvržení štítků nadřazených kategorií. Používá se jen u grafů Treemap. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ParentSeries](./get_parentseries/)(**int32_t**) override | Vrací sérii grafu v nadřazené skupině sérií na zadaném indexu. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_ParentSeriesGroup](./get_parentseriesgroup/)() override | ParentSeriesGroup. Pouze pro čtení [IChartSeriesGroup](../ichartseriesgroup/). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | Určuje, jak určit, které datové body jsou ve druhém výseku nebo sloupci v grafu pie-of-pie nebo bar-of-pie. Tato vlastnost není jen pro tuto sérii, ale pro všechny série v nadřazené skupině sérií – jedná se o projekci příslušné vlastnosti skupiny. Tato vlastnost je pouze pro čtení. Použijte ParentSeriesGroup ... Použijte [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitBy() čtení/zápis pro změnu hodnoty. Pouze pro čtení [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | Vlastní informace o rozdělení pro graf pie-of-pie nebo bar-of-pie s vlastním rozdělením. Vrací datový bod, který má být vykreslen v druhém výseku nebo sloupci v grafu pie-of-pie nebo bar-of-pie na zadaném indexu. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | Vlastní informace o rozdělení pro graf pie-of-pie nebo bar-of-pie s vlastním rozdělením. Obsahuje datové body, které mají být vykresleny ve druhém výseku nebo sloupci v grafu pie-of-pie nebo bar-of-pie. Tato vlastnost není jen pro tuto sérii, ale pro všechny série v nadřazené skupině sérií – jedná se o projekci příslušné vlastnosti skupiny. Pouze pro čtení [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | Určuje hodnotu, která má být použita k určení, které datové body jsou ve druhém výseku nebo sloupci v grafu pie-of-pie nebo bar-of-pie. Používá se spolu s vlastností PieSplitBy. Tato vlastnost není jen pro tuto sérii, ale pro všechny série v nadřazené skupině sérií – jedná se o projekci příslušné vlastnosti skupiny. Tato vlastnost je pouze pro čtení. Použijte ParentSeriesGroup ... Použijte [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitPosition() čtení/zápis pro změnu hodnoty. Pouze pro čtení **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | Indikuje, zda je tato série vykreslena na sekundární ose. Číst **bool**. |
| [QuartileMethodType](../quartilemethodtype/) [get_QuartileMethod](./get_quartilemethod/)() override | Reprezentuje metodu kvartilu. Používá se jen u grafů BoxAndWhisker. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | Reprezentuje položku legendy související s touto sérií. Pouze pro čtení [ILegendEntryProperties](../ilegendentryproperties/). |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | Určuje velikost druhého výseku nebo sloupce v grafu pie-of-pie nebo bar-of-pie jako procento velikosti prvního výseku (může být mezi 5 a 200 %). Tato vlastnost není jen pro tuto sérii, ale pro všechny série v nadřazené skupině sérií – jedná se o projekci příslušné vlastnosti skupiny. Tato vlastnost je pouze pro čtení. Použijte ParentSeriesGroup ... Použijte [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_SecondPieSize() čtení/zápis pro změnu hodnoty. Pouze pro čtení **uint16_t**. |
| **bool** [get_ShowConnectorLines](./get_showconnectorlines/)() override | Reprezentuje spojovací čáry. Používá se jen u grafů Waterfall. |
| **bool** [get_ShowInnerPoints](./get_showinnerpoints/)() override | Reprezentuje vnitřní body. Pravda, pokud jsou vnitřní body zobrazeny v grafu BoxAndWhisker. Používá se jen u grafů BoxAndWhisker. Číst **bool**. |
| **bool** [get_ShowMeanLine](./get_showmeanline/)() override | Reprezentuje průměrovací čáru. Pravda, pokud jsou průměrovací čáry zobrazeny v grafu BoxAndWhisker. Používá se jen u grafů BoxAndWhisker. Číst **bool**. |
| **bool** [get_ShowMeanMarkers](./get_showmeanmarkers/)() override | Reprezentuje průměrovací značky. Pravda, pokud jsou průměrovací značky zobrazeny v grafu BoxAndWhisker. Používá se jen u grafů BoxAndWhisker. Číst **bool**. |
| **bool** [get_ShowOutlierPoints](./get_showoutlierpoints/)() override | Reprezentuje odlehlé body. Pravda, pokud jsou odlehlé body zobrazeny v grafu BoxAndWhisker. Používá se jen u grafů BoxAndWhisker. Číst **bool**. |
| **bool** [get_Smooth](./get_smooth/)() override | Reprezentuje vyhlazování křivek. Pravda, pokud je vyhlazování křivek zapnuto pro čárový graf nebo bodový graf. Používá se jen u čárových a bodových grafů spojených čarami. Číst **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITrendline](../itrendline/)\> [get_TrendLine](./get_trendline/)(**int32_t**) override | Vrací trendovou čáru na zadaném indexu. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITrendlineCollection](../itrendlinecollection/)\> [get_TrendLines](./get_trendlines/)() override | Kolekce trendových čar série. Pouze pro čtení [ITrendlineCollection](../itrendlinecollection/). |
| [ChartType](../charttype/) [get_Type](./get_type/)() override | Vrací typ této série. Číst [ChartType](../charttype/). |
| [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticSeriesColor](./getautomaticseriescolor/)() override | Vrací automatickou barvu série na základě indexu série a stylu grafu. Tato barva je použita ve výchozím nastavení, pokud je FillType rovno NotDefined. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu čítače odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač odkazů o zadanou hodnotu. |
| void [set_Bar3DShape](./set_bar3dshape/)([ChartShapeType](../chartshapetype/)) override | Určuje tvar série 3-D sloupcového grafu. Změna hodnoty této vlastnosti může způsobit automatickou změnu typu série. Zapište [ChartShapeType](../chartshapetype/). |
| void [set_Explosion](./set_explosion/)(**int32_t**) override | Vzdálenost výseku otevřeného koláče od středu koláčového grafu je vyjádřena v procentech průměru koláče. Zapište **int32_t**. |
| void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) override | Určuje, že sloupcová, sloupcová nebo bublinová série má invertovat barvy, pokud je hodnota záporná. Zapište **bool**. |
| void [set_NumberFormatOfBubbleSizes](./set_numberformatofbubblesizes/)([System::String](../../system/string/)) override | NumberFormatOfBubbleSizes. Zapište [System::String](../../system/string/). |
| void [set_NumberFormatOfValues](./set_numberformatofvalues/)([System::String](../../system/string/)) override | NumberFormatOfValues. Zapište [System::String](../../system/string/). |
| void [set_NumberFormatOfXValues](./set_numberformatofxvalues/)([System::String](../../system/string/)) override | NumberFormatOfXValues. Zapište [System::String](../../system/string/). |
| void [set_NumberFormatOfYValues](./set_numberformatofyvalues/)([System::String](../../system/string/)) override | NumberFormatOfYValues. Zapište [System::String](../../system/string/). |
| void [set_Order](./set_order/)(**int32_t**) override | Vrací pořadí série. Zapište **int32_t**. |
| void [set_ParentLabelLayout](./set_parentlabellayout/)([ParentLabelLayoutType](../parentlabellayouttype/)) override | Reprezentuje rozvržení štítků nadřazených kategorií. Používá se jen u grafů Treemap. |
| void [set_PlotOnSecondAxis](./set_plotonsecondaxis/)(**bool**) override | Indikuje, zda je tato série vykreslena na sekundární ose. Zapište **bool**. |
| void [set_QuartileMethod](./set_quartilemethod/)([QuartileMethodType](../quartilemethodtype/)) override | Reprezentuje metodu kvartilu. Používá se jen u grafů BoxAndWhisker. |
| void [set_ShowConnectorLines](./set_showconnectorlines/)(**bool**) override | Reprezentuje spojovací čáry. Používá se jen u grafů Waterfall. |
| void [set_ShowInnerPoints](./set_showinnerpoints/)(**bool**) override | Reprezentuje vnitřní body. Pravda, pokud jsou vnitřní body zobrazeny v grafu BoxAndWhisker. Používá se jen u grafů BoxAndWhisker. Zapište **bool**. |
| void [set_ShowMeanLine](./set_showmeanline/)(**bool**) override | Reprezentuje průměrovací čáru. Pravda, pokud jsou průměrovací čáry zobrazeny v grafu BoxAndWhisker. Používá se jen u grafů BoxAndWhisker. Zapište **bool**. |
| void [set_ShowMeanMarkers](./set_showmeanmarkers/)(**bool**) override | Reprezentuje průměrovací značky. Pravda, pokud jsou průměrovací značky zobrazeny v grafu BoxAndWhisker. Používá se jen u grafů BoxAndWhisker. Zapište **bool**. |
| void [set_ShowOutlierPoints](./set_showoutlierpoints/)(**bool**) override | Reprezentuje odlehlé body. Pravda, pokud jsou odlehlé body zobrazeny v grafu BoxAndWhisker. Používá se jen u grafů BoxAndWhisker. Zapište **bool**. |
| void [set_Smooth](./set_smooth/)(**bool**) override | Reprezentuje vyhlazování křivek. Pravda, pokud je vyhlazování křivek zapnuto pro čárový graf nebo bodový graf. Používá se jen u čárových a bodových grafů spojených čarami. Zapište **bool**. |
| void [set_Type](./set_type/)([ChartType](../charttype/)) override | Vrací typ této série. Zapište [ChartType](../charttype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač odkazů. Nemělo by se volat přímo; místo toho používejte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač odkazů. Nemělo by se volat přímo; místo toho používejte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač odkazů. Nemělo by se volat přímo; místo toho používejte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač odkazů. Nemělo by se volat přímo; místo toho používejte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [IChartSeries](../ichartseries/)
* Třída [IDOMObject](../../aspose.slides/idomobject/)
* Namespace [Aspose::Slides::Charts](../)
* Knihovna [Aspose.Slides](../../)