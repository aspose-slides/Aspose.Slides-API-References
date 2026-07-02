---
title: IDocumentProperties
second_title: Aspose.Sildes voor .NET API-referentie
description: Vertegenwoordigt eigenschappen van een presentatie.
type: docs
weight: 5710
url: /nl/aspose.slides/idocumentproperties/
---
## IDocumentProperties interface

Stelt de eigenschappen van een presentatie voor.

```csharp
public interface IDocumentProperties
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Geeft de sjabloon van een toepassing terug of stelt deze in. Lezen/Schrijven String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Geeft de app-versie terug. Alleen-lezen String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Geeft de auteur van een presentatie terug of stelt deze in. Lezen/Schrijven String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Geeft de categorie van een presentatie terug of stelt deze in. Lezen/Schrijven String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Geeft de opmerkingen van een presentatie terug of stelt deze in. Lezen/Schrijven String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Geeft de bedrijfs-eigenschap terug of stelt deze in. Lezen/Schrijven String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Geeft de inhoudsstatus van een presentatie terug of stelt deze in. Lezen/Schrijven String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Geeft het inhoudstype van een presentatie terug of stelt dit in. Lezen/Schrijven String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Geeft het aantal aangepaste eigenschappen dat daadwerkelijk in een collectie zit terug. Alleen-lezen Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Geeft de datum waarop een presentatie is gemaakt terug. De waarden zijn in UTC. Lezen/Schrijven DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Geeft de groepering van documentonderdelen en het aantal onderdelen in elke groep aan. Alleen-lezen IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Specificeert het aantal verborgene dia's in een presentatiedocument. Alleen-lezen Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Geeft de HyperlinkBase-documenteigenschap terug of stelt deze in. Lezen/Schrijven String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Specificeert dat één of meer hyperlinks in dit onderdeel uitsluitend in dit onderdeel door een producent zijn bijgewerkt. De volgende producent die dit document opent, dient de hyperlinkrelaties bij te werken met de nieuwe hyperlinks die in dit onderdeel zijn gespecificeerd. Lezen/Schrijven Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Geeft de aangepaste eigenschap gekoppeld aan een opgegeven naam terug of stelt deze in. Lezen/Schrijven Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Geeft de trefwoorden van een presentatie terug of stelt deze in. Lezen/Schrijven String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Geeft de datum waarop een presentatie voor het laatst is afgedrukt terug. Lezen/Schrijven DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Geeft de naam van de laatste persoon die een presentatie heeft bewerkt terug of stelt deze in. Lezen/Schrijven String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; } | Geeft de datum waarop een presentatie voor het laatst is gewijzigd terug. De waarden zijn in UTC. Alleen-lezen in het geval van Presentation.DocumentProperties (omdat het intern wordt bijgewerkt tijdens het opslaan van het IPresentation-object). Kan worden gewijzigd via DocumentProperties-instantie geretourneerd door methode [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Zie het voorbeeld in samenvatting van methode [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Geeft aan of hyperlinks in een document up-to-date zijn. Stel dit element in op **true** om aan te geven dat hyperlinks zijn bijgewerkt. Stel dit element in op **false** om aan te geven dat hyperlinks verouderd zijn. Lezen/Schrijven Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Geeft de manager-eigenschap terug of stelt deze in. Lezen/Schrijven String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Specificeert het totale aantal geluids- of videoclips dat in het document aanwezig is. Alleen-lezen Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Geeft de naam van de toepassing terug of stelt deze in. Lezen/Schrijven String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Specificeert het aantal dia's in een presentatie die notities bevatten. Alleen-lezen Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Specificeert het totale aantal alinea's dat in een document is gevonden, indien van toepassing. Alleen-lezen Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Geeft het beoogde formaat van een presentatie terug of stelt dit in. Lezen/Schrijven String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Geeft het revisienummer van de presentatie terug of stelt dit in. Lezen/Schrijven Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Geeft de weergavemodus van de miniatuur van het document aan. Stel dit element in op **true** om de schaal van de documentminiatuur aan te passen aan het display. Stel dit element in op **false** om de bijsnijding van de documentminiatuur in te schakelen zodat alleen secties worden getoond die op het display passen. Lezen/Schrijven Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Bepaalt of de presentatie wordt gedeeld tussen meerdere personen. Lezen/Schrijven Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Specificeert het totale aantal dia's in een presentatiedocument. Alleen-lezen Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Geeft het onderwerp van een presentatie terug of stelt dit in. Lezen/Schrijven String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Geeft de titel van een presentatie terug of stelt deze in. Lezen/Schrijven String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Specificeert de titel van elk documentonderdeel. Deze onderdelen zijn geen documentonderdelen maar conceptuele weergaven van documentsecties. Alleen-lezen string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Totale bewerkingstijd van een presentatie. Lezen/Schrijven TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Specificeert het totale aantal woorden dat in een document voorkomt. Alleen-lezen Int32. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Wis en stel standaardwaarden in voor alle ingebouwde eigenschappen. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Verwijdert alle aangepaste eigenschappen. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Controleer de aanwezigheid van een aangepaste eigenschap met een opgegeven naam. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Retourneer de naam van een aangepaste eigenschap op de opgegeven index. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Haalt een benoemde booleaanse waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Haalt een benoemde DateTime-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Haalt een benoemde double-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Haalt een benoemde float-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Haalt een benoemde integer-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Haalt een benoemde string-waarde op uit de aangepaste eigenschappen. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Haalt een array van gevoeligheidslabels op uit de aangepaste documenteigenschappen (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Verwijdert een aangepaste eigenschap die is gekoppeld aan een opgegeven naam. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Stelt een benoemde booleaanse aangepaste eigenschap in. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Stelt een benoemde DateTime-aangepaste eigenschap in. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Stelt een benoemde double-aangepaste eigenschap in. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Stelt een benoemde float-aangepaste eigenschap in. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Stelt een benoemde integer-aangepaste eigenschap in. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Stelt een benoemde string-aangepaste eigenschap in. |

### Zie ook

* naamruimte [Aspose.Slides](../../aspose.slides)
* assemblage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->