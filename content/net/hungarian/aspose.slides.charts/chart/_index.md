---
title: Chart
second_title: Aspose.Sildes .NET API referencia
description: Egy dián lévő grafikus diagramot képvisel.
type: docs
weight: 1240
url: /hu/aspose.slides.charts/chart/
---
## Chart osztály

Egy grafikus diagramot ábrázol egy dián.

```csharp
public class Chart : GraphicalObject, IChart
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja az alakzathoz társított alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja az alakzathoz társított alternatív szöveg címét. Olvasás/írás String. |
| [AsIFormattedTextContainer](../../aspose.slides.charts/chart/asiformattedtextcontainer) { get; } | Lehetővé teszi az alap IFormattedTextContainer interfész lekérdezését. Csak olvasható [`IFormattedTextContainer`](../iformattedtextcontainer). |
| [AsIThemeable](../../aspose.slides.charts/chart/asithemeable) { get; } | Lehetővé teszi az alap IThemeable interfész lekérdezését. Csak olvasható [`IThemeable`](../../aspose.slides.theme/ithemeable). |
| [Axes](../../aspose.slides.charts/chart/axes) { get; } | Hozzáférést biztosít a diagram tengelyeihez. Csak olvasható [`IAxesManager`](../iaxesmanager). |
| [BackWall](../../aspose.slides.charts/chart/backwall) { get; } | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram háttérfalának formátumának módosítását. Csak olvasható [`IChartWall`](../ichartwall). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A tulajdonság meghatározza, hogyan jelenik meg egy alakzat fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ChartData](../../aspose.slides.charts/chart/chartdata) { get; } | Visszaad információt a diagramhoz kapcsolt vagy beágyazott adatról. Csak olvasható [`IChartData`](../ichartdata). |
| [ChartDataTable](../../aspose.slides.charts/chart/chartdatatable) { get; } | Visszaad egy diagram adat táblát. Csak olvasható [`IDataTable`](../idatatable). |
| [ChartTitle](../../aspose.slides.charts/chart/charttitle) { get; } | Visszaadja vagy beállítja a diagram címét. Csak olvasható [`IChartTitle`](../icharttitle). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja a forma csatlakozási pontjainak számát. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja a forma egyéni adatait. Csak olvasható [`ICustomData`](../../aspose.slides/icustomdata). |
| [DisplayBlanksAs](../../aspose.slides.charts/chart/displayblanksas) { get; set; } | Visszaadja vagy beállítja a diagram üres celláinak ábrázolásának módját. Olvasás/írás [`DisplayBlanksAsType`](../displayblanksastype). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely pixelhatásokat tartalmaz, amelyeket egy alakzatra alkalmaznak. Megjegyzés: bizonyos alakzatok esetén, amelyeknek nincs effektus tulajdonságuk, null értéket adhat vissza. Csak olvasható [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely kitöltési formázási tulajdonságokat tartalmaz egy alakzat számára. Megjegyzés: bizonyos alakzatok esetén, amelyeknek nincs kitöltési tulajdonságuk, null értéket adhat vissza. Csak olvasható [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Floor](../../aspose.slides.charts/chart/floor) { get; } | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram alapjának formátumának módosítását. Csak olvasható [`IChartWall`](../ichartwall). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja az alakzat keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Visszaadja a forma zárolásait. Csak olvasható [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [HasDataTable](../../aspose.slides.charts/chart/hasdatatable) { get; set; } | Megállapítja, hogy a diagram rendelkezik-e adat táblával. Olvasás/írás Boolean. |
| [HasLegend](../../aspose.slides.charts/chart/haslegend) { get; set; } | Megállapítja, hogy a diagram rendelkezik-e jelmagyarázattal. Olvasás/írás Boolean. |
| [HasRoundedCorners](../../aspose.slides.charts/chart/hasroundedcorners) { get; set; } | Megadja, hogy a diagram területének legyenek lekerekített sarkai. Olvasás/írás Boolean. |
| [HasTitle](../../aspose.slides.charts/chart/hastitle) { get; set; } | Megállapítja, hogy a diagram rendelkezik-e látható címmel. Olvasás/írás Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Visszaadja vagy beállítja az alakzat magasságát pontban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Megállapítja, hogy az alakzat rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperhivatkozás-kezelőt. Csak olvasható [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egérmutatóra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Visszaadja vagy beállítja a 'Mark as decorative' opciót. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Megállapítja, hogy az alakzat csoportosítva van-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Megállapítja, hogy az alakzat TextHolder_PPT-e. Csak olvasható Boolean. |
| [Legend](../../aspose.slides.charts/chart/legend) { get; } | Visszaadja vagy beállítja egy diagram jelmagyarázatát. Csak olvasható [`ILegend`](../ilegend). |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely vonalformázási tulajdonságokat tartalmaz egy alakzat számára. Megjegyzés: bizonyos alakzatok esetén, amelyeknek nincs vonal tulajdonságuk, null értéket adhat vissza. Csak olvasható [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja egy alakzat nevét. Nem lehet null. Szükség esetén használjon üres karakterlánc értéket. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy diára vonatkozó egyedi azonosítót, amely a forma teljes életciklusa alatt állandó, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely részéről. Csak olvasható UInt32. Lásd még [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosítva van. Egyébként null értéket ad vissza. Csak olvasható [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja egy forma helyőrzőjét. Null értéket ad vissza, ha a formának nincs helyőrzője. Csak olvasható [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [PlotArea](../../aspose.slides.charts/chart/plotarea) { get; } | A diagram ábrázolási területét képviseli. Csak olvasható [`IChartPlotArea`](../ichartplotarea). |
| [PlotVisibleCellsOnly](../../aspose.slides.charts/chart/plotvisiblecellsonly) { get; set; } | Megállapítja, hogy csak a látható cellák legyenek ábrázolva. Hamis érték esetén a látható és a rejtett cellák is ábrázolva lesznek. Olvasás/írás Boolean. |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja egy dia szülő prezentációját. Csak olvasható [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers alakzat keret tulajdonságait. Olvasás/írás [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott alakzat z-tengely körüli forgatásának fokszámát. A pozitív érték az óramű irányú forgást jelzi; a negatív érték az óramű ellenkező irányú forgást jelzi. Olvasás/írás Single. |
| [Rotation3D](../../aspose.slides.charts/chart/rotation3d) { get; } | Visszaad egy 3D forgást egy diagramhoz. Csak olvasható [`IRotation3D`](../irotation3d). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Visszaadja a forma zárolásait. Csak olvasható [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 tulajdonság) |
| [ShowDataLabelsOverMaximum](../../aspose.slides.charts/chart/showdatalabelsovermaximum) { get; set; } | Megadja, hogy a diagram maximuma feletti adatcímkék megjelenjenek-e. Olvasás/írás Boolean. |
| [SideWall](../../aspose.slides.charts/chart/sidewall) { get; } | Visszaad egy objektumot, amely lehetővé teszi a 3D diagram oldalfalának formátumának módosítását. Csak olvasható [`IChartWall`](../ichartwall). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja egy forma szülő diát. Csak olvasható [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [Style](../../aspose.slides.charts/chart/style) { get; set; } | Visszaadja vagy beállítja a diagram stílusát. Olvasás/írás [`StyleType`](../styletype). |
| [TextFormat](../../aspose.slides.charts/chart/textformat) { get; } | Visszaadja a diagram szövegformátumát. A tulajdonság nem alkalmazható a következő típusokra: Treemap, Sunburst, Waterfall, Histogram, Funnel, BoxAndWhisker. Csak olvasható [`IChartTextFormat`](../icharttextformat). |
| [ThemeManager](../../aspose.slides.charts/chart/thememanager) { get; } | Visszaadja a témakezelőt. Csak olvasható [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely egy alakzat 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzatok esetén, amelyeknek nincs 3D tulajdonságuk, null értéket adhat vissza. Csak olvasható [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Type](../../aspose.slides.charts/chart/type) { get; set; } | Visszaadja vagy beállítja a diagram típusát. Olvasás/írás [`ChartType`](../charttype). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentációra korlátozott azonosítót, amelyet kiegészítők vagy más kód használhat. Mivel ezt az értéket a felhasználó vagy programozott módon át lehet állítani, nem szabad állandó egyedi kulcsként kezelni. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [UserShapes](../../aspose.slides.charts/chart/usershapes) { get; } | Meghatározza a diagram tetején megrajzolt alakzatokat. Csak olvasható [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Visszaadja vagy beállítja az alakzat szélességét pontban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Visszaadja vagy beállítja az alakzat bal felső sarkának x-koordinátáját pontban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Visszaadja vagy beállítja az alakzat bal felső sarkának y-koordinátáját pontban mérve. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja egy alakzat pozícióját a z-rendetben. A Shapes[0] a z-rend hátsó alakzatát adja, a Shapes[Shapes.Count - 1] pedig a frontális alakzatot. Csak olvasható Int32. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helyőrzőt ad hozzá, ha nincs, és beállítja a helyőrző tulajdonságait a megadottra. |
| [CreateThemeEffective](../../aspose.slides.charts/chart/createthemeeffective)() | Visszaad egy hatékony témát ehhez a diagramhoz. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helyőrző alakzatot (az elrendezés vagy a fődia alakzata, amelyből a jelenlegi alakzat örököl). Null érték visszaadva, ha a jelenlegi alakzat nem örököl. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja az alakzat bélyegképét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape bélyegkép határok típusa használatos. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja az alakzat bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Visszaadja az alakzat vizuális határait, amelyet a renderelt tartalma alapján számolnak. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez az alakzat nem helyőrző. |
| [ValidateChartLayout](../../aspose.slides.charts/chart/validatechartlayout)() | Kiszámítja a diagram elemeinek tényleges értékeit. A tényleges értékek tartalmazzák az IActualLayout interfész (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) implementáló elemek pozícióját, valamint a tényleges tengelyértékeket (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale). |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | A Shape tartalmát SVG fájlként menti. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | A Shape tartalmát SVG fájlként menti. |

### Lásd még

* osztály [GraphicalObject](../../aspose.slides/graphicalobject)
* interfész [IChart](../ichart)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->