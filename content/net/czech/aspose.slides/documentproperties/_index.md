---
title: DocumentProperties
second_title: Aspose.Sildes pro .NET – referenční příručka API
description: Reprezentuje vlastnosti prezentace.
type: docs
weight: 2790
url: /cs/aspose.slides/documentproperties/
---
## DocumentProperties třída

Represents properties of a presentation.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [DocumentProperties](documentproperties)() | Inicializuje novou instanci třídy [`DocumentProperties`](../documentproperties). |

## Vlastnosti

| Název | Popis |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Vrací nebo nastavuje šablonu aplikace. Číst/Zapisovat String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Vrací verzi aplikace. Pouze pro čtení String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Vrací nebo nastavuje autora prezentace. Číst/Zapisovat String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Vrací nebo nastavuje kategorii prezentace. Číst/Zapisovat String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Vrací nebo nastavuje komentáře prezentace. Číst/Zapisovat String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Vrací nebo nastavuje vlastnost společnosti. Číst/Zapisovat String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Vrací nebo nastavuje stav obsahu prezentace. Číst/Zapisovat String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Vrací nebo nastavuje typ obsahu prezentace. Číst/Zapisovat String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Vrací počet vlastních vlastností skutečně obsažených ve sbírce. Pouze pro čtení Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Vrací datum vytvoření prezentace. Hodnoty jsou v UTC. Číst/Zapisovat DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Indikuje seskupení částí dokumentu a počet částí v každé skupině. Pouze pro čtení IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Vrací počet skrytých snímků v dokumentu prezentace. Pouze pro čtení Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Vrací nebo nastavuje dokumentovou vlastnost HyperlinkBase. Číst/Zapisovat String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Určuje, že jeden nebo více hypertextových odkazů v této části byly aktualizovány výhradně v této části výrobcem. Další výrobce, který otevře tento dokument, aktualizuje vztahy hypertextových odkazů novými odkazy uvedenými v této části. Číst/Zapisovat Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Vrací nebo nastavuje vlastní vlastnost spojenou s určeným názvem. Číst/Zapisovat Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Vrací nebo nastavuje klíčová slova prezentace. Číst/Zapisovat String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Vrací datum, kdy byla prezentace naposledy vytištěna. Číst/Zapisovat DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Vrací nebo nastavuje jméno poslední osoby, která upravila prezentaci. Číst/Zapisovat String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Vrací datum poslední úpravy prezentace. Hodnoty jsou v UTC. Pouze pro čtení v případě Presentation.DocumentProperties (protože bude aktualizováno interně během ukládání objektu IPresentation). Lze změnit pomocí instance DocumentProperties vrácené metodou [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Podívejte se na příklad v souhrnu metody [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Indikuje, zda jsou hypertextové odkazy v dokumentu aktuální. Nastavte tento prvek na **true**, aby odkazoval, že odkazy jsou aktualizovány. Nastavte tento prvek na **false**, aby odkazoval, že odkazy jsou zastaralé. Číst/Zapisovat Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Vrací nebo nastavuje vlastnost manažer. Číst/Zapisovat String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Vrací celkový počet zvukových nebo video klipů, které jsou v dokumentu. Pouze pro čtení Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Vrací nebo nastavuje název aplikace. Číst/Zapisovat String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Vrací počet snímků v prezentaci obsahujících poznámky. Pouze pro čtení Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Vrací celkový počet odstavců nalezených v dokumentu, pokud je to relevantní. Pouze pro čtení Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Vrací nebo nastavuje zamýšlený formát prezentace. Číst/Zapisovat String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Vrací nebo nastavuje číslo revize prezentace. Číst/Zapisovat Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Indikuje režim zobrazení miniatury dokumentu. Nastavte tento prvek na **true**, aby se umožnilo škálování miniatury dokumentu na displej. Nastavte tento prvek na **false**, aby se povolilo ořezání miniatury dokumentu tak, aby se zobrazily pouze části, které se vejdou na displej. Číst/Zapisovat Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Určuje, zda je prezentace sdílena mezi více lidmi. Číst/Zapisovat Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Vrací celkový počet snímků v dokumentu prezentace. Pouze pro čtení Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Vrací nebo nastavuje předmět prezentace. Číst/Zapisovat String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Vrací nebo nastavuje název prezentace. Číst/Zapisovat String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Určuje název každé části dokumentu. Tyto části nejsou skutečnými částmi dokumentu, ale koncepčními reprezentacemi sekcí dokumentu. Pouze pro čtení string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Celkový čas úprav prezentace. Číst/Zapisovat TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Vrací celkový počet slov obsažených v dokumentu. Pouze pro čtení Int32. |

## Metody

| Název | Popis |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Vyčistí a nastaví výchozí hodnoty pro všechny vestavěné vlastnosti. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Odstraní všechny vlastní vlastnosti. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Klonuje aktuální objekt. |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Klonuje aktuální objekt. |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Kontroluje přítomnost vlastní vlastnosti se zadaným názvem. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Vrací název vlastní vlastnosti na zadaném indexu. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Získá pojmenovanou boolean hodnotu z vlastních vlastností. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Získá pojmenovanou DateTime hodnotu z vlastních vlastností. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Získá pojmenovanou double hodnotu z vlastních vlastností. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Získá pojmenovanou float hodnotu z vlastních vlastností. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Získá pojmenovanou integer hodnotu z vlastních vlastností. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Získá pojmenovanou string hodnotu z vlastních vlastností. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | Získá pole štítků citlivosti z vlastních vlastností dokumentu (Metadata Microsoft Information Protection SDK). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Odebere vlastní vlastnost spojenou se zadaným názvem. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Nastaví pojmenovanou boolean vlastní vlastnost. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Nastaví pojmenovanou DateTime vlastní vlastnost. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Nastaví pojmenovanou double vlastní vlastnost. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Nastaví pojmenovanou float vlastní vlastnost. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Nastaví pojmenovanou integer vlastní vlastnost. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Nastaví pojmenovanou string vlastní vlastnost. |

### Příklady

Následující příklad ukazuje, jak přistupovat k vestavěným vlastnostem PowerPoint prezentace.

```csharp
[C#]
// Vytvořte instanci třídy Presentation, která představuje prezentaci
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Vytvořte odkaz na objekt IDocumentProperties spojený s prezentací
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Zobrazte vestavěné vlastnosti
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

Následující příklad ukazuje, jak upravit vestavěné vlastnosti PowerPoint prezentace.

```csharp
[C#]
// Vytvořte instanci třídy Presentation, která představuje prezentaci
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Vytvořte odkaz na objekt IDocumentProperties spojený s prezentací
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// Nastavte vestavěné vlastnosti
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// Uložte prezentaci do souboru
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### Viz také

* rozhraní [IDocumentProperties](../idocumentproperties)
* rozhraní [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->