---
title: IDocumentProperties
second_title: Aspose.Slides .NET API referencia
description: A bemutató tulajdonságait képviseli.
type: docs
weight: 5710
url: /hu/aspose.slides/idocumentproperties/
---
## IDocumentProperties interfész

A bemutató tulajdonságait képviseli.

```csharp
public interface IDocumentProperties
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Visszaadja vagy beállítja egy alkalmazás sablonját. Olvasás/írás String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Visszaadja az alkalmazás verzióját. Csak olvasható String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Visszaadja vagy beállítja egy bemutató szerzőjét. Olvasás/írás String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Visszaadja vagy beállítja egy bemutató kategóriáját. Olvasás/írás String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Visszaadja vagy beállítja egy bemutató megjegyzéseit. Olvasás/írás String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Visszaadja vagy beállítja a cég tulajdonságát. Olvasás/írás String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Visszaadja vagy beállítja egy bemutató tartalomállapotát. Olvasás/írás String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Visszaadja vagy beállítja egy bemutató tartalom típusát. Olvasás/írás String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Visszaadja a gyűjteményben ténylegesen lévő egyéni tulajdonságok számát. Csak olvasható Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Visszaadja a bemutató létrehozásának dátumát. Az értékek UTC-ben vannak. Olvasás/írás DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Jelzi a dokumentum részek csoportosítását és egy csoportban lévő részek számát. Csak olvasható IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Meghatározza a bemutató dokumentumban rejtett diák számát. Csak olvasható Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Visszaadja vagy beállítja a HyperlinkBase dokumentumtulajdonságot. Olvasás/írás String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Meghatározza, hogy a részben egy vagy több hiperhivatkozást kizárólag egy termelő frissített ebben a részben. A következő termelő, aki megnyitja a dokumentumot, frissíti a hiperhivatkozási kapcsolatokat az ebben a részben megadott új hiperhivatkozásokkal. Olvasás/írás Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Visszaadja vagy beállítja egy megadott névhez tartozó egyéni tulajdonságot. Olvasás/írás Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Visszaadja vagy beállítja egy bemutató kulcsszavait. Olvasás/írás String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Visszaadja a bemutató legutóbbi nyomtatásának dátumát. Olvasás/írás DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Visszaadja vagy beállítja a bemutatót utoljára módosító személy nevét. Olvasás/írás String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Visszaadja a bemutató legutóbbi módosításának dátumát. Az értékek UTC-ben vannak. Csak olvasható a Presentation.DocumentProperties esetén (mert az IPresentation objektum mentési folyamata során belsőleg frissül). Módosítható a [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) metódus által visszaadott DocumentProperties példányon keresztül. Lásd a példát a [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) metódus összefoglalójában. |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Jelzi, hogy a dokumentum hiperhivatkozásai naprakészek-e. Állítsa ezt az elemet **true**-ra, ha a hiperhivatkozások frissítve vannak. Állítsa ezt az elemet **false**-ra, ha a hiperhivatkozások elavultak. Olvasás/írás Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Visszaadja vagy beállítja a menedzser tulajdonságot. Olvasás/írás String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Megadja a dokumentumban található hang- vagy videoklipek teljes számát. Csak olvasható Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Visszaadja vagy beállítja az alkalmazás nevét. Olvasás/írás String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Megadja a jegyzeteket tartalmazó diák számát a bemutatóban. Csak olvasható Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Megadja a dokumentumban található bekezdések teljes számát, ha alkalmazható. Csak olvasható Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Visszaadja vagy beállítja a bemutató tervezett formátumát. Olvasás/írás String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Visszaadja vagy beállítja a bemutató revíziószámát. Olvasás/írás Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Jelzi a dokumentum bélyegkép megjelenítési módját. Állítsa ezt az elemet **true**-ra, ha a bélyegkép skálázását szeretné engedélyezni a megjelenítőhöz. Állítsa ezt az elemet **false**-ra, ha a bélyegkép vágását szeretné engedélyezni, hogy csak a kijelzőhöz illeszkedő részeket mutassa. Olvasás/írás Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Meghatározza, hogy a bemutató több felhasználó között megosztott-e. Olvasás/írás Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Megadja a bemutató dokumentumban lévő diák teljes számát. Csak olvasható Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Visszaadja vagy beállítja a bemutató tárgyát. Olvasás/írás String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Visszaadja vagy beállítja a bemutató címét. Olvasás/írás String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Megadja minden dokumentum rész címét. Ezek a részek nem dokumentumrészek, hanem a dokumentumszakaszok koncepcionális ábrázolásai. Csak olvasható string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | A bemutató teljes szerkesztési ideje. Olvasás/írás TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Megadja a dokumentumban található szavak teljes számát. Csak olvasható Int32. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Törli és alapértelmezett értékeket állít be az összes beépített tulajdonságra. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Eltávolítja az összes egyéni tulajdonságot. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Ellenőrzi egy megadott névvel rendelkező egyéni tulajdonság létezését. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Visszaad egy egyéni tulajdonság nevét a megadott indexnél. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Lekér egy megnevezett logikai értéket az egyéni tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Lekér egy megnevezett DateTime értéket az egyéni tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Lekér egy megnevezett double értéket az egyéni tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Lekér egy megnevezett float értéket az egyéni tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Lekér egy megnevezett egész értéket az egyéni tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Lekér egy megnevezett string értéket az egyéni tulajdonságokból. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Lekér egy tömböt a szenzitivitási címkékkel az egyéni dokumentumtulajdonságokból (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Eltávolít egy megadott névhez tartozó egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Beállít egy megnevezett logikai egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Beállít egy megnevezett DateTime egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Beállít egy megnevezett double egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Beállít egy megnevezett float egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Beállít egy megnevezett egész egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Beállít egy megnevezett string egyéni tulajdonságot. |

### Lásd még

* névtér [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->