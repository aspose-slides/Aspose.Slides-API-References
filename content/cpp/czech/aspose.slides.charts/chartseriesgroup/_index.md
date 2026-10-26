---
title: ChartSeriesGroup
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Představuje skupinu sérií.
type: docs
weight: 300
url: /cs/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup třída


Představuje skupinu sérií.

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | Určuje, jak jsou hodnoty velikosti bublin reprezentovány v bublinovém grafu. Přečtěte si [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | Určuje měřítkový faktor pro bublinový graf (může být mezi 0 a 300 procenty výchozí velikosti). Přečtěte si **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Vrací nadřazený graf. Pouze ke čtení [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | Vrací sérii grafu ve skupině na zadaném indexu. |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | Určuje velikost díry v prstencovém grafu (může být mezi 0 a 90 procenty velikosti oblasti nákresu). Přečtěte si **uint8_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | Získá úhel první výseče koláčového nebo prstencového grafu ve stupních (ve směru hodinových ručiček od shora, od 0 do 360 stupňů). Přečtěte si **uint16_t**. |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | Vrací vzdálenost, jako procento šířky značky, mezi datovými sériemi ve 3D grafu. Přečtěte si **uint16_t**. |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | Určuje prostor mezi shluky sloupců nebo pruhů, jako procento šířky sloupce nebo pruhu. Přečtěte si **uint16_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | True pokud graf má čáry sérií. Použito u sloupcových grafů s naskládáním a OfPie grafů. Přečtěte si **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | Určuje formát HiLowLines. HiLowLines se používá s typy grafů HiLowClose, OpenHiLowClose, VolumeHiLowClose a VolumeOpenHiLowClose. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | Určuje, že každý datový marker v sérii má jinou barvu. Přečtěte si **bool**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | Určuje, o kolik se mají sloupce a pruhy překrývat v 2D grafech, jako procento (od -100 % do 100 %). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | Určuje, jak určit, které datové body jsou ve druhém koláči nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Přečtěte si [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | Vlastní informace o rozdělení pro graf pie-of-pie nebo bar-of-pie s vlastním rozdělením. Vrací datový bod, který má být vykreslen ve druhém koláči nebo pruhu v grafu pie-of-pie nebo bar-of-pie podle indexu. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | Vlastní informace o rozdělení pro graf pie-of-pie nebo bar-of-pie s vlastním rozdělením. Obsahuje datové body, které mají být vykresleny ve druhém koláči nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Pouze ke čtení [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | Určuje hodnotu, která se má použít k určení, které datové body jsou ve druhém koláči nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Používá se spolu s vlastností PieSplitBy. Přečtěte si **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | Ukazuje, zda jsou série této skupiny vykresleny na sekundární ose. Pouze ke čtení **bool**. |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | Určuje velikost druhého koláče nebo pruhu v grafu pie-of-pie nebo bar-of-pie jako procento velikosti prvního koláče (může být mezi 5 a 200 procenty). Přečtěte si **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | Vrací kolekci sérií. Pouze ke čtení [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | Vrací typ této skupiny sérií. Pouze ke čtení [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | Poskytuje přístup k horním/dolním pruhům v čárovém nebo akciovém grafu. Pouze ke čtení [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | Získá prvek na zadaném indexu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny interní datové struktury. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený počítadlo referencí o zadanou hodnotu. |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | Určuje, jak jsou hodnoty velikosti bublin reprezentovány v bublinovém grafu. Zapište [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | Určuje měřítkový faktor pro bublinový graf (může být mezi 0 a 300 procenty výchozí velikosti). Zapište **int32_t**. |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | Určuje velikost díry v prstencovém grafu (může být mezi 0 a 90 procenty velikosti oblasti nákresu). Zapište **uint8_t**. |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | Nastaví úhel první výseče koláčového nebo prstencového grafu ve stupních (ve směru hodinových ručiček od shora, od 0 do 360 stupňů). Zapište **uint16_t**. |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | Nastaví vzdálenost, jako procento šířky značky, mezi datovými sériemi ve 3D grafu. Zapište **uint16_t**. |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | Určuje prostor mezi shluky sloupců nebo pruhů, jako procento šířky sloupce nebo pruhu. Zapište **uint16_t**. |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | True pokud graf má čáry sérií. Použito u sloupcových grafů s naskládáním a OfPie grafů. Zapište **bool**. |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | Určuje, že každý datový marker v sérii má jinou barvu. Zapište **bool**. |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | Určuje, o kolik se mají sloupce a pruhy překrývat v 2D grafech, jako procento (od -100 % do 100 %). |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | Určuje, jak určit, které datové body jsou ve druhém koláči nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Zapište [PieSplitType](../piesplittype/). |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | Určuje hodnotu, která se má použít k určení, které datové body jsou ve druhém koláči nebo pruhu v grafu pie-of-pie nebo bar-of-pie. Používá se spolu s vlastností PieSplitBy. Zapište **double**. |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | Určuje velikost druhého koláče nebo pruhu v grafu pie-of-pie nebo bar-of-pie jako procento velikosti prvního koláče (může být mezi 5 a 200 procenty). Zapište **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (místo sdíleného). Umožňuje přepnout ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílené počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílené počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabé počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabé počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |

## Poznámky


1) Viz souhrn a poznámky pro třídu ChartSeriesGroupCollection a výčet CombinableSeriesTypesGroup. 2) Skupina sérií obsahuje některé vlastnosti sérií, které jsou společné pro každou sérii ve skupině ("series group properties"). "Series group properties" ve třídě [ChartSeriesGroup](./) jsou čtení/zápis. Každá z "series group properties" může mít projekci pouze ke čtení ve třídě [ChartSeries](../chartseries/). 

## Viz také

* Třída [IChartSeriesGroup](../ichartseriesgroup/)
* Třída [IDOMObject](../../aspose.slides/idomobject/)
* Jmenný prostor [Aspose::Slides::Charts](../)
* Knihovna [Aspose.Slides](../../)