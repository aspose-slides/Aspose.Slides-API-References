---
title: PdfOptions
second_title: Aspose.Sildes pro .NET API Reference
description: Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu PDF.
type: docs
weight: 4310
url: /cs/aspose.slides.export/pdfoptions/
---
## PdfOptions třída

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu Pdf.

```csharp
public class PdfOptions : SaveOptions, IPdfOptions
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [PdfOptions](pdfoptions)() | Výchozí konstruktor. |

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/pdfoptions/accesspermissions) { get; set; } | Obsahuje sadu příznaků určujících, která přístupová oprávnění mají být při otevření dokumentu s uživatelským přístupem udělena. Viz [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Vrací nebo nastavuje pole uživatelem definovaných názvů rodin písem, které by Aspose.Slides měl považovat za běžné. Čtení/zápis String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Aplikuje zadanou průhlednou barvu na obrázek, pokud je `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Určuje, zda má být pro každý obrázek automaticky vybrána nejúčinnější komprese (namísto výchozí). Pokud je nastavena na Boolean.true, pro každý obrázek v prezentaci bude vybrán nejvhodnější kompresní algoritmus, což povede k menší velikosti výsledného PDF dokumentu. Výběr nejlepšího poměru komprese obrázku je výpočetně náročný a vyžaduje další paměť RAM, a tato možnost je ve výchozím nastavení Boolean.false. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Požadovaná úroveň souladu pro generovaný PDF dokument. Čtení/zápis [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Vrací nebo nastavuje písmo použité v případě, že není nalezeno zdrojové písmo. Čtení/zápis String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True pro vykreslení černého rámečku kolem každého snímku. Čtení/zápis Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Určuje, zda mají být vloženy všechny znaky písma nebo jen použita podmnožina. Čtení/zápis Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Určuje, zda Aspose.Slides vloží běžná písma pro ASCII (rozsah kódů 33..127) text. Písma pro znakové kódy vyšší než 127 jsou vždy vložena. Seznam běžných písem zahrnuje základních 14 písem PDF a další uživatelem určená písma. Čtení/zápis Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Vrací nebo nastavuje vizuální styl gradientu. Čtení/zápis [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Vrací nebo nastavuje průhlednou barvu obrázku. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | True pro převod všech OLE dat z prezentace do vložených souborů ve výsledném PDF. Čtení/zápis Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Poskytuje možnosti, které řídí vzhled Ink objektů v exportovaném dokumentu. Pouze pro čtení [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. Čtení/zápis Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Nastavení uživatelského hesla pro ochranu PDF dokumentu. Čtení/zápis String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Representuje objekt zpětného volání pro ukládání aktualizací průběhu v procentech. Viz [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Určuje, zda má být text rasterizován jako bitmapa a uložen do PDF, když písmo nepodporuje tučné formátování. Tento přístup může zlepšit kvalitu textu ve výsledném PDF pro určitá písma. Čtení/zápis Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True pro převod všech meta souborů použitých v prezentaci na PNG obrázky. Čtení/zápis Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Určuje, zda má generovaný dokument zahrnovat skryté snímky, nebo ne. Výchozí hodnota je `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláními JavaScriptu. Čtení/zápis Boolean. Výchozí hodnota je **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Vrací nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Vrací nebo nastavuje hodnotu určující rozlišení obrázků v PDF dokumentu. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Určuje typ komprese, který se má použít pro veškerý textový obsah v dokumentu. Čtení/zápis [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude proces načítání pokračovat nebo bude přerušen. Čtení/zápis [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Příklady

Následující příklad ukazuje, jak převést PowerPoint do PDF s vlastním nastavením.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Vytvoří instanci třídy PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Nastaví kvalitu Jpeg
	pdfOptions.JpegQuality = 90;
	// Nastaví chování pro metafily
	pdfOptions.SaveMetafilesAsPng = true;
	// Nastaví úroveň komprese textu
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Definuje standard PDF
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Uloží prezentaci jako PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Následující příklad ukazuje, jak převést PowerPoint do PDF se skrytými snímky.

```csharp
[C#]
// Vytvoří instanci třídy Presentation, která představuje soubor PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Vytvoří instanci třídy PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Přidá skryté snímky
	pdfOptions.ShowHiddenSlides = true;
	// Uloží prezentaci jako PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Následující příklad ukazuje, jak převést PowerPoint do PDF chráněného heslem.

```csharp
[C#]
// Vytvoří objekt Presentation, který představuje soubor PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Vytvoří instanci třídy PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Nastaví heslo PDF a přístupová oprávnění
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Uloží prezentaci jako PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

Následující příklad ukazuje, jak převést PowerPoint do PDF s poznámkami.

```csharp
[C#]
// Vytvoří objekt Presentation, který představuje soubor prezentace
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// Nastavování typu a velikosti snímku
		//auxPresentation.SlideSize.SetSize(presentation.SlideSize.Size.Width, presentation.SlideSize.Size.Height,SlideSizeScaleType.EnsureFit);
		auxPresentation.SlideSize.SetSize(612F, 792F, SlideSizeScaleType.EnsureFit);
		PdfOptions pdfOptions = new PdfOptions();
		pdfOptions.SlidesLayoutOptions = new NotesCommentsLayoutingOptions() { NotesPosition = NotesPositions.BottomFull };
		auxPresentation.Save("PDFnotes_out.pdf", SaveFormat.Pdf, pdfOptions);
	}
}
```

### Viz také

* třída [SaveOptions](../saveoptions)
* rozhraní [IPdfOptions](../ipdfoptions)
* jmenný prostor [Aspose.Slides.Export](../../aspose.slides.export)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->