---
title: LoadOptions
second_title: Aspose.Sildes a .NET API hivatkozás
description: Lehetővé teszi további beállítások, például a formátum vagy az alapértelmezett betűtípus megadását egy bemutató betöltésekor.
type: docs
weight: 7820
url: /hu/aspose.slides/loadoptions/
---
## LoadOptions osztály

Lehetővé teszi további beállítások (például formátum vagy alapértelmezett betűtípus) megadását egy bemutató betöltésekor.

```csharp
public class LoadOptions : ILoadOptions
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Új alapértelmezett betöltési beállításokat hoz létre. |
| [LoadOptions](loadoptions#constructor_1)(LoadFormat) | Új betöltési beállításokat hoz létre. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | A lehetőségek, amelyeket a Binary Large Objects (BLOB) kezelési viselkedésének kezelésére lehet használni, például ideiglenes fájlok használata vagy a memóriaban tárolt BLOB-ok maximális bájtja. Ezek a beállítások a legjobb teljesítmény/memóriafogyasztás arány elérését célozzák egy adott környezet vagy követelmény esetén. A Binary Large Object (BLOB) egy bináris adat, amely egyetlen entitásként van tárolva – például BLOB lehet hang, videó vagy maga a bemutató. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Az alapértelmezett ázsiai betűtípust adja vissza vagy állítja be, ha a forrás betűtípusa nem található. Olvasás/írás String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Az alapértelmezett normál betűtípust adja vissza vagy állítja be, ha a forrás betűtípusa nem található. Olvasás/írás String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Az alapértelmezett szimbólum betűtípust adja vissza vagy állítja be, ha a forrás betűtípusa nem található. Olvasás/írás String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | A bemutató szövegének alapértelmezett nyelvét adja vissza vagy állítja be. Olvasás/írás String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Megállapítja, hogy az Aspose.Slides törli-e az összes beágyazott bináris objektumot a bemutató betöltésekor. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Megadja a külső betűtípusok forrásait, amelyeket a bemutató használ. Ezek a betűtípusok a bemutató teljes életciklusa alatt elérhetők, és nem osztoznak más bemutatókon. |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | A token a megszakítási kérések figyeléséhez. Ez a token kezeli a teljes [`IPresentation`](../ipresentation) példány életciklusát. Bármely hosszú művelet, például a bemutató betöltése vagy mentése, a [`InterruptionTokenSource`](../interruptiontokensource) [`Interrupt`](../interruptiontokensource/interrupt) metódusának meghívásával lesz megszakítva. |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | A betöltendő bemutató formátumát adja vissza vagy állítja be. Olvasás/írás [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Ez a tulajdonság akkor értelmezhető, ha a bemutató fájl jelszóval védett. A true érték azt jelenti, hogy csak a dokumentum tulajdonságait kell betölteni egy titkosított bemutató fájlból, és a jelszót figyelmen kívül kell hagyni. A false érték azt jelenti, hogy az egész titkosított bemutatót a megfelelő jelszó használatával kell betölteni. Ha a bemutató nincs titkosítva, akkor a tulajdonság értéke mindig figyelmen kívül marad. Ha egy titkosított fájl dokumentum tulajdonságai nem nyilvánosak és a tulajdonság értéke true, akkor a dokumentum tulajdonságai nem tölthetők be, és kivétel keletkezik. Olvasás/írás Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | A jelszót adja vissza vagy állítja be. Olvasás/írás String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | A külső erőforrások betöltését kezelő callback interfészt adja vissza vagy állítja be. Olvasás/írás [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | A táblázatok beállításait adja vissza. Például ezek a beállítások befolyásolják a diagramok képleteinek számítását. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Figyelmeztetéseket fogadó és eldöntő objektumot ad vissza vagy állít be, amely meghatározza, hogy a betöltési folyamat folytatódik-e vagy megszakad. Olvasás/írás [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Lásd még

* interfész [ILoadOptions](../iloadoptions)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->