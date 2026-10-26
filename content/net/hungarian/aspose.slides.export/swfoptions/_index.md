---
title: SwfOptions
second_title: Aspose.Sildes .NET API referenciája
description: Lehetővé teszi az opciók megadását, amelyek szabályozzák, hogyan mentődik a prezentáció Swf formátumban.
type: docs
weight: 4530
url: /hu/aspose.slides.export/swfoptions/
---
## SwfOptions osztály

Lehetővé teszi a beállítások megadását, amelyek meghatározzák, hogyan mentődik a prezentáció Swf formátumban.

```csharp
public class SwfOptions : SaveOptions, ISwfOptions
```

## Konstruktorok

| Name | Description |
| --- | --- |
| [SwfOptions](swfoptions)() | Alapértelmezett konstruktor. |

## Tulajdonságok

| Name | Description |
| --- | --- |
| [Compressed](../../aspose.slides.export/swfoptions/compressed) { get; set; } | Megadja, hogy a generált SWF dokumentum legyen-e tömörítve vagy sem. Alapértelmezett érték `true`. |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Visszaadja vagy beállítja a használandó betűkészletet, ha a forrás betűkészlet nem található. Olvasás-írás String. |
| [EnableContextMenu](../../aspose.slides.export/swfoptions/enablecontextmenu) { get; set; } | A helyi menü engedélyezése vagy letiltása. Alapértelmezett érték true. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Visszaadja vagy beállítja a színátmenet vizuális stílusát. Olvasás-írás [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [JpegQuality](../../aspose.slides.export/swfoptions/jpegquality) { get; set; } | Megadja a JPEG képek minőségét. Alapértelmezett érték 95. |
| [LogoImageBytes](../../aspose.slides.export/swfoptions/logoimagebytes) { get; set; } | Az a kép, amely a néző jobb felső sarkában logóként jelenik meg. A képnek 32x64 képpont méretű PNG-nek kell lennie, egyébként a logó helytelenül jelenhet meg. |
| [LogoLink](../../aspose.slides.export/swfoptions/logolink) { get; set; } | Visszaadja vagy beállítja a logó teljes hiperhivatkozási címét. Csak akkor van hatása, ha egy [`LogoImageBytes`](./logoimagebytes) van megadva. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Egy visszahívási objektumot képvisel a mentés előrehaladási frissítései százalékban. Lásd [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowBottomPane](../../aspose.slides.export/swfoptions/showbottompane) { get; set; } | Az alsó ablaktábla megjelenítése/elrejtése. Flashvars-okban felülírható. Alapértelmezett érték true. |
| [ShowFullScreen](../../aspose.slides.export/swfoptions/showfullscreen) { get; set; } | A teljes képernyős gomb megjelenítése/elrejtése. Flashvars-okban felülírható. Alapértelmezett érték true. |
| [ShowHiddenSlides](../../aspose.slides.export/swfoptions/showhiddenslides) { get; set; } | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett érték `false`. |
| [ShowLeftPane](../../aspose.slides.export/swfoptions/showleftpane) { get; set; } | A bal ablaktábla megjelenítése/elrejtése. Flashvars-okban felülírható. Alapértelmezett érték true. |
| [ShowPageBorder](../../aspose.slides.export/swfoptions/showpageborder) { get; set; } | Megadja, hogy a lapok körüli keret megjelenjen-e. Alapértelmezett érték true. |
| [ShowPageStepper](../../aspose.slides.export/swfoptions/showpagestepper) { get; set; } | Az oldal léptető megjelenítése/elrejtése. Flashvars-okban felülírható. Alapértelmezett érték true. |
| [ShowSearch](../../aspose.slides.export/swfoptions/showsearch) { get; set; } | A keresési szakasz megjelenítése/elrejtése. Flashvars-okban felülírható. Alapértelmezett érték true. |
| [ShowTopPane](../../aspose.slides.export/swfoptions/showtoppane) { get; set; } | Az egész felső ablaktábla megjelenítése/elrejtése. Flashvars-okban felülírható. Alapértelmezett érték true. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Megadja, hogy a prezentáció mentésekor kihagyjuk-e a JavaScript hívásokat tartalmazó hiperhivatkozásokat. Olvasás-írás Boolean. Az alapértelmezett érték **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/swfoptions/slideslayoutoptions) { get; set; } | Visszaadja vagy beállítja azt a módot, amelyben a diák a lapra kerülnek egy prezentáció [`ISlidesLayoutOptions`](../islideslayoutoptions) exportálásakor. Ez a tulajdonság nem támogatja a [`HandoutLayoutingOptions`](../handoutlayoutingoptions) típusú objektumok hozzárendelését. |
| [StartOpenLeftPane](../../aspose.slides.export/swfoptions/startopenleftpane) { get; set; } | Az indulás nyitott bal ablaktáblával. Flashvars-okban felülírható. Alapértelmezett érték false. |
| [ViewerIncluded](../../aspose.slides.export/swfoptions/viewerincluded) { get; set; } | Megadja, hogy a generált SWF dokumentum tartalmazza-e az integrált dokumentumnézőt vagy sem. Alapértelmezett érték `true`. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Visszaad vagy beállít egy objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. Olvasás-írás [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Példák

A következő példa bemutatja, hogyan lehet a PowerPoint-ot SWF Flash formátumba konvertálni.

```csharp
[C#]
// Példányosít egy Presentation objektumot, amely egy prezentációs fájlt képvisel
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