---
title: DocumentProperties
second_title: Aspose.Sildes pro .NET API referenci
description: Reprezentuje vlastnosti prezentace.
type: docs
weight: 2770
url: /cs/aspose.slides/documentproperties/
---
## DocumentProperties třída

Reprezentuje vlastnosti prezentace.

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
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Vrací nebo nastavuje šablonu aplikace. Read/write String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Vrací verzi aplikace. Read-only String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Vrací nebo nastavuje autora prezentace. Read/write String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Vrací nebo nastavuje kategorii prezentace. Read/write String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Vrací nebo nastavuje komentáře prezentace. Read/write String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Vrací nebo nastavuje vlastnost společnosti. Read/write String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Vrací nebo nastavuje stav obsahu prezentace. Read/write String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Vrací nebo nastavuje typ obsahu prezentace. Read/write String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Vrací počet vlastních vlastností aktuálně obsažených ve sbírce. Read-only Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Vrací datum, kdy byla prezentace vytvořena. Hodnoty jsou v UTC. Read/write DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Udává seskupení částí dokumentu a počet částí v každé skupině. Read-only IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Vrací počet skrytých snímků v dokumentu prezentace. Read-only Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Vrací nebo nastavuje dokumentovou vlastnost HyperlinkBase. Read/write String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Určuje, že jeden nebo více hyperodkazů v této části byly aktualizovány výhradně v této části producentem. Další producent, který otevře tento dokument, má aktualizovat vztahy hyperodkazů s novými hyperodkazy určenými v této části. Read/write Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Vrací nebo nastavuje vlastní vlastnost přiřazenou ke konkrétnímu názvu. Read/write Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Vrací nebo nastavuje klíčová slova prezentace. Read/write String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Vrací datum, kdy byla prezentace naposledy vytištěna. Read/write DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Vrací nebo nastavuje jméno poslední osoby, která upravila prezentaci. Read/write String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Vrací datum, kdy byla prezentace naposledy upravena. Hodnoty jsou v UTC. Read-only v případě Presentation.DocumentProperties (protože bude aktualizováno interně během procesu ukládání objektu IPresentation). Lze změnit pomocí instance DocumentProperties vrácené metodou [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Viz příklad v souhrnu metody [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Udává, zda jsou hyperodkazy v dokumentu aktuální. Nastavte tuto položku na **true**, aby označila, že hyperodkazy jsou aktualizovány. Nastavte tuto položku na **false**, aby označila, že hyperodkazy jsou zastaralé. Read/write Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Vrací nebo nastavuje vlastnost manažera. Read/write String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Vrací celkový počet zvukových nebo videozáznamů, které jsou v dokumentu. Read-only Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Vrací nebo nastavuje název aplikace. Read/write String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Vrací počet snímků v prezentaci obsahujících poznámky. Read-only Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Vrací celkový počet odstavců nalezených v dokumentu, pokud je to relevantní. Read-only Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Vrací nebo nastavuje zamýšlený formát prezentace. Read/write String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Vrací nebo nastavuje číslo revize prezentace. Read/write Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Udává režim zobrazení miniatury dokumentu. Nastavte tuto položku na **true**, aby se povolilo škálování miniatury dokumentu na displej. Nastavte tuto položku na **false**, aby se povolilo ořezání miniatury dokumentu tak, aby se zobrazovaly jen části, které se vejdou na displej. Read/write Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Určuje, zda je prezentace sdílená mezi několika lidmi. Read/write Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Vrací celkový počet snímků v dokumentu prezentace. Read-only Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Vrací nebo nastavuje předmět prezentace. Read/write String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Vrací nebo nastavuje název prezentace. Read/write String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Určuje název každé části dokumentu. Tyto části nejsou částmi dokumentu, ale koncepčními reprezentacemi sekcí dokumentu. Read-only string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Celkový čas úprav prezentace. Read/write TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Vrací celkový počet slov obsažených v dokumentu. Read-only Int32. |

## Metody

| Název | Popis |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Vymaže a nastaví výchozí hodnoty pro všechny vestavěné vlastnosti. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Odstraní všechny vlastní vlastnosti. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Klonuje aktuální objekt |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Klonuje aktuální objekt |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Zkontroluje přítomnost vlastní vlastnosti se zadaným názvem. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Vrátí název vlastní vlastnosti na určeném indexu. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Získá pojmenovanou hodnotu typu boolean z vlastních vlastností. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Získá pojmenovanou hodnotu typu DateTime z vlastních vlastností. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Získá pojmenovanou hodnotu typu double z vlastních vlastností. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Získá pojmenovanou hodnotu typu float z vlastních vlastností. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Získá pojmenovanou celočíselnou hodnotu z vlastních vlastností. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Získá pojmenovanou řetězcovou hodnotu z vlastních vlastností. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | Získá pole štítků citlivosti ze vlastních vlastností dokumentu (Metadata Microsoft Information Protection SDK). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Odstraní vlastní vlastnost spojenou se zadaným názvem. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Nastaví pojmenovanou boolean vlastní vlastnost. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Nastaví pojmenovanou DateTime vlastní vlastnost. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Nastaví pojmenovanou double vlastní vlastnost. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Nastaví pojmenovanou float vlastní vlastnost. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Nastaví pojmenovanou celočíselnou vlastní vlastnost. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Nastaví pojmenovanou řetězcovou vlastní vlastnost. |

### Příklady

Následující příklad ukazuje, jak získat přístup k vestavěným vlastnostem prezentace PowerPoint.

```csharp
[C#]
// Vytvořte instanci třídy Presentation, která představuje prezentaci
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Vytvořte referenci na objekt IDocumentProperties spojený s Presentation
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Zobrazte vestavěné vlastnosti
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

Následující příklad ukazuje, jak upravit vestavěné vlastnosti prezentace PowerPoint.

```csharp
[C#]
// Vytvořte instanci třídy Presentation, která představuje prezentaci
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Vytvořte referenci na objekt IDocumentProperties spojený s Presentation
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
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->