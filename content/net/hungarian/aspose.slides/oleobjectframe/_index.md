---
title: OleObjectFrame
second_title: Aspose.Sildes .NET API hivatkozás
description: OLE objektumot képvisel egy dián.
type: docs
weight: 9250
url: /hu/aspose.slides/oleobjectframe/
---
## OleObjectFrame osztály

OLE objektumot képvisel egy dián.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Visszaadja vagy beállítja az alakzathoz tartozó alternatív szöveget. Olvasás/írás String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Visszaadja vagy beállítja az alakzathoz kapcsolódó alternatív szöveg címét. Olvasás/írás String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Lehetővé teszi a(z) IGraphicalObject alap interfész lekérését. Csak olvasható [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A tulajdonság meghatározza, hogy az alakzat hogyan jelenik meg fekete-fehér megjelenítési módban. Olvasás/írás [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Visszaadja az alakzaton lévő csatlakozási pontok számát. Csak olvasható Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Visszaadja az alakzat egyéni adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Visszaadja az EffectFormat objektumot, amely a alakzatra alkalmazott pixelhatásokat tartalmazza. Megjegyzés: bizonyos, hatás tulajdonságokkal nem rendelkező alakzatok esetén null értéket adhat vissza. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Lekéri vagy beállítja az OLE beágyazott adatokról szóló információkat. Olvasás/írás [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Visszaadja a beágyazott OLE objektum fájlnevét |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Visszaadja a beágyazott OLE objektum elérési útját |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Visszaadja a FillFormat objektumot, amely az alakzat kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzatok esetén, amelyeknek nincs kitöltési tulajdonsága, null értéket adhat vissza. Csak olvasható [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Visszaadja vagy beállítja az alakzat keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Visszaadja az alakzat zárolásait. Csak olvasható [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Lekéri vagy beállítja az alakzat magasságát, pontban mérve. Olvasás/írás Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Meghatározza, hogy az alakzat rejtett-e. Olvasás/írás Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Visszaadja a hiperhivatkozás-kezelőt. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér fölé viszésre definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Lekéri vagy beállítja a 'Mark as decorative' opciót. Olvasás/írás Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Meghatározza, hogy az alakzat csoportosítva van-e. Csak olvasható Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Meghatározza, hogy az objektum ikonként látható-e. Olvasás/írás Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Meghatározza, hogy az objektum külső fájlra hivatkozik-e. Csak olvasható Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Meghatározza, hogy az alakzat TextHolder_PPT-e. Csak olvasható Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Visszaadja a LineFormat objektumot, amely az alakzat vonalformázási tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzatoknál, amelyeknek nincs vonal tulajdonsága, null értéket adhat vissza. Csak olvasható [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Visszaadja a hivatkozott fájl teljes elérési útját. Rövid fájlnév lesz használva. Csak olvasható String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Visszaadja a hivatkozott fájl teljes elérési útját. Hosszú fájlnév lesz használva. Olvasás/írás String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | Visszaadja a hivatkozott fájl relatív útját, ha létezik, egyébként üres stringet ad vissza. Csak olvasható String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Visszaadja vagy beállítja egy alakzat nevét. Nem lehet null. Szükség esetén üres stringet használjon. Olvasás/írás String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Visszaadja vagy beállítja egy objektum nevét. Olvasás/írás String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Visszaadja egy objektum ProgID-ját. Csak olvasható String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Visszaad egy diára korlátozott egyedi azonosítót, amely a forma életciklusáig állandó marad, és lehetővé teszi a PowerPoint vagy interop kód számára, hogy a dokumentum bármely pontjáról megbízhatóan hivatkozzon a formára. Csak olvasható UInt32. Lásd még [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Visszaadja a szülő GroupShape objektumot, ha az alakzat csoportosított. Egyébként null értéket ad vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Visszaadja egy alakzat helykitöltőjét. Null értéket ad vissza, ha az alakzatnak nincs helykitöltője. Csak olvasható [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Visszaadja egy dia szülő prezentációját. Csak olvasható [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Visszaadja vagy beállítja a nyers alakzat keretének tulajdonságait. Olvasás/írás [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Visszaadja vagy beállítja, hogy a megadott alakzat hány fokkal van elforgatva a z-tengely körül. A pozitív érték az óramutató járásával megegyező forgást jelzi; a negatív érték az ellentétes irányt. Olvasás/írás Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Visszaadja az alakzat zárolásait. Csak olvasható [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 tulajdonság) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Visszaadja egy alakzat szülő diáját. Csak olvasható [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Visszaadja az OleObject képkitöltési tulajdonságok objektumát. Csak olvasható [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Visszaadja vagy beállítja az OleObject ikon címét. Olvasás/írás String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely egy alakzat 3D hatás tulajdonságait tartalmazza. Megjegyzés: bizonyos alakzatoknál, amelyeknek nincs 3D tulajdonsága, null értéket adhat vissza. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Visszaad egy belső, prezentációra korlátozott azonosítót, amely kiegészítők vagy más kód számára készült. Mivel ezt az értéket a felhasználó vagy programozott módon át lehet rendelni, nem tekinthető állandó egyedi kulcsnak. Csak olvasható UInt32. Lásd még [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Meghatározza, hogy a hivatkozott beágyazott objektum automatikusan frissül-e a prezentáció megnyitásakor vagy nyomtatásakor. Olvasás/írás Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Lekéri vagy beállítja az alakzat szélességét, pontban mérve. Olvasás/írás Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Lekéri vagy beállítja az alakzat bal felső sarkának x koordinátáját, pontban mérve. Olvasás/írás Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Lekéri vagy beállítja az alakzat bal felső sarkának y koordinátáját, pontban mérve. Olvasás/írás Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Visszaadja egy alakzat z-sorrendben elfoglalt pozícióját. A Shapes[0] a z-sorrend hátul lévő alakzatot adja vissza, a Shapes[Shapes.Count - 1] pedig a frontot. Csak olvasható Int32. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Új helykitöltőt ad hozzá, ha nincs, és a helykitöltő tulajdonságait egy megadottra állítja. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Visszaad egy alap helykitöltő alakzatot (az elrendezés és/vagy mesterdia alakzata, amelyből a jelenlegi alakzat örököl). Null értéket ad vissza, ha a jelenlegi alakzat nem örököl. |
| [GetImage](../../aspose.slides/shape/getimage)() | Visszaadja az alakzat bélyegképét. Alapértelmezésként a ShapeThumbnailBounds.Shape bélyegképhatároló típust használja. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Visszaadja az alakzat bélyegképét. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Lekéri az alakzat vizuális határait, amelyeket a renderelt tartalom alapján számol. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Meghatározza, hogy ez az alakzat nem helykitöltő. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Beállítja az OLE beágyazott adatokról szóló információkat. Ez a metódus módosítja az objektum tulajdonságait az új adatok tükrözésére, és az IsObjectLink jelzőt false értékre állítja, ami azt jelzi, hogy az OLE objektum beágyazott. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Elmenti az alakzat tartalmát SVG fájlként. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Elmenti az alakzat tartalmát SVG fájlként. |

### Példák

Az alábbi példa bemutatja, hogyan lehet elérni az OLE objektum kereteket.

```csharp
[C#]
// Betölti a PPTX-et egy prezentáció objektumba
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // Eléri az első diát
    ISlide sld = pres.Slides[0];
    // Átkonvertálja az alakzatot OleObjectFrame típusra
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // Beolvassa az OLE objektumot és leírja a lemezre
    if (oleObjectFrame != null)
    {
        // Lekéri a beágyazott fájl adatait
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Lekéri a beágyazott fájl kiterjesztését
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // Létrehozza az elérési utat a kicsomagolt fájl mentéséhez
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // Mentette a kicsomagolt adatokat
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
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->