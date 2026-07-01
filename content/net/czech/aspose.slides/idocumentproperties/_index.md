---
title: IDocumentProperties
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje vlastnosti prezentace.
type: docs
weight: 5690
url: /cs/aspose.slides/idocumentproperties/
---
## IDocumentProperties rozhraní

Reprezentuje vlastnosti prezentace.

```csharp
public interface IDocumentProperties
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Vrací nebo nastavuje šablonu aplikace. Čtení/zápis String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Vrací verzi aplikace. Pouze ke čtení String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Vrací nebo nastavuje autora prezentace. Čtení/zápis String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Vrací nebo nastavuje kategorii prezentace. Čtení/zápis String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Vrací nebo nastavuje komentáře k prezentaci. Čtení/zápis String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Vrací nebo nastavuje vlastnost společnosti. Čtení/zápis String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Vrací nebo nastavuje stav obsahu prezentace. Čtení/zápis String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Vrací nebo nastavuje typ obsahu prezentace. Čtení/zápis String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Vrací počet vlastních vlastností ve skutečnosti obsažených v kolekci. Pouze ke čtení Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Vrací datum vytvoření prezentace. Hodnoty jsou v UTC. Čtení/zápis DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Indikuje seskupení částí dokumentu a počet částí v každé skupině. Pouze ke čtení IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Určuje počet skrytých snímků v dokumentu prezentace. Pouze ke čtení Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Vrací nebo nastavuje vlastnost dokumentu HyperlinkBase. Čtení/zápis String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Určuje, že jeden nebo více hypertextových odkazů v této části byly aktualizovány výhradně v této části producentem. Další producent otevřouci tento dokument aktualizuje vztahy hypertextových odkazů s novými odkazy uvedenými v této části. Čtení/zápis Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Vrací nebo nastavuje vlastní vlastnost spojenou se zadaným názvem. Čtení/zápis Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Vrací nebo nastavuje klíčová slova prezentace. Čtení/zápis String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Vrací datum posledního tisku prezentace. Čtení/zápis DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Vrací nebo nastavuje jméno poslední osoby, která upravila prezentaci. Čtení/zápis String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Vrací datum poslední úpravy prezentace. Hodnoty jsou v UTC. Pouze ke čtení v případě Presentation.DocumentProperties (protože bude aktualizováno interně během procesu ukládání objektu IPresentation). Lze změnit pomocí instance DocumentProperties vrácené metodou [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Viz příklad v souhrnu metody [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Indikuje, zda jsou hypertextové odkazy v dokumentu aktuální. Nastavte tento prvek na **true**, aby označil, že odkazy jsou aktualizovány. Nastavte tento prvek na **false**, aby označil, že odkazy jsou zastaralé. Čtení/zápis Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Vrací nebo nastavuje vlastnost manager. Čtení/zápis String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Určuje celkový počet zvukových nebo video klipů v dokumentu. Pouze ke čtení Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Vrací nebo nastavuje název aplikace. Čtení/zápis String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Určuje počet snímků v prezentaci obsahujících poznámky. Pouze ke čtení Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Určuje celkový počet odstavců nalezených v dokumentu, pokud jsou k dispozici. Pouze ke čtení Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Vrací nebo nastavuje zamýšlený formát prezentace. Čtení/zápis String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Vrací nebo nastavuje číslo revize prezentace. Čtení/zápis Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Indikuje režim zobrazení miniatury dokumentu. Nastavte tento prvek na **true**, aby se povolilo škálování miniatury dokumentu na displej. Nastavte tento prvek na **false**, aby se povolilo oříznutí miniatury dokumentu tak, aby zobrazovala pouze části, které se vejde na displej. Čtení/zápis Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Určuje, zda je prezentace sdílena mezi více lidmi. Čtení/zápis Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Určuje celkový počet snímků v dokumentu prezentace. Pouze ke čtení Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Vrací nebo nastavuje předmět prezentace. Čtení/zápis String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Vrací nebo nastavuje název prezentace. Čtení/zápis String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Určuje název každé části dokumentu. Tyto části nejsou skutečnými částmi dokumentu, ale konceptuálními reprezentacemi sekcí dokumentu. Pouze ke čtení string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Celkový čas úprav prezentace. Čtení/zápis TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Určuje celkový počet slov v dokumentu. Pouze ke čtení Int32. |

## Metody

| Název | Popis |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Vyčistí a nastaví výchozí hodnoty pro všechny vestavěné vlastnosti. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Odstraní všechny vlastní vlastnosti. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Zkontroluje přítomnost vlastní vlastnosti se zadaným názvem. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Vrátí název vlastní vlastnosti na určeném indexu. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Získá pojmenovanou boolean hodnotu z vlastních vlastností. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Získá pojmenovanou DateTime hodnotu z vlastních vlastností. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Získá pojmenovanou double hodnotu z vlastních vlastností. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Získá pojmenovanou float hodnotu z vlastních vlastností. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Získá pojmenovanou integer hodnotu z vlastních vlastností. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Získá pojmenovanou string hodnotu z vlastních vlastností. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Získá pole štítků citlivosti z vlastních vlastností dokumentu (Microsoft Information Protection SDK Metadata). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Odstraní vlastní vlastnost spojenou se zadaným názvem. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Nastaví pojmenovanou boolean vlastní vlastnost. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Nastaví pojmenovanou DateTime vlastní vlastnost. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Nastaví pojmenovanou double vlastní vlastnost. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Nastaví pojmenovanou float vlastní vlastnost. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Nastaví pojmenovanou integer vlastní vlastnost. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Nastaví pojmenovanou string vlastní vlastnost. |

### Viz také

* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->