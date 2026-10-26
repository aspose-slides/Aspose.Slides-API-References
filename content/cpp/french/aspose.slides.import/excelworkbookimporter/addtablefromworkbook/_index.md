---
title: AddTableFromWorkbook()
second_title: Référence de l'API Aspose.Slides pour C++
description: Récupère un tableau à partir du classeur Excel spécifié et l'ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées.
type: docs
weight: 14
url: /fr/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) method


Récupère un tableau à partir du classeur [Excel](../../../aspose.slides.excel/) spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La collection de formes à laquelle le tableau sera ajouté. |
| x | **float** | La coordonnée X pour positionner le tableau. |
| y | **float** | La coordonnée Y pour positionner le tableau. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Le classeur [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | Le nom de la feuille de calcul contenant le tableau. |
| cellRange | [System::String](../../../system/string/) | La plage de cellules qui définit le tableau (par exemple, \"A1:D10\"). |

### Return Value

Le tableau qui a été ajouté à la collection de formes.
## Remarques




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) method


Récupère un tableau à partir du fichier classeur [Excel](../../../aspose.slides.excel/) spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La collection de formes à laquelle le tableau sera ajouté. |
| x | **float** | La coordonnée X pour positionner le tableau. |
| y | **float** | La coordonnée Y pour positionner le tableau. |
| workbookPath | [System::String](../../../system/string/) | Le chemin vers le fichier classeur [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | Le nom de la feuille de calcul contenant le tableau. |
| cellRange | [System::String](../../../system/string/) | La plage de cellules qui définit le tableau (par exemple, \"A1:D10\"). |

### Return Value

Le tableau qui a été ajouté à la collection de formes.
## Remarques




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) method


Récupère un tableau à partir du fichier classeur [Excel](../../../aspose.slides.excel/) spécifié et l’ajoute à la fin de la collection de formes donnée aux coordonnées spécifiées.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La collection de formes à laquelle le tableau sera ajouté. |
| x | **float** | La coordonnée X pour positionner le tableau. |
| y | **float** | La coordonnée Y pour positionner le tableau. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flux contenant les données du classeur. |
| worksheetName | [System::String](../../../system/string/) | Le nom de la feuille de calcul contenant le tableau. |
| cellRange | [System::String](../../../system/string/) | La plage de cellules qui définit le tableau (par exemple, \"A1:D10\"). |

### Return Value

Le tableau qui a été ajouté à la collection de formes.
## Remarques




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITable](../../../aspose.slides/itable/)
* Classe [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Classe [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Classe [String](../../../system/string/)
* Classe [ExcelWorkbookImporter](../)
* Classe [Stream](../../../system.io/stream/)
* Espace de noms [Aspose::Slides::Import](../../)
* Bibliothèque [Aspose.Slides](../../../)