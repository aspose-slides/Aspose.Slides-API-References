---
title: OleObjectFrame
second_title: Aspose.Sildes .NET API Referenciához
description: Egy dián található OLE objektumot reprezentál.
type: docs
weight: 9210
url: /hu/aspose.slides/oleobjectframe/
---
## OleObjectFrame osztály

Olyan OLE objektumot ábrázol, amely egy dián jelenik meg.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja a formához társított alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja a formához társított alternatív szöveg címsorát. Olvasás/írás String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Lehetővé teszi az alap IGraphicalObject interfész lekérését. Csak olvasható [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A tulajdonság meghatározza, hogyan jelenik meg a forma fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja a forma csatlakozási pontjainak számát. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja a forma egyéni adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a forma pixeles effektusait tartalmazza. Megjegyzés: bizonyos típusú formák esetén null értéket adhat vissza, amelyeknek nincs effektus tulajdonsága. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Lekéri vagy beállítja az OLE beágyazott adatokkal kapcsolatos információkat. Olvasás/írás [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Visszaadja a beágyazott OLE objektum fájlnevét |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Visszaadja a beágyazott OLE objektum útvonalát |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely a forma kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú formák esetén null értéket adhat vissza, amelyeknek nincs kitöltési tulajdonsága. Csak olvasható [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja a forma keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Visszaadja a forma zárolásait. Csak olvasható [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lekéri vagy beállítja a forma magasságát pontokban. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Meghatározza, hogy a forma rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hivatkozáskezelőt. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér feletti állapotra definiált hivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lekéri vagy beállítja a „Megjelölés dekorációként” beállítást. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Meghatározza, hogy a forma csoportosított-e. Csak olvasható Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Meghatározza, hogy egy objektum ikonként látható-e. Olvasás/írás Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Meghatározza, hogy egy objektum külső fájlra van-e hivatkozva. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Meghatározza, hogy a forma TextHolder_PPT-e. Csak olvasható Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely a forma vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú formák esetén null értéket adhat vissza, amelyeknek nincs vonal tulajdonsága. Csak olvasható [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Visszaadja a hivatkozott fájl teljes útvonalát. A rövid fájlnév lesz használva. Csak olvasható String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Visszaadja a hivatkozott fájl teljes útvonalát. A hosszú fájlnév lesz használva. Olvasás/írás String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | Visszaadja a hivatkozott fájl relatív útvonalát, ha létezik, egyébként üres karakterláncot ad vissza. Csak olvasható String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja a forma nevét. Nem lehet null. Ha szükséges, használjon üres karakterláncot. Olvasás/írás String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Visszaadja vagy beállítja egy objektum nevét. Olvasás/írás String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Visszaadja egy objektum ProgID-jét. Csak olvasható String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy diára korlátozott egyedi azonosítót, amely a forma élettartama alatt állandó, és lehetővé teszi a PowerPoint vagy az interop kód számára, hogy megbízhatóan hivatkozzon a formára a dokumentum bármely részéről. Csak olvasható UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha a forma csoportosított. Egyébként null értéket ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja a forma helyőrzőjét. Null értéket ad, ha a formának nincs helyőrzője. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja a dia szülő prezentációját. Csak olvasható [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers forma keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja a megadott forma z-tengely körüli elforgatásának fokszámát. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellenkező irányt. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Visszaadja a forma zárolásait. Csak olvasható [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 tulajdonság) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja a forma szülő diáját. Csak olvasható [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Visszaadja az OleObject képtöltő tulajdonságok objektumát. Csak olvasható [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Visszaadja vagy beállítja az OleObject ikon címét. Olvasás/írás String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a forma 3D effektus tulajdonságait tartalmazza. Megjegyzés: bizonyos típusú formák esetén null értéket adhat vissza, amelyeknek nincs 3D tulajdonsága. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentációra korlátozott azonosítót, amelyet a kiegészítők vagy más kód használhat. Mivel ezt az értéket a felhasználó vagy a kód módosíthatja, nem tekinthető állandó egyedi kulcsnak. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Meghatározza, hogy a hivatkozott beágyazott objektum automatikusan frissüljön-e a prezentáció megnyitásakor vagy nyomtatásakor. Olvasás/írás Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lekéri vagy beállítja a forma szélességét pontokban. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lekéri vagy beállítja a forma bal felső sarkának x koordinátáját pontokban. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lekéri vagy beállítja a forma bal felső sarkának y koordinátáját pontokban. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja egy forma z-sorrendbeli pozícióját. A Shapes[0] a z-sorrend hátsó elemét, a Shapes[Shapes.Count - 1] pedig az első elemet adja vissza. Csak olvasható Int32. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helyőrzőt ad hozzá, ha nincs, és beállítja a helyőrző tulajdonságait a megadottra. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helyőrző formát (a layout vagy a mester diáról származó formát, amelyről a jelenlegi forma örököl). Null érték visszatér, ha a jelenlegi forma nem örököl. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja a forma bélyegképét. Alapértelmezésben a ShapeThumbnailBounds.Shape bélyegkép határoló típust használja. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja a forma bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lekérdezi a forma vizuális határait, amelyek a megjelenített tartalomból számítódnak. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez a forma nem helyőrző. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Beállítja az OLE beágyazott adatokkal kapcsolatos információkat. Ez a módszer módosítja az objektum tulajdonságait, hogy tükrözze az új adatokat, és a IsObjectLink jelzőt hamisra állítja, jelezve, hogy az OLE objektum beágyazott. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Elmenti a Shape tartalmát SVG fájlként. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Elmenti a Shape tartalmát SVG fájlként. |

### Példák

Az alábbi példa azt mutatja be, hogyan lehet elérni az OLE Object kereteket.

```csharp
[C#]
// Betölti a PPTX-et egy prezentáció objektumba
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // Eléri az első diát
    ISlide sld = pres.Slides[0];
    // Átkonvertálja a alakzatot OleObjectFrame típusra
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // Beolvassa az OLE objektumot és leírja a lemezre
    if (oleObjectFrame != null)
    {
        // Lekéri a beágyazott fájl adatokat
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Lekéri a beágyazott fájl kiterjesztését
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // Létrehozza az elérési utat a kinyert fájl mentéséhez
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // Elmenti a kinyert adatokat
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### Lásd még

* osztály [GraphicalObject](../graphicalobject)
* interfész [IOleObjectFrame](../ioleobjectframe)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->