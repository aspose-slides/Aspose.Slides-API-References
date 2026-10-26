---
title: LoadOptions
second_title: Aspose.Sildes .NET API referenciája
description: Lehetővé teszi további beállítások megadását, például formátum vagy alapértelmezett betűtípus használatát a bemutató betöltésekor.
type: docs
weight: 7840
url: /hu/aspose.slides/loadoptions/
---
## LoadOptions osztály

Lehetővé teszi további beállítások (például formátum vagy alapértelmezett betűtípus) megadását a bemutató betöltésekor.

```csharp
public class LoadOptions : ILoadOptions
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Létrehozza az új alapértelmezett betöltési beállításokat. |
| [LoadOptions](loadoptions#constructor_1)(LoadFormat) | Létrehozza az új betöltési beállításokat. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | A lehetőségek, amelyek a Binary Large Objects (BLOBs) kezelésének viselkedését vezérelhetik, például ideiglenes fájlok használata vagy a memóriaban lévő maximális BLOB bájtok száma. Ezek a beállítások a legjobb teljesítmény/ memóriafelhasználás arány elérését célozzák egy adott környezet vagy követelmények számára. A Binary Large Object (BLOB) egy bináris adat, amely egyetlen entitásként tárolódik – pl. a BLOB lehet hang, videó vagy maga a bemutató. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Visszaadja vagy beállítja az ázsiai betűtípust, amely akkor kerül felhasználásra, ha a forrás betűtípusa nem található. Olvasás/írás String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Visszaadja vagy beállítja a szabályos betűtípust, amely akkor kerül felhasználásra, ha a forrás betűtípusa nem található. Olvasás/írás String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Visszaadja vagy beállítja a szimbólum betűtípust, amely akkor kerül felhasználásra, ha a forrás betűtípusa nem található. Olvasás/írás String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Visszaadja vagy beállítja a bemutató szövegének alapértelmezett nyelvét. Olvasás/írás String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Meghatározza, hogy az Aspose.Slides törli-e az összes beágyazott bináris objektumot a bemutató betöltésekor. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Megadja a külső betűtípusok forrásait, amelyeket a bemutató használ. Ezek a betűtípusok a bemutató teljes élettartama alatt elérhetők, és nem osztódnak meg más bemutatókkal. |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | Az a token, amely a megszakítási kéréseket figyeli. Ez a token kezeli a teljes [`IPresentation`](../ipresentation) példány életciklusát. Bármely hosszú ideig futó művelet, például a bemutató betöltése vagy mentése, a [`Interrupt`](../interruptiontokensource/interrupt) metódus meghívásával a [`InterruptionTokenSource`](../interruptiontokensource)-ben lesz megszakítva. |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Visszaadja vagy beállítja a betöltendő bemutató formátumát. Olvasás/írás [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Ez a tulajdonság akkor értelmezhető, ha a bemutató fájl jelszóval védett. Az igaz érték azt jelenti, hogy csak a dokumentum tulajdonságait kell betölteni a titkosított bemutatófájlból, és a jelszót figyelmen kívül kell hagyni. A hamis érték azt jelenti, hogy az egész titkosított bemutatót a megfelelő jelszó használatával kell betölteni. Ha a bemutató nincs titkosítva, akkor a tulajdonság értéke mindig figyelmen kívül marad. Ha egy titkosított fájl dokumentumtulajdonságai nem nyilvánosak és a tulajdonság értéke igaz, akkor a dokumentumtulajdonságok nem tölthetők be, és kivétel lesz dobva. Olvasás/írás Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Lekéri vagy beállítja a jelszót. Olvasás/írás String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Visszaadja vagy beállítja a visszahívási interfészt, amely a külső erőforrások betöltését kezeli. Olvasás/írás [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Lekéri a táblázatok beállításait. Például ezek a beállítások befolyásolják a diagramok képleteinek számítását. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Visszaadja vagy beállítja azt az objektumot, amely figyelmeztetéseket kap, és dönt arról, hogy a betöltési folyamat folytatódik-e vagy megszakad. Olvasás/írás [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Lásd még

* interface [ILoadOptions](../iloadoptions)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->