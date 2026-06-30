---
title: IPdfOptions
second_title: Aspose.Sildes .NET API hivatkozás
description: Lehetővé teszi a beállítások megadását, amelyek szabályozzák, hogyan mentődik egy prezentáció PDF formátumban.
type: docs
weight: 3980
url: /hu/aspose.slides.export/ipdfoptions/
---
## IPdfOptions interfész

Lehetővé teszi a beállítások megadását, amelyek szabályozzák, hogyan mentődik a prezentáció PDF formátumban.

```csharp
public interface IPdfOptions : ISaveOptions
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AccessPermissions](../../aspose.slides.export/ipdfoptions/accesspermissions) { get; set; } | Tartalmaz egy jelzőkészletet, amely meghatározza, milyen hozzáférési engedélyeket kell megadni, amikor a dokumentumot felhasználói hozzáféréssel nyitják meg. Lásd [`PdfAccessPermissions`](../pdfaccesspermissions). |
| [AdditionalCommonFontFamilies](../../aspose.slides.export/ipdfoptions/additionalcommonfontfamilies) { get; set; } | Visszaadja vagy beállítja a felhasználó által meghatározott betűcsaládnevek tömbjét, amelyeket az Aspose.Slides közösnek tekint. Olvasás/írás String[]. |
| [ApplyImageTransparent](../../aspose.slides.export/ipdfoptions/applyimagetransparent) { get; set; } | Alkalmazza a megadott átlátszó színt a képre, ha `true`. |
| [AsISaveOptions](../../aspose.slides.export/ipdfoptions/asisaveoptions) { get; } | Visszaadja az ISaveOptions interfészt. Csak olvasható [`ISaveOptions`](../isaveoptions). |
| [BestImagesCompressionRatio](../../aspose.slides.export/ipdfoptions/bestimagescompressionratio) { get; set; } | Jelzi, hogy a leghatékonyabb tömörítést (az alapértelmezett helyett) minden képhez automatikusan ki kell-e választani. Ha Boolean.true értékre van állítva, a prezentáció minden képe számára a legmegfelelőbb tömörítési algoritmus lesz kiválasztva, ami a végső PDF dokumentum kisebb méretéhez vezet. A legjobb kép tömörítési arány kiválasztása számításigényes és további RAM-ot igényel, és ez a beállítás alapértelmezés szerint Boolean.false. |
| [Compliance](../../aspose.slides.export/ipdfoptions/compliance) { get; set; } | A generált PDF dokumentum kívánt megfelelőségi szintje. Olvasás/írás [`PdfCompliance`](../pdfcompliance). |
| [DrawSlidesFrame](../../aspose.slides.export/ipdfoptions/drawslidesframe) { get; set; } | Igaz, ha fekete keretet kell rajzolni minden diához. Olvasás/írás Boolean. |
| [EmbedFullFonts](../../aspose.slides.export/ipdfoptions/embedfullfonts) { get; set; } | Meghatározza, hogy a betűtípus minden karaktere be legyen-e ágyazva, vagy csak a használt részhalmaz. Olvasás/írás Boolean. |
| [EmbedTrueTypeFontsForASCII](../../aspose.slides.export/ipdfoptions/embedtruetypefontsforascii) { get; set; } | Igaz, ha a TrueType betűtípusokat be kell ágyazni az ASCII karakterek 32-127-hez. A 127-nél nagyobb karakterkódokhoz tartozó betűtípusok mindig be vannak ágyazva. Olvasás/írás Boolean. |
| [ImageTransparentColor](../../aspose.slides.export/ipdfoptions/imagetransparentcolor) { get; set; } | Lekéri vagy beállítja a kép átlátszó színét. |
| [IncludeOleData](../../aspose.slides.export/ipdfoptions/includeoledata) { get; set; } | Igaz, ha az összes OLE adatot a prezentációból beágyazott fájlokká kell konvertálni a végeredmény PDF-ben. Olvasás/írás Boolean. |
| [InkOptions](../../aspose.slides.export/ipdfoptions/inkoptions) { get; } | Lehetővé teszi a beállításokat, amelyek szabályozzák a tintaobjektumok megjelenését az exportált dokumentumban. Csak olvasható [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/ipdfoptions/jpegquality) { get; set; } | Visszaadja vagy beállítja a PDF dokumentumban lévő JPEG képek minőségét meghatározó értéket. Olvasás/írás Byte. |
| [Password](../../aspose.slides.export/ipdfoptions/password) { get; set; } | Felhasználói jelszó beállítása a PDF dokumentum védelméhez. Olvasás/írás String. |
| [RasterizeUnsupportedFontStyles](../../aspose.slides.export/ipdfoptions/rasterizeunsupportedfontstyles) { get; set; } | Jelzi, hogy a szöveget bitmapként kell-e rasterizálni és PDF-be menteni, ha a betűtípus nem támogatja a félkövér stílusú formázást. Ez a megközelítés bizonyos betűtípusok esetén javíthatja a szöveg minőségét a végső PDF-ben. Olvasás/írás Boolean. |
| [SaveMetafilesAsPng](../../aspose.slides.export/ipdfoptions/savemetafilesaspng) { get; set; } | Igaz, ha a prezentációban használt összes metafájl PNG képekké konvertálódik. Olvasás/írás Boolean. |
| [ShowHiddenSlides](../../aspose.slides.export/ipdfoptions/showhiddenslides) { get; set; } | Meghatározza, hogy a generált dokumentum tartalmazzon-e rejtett diákat vagy sem. Alapértelmezett érték `false`. |
| [SlidesLayoutOptions](../../aspose.slides.export/ipdfoptions/slideslayoutoptions) { get; set; } | Lekéri vagy beállítja azt a módot, ahogyan a diákat az oldalon elhelyezik a prezentáció exportálásakor [`ISlidesLayoutOptions`](../islideslayoutoptions). |
| [SufficientResolution](../../aspose.slides.export/ipdfoptions/sufficientresolution) { get; set; } | Visszaadja vagy beállítja a PDF dokumentumban lévő képek felbontását meghatározó értéket. |
| [TextCompression](../../aspose.slides.export/ipdfoptions/textcompression) { get; set; } | Megadja a dokumentum összes szöveges tartalmára használandó tömörítési típust. Olvasás/írás [`PdfTextCompression`](../pdftextcompression). |

### Lásd még

* interfész [ISaveOptions](../isaveoptions)
* névtér [Aspose.Slides.Export](../../aspose.slides.export)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->