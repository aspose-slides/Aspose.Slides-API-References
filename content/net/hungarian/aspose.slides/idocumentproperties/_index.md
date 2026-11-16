---
title: IDocumentProperties
second_title: Aspose.Sildes .NET API referencia
description: A prezentáció tulajdonságait reprezentálja.
type: docs
weight: 5730
url: /hu/aspose.slides/idocumentproperties/
---
## IDocumentProperties interfész

Represents properties of a presentation.

```csharp
public interface IDocumentProperties
```

## Tulajdonságok

| Name | Description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Visszaadja vagy beállítja egy alkalmazás sablonját. Olvasás/írás String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Visszaadja az alkalmazás verzióját. Csak olvasás String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Visszaadja vagy beállítja egy bemutató szerzőjét. Olvasás/írás String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Visszaadja vagy beállítja egy bemutató kategóriáját. Olvasás/írás String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Visszaadja vagy beállítja egy bemutató megjegyzéseit. Olvasás/írás String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Visszaadja vagy beállítja a vállalat tulajdonságát. Olvasás/írás String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Visszaadja vagy beállítja egy bemutató tartalom állapotát. Olvasás/írás String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Visszaadja vagy beállítja egy bemutató tartalom típusát. Olvasás/írás String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Visszaadja a gyűjteményben ténylegesen szereplő egyedi tulajdonságok számát. Csak olvasás Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Visszaadja, hogy mikor hozták létre a bemutatót. Az értékek UTC-ben vannak. Olvasás/írás DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Jelzi a dokumentum részek csoportosítását és a csoportonkénti részek számát. Csak olvasás IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Megadja a rejtett diák számát egy bemutató dokumentumban. Csak olvasás Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Visszaadja vagy beállítja a HyperlinkBase dokumentum tulajdonságát. Olvasás/írás String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Megadja, hogy egy vagy több hiperhivatkozás ebben a részben kizárólag ebben a részben lett frissítve egy termelő által. A következő termelő, aki megnyitja a dokumentumot, frissíti a hiperhivatkozás kapcsolatokat az ebben a részben megadott új hiperhivatkozásokkal. Olvasás/írás Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Visszaadja vagy beállítja a megadott névhez tartozó egyedi tulajdonságot. Olvasás/írás Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Visszaadja vagy beállítja egy bemutató kulcsszavait. Olvasás/írás String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Visszaadja a dátumot, amikor a bemutatót utoljára nyomtatták. Olvasás/írás DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Visszaadja az utolsó személy nevét, aki módosította a bemutatót. Olvasás/írás String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Visszaadja a dátumot, amikor a bemutatót utoljára módosították. Az értékek UTC-ben vannak. Csak olvasás, ha a Presentation.DocumentProperties esetén (mivel a mentési folyamat során belsőleg frissül). Módosítható a [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) metódus által visszaadott DocumentProperties példányon keresztül. Lásd a példát a [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) metódus összefoglalójában. |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Jelzi, hogy a dokumentum hiperhivatkozásai naprakészek-e. Állítsa ezt az elemet **true**-ra a hiperhivatkozások frissítésének jelzéséhez. Állítsa **false**-ra a hiperhivatkozások elavulttá jelzéséhez. Olvasás/írás Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Visszaadja vagy beállítja a menedzser tulajdonságát. Olvasás/írás String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Megadja a hang vagy videó klipek teljes számát, amelyek a dokumentumban vannak. Csak olvasás Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Visszaadja vagy beállítja az alkalmazás nevét. Olvasás/írás String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Megadja a megjegyzésekkel ellátott diák számát egy bemutatóban. Csak olvasás Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Megadja a dokumentumban megtalálható bekezdések teljes számát, ha van. Csak olvasás Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Visszaadja vagy beállítja a bemutató kívánt formátumát. Olvasás/írás String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Visszaadja vagy beállítja a bemutató revízió számát. Olvasás/írás Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Jelzi a dokumentum bélyegkép megjelenítési módját. Állítsa ezt az elemet **true**-ra a bélyegkép skálázásának engedélyezéséhez a képernyőhöz. Állítsa **false**-ra a bélyegkép vágásának engedélyezéséhez, hogy csak a képernyőnek megfelelő részeket mutassa. Olvasás/írás Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Meghatározza, hogy a bemutató megosztott-e több ember között. Olvasás/írás Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Megadja a bemutató dokumentumban lévő diák teljes számát. Csak olvasás Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Visszaadja vagy beállítja a bemutató tárgyát. Olvasás/írás String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Visszaadja vagy beállítja egy bemutató címét. Olvasás/írás String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Megadja minden dokumentum rész címét. Ezek a részek nem dokumentum részek, hanem a dokumentum szakaszok koncepcionális ábrázolásai. Csak olvasás string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | A bemutató teljes szerkesztési ideje. Olvasás/írás TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Megadja a dokumentumban található szavak teljes számát. Csak olvasás Int32. |

## Metódusok

| Name | Description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Törli és alapértelmezett értékeket állít be az összes beépített tulajdonságnál. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Eltávolítja az összes egyedi tulajdonságot. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Ellenőrzi egy megadott névhez tartozó egyedi tulajdonság meglétét. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Visszaad egy egyedi tulajdonság nevét a megadott indexnél. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Lekér egy nevesített boolean értéket az egyedi tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Lekér egy nevesített DateTime értéket az egyedi tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Lekér egy nevesített double értéket az egyedi tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Lekér egy nevesített float értéket az egyedi tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Lekér egy nevesített integer értéket az egyedi tulajdonságokból. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Lekér egy nevesített string értéket az egyedi tulajdonságokból. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Lekér egy tömböt érzékenységi címkékkel az egyedi dokumentum tulajdonságokból (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Eltávolít egy megadott névhez kapcsolódó egyedi tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Beállít egy nevesített boolean egyedi tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Beállít egy nevesített DateTime egyedi tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Beállít egy nevesített double egyedi tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Beállít egy nevesített float egyedi tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Beállít egy nevesített integer egyedi tulajdonságot. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Beállít egy nevesített string egyedi tulajdonságot. |

### Lásd még

* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->