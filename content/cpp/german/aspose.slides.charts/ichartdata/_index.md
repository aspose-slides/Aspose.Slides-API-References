---
title: IChartData
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt die für die Diagrammdarstellung verwendeten Daten dar.
type: docs
weight: 651
url: /de/aspose.slides.charts/ichartdata/
---
## IChartData Klasse

Represents data used for a chart plotting.

```cpp
class IChartData : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() | Ruft die primären Kategorien ab (oder sowohl primäre als auch sekundäre Kategorien, wenn [IChartData::set_UseSecondaryCategories](./set_usesecondarycategories/) auf false gesetzt ist). Schreibgeschützt [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) | Gibt die primäre Kategorie am angegebenen Index zurück. Wenn [get_UseSecondaryCategories](./get_usesecondarycategories/) false ist, wird aus allen Kategorien abgerufen. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() | Ruft die Zellenfabrik ab, um Zellen für Diagrammreihen oder -kategorien zu erstellen. Schreibgeschützt [IChartDataWorkbook](../ichartdataworkbook/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | Gibt die Reihe am angegebenen Index zurück. |
| virtual [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() | Stellt die Datenquelle des Diagramms dar |
| virtual [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() | Ruft den Typ der eingebetteten Arbeitsmappe ab. Gibt [WorkbookType::NotDefined](../workbooktype/) zurück, wenn [IChartData::get_DataSourceType](./get_datasourcetype/) [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/) ist. Schreibgeschützt [WorkbookType](../workbooktype/). |
| virtual [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() | Stellt den Pfad einer externen Arbeitsmappe dar, falls die Datenquelle extern ist, sonst null. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() | Ruft die sekundären Kategorien ab, falls [IChartData::get_UseSecondaryCategories](./get_usesecondarycategories/) true ist. Schreibgeschützt [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) | Gibt die sekundäre Kategorie am angegebenen Index zurück. Wenn [get_UseSecondaryCategories](./get_usesecondarycategories/) false ist, ist [IChartData::get_SecondaryCategories](./get_secondarycategories/) null. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() | Ruft die Reihen ab. Schreibgeschützt [IChartSeriesCollection](../ichartseriescollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) | Gibt die Gruppe von Reihen am angegebenen Index zurück. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() | Ruft die Gruppen von Reihen ab. Schreibgeschützt [IChartSeriesGroupCollection](../ichartseriesgroupcollection/). |
| virtual **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() | Ist auf false gesetzt, gibt [IChartData::get_SecondaryCategories](./get_secondarycategories/) null zurück und die Daten in [IChartData::get_Categories](./get_categories/) werden sowohl für primäre als auch sekundäre Reihen verwendet. Ist auf true gesetzt, werden die Daten in [IChartData::get_SecondaryCategories](./get_secondarycategories/) für sekundäre Reihen und die Daten in [IChartData::get_Categories](./get_categories/) für primäre Reihen verwendet. Lese **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ruft die Referenzzähler-Datenstruktur ab, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual [System::String](../../system/string/) [GetRange](./getrange/)() | Ruft den Diagrammdatenbereich ab. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ruft den tatsächlichen Typ des Objekts ab. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Überprüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-`is`-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erzeugt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert eigentlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert eigentlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() | Schreibt die intern enthaltene [Excel](../../aspose.slides.excel/)-Arbeitsmappe in einen In-Memory-Stream. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte anhand ihrer Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte anhand ihrer Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsam genutzten Referenzzähler um den angegebenen Wert. |
| virtual void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) | Ist auf false gesetzt, gibt [IChartData::get_SecondaryCategories](./get_secondarycategories/) null zurück und die Daten in [IChartData::get_Categories](./get_categories/) werden sowohl für primäre als auch sekundäre Reihen verwendet. Ist auf true gesetzt, werden die Daten in [IChartData::get_SecondaryCategories](./get_secondarycategories/) für sekundäre Reihen und die Daten in [IChartData::get_Categories](./get_categories/) für primäre Reihen verwendet. Schreibe **bool**. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) | Setzt eine externe Arbeitsmappe als Datenquelle für das Diagramm. [Chart](../chart/)-Daten werden aus der Zielarbeitsmappe aktualisiert. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) | Setzt eine externe Arbeitsmappe als Datenquelle für das Diagramm. |
| virtual void [SetRange](./setrange/)([System::String](../../system/string/)) | Setzt den Diagrammdatenbereich. Reihen und Kategorien werden basierend auf dem neuen Datenbereich aktualisiert. Wenn die Anzahl der Reihen im Datenbereich größer ist als die Anzahl der Reihen in den Diagrammdaten, werden zusätzliche Reihen mit dem gleichen Typ wie die letzte Reihe der aktuellen Sammlung am Ende der Sammlung hinzugefügt. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument als schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ruft den aktuellen Wert des gemeinsam genutzten Referenzzählers ab. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsam genutzten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsam genutzten Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual void [SwitchRowColumn](./switchrowcolumn/)() | Vertauscht die Daten über die Achse. Daten, die auf der X-Achse dargestellt werden, werden auf die Y-Achse verschoben und umgekehrt. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht das Konvertieren benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) | Initialisiert die intern enthaltene [Excel](../../aspose.slides.excel/)-Arbeitsmappe mit dem vom Benutzer angegebenen Wert. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [Aspose::Slides::Charts](../)
* Bibliothek [Aspose.Slides](../../)