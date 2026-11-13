---
title: LoadOptions
second_title: Aspose.Sildes a .NET API hivatkozás
description: Lehetővé teszi további opciók, például formátum vagy alapértelmezett betűtípus megadását egy prezentáció betöltésekor.
type: docs
weight: 7860
url: /hu/aspose.slides/loadoptions/
---
## LoadOptions osztály

Lehetővé teszi további opciók (például formátum vagy alapértelmezett betűtípus) megadását egy prezentáció betöltésekor.

```csharp
public class LoadOptions : ILoadOptions
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Új alapértelmezett betöltési opciókat hoz létre. |
| [LoadOptions](loadoptions#constructor_1)(LoadFormat) | Új betöltési opciókat hoz létre. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | A lehetőségek képviseli, amelyeket a Bináris Nagy Objektumok (BLOBs) kezelési viselkedésének kezelésére lehet használni, például ideiglenes fájlok használata vagy a memória maximális BLOB-ok bájtja. Ezek a beállítások a legjobb teljesítmény/memóriafogyasztás arányt próbálják megvalósítani egy adott környezet vagy követelmény esetén. A Bináris Nagy Objektum (BLOB) egy bináris adat, amely egyetlen entitásként van tárolva – például a BLOB egy hang, videó vagy maga a prezentáció is lehet. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Visszaadja vagy beállítja az ázsiai betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található. Olvasás/írás String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Visszaadja vagy beállítja a normál betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található. Olvasás/írás String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Visszaadja vagy beállítja a szimbólum betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található. Olvasás/írás String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Visszaadja vagy beállítja a prezentáció szövegének alapértelmezett nyelvét. Olvasás/írás String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Meghatározza, hogy az Aspose.Slides törli-e az összes beágyazott bináris objektumot a prezentáció betöltésekor. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Megadja a külső betűtípusok forrásait, amelyeket a prezentáció használ. Ezek a betűtípusok a prezentáció teljes élettartama alatt elérhetők, és nem osztódnak meg más prezentációkkal. |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | Az megszakítási kérések figyelésére szolgáló token. Ez a token kezeli a teljes [`IPresentation`](../ipresentation) példány életciklusát. Bármely hosszú futású művelet, például a prezentáció betöltése vagy mentése, a [`Interrupt`](../interruptiontokensource/interrupt) metódus hívásával lesz megszakítva a [`InterruptionTokenSource`](../interruptiontokensource) esetén. |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Visszaadja vagy beállítja a betöltendő prezentáció formátumát. Olvasás/írás [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Ez a tulajdonság akkor értelmezhető, ha a prezentáció fájl jelszóval védett. A true érték azt jelenti, hogy csak a dokumentum tulajdonságait kell betölteni a titkosított prezentációból, és a jelszót figyelmen kívül kell hagyni. A false érték azt jelenti, hogy a teljes titkosított prezentációt a megfelelő jelszóval kell betölteni. Ha a prezentáció nincs titkosítva, akkor a tulajdonság értéke mindig figyelmen kívül marad. Ha egy titkosított fájl dokumentum tulajdonságai nem nyilvánosak, és a tulajdonság értéke true, akkor a dokumentum tulajdonságok nem tölthetők be, és kivétel keletkezik. Olvasás/írás Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Visszaadja vagy beállítja a jelszót. Olvasás/írás String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Visszaadja vagy beállítja a visszahívási interfészt, amely a külső erőforrások betöltését kezeli. Olvasás/írás [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Megadja a táblázatkezelők opcióit. Például ezek az opciók befolyásolják a diagramok képleteinek számítását. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és eldönti, hogy a betöltési folyamat folytatódik-e vagy megszakad. Olvasás/írás [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Lásd még

* interfész [ILoadOptions](../iloadoptions)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->