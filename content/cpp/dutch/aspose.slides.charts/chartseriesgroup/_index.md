---
title: ChartSeriesGroup
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een groep series voor.
type: docs
weight: 300
url: /nl/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup klasse

Stelt een groep van series voor.

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
```

## Methoden

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | Specificeert hoe de bubbelaantalgroottes worden weergegeven op het bubbel-diagram. Lees [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | Specificeert de schaalfactor voor het bubbel-diagram (kan tussen 0 en 300 procent van de standaardgrootte liggen). Lees **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Retourneert het bovenliggende diagram. Alleen-lezen [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | Retourneert de diagramreeks in de groep op de opgegeven index. |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | Specificeert de grootte van het gat in een donutdiagram (kan tussen 0 en 90 procent van de grootte van het plotgebied liggen). Lees **uint8_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | Haal de hoek van het eerste taart- of donutdiagramsegment op, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Lees **uint16_t**. |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | Retourneert de afstand, als een percentage van de markerbreedte, tussen de gegevensreeksen in een 3D-diagram. Lees **uint16_t**. |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | Specificeert de ruimte tussen balk- of kolomclusters, als percentage van de balk- of kolombreedte. Lees **uint16_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | Waar als het diagram serielijnen heeft. Toegepast op gestapelde balk- en OfPie-diagrammen. Lees **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | Specificeert het HiLowLines-formaat. HiLowLines worden toegepast met HiLowClose-, OpenHiLowClose-, VolumeHiLowClose- en VolumeOpenHiLowClose-diagramtypen. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | Specificeert dat elke datamarker in de reeks een andere kleur heeft. Lees **bool**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | Specificeert hoeveel balken en kolommen elkaar overlappen in 2-D-diagrammen, als percentage (van -100% tot 100%). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | Specificeert hoe te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-in-taart- of balk-in-taart-diagram. Lees [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | De aangepaste splitsinformatie voor een taart-in-taart- of balk-in-taart-diagram met een aangepaste splitsing. Retourneert het datapunt dat moet worden getekend in de tweede taart of balk in een taart-in-taart- of balk-in-taart-diagram, op basis van index. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | De aangepaste splitsinformatie voor een taart-in-taart- of balk-in-taart-diagram met een aangepaste splitsing. Bevat datapunt(en) die in de tweede taart of balk in een taart-in-taart- of balk-in-taart-diagram getekend moeten worden. Alleen-lezen [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | Specificeert een waarde die gebruikt moet worden om te bepalen welke datapunt(en) zich in de tweede taart of balk bevinden in een taart-in-taart- of balk-in-taart-diagram. Wordt samen met de PieSplitBy-eigenschap gebruikt. Lees **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | Geeft aan of de reeksen van deze groep op een secundaire as worden geplot. Alleen-lezen **bool**. |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | Specificeert de grootte van de tweede taart of balk van een taart-in-taart- of balk-in-taart-diagram, als percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). Lees **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | Retourneert een verzameling van reeksen. Alleen-lezen [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | Retourneert een type van deze reeksgroep. Alleen-lezen [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | Biedt toegang tot op/af-balken van een Lijn- of Aandelendiagram. Alleen-lezen [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haal de referentieteller-gegevensstructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | Haalt het element op op de opgegeven index. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets, initialiseert alleen een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert enkel een nieuw object en maakt het mogelijk om subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt referentieel een waardetype-object met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | Specificeert hoe de bubbelaantalgroottes worden weergegeven op het bubbel-diagram. Schrijf [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | Specificeert de schaalfactor voor het bubbel-diagram (kan tussen 0 en 300 procent van de standaardgrootte liggen). Schrijf **int32_t**. |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | Specificeert de grootte van het gat in een donutdiagram (kan tussen 0 en 90 procent van de grootte van het plotgebied liggen). Schrijf **uint8_t**. |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | Stelt de hoek van het eerste taart- of donutsegment in, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Schrijf **uint16_t**. |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | Stelt de afstand in, als percentage van de markerbreedte, tussen de gegevensreeksen in een 3D-diagram. Schrijf **uint16_t**. |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | Specificeert de ruimte tussen balk- of kolomclusters, als percentage van de balk- of kolombreedte. Schrijf **uint16_t**. |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | Waar als het diagram serielijnen heeft. Toegepast op gestapelde balk- en OfPie-diagrammen. Schrijf **bool**. |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | Specificeert dat elke datamarker in de reeks een andere kleur heeft. Schrijf **bool**. |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | Specificeert hoeveel balken en kolommen elkaar overlappen in 2-D-diagrammen, als percentage (van -100% tot 100%). |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | Specificeert hoe te bepalen welke datapunt(en) zich in de tweede taart of balk bevinden in een taart-in-taart- of balk-in-taart-diagram. Schrijf [PieSplitType](../piesplittype/). |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | Specificeert een waarde die gebruikt moet worden om te bepalen welke datapunt(en) zich in de tweede taart of balk bevinden in een taart-in-taart- of balk-in-taart-diagram. Wordt samen met de PieSplitBy-eigenschap gebruikt. Schrijf **double**. |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | Specificeert de grootte van de tweede taart of balk van een taart-in-taart- of balk-in-taart-diagram, als percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). Schrijf **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeelde). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het mogelijk om aangepaste objecten naar string te converteren. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Opmerkingen

1) Zie samenvatting en opmerkingen voor ChartSeriesGroupCollection klasse en CombinableSeriesTypesGroup enum. 2) Een groep series bevat enkele series-eigenschappen die gemeenschappelijk zijn voor elke serie in de groep (\"series group properties\"). \"Series group properties\" in [ChartSeriesGroup](./) klasse is lees/schrijf. Elke \"series group properties\" kan een alleen-lezen projectie hebben in [ChartSeries](../chartseries/) klasse. 

## Zie ook

* Klasse [IChartSeriesGroup](../ichartseriesgroup/)
* Klasse [IDOMObject](../../aspose.slides/idomobject/)
* Naamruimte [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)