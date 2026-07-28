---
title: ChartData
second_title: Aspose.Slides for C++ API Referencia
description: A diagram ábrázolásához használt adatokat képviseli.
type: docs
weight: 118
url: /hu/aspose.slides.charts/chartdata/
---
## ChartData osztály

Képviseli a diagram ábrázolásához használt adatokat.

```cpp
class ChartData : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                  public Aspose::Slides::Charts::IChartData
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Összehasonlítja az objektumokat a C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja a referenciatípusú objektumokat C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Összehasonlítja az értéktípusú objektumokat C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Utánozza a C# stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekintendő, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Utánozza a C# stílusú lebegőpontos összehasonlítást, ahol a két NaN egyenlőnek tekintendő, még akkor is, ha az IEC 60559:1989 szerint a NaN nem egyenlő semmilyen értékkel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső célokra. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() override | Lekéri az elsődleges kategóriákat (vagy az elsődleges és másodlagos kategóriákat is, ha a [ChartData::set_UseSecondaryCategories](./set_usesecondarycategories/) hamisra van állítva). Írásvédett [IChartCategoryCollection](../ichartcategorycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) override | Visszaadja a megadott indexű elsődleges kategóriát. Ha [get_UseSecondaryCategories](./get_usesecondarycategories/) hamis, akkor az összes kategória közül adja vissza. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() override | Lekéri a cellagyárat a diagram sorozatokhoz vagy kategóriákhoz használt cellák létrehozásához. Írásvédett [IChartDataWorkbook](../ichartdataworkbook/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | Visszaadja a megadott indexű sorozatot. |
| [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() override | Külső munkafüzet útvonalat reprezentál, ha külső adatforrás, egyébként null |
| [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() override | Lekéri a beágyazott munkafüzet típusát. [WorkbookType::NotDefined](../workbooktype/)-t ad vissza, ha a [ChartData::get_DataSourceType](./get_datasourcetype/) [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/). Írásvédett [WorkbookType](../workbooktype/). |
| [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() override | A diagram adatforrását reprezentálja |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() override | Lekéri a másodlagos kategóriákat, ha [ChartData::get_UseSecondaryCategories](./get_usesecondarycategories/) igaz. Írásvédett [IChartCategoryCollection](../ichartcategorycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) override | Visszaadja a megadott indexű másodlagos kategóriát. Ha [get_UseSecondaryCategories](./get_usesecondarycategories/) hamis, akkor [ChartData::get_SecondaryCategories](./get_secondarycategories/) null. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() override | Lekéri a sorozatokat. Írásvédett [IChartSeriesCollection](../ichartseriescollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) override | Visszaadja a megadott indexű sorozatcsoportot. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() override | Lekéri a sorozatcsoportokat. Írásvédett [IChartSeriesGroupCollection](../ichartseriesgroupcollection/). |
| **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() override | Ha hamisra van állítva, akkor a [ChartData::get_SecondaryCategories](./get_secondarycategories/) nullt ad vissza, és a [ChartData::get_Categories](./get_categories/) adatait használja mind az elsődleges, mind a másodlagos sorozathoz. Ha igazra van állítva, akkor a [ChartData::get_SecondaryCategories](./get_secondarycategories/) adatait használja a másodlagos sorozathoz, a [ChartData::get_Categories](./get_categories/) adatait pedig az elsődleges sorozathoz. Írás **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz társított referencia számláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi az egyedi objektumok hash-elését. |
| [System::String](../../system/string/) [GetRange](./getrange/)() override | Lekéri a diagram adat tartományt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | Megvalósítja a C# lock() utasítást zároláshoz. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásával történő létrehozását. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Értékadási operátor. Valójában nem másol semmit, csak új objektumot inicializál és lehetővé teszi az alosztályok másolásával történő létrehozását. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() override | A belső [Excel](../../aspose.slides.excel/) munkafüzetet egy memóriafolyamba írja. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Összehasonlítja az objektumokat referencia szerint. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Összehasonlítja az objektumokat referencia szerint. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia-összehasonlítja az értéktípusú objektumot a nullptr-tel. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterlánc és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja karakterláncok esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referencia számlálót a megadott értékkel. |
| void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) override | Ha hamisra van állítva, akkor a [ChartData::get_SecondaryCategories](./get_secondarycategories/) nullt ad vissza, és a [ChartData::get_Categories](./get_categories/) adatait használja mind az elsődleges, mind a másodlagos sorozathoz. Ha igazra van állítva, akkor a [ChartData::get_SecondaryCategories](./get_secondarycategories/) adatait használja a másodlagos sorozathoz, a [ChartData::get_Categories](./get_categories/) adatait pedig az elsődleges sorozathoz. Írható **bool**. |
| void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) override | Beállítja a külső munkafüzét adatforrásként a diagramhoz. A [Chart](../chart/) adatok a cél munkafüzetről frissülnek. |
| void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) override | Beállítja a külső munkafüzét adatforrásként a diagramhoz. |
| void [SetRange](./setrange/)([System::String](../../system/string/)) override | Beállítja a diagram adat tartományt. A sorozatok és kategóriák az új adat tartomány alapján frissülnek. Ha a sorozatok száma az adat tartományban nagyobb, mint a diagram adatban lévő sorozatok száma, akkor további sorozatok a jelenlegi gyűjtemény utolsó sorozatával megegyező típussal kerülnek a gyűjtemény végére. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Az n-edik sablonargumentumot gyenge mutatóra (nem megosztott) állítja. Lehetővé teszi a mutatók átkapcsolását konténerekben gyenge módra. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referencia számláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [SwitchRowColumn](./switchrowcolumn/)() override | Az adatcserét az tengelyen végzi. Az X tengelyen ábrázolt adatok az Y tengelyre, és fordítva. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Megvalósítja a C# typeof([System.Object](../../system/object/)) konstrukciót. |
| void [Unlock](../../system/object/unlock/)() | Megvalósítja a C# lock() utasítás feloldását. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) őrző objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referencia számlálót. Nem szabad közvetlenül hívni; helyette használjon okos mutatókat vagy ThisProtector-t. |
| void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) override | Inicializálja a belső [Excel](../../aspose.slides.excel/) munkafüzetet a felhasználó által megadott értékkel. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [DomObject](../../aspose.slides/domobject/)
* Osztály [IChartData](../ichartdata/)
* Névtér [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)