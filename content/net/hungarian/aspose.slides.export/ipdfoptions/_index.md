---
title: IPdfOptions
second_title: Aspose.Sildes .NET API referencia
description: Lehetővé teszi a beállításokat, amelyek szabályozzák, hogyan mentődik egy prezentáció Pdf formátumban.
type: docs
weight: 4020
url: /hu/aspose.slides.export/ipdfoptions/
---
## IPdfOptions interfész

Lehetővé teszi azokat a beállításokat, amelyek meghatározzák, hogyan mentődik egy prezentáció PDF formátumban.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Tartalmaz egy zászlók halmazát, amely meghatározza, mely hozzáférési engedélyek legyenek megadva, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. Lásd [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Visszaadja vagy beállítja a felhasználó által meghatározott betűcsaládnevek tömbjét, amelyeket az Aspose.Slides közösnek tekint. Olvasás/írás String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Alkalmazza a megadott átlátszó színt egy képre, ha `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Visszaadja az ISaveOptions interfészt. Csak olvasható [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Jelzi, hogy a leghatékonyabb tömörítést (az alapértelmezett helyett) minden képhez automatikusan ki kell-e választani. Ha Boolean.true értékre van állítva, a prezentáció minden képe esetén a legmegfelelőbb tömörítési algoritmus lesz kiválasztva, ami a végleges PDF dokumentum kisebb méretéhez vezet. A legjobb képtömörítési arány meghatározása számításigényes, és extra RAM-ot igényel, ez a beállítás alapértelmezés szerint Boolean.false. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | A generált PDF dokumentum kívánt megfelelőségi szintje. Olvasás/írás [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | True to draw black frame around each slide. Olvasás/írás Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Meghatározza, hogy a betűtípus összes karaktere be legyen-e ágyazva, vagy csak a használt részhalmaz. Olvasás/írás Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | True to embed true type fonts for ASCII characters 32-127. Fonts for character codes greater than 127 are always embedded. Olvasás/írás Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Visszaadja vagy beállítja a kép átlátszó színét. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | True to convert all OLE data from the presentation to embedded files in the resulting PDF. Olvasás/írás Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Lehetővé teszi a beállításokat, amelyek szabályozzák az Ink objektumok megjelenését az exportált dokumentumban. Csak olvasható [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Visszaadja vagy beállítja a JPEG képek minőségét a PDF dokumentumban. Olvasás/írás Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Felhasználói jelszó beállítása a PDF dokumentum védelméhez. Olvasás/írás String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Jelzi, hogy a szöveget bitmapként rasterizálja-e és PDF-be menti, ha a betűtípus nem támogatja a félkövér formázást. Ez a megközelítés bizonyos betűtípusok esetén javíthatja a szöveg minőségét a végleges PDF-ben. Olvasás/írás Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | True to convert all metafiles used in a presentation to the PNG images. Olvasás/írás Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Meghatározza, hogy a generált dokumentum tartalmazzon-e rejtett diákot vagy sem. Alapértelmezett érték `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Visszaadja vagy beállítja azt a módot, ahogyan a diák az oldalra kerülnek a prezentáció exportálásakor [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Visszaadja vagy beállítja a PDF dokumentumban lévő képek felbontását meghatározó értéket. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Meghatározza a dokumentum összes szöveges tartalmához használandó tömörítési típust. Olvasás/írás [`PdfTextCompression`](../pdftextcompression). |

### Lásd még

* interfész [ISaveOptions](../isaveoptions)
* névtér [Aspose.Slides.Export](../../aspose.slides.export)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->