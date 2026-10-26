---
title: DocumentProperties
second_title: Aspose.Sildes voor .NET API-referentie
description: Stelt de eigenschappen van een presentatie voor.
type: docs
weight: 2790
url: /nl/aspose.slides/documentproperties/
---
## DocumentProperties klasse

Stelt de eigenschappen van een presentatie voor.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [DocumentProperties](documentproperties)() | Initialiseert een nieuw exemplaar van klasse [`DocumentProperties`](../documentproperties). |

## Properties

| Naam | Beschrijving |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Geeft de sjabloon van een toepassing terug of stelt deze in. Lezen/schrijven String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Geeft de versie van de toepassing terug. Alleen-lezen String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Geeft de auteur van een presentatie terug of stelt deze in. Lezen/schrijven String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Geeft de categorie van een presentatie terug of stelt deze in. Lezen/schrijven String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Geeft de opmerkingen van een presentatie terug of stelt deze in. Lezen/schrijven String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Geeft de bedrijfs-eigenschap terug of stelt deze in. Lezen/schrijven String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Geeft de inhoudstatus van een presentatie terug of stelt deze in. Lezen/schrijven String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Geeft het inhoudstype van een presentatie terug of stelt dit in. Lezen/schrijven String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Geeft het aantal aangepaste eigenschappen dat zich daadwerkelijk in een collectie bevindt terug. Alleen-lezen Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Geeft de datum terug waarop een presentatie is gemaakt. Waarden zijn in UTC. Lezen/schrijven DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Geeft de groepering van documentonderdelen en het aantal onderdelen in elke groep aan. Alleen-lezen IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Geeft het aantal verborgen dia's in een presentatiedocument terug. Alleen-lezen Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Geeft de HyperlinkBase-documenteigenschap terug of stelt deze in. Lezen/schrijven String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Specificeert dat één of meer hyperlinks in dit onderdeel uitsluitend in dit onderdeel door een producent zijn bijgewerkt. De volgende producent die dit document opent, moet de hyperlinkrelaties bijwerken met de nieuwe hyperlinks die in dit onderdeel zijn gespecificeerd. Lezen/schrijven Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Geeft de aangepaste eigenschap die aan een opgegeven naam is gekoppeld terug of stelt deze in. Lezen/schrijven Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Geeft de trefwoorden van een presentatie terug of stelt deze in. Lezen/schrijven String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Geeft de datum terug waarop een presentatie voor het laatst is afgedrukt. Lezen/schrijven DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Geeft de naam terug van de laatste persoon die een presentatie heeft gewijzigd. Lezen/schrijven String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Geeft de datum terug waarop een presentatie voor het laatst is aangepast. Waarden zijn in UTC. Alleen-lezen in het geval van Presentation.DocumentProperties (omdat het intern wordt bijgewerkt tijdens het opslaan van het IPresentation-object). Kan worden gewijzigd via een DocumentProperties-instantie die wordt geretourneerd door methode [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Zie het voorbeeld in de samenvatting van methode [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Geeft aan of hyperlinks in een document up-to-date zijn. Stel dit element in op **true** om aan te geven dat hyperlinks zijn bijgewerkt. Stel dit element in op **false** om aan te geven dat hyperlinks verouderd zijn. Lezen/schrijven Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Geeft de manager-eigenschap terug of stelt deze in. Lezen/schrijven String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Geeft het totale aantal geluids- of videoclips dat zich in het document bevindt terug. Alleen-lezen Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Geeft de naam van de toepassing terug of stelt deze in. Lezen/schrijven String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Geeft het aantal dia's in een presentatie dat notities bevat terug. Alleen-lezen Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Geeft het totale aantal alinea's dat in een document is gevonden terug, indien van toepassing. Alleen-lezen Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Geeft het beoogde formaat van een presentatie terug of stelt dit in. Lezen/schrijven String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Geeft het revisienummer van de presentatie terug of stelt dit in. Lezen/schrijven Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Geeft de weergavemodus van de miniatuur van het document aan. Stel dit element in op **true** om het schalen van de miniatuur naar het scherm mogelijk te maken. Stel dit element in op **false** om bijsnijden van de miniatuur mogelijk te maken zodat alleen secties die op het scherm passen worden getoond. Lezen/schrijven Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Bepaalt of de presentatie wordt gedeeld tussen meerdere personen. Lezen/schrijven Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Geeft het totale aantal dia's in een presentatiedocument terug. Alleen-lezen Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Geeft het onderwerp van een presentatie terug of stelt dit in. Lezen/schrijven String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Geeft de titel van een presentatie terug of stelt deze in. Lezen/schrijven String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Specificeert de titel van elk documentonderdeel. Deze onderdelen zijn geen documentonderdelen maar conceptuele representaties van documentsecties. Alleen-lezen string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Totale bewerkingstijd van een presentatie. Lezen/schrijven TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Geeft het totale aantal woorden dat in een document staat terug. Alleen-lezen Int32. |

## Methods

| Naam | Beschrijving |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Wis en stel standaardwaarden in voor alle ingebouwde eigenschappen. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Verwijdert alle aangepaste eigenschappen. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Kloont het huidige object |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Kloont het huidige object |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Controleert de aanwezigheid van een aangepaste eigenschap met een opgegeven naam. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Retourneert een aangepaste eigenschapsnaam op de opgegeven index. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Haalt een benoemde booleaanse waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Haalt een benoemde DateTime-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Haalt een benoemde double-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Haalt een benoemde float-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Haalt een benoemde gehele-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Haalt een benoemde string-waarde op uit de aangepaste eigenschappen. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | Haalt een array van gevoeligheidslabels op uit de aangepaste documenteigenschappen (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Verwijdert een aangepaste eigenschap die aan een opgegeven naam is gekoppeld. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Stelt een benoemde booleaanse aangepaste eigenschap in. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Stelt een benoemde DateTime-aangepaste eigenschap in. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Stelt een benoemde double-aangepaste eigenschap in. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Stelt een benoemde float-aangepaste eigenschap in. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Stelt een benoemde gehele-aangepaste eigenschap in. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Stelt een benoemde string-aangepaste eigenschap in. |

### Voorbeelden

Het volgende voorbeeld toont hoe u de ingebouwde eigenschappen van een PowerPoint-presentatie kunt benaderen.

```csharp
[C#]
// Instantieer de Presentation-klasse die de presentatie vertegenwoordigt
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Maak een referentie naar het IDocumentProperties-object dat aan Presentation is gekoppeld
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Toon de ingebouwde eigenschappen
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

Het volgende voorbeeld toont hoe u de ingebouwde eigenschappen van een PowerPoint-presentatie kunt wijzigen.

```csharp
[C#]
// Instantieer de Presentation-klasse die de Presentation vertegenwoordigt
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Maak een referentie naar het IDocumentProperties-object dat aan Presentation is gekoppeld
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// Stel de ingebouwde eigenschappen in
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// Sla uw presentatie op in een bestand
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### Zie ook

* interface [IDocumentProperties](../idocumentproperties)
* interface [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->