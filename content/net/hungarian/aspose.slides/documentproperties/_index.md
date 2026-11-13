---
title: DocumentProperties
second_title: Aspose.Sildes .NET API Referencia
description: A prezentáció tulajdonságait képviseli.
type: docs
weight: 2810
url: /hu/aspose.slides/documentproperties/
---
## DocumentProperties osztály

Represents properties of a presentation.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [DocumentProperties](documentproperties)() | Új [`DocumentProperties`](../documentproperties) példányt inicializál. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Visszaadja vagy beállítja egy alkalmazás sablonját. Olvasás/írás String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Visszaadja az alkalmazás verzióját. Csak olvasható String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Visszaadja vagy beállítja a bemutató szerzőjét. Olvasás/írás String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Visszaadja vagy beállítja a bemutató kategóriáját. Olvasás/írás String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Visszaadja vagy beállítja a bemutató megjegyzéseit. Olvasás/írás String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Visszaadja vagy beállítja a vállalat tulajdonságát. Olvasás/írás String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Visszaadja vagy beállítja a bemutató tartalom állapotát. Olvasás/írás String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Visszaadja vagy beállítja a bemutató tartalom típusát. Olvasás/írás String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Visszaadja a gyűjteményben ténylegesen szereplő egyéni tulajdonságok számát. Csak olvasható Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Visszaadja a bemutató létrehozásának dátumát. Az értékek UTC-ben vannak. Olvasás/írás DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Jelzi a dokumentumrészek csoportosítását és az egyes csoportokban lévő részek számát. Csak olvasható IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Visszaadja a bemutató dokumentumban rejtett diák számát. Csak olvasható Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Visszaadja vagy beállítja a HyperlinkBase dokumentumtulajdonságot. Olvasás/írás String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Megadja, hogy a részben egy vagy több hiperhivatkozás kizárólag ebben a részben lett frissítve egy gyártó által. A következő gyártó, aki megnyitja a dokumentumot, frissíti a hiperhivatkozáskapcsolatokat az ebben a részben megadott új hiperhivatkozásokkal. Olvasás/írás Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Visszaadja vagy beállítja a megadott névhez tartozó egyéni tulajdonságot. Olvasás/írás Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Visszaadja vagy beállítja a bemutató kulcsszavait. Olvasás/írás String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Visszaadja a bemutató legutóbbi nyomtatásának dátumát. Olvasás/írás DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Visszaadja vagy beállítja a bemutatót legutóbb módosító személy nevét. Olvasás/írás String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Visszaadja a bemutató legutóbbi módosításának dátumát. Az értékek UTC-ben vannak. Csak olvasható a Presentation.DocumentProperties esetén (mivel a mentési folyamat során belsőleg frissül). A [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) metódus által visszaadott DocumentProperties példányon keresztül módosítható. Lásd a példát a [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) metódus összegzésében. |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Jelzi, hogy a dokumentum hiperhivatkozásai naprakészek-e. Állítsa ezt az elemet **true**-ra, ha a hiperhivatkozások frissítve vannak. Állítsa ezt az elemet **false**-ra, ha a hiperhivatkozások elavultak. Olvasás/írás Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Visszaadja vagy beállítja a manager tulajdonságot. Olvasás/írás String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Visszaadja a dokumentumban található hang- vagy videoszekvenciák teljes számát. Csak olvasható Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Visszaadja vagy beállítja az alkalmazás nevét. Olvasás/írás String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Visszaadja a bemutató megjegyzésekkel ellátott diáinak számát. Csak olvasható Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Visszaadja a dokumentumban talált bekezdések teljes számát, ha alkalmazható. Csak olvasható Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Visszaadja vagy beállítja a bemutató tervezett formátumát. Olvasás/írás String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Visszaadja vagy beállítja a bemutató revíziószámát. Olvasás/írás Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Jelzi a dokumentum miniatűr megjelenítési módját. Állítsa ezt az elemet **true**-ra a miniatűr skálázásának engedélyezéséhez a kijelzőn. Állítsa ezt az elemet **false**-ra a miniatűr vágásának engedélyezéséhez, hogy csak a kijelzőnek megfelelő részek jelenjenek meg. Olvasás/írás Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Meghatározza, hogy a bemutató több személy között meg legyen osztva. Olvasás/írás Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Visszaadja a bemutató dokumentum diáinak teljes számát. Csak olvasható Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Visszaadja vagy beállítja a bemutató tárgyát. Olvasás/írás String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Visszaadja vagy beállítja a bemutató címét. Olvasás/írás String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Megadja az egyes dokumentumrészek címét. Ezek a részek nem dokumentumrészek, hanem a dokumentumszakaszok koncepció szerinti ábrázolásai. Csak olvasható string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | A bemutató teljes szerkesztési ideje. Olvasás/írás TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Visszaadja a dokumentumban található szavak teljes számát. Csak olvasható Int32. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Törli és alapértelmezett értékeket állít be az összes beépített tulajdonságnál. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Eltávolítja az összes egyéni tulajdonságot. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Klónozza a jelenlegi objektumot |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Klónozza a jelenlegi objektumot |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Ellenőrzi egy megadott névvel rendelkező egyéni tulajdonság jelenlétét. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Visszaad egy egyéni tulajdonság nevét a megadott indexen. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Lekéri a megnevezett logikai értéket az egyéni tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Lekéri a megnevezett DateTime értéket az egyéni tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Lekéri a megnevezett double értéket az egyéni tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Lekéri a megnevezett float értéket az egyéni tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Lekéri a megnevezett egész szám értékét az egyéni tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Lekéri a megnevezett string értékét az egyéni tulajdonságokból. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | Lekéri a szenzitivitási címkék tömbjét az egyéni dokumentumtulajdonságokból (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Eltávolít egy megadott névhez tartozó egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Beállít egy megnevezett logikai egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Beállít egy megnevezett DateTime egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Beállít egy megnevezett double egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Beállít egy megnevezett float egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Beállít egy megnevezett egész szám egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Beállít egy megnevezett string egyéni tulajdonságot. |

### Példák

A következő példa bemutatja, hogyan lehet elérni a PowerPoint Presentation beépített tulajdonságait.

```csharp
[C#]
// Létrehozza a Presentation osztályt, amely a bemutatót képviseli
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Létrehoz egy hivatkozást a Presentationhez társított IDocumentProperties objektumra
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Kiírja a beépített tulajdonságokat
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

A következő példa bemutatja, hogyan lehet módosítani a PowerPoint Presentation beépített tulajdonságait.

```csharp
[C#]
// Létrehozza a Presentation osztályt, amely a Presentation-t képviseli
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Létrehoz egy hivatkozást a Presentation-hez társított IDocumentProperties objektumra
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// Beállítja a beépített tulajdonságokat
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// Mentse el a prezentációt egy fájlba
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### Lásd még

* interfész [IDocumentProperties](../idocumentproperties)
* interfész [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->