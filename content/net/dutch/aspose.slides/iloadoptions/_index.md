---
title: ILoadOptions
second_title: Aspose.Sildes voor .NET API-referentie
description: Staat toe extra opties op te geven, zoals formaat of standaardlettertype, bij het laden van een presentatie.
type: docs
weight: 6340
url: /nl/aspose.slides/iloadoptions/
---
## ILoadOptions interface

Staat toe extra opties op te geven (zoals formaat of standaardlettertype) bij het laden van een presentatie.

```csharp
public interface ILoadOptions
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/iloadoptions/blobmanagementoptions) { get; set; } | Stelt de opties voor die kunnen worden gebruikt om het gedrag van het omgaan met Binary Large Objects (BLOB's) te beheren, bijvoorbeeld het gebruik van tijdelijke bestanden of het maximale aantal BLOB-bytes in het geheugen. Deze opties zijn bedoeld om de beste verhouding tussen prestaties en geheugenverbruik in te stellen voor een specifieke omgeving of vereisten. Een Binary Large Object (BLOB) is binaire data die als één entiteit wordt opgeslagen – d.w.z. een BLOB kan een audio-, video- of presentatie zelf zijn. |
| [DefaultAsianFont](../../aspose.slides/iloadoptions/defaultasianfont) { get; set; } | Geeft het Aziatische lettertype terug of stelt het in dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Lezen-schrijven String. |
| [DefaultRegularFont](../../aspose.slides/iloadoptions/defaultregularfont) { get; set; } | Geeft het reguliere lettertype terug of stelt het in wanneer het bronlettertype niet wordt gevonden. Lezen-schrijven String. |
| [DefaultSymbolFont](../../aspose.slides/iloadoptions/defaultsymbolfont) { get; set; } | Geeft het Symbool-lettertype terug of stelt het in wanneer het bronlettertype niet wordt gevonden. Lezen-schrijven String. |
| [DefaultTextLanguage](../../aspose.slides/iloadoptions/defaulttextlanguage) { get; set; } | Geeft de standaardtaal voor presentatietekst terug of stelt deze in. Lezen/schrijven String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/iloadoptions/deleteembeddedbinaryobjects) { get; set; } | Bepaalt of Aspose.Slides alle ingebedde binaire objecten zal verwijderen tijdens het laden van de presentatie. |
| [DocumentLevelFontSources](../../aspose.slides/iloadoptions/documentlevelfontsources) { get; set; } | Specificeert de bronnen voor externe lettertypen die door de presentatie worden gebruikt. Deze lettertypen zijn gedurende de volledige levensduur van de presentatie beschikbaar en worden niet gedeeld met andere presentaties |
| [InterruptionToken](../../aspose.slides/iloadoptions/interruptiontoken) { get; set; } | Het token om te monitoren voor onderbrekingsverzoeken.  Dit token beheert de volledige levensduur van de [`IPresentation`](../ipresentation) instantie. Elke langdurige bewerking, zoals het laden of opslaan van een presentatie, wordt onderbroken via het aanroepen van de [`Interrupt`](../iinterruptiontokensource/interrupt) methode van de [`IInterruptionTokenSource`](../iinterruptiontokensource). |
| [LoadFormat](../../aspose.slides/iloadoptions/loadformat) { get; set; } | Geeft het formaat van een te laden presentatie terug of stelt dit in. Lezen/schrijven [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/iloadoptions/onlyloaddocumentproperties) { get; set; } | Deze eigenschap heeft betekenis als het presentatied bestand met wachtwoord is beveiligd. De waarde true betekent dat alleen documenteigenschappen moeten worden geladen uit een versleuteld presentatiebestand en het wachtwoord moet worden genegeerd. De waarde false betekent dat de volledige versleutelde presentatie moet worden geladen met het juiste wachtwoord. Als de presentatie niet versleuteld is, wordt de eigenschapswaarde altijd genegeerd. Als de documenteigenschappen van een versleuteld bestand niet openbaar zijn en de eigenschapswaarde true is, kunnen de documenteigenschappen niet worden geladen en wordt er een uitzondering gegooid. Lezen-schrijven Boolean. |
| [Password](../../aspose.slides/iloadoptions/password) { get; set; } | Geeft het wachtwoord terug of stelt het in. Lezen-schrijven String. |
| [ResourceLoadingCallback](../../aspose.slides/iloadoptions/resourceloadingcallback) { get; set; } | Geeft de callback-interface terug of stelt deze in die het laden van externe bronnen beheert. Lezen/schrijven [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/iloadoptions/spreadsheetoptions) { get; set; } | Stelt opties voor die kunnen worden gebruikt om extra spreadsheet-gedrag te specificeren. |
| [WarningCallback](../../aspose.slides/iloadoptions/warningcallback) { get; set; } | Geeft een object terug of stelt dit in dat waarschuwingen ontvangt en bepaalt of het laadproces wordt voortgezet of wordt afgebroken. Lezen/schrijven [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Zie ook

* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->