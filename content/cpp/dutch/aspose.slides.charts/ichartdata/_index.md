---
title: IChartData
second_title: Aspose.Slides voor C++ API-referentie
description: Vertegenwoordigt gegevens die gebruikt worden voor het plotten van een diagram.
type: docs
weight: 651
url: /nl/aspose.slides.charts/ichartdata/
---
## IChartData klasse


Represents data used for a chart plotting.

```cpp
class IChartData : public virtual System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekommavergelijking waarbij twee NaN's als gelijk worden beschouwd, ook al is volgens IEC 60559:1989 NaN niet gelijk aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() | Haalt de primaire categorieën op (of zowel primaire als secundaire categorieën als [IChartData::set_UseSecondaryCategories](./set_usesecondarycategories/) op false staat). Alleen-lezen [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) | Returned de primaire categorie op de opgegeven index. Als [get_UseSecondaryCategories](./get_usesecondarycategories/) false is, haal op uit alle categorieën. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() | Haalt de cellen-fabriek op om cellen te maken die gebruikt worden voor chart-series of categorieën. Alleen-lezen [IChartDataWorkbook](../ichartdataworkbook/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | Returned de series op de opgegeven index. |
| virtual [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() | Stelt de gegevensbron van de chart voor. |
| virtual [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() | Haalt het type op van de ingebedde werkmap. Retourneert [WorkbookType::NotDefined](../workbooktype/) als [IChartData::get_DataSourceType](./get_datasourcetype/) [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/) is. Alleen-lezen [WorkbookType](../workbooktype/). |
| virtual [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() | Stelt het pad naar een externe werkmap voor als de gegevensbron extern is, anders null. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() | Haalt de secundaire categorieën op als [IChartData::get_UseSecondaryCategories](./get_usesecondarycategories/) true is. Alleen-lezen [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) | Returned de secundaire categorie op de opgegeven index. Als [get_UseSecondaryCategories](./get_usesecondarycategories/) false is, is [IChartData::get_SecondaryCategories](./get_secondarycategories/) null. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() | Haalt de series op. Alleen-lezen [IChartSeriesCollection](../ichartseriescollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) | Returned de groep series op de opgegeven index. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() | Haalt de groepen series op. Alleen-lezen [IChartSeriesGroupCollection](../ichartseriesgroupcollection/). |
| virtual **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() | Indien ingesteld op false, retourneert [IChartData::get_SecondaryCategories](./get_secondarycategories/) null en worden gegevens in [IChartData::get_Categories](./get_categories/) zowel voor primaire als secundaire series gebruikt. Indien ingesteld op true, worden gegevens in [IChartData::get_SecondaryCategories](./get_secondarycategories/) gebruikt voor secundaire series en gegevens in [IChartData::get_Categories](./get_categories/) voor primaire series. Lezen **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-gegevensstructuur op die aan het object gekoppeld is. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hash van aangepaste objecten mogelijk. |
| virtual [System::String](../../system/string/) [GetRange](./getrange/)() | Haalt het gegevensbereik van de chart op. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/) aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert vergrendeling van C# lock() statement. Direct aanroepen of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne gegevensstructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert niets, initialiseert alleen een nieuw object en maakt kopie-construeren van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, initialiseert alleen een nieuw object en maakt kopie-construeren van subklassen mogelijk. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() | Schrijft de intern aanwezige [Excel](../../aspose.slides.excel/) werkmap naar een geheugenstroom. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) | Indien ingesteld op false, retourneert [IChartData::get_SecondaryCategories](./get_secondarycategories/) null en worden gegevens in [IChartData::get_Categories](./get_categories/) zowel voor primaire als secundaire series gebruikt. Indien ingesteld op true, worden gegevens in [IChartData::get_SecondaryCategories](./get_secondarycategories/) gebruikt voor secundaire series en gegevens in [IChartData::get_Categories](./get_categories/) voor primaire series. Schrijf **bool**. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) | Stelt een externe werkmap in als gegevensbron voor de chart. [Chart](../chart/) gegevens zullen worden bijgewerkt vanuit de doelwerkmap. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) | Stelt een externe werkmap in als gegevensbron voor de chart. |
| virtual void [SetRange](./setrange/)([System::String](../../system/string/)) | Stel het gegevensbereik van de chart in. Series en categorieën worden bijgewerkt op basis van het nieuwe gegevensbereik. Als het aantal series in het gegevensbereik groter is dan het aantal series in de chart-gegevens, dan worden extra series met hetzelfde type als de laatste serie in de huidige collectie aan het einde van de collectie toegevoegd. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stel het n'te sjabloonargument in op een zwakke pointer (in plaats van een gedeelde). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual void [SwitchRowColumn](./switchrowcolumn/)() | Wisselt de gegevens over de as. Gegevens die op de X-as worden gechart, worden verplaatst naar de Y-as en omgekeerd. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert ontgrendeling van C# lock() statement. Direct aanroepen of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) | Initialiseert de intern aanwezige [Excel](../../aspose.slides.excel/)-werkmap met door de gebruiker gespecificeerde waarde. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijeft alle interne gegevensstructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [Aspose::Slides::Charts](../)
* Bibliotheek [Aspose.Slides](../../)