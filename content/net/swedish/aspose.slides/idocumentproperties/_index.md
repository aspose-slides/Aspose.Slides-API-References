---
title: IDocumentProperties
second_title: Aspose.Sildes för .NET API-referens
description: Representerar egenskaper för en presentation.
type: docs
weight: 5690
url: /sv/aspose.slides/idocumentproperties/
---
## IDocumentProperties gränssnitt

Representerar egenskaper för en presentation.

```csharp
public interface IDocumentProperties
```

## Egenskaper

| Name | Description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Returnerar eller anger mall för en applikation. Läs/skriv String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Returnerar programversionen. Endast läsning String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Returnerar eller anger författaren till en presentation. Läs/skriv String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Returnerar eller anger kategorin för en presentation. Läs/skriv String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Returnerar eller anger kommentarer för en presentation. Läs/skriv String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Returnerar eller anger företagsegenskapen. Läs/skriv String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Returnerar eller anger innehållsstatus för en presentation. Läs/skriv String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Returnerar eller anger innehållstypen för en presentation. Läs/skriv String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Returnerar antalet anpassade egenskaper som faktiskt finns i en samling. Endast läsning Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Returnerar datumet då en presentation skapades. Värdena är i UTC. Läs/skriv DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Indikerar gruppering av dokumentdelar och antalet delar i varje grupp. Endast läsning IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Anger antalet dolda bilder i ett presentationsdokument. Endast läsning Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Returnerar eller anger HyperlinkBase-dokumentegenskapen. Läs/skriv String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Anger att en eller flera hyperlänkar i denna del uppdaterades uteslutande i denna del av en producent. Nästa producent som öppnar detta dokument ska uppdatera hyperlänksrelationerna med de nya hyperlänkarna som specificerats i denna del. Läs/skriv Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Returnerar eller anger den anpassade egenskapen som är associerad med ett specificerat namn. Läs/skriv Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Returnerar eller anger nyckelorden för en presentation. Läs/skriv String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Returnerar datumet då en presentation senast skrevs ut. Läs/skriv DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Returnerar eller anger namnet på den senaste personen som modifierade en presentation. Läs/skriv String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Returnerar datumet då en presentation senast modifierades. Värdena är i UTC. Endast läsning i fallet Presentation.DocumentProperties (eftersom den uppdateras internt under IPresentation-objektets sparprocess). Kan ändras via DocumentProperties-instansen som returneras av metoden [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Se exemplet i [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) metodsammanfattning. |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Indikerar om hyperlänkar i ett dokument är aktuella. Sätt detta element till **true** för att indikera att hyperlänkar är uppdaterade. Sätt detta element till **false** för att indikera att hyperlänkar är föråldrade. Läs/skriv Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Returnerar eller anger chefsegenskapen. Läs/skriv String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Anger det totala antalet ljud- eller videoklipp som finns i dokumentet. Endast läsning Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Returnerar eller anger namnet på applikationen. Läs/skriv String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Anger antalet bilder i en presentation som innehåller anteckningar. Endast läsning Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Anger det totala antalet stycken som hittas i ett dokument, om tillämpligt. Endast läsning Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Returnerar eller anger det avsedda formatet för en presentation. Läs/skriv String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Returnerar eller anger presentationsrevisionsnumret. Läs/skriv Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Indikerar visningsläget för dokumentets miniatyrbild. Sätt detta element till **true** för att möjliggöra skalning av miniatyrbilden till displayen. Sätt detta element till **false** för att möjliggöra beskärning av miniatyrbilden så att endast sektioner som passar displayen visas. Läs/skriv Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Avgör om presentationen är delad mellan flera personer. Läs/skriv Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Anger det totala antalet bilder i ett presentationsdokument. Endast läsning Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Returnerar eller anger ämnet för en presentation. Läs/skriv String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Returnerar eller anger titeln för en presentation. Läs/skriv String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Anger titeln för varje dokumentdel. Dessa delar är inte dokumentdelar utan konceptuella representationer av dokumentsektioner. Endast läsning string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Total redigeringstid för en presentation. Läs/skriv TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Anger det totala antalet ord som finns i ett dokument. Endast läsning Int32. |

## Metoder

| Name | Description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Rensar och sätter standardvärden för alla inbyggda egenskaper. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Tar bort alla anpassade egenskaper. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Kontrollerar om en anpassad egenskap med ett specificerat namn finns. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Returnerar ett anpassat egenskapsnamn på det specificerade indexet. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Hämtar ett namngivet booleskt värde från de anpassade egenskaperna. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Hämtar ett namngivet DateTime-värde från de anpassade egenskaperna. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Hämtar ett namngivet double-värde från de anpassade egenskaperna. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Hämtar ett namngivet float-värde från de anpassade egenskaperna. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Hämtar ett namngivet heltalsvärde från de anpassade egenskaperna. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Hämtar ett namngivet strängvärde från de anpassade egenskaperna. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Hämtar en array av sensitivitetsetiketter från de anpassade dokumentegenskaperna (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Tar bort en anpassad egenskap som är associerad med ett specificerat namn. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Sätter en namngiven boolesk anpassad egenskap. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Sätter en namngiven DateTime-anpassad egenskap. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Sätter en namngiven double-anpassad egenskap. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Sätter en namngiven float-anpassad egenskap. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Sätter en namngiven heltals-anpassad egenskap. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Sätter en namngiven sträng-anpassad egenskap. |

### Se även

* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->