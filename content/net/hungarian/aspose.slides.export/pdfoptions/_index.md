---
title: PdfOptions
second_title: Aspose.Sildes .NET API hivatkozása
description: Lehetővé teszi beállítások megadását, amelyek szabályozzák, hogyan mentődik egy prezentáció PDF formátumban.
type: docs
weight: 4310
url: /hu/aspose.slides.export/pdfoptions/
---
## PdfOptions osztály

Lehetővé teszi azoknak a beállításoknak a megadását, amelyek szabályozzák, hogyan mentődik egy prezentáció PDF formátumban.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [PdfOptions](pdfoptions)() | Alapértelmezett konstruktor. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Tartalmaz egy zászlókészletet, amely meghatározza, hogy milyen hozzáférési engedélyeket kell biztosítani, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. Lásd [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Visszaadja vagy beállítja a felhasználó által meghatározott betűcsaládnevek tömbjét, amelyeket az Aspose.Slides közösnek tekint. Olvasás/írás String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Alkalmazza a megadott átlátszó színt a képre, ha `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Jelzi, hogy a leghatékonyabb tömörítés (az alapértelmezett helyett) minden képre automatikusan ki legyen-e választva. Ha Boolean.true-re van állítva, a prezentáció minden képére a legmegfelelőbb tömörítési algoritmus kerül kiválasztásra, ami a létrejövő PDF dokumentum kisebb méretéhez vezet. A legjobb képtömörítési arány kiválasztása számításigényes, további RAM-ot igényel, és ez az opció alapértelmezés szerint Boolean.false. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | A generált PDF dokumentum kívánt megfelelőségi szintje. Olvasás/írás [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Visszaadja vagy beállítja a betűtípust, amelyet akkor használ, ha a forrásbetűtípus nem található. Olvasás/írás String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | Igaz érték esetén fekete keretet rajzol minden dia köré. Olvasás/írás Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Meghatározza, hogy a betűtípus összes karaktere be legyen-e ágyazva, vagy csak a használt részhalmaz. Olvasás/írás Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Meghatározza, hogy az Aspose.Slides beágyazza-e a közös betűtípusokat ASCII (33..127 kódtartomány) szöveghez. Az 127-nél nagyobb karakterkódok betűtípusai mindig be lesznek ágyazva. A közös betűtípusok listája tartalmazza a PDF alap 14 betűtípusát és a felhasználó által megadott további betűtípusokat. Olvasás/írás Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Visszaadja vagy beállítja a h Gradient vizuális stílusát. Olvasás/írás [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Visszaadja vagy beállítja a kép átlátszó színét. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | Igaz érték esetén az összes OLE adatot a prezentációból beágyazott fájlokká konvertálja a létrejövő PDF-ben. Olvasás/írás Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Lehetővé teszi, hogy beállítások szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. Csak olvasható [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Visszaadja vagy beállítja a JPEG képek minőségét a PDF dokumentumban. Olvasás/írás Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Felhasználói jelszó beállítása a PDF dokumentum védelméhez. Olvasás/írás String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Egy visszahívási objektum, amely a mentés előrehaladását százalékban adja vissza. Lásd [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Jelzi, hogy a szöveget bitmapként kell-e rasterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér stílust. Ez a megközelítés bizonyos betűtípusok esetén javíthatja a szöveg minőségét a létrejövő PDF-ben. Olvasás/írás Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | Igaz érték esetén az összes prezentációban használt metafájlt PNG képpé konvertálja. Olvasás/írás Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákot. Alapértelmezett érték: `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Meghatározza, hogy a mentés során kihagyja-e a JavaScript-hívásokat tartalmazó hiperhivatkozásokat. Olvasás/írás Boolean. Alapértelmezett érték: **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Visszaadja vagy beállítja a módot, amelyben a diák az oldalon helyezkednek el a prezentáció exportálásakor [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Visszaadja vagy beállítja a PDF dokumentumban lévő képek felbontását. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Meghatározza a dokumentumban lévő szöveges tartalom tömörítési típusát. Olvasás/írás [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. Olvasás/írás [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Példák

Az alábbi példa bemutatja, hogyan konvertálhatunk PowerPoint-ot PDF-be egyedi beállításokkal.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Példányosítja a PdfOptions osztályt
	PdfOptions pdfOptions = new PdfOptions();
	// Beállítja a Jpeg minőséget
	pdfOptions.JpegQuality = 90;
	// Beállítja a metafájlok viselkedését
	pdfOptions.SaveMetafilesAsPng = true;
	// Beállítja a szövegtömörítés szintjét
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Meghatározza a PDF szabványt
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Mentés a prezentáció PDF-ként
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Az alábbi példa bemutatja, hogyan konvertálhatunk PowerPoint-ot PDF-be rejtett diákkal.

```csharp
[C#]
// Példányosít egy Presentation osztályt, amely egy PowerPoint fájlt képvisel
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Példányosítja a PdfOptions osztályt
	PdfOptions pdfOptions = new PdfOptions();
	// Hozzáad rejtett diákat
	pdfOptions.ShowHiddenSlides = true;
	// Mentés a prezentáció PDF-ként
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Az alábbi példa bemutatja, hogyan konvertálhatunk PowerPoint-ot jelszóval védett PDF-be.

```csharp
[C#]
// Példányosít egy Presentation objektumot, amely egy PowerPoint fájlt képvisel
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Példányosítja a PdfOptions osztályt
	PdfOptions pdfOptions = new PdfOptions();
	// Beállítja a PDF jelszót és a hozzáférési engedélyeket
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Mentés a prezentáció PDF-ként
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Az alábbi példa bemutatja, hogyan konvertálhatunk PowerPoint-ot PDF-be jegyzetekkel.

```csharp
[C#]
// Példányosít egy Presentation objektumot, amely egy prezentáció fájlt képvisel
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// Diatípus és méret beállítása
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### Lásd még

* osztály [SaveOptions](../saveoptions)
* interfész [IPdfOptions](../ipdfoptions)
* névtér [Aspose.Slides.Export](../../aspose.slides.export)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->