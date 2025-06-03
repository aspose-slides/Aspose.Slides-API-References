---
title: Chart
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente un graphique sur une diapositive.
type: docs
weight: 1180
url: /fr/aspose.slides.charts/chart/
---

## Classe Chart

Représente un graphique sur une diapositive.

```csharp
public class Chart : GraphicalObject, IChart
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Renvoie ou définit le texte alternatif associé à une forme. Lecture/écriture String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Renvoie ou définit le titre du texte alternatif associé à une forme. Lecture/écriture String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Permet d'obtenir l'interface de base IFormattedTextContainer. Lecture seule [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Permet d'obtenir l'interface de base IThemeable. Lecture seule [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Fournit un accès aux axes du graphique. Lecture seule [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | Renvoie un objet qui permet de changer le format du mur arrière d'un graphique 3D. Lecture seule [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Propriété spécifiant comment une forme sera rendue en mode d'affichage en noir et blanc. Lecture/écriture [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Renvoie des informations sur les données liées ou intégrées associées à un graphique. Lecture seule [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Renvoie un tableau de données d'un graphique. Lecture seule [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Renvoie ou définit un titre de graphique. Lecture seule [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Renvoie le nombre de sites de connexion sur la forme. Lecture seule Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Renvoie les données personnalisées de la forme. Lecture seule [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Renvoie ou définit la façon de tracer les cellules vides sur un graphique. Lecture/écriture [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Renvoie l'objet EffectFormat qui contient des effets de pixel appliqués à une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés d'effet. Lecture seule [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Renvoie l'objet FillFormat qui contient des propriétés de mise en forme de remplissage pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés de remplissage. Lecture seule [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | Renvoie un objet qui permet de changer le format du sol d'un graphique 3D. Lecture seule [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Renvoie ou définit les propriétés du cadre de la forme. Lecture/écriture [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Renvoie les verrous de la forme. Lecture seule [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Détermine si un graphique a un tableau de données. Lecture/écriture Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Détermine si un graphique a une légende. Lecture/écriture Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Spécifie que la zone du graphique aura des coins arrondis. Lecture/écriture Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Détermine si un graphique a un titre visible. Lecture/écriture Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Renvoie ou définit la hauteur de la forme. Lecture/écriture Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Détermine si la forme est cachée. Lecture/écriture Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Renvoie ou définit l'hyperlien défini pour un clic de souris. Lecture/écriture [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Renvoie le gestionnaire d'hyperliens. Lecture seule [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Renvoie ou définit l'hyperlien défini pour un survol de souris. Lecture/écriture [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtient ou définit l'option 'Marquer comme décoratif' Lecture/écriture Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Détermine si la forme est groupée. Lecture seule Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Détermine si la forme est un TextHolder_PPT. Lecture seule Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Renvoie ou définit une légende pour un graphique. Lecture seule [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Renvoie l'objet LineFormat qui contient des propriétés de mise en forme de ligne pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés de ligne. Lecture seule [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Renvoie ou définit le nom d'une forme. Ne doit pas être nul. Utilisez une valeur de chaîne vide si nécessaire. Lecture/écriture String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Obtient un identifiant unique de forme dans le contexte de la diapositive. Lecture seule UInt32. Voir aussi [`UniqueId`](../../aspose.slides/shape/uniqueid) pour obtenir l'identifiant unique de forme dans le contexte de la présentation. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Renvoie l'objet GroupShape parent si la forme est groupée. Renvoie null sinon. Lecture seule [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Renvoie le placeholder pour une forme. Renvoie null si la forme n'a pas de placeholder. Lecture seule [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | Représente la zone de tracé d'un graphique. Lecture seule [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Détermine si seules les cellules visibles sont tracées. Faux pour tracer à la fois les cellules visibles et cachées. Lecture/écriture Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Renvoie la présentation parente d'une diapositive. Lecture seule [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Renvoie ou définit les propriétés du cadre brut de la forme. Lecture/écriture [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Renvoie ou définit le nombre de degrés par lequel la forme spécifiée est pivotée autour de l'axe z. Une valeur positive indique une rotation dans le sens des aiguilles d'une montre ; une valeur négative indique une rotation dans le sens inverse. Lecture/écriture Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Renvoie une rotation 3D d'un graphique. Lecture seule [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Renvoie les verrous de la forme. Lecture seule [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 propriétés) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Spécifie que les étiquettes de données au-dessus du maximum du graphique doivent être affichées. Lecture/écriture Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | Renvoie un objet qui permet de changer le format du mur latéral d'un graphique 3D. Lecture seule [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Renvoie la diapositive parente d'une forme. Lecture seule [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Renvoie ou définit le style du graphique. Lecture/écriture [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Renvoie le format de texte du graphique. La propriété n'est pas applicable pour les types suivants : Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker. Lecture seule [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Renvoie le gestionnaire de thème. Lecture seule [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Renvoie l'objet ThreeDFormat qui contient des propriétés d'effet 3D pour une forme. Remarque : peut renvoyer null pour certains types de formes qui n'ont pas de propriétés 3D. Lecture seule [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Renvoie ou définit le type de graphique. Lecture/écriture [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Obtient un identifiant unique de forme dans le contexte de la présentation. Lecture seule UInt32. Voir aussi [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) pour obtenir l'identifiant unique de forme dans le contexte de la diapositive. |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Spécifie les formes dessinées au-dessus du graphique. Lecture seule [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Renvoie ou définit la largeur de la forme. Lecture/écriture Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Renvoie ou définit la coordonnée x du coin supérieur gauche de la forme. Lecture/écriture Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Renvoie ou définit la coordonnée y du coin supérieur gauche de la forme. Lecture/écriture Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Renvoie la position d'une forme dans l'ordre z. Shapes[0] renvoie la forme à l'arrière de l'ordre z, et Shapes[Shapes.Count - 1] renvoie la forme à l'avant de l'ordre z. Lecture seule Int32. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Ajoute un nouveau placeholder s'il n'y en a pas et définit les propriétés du placeholder à un spécifié. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Renvoie un thème effectif pour ce graphique. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Renvoie une forme de placeholder de base (forme provenant de la mise en page et/ou de la diapositive maître dont la forme actuelle est héritée). Un null est renvoyé si la forme actuelle n'est pas héritée. |
| [GetImage](../../aspose.slides/shape/getimage)() | Renvoie la miniature de la forme. ShapeThumbnailBounds.Shape type de limites de miniature de forme est utilisé par défaut. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Renvoie la miniature de la forme. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Définit que cette forme n'est pas un placeholder. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Calcule les valeurs réelles des éléments du graphique. Les valeurs réelles incluent la position des éléments qui implémentent l'interface IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) et les valeurs réelles des axes (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale) |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Enregistre le contenu de la forme en tant que fichier SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Enregistre le contenu de la forme en tant que fichier SVG. |

### Voir aussi

* classe [GraphicalObject](../../aspose.slides/graphicalobject)
* interface [IChart](../ichart)
* namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->