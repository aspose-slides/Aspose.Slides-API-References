---
title: Hyperlink
second_title: Aspose.Sildes pro .NET – reference API
description: Zastupuje hypertextový odkaz.
type: docs
weight: 5120
url: /cs/aspose.slides/hyperlink/
---
## Třída Hyperlink

Zastupuje hypertextový odkaz.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Vytvoří instanci hypertextového odkazu, který ukazuje na konkrétní snímek. Poznámka: vytvořený hypertextový odkaz by měl být přiřazen k nějakému objektu ze stejné prezentace, jinak bude odkaz uložen jako NoAction. |
| [Hyperlink](hyperlink#constructor_2)(string) | Vytvoří instanci hypertextového odkazu. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Vytvoří instanci hypertextového odkazu pomocí jiného hypertextového odkazu jako zdroje, přepisujíc sekundární vlastnosti. |

## Vlastnosti

| Název | Popis |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Vrací hypertextový odkaz, který ukončuje prezentaci. Pouze pro čtení [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Vrací hypertextový odkaz na první snímek prezentace. Pouze pro čtení [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Vrací hypertextový odkaz na poslední snímek prezentace. Pouze pro čtení [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Vrací hypertextový odkaz na naposledy zobrazený snímek. Pouze pro čtení [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Vrací speciální hypertextový odkaz "play mediafile". Používá se v AudioFrame a VideoFrame. Pouze pro čtení [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Vrací hypertextový odkaz na další snímek. Pouze pro čtení [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Vrací speciální hypertextový odkaz "do nothing". Pouze pro čtení [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Vrací hypertextový odkaz na předchozí snímek. Pouze pro čtení [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Vrací typ akce Hyperlinku. Pouze pro čtení [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umožňuje získat základní rozhraní IPresentationComponent. Pouze pro čtení [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | Zastupuje zdroj barvy hypertextového odkazu – buď styly, nebo formát části. Čtení/zápis [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Specifikuje externí URL. Pouze pro čtení String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Zastupuje hypertextový odkaz nastavený pro tuto část bez ohledu na skutečný obsah části. PowerPoint se chová specificky pro odkazy a jejich odpovídající text v části. Umožňuje vytvořit text pro hypertextový odkaz ve formě platné URL, odlišné od skutečné adresy odkazu. V takovém případě, když si odkaz zobrazíte v editačním okně, bude změněn tak, aby odpovídal textové části. Tato vlastnost představuje původní hodnotu hypertextového odkazu. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Určuje, zda má být hypertextový odkaz při kliknutí zvýrazněn. Čtení/zápis Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Určuje, zda cíl nadřazeného hypertextového odkazu má být při vyvolání přidán do seznamu zobrazených hypertextových odkazů. Čtení/zápis Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | Zastupuje přehrávaný zvuk hypertextového odkazu. Čtení/zápis [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Určuje, zda má být zvuk při kliknutí na hypertextový odkaz zastaven. Čtení/zápis Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Vrací rámec v nadřazeném HTML framesetu pro cíl nadřazeného hypertextového odkazu, pokud existuje. Čtení/zápis String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Pokud Hyperlink cílí na konkrétní snímek, vrací tento snímek. Pouze pro čtení [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Vrací řetězec, který může být zobrazen v uživatelském rozhraní jako spojený s nadřazeným hypertextovým odkazem. Čtení/zápis String. |

## Metody

| Název | Popis |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Určuje, zda jsou dvě instance Hyperlinku rovny. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Určuje, zda jsou dvě instance Hyperlinku rovny. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Slouží jako hashovací funkce pro konkrétní typ, vhodná pro použití v hashovacích algoritmech a datových strukturách jako je hashovací tabulka. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Testuje dva hypertextové odkazy na rovnost. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Testuje dva hypertextové odkazy na nerovnost. |

### Viz také

* třída [PVIObject](../pviobject)
* rozhraní [IHyperlink](../ihyperlink)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->