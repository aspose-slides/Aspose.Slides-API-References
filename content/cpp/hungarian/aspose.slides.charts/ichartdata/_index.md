---
title: IChartData
second_title: Aspose.Slides C++ API referencia
description: A diagram ábrázolásához használt adatokat képviseli.
type: docs
weight: 651
url: /hu/aspose.slides.charts/ichartdata/
---
## IChartData osztály


Represents data used for a chart plotting.

```cpp
class IChartData : public virtual System::Object
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objektumokat hasonlít össze C# [Object.Equals](../../system/object/equals/) szemantika szerint. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referencia típusú objektumokat hasonlít össze C# stílusban. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Érték típusú objektumokat hasonlít össze C# stílusban. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-stílusú lebegőpontos összehasonlítást emulál, ahol két NaN egyenlőnek tekinthető, még ha az IEC 60559:1989 szerint a NaN nem egyenlő semmivel, beleértve a NaN-t is. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Csak belső használatra. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() | Lekéri az elsődleges kategóriákat (vagy az elsődleges és másodlagos kategóriákat, ha a [IChartData::set_UseSecondaryCategories](./set_usesecondarycategories/) hamisra van állítva). Csak olvasható [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) | Visszaadja a megadott indexű elsődleges kategóriát. Ha a [get_UseSecondaryCategories](./get_usesecondarycategories/) hamis, akkor az összes kategória közül adja vissza. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() | Lekéri a cellagyárat a diagram sorozatokhoz vagy kategóriákhoz használt cellák létrehozásához. Csak olvasható [IChartDataWorkbook](../ichartdataworkbook/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | Visszaadja a megadott indexű sorozatot. |
| virtual [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() | A diagram adatforrását képviseli. |
| virtual [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() | Lekéri a beágyazott munkafüzet típusát. [WorkbookType::NotDefined](../workbooktype/) értéket ad vissza, ha a [IChartData::get_DataSourceType](./get_datasourcetype/) [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/). Csak olvasható [WorkbookType](../workbooktype/). |
| virtual [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() | Különálló munkafüzet útvonalát képviseli, ha az adatforrás külső, egyébként null. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() | Lekéri a másodlagos kategóriákat, ha a [IChartData::get_UseSecondaryCategories](./get_usesecondarycategories/) igaz. Csak olvasható [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) | Visszaadja a megadott indexű másodlagos kategóriát. Ha a [get_UseSecondaryCategories](./get_usesecondarycategories/) hamis, akkor a [IChartData::get_SecondaryCategories](./get_secondarycategories/) null. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() | Lekéri a sorozatot. Csak olvasható [IChartSeriesCollection](../ichartseriescollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) | Visszaadja a megadott indexű sorozatcsoportot. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() | Lekéri a sorozatcsoportokat. Csak olvasható [IChartSeriesGroupCollection](../ichartseriesgroupcollection/). |
| virtual **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() | Ha hamisra van állítva, akkor a [IChartData::get_SecondaryCategories](./get_secondarycategories/) null értéket ad vissza, és a [IChartData::get_Categories](./get_categories/) adatok mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. Ha igazra van állítva, akkor a [IChartData::get_SecondaryCategories](./get_secondarycategories/) adatok a másodlagos sorozatokhoz, a [IChartData::get_Categories](./get_categories/) adat pedig az elsődleges sorozatokhoz használatosak. Csak **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Lekéri az objektumhoz kapcsolódó referenciaszámláló adatstruktúrát. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | A C# [Object.GetHashCode()](../../system/object/gethashcode/) metódus analógiája. Lehetővé teszi az egyedi objektumok hash-elését. |
| virtual [System::String](../../system/string/) [GetRange](./getrange/)() | Lekéri a diagram adat-tartományt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Lekéri az objektum tényleges típusát. A C# [System.Object.GetType()](../../system/object/gettype/) hívás analógiája. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ellenőrzi, hogy az objektum a targetType által leírt típus példánya-e. A C# 'is' operátor analógiája. |
| void [Lock](../../system/object/lock/)() | A C# lock() utasítást valósítja meg zároláshoz. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentry objektumot. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | A C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metódus analógiája. Lehetővé teszi egyedi típusok klónozását. |
|  [Object](../../system/object/object/)() | Létrehozza az objektumot. Inicializálja az összes belső adatstruktúrát. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Másoló konstruktor. Valójában semmit sem másol, csak inicializál egy új objektumot, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Hozzárendelési operátor. Valójában semmit sem másol, csak inicializál egy új objektumot, és lehetővé teszi az alosztályok másoló konstrukcióját. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() | Beírja a belsőleg tartalmazott [Excel](../../aspose.slides.excel/) munkafüzetet egy memóriában tárolt adatfolyamba. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Objektumokat összehasonlít referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Objektumokat összehasonlít referenciával. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referencia-összehasonlítást végez érték típusú objektummal a nullptr érték ellen. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja string és nullptr esetére. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | A [Object::ReferenceEquals](../../system/object/referenceequals/) specializációja stringek esetére. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Csökkenti a megosztott referenciaszámlálót a megadott értékkel. |
| virtual void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) | Ha hamisra van állítva, akkor a [IChartData::get_SecondaryCategories](./get_secondarycategories/) null visszatér, és a [IChartData::get_Categories](./get_categories/) adat mind az elsődleges, mind a másodlagos sorozatokhoz használatos. Ha igazra állítja, akkor a [IChartData::get_SecondaryCategories](./get_secondarycategories/) adat a másodlagos sorozatokhoz, a [IChartData::get_Categories](./get_categories/) adat pedig az elsődleges sorozatokhoz használatos. Írja **bool** értéket. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) | Külső munkafüzetet állít be a diagram adatforrásaként. A [Chart](../chart/) adat frissülni fog a célmunkafüzetből. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) | Külső munkafüzetet állít be a diagram adatforrásaként. |
| virtual void [SetRange](./setrange/)([System::String](../../system/string/)) | Beállítja a diagram adat-tartományt. A sorozatok és kategóriák az új adat-tartomány alapján frissülnek. Ha az adat-tartományban lévő sorozatok száma nagyobb, mint a diagram adatban lévő sorozatok száma, akkor további sorozatok, az aktuális gyűjtemény utolsó sorozatának típusával megegyező típusú sorozatok kerülnek a gyűjtemény végére. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Beállítja az n-edik sablonargumentumot gyenge mutatóként (nem megosztott). Lehetővé teszi a mutatók átváltását gyengére a tárolókban. |
| int [SharedCount](../../system/object/sharedcount/)() const | Lekéri a megosztott referenciaszámláló jelenlegi értékét. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Növeli a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Csökkenti és visszaadja a megosztott referenciaszámlálót. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual void [SwitchRowColumn](./switchrowcolumn/)() | Az adatot az tengelyek mentén cseréli. Az X tengelyen megjelenített adatok az Y tengelyre, és fordítva mozdulnak. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | A C# [Object.ToString()](../../system/object/tostring/) metódus analógiája. Lehetővé teszi egyedi objektumok stringgé konvertálását. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | A C# typeof([System.Object](../../system/object/)) konstrukciót valósítja meg. |
| void [Unlock](../../system/object/unlock/)() | A C# lock() utasítás feloldását valósítja meg. Hívja közvetlenül vagy használja a [LockContext](../../system/lockcontext/) sentry objektumot. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Növeli a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Csökkenti a gyenge referenciaszámlálót. Nem szabad közvetlenül meghívni; használjon okos mutatókat vagy ThisProtector-t. |
| virtual void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) | Inicializálja a belsőleg tartalmazott [Excel](../../aspose.slides.excel/) munkafüzetet a felhasználó által megadott értékkel. |
| virtual  [~Object](../../system/object/~object/)() | Megsemmisíti az objektumot. Felszabadítja az összes belső adatstruktúrát. |

## Lásd még

* Osztály [Object](../../system/object/)
* Névtere [Aspose::Slides::Charts](../)
* Könyvtár [Aspose.Slides](../../)