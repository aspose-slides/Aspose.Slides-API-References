---
title: PictureFrame
second_title: Aspose.Sildes .NET API referencia
description: Képet tartalmazó keretet képvisel.
type: docs
weight: 9390
url: /hu/aspose.slides/pictureframe/
---
## PictureFrame osztály

Képet tartalmazó keretet képviseli.

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Visszaadja a shape igazítási értékeinek gyűjteményét. Csak olvasható [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja egy shape-hez kapcsolódó alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja az alternatív szöveg címét, amely egy shape-hez tartozik. Olvasás/írás String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A tulajdonság meghatározza, hogy egy shape hogyan jelenik meg fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja az alakzaton lévő csatlakozási pontok számát. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja az shape egyéni adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a shape-re alkalmazott pixel effektusokat tartalmazza. Megjegyzés: bizonyos, effektus tulajdonságokkal nem rendelkező shape-ok esetén null értéket adhat vissza. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely a shape kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos, kitöltési tulajdonságokkal nem rendelkező shape-ok esetén null értéket adhat vissza. Csak olvasható [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja a shape keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Visszaadja vagy beállítja a shape magasságát pontban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Meghatározza, hogy a shape rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja a egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperhivatkozás-kezelőt. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egérmutatásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Megállapítja, hogy a PictureFrame Cameo objektum-e vagy sem. Csak olvasható Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Visszaadja vagy beállítja a 'Mark as decorative' opciót. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Megállapítja, hogy a shape csoportosított-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Megállapítja, hogy a shape TextHolder_PPT-e. Csak olvasható Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely a shape vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos, vonal tulajdonságokkal nem rendelkező shape-ok esetén null értéket adhat vissza. Csak olvasható [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja egy shape nevét. Nem lehet null. Szükség esetén használjon üres karakterláncot. Olvasás/írás String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy diára korlátozott egyedi azonosítót, amely az shape élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy az interop kód számára, hogy a dokumentum bármely részéről megbízhatóan hivatkozzon az shape-ra. Csak olvasható UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha az shape csoportosított. Ellenkező esetben null értéket ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Visszaadja a PictureFillFormat objektumot egy képkerethez. Csak olvasható [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Visszaadja az shape zárolásait. Csak olvasható [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja egy shape helyőrzőjét. Null értéket ad vissza, ha az shape-nak nincs helyőrzője. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a dia szülő prezentációját. Csak olvasható [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers shape keret tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Visszaadja vagy beállítja a képkeret magasságának méretezését (az eredeti képmérettől függően). Az 1,0 érték 100%-nak felel meg. Olvasás/írás Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Visszaadja vagy beállítja a képkeret szélességének méretezését (az eredeti képmérettől függően). Az 1,0 érték 100%-nak felel meg. Olvasás/írás Single. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott shape Z-tengely körüli forgatásának fokszámát. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellenkező irányú forgást. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Visszaadja az shape zárolásait. Csak olvasható [`IPictureFrameLock`](../ipictureframelock). (2 tulajdonság) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Visszaadja az shape stílusobjektumát. Csak olvasható [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Visszaadja vagy beállítja a PictureFrame AutoShape típusát. A [`ShapeType`](../shapetype) halmaz összes eleme engedélyezett, kivéve a különböző vonalakat: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja egy shape szülő diáját. Csak olvasható [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely egy shape 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos, 3D tulajdonságokkal nem rendelkező shape-ok esetén null értéket adhat vissza. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentációra korlátozott azonosítót, amely kiegészítők vagy más kód számára készült. Mivel ezt az értéket a felhasználó vagy programozottan felülírhatja, nem szabad állandó egyedi kulcsként kezelni. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Visszaadja vagy beállítja az shape szélességét pontban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Visszaadja vagy beállítja az shape bal felső sarkának x koordinátáját pontban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Visszaadja vagy beállítja az shape bal felső sarkának y koordinátáját pontban mérve. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja az shape z-sorrendben betöltött pozícióját. A Shapes[0] a z-sorrend hátul lévő shape-ot adja vissza, és a Shapes[Shapes.Count - 1] a legelső shape-ot. Csak olvasható Int32. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helyőrzőt ad hozzá, ha nincs, és a megadott helyőrző tulajdonságait beállítja. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Létrehozza és visszaadja az shape elemeinek tömbjét. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helyőrző shape-et (az elrendezésről és/vagy a fő diáról származó shape, amelyből a jelenlegi shape örökölt). Null érték visszaadása, ha a jelenlegi shape nem örökölt. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Visszaadja a geometriai shape útvonalának másolatát. A koordináták az shape bal felső sarkához viszonyítva vannak. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja az shape bélyegképét. Alapértelmezés szerint a ShapeThumbnailBounds.Shape típusú shape határolókat használ. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja az shape bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Visszaadja a megjelenített tartalom alapján kiszámított vizuális határokat az shape-ra. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez az shape nem helyőrző. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Frissíti az shape geometriáját a [`IGeometryPath`](../igeometrypath) objektumból. A koordinátáknak az shape bal felső sarkához kell viszonyulniuk. Az shape típusát ([`ShapeType`](../geometryshape/shapetype)) egyéni típusra változtatja. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Frissíti az shape geometriáját a [`IGeometryPath`](../igeometrypath) tömbből. A koordinátáknak az shape bal felső sarkához kell viszonyulniuk. Az shape típusát ([`ShapeType`](../geometryshape/shapetype)) egyéni típusra változtatja. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | A Shape tartalmát SVG fájlként menti. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | A Shape tartalmát SVG fájlként menti. |

### Példák

A következő példák bemutatják, hogyan lehet módosítani egy Audio Frame bélyegképet.

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // Hangkeretet ad a diára a megadott pozícióval és mérettel.
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // Képet ad a prezentáció erőforrásaihoz.
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // Beállítja a képet a hangkerethez.
    audioFrame.PictureFormat.Picture.Image = audioImage;
	//Mentse a módosított prezentációt lemezre
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### Lásd még

* osztály [GeometryShape](../geometryshape)
* interfész [IPictureFrame](../ipictureframe)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->