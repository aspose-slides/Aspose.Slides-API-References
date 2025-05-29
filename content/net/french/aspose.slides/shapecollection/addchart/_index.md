---
title: AddChart
second_title: Référence de l'API Aspose.Slides pour .NET
description: Crée un nouveau graphique, l'initialise avec des données et des paramètres d'exemple, et l'ajoute à la fin de la collection.
type: docs
weight: 100
url: /fr/aspose.slides/shapecollection/addchart/
---

## AddChart(ChartType, float, float, float, float) {#addchart}

Crée un nouveau graphique, l'initialise avec des données et des paramètres d'exemple, et l'ajoute à la fin de la collection.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| type | ChartType | Type de graphique. |
| x | Single | Coordonnée X d'un nouveau graphique. |
| y | Single | Coordonnée Y d'un nouveau graphique. |
| width | Single | Largeur du graphique. |
| height | Single | Hauteur du graphique. |

### Valeur de retour

Graphique créé.

### Exemples

L'exemple suivant montre comment créer un graphique dans une présentation PowerPoint.

```csharp
[C#]
// Instancie la classe Presentation qui représente un fichier PPTX
using(Presentation pres = new Presentation()) {
  // Accède à la première diapositive
  ISlide sld = pres.Slides[0];
  // Ajoute un graphique avec ses données par défaut
  IChart chart = sld.Shapes.AddChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
  // Définit le titre du graphique
  chart.ChartTitle.AddTextFrameForOverriding("Titre Exemple");
  chart.ChartTitle.TextFrameForOverriding.TextFrameFormat.CenterText = NullableBool.True;
  chart.ChartTitle.Height = 20;
  chart.HasTitle = true;
  // Définit la première série pour afficher les valeurs
  chart.ChartData.Series[0].Labels.DefaultDataLabelFormat.ShowValue = true;
  // Définit l'index de la feuille de données du graphique
  int defaultWorksheetIndex = 0;
  // Obtient la feuille de calcul des données du graphique
  IChartDataWorkbook fact = chart.ChartData.ChartDataWorkbook;
  // Supprime les séries et catégories générées par défaut
  chart.ChartData.Series.Clear();
  chart.ChartData.Categories.Clear();
  int s = chart.ChartData.Series.Count;
  s = chart.ChartData.Categories.Count;
  // Ajoute de nouvelles séries
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 1, "Série 1"), chart.Type);
  chart.ChartData.Series.Add(fact.GetCell(defaultWorksheetIndex, 0, 2, "Série 2"), chart.Type);
  // Ajoute de nouvelles catégories
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 1, 0, "Catégorie 1"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 2, 0, "Catégorie 2"));
  chart.ChartData.Categories.Add(fact.GetCell(defaultWorksheetIndex, 3, 0, "Catégorie 3"));
  // Prend la première série du graphique
  IChartSeries series = chart.ChartData.Series[0];
  // Remplit les données de la série
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 1, 20));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 1, 50));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 1, 30));
  // Définit la couleur de remplissage pour la série
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Red;
  // Prend la deuxième série du graphique
  series = chart.ChartData.Series[1];
  // Remplit les données de la série
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 1, 2, 30));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 2, 2, 10));
  series.DataPoints.AddDataPointForBarSeries(fact.GetCell(defaultWorksheetIndex, 3, 2, 60));
  // Définit la couleur de remplissage pour la série
  series.Format.Fill.FillType = FillType.Solid;
  series.Format.Fill.SolidFillColor.Color = Color.Green;
  // Définit la première étiquette pour afficher le nom de la catégorie
  IDataLabel lbl = series.DataPoints[0].Label;
  lbl.DataLabelFormat.ShowCategoryName = true;
  lbl = series.DataPoints[1].Label;
  lbl.DataLabelFormat.ShowSeriesName = true;
  // Définit la série pour afficher la valeur pour la troisième étiquette
  lbl = series.DataPoints[2].Label;
  lbl.DataLabelFormat.ShowValue = true;
  lbl.DataLabelFormat.ShowSeriesName = true;
  lbl.DataLabelFormat.Separator = "/";
  // Enregistre le fichier PPTX sur le disque
  pres.Save("AsposeChart_out.pptx", SaveFormat.Pptx);
}
```

### Voir aussi

* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

---

## AddChart(ChartType, float, float, float, float, bool) {#addchart_1}

Crée un nouveau graphique et l'ajoute à la fin de la collection.

```csharp
public IChart AddChart(ChartType type, float x, float y, float width, float height, 
    bool initWithSample)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| type | ChartType | Type de graphique. |
| x | Single | Coordonnée X d'un nouveau graphique. |
| y | Single | Coordonnée Y d'un nouveau graphique. |
| width | Single | Largeur du graphique. |
| height | Single | Hauteur du graphique. |
| initWithSample | Boolean | Si vrai, le nouveau graphique sera initialisé avec des données et des paramètres de série d'exemple. Si faux, le nouveau graphique n'aura aucune série et des paramètres minimum. Dans ce cas, la création du graphique sera plus rapide. |

### Valeur de retour

Graphique créé.

### Voir aussi

* interface [IChart](../../../aspose.slides.charts/ichart)
* enum [ChartType](../../../aspose.slides.charts/charttype)
* class [ShapeCollection](../../shapecollection)
* namespace [Aspose.Slides](../../shapecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->