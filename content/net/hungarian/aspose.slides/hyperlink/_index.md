---
title: Hyperlink
second_title: Aspose.Sildes .NET API hivatkozás
description: Egy hiperhivatkozást képvisel.
type: docs
weight: 5120
url: /hu/aspose.slides/hyperlink/
---
## Hyperlink osztály

Egy hiperhivatkozást képvisel.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Létrehoz egy hiperhivatkozás példányt, amely egy adott diára mutat. Megjegyzés: a létrehozott hiperhivatkozást egy ugyanabból a bemutatóból származó objektumhoz kell rendelni, ellenkező esetben a link NoAction-ként lesz mentve. |
| [Hyperlink](hyperlink#constructor_2)(string) | Létrehoz egy hiperhivatkozás példányt. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Létrehoz egy hiperhivatkozás példányt egy másik hiperhivatkozást forrásként használva, felülírva a másodlagos tulajdonságokat. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Visszaad egy hiperhivatkozást, amely befejezi a bemutatót. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Visszaad egy hiperhivatkozást a bemutató első diajára. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Visszaad egy hiperhivatkozást a bemutató utolsó diajára. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Visszaad egy hiperhivatkozást az utoljára megtekintett diára. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Visszaad egy speciális „mediafájl lejátszása” hiperhivatkozást. Az AudioFrame és a VideoFrame esetében használják. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Visszaad egy hiperhivatkozást a következő diára. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Visszaad egy speciális „ne tegyen semmit” hiperhivatkozást. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Visszaad egy hiperhivatkozást az előző diára. Csak olvasható [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Visszaad a Hyperlink műveletének típusát. Csak olvasható [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi az alap IPresentationComponent interfész lekérését. Csak olvasható [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | A hiperhivatkozás szín forrását képviseli – legyen az stílus vagy részformátum. Olvasható/írható [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Meghatározza a külső URL-t. Csak olvasható String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Egy hiperhivatkozást képvisel, amelyet ennek a résznek állítottak be, függetlenül a rész tényleges tartalmától. A PowerPoint speciálisan kezeli a hivatkozásokat és a hozzájuk tartozó szöveget egy részben. Lehetővé teszi, hogy a hiperhivatkozáshoz szöveget hozzunk létre egy érvényes URL formájában, amely különbözik a link valódi címétől. Ebben az esetben, amikor a szerkesztőablakban megtekinted a linket, az a szövegrésznek megfelelően módosul. Ez a tulajdonság a hiperhivatkozás eredeti értékét tartalmazza. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Meghatározza, hogy a hiperhivatkozást kattintáskor ki kell-e emelni. Olvasható/írható Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Meghatározza, hogy a szülő hiperhivatkozás célpontja hozzá legyen-e adva a megtekintett hiperhivatkozások listájához, amikor meghívásra kerül. Olvasható/írható Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | A hiperhivatkozás lejátszott hangját képviseli. Olvasható/írható [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Meghatározza, hogy a hang le legyen-e állítva a hiperhivatkozásra kattintáskor. Olvasható/írható Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Visszaad a szülő HTML-keretcsoporton belüli keretet, amely a szülő hiperhivatkozás célpontja, ha létezik. Olvasható/írható String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Ha a Hyperlink egy adott diára mutat, visszaadja azt a diát. Csak olvasható [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Visszaadja a karakterláncot, amely a felhasználói felületen a szülő hiperhivatkozáshoz kapcsolódóan megjelenhet. Olvasható/írható String. |

## Metódusok

| Név | Leírás |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Megállapítja, hogy a két Hyperlink példány egyenlő-e. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Megállapítja, hogy a két Hyperlink példány egyenlő-e. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Hash függvényként szolgál egy adott típushoz, alkalmas hasítóalgoritmusokban és adatszerkezetekben, például hash táblában való használatra. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Két hiperhivatkozást tesztel az egyenlőség szempontjából. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Két hiperhivatkozást tesztel a különbözőség szempontjából. |

### Lásd még

* osztály [PVIObject](../pviobject)
* interfész [IHyperlink](../ihyperlink)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->