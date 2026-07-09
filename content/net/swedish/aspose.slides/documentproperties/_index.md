---
title: DocumentProperties
second_title: Aspose.Sildes för .NET API-referens
description: Representerar egenskaper för en presentation.
type: docs
weight: 2790
url: /sv/aspose.slides/documentproperties/
---
## DocumentProperties klass

Representerar egenskaper för en presentation.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## Konstruktorer

| Namn | Beskrivning |
| --- | --- |
| [DocumentProperties](documentproperties)() | Initialiserar en ny instans av klassen [`DocumentProperties`](../documentproperties). |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Returnerar eller anger mallen för en applikation. Läs/skriv String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Returnerar appens version. Endast läs String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Returnerar eller anger författaren till en presentation. Läs/skriv String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Returnerar eller anger kategorin för en presentation. Läs/skriv String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Returnerar eller anger kommentarer för en presentation. Läs/skriv String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Returnerar eller anger företagsegenskapen. Läs/skriv String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Returnerar eller anger innehållsstatus för en presentation. Läs/skriv String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Returnerar eller anger innehållstyp för en presentation. Läs/skriv String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Returnerar antalet anpassade egenskaper som faktiskt finns i en samling. Endast läs Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Returnerar datumet då en presentation skapades. Värdena är i UTC. Läs/skriv DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Anger gruppering av dokumentdelar och antalet delar i varje grupp. Endast läs IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Returnerar antalet dolda bilder i ett presentationsdokument. Endast läs Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Returnerar eller anger HyperlinkBase-dokumentegenskapen. Läs/skriv String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Anger att en eller flera hyperlänkar i denna del uppdaterades uteslutande i denna del av en producent. Nästa producent som öppnar detta dokument ska uppdatera hyperlänksrelationerna med de nya hyperlänkarna som anges i denna del. Läs/skriv Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Returnerar eller anger den anpassade egenskapen som är associerad med ett angivet namn. Läs/skriv Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Returnerar eller anger nyckelorden för en presentation. Läs/skriv String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Returnerar datumet då en presentation senast skrevs ut. Läs/skriv DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Returnerar eller anger namnet på den senaste personen som ändrade en presentation. Läs/skriv String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Returnerar datumet då en presentation senast ändrades. Värdena är i UTC. Endast läs i fallet Presentation.DocumentProperties (eftersom den uppdateras internt under IPresentation-objektets sparprocess). Kan ändras via DocumentProperties-instansen som returneras av metoden [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Se exempel i metodsammanfattningen för [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Anger om hyperlänkar i ett dokument är aktuella. Ställ in detta element till **true** för att indikera att hyperlänkar är uppdaterade. Ställ in detta element till **false** för att indikera att hyperlänkar är föråldrade. Läs/skriv Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Returnerar eller anger chefegenskapen. Läs/skriv String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Returnerar det totala antalet ljud- eller videoklipp som finns i dokumentet. Endast läs Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Returnerar eller anger namnet på applikationen. Läs/skriv String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Returnerar antalet bilder i en presentation som innehåller anteckningar. Endast läs Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Returnerar det totala antalet stycken som hittas i ett dokument om tillämpligt. Endast läs Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Returnerar eller anger det avsedda formatet för en presentation. Läs/skriv String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Returnerar eller anger presentationsrevisionsnumret. Läs/skriv Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Anger visningsläget för dokumentets miniatyrbild. Ställ in detta element till **true** för att möjliggöra skalning av miniatyrbilden till displayen. Ställ in detta element till **false** för att möjliggöra beskärning av miniatyrbilden så att endast sektioner som passar displayen visas. Läs/skriv Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Bestämmer om presentationen delas mellan flera personer. Läs/skriv Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Returnerar det totala antalet bilder i ett presentationsdokument. Endast läs Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Returnerar eller anger ämnet för en presentation. Läs/skriv String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Returnerar eller anger titeln för en presentation. Läs/skriv String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Anger titeln på varje dokumentdel. Dessa delar är inte dokumentdelar utan konceptuella representationer av dokumentssektioner. Endast läs string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Total redigeringstid för en presentation. Läs/skriv TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Returnerar det totala antalet ord som finns i ett dokument. Endast läs Int32. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Rensar och sätter standardvärden för alla inbyggda egenskaper. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Tar bort alla anpassade egenskaper. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Klonar aktuellt objekt |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Klonar aktuellt objekt |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Kontrollerar förekomsten av en anpassad egenskap med ett angivet namn. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Returnerar ett anpassat egenskapsnamn på det angivna indexet. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Hämtar ett namngivet booleskt värde från de anpassade egenskaperna. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Hämtar ett namngivet DateTime-värde från de anpassade egenskaperna. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Hämtar ett namngivet double-värde från de anpassade egenskaperna. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Hämtar ett namngivet float-värde från de anpassade egenskaperna. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Hämtar ett namngivet heltal från de anpassade egenskaperna. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Hämtar ett namngivet strängvärde från de anpassade egenskaperna. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | Hämtar en array av känslighetsetiketter från de anpassade dokumentegenskaperna (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Tar bort en anpassad egenskap som är associerad med ett angivet namn. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Ställer in en namngiven boolesk anpassad egenskap. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Ställer in en namngiven DateTime-anpassad egenskap. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Ställer in en namngiven double-anpassad egenskap. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Ställer in en namngiven float-anpassad egenskap. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Ställer in en namngiven heltals-anpassad egenskap. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Ställer in en namngiven sträng-anpassad egenskap. |

### Exempel

Följande exempel visar hur man får åtkomst till inbyggda egenskaper i en PowerPoint-presentation.

```csharp
[C#]
// Skapa en instans av Presentation-klassen som representerar presentationen
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Skapa en referens till IDocumentProperties-objektet som är associerat med Presentation
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Visa de inbyggda egenskaperna
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

Följande exempel visar hur man ändrar inbyggda egenskaper i en PowerPoint-presentation.

```csharp
[C#]
// Skapa en instans av Presentation-klassen som representerar Presentation
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Skapa en referens till IDocumentProperties-objektet som är associerat med Presentation
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// Ställ in de inbyggda egenskaperna
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// Spara din presentation till en fil
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### Se även

* gränssnitt [IDocumentProperties](../idocumentproperties)
* gränssnitt [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->