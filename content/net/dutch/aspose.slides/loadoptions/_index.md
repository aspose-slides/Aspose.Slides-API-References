---
title: LoadOptions
second_title: Aspose.Sildes voor .NET API-referentie
description: Staat toe extra opties op te geven, zoals formaat of standaardlettertype, bij het laden van een presentatie.
type: docs
weight: 7840
url: /nl/aspose.slides/loadoptions/
---
## LoadOptions klasse

Staat toe extra opties op te geven (zoals formaat of standaardlettertype) bij het laden van een presentatie.

```csharp
public class LoadOptions : ILoadOptions
```

## Constructoren

| Naam | Beschrijving |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Maakt nieuwe standaard laadopties aan. |
| [LoadOptions](loadoptions#constructor_1)(LoadFormat) | Maakt nieuwe laadopties aan. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Stelt de opties voor die gebruikt kunnen worden om het gedrag van het omgaan met Binary Large Objects (BLOB's) te beheren, zoals het gebruik van tijdelijke bestanden of het maximale aantal BLOB-bytes in het geheugen. Deze opties zijn bedoeld om de beste verhouding tussen prestaties en geheugengebruik in te stellen voor een bepaalde omgeving of vereisten. Een Binary Large Object (BLOB) is binaire data opgeslagen als één entiteit – d.w.z. een BLOB kan een audio-, video- of presentatie-bestand zelf zijn. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Geeft het Aziatische lettertype terug of stelt het in wanneer het bronlettertype niet wordt gevonden. Lezen/schrijven String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Geeft het reguliere lettertype terug of stelt het in wanneer het bronlettertype niet wordt gevonden. Lezen/schrijven String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Geeft het symbolenlettertype terug of stelt het in wanneer het bronlettertype niet wordt gevonden. Lezen/schrijven String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Geeft de standaardtaal voor presentatietekst terug of stelt deze in. Lezen/schrijven String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Bepaalt of Aspose.Slides alle ingesloten binaire objecten zal verwijderen tijdens het laden van de presentatie. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Specificeert bronnen voor externe lettertypen die door de presentatie worden gebruikt. Deze lettertypen zijn gedurende de levensduur van de presentatie beschikbaar en worden niet gedeeld met andere presentaties. |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | Het token om te monitoren voor onderbrekingsverzoeken. Dit token beheert de gehele levensduur van de [`IPresentation`](../ipresentation)-instantie. Elke langdurige bewerking, zoals het laden of opslaan van een presentatie, wordt onderbroken via het aanroepen van de [`Interrupt`](../interruptiontokensource/interrupt)-methode van de [`InterruptionTokenSource`](../interruptiontokensource). |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Geeft het formaat van een te laden presentatie terug of stelt dit in. Lezen/schrijven [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Deze eigenschap is van belang als het presentatie-bestand met een wachtwoord is beveiligd. Een waarde van true betekent dat alleen documenteigenschappen moeten worden geladen uit een versleuteld presentatie-bestand en het wachtwoord moet worden genegeerd. Een waarde van false betekent dat de volledige versleutelde presentatie moet worden geladen met het juiste wachtwoord. Als de presentatie niet versleuteld is, wordt de eigenschap altijd genegeerd. Als de documenteigenschappen van een versleuteld bestand niet openbaar zijn en de eigenschapwaarde true is, kunnen de documenteigenschappen niet worden geladen en wordt er een uitzondering gegooid. Lezen/schrijven Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Haalt het wachtwoord op of stelt het in. Lezen/schrijven String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Geeft de callback-interface terug of stelt deze in die het laden van externe bronnen beheert. Lezen/schrijven [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Haalt opties op voor spreadsheets. Bijvoorbeeld, deze opties beïnvloeden het berekenen van formules voor grafieken. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Geeft een object terug of stelt dit in dat waarschuwingen ontvangt en beslist of het laadproces wordt voortgezet of wordt afgebroken. Lezen/schrijven [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Zie ook

* interface [ILoadOptions](../iloadoptions)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->