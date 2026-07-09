---
title: PdfOptions
second_title: Aspose.Sildes .NET API Referenciája
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan kerül egy prezentáció mentésre Pdf formátumban.
type: docs
weight: 4330
url: /hu/aspose.slides.export/pdfoptions/
---
## PdfOptions osztály

Lehetőségeket biztosít, amelyek szabályozzák, hogyan kerül egy prezentáció mentésre Pdf formátumban.

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
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Tartalmaz egy zászlókészletet, amely meghatározza, hogy mely hozzáférési engedélyek legyenek megadva, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. Lásd [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Visszaadja vagy beállítja a felhasználó által definiált betűcsaládnevek tömbjét, amelyekről az Aspose.Slides azt feltételezi, hogy gyakoriak. Olvasás/írás String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Alkalmazza a megadott átlátszó színt egy képre, ha `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Azt jelzi, hogy minden kép esetén a leghatékonyabb tömörítést (az alapértelmezett helyett) kell-e automatikusan kiválasztani. Ha Boolean.true értékre van állítva, a prezentáció minden képére a legmegfelelőbb tömörítési algoritmus lesz kiválasztva, ami a létrejövő PDF-dokumentum kisebb méretéhez vezet. A legjobb képtömörítési arány kiválasztása számítási szempontból költséges és további RAM-ot igényel, és ez a beállítás alapértelmezés szerint Boolean.false. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | A generált PDF-dokumentum kívánt megfelelőségi szintje. Olvasás/írás [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Visszaadja vagy beállítja a betűtípust, ha a forrás betűtípus nem található. Olvasás/írás String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True, ha fekete keretet kell rajzolni minden diára. Olvasás/írás Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Megadja, hogy a betűtípus összes karaktere legyen-e beágyazva, vagy csak a használt részhalmaz. Olvasás/írás Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Megadja, hogy az Aspose.Slides beágyazza-e a gyakori betűtípusokat ASCII (33..127 kódtartomány) szöveghez. A 127 fölötti karakterkódok betűtípusai mindig be vannak ágyazva. A gyakori betűtípusok listája tartalmazza a PDF alap 14 betűtípusát és a felhasználó által megadott további betűtípusokat. Olvasás/írás Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Visszaadja vagy beállítja a gradient vizuális stílusát. Olvasás/írás [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Visszaadja vagy beállítja a kép átlátszó színét. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | True, ha az összes OLE adatot a prezentációból beágyazott fájlokká kell konvertálni a létrejövő PDF-ben. Olvasás/írás Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Az exportált dokumentumban az Ink objektumok megjelenését szabályozó beállításokat biztosít. Csak-olvasás [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Visszaadja vagy beállítja a JPEG képek minőségét a PDF-dokumentumban. Olvasás/írás Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | A PDF-dokumentum védelmére szolgáló felhasználói jelszó beállítása. Olvasás/írás String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | A mentési folyamat százalékos frissítéseihez tartozó visszahívási objektumot képviseli. Lásd [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Azt jelzi, hogy a szöveget bitmapként kell-e rasterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér stílust. Ez a megközelítés bizonyos betűtípusoknál javíthatja a szöveg minőségét a létrejövő PDF-ben. Olvasás/írás Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True, ha a prezentációban használt összes metafájlt PNG képekké kell konvertálni. Olvasás/írás Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Megadja, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. Az alapértelmezett érték `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Megadja, hogy a prezentáció mentésekor kihagyandók-e a JavaScript hívású hiperhivatkozások. Olvasás/írás Boolean. Az alapértelmezett érték **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Visszaadja vagy beállítja azt a módot, ahogyan a diák az oldalon elhelyezésre kerülnek a prezentáció exportálásakor [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Visszaadja vagy beállítja a PDF-dokumentumban lévő képek felbontását meghatározó értéket. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Megadja a dokumentum összes szöveges tartalmára alkalmazandó tömörítési típust. Olvasás/írás [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódjon-e vagy megszakadjon. Olvasás/írás [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Példák

Az alábbi példa bemutatja, hogyan lehet PowerPointot PDF-be konvertálni egyedi beállításokkal.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Létrehozza a PdfOptions osztályt
	PdfOptions pdfOptions = new PdfOptions();
	// Beállítja a JPEG minőséget
	pdfOptions.JpegQuality = 90;
	// Beállítja a metafájlok viselkedését
	pdfOptions.SaveMetafilesAsPng = true;
	// Beállítja a szöveg tömörítési szintjét
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Meghatározza a PDF szabványt
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Mentés a prezentáció PDF-ként
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Az alábbi példa bemutatja, hogyan lehet PowerPointot PDF-be konvertálni rejtett diák használatával.

```csharp
[C#]
// Létrehozza a Presentation osztályt, amely egy PowerPoint fájlt képvisel
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Létrehozza a PdfOptions osztályt
	PdfOptions pdfOptions = new PdfOptions();
	// Hozzáadja a rejtett diákat
	pdfOptions.ShowHiddenSlides = true;
	// Mentés a prezentációt PDF-ként
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Az alábbi példa bemutatja, hogyan lehet PowerPointot jelszóval védett PDF-be konvertálni.

```csharp
[C#]
// Létrehozza a Presentation objektumot, amely egy PowerPoint fájlt képvisel
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Létrehozza a PdfOptions osztályt
	PdfOptions pdfOptions = new PdfOptions();
	// Beállítja a PDF jelszót és a hozzáférési engedélyeket
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Mentés a prezentációt PDF-ként
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Az alábbi példa bemutatja, hogyan lehet PowerPointot PDF-be konvertálni a jegyzetekkel.

```csharp
[C#]
// Létrehozza a Presentation objektumot, amely egy prezentációfájlt képvisel
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
* interface [IPdfOptions](../ipdfoptions)
* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->