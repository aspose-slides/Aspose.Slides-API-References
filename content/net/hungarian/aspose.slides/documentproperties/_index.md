---
title: DocumentProperties
second_title: Aspose.Sildes .NET API referencia
description: A prezentáció tulajdonságait képviseli.
type: docs
weight: 2790
url: /hu/aspose.slides/documentproperties/
---
## DocumentProperties osztály

A prezentáció tulajdonságait képviseli.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [DocumentProperties](documentproperties)() | Új példányt inicializál a [`DocumentProperties`](../documentproperties) osztályból. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Visszaadja vagy beállítja egy alkalmazás sablonját. Olvasás/írás String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Visszaadja az alkalmazás verzióját. Csak olvasható String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Visszaadja vagy beállítja a prezentáció szerzőjét. Olvasás/írás String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Visszaadja vagy beállítja a prezentáció kategóriáját. Olvasás/írás String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Visszaadja vagy beállítja a prezentáció megjegyzéseit. Olvasás/írás String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Visszaadja vagy beállítja a cég tulajdonságát. Olvasás/írás String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Visszaadja vagy beállítja a prezentáció tartalom állapotát. Olvasás/írás String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Visszaadja vagy beállítja a prezentáció tartalomtípusát. Olvasás/írás String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Visszaadja a gyűjteményben ténylegesen lévő egyéni tulajdonságok számát. Csak olvasható Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Visszaadja a prezentáció létrehozásának dátumát. Az értékek UTC-ben vannak. Olvasás/írás DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Jeli a dokumentumrészek csoportosítását és az egyes csoportokban lévő részek számát. Csak olvasható IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Visszaadja a prezentáció dokumentumban lévő rejtett diák számát. Csak olvasható Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Visszaadja vagy beállítja a HyperlinkBase dokumentum tulajdonságot. Olvasás/írás String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Megadja, hogy ezt a részt egy vagy több hiperhivatkozás kizárólag ebben a részben lett frissítve egy előállító által. A következő előállító, aki megnyitja a dokumentumot, frissíti a hiperhivatkozás kapcsolatokkal a ebben a részben megadott új hiperhivatkozásokat. Olvasás/írás Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Visszaadja vagy beállítja a megadott névhez társított egyéni tulajdonságot. Olvasás/írás Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Visszaadja vagy beállítja a prezentáció kulcsszavait. Olvasás/írás String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Visszaadja a prezentáció legutóbbi nyomtatásának dátumát. Olvasás/írás DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Visszaadja vagy beállítja a prezentációt legutóbb módosító személy nevét. Olvasás/írás String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Visszaadja a prezentáció legutóbbi módosításának dátumát. Az értékek UTC-ben vannak. Csak olvasható a Presentation.DocumentProperties esetén (mivel a mentési folyamat során belsőleg frissül). Megváltoztatható a [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) metódus által visszaadott DocumentProperties példányon keresztül. Lásd a példát a [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) metódus összefoglalójában. |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Jeli, hogy a dokumentum hiperhivatkozásai naprakészek-e. Állítsa ezt az elemet **true** értékre, ha a hiperhivatkozások frissítve vannak. Állítsa **false** értékre, ha a hiperhivatkozások elavultak. Olvasás/írás Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Visszaadja vagy beállítja a manager (menedzser) tulajdonságot. Olvasás/írás String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Visszaadja a dokumentumban jelen lévő hang- vagy videoklipek teljes számát. Csak olvasható Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Visszaadja vagy beállítja az alkalmazás nevét. Olvasás/írás String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Visszaadja a megjegyzéseket tartalmazó diák számát a prezentációban. Csak olvasható Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Visszaadja a dokumentumban található bekezdések teljes számát, ha alkalmazható. Csak olvasható Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Visszaadja vagy beállítja a prezentáció kívánt formátumát. Olvasás/írás String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Visszaadja vagy beállítja a prezentáció revíziószámát. Olvasás/írás Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Jeli a dokumentum bélyegkép megjelenítési módját. Állítsa ezt az elemet **true** értékre, hogy engedélyezze a bélyegkép méretezését a képernyőhöz. Állítsa **false** értékre, hogy engedélyezze a bélyegkép levágását, hogy csak a képernyőnek megfelelő részek jelenjenek meg. Olvasás/írás Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Meghatározza, hogy a prezentáció több személy között van-e megosztva. Olvasás/írás Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Visszaadja a prezentáció dokumentumban lévő diák teljes számát. Csak olvasható Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Visszaadja vagy beállítja a prezentáció tárgyát. Olvasás/írás String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Visszaadja vagy beállítja a prezentáció címét. Olvasás/írás String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Megadja minden dokumentumrész címét. Ezek a részek nem tényleges dokumentumrészek, hanem a dokumentum szakaszainak koncepciós ábrázolásai. Csak olvasható string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | A prezentáció teljes szerkesztési ideje. Olvasás/írás TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Visszaadja a dokumentumban lévő szavak teljes számát. Csak olvasható Int32. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Törli és alapértelmezett értékeket állít be az összes beépített tulajdonságnál. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Eltávolítja az összes egyéni tulajdonságot. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Klónozza a jelenlegi objektumot |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Klónozza a jelenlegi objektumot |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Ellenőrzi egy megadott névvel rendelkező egyéni tulajdonság meglétét. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Visszaad egy egyéni tulajdonság nevét a megadott indexnél. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Lekéri egy neves boolean értéket az egyéni tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Lekéri egy neves DateTime értéket az egyéni tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Lekéri egy neves double értéket az egyéni tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Lekéri egy neves float értéket az egyéni tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Lekéri egy neves integer értéket az egyéni tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Lekéri egy neves string értéket az egyéni tulajdonságokból. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | Lekéri a szenzitivitási címkék tömbjét az egyéni dokumentumtulajdonságokból (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Eltávolít egy megadott névhez társított egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Beállít egy neves boolean egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Beállít egy neves DateTime egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Beállít egy neves double egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Beállít egy neves float egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Beállít egy neves integer egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Beállít egy neves string egyéni tulajdonságot. |

### Példák

Az alábbi példa bemutatja, hogyan lehet elérni a PowerPoint prezentáció beépített tulajdonságait.

```csharp
[C#]
// Példányosítsa a Presentation osztályt, amely a prezentációt képviseli
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Hozzon létre egy hivatkozást a Presentation-hez kapcsolódó IDocumentProperties objektumra
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Jelenítse meg a beépített tulajdonságokat
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

Az alábbi példa bemutatja, hogyan lehet módosítani a PowerPoint prezentáció beépített tulajdonságait.

```csharp
[C#]
// Példányosítsa a Presentation osztályt, amely a Presentation-t képviseli
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Hozzon létre egy hivatkozást a Presentation-hez kapcsolódó IDocumentProperties objektumra
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// Állítsa be a beépített tulajdonságokat
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// Mentse a prezentációt egy fájlba
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### Lásd még

* interfész [IDocumentProperties](../idocumentproperties)
* interfész [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* névtér [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->