---
title: IDocumentProperties
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt de eigenschappen van een presentatie voor.
type: docs
weight: 5730
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
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Geeft de sjabloon van een applicatie terug of stelt deze in. Lezen/schrijven String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Geeft de versie van de app terug. Alleen-lezen String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Geeft de auteur van een presentatie terug of stelt deze in. Lezen/schrijven String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Geeft de categorie van een presentatie terug of stelt deze in. Lezen/schrijven String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Geeft de opmerkingen van een presentatie terug of stelt deze in. Lezen/schrijven String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Geeft de bedrijfseigenschap terug of stelt deze in. Lezen/schrijven String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Geeft de inhoudsstatus van een presentatie terug of stelt deze in. Lezen/schrijven String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Geeft het inhoudstype van een presentatie terug of stelt dit in. Lezen/schrijven String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Geeft het aantal aangepaste eigenschappen dat daadwerkelijk in een collectie zit terug. Alleen-lezen Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Geeft de datum waarop een presentatie werd gemaakt terug. Waarden zijn in UTC. Lezen/schrijven DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Geeft de groepering van documentonderdelen en het aantal onderdelen in elke groep aan. Alleen-lezen IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Specificeert het aantal verborgen dia's in een presentatiedocument. Alleen-lezen Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Geeft de HyperlinkBase-documenteigenschap terug of stelt deze in. Lezen/schrijven String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Specificeert dat één of meer hyperlinks in dit onderdeel uitsluitend door een producer in dit onderdeel zijn bijgewerkt. De volgende producer die dit document opent, moet de hyperlinkrelaties bijwerken met de nieuwe hyperlinks die in dit onderdeel zijn opgegeven. Lezen/schrijven Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Geeft de aangepaste eigenschap die aan een opgegeven naam is gekoppeld terug of stelt deze in. Lezen/schrijven Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Geeft de trefwoorden van een presentatie terug of stelt deze in. Lezen/schrijven String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Geeft de datum waarop een presentatie voor het laatst werd afgedrukt terug. Lezen/schrijven DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Geeft de naam van de laatste persoon die een presentatie heeft gewijzigd terug of stelt deze in. Lezen/schrijven String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Geeft de datum waarop een presentatie voor het laatst is gewijzigd terug. Waarden zijn in UTC.P Alleen-lezen in het geval van Presentation.DocumentProperties (omdat deze intern wordt bijgewerkt tijdens het opslaan van het IPresentation-object). Kan worden gewijzigd via de DocumentProperties-instantie die wordt geretourneerd door methode [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Zie het voorbeeld in de samenvatting van methode [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Geeft aan of hyperlinks in een document up-to-date zijn. Stel dit element in op **true** om aan te geven dat hyperlinks zijn bijgewerkt. Stel dit element in op **false** om aan te geven dat hyperlinks verouderd zijn. Lezen/schrijven Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Geeft de manager-eigenschap terug of stelt deze in. Lezen/schrijven String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Specificeert het totale aantal geluids- of video-fragmenten dat in het document aanwezig is. Alleen-lezen Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Geeft de naam van de applicatie terug of stelt deze in. Lezen/schrijven String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Specificeert het aantal dia's in een presentatie met aantekeningen. Alleen-lezen Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Specificeert het totale aantal alinea's dat in een document is gevonden, indien van toepassing. Alleen-lezen Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Geeft het beoogde formaat van een presentatie terug of stelt dit in. Lezen/schrijven String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Geeft het revisienummer van de presentatie terug of stelt dit in. Lezen/schrijven Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Geeft de weergavemodus van de documentminiatuur aan. Stel dit element in op **true** om het schalen van de documentminiatuur naar het scherm in te schakelen. Stel dit element in op **false** om bijsnijden van de documentminiatuur in te schakelen zodat alleen secties die op het scherm passen worden getoond. Lezen/schrijven Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Bepaalt of de presentatie wordt gedeeld tussen meerdere personen. Lezen/schrijven Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Specificeert het totale aantal dia's in een presentatiedocument. Alleen-lezen Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Geeft het onderwerp van een presentatie terug of stelt dit in. Lezen/schrijven String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Geeft de titel van een presentatie terug of stelt deze in. Lezen/schrijven String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Specificeert de titel van elk documentonderdeel. Deze onderdelen zijn geen documentonderdelen, maar conceptuele weergaven van documentsecties. Alleen-lezen string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Totale bewerkingstijd van een presentatie. Lezen/schrijven TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Specificeert het totale aantal woorden in een document. Alleen-lezen Int32. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Wis en stel standaardwaarden in voor alle ingebouwde eigenschappen. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Verwijdert alle aangepaste eigenschappen. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Controleer de aanwezigheid van een aangepaste eigenschap met een opgegeven naam. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Geef een aangepaste eigenschapsnaam terug op de opgegeven index. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Haalt een benoemde booleaanse waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Haalt een benoemde DateTime-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Haalt een benoemde double-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Haalt een benoemde float-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Haalt een benoemde integer-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Haalt een benoemde string-waarde op uit de aangepaste eigenschappen. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Haalt een array met gevoeligheidslabels op uit de aangepaste documenteigenschappen (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Verwijdert een aangepaste eigenschap die aan een opgegeven naam is gekoppeld. |
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