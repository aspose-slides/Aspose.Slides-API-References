---
title: AddChartFromWorkbook()
second_title: Référence API Aspose.Slides pour C++
description: Récupère un graphique à partir du classeur Excel spécifié et l'ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées.
type: docs
weight: 1
url: /fr/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) méthode


Récupère un graphique à partir du classeur [Excel](../../../aspose.slides.excel/) spécifié et l'ajoute à la fin de la collection de formes fournie aux coordonnées indiquées.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La collection de formes à laquelle le graphique sera ajouté. |
| x | **float** | La coordonnée X pour positionner le graphique. |
| y | **float** | La coordonnée Y pour positionner le graphique. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Le classeur [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | Le nom de la feuille de calcul contenant le graphique. |
| chartIndex | **int32_t** | L'index basé sur zéro de la forme graphique à insérer. Cet index peut être obtenu à l'aide de la méthode [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../). |
| embedAllWorkbook | **bool** | Si **true**, le classeur entier sera intégré au graphique ; si **false**, seules les données du graphique seront intégrées. |

### Valeur de retour

Le graphique qui a été ajouté à la collection de formes.
## Remarques



Exemple: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) méthode


Récupère un graphique à partir du classeur [Excel](../../../aspose.slides.excel/) spécifié et l'ajoute à la fin de la collection de formes fournie aux coordonnées indiquées.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La collection de formes à laquelle le graphique sera ajouté. |
| x | **float** | La coordonnée X pour positionner le graphique. |
| y | **float** | La coordonnée Y pour positionner le graphique. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Le classeur [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | Le nom de la feuille de calcul contenant le graphique. |
| chartName | [System::String](../../../system/string/) | Le nom du graphique à ajouter. |
| embedAllWorkbook | **bool** | Si **true**, le classeur entier sera intégré au graphique ; si **false**, seules les données du graphique seront intégrées. |

### Valeur de retour

Le graphique qui a été ajouté à la collection de formes.
## Remarques



Exemple: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();

System::String worksheetName = u"worksheet name";
auto worksheetCharts = wb->GetChartsFromWorksheet(worksheetName);
for (auto&& chart : worksheetCharts)
{
    System::SharedPtr<ISlide> slide = pres->get_Slides()->AddEmptySlide(pres->get_LayoutSlides()->idx_get(0));
    ExcelWorkbookImporter::AddChartFromWorkbook(slide->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chart.get_Key(), false);
}
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String, bool) méthode


Récupère un graphique à partir du classeur [Excel](../../../aspose.slides.excel/) spécifié et l'ajoute à la fin de la collection de formes fournie aux coordonnées indiquées.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La collection de formes à laquelle le graphique sera ajouté. |
| x | **float** | La coordonnée X pour positionner le graphique. |
| y | **float** | La coordonnée Y pour positionner le graphique. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flux contenant les données du classeur. |
| worksheetName | [System::String](../../../system/string/) | Le nom de la feuille de calcul contenant le graphique. |
| chartName | [System::String](../../../system/string/) | Le nom du graphique à ajouter. |
| embedAllWorkbook | **bool** | Si **true**, le classeur entier sera intégré au graphique ; si **false**, seules les données du graphique seront intégrées. |

### Valeur de retour

Le graphique qui a été ajouté à la collection de formes.
## Remarques



Exemple: 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) méthode


Récupère un graphique à partir du classeur [Excel](../../../aspose.slides.excel/) spécifié et l'ajoute à la fin de la collection de formes fournie aux coordonnées indiquées.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La collection de formes à laquelle le graphique sera ajouté. |
| x | **float** | La coordonnée X pour positionner le graphique. |
| y | **float** | La coordonnée Y pour positionner le graphique. |
| workbookPath | [System::String](../../../system/string/) | Le chemin du fichier vers le classeur contenant le graphique. |
| worksheetName | [System::String](../../../system/string/) | Le nom de la feuille de calcul contenant le graphique. |
| chartName | [System::String](../../../system/string/) | Le nom du graphique à ajouter. |
| embedWorkbook | **bool** | Si **true**, le classeur sera intégré au graphique ; si **false**, le graphique référencera le classeur externe. |

### Valeur de retour

Le graphique qui a été ajouté à la collection de formes.
## Remarques



Exemple: 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Class [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Class [String](../../../system/string/)
* Class [ExcelWorkbookImporter](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)