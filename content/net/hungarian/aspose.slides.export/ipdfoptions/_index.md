---
title: IPdfOptions
second_title: Aspose.Sildes a .NET API hivatkozás
description: Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik a prezentáció PDF formátumban.
type: docs
weight: 4000
url: /hu/aspose.slides.export/ipdfoptions/
---
## IPdfOptions interfész

Lehetőségeket biztosít, amelyek szabályozzák, hogyan mentődik a prezentáció PDF formátumban.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Tartalmaz egy flagkészletet, amely meghatározza, hogy milyen hozzáférési engedélyeket kell megadni, amikor a dokumentum felhasználói hozzáféréssel nyílik meg. Lásd [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Visszaadja vagy beállítja a felhasználó által megadott betűcsaládnevek tömbjét, amelyeket az Aspose.Slides közösnek tekint. Olvasás/írás String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Alkalmazza a megadott átlátszó színt a képre, ha `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Visszaadja az ISaveOptions interfészt. Csak olvasható [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Jelzi, hogy az egyes képekhez a leghatékonyabb tömörítést (az alapértelmezett helyett) automatikusan kell-e kiválasztani. Ha Boolean.true értékre van állítva, a prezentáció minden képe számára a legmegfelelőbb tömörítési algoritmus lesz kiválasztva, ami a létrehozott PDF dokumentum kisebb méretéhez vezet. A legjobb képtömörítési arány kiválasztása számításigényes, további RAM-ot igényel, és ez az opció alapértelmezés szerint Boolean.false. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | A generált PDF dokumentum kívánt megfelelőségi szintje. Olvasás/írás [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | True érték esetén fekete keret kerül rajzolásra minden diára. Olvasás/írás Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Meghatározza, hogy a betűtípus összes karaktere legyen beágyazva vagy csak a használt részhalmaz. Olvasás/írás Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | True érték esetén a TrueType betűtípusok be lesznek ágyazva az ASCII 32-127 karakterekhez. A 127-nél nagyobb karakterkódok betűtípusai mindig be vannak ágyazva. Olvasás/írás Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Visszaadja vagy beállítja a kép átlátszó színét. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | True érték esetén az összes OLE adat a prezentációból beágyazott fájlokká lesz konvertálva a létrehozott PDF-ben. Olvasás/írás Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Beállításokat biztosít, amelyek szabályozzák a tintával készült objektumok megjelenését az exportált dokumentumban. Csak olvasható [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Visszaadja vagy beállítja a PDF dokumentumban lévő JPEG képek minőségét meghatározó értéket. Olvasás/írás Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | A PDF dokumentum védelméhez felhasználói jelszó beállítása. Olvasás/írás String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Jelzi, hogy a szöveget bitmapként kell-e rasterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér formázást. Ez a megközelítés bizonyos betűtípusok esetén javíthatja a szöveg minőségét a létrehozott PDF-ben. Olvasás/írás Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | True érték esetén a prezentációban használt összes metafájl PNG képpé lesz konvertálva. Olvasás/írás Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Meghatározza, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. Alapértelmezett érték `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Visszaadja vagy beállítja a módot, ahogy a diák az oldalon elhelyezésre kerülnek a prezentáció exportálásakor [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Visszaadja vagy beállítja a PDF dokumentumban lévő képek felbontását meghatározó értéket. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Megadja, hogy a dokumentum összes szöveges tartalmára milyen tömörítési típust kell használni. Olvasás/írás [`PdfTextCompression`](../pdftextcompression). |

### Lásd még

* interfész [ISaveOptions](../isaveoptions)
* névtér [Aspose.Slides.Export](../../aspose.slides.export)
* összeszerelés [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->