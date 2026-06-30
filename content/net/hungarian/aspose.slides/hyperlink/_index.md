---
title: Hyperlink
second_title: Aspose.Slides .NET API-referencia
description: Hiperhivatkozást reprezentál.
type: docs
weight: 5100
url: /hu/aspose.slides/hyperlink/
---
## Hyperlink osztály

Hiperhivatkozást reprezentál.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Létrehoz egy hiperhivatkozás példányt, amely egy adott diára mutat. Megjegyzés: a létrehozott hiperhivatkozást ugyanazon előadás egy objektumához kell rendelni, különben a hivatkozás NoAction-ként lesz mentve. |
| [Hyperlink](hyperlink#constructor_2)(string) | Létrehoz egy hiperhivatkozás példányt. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Létrehoz egy hiperhivatkozás példányt egy másik hiperhivatkozást forrásként használva, felülírva a másodlagos tulajdonságokat. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Visszaad egy hiperhivatkozást, amely befejezi az előadást. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Visszaad egy hiperhivatkozást az előadás első diájára. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Visszaad egy hiperhivatkozást az előadás utolsó diájára. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Visszaad egy hiperhivatkozást az utoljára megtekintett diára. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Visszaad egy speciális "play mediafile" hiperhivatkozást. AudioFrame-ben és VideoFrame-ben használatos. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Visszaad egy hiperhivatkozást a következő diára. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Visszaad egy speciális "do nothing" hiperhivatkozást. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Visszaad egy hiperhivatkozást az előző diára. Csak olvasható [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Visszaad a Hyperlink műveletének típusát. Csak olvasható [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi az IPresentationComponent alapinterfész lekérését. Csak olvasható [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | A hiperhivatkozás színének forrását reprezentál – stílusok vagy szakaszformátum. Olvasás/írás [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Meghatározza a külső URL-t. Csak olvasható String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | Egy olyan hiperhivatkozást reprezentál, amely erre a szakaszra van beállítva, a szakasz tényleges tartalmától függetlenül. A PowerPoint a hivatkozásokkal és a szakaszokhoz tartozó szöveggel különböző módon jár el. Lehetővé teszi, hogy a hiperhivatkozás szövegét egy érvényes URL formájában hozzuk létre, amely eltér a hivatkozás valós címétől. Ebben az esetben, amikor a szerkesztőablakban megtekinti a hivatkozást, az a szövegszakasznak megfelelően módosul. Ez a tulajdonság a hiperhivatkozás eredeti értékét reprezentálja. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Meghatározza, hogy a hiperhivatkozást kattintáskor ki kell-e emelni. Olvasás/írás Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Meghatározza, hogy a szülő hiperhivatkozás célja hozzá legyen-e adva a megtekintett hiperhivatkozások listájához, amikor meghívják. Olvasás/írás Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | A hiperhivatkozás lejátszott hangját reprezentálja. Olvasás/írás [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Meghatározza, hogy a hangot le kell-e állítani a hiperhivatkozás kattintásakor. Olvasás/írás Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Visszaad a szülő HTML keretcsoportban a szülő hiperhivatkozás céljához tartozó keretet, ha létezik. Olvasás/írás String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Ha a Hyperlink egy adott diára mutat, visszaadja azt a diát. Csak olvasható [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Visszaad egy karakterláncot, amely a felhasználói felületen megjelenhet, és a szülő hiperhivatkozáshoz kapcsolódik. Olvasás/írás String. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Megállapítja, hogy a két Hyperlink példány egyenlő-e. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Megállapítja, hogy a két Hyperlink példány egyenlő-e. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Hash függvényként szolgál egy adott típushoz, amely alkalmas hash algoritmusok és adatstruktúrák, például hash táblázat használatához. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Két hiperhivatkozást tesztel egyenlőségre. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Két hiperhivatkozást tesztel egyenlőtlenségre. |

### Lásd még

* osztály [PVIObject](../pviobject)
* interfész [IHyperlink](../ihyperlink)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->