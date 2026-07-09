---
title: IDocumentProperties
second_title: Aspose.Sildes voor .NET API-referentie
description: Beschrijft eigenschappen van een presentatie.
type: docs
weight: 5710
url: /nl/aspose.slides/idocumentproperties/
---
## IDocumentProperties interface

Beschrijft eigenschappen van een presentatie.

```csharp
public interface IDocumentProperties
```

## Eigenschappen

| Name | Description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Geeft of stelt het sjabloon van een applicatie in. Lezen/Schrijven String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Geeft de versie van de applicatie. Alleen-lezen String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Geeft of stelt de auteur van een presentatie in. Lezen/Schrijven String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Geeft of stelt de categorie van een presentatie in. Lezen/Schrijven String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Geeft of stelt de opmerkingen van een presentatie in. Lezen/Schrijven String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Geeft of stelt de bedrijfs-eigenschap in. Lezen/Schrijven String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Geeft of stelt de inhoudsstatus van een presentatie in. Lezen/Schrijven String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Geeft of stelt het inhoudstype van een presentatie in. Lezen/Schrijven String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Geeft het aantal aangepaste eigenschappen dat daadwerkelijk in een collectie aanwezig is. Alleen-lezen Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Geeft de datum waarop een presentatie is gemaakt. De waarden zijn in UTC. Lezen/Schrijven DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Geeft de groepering van documentonderdelen en het aantal onderdelen in elke groep aan. Alleen-lezen IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Specificeert het aantal verborgen dia's in een presentatiedocument. Alleen-lezen Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Geeft of stelt de HyperlinkBase-documenteigenschap in. Lezen/Schrijven String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Specificeert dat één of meer hyperlinks in dit onderdeel uitsluitend in dit onderdeel door een producer zijn bijgewerkt. De volgende producer die dit document opent, moet de hyperlinkrelaties bijwerken met de nieuwe hyperlinks die in dit onderdeel zijn gespecificeerd. Lezen/Schrijven Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Geeft of stelt de aangepaste eigenschap gekoppeld aan een opgegeven naam in. Lezen/Schrijven Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Geeft of stelt de sleutelwoorden van een presentatie in. Lezen/Schrijven String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Geeft de datum waarop een presentatie voor het laatst werd afgedrukt. Lezen/Schrijven DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Geeft of stelt de naam van de laatste persoon die een presentatie heeft bewerkt in. Lezen/Schrijven String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Geeft de datum waarop een presentatie voor het laatst is bewerkt. De waarden zijn in UTC. Alleen-lezen in het geval van Presentation.DocumentProperties (omdat het intern wordt bijgewerkt tijdens het opslaan van het IPresentation-object). Kan worden gewijzigd via de DocumentProperties-instantie die wordt geretourneerd door methode [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Zie het voorbeeld in de samenvatting van methode [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Geeft aan of hyperlinks in een document up-to-date zijn. Stel dit element in op **true** om aan te geven dat hyperlinks zijn bijgewerkt. Stel dit element in op **false** om aan te geven dat hyperlinks verouderd zijn. Lezen/Schrijven Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Geeft of stelt de manager-eigenschap in. Lezen/Schrijven String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Specificeert het totale aantal geluids- of videoclips dat in het document aanwezig is. Alleen-lezen Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Geeft of stelt de naam van de toepassing in. Lezen/Schrijven String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Specificeert het aantal dia's in een presentatie dat notities bevat. Alleen-lezen Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Specificeert het totale aantal alinea's dat in een document is gevonden, indien van toepassing. Alleen-lezen Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Geeft of stelt het beoogde formaat van een presentatie in. Lezen/Schrijven String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Geeft of stelt het revisienummer van de presentatie in. Lezen/Schrijven Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Geeft de weergavemodus van de miniatuur van het document aan. Stel dit element in op **true** om het schalen van de miniatuur naar het scherm in te schakelen. Stel dit element in op **false** om het bijsnijden van de miniatuur in te schakelen zodat alleen delen die op het scherm passen worden getoond. Lezen/Schrijven Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Bepaalt of de presentatie wordt gedeeld tussen meerdere personen. Lezen/Schrijven Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Specificeert het totale aantal dia's in een presentatiedocument. Alleen-lezen Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Geeft of stelt het onderwerp van een presentatie in. Lezen/Schrijven String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Geeft of stelt de titel van een presentatie in. Lezen/Schrijven String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Specificeert de titel van elk documentonderdeel. Deze onderdelen zijn geen documentonderdelen, maar conceptuele representaties van documentsecties. Alleen-lezen string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Totale bewerkingstijd van een presentatie. Lezen/Schrijven TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Specificeert het totale aantal woorden dat in een document zit. Alleen-lezen Int32. |

## Methoden

| Name | Description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Wis en stel standaardwaarden in voor alle ingebouwde eigenschappen. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Verwijdert alle aangepaste eigenschappen. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Controleert de aanwezigheid van een aangepaste eigenschap met een opgegeven naam. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Geeft de naam van een aangepaste eigenschap op de opgegeven index terug. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Haalt een benoemde bool-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Haalt een benoemde DateTime-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Haalt een benoemde double-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Haalt een benoemde float-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Haalt een benoemde integer-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Haalt een benoemde string-waarde op uit de aangepaste eigenschappen. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Haalt een array van gevoeligheidslabels op uit de aangepaste documenteigenschappen (Microsoft Information Protection SDK-metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Verwijdert een aangepaste eigenschap die aan een opgegeven naam is gekoppeld. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Stelt een benoemde bool-aangepaste eigenschap in. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Stelt een benoemde DateTime-aangepaste eigenschap in. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Stelt een benoemde double-aangepaste eigenschap in. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Stelt een benoemde float-aangepaste eigenschap in. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Stelt een benoemde integer-aangepaste eigenschap in. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Stelt een benoemde string-aangepaste eigenschap in. |

### Zie ook

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->