---
title: PdfOptions
second_title: Aspose.Sildes .NET API referencia
description: Lehetővé teszi azon opciók megadását, amelyek szabályozzák, hogyan mentődik a prezentáció PDF formátumban.
type: docs
weight: 4350
url: /hu/aspose.slides.export/pdfoptions/
---
## PdfOptions osztály

Lehetővé teszi azon beállítások megadását, amelyek szabályozzák, hogy a prezentáció hogyan kerül mentésre PDF formátumban.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Konstruktorok

| Name | Description |
| --- | --- |
| [PdfOptions](pdfoptions)() | Alapértelmezett konstruktor. |

## Tulajdonságok

| Name | Description |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Tartalmaz egy flag halmazt, amely meghatározza, hogy milyen hozzáférési engedélyeket kell megadni, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. Lásd [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Visszaadja vagy beállítja a felhasználó által megadott betűcsaládnevek tömbjét, amelyeket az Aspose.Slides közösnek kell tekintse. Olvasás/írás String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Alkalmazza a megadott átlátszó színt a képre, ha `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Jelzi, hogy a minden képre vonatkozó legoptimálisabb tömörítést (az alapértelmezett helyett) automatikusan kell-e kiválasztani. Ha Boolean.true értékre van állítva, a prezentáció minden képe esetén a legmegfelelőbb tömörítési algoritmus lesz kiválasztva, ami a létrejövő PDF dokumentum kisebb méretéhez vezet. A legjobb képtömörítési arány kiválasztása számításigényes és további RAM-ot igényel, és ez a beállítás alapértelmezés szerint Boolean.false. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | A generált PDF dokumentum kívánt megfelelőségi szintje. Olvasás/írás [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Visszaadja vagy beállítja a betűtípust, amelyet akkor használ, ha a forrás betűtípus nem található. Olvasás/írás String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | Igaz érték esetén fekete keretet rajzol minden diára. Olvasás/írás Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Meghatározza, hogy a betűtípus összes karaktere be legyen-e ágyazva, vagy csak a használt részhalmaz. Olvasás/írás Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Meghatározza, hogy az Aspose.Slides beágyazza-e a gyakori betűtípusokat az ASCII (33..127 kódtartomány) szöveghez. A 127-nél nagyobb karakterkódok betűtípusai mindig be vannak ágyazva. A gyakori betűtípusok listája tartalmazza a PDF alap 14 betűtípusát és a felhasználó által megadott további betűtípusokat. Olvasás/írás Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Visszaadja vagy beállítja a gradiens vizuális stílusát. Olvasás/írás [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Visszaadja vagy beállítja a kép átlátszó színét. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | Igaz érték esetén az összes OLE adatot a prezentációból beágyazott fájlokká konvertálja a létrejövő PDF-ben. Olvasás/írás Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Lehetővé teszi azoknak a beállításoknak, amelyek szabályozzák a tintaobjektusok megjelenését az exportált dokumentumban. Csak olvasható [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Visszaadja vagy beállítja a PDF dokumentumban lévő JPEG képek minőségét meghatározó értéket. Olvasás/írás Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Felhasználói jelszó beállítása a PDF dokumentum védelméhez. Olvasás/írás String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Egy visszahívási objektumot képvisel a mentési folyamat százalékos frissítéseihez. Lásd [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Jelzi, hogy a szöveget bitmapként kell-e raszterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér formázást. Ez a megközelítés bizonyos betűtípusok esetén javíthatja a szöveg minőségét a létrejövő PDF-ben. Olvasás/írás Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | Igaz érték esetén az összes prezentációban használt metafájlt PNG képpé konvertálja. Olvasás/írás Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Megadja, hogy a generált dokumentumban legyenek-e rejtett diák vagy sem. Alapértelmezett érték `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Megadja, hogy a prezentáció mentésekor kihagyja-e a JavaScript hívású hiperhivatkozásokat. Olvasás/írás Boolean. Az alapértelmezett érték **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Visszaadja vagy beállítja azt a módot, ahogyan a diák az oldalon elhelyezésre kerülnek a prezentáció exportálásakor [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Visszaadja vagy beállítja a PDF dokumentumban lévő képek felbontását meghatározó értéket. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Megadja a dokumentum összes szöveges tartalmára alkalmazandó tömörítési típust. Olvasás/írás [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. Olvasás/írás [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Példák

Az alábbi példa bemutatja, hogyan konvertálhatja a PowerPointot PDF-re egyéni beállításokkal.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Példányosítja a PdfOptions osztályt
	PdfOptions pdfOptions = new PdfOptions();
	// Beállítja a JPEG minőséget
	pdfOptions.JpegQuality = 90;
	// Beállítja a metafájlok viselkedését
	pdfOptions.SaveMetafilesAsPng = true;
	// Beállítja a szöveg tömörítési szintjét
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Meghatározza a PDF szabványt
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Mentse a prezentációt PDF-ként
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Az alábbi példa bemutatja, hogyan konvertálhatja a PowerPointot PDF-re rejtett diák használatával.

```csharp
[C#]
// Példányosít egy Presentation osztályt, amely egy PowerPoint fájlt képvisel
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Példányosítja a PdfOptions osztályt
	PdfOptions pdfOptions = new PdfOptions();
	// Hozzáadja a rejtett diák
	pdfOptions.ShowHiddenSlides = true;
	// Mentse a prezentációt PDF-ként
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Az alábbi példa bemutatja, hogyan konvertálhatja a PowerPointot jelszóval védett PDF-be.

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
	// Mentse a prezentációt PDF-ként
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Az alábbi példa bemutatja, hogyan konvertálhatja a PowerPointot PDF-re megjegyzésekkel.

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