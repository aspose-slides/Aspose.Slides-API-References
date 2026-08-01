---
title: IChartSeriesGroup
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een groep series voor.
type: docs
weight: 846
url: /nl/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup klasse

Representeert een groep van series.

```cpp
class IChartSeriesGroup : public Aspose::Slides::Charts::IChartComponent
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | Specificeert hoe de bubbelgroottewaarden worden weergegeven op het bubbel-diagram. Lees [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | Specificeert de schaalfactor voor het bubbel-diagram (kan tussen 0 en 300 procent van de standaardgrootte liggen). Lees **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Geeft het diagram terug. Alleen-lezen [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | Geeft de diagramreeks in de groep terug op de gespecificeerde index. |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | Specificeert de grootte van het gat in een donut-diagram (kan tussen 10 en 90 procent van de grootte van het plotgebied liggen). Lees **uint8_t**. |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | Haalt de hoek van het eerste taart- of donut-diagramsegment op, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Lees **uint16_t**. |
| virtual **uint16_t** [get_GapDepth](./get_gapdepth/)() | Geeft de afstand terug, als een percentage van de markerbreedte, tussen de gegevensreeksen in een 3D-diagram. Lees **uint16_t**. |
| virtual **uint16_t** [get_GapWidth](./get_gapwidth/)() | Specificeert de ruimte tussen balk- of kolomclusters, als een percentage van de balk- of kolombreedte. Lees **uint16_t**. |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | Waar als het diagram reekslijnen heeft. Toegepast op gestapelde balk- en OfPie-diagrammen. Lees **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() | Specificeert het HiLowLines-formaat. HiLowLines toegepast met HiLowClose, OpenHiLowClose, VolumeHiLowClose en VolumeOpenHiLowClose-diagramtypen. |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | Specificeert dat elke datamarker in de reeks een andere kleur heeft. Lees **bool**. |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | Specificeert hoeveel balken en kolommen op 2D-diagrammen overlappen, als een percentage (van -100% tot 100%). |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | Specificeert hoe te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-van-taart- of balk-van-taart-diagram. Lees [PieSplitType](../piesplittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | De aangepaste splitsinformatie voor een taart-van-taart- of balk-van-taart-diagram met een aangepaste splitsing. Geeft het datapunten terug dat getekend moet worden in de tweede taart of balk in een taart-van-taart- of balk-van-taart-diagram op basis van index. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | De aangepaste splitsinformatie voor een taart-van-taart- of balk-van-taart-diagram met een aangepaste splitsing. Bevat datapunten die getekend moeten worden in de tweede taart of balk in een taart-van-taart- of balk-van-taart-diagram. Alleen-lezen [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/). |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | Specificeert een waarde die gebruikt wordt om te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-van-taart- of balk-van-taart-diagram. Wordt gebruikt samen met de eigenschap PieSplitBy. Lees **double**. |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | Geeft aan of de reeksen van deze groep worden geplot op de secundaire as. Alleen-lezen **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Geeft de presentatie terug. Alleen-lezen [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | Specificeert de grootte van de tweede taart of balk van een taart-van-taart- of balk-van-taart-diagram, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). Lees **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() | Geeft een alleen-lezen collectie van diagramreeksen terug. Alleen-lezen [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Geeft de basisslide terug. Alleen-lezen [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() | Geeft een type van deze serie-groep terug. Alleen-lezen [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() | Biedt toegang tot op/af-balken van een lijn- of aandelen-diagram. Alleen-lezen [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) | Haalt het element op op de gespecificeerde index. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van de C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het vergrendelen van de C# lock()-statement. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets, initialiseert slechts een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toekenningsoperator. Kopieert niets, initialiseert slechts een nieuw object en maakt kopieerconstructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) | Specificeert hoe de bubbelgroottewaarden worden weergegeven op het bubbel-diagram. Schrijf [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) | Specificeert de schaalfactor voor het bubbel-diagram (kan tussen 0 en 300 procent van de standaardgrootte liggen). Schrijf **int32_t**. |
| virtual void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) | Specificeert de grootte van het gat in een donut-diagram (kan tussen 10 en 90 procent van de grootte van het plotgebied liggen). Schrijf **uint8_t**. |
| virtual void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) | Stelt de hoek van het eerste taart- of donut-diagramsegment in, in graden (met de klok mee vanaf boven, van 0 tot 360 graden). Schrijf **uint16_t**. |
| virtual void [set_GapDepth](./set_gapdepth/)(**uint16_t**) | Stelt de afstand in, als een percentage van de markerbreedte, tussen de gegevensreeksen in een 3D-diagram. Schrijf **uint16_t**. |
| virtual void [set_GapWidth](./set_gapwidth/)(**uint16_t**) | Specificeert de ruimte tussen balk- of kolomclusters, als een percentage van de balk- of kolombreedte. Schrijf **uint16_t**. |
| virtual void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) | Waar als het diagram reekslijnen heeft. Toegepast op gestapelde balk- en OfPie-diagrammen. Schrijf **bool**. |
| virtual void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) | Specificeert dat elke datamarker in de reeks een andere kleur heeft. Schrijf **bool**. |
| virtual void [set_Overlap](./set_overlap/)(**int8_t**) | Specificeert hoeveel balken en kolommen op 2-D-diagrammen overlappen, als een percentage (van -100% tot 100%). |
| virtual void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) | Specificeert hoe te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-van-taart- of balk-van-taart-diagram. Schrijf [PieSplitType](../piesplittype/). |
| virtual void [set_PieSplitPosition](./set_piesplitposition/)(**double**) | Specificeert een waarde die gebruikt moet worden om te bepalen welke datapunten zich in de tweede taart of balk bevinden in een taart-van-taart- of balk-van-taart-diagram. Wordt gebruikt samen met de eigenschap PieSplitBy. Schrijf **double**. |
| virtual void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) | Specificeert de grootte van de tweede taart of balk van een taart-van-taart- of balk-van-taart-diagram, als een percentage van de grootte van de eerste taart (kan tussen 5 en 200 procent liggen). Schrijf **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'te sjabloonargument in als een zwakke pointer (in plaats van gedeelde). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/))-constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-statement. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Opmerkingen

1) Zie samenvatting en opmerkingen voor ChartSeriesGroupCollection klasse en CombinableSeriesTypesGroup enum. 2) Groep van series bevat enkele serie-eigenschappen die gemeenschappelijk zijn voor elke serie in de groep ("series group properties"). "Series group properties" in [ChartSeriesGroup](../chartseriesgroup/) klasse is lezen/schrijven. Elke "series group properties" kan een alleen-lezen projectie hebben in [ChartSeries](../chartseries/) klasse.

## Zie ook

* Klasse [IChartComponent](../ichartcomponent/)
* Naamruimte [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)