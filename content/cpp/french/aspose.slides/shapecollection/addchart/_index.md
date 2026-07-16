---
title: AddChart()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée un nouveau graphique, l'initialise avec des données de séries d'exemple et des paramètres, puis l'ajoute à la fin de la collection de formes.
type: docs
weight: 66
url: /fr/aspose.slides/shapecollection/addchart/
---
## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float) method

Crée un nouveau graphique, l'initialise avec des données de séries d'exemple et des paramètres, puis l'ajoute à la fin de la collection de formes.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Le type de graphique à ajouter. |
| x | **float** | La coordonnée x du nouveau graphique, en points. |
| y | **float** | La coordonnée y du nouveau graphique, en points. |
| width | **float** | La largeur du graphique, en points. |
| height | **float** | La hauteur du graphique, en points. |

### Valeur de retour

Le [Charts::IChart](../../../aspose.slides.charts/ichart/) nouvellement créé.

## Remarques

L'exemple suivant montre comment créer un graphique dans PowerPoint [Presentation](../../presentation/). 
```cpp
// Instancie la classe Presentation qui représente un fichier PPTX
auto pres = System::MakeObject<Presentation>();
// Accède à la première diapositive
auto slide = pres->get_Slides()->idx_get(0);
// Ajoute un graphique avec ses données par défaut
System::SharedPtr<IChart> chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 0.0f, 0.0f, 500.0f, 500.0f);
// Définit le titre du graphique
auto chartTitle = chart->get_ChartTitle();
chartTitle->AddTextFrameForOverriding(u"Sample Title");
chartTitle->get_TextFrameForOverriding()->get_TextFrameFormat()->set_CenterText(NullableBool::True);
chartTitle->set_Height(20.0f);
chart->set_HasTitle(true);

auto chartData = chart->get_ChartData();
auto categories = chartData->get_Categories();
auto chartSeries = chartData->get_Series();
// Définit la première série pour afficher les valeurs
chartSeries->idx_get(0)->get_Labels()->get_DefaultDataLabelFormat()->set_ShowValue(true);
// Définit l'index pour la feuille de données du graphique
int32_t defaultWorksheetIndex = 0;
// Obtient la feuille de calcul des données du graphique
System::SharedPtr<IChartDataWorkbook> fact = chartData->get_ChartDataWorkbook();
// Supprime les séries et catégories générées par défaut
chartSeries->Clear();
categories->Clear();
int32_t s = chartSeries->get_Count();
s = categories->get_Count();
// Ajoute de nouvelles séries
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 1, System::ExplicitCast<System::Object>(u"Series 1")), chart->get_Type());
chartSeries->Add(fact->GetCell(defaultWorksheetIndex, 0, 2, System::ExplicitCast<System::Object>(u"Series 2")), chart->get_Type());
// Ajoute de nouvelles catégories
categories->Add(fact->GetCell(defaultWorksheetIndex, 1, 0, System::ExplicitCast<System::Object>(u"Caetegoty 1")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 2, 0, System::ExplicitCast<System::Object>(u"Caetegoty 2")));
categories->Add(fact->GetCell(defaultWorksheetIndex, 3, 0, System::ExplicitCast<System::Object>(u"Caetegoty 3")));
// Récupère la première série du graphique
System::SharedPtr<IChartSeries> series = chart->get_ChartData()->get_Series()->idx_get(0);
auto dataPoints = series->get_DataPoints();
// Remplit les données de la série
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 1, System::ExplicitCast<System::Object>(20)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 1, System::ExplicitCast<System::Object>(50)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 1, System::ExplicitCast<System::Object>(30)));
// Définit la couleur de remplissage pour la série
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
// Récupère la deuxième série du graphique
series = chart->get_ChartData()->get_Series()->idx_get(1);
// Remplit les données de la série
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 1, 2, System::ExplicitCast<System::Object>(30)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 2, 2, System::ExplicitCast<System::Object>(10)));
dataPoints->AddDataPointForBarSeries(fact->GetCell(defaultWorksheetIndex, 3, 2, System::ExplicitCast<System::Object>(60)));
// Définit la couleur de remplissage pour la série
series->get_Format()->get_Fill()->set_FillType(FillType::Solid);
series->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Green());
// Définit le premier libellé pour afficher le nom de la catégorie
System::SharedPtr<IDataLabel> lbl = dataPoints->idx_get(0)->get_Label();
lbl->get_DataLabelFormat()->set_ShowCategoryName(true);
lbl = dataPoints->idx_get(1)->get_Label();
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
// Définit la série pour afficher la valeur du troisième libellé
lbl = dataPoints->idx_get(2)->get_Label();
lbl->get_DataLabelFormat()->set_ShowValue(true);
lbl->get_DataLabelFormat()->set_ShowSeriesName(true);
lbl->get_DataLabelFormat()->set_Separator(u"/");
// Enregistre le fichier PPTX sur le disque
pres->Save(u"AsposeChart_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) method

Crée un nouveau graphique, l'initialise avec des données de séries d'exemple et des paramètres, puis l'ajoute à la fin de la collection de formes.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | Le type de graphique à ajouter. |
| x | **float** | La coordonnée x du nouveau graphique, en points. |
| y | **float** | La coordonnée y du nouveau graphique, en points. |
| width | **float** | La largeur du graphique, en points. |
| height | **float** | La hauteur du graphique, en points. |
| initWithSample | **bool** | True pour initialiser le nouveau graphique avec des données de séries d'exemple et des paramètres ; false pour créer le graphique sans séries et avec seulement des paramètres minimaux, ce qui accélère la création. |

### Valeur de retour

Le [Charts::IChart](../../../aspose.slides.charts/ichart/) nouvellement créé.

## Voir aussi

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChart](../../../aspose.slides.charts/ichart/)
* Classe [ShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)