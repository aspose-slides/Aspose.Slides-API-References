---
title: SwfOptions
second_title: Aspose.Sildes .NET API hivatkozás
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik a prezentáció Swf formátumban.
type: docs
weight: 4550
url: /hu/aspose.slides.export/swfoptions/
---
## SwfOptions osztály

Lehetőségeket biztosít, amelyek szabályozzák, hogyan kerül mentésre a prezentáció Swf formátumban.

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
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Megadja, hogy a generált SWF dokumentum tömörítve legyen-e vagy sem. Alapértelmezett érték `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Visszaadja vagy beállítja a betűtípust, amelyet akkor használnak, ha a forrás betűtípusa nem található. Olvasás-írás String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | A helyi menü engedélyezése/letiltása. Alapértelmezett érték true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Visszaadja vagy beállítja a gradient vizuális stílusát. Olvasás/írás [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Megadja a JPEG képek minőségét. Alapértelmezett érték 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Kép, amely a megjelenítő jobb felső sarkában logóként jelenik meg. A képnek 32x64 pixel PNG formátumúnak kell lennie, ellenkező esetben a logó helytelenül jelenhet meg. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Visszaadja vagy beállítja a logó teljes hiperhivatkozás-címét. Csak akkor van hatása, ha a [`LogoImageBytes`](./logoimagebytes) meg van adva. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Egy visszahívási objektumot képvisel a mentési folyamat százalékos frissítéseihez. Lásd [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Alsó ablaktábla megjelenítése/elrejtése. Flashvars-ban felülírható. Alapértelmezett érték true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | Teljes képernyős gomb megjelenítése/elrejtése. Flashvars-ban felülírható. Alapértelmezett érték true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett érték `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | Bal ablaktábla megjelenítése/elrejtése. Flashvars-ban felülírható. Alapértelmezett érték true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Megadja, hogy a lapok körüli keret megjelenjen-e. Alapértelmezett érték true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Oldal léptető megjelenítése/elrejtése. Flashvars-ban felülírható. Alapértelmezett érték true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | Keresési szakasz megjelenítése/elrejtése. Flashvars-ban felülírható. Alapértelmezett érték true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Teljes felső ablaktábla megjelenítése/elrejtése. Flashvars-ban felülírható. Alapértelmezett érték true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívású hiperhivatkozásokat. Olvasás/írás Boolean. Az alapértelmezett érték **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Visszaadja vagy beállítja a módot, amelyben a diák az oldalra kerülnek a [`ISlidesLayoutOptions`](../islideslayoutoptions) prezentáció exportálásakor. Ez a tulajdonság nem támogatja [`HandoutLayoutingOptions`](../handoutlayoutingoptions) típusú objektumok hozzárendelését. |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Bal ablaktábla nyitott állapotú indulás. Flashvars-ban felülírható. Alapértelmezett érték false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Megadja, hogy a generált SWF dokumentum tartalmazza-e az integrált dokumentum megjelenítőt vagy sem. Alapértelmezett érték `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Visszaadja vagy beállítja egy olyan objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad. Olvasás/írás [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Példák

A következő példa bemutatja, hogyan konvertálható a PowerPoint SWF Flash formátumba.

```csharp
[C#]
// Hozzon létre egy Presentation objektumot, amely egy prezentációs fájlt képvisel
using (Presentation presentation = new Presentation("HelloWorld.pptx"))
{
    SwfOptions swfOptions = new SwfOptions();
    swfOptions.ViewerIncluded = false;
    INotesCommentsLayoutingOptions notesOptions = swfOptions.NotesCommentsLayouting;
    notesOptions.NotesPosition = NotesPositions.BottomFull;
    // Prezentáció és jegyzetoldalak mentése
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