---
title: Chart
second_title: Aspose.Sildes pro .NET API Reference
description: Representuje grafický diagram na snímku.
type: docs
weight: 1240
url: /cs/aspose.slides.charts/chart/
---
## třída Chart

Represents an graphic chart on a slide.

```csharp
public class Chart : GraphicalObject, IChart
```

## Vlastnosti

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Vrací nebo nastavuje alternativní text spojený s tvarem. Čtení/zápis String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Vrací nebo nastavuje název alternativního textu spojeného s tvarem. Čtení/zápis String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Umožňuje získat základní rozhraní IFormattedTextContainer. Pouze pro čtení [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Umožňuje získat základní rozhraní IThemeable. Pouze pro čtení [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Poskytuje přístup k osám diagramu. Pouze pro čtení [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | Vrací objekt, který umožňuje změnit formát zadní stěny 3D diagramu. Pouze pro čtení [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Vlastnost určuje, jak bude tvar vykreslen v černobílém režimu zobrazení. Čtení/zápis [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Vrací informace o propojených nebo vložených datech spojených s diagramem. Pouze pro čtení [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Vrací datovou tabulku diagramu. Pouze pro čtení [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Vrací nebo nastavuje název diagramu. Pouze pro čtení [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Vrací počet připojovacích míst na tvaru. Pouze pro čtení Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Vrací vlastní data tvaru. Pouze pro čtení [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Vrací nebo nastavuje způsob vykreslování prázdných buněk v diagramu. Čtení/zápis [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Vrací objekt EffectFormat, který obsahuje pixelové efekty aplikované na tvar. Poznámka: může vrátit null u některých typů tvarů, které nemají vlastnosti efektu. Pouze pro čtení [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Vrací objekt FillFormat, který obsahuje vlastnosti výplně pro tvar. Poznámka: může vrátit null u některých typů tvarů, které nemají vlastnosti výplně. Pouze pro čtení [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | Vrací objekt, který umožňuje změnit formát podlahy 3D diagramu. Pouze pro čtení [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Vrací nebo nastavuje vlastnosti rámce tvaru. Čtení/zápis [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Vrací zámky tvaru. Pouze pro čtení [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Určuje, zda diagram má datovou tabulku. Čtení/zápis Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Určuje, zda diagram má legendu. Čtení/zápis Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Určuje, zda oblast diagramu má zaoblené rohy. Čtení/zápis Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Určuje, zda diagram má viditelný název. Čtení/zápis Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Vrací nebo nastavuje výšku tvaru, měřenou v bodech. Čtení/zápis Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Určuje, zda je tvar skrytý. Čtení/zápis Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší. Čtení/zápis [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Vrací správce hypertextových odkazů. Pouze pro čtení [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Vrací nebo nastavuje hypertextový odkaz definovaný pro ukázání myší. Čtení/zápis [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Vrací nebo nastavuje možnost 'Označit jako dekorativní'. Čtení/zápis Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Určuje, zda je tvar seskupený. Pouze pro čtení Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Určuje, zda je tvar TextHolder_PPT. Pouze pro čtení Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Vrací nebo nastavuje legendu pro diagram. Pouze pro čtení [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Vrací objekt LineFormat, který obsahuje vlastnosti formátování čáry pro tvar. Poznámka: může vrátit null u některých typů tvarů, které nemají vlastnosti čáry. Pouze pro čtení [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Vrací nebo nastavuje název tvaru. Nesmí být null. V případě potřeby použijte prázdný řetězec. Čtení/zápis String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Vrací jedinečný identifikátor v rámci snímku, který zůstává konstantní po celou životnost tvaru a umožňuje PowerPointu nebo interop kódu spolehlivě odkazovat na tvar odkudkoli v dokumentu. Pouze pro čtení UInt32. Viz také [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Vrací objekt GroupShape rodiče, pokud je tvar seskupený. Jinak vrací null. Pouze pro čtení [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Vrací zástupný prvek pro tvar. Vrací null, pokud tvar nemá zástupný prvek. Pouze pro čtení [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | Představuje vykreslovací oblast diagramu. Pouze pro čtení [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Určuje, zda jsou vykreslovány pouze viditelné buňky. False pro vykreslování jak viditelných, tak skrytých buněk. Čtení/zápis Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Vrací nadřazenou prezentaci snímku. Pouze pro čtení [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Vrací nebo nastavuje surové vlastnosti rámce tvaru. Čtení/zápis [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Vrací nebo nastavuje počet stupňů, o které je daný tvar otočen okolo osy z. Kladná hodnota označuje otáčení po směru hodinových ručiček; záporná hodnota označuje otáčení proti směru hodinových ručiček. Čtení/zápis Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Vrací 3D otočení diagramu. Pouze pro čtení [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Vrací zámky tvaru. Pouze pro čtení [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 vlastnosti) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Určuje, zda se mají zobrazovat datové popisky nad maximem diagramu. Čtení/zápis Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | Vrací objekt, který umožňuje změnit formát boční stěny 3D diagramu. Pouze pro čtení [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Vrací nadřazený snímek tvaru. Pouze pro čtení [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Vrací nebo nastavuje styl diagramu. Čtení/zápis [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Vrací formát textu diagramu. Vlastnost není použita pro následující typy: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker. Pouze pro čtení [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Vrací správce motivu. Pouze pro čtení [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Vrací objekt ThreeDFormat, který obsahuje 3D efektní vlastnosti pro tvar. Poznámka: může vrátit null u některých typů tvarů, které nemají 3D vlastnosti. Pouze pro čtení [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Vrací nebo nastavuje typ diagramu. Čtení/zápis [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Vrací interní identifikátor v rámci prezentace určený pro použití doplňky nebo jiným kódem. Protože tato hodnota může být přeassignována uživatelem nebo programově, nesmí být považována za trvalý unikátní klíč. Pouze pro čtení UInt32. Viz také [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Určuje tvary kreslené nad diagramem. Pouze pro čtení [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Vrací nebo nastavuje šířku tvaru, měřenou v bodech. Čtení/zápis Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Vrací nebo nastavuje x-koordinační hodnotu levého horního rohu tvaru, měřenou v bodech. Čtení/zápis Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Vrací nebo nastavuje y-koordinační hodnotu levého horního rohu tvaru, měřenou v bodech. Čtení/zápis Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Vrací pozici tvaru v Z-řazení. Shapes[0] vrací tvar na zadní pozici Z-řazení a Shapes[Shapes.Count - 1] vrací tvar na přední pozici Z-řazení. Pouze pro čtení Int32. |

## Metody

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Přidá nový zástupný prvek, pokud neexistuje, a nastaví vlastnosti zástupného prvku na zadaný. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Vrací účinný motiv pro tento diagram. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Vrací základní tvar zástupného prvku (tvar z rozvržení a/nebo hlavní snímku, ze kterého je aktuální tvar odvozen). Vrací null, pokud aktuální tvar není odvozen. |
| [GetImage](../../aspose.slides/shape/getimage)() | Vrací miniaturu tvaru. Výchozí je typ ShapeThumbnailBounds.Shape pro hranice miniatury. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Vrací miniaturu tvaru. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Získá vizuální hranice tvaru vypočtené z jeho vykresleného obsahu. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Definuje, že tento tvar není zástupný prvek. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Vypočítá skutečné hodnoty prvků diagramu. Skutečné hodnoty zahrnují pozice prvků implementujících rozhraní IActualLayout (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) a skutečné hodnoty os (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Uloží obsah tvaru jako soubor SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Uloží obsah tvaru jako soubor SVG. |

### Viz také

* třída [GraphicalObject](../../aspose.slides/graphicalobject)
* rozhraní [IChart](../ichart)
* jmenný prostor [Aspose.Slides.Charts](../../aspose.slides.charts)
* sestava [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->