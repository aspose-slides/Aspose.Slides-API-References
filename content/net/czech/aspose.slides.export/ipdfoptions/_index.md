---
title: IPdfOptions
second_title: Aspose.Sildes pro .NET API Reference
description: Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu Pdf.
type: docs
weight: 3980
url: /cs/aspose.slides.export/ipdfoptions/
---
## IPdfOptions rozhraní

Poskytuje možnosti, které řídí, jak je prezentace uložena ve formátu Pdf.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Obsahuje sadu příznaků určujících, která přístupová oprávnění by měla být udělena při otevření dokumentu s uživatelským přístupem. Viz [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Vrací nebo nastavuje pole uživatelem definovaných názvů rodin písem, které má Aspose.Slides považovat za běžné. Read/write String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Použije zadanou průhlednou barvu na obrázek, pokud je nastaveno na `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Vrací rozhraní ISaveOptions. Read-only [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Určuje, zda má být pro každý obrázek automaticky vybrána nejúčinnější komprese (namísto výchozí). Pokud je nastaveno na Boolean.true, pro každý obrázek v prezentaci bude zvolen nejvhodnější kompresní algoritmus, což povede k menší velikosti výsledného PDF dokumentu. Výběr nejlepšího poměru komprese obrázků je výpočetně náročný a vyžaduje další množství RAM, a tato volba je ve výchozím nastavení Boolean.false. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | Požadovaná úroveň souladu pro generovaný PDF dokument. Read/write [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | True pro nakreslení černého rámečku kolem každého snímku. Read/write Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Určuje, zda mají být vloženy všechny znaky písma nebo pouze použita podmnožina. Read/write Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | True pro vložení TrueType písem pro ASCII znaky 32-127. Písma pro kódy znaků větší než 127 jsou vždy vložena. Read/write Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Vrací nebo nastavuje průhlednou barvu obrázku. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | True pro převod všech OLE dat z prezentace do vložených souborů ve výsledném PDF. Read/write Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Poskytuje možnosti, které řídí vzhled ink objektů v exportovaném dokumentu. Read-only [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. Read/write Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Nastavuje uživatelské heslo pro ochranu PDF dokumentu. Read/write String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Určuje, zda má být text rasterizován jako bitmapa a uložen do PDF, když písmo nepodporuje tučné stylování. Tento přístup může zlepšit kvalitu textu ve výsledném PDF pro některá písma. Read/write Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | True pro převod všech metafajlů použitých v prezentaci na PNG obrázky. Read/write Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Určuje, zda má generovaný dokument zahrnovat skryté snímky, nebo ne. Výchozí hodnota je `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Vrací nebo nastavuje režim, ve kterém jsou snímky umístěny na stránku při exportu prezentace [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Vrací nebo nastavuje hodnotu určující rozlišení obrázků v PDF dokumentu. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Určuje typ komprese, který bude použit pro veškerý textový obsah v dokumentu. Read/write [`PdfTextCompression`](../pdftextcompression). |

### Viz také

* rozhraní [ISaveOptions](../isaveoptions)
* jmenný prostor [Aspose.Slides.Export](../../aspose.slides.export)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->