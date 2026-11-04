---
title: PdfOptions
second_title: Aspose.Sildes pro .NET API Reference
description: Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu PDF.
type: docs
weight: 4350
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
| [AdditionalCommonFontFamilies](../../aspose.slides.export/pdfoptions/additionalcommonfontfamilies) { get; set; } | Vrací nebo nastavuje pole uživatelem definovaných názvů rodin písem, které má Aspose.Slides považovat za běžné. Read/write String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/pdfoptions/applyimagetransparent) { get; set; } | Použije určenou průhlednou barvu na obrázek, pokud je `true`. |
| [BestImagesCompressionRatio](../../aspose.slides.export/pdfoptions/bestimagescompressionratio) { get; set; } | Určuje, zda má být pro každý obrázek automaticky vybrána nejúčinnější komprese (namísto výchozí). Pokud je nastaveno na Boolean.true, pro každý obrázek v prezentaci bude vybrán nejvhodnější kompresní algoritmus, což povede k menší velikosti výsledného PDF dokumentu. Výběr nejlepšího poměru komprese obrázku je výpočetně náročný a vyžaduje další paměť RAM, a tato možnost je ve výchozím nastavení Boolean.false. |
| [Compliance](../../aspose.slides.export/pdfoptions/compliance) { get; set; } | Požadovaná úroveň souladu pro generovaný PDF dokument. Read/write [`PdfCompliance`](../pdfcompliance). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Vrací nebo nastavuje písmo použité v případě, že není nalezeno zdrojové písmo. Read-write String. |
| [DrawSlidesFrame](../../aspose.slides.export/pdfoptions/drawslidesframe) { get; set; } | True pro vykreslení černého rámu kolem každého snímku. Read/write Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/pdfoptions/embedfullfonts) { get; set; } | Určuje, zda mají být vloženy všechny znaky písma nebo pouze použita podmnožina. Read/write Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/pdfoptions/embedtruetypefontsforascii) { get; set; } | Určuje, zda Aspose.Slides vloží běžná písma pro text ASCII (rozsah kódů 33..127). Písma pro kódy znaků vyšší než 127 jsou vždy vložena. Seznam běžných písem zahrnuje základních 14 písem PDF a další uživatelem určená písma. Read/write Boolean. |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Vrací nebo nastavuje vizuální styl gradientu. Read/write [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [ImageTransparentColor](../../aspose.slides.export/pdfoptions/imagetransparentcolor) { get; set; } | Vrací nebo nastavuje průhlednou barvu obrázku. |
| [IncludeOleData](../../aspose.slides.export/pdfoptions/includeoledata) { get; set; } | True pro převod všech OLE dat z prezentace do vložených souborů v výsledném PDF. Read/write Boolean. |
| [InkOptions](../../aspose.slides.export/pdfoptions/inkoptions) { get; } | Poskytuje možnosti, které řídí vzhled Ink objektů v exportovaném dokumentu. Read-only [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/pdfoptions/jpegquality) { get; set; } | Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. Read/write Byte. |
| [Password](../../aspose.slides.export/pdfoptions/password) { get; set; } | Nastavení uživatelského hesla pro ochranu PDF dokumentu. Read/write String. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Reprezentuje objekt zpětného volání pro ukládání průběžných aktualizací v procentech. Viz [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/pdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Určuje, zda má být text rasterizován jako bitmapa a uložen do PDF, když písmo nepodporuje tučné stylování. Tento přístup může zlepšit kvalitu textu ve výsledném PDF pro některá písma. Read/write Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/pdfoptions/savemetafilesaspng) { get; set; } | True, pokud chcete převést všechny metafily použité v prezentaci na PNG obrázky. Čtení/zápis Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/pdfoptions/showhiddenslides) { get; set; } | Určuje, zda vygenerovaný dokument má obsahovat skryté snímky nebo ne. Výchozí hodnota je `false`. |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Určuje, zda při ukládání prezentace přeskočit hypertextové odkazy s voláním JavaScriptu. Čtení/zápis Boolean. Výchozí hodnota je **false**. |
| [SlidesLayoutOptions](../../aspose.slides.export/pdfoptions/slideslayoutoptions) { get; set; } | Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/pdfoptions/sufficientresolution) { get; set; } | Vrací nebo nastaví hodnotu určující rozlišení obrázků uvnitř PDF dokumentu. |
| [TextCompression](../../aspose.slides.export/pdfoptions/textcompression) { get; set; } | Určuje typ komprese, který se použije pro celý textový obsah v dokumentu. Čtení/zápis [`PdfTextCompression`](../pdftextcompression). |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Vrací nebo nastavuje objekt, který přijímá varování a rozhoduje, zda bude načítací proces pokračovat nebo bude přerušen. Čtení/zápis [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Příklady

The following example shows how to convert PowerPoint to PDF with custom options.

```csharp
[C#]
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instancuje třídu PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Nastavuje kvalitu JPEG
	pdfOptions.JpegQuality = 90;
	// Nastavuje chování metafilek
	pdfOptions.SaveMetafilesAsPng = true;
	// Nastavuje úroveň komprese textu
	pdfOptions.TextCompression = PdfTextCompression.Flate;
	// Definuje standard PDF
	pdfOptions.Compliance = PdfCompliance.Pdf15;
	// Ukládá prezentaci jako PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

The following example shows how to convert PowerPoint to PDF with hidden slides.

```csharp
[C#]
// Instancuje třídu Presentation, která představuje soubor PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	// Instancuje třídu PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Přidá skryté snímky
	pdfOptions.ShowHiddenSlides = true;
	// Uloží prezentaci jako PDF
	presentation.Save("PowerPoint-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

The following example shows how to convert PowerPoint to password protected PDF.

```csharp
[C#]
// Instancuje objekt Presentation, který představuje soubor PowerPoint
using (Presentation presentation = new Presentation("PowerPoint.pptx"))
{
	/// Instancuje třídu PdfOptions
	PdfOptions pdfOptions = new PdfOptions();
	// Nastavuje heslo PDF a oprávnění k přístupu
	pdfOptions.Password = "password";
	pdfOptions.AccessPermissions = PdfAccessPermissions.PrintDocument | PdfAccessPermissions.HighQualityPrint;
	// Ukládá prezentaci jako PDF
	presentation.Save("PPTX-to-PDF.pdf", SaveFormat.Pdf, pdfOptions);
}
```

The following example shows how to convert PowerPoint to PDF with notes.

```csharp
[C#]
// Instancuje objekt Presentation, který představuje soubor prezentace
using (Presentation presentation = new Presentation("SelectedSlides.pptx"))
{
	using (Presentation auxPresentation = new Presentation())
	{
		ISlide slide = presentation.Slides[0];
		auxPresentation.Slides.InsertClone(0, slide);
		// Nastavení typu a velikosti snímku
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