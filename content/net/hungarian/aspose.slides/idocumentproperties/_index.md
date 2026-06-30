---
title: IDocumentProperties
second_title: Aspose.Sildes .NET API Referencia
description: A prezentáció tulajdonságait képviseli.
type: docs
weight: 5690
url: /hu/aspose.slides/idocumentproperties/
---
## IDocumentProperties interfész

A prezentáció tulajdonságait képviseli.

```csharp
public interface IDocumentProperties
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Visszaadja vagy beállítja egy alkalmazás sablonját. Olvasás/írás String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Visszaadja az alkalmazás verzióját. Csak olvasható String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Visszaadja vagy beállítja a prezentáció szerzőjét. Olvasás/írás String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Visszaadja vagy beállítja a prezentáció kategóriáját. Olvasás/írás String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Visszaadja vagy beállítja a prezentáció megjegyzéseit. Olvasás/írás String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Visszaadja vagy beállítja a cég tulajdonságát. Olvasás/írás String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Visszaadja vagy beállítja a prezentáció tartalom állapotát. Olvasás/írás String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Visszaadja vagy beállítja a prezentáció tartalom típusát. Olvasás/írás String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Visszaadja egy gyűjteményben ténylegesen található egyéni tulajdonságok számát. Csak olvasható Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Visszaadja a prezentáció létrehozásának dátumát. Az értékek UTC-ben vannak. Olvasás/írás DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Jelzi a dokumentum részek csoportosítását és az egyes csoportokban lévő részek számát. Csak olvasható IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Megadja a rejtett diák számát egy prezentációs dokumentumban. Csak olvasható Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Visszaadja vagy beállítja a HyperlinkBase dokumentum tulajdonságát. Olvasás/írás String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Megadja, hogy a részben egy vagy több hivatkozás kizárólag ebben a részben lett frissítve egy előállító által. A következő előállító, aki megnyitja a dokumentumot, frissíti a hivatkozási kapcsolatokat az ebben a részben megadott új hivatkozásokkal. Olvasás/írás Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Visszaadja vagy beállítja a megadott névhez kapcsolódó egyéni tulajdonságot. Olvasás/írás Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Visszaadja vagy beállítja a prezentáció kulcsszavait. Olvasás/írás String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Visszaadja, hogy a prezentációt legutóbb mikor nyomtatták. Olvasás/írás DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Visszaadja vagy beállítja a prezentációt legutóbb módosító személy nevét. Olvasás/írás String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Visszaadja a prezentáció legutóbbi módosításának dátumát. Az értékek UTC-ben vannak. Csak olvasható a Presentation.DocumentProperties esetén (mert a mentési folyamat során belsőleg frissül). Módosítható a [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) metódus által visszaadott DocumentProperties példányon keresztül. Lásd a példát a [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) metódus összegzésében. |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Jelzi, hogy a dokumentum hivatkozásai naprakészek-e. Állítsa ezt az elemet **true**-ra, ha a hivatkozások frissítve vannak. Állítsa **false**-ra, ha a hivatkozások elavultak. Olvasás/írás Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Visszaadja vagy beállítja a manager tulajdonságot. Olvasás/írás String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Megadja a dokumentumban található hang- vagy videoszámok összes számát. Csak olvasható Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Visszaadja vagy beállítja az alkalmazás nevét. Olvasás/írás String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Megadja a jegyzetekkel rendelkező diák számát egy prezentációban. Csak olvasható Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Megadja a dokumentumban megtalálható bekezdések teljes számát, ha alkalmazható. Csak olvasható Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Visszaadja vagy beállítja a prezentáció kívánt formátumát. Olvasás/írás String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Visszaadja vagy beállítja a prezentáció revíziószámát. Olvasás/írás Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Jelzi a dokumentum bélyegkép megjelenítési módját. Állítsa ezt az elemet **true**-ra a bélyegkép skálázásának engedélyezéséhez a kijelzőhöz. Állítsa **false**-ra a bélyegkép vágásának engedélyezéséhez, hogy csak a kijelzőhöz illeszkedő részek jelenjenek meg. Olvasás/írás Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Meghatározza, hogy a prezentáció több személy között meg van-e osztva. Olvasás/írás Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Megadja a prezentáció dokumentumban lévő diák teljes számát. Csak olvasható Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Visszaadja vagy beállítja a prezentáció tárgyát. Olvasás/írás String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Visszaadja vagy beállítja a prezentáció címét. Olvasás/írás String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Megadja minden dokumentumrész címét. Ezek a részek nem dokumentumrészek, hanem a dokumentum szakaszainak koncepcionális ábrázolásai. Csak olvasható string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | A prezentáció teljes szerkesztési ideje. Olvasás/írás TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Megadja a dokumentumban található szavak teljes számát. Csak olvasható Int32. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Törli és alapértelmezett értékekre állítja az összes beépített tulajdonságot. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Eltávolítja az összes egyéni tulajdonságot. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Ellenőrzi egy megadott névvel rendelkező egyéni tulajdonság meglétét. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Visszaad egy egyéni tulajdonság nevét a megadott indexen. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Lekéri egy elnevezett boolean értéket az egyéni tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Lekéri egy elnevezett DateTime értéket az egyéni tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Lekéri egy elnevezett double értéket az egyéni tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Lekéri egy elnevezett float értéket az egyéni tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Lekéri egy elnevezett integer értéket az egyéni tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Lekéri egy elnevezett string értéket az egyéni tulajdonságokból. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Lekéri az egyéni dokumentumtulajdonságokból a szenzitivitási címkék tömbjét (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Eltávolít egy megadott névhez kapcsolódó egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Beállít egy elnevezett boolean egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Beállít egy elnevezett DateTime egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Beállít egy elnevezett double egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Beállít egy elnevezett float egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Beállít egy elnevezett integer egyéni tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Beállít egy elnevezett string egyéni tulajdonságot. |

### Lásd még

* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->