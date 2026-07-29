---
title: IChartData
second_title: Aspose.Slides för C++ API-referens
description: Representerar data som används för att plotta ett diagram.
type: docs
weight: 651
url: /sv/aspose.slides.charts/ichartdata/
---
## IChartData klass

Representerar data som används för att rita ett diagram.

```cpp
class IChartData : public virtual System::Object
```

## Metoder

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/) semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C# stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypsobjekt i C# stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() | Hämtar de primära kategorierna (eller både primära och sekundära kategorier om [IChartData::set_UseSecondaryCategories](./set_usesecondarycategories/) är satt till false). Skrivskyddad [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) | Returnerar den primära kategorin vid angivet index. Om [get_UseSecondaryCategories](./get_usesecondarycategories/) är false, hämta bland alla kategorier. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() | Hämtar cellfabriken för att skapa celler som används för diagramserier eller kategorier. Skrivskyddad [IChartDataWorkbook](../ichartdataworkbook/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | Returnerar serien vid angivet index. |
| virtual [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() | Representerar diagrammets datakälla |
| virtual [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() | Hämtar typen av den inbäddade arbetsboken. Returnerar [WorkbookType::NotDefined](../workbooktype/) om [IChartData::get_DataSourceType](./get_datasourcetype/) är [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/). Skrivskyddad [WorkbookType](../workbooktype/). |
| virtual [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() | Representerar sökväg till extern arbetsbok om datakällan är extern, annars null |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() | Hämtar de sekundära kategorierna om [IChartData::get_UseSecondaryCategories](./get_usesecondarycategories/) är true. Skrivskyddad [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) | Returnerar den sekundära kategorin vid angivet index. Om [get_UseSecondaryCategories](./get_usesecondarycategories/) är false, är [IChartData::get_SecondaryCategories](./get_secondarycategories/) null. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() | Hämtar serierna. Skrivskyddad [IChartSeriesCollection](../ichartseriescollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) | Returnerar gruppen av serier vid angivet index. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() | Hämtar grupper av serier. Skrivskyddad [IChartSeriesGroupCollection](../ichartseriesgroupcollection/). |
| virtual **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() | Om satt till false returnerar [IChartData::get_SecondaryCategories](./get_secondarycategories/) null och data i [IChartData::get_Categories](./get_categories/) används både för primära och sekundära serier. Om satt till true används data i [IChartData::get_SecondaryCategories](./get_secondarycategories/) för sekundära serier och data i [IChartData::get_Categories](./get_categories/) för primära serier. Läs **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual [System::String](../../system/string/) [GetRange](./getrange/)() | Hämtar diagrammets dataområde. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satss låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, bara initierar ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() | Skriver den internt innehållande [Excel](../../aspose.slides.excel/)-arbetsboken till en minnesström. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför värdeobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) | Om satt till false returnerar [IChartData::get_SecondaryCategories](./get_secondarycategories/) null och data i [IChartData::get_Categories](./get_categories/) används både för primära och sekundära serier. Om satt till true används data i [IChartData::get_SecondaryCategories](./get_secondarycategories/) för sekundära serier och data i [IChartData::get_Categories](./get_categories/) för primära serier. Skriv **bool**. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) | Sätter extern arbetsbok som datakälla för diagrammet. [Chart](../chart/)-data kommer att uppdateras från målarbetsboken. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) | Sätter extern arbetsbok som datakälla för diagrammet. |
| virtual void [SetRange](./setrange/)([System::String](../../system/string/)) | Sätt diagrammets dataområde. Serier och kategorier kommer att uppdateras baserat på det nya dataområdet. Om antalet serier i dataområdet är större än antalet serier i diagrammets data läggs ytterligare serier med samma typ som den sista serien i den aktuella samlingen till i slutet av samlingen. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te templatargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde av delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual void [SwitchRowColumn](./switchrowcolumn/)() | Byt data över axeln. Data som diagrammeras på X-axeln flyttas till Y-axeln och vice versa. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) | Initierar den internt innehållande [Excel](../../aspose.slides.excel/)-arbetsboken med ett av användaren specificerat värde. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |
## Se även

* Klass [Object](../../system/object/)
* Namnrymd [Aspose::Slides::Charts](../)
* Bibliotek [Aspose.Slides](../../)