---
title: Aspose.Slides.Charts
second_title: Référence de l'API Aspose.Slides pour .NET
description: Contient des classes pour travailler avec des graphiques dans les présentations Microsoft PowerPoint.
type: docs
weight: 30
url: /fr/aspose.slides.charts/
---

Contient des classes pour travailler avec des graphiques dans les présentations Microsoft PowerPoint.

## Classes

| Classe | Description |
| --- | --- |
| [AxesCompositionNotCombinableException](./axescompositionnotcombinableexception) | Exception levée lorsque la composition des axes de la série n'est pas combinable avec la composition des axes actuelle dans le graphique. |
| [AxesManager](./axesmanager) | Fournit un accès aux axes du graphique. |
| [Axis](./axis) | Encapsule l'objet qui représente un axe de graphique. |
| [AxisFormat](./axisformat) | Représente les propriétés de format de graphique. |
| [BaseChartValue](./basechartvalue) | Représente une valeur d'un graphique. |
| [CannotCombine2DAnd3DChartsException](./cannotcombine2dand3dchartsexception) | Exception levée lorsqu'on essaie de combiner des types de graphiques 2D et 3D. |
| [Chart](./chart) | Représente un graphique sur une diapositive. |
| [ChartCategory](./chartcategory) | Représente les catégories de graphiques. |
| [ChartCategoryCollection](./chartcategorycollection) | Représente une collection de [`ChartCategory`](../aspose.slides.charts/chartcategory) |
| [ChartCategoryLevelsManager](./chartcategorylevelsmanager) | Conteneur géré des valeurs des niveaux de catégorie de graphique. |
| [ChartCellCollection](./chartcellcollection) | Représente une collection de cellules contenant des données. |
| [ChartData](./chartdata) | Représente les données utilisées pour la traçage d'un graphique. |
| [ChartDataCell](./chartdatacell) | Représente une cellule pour les données du graphique. |
| [ChartDataPoint](./chartdatapoint) | Représente un point de données de série. |
| [ChartDataPointCollection](./chartdatapointcollection) | Représente une collection d'un point de données de série. |
| [ChartDataPointLevel](./chartdatapointlevel) | Représente le niveau du point de données. S'applique aux graphiques Treemap et Sunburst. |
| [ChartDataPointLevelsManager](./chartdatapointlevelsmanager) | Conteneur des niveaux de points de données. Appliqué pour les séries Treeamp et Sunburst. L'indexation des niveaux de points de données est basée sur zéro. |
| [ChartDataWorkbook](./chartdataworkbook) | Fournit un accès au classeur Excel intégré |
| [ChartDataWorksheet](./chartdataworksheet) | Représente la feuille de calcul associée à [`IChartDataCell`](../aspose.slides.charts/ichartdatacell) |
| [ChartDataWorksheetCollection](./chartdataworksheetcollection) | Représente la collection des feuilles de calcul du classeur de données du graphique. |
| [ChartLinesFormat](./chartlinesformat) | Représente les propriétés de format des lignes de grille. |
| [ChartPlotArea](./chartplotarea) | Représente le rectangle où le graphique doit être tracé. |
| [ChartPortionFormat](./chartportionformat) | Cette classe contient les propriétés de format de portion de graphique utilisées dans les graphiques. Contrairement à [`IPortionFormatEffectiveData`](../aspose.slides/iportionformateffectivedata), toutes les propriétés de cette classe sont modifiables. |
| [ChartSeries](./chartseries) | Représente une série de graphiques. |
| [ChartSeriesCollection](./chartseriescollection) | Représente une collection de [`ChartSeries`](../aspose.slides.charts/chartseries) |
| [ChartSeriesGroup](./chartseriesgroup) | Représente un groupe de séries. |
| [ChartTextFormat](./charttextformat) | Spécifie le formatage de texte par défaut pour les éléments de texte du graphique. |
| [ChartTitle](./charttitle) | Représente les propriétés du titre du graphique. |
| [ChartTypeCharacterizer](./charttypecharacterizer) | Aide à obtenir des informations supplémentaires sur les graphiques et les séries par son TypeDeGraphique. |
| [ChartWall](./chartwall) | Représente les murs sur les graphiques 3D. |
| [DataLabel](./datalabel) | Représente les étiquettes d'une série. |
| [DataLabelCollection](./datalabelcollection) | Représente les étiquettes d'une série. |
| [DataLabelFormat](./datalabelformat) | Représente les options de formatage pour DataLabel. |
| [DataSourceTypeForErrorBarsCustomValues](./datasourcetypeforerrorbarscustomvalues) | Spécifie les types de valeurs dans la liste des propriétés ChartDataPoint.ErrorBarsCustomValues |
| [DataTable](./datatable) | Représente les propriétés de la table de données. |
| [DoubleChartValue](./doublechartvalue) | Représente une valeur double qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans la cellule ou les cellules du classeur liées au graphique ; 2) en tant que valeur littérale. |
| [ErrorBarsCustomValues](./errorbarscustomvalues) | Spécifie les valeurs de la barre d'erreurs. Il doit être utilisé uniquement lorsque le type de valeur des barres d'erreurs est Personnalisé. |
| [ErrorBarsFormat](./errorbarsformat) | Représente les barres d'erreurs de la série de graphiques. Les valeurs personnalisées de ErrorBars se trouvent dans IChartDataPointCollection (dans la propriété [`ErrorBarsCustomValues`](../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues)). |
| [Format](./format) | Représente les propriétés de format du graphique. |
| [Legend](./legend) | Représente les propriétés de la légende du graphique. |
| [LegendEntryCollection](./legendentrycollection) | Représente la collection des légendes. |
| [LegendEntryProperties](./legendentryproperties) | Représente les propriétés de légende d'un graphique. |
| [Marker](./marker) | Représente un marqueur d'un graphique. |
| [PieSplitCustomPointCollection](./piesplitcustompointcollection) | Représente une collection de points pour un point de séparation dans un graphique en barre de tarte ou un graphique en tarte de tarte avec une séparation personnalisée. |
| [Rotation3D](./rotation3d) | Représente la rotation 3D d'un graphique. |
| [StringChartValue](./stringchartvalue) | Représente une valeur string qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans la cellule ou les cellules du classeur liées au graphique ; 2) en tant que valeur littérale. |
| [StringOrDoubleChartValue](./stringordoublechartvalue) | Représente une valeur string ou double qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans la cellule ou les cellules du classeur liées au graphique ; 2) en tant que valeur littérale. |
| [Trendline](./trendline) | La classe représente la ligne de tendance de la série de graphiques. |
| [TrendlineCollection](./trendlinecollection) | Représente une collection de Trendline. |
| [UpDownBarsManager](./updownbarsmanager) | Fournit un accès aux barres de montée/descentes des graphiques en ligne ou de stock. |
## Interfaces

| Interface | Description |
| --- | --- |
| [IActualLayout](./iactuallayout) | Spécifie la position réelle d'un élément de graphique. |
| [IAxesManager](./iaxesmanager) | Fournit un accès aux axes du graphique. |
| [IAxis](./iaxis) | Encapsule l'objet qui représente un axe de graphique. |
| [IAxisFormat](./iaxisformat) | Représente les propriétés de format du graphique. |
| [IBaseChartValue](./ibasechartvalue) | Représente une valeur d'un graphique. |
| [IChart](./ichart) | Représente un graphique sur une diapositive. |
| [IChartCategory](./ichartcategory) | Représente les catégories de graphiques. |
| [IChartCategoryCollection](./ichartcategorycollection) | Représente une collection de [`IChartCategory`](../aspose.slides.charts/ichartcategory) |
| [IChartCategoryLevelsManager](./ichartcategorylevelsmanager) | Conteneur géré des valeurs des niveaux de catégorie de graphique. |
| [IChartCellCollection](./ichartcellcollection) | Représente une collection de cellules contenant des données. |
| [IChartComponent](./ichartcomponent) | Représente un composant de graphique. |
| [IChartData](./ichartdata) | Représente les données utilisées pour le traçage d'un graphique. |
| [IChartDataCell](./ichartdatacell) | Représente une cellule pour les données du graphique. |
| [IChartDataPoint](./ichartdatapoint) | Représente un point de données de série. |
| [IChartDataPointCollection](./ichartdatapointcollection) | Représente une collection d'un point de données de série. |
| [IChartDataPointLevel](./ichartdatapointlevel) | Représente le niveau du point de données. S'applique aux graphiques Treemap et Sunburst. |
| [IChartDataPointLevelsManager](./ichartdatapointlevelsmanager) | Conteneur des niveaux de points de données. Appliqué pour les séries Treeamp et Sunburst. L'indexation des niveaux de points de données est basée sur zéro. |
| [IChartDataWorkbook](./ichartdataworkbook) | Fournit un accès au classeur Excel intégré |
| [IChartDataWorksheet](./ichartdataworksheet) | Représente la feuille de calcul associée à [`IChartDataCell`](../aspose.slides.charts/ichartdatacell) |
| [IChartDataWorksheetCollection](./ichartdataworksheetcollection) | Représente la collection des feuilles de calcul du classeur de données du graphique. |
| [IChartLinesFormat](./ichartlinesformat) | Représente les propriétés de format des lignes de grille. |
| [IChartParagraphFormat](./ichartparagraphformat) | Représente les propriétés de format de paragraphe d'un graphique. |
| [IChartPlotArea](./ichartplotarea) | Représente les propriétés du titre du graphique. |
| [IChartPortionFormat](./ichartportionformat) | Représente les propriétés de formatting de la portion de graphique utilisées dans les graphiques. |
| [IChartSeries](./ichartseries) | Représente une série de graphiques. |
| [IChartSeriesCollection](./ichartseriescollection) | Représente une collection de [`IChartSeries`](../aspose.slides.charts/ichartseries) |
| [IChartSeriesGroup](./ichartseriesgroup) | Représente un groupe de séries. |
| [IChartSeriesGroupCollection](./ichartseriesgroupcollection) | Représente la collection de groupes de séries combinables. |
| [IChartSeriesReadonlyCollection](./ichartseriesreadonlycollection) | Représente une collection en lecture seule de [`IChartSeries`](../aspose.slides.charts/ichartseries) |
| [IChartTextBlockFormat](./icharttextblockformat) | Représente les propriétés de formatage pour les éléments de texte du graphique. |
| [IChartTextFormat](./icharttextformat) | Le graphique fonctionne avec un ensemble restreint de propriétés de format de texte. Les interfaces IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat décrivent cet ensemble restreint. |
| [IChartTitle](./icharttitle) | Représente les propriétés du titre du graphique. |
| [IChartWall](./ichartwall) | Représente les murs sur les graphiques 3D. |
| [IDataLabel](./idatalabel) | Représente les étiquettes d'une série. |
| [IDataLabelCollection](./idatalabelcollection) | Représente les étiquettes d'une série. |
| [IDataLabelFormat](./idatalabelformat) | Représente les options de formatage pour DataLabel. |
| [IDataSourceTypeForErrorBarsCustomValues](./idatasourcetypeforerrorbarscustomvalues) | Spécifie les types de valeurs dans la liste des propriétés ChartDataPoint.ErrorBarsCustomValues |
| [IDataTable](./idatatable) | Représente les propriétés de la table de données. |
| [IDoubleChartValue](./idoublechartvalue) | Représente une valeur double qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans la cellule ou les cellules du classeur liées au graphique ; 2) en tant que valeur littérale. |
| [IErrorBarsCustomValues](./ierrorbarscustomvalues) | Spécifie les valeurs de la barre d'erreurs. Il doit être utilisé uniquement lorsque le type de valeur des barres d'erreurs est Personnalisé. |
| [IErrorBarsFormat](./ierrorbarsformat) | Représente les barres d'erreurs de la série de graphiques. Les valeurs personnalisées de ErrorBars se trouvent dans IChartDataPointCollection (dans la propriété [`ErrorBarsCustomValues`](../aspose.slides.charts/ichartdatapoint/errorbarscustomvalues)). |
| [IFormat](./iformat) | Représente les propriétés de format du graphique. |
| [IFormattedTextContainer](./iformattedtextcontainer) | Représente le format de texte du graphique. |
| [ILayoutable](./ilayoutable) | Spécifie la position exacte d'un élément de graphique. |
| [ILegend](./ilegend) | Représente les propriétés de la légende du graphique. |
| [ILegendEntryCollection](./ilegendentrycollection) | Représente la collection des légendes. |
| [ILegendEntryProperties](./ilegendentryproperties) | Représente les propriétés de légende d'un graphique. |
| [IMarker](./imarker) | Représente un marqueur d'un graphique. |
| [IMultipleCellChartValue](./imultiplecellchartvalue) | Représente une collection de cellules de graphique. |
| [IOverridableText](./ioverridabletext) | Représente le texte remplaçable pour un graphique. |
| [IPieSplitCustomPointCollection](./ipiesplitcustompointcollection) | Représente une collection de points qui doivent être dessinés dans la seconde tarte ou barre sur un graphique en barre de tarte ou en tarte de tarte avec une séparation personnalisée. |
| [IRotation3D](./irotation3d) | Représente la rotation 3D d'un graphique. |
| [ISingleCellChartValue](./isinglecellchartvalue) | Représente une cellule de données de graphique. |
| [IStringChartValue](./istringchartvalue) | Représente une valeur string qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans la cellule ou les cellules du classeur liées au graphique ; 2) en tant que valeur littérale. |
| [IStringOrDoubleChartValue](./istringordoublechartvalue) | Représente une valeur string ou double qui peut être stockée dans un document de présentation pptx de deux manières : 1) dans la cellule ou les cellules du classeur liées au graphique ; 2) en tant que valeur littérale. |
| [ITrendline](./itrendline) | La classe représente la ligne de tendance de la série de graphiques. |
| [ITrendlineCollection](./itrendlinecollection) | Représente une collection de TrendlineEx |
| [IUpDownBarsManager](./iupdownbarsmanager) | Fournit un accès aux barres de montée/descentes des graphiques en ligne ou de stock. |
## Énumération

| Énumération | Description |
| --- | --- |
| [AxisAggregationType](./axisaggregationtype) | Représente le type d'agrégation de l'axe de catégorie. Utilisé uniquement avec les séries Histogram ou HistogramPareto. |
| [AxisPositionType](./axispositiontype) | Détermine la position d'un axe. |
| [BubbleSizeRepresentationType](./bubblesizerepresentationtype) | Spécifie les manières possibles de représenter les données sous forme de tailles de graphiques à bulles. |
| [CategoryAxisType](./categoryaxistype) | Représente un type d'axe de catégorie. |
| [ChartDataSourceType](./chartdatasourcetype) | Représente un type de source de données du graphique. |
| [ChartShapeType](./chartshapetype) | Représente une forme de graphique. |
| [ChartType](./charttype) | Représente un type de graphique. |
| [CombinableSeriesTypesGroup](./combinableseriestypesgroup) | Énumération des groupes de types de séries combinables. Chaque élément se rapporte à un groupe de types de séries de graphiques qui peuvent persister simultanément dans un seul ChartSeriesGroup. Par exemple : la série ChartType.PercentsStackedArea ne peut pas être utilisée simultanément avec la série ChartType.StackedArea dans un seul ChartSeriesGroup. Mais deux ou plusieurs ChartType.PercentsStackedArea peuvent être dans un seul ChartSeriesGroup simultanément (CombinableSeriesTypesGroup.AreaChart_PercentsStackedArea). Et la série ChartType.Line peut être utilisée avec la série ChartType.LineWithMarkers simultanément dans un seul CombinableSeriesTypesGroup.LineChart_Line ChartSeriesGroup. |
| [CrossesType](./crossestype) | Détermine où l'axe croisera. |
| [DataSourceType](./datasourcetype) | Types de sources de données. |
| [DisplayBlanksAsType](./displayblanksastype) | Détermine comment les données manquantes seront affichées. |
| [DisplayUnitType](./displayunittype) | Détermine la multiplicité des données affichées. |
| [ErrorBarType](./errorbartype) | Représente le type de barre d'erreurs. |
| [ErrorBarValueType](./errorbarvaluetype) | Représente le type de valeur de barre d'erreurs. |
| [LayoutTargetType](./layouttargettype) | Si la disposition de la zone de traçage est définie manuellement, cette propriété spécifie si la zone de traçage doit être disposée à l'intérieur (sans inclure l'axe et les étiquettes d'axe) ou à l'extérieur (en incluant l'axe et les étiquettes d'axe). |
| [LegendDataLabelPosition](./legenddatalabelposition) | Détermine la position des étiquettes de données. |
| [LegendPositionType](./legendpositiontype) | Détermine la position de la légende sur un graphique. |
| [MarkerStyleType](./markerstyletype) | Détermine la forme du marqueur sur le point de données du graphique. |
| [ParentLabelLayoutType](./parentlabellayouttype) | Représente la disposition des étiquettes de données de catégorie. Utilisé uniquement avec les séries Treemap. |
| [PictureType](./picturetype) | Détermine le mode de remplissage de l'image de barre. |
| [PieSplitType](./piesplittype) | Représente un type de points de séparation dans la seconde tarte ou barre sur un graphique en tarte de tarte ou en barre de tarte. |
| [QuartileMethodType](./quartilemethodtype) | Renvoie le type de méthode quartile. |
| [StyleType](./styletype) | Représente le style du graphique. |
| [TickLabelPositionType](./ticklabelpositiontype) | Représente le type de position des étiquettes de marqueurs sur l'axe spécifié. |
| [TickMarkType](./tickmarktype) | Représente le type de marqueur pour l'axe spécifié. |
| [TimeUnitType](./timeunittype) | Représente l'unité de base pour l'axe de catégorie. |
| [TrendlineType](./trendlinetype) | Représente le type de ligne de tendance |