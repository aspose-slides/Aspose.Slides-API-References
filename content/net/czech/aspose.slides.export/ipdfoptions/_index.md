---
title: IPdfOptions
second_title: Aspose.Sildes pro .NET API referenci
description: Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu PDF.
type: docs
weight: 4000
url: /cs/aspose.slides.export/ipdfoptions/
---
## IPdfOptions rozhraní

Provides options that control how a presentation is saved in Pdf format.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Obsahuje sadu příznaků určujících, která oprávnění k přístupu by měla být udělena při otevření dokumentu s uživatelským přístupem. Viz [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Vrací nebo nastavuje pole uživatelem definovaných názvů rodin písem, které by Aspose.Slides měl považovat za běžné. Čtení/zápis String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Aplikuje zadanou průhlednou barvu na obrázek, pokud je `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Vrací rozhraní ISaveOptions. Pouze pro čtení [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Určuje, zda má být pro každý obrázek automaticky vybráno nejúčinnější komprimování (místo výchozího). Pokud je nastaveno na Boolean.true, pro každý obrázek v prezentaci bude zvolen nejvhodnější kompresní algoritmus, což povede k menší velikosti výsledného PDF dokumentu. Výběr nejlepšího poměru komprese obrázků je výpočetně náročný a vyžaduje další množství RAM, a tato možnost je ve výchozím stavu Boolean.false. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Požadovaná úroveň souladu pro generovaný PDF dokument. Čtení/zápis [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | True pro vykreslení černého rámce kolem každého snímku. Čtení/zápis Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Určuje, zda mají být vloženy všechny znaky písma nebo jen použita podmnožina. Čtení/zápis Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | True pro vložení TrueType fontů pro ASCII znaky 32-127. Fonty pro kódy znaků vyšší než 127 jsou vždy vloženy. Čtení/zápis Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Vrací nebo nastavuje průhlednou barvu obrázku. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | True pro konverzi všech OLE dat z prezentace na vložené soubory v výsledném PDF. Čtení/zápis Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Poskytuje možnosti, které řídí vzhled objektů Ink v exportovaném dokumentu. Pouze pro čtení [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků uvnitř PDF dokumentu. Čtení/zápis Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Nastavení uživatelského hesla pro ochranu PDF dokumentu. Čtení/zápis String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Určuje, zda má být text rastrován jako bitmapa a uložen do PDF, když písmo nepodporuje tučné stylování. Tento přístup může zlepšit kvalitu textu v výsledném PDF pro určitá písma. Čtení/zápis Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | True pro konverzi všech metafiles použitých v prezentaci na PNG obrázky. Čtení/zápis Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Určuje, zda má generovaný dokument obsahovat skryté snímky nebo ne. Výchozí hodnota je `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Vrací nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Vrací nebo nastavuje hodnotu určující rozlišení obrázků uvnitř PDF dokumentu. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Určuje typ komprese, který se má použít pro veškerý textový obsah v dokumentu. Čtení/zápis [`PdfTextCompression`](../pdftextcompression). |

### Viz také

* rozhraní [ISaveOptions](../isaveoptions)
* jmenný prostor [Aspose.Slides.Export](../../aspose.slides.export)
* assemblie [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->