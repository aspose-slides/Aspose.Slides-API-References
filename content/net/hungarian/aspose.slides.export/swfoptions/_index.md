---
title: SwfOptions
second_title: Aspose.Sildes .NET API-referencia
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik egy prezentáció Swf formátumban.
type: docs
weight: 4510
url: /hu/aspose.slides.export/swfoptions/
---
## SwfOptions osztály

Lehetőségeket biztosít, amelyek meghatározzák, hogyan mentődik a bemutató Swf formátumban.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [SwfOptions](swfoptions)() | Alapértelmezett konstruktor. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Megadja, hogy a generált SWF dokumentum tömörítve legyen-e vagy sem. Alapértelmezett érték a `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Visszaadja vagy beállítja a betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található. Olvasás-írás típusú String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | A helyi menü engedélyezése/letiltása. Alapértelmezett érték igaz. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Visszaadja vagy beállítja a gradient vizuális stílusát. Olvasás/írás [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Megadja a JPEG képek minőségét. Alapértelmezett érték 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | A kép, amely a megjelenítő jobb felső sarkában logóként jelenik meg. A képnek 32x64 pixel PNG képnek kell lennie, ellenkező esetben a logó helytelenül jelenhet meg. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | A logó teljes hiperhivatkozási címét adja vissza vagy állítja be. Csak akkor van hatása, ha egy [`LogoImageBytes`](./logoimagebytes) van megadva. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Egy visszahívási objektumot képvisel a mentés előrehaladási százalékos frissítéseihez. Lásd [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Alsó ablaktábla megjelenítése/elrejtése. Felülírható a flashvars-ben. Alapértelmezett érték igaz. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Teljes képernyős gomb megjelenítése/elrejtése. Felülírható a flashvars-ben. Alapértelmezett érték igaz. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. Alapértelmezett érték a `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Bal ablaktábla megjelenítése/elrejtése. Felülírható a flashvars-ben. Alapértelmezett érték igaz. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Megadja, hogy a lapok körüli keret megjelenjen-e. Alapértelmezett érték igaz. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Oldal léptető megjelenítése/elrejtése. Felülírható a flashvars-ben. Alapértelmezett érték igaz. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Keresési szekció megjelenítése/elrejtése. Felülírható a flashvars-ben. Alapértelmezett érték igaz. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Az egész felső ablaktábla megjelenítése/elrejtése. Felülírható a flashvars-ben. Alapértelmezett érték igaz. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Megadja, hogy a mentés során kihagyja-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Olvasás/írás típusú Boolean. Az alapértelmezett érték **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | A diak oldalra történő elhelyezésének módját adja vissza vagy állítja be a prezentáció exportálásakor [`ISlidesLayoutOptions`](../islideslayoutoptions). Ez a tulajdonság nem támogatja az [`HandoutLayoutingOptions`](../handoutlayoutingoptions) típusú objektumok hozzárendelését. |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Bal ablaktábla nyitott állapotú indulás. Felülírható a flashvars-ben. Alapértelmezett érték hamis. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Megadja, hogy a generált SWF dokumentum tartalmazza-e az integrált dokumentum megjelenítőt vagy sem. Alapértelmezett érték a `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. Olvasás/írás [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Példák

Az alábbi példa bemutatja, hogyan lehet a PowerPoint-ot SWF Flash formátumba konvertálni.

```csharp
[C#]
// Példányosít egy Presentation objektumot, amely egy prezentációs fájlt képvisel
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // A prezentáció és a jegyzetoldalak mentése
    presentation.Save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
    swfOptions.ViewerIncluded = true;
    presentation.Save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
}
```

### Lásd még

* osztály [SaveOptions](../saveoptions)
* interfész [ISwfOptions](../iswfoptions)
* névtér [Aspose.Slides.Export](../../aspose.slides.export)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->