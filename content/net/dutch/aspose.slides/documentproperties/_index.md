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

## Constructoren

| Naam | Beschrijving |
| --- | --- |
| [DocumentProperties](documentproperties)() | Initialiseert een nieuw exemplaar van klasse [`DocumentProperties`](../documentproperties). |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Retourneert of stelt het sjabloon van een toepassing in. Lezen/schrijven String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Retourneert de versie van de toepassing. Alleen-lezen String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Retourneert of stelt de auteur van een presentatie in. Lezen/schrijven String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Retourneert of stelt de categorie van een presentatie in. Lezen/schrijven String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Retourneert of stelt de opmerkingen van een presentatie in. Lezen/schrijven String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Retourneert of stelt de bedrijfs eigenschap in. Lezen/schrijven String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Retourneert of stelt de inhoudstatus van een presentatie in. Lezen/schrijven String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Retourneert of stelt het inhoudstype van een presentatie in. Lezen/schrijven String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Retourneert het aantal aangepaste eigenschappen dat daadwerkelijk in een collectie voorkomt. Alleen-lezen Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Retourneert de datum waarop een presentatie is gemaakt. Waarden zijn in UTC. Lezen/schrijven DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Geeft de groepering van documentonderdelen en het aantal onderdelen in elke groep aan. Alleen-lezen IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Retourneert het aantal verborgen dia's in een presentatiedocument. Alleen-lezen Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Retourneert of stelt de HyperlinkBase documenteigenschap in. Lezen/schrijven String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Specificeert dat één of meer hyperlinks in dit onderdeel exclusief in dit onderdeel door een producent zijn bijgewerkt. De volgende producent die dit document opent, moet de hyperlinkrelaties bijwerken met de nieuwe hyperlinks die in dit onderdeel zijn gespecificeerd. Lezen/schrijven Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Retourneert of stelt de aangepaste eigenschap die aan een opgegeven naam is gekoppeld in. Lezen/schrijven Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Retourneert of stelt de sleutelwoorden van een presentatie in. Lezen/schrijven String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Retourneert de datum waarop een presentatie voor het laatst is afgedrukt. Lezen/schrijven DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Retourneert of stelt de naam van de laatste persoon die een presentatie heeft gewijzigd in. Lezen/schrijven String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Retourneert de datum waarop een presentatie voor het laatst is gewijzigd. Waarden zijn in UTC. Alleen-lezen in het geval van Presentation.DocumentProperties (omdat het intern wordt bijgewerkt tijdens het opslaan van het IPresentation-object). Kan worden gewijzigd via een DocumentProperties-instantie die wordt geretourneerd door de methode [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Zie het voorbeeld in de samenvatting van de methode [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Geeft aan of hyperlinks in een document up-to-date zijn. Stel dit element in op **true** om aan te geven dat hyperlinks zijn bijgewerkt. Stel dit element in op **false** om aan te geven dat hyperlinks verouderd zijn. Lezen/schrijven Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Retourneert of stelt de manager-eigenschap in. Lezen/schrijven String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Retourneert het totale aantal geluid- of video-clips dat in het document aanwezig is. Alleen-lezen Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Retourneert of stelt de naam van de toepassing in. Lezen/schrijven String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Retourneert het aantal dia's in een presentatie die notities bevatten. Alleen-lezen Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Retourneert het totale aantal alinea's dat in een document is gevonden, indien van toepassing. Alleen-lezen Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Retourneert of stelt het beoogde formaat van een presentatie in. Lezen/schrijven String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Retourneert of stelt het revisienummer van de presentatie in. Lezen/schrijven Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Geeft de weergavemodus van de documentminiatuur aan. Stel dit element in op **true** om het schalen van de documentminiatuur naar het scherm mogelijk te maken. Stel dit element in op **false** om bijsnijden van de documentminiatuur mogelijk te maken zodat alleen secties die op het scherm passen worden getoond. Lezen/schrijven Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Bepaalt of de presentatie wordt gedeeld tussen meerdere personen. Lezen/schrijven Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Retourneert het totale aantal dia's in een presentatiedocument. Alleen-lezen Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Retourneert of stelt het onderwerp van een presentatie in. Lezen/schrijven String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Retourneert of stelt de titel van een presentatie in. Lezen/schrijven String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Specificeert de titel van elk documentonderdeel. Deze onderdelen zijn geen documentonderdelen maar conceptuele weergaven van documentsecties. Alleen-lezen string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Totale bewerkingstijd van een presentatie. Lezen/schrijven TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Retourneert het totale aantal woorden dat in een document voorkomt. Alleen-lezen Int32. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Wis en stel standaardwaarden in voor alle ingebouwde eigenschappen. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Verwijdert alle aangepaste eigenschappen. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Kloon het huidige object |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Kloon het huidige object |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Controleert de aanwezigheid van een aangepaste eigenschap met een opgegeven naam. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Retourneert een aangepaste eigenschapsnaam op de opgegeven index. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Haalt een benoemde booleaanse waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Haalt een benoemde DateTime-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Haalt een benoemde double-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Haalt een benoemde float-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Haalt een benoemde integer-waarde op uit de aangepaste eigenschappen. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Haalt een benoemde string-waarde op uit de aangepaste eigenschappen. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | Haalt een array met gevoeligheidslabels op uit de aangepaste documenteigenschappen (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Verwijdert een aangepaste eigenschap die aan een opgegeven naam is gekoppeld. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Stelt een benoemde booleaanse aangepaste eigenschap in. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Stelt een benoemde DateTime-aangepaste eigenschap in. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Stelt een benoemde double-aangepaste eigenschap in. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Stelt een benoemde float-aangepaste eigenschap in. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Stelt een benoemde integer-aangepaste eigenschap in. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Stelt een benoemde string-aangepaste eigenschap in. |

### Voorbeelden

Het volgende voorbeeld toont hoe de ingebouwde eigenschappen van een PowerPoint-presentatie kunnen worden benaderd.

```csharp
[C#]
// Maak een instantie van de Presentation-klasse die de presentatie vertegenwoordigt
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Maak een referentie naar het IDocumentProperties-object dat aan de Presentation is gekoppeld
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Toon de ingebouwde eigenschappen
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

Het volgende voorbeeld toont hoe de ingebouwde eigenschappen van een PowerPoint-presentatie kunnen worden gewijzigd.

```csharp
[C#]
// Maak een instantie van de Presentation-klasse die de presentatie vertegenwoordigt
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Maak een referentie naar het IDocumentProperties-object dat aan de Presentation is gekoppeld
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// Stel de ingebouwde eigenschappen in
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// Sla uw presentatie op naar een bestand
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### Zie ook

* interface [IDocumentProperties](../idocumentproperties)
* interface [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->