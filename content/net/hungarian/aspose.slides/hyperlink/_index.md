---
title: Hyperlink
second_title: Aspose.Sildes .NET API hivatkozás
description: Egy hiperlinket reprezentál.
type: docs
weight: 5140
url: /hu/aspose.slides/hyperlink/
---
## Hyperlink osztály

Egy hiperlinket reprezentál.

```csharp
public sealed class Hyperlink : PVIObject, IHyperlink
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [Hyperlink](hyperlink#constructor_1)(ISlide) | Létrehoz egy hiperlink példányt, amely egy adott diára mutat. Megjegyzés: a létrehozott hiperlinket egy ugyanabból a bemutatóból származó objektumhoz kell rendelni, különben a hivatkozás NoActionként lesz mentve. |
| [Hyperlink](hyperlink#constructor_2)(string) | Létrehoz egy hiperlink példányt. |
| [Hyperlink](hyperlink#constructor)(Hyperlink, string, string, bool, bool, bool) | Létrehoz egy hiperlink példányt egy másik hiperlinkből kiindulva, felülírva a másodlagos tulajdonságokat. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| static [EndShow](../../aspose.slides/hyperlink/endshow) { get; } | Visszaad egy hiperlinket, amely befejezi a bemutatót. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [FirstSlide](../../aspose.slides/hyperlink/firstslide) { get; } | Visszaad egy hiperlinket a bemutató első diájához. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [LastSlide](../../aspose.slides/hyperlink/lastslide) { get; } | Visszaad egy hiperlinket a bemutató utolsó diájához. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [LastVievedSlide](../../aspose.slides/hyperlink/lastvievedslide) { get; } | Visszaad egy hiperlinket az utoljára megtekintett diához. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [Media](../../aspose.slides/hyperlink/media) { get; } | Visszaad egy speciális "play mediafile" hiperlinket. AudioFrame és VideoFrame esetén használatos. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [NextSlide](../../aspose.slides/hyperlink/nextslide) { get; } | Visszaad egy hiperlinket a következő diához. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [NoAction](../../aspose.slides/hyperlink/noaction) { get; } | Visszaad egy speciális "do nothing" hiperlinket. Csak olvasható [`Hyperlink`](../hyperlink). |
| static [PreviousSlide](../../aspose.slides/hyperlink/previousslide) { get; } | Visszaad egy hiperlinket az előző diához. Csak olvasható [`Hyperlink`](../hyperlink). |
| [ActionType](../../aspose.slides/hyperlink/actiontype) { get; } | Visszaadja a Hyperlink műveletének típusát. Csak olvasható [`HyperlinkActionType`](../hyperlinkactiontype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi az IPresentationComponent alap interfész lekérését. Csak olvasható [`IPresentationComponent`](../ipresentationcomponent). |
| [ColorSource](../../aspose.slides/hyperlink/colorsource) { get; set; } | A hiperlink szín forrását képviseli – stílus vagy szakasz formátum. Olvasható/írható [`HyperlinkColorSource`](../hyperlinkcolorsource). |
| [ExternalUrl](../../aspose.slides/hyperlink/externalurl) { get; } | Megadja a külső URL-t. Csak olvasható String. |
| [ExternalUrlOriginal](../../aspose.slides/hyperlink/externalurloriginal) { get; } | A hiperlinket reprezentálja, amely erre a szakaszra van beállítva, anélkül, hogy figyelembe venné a szakasz tényleges tartalmát. A PowerPoint speciális módon kezeli a hivatkozásokat és a hozzájuk tartozó szöveget egy szakaszon belül. Lehetővé teszi, hogy a hiperlink szövegét egy érvényes URL formájában hozza létre, amely eltér a hivatkozás valós címétől. Ebben az esetben, amikor a hivatkozást a szerkesztőablakban megtekinti, az a szövegrésznek megfelelően módosul. Ez a tulajdonság a hiperlink eredeti értékét reprezentálja. |
| [HighlightClick](../../aspose.slides/hyperlink/highlightclick) { get; set; } | Meghatározza, hogy a hiperlink kattintáskor legyen-e kiemelve. Olvasható/írható Boolean. |
| [History](../../aspose.slides/hyperlink/history) { get; set; } | Meghatározza, hogy a szülő hiperlink célja hozzáadódjon-e a megtekintett hiperlinkek listájához, amikor meghívásra kerül. Olvasható/írható Boolean. |
| [Sound](../../aspose.slides/hyperlink/sound) { get; set; } | A hiperlink lejátszott hangját képviseli. Olvasható/írható [`IAudio`](../iaudio). |
| [StopSoundOnClick](../../aspose.slides/hyperlink/stopsoundonclick) { get; set; } | Meghatározza, hogy a hang leálljon-e a hiperlink kattintásakor. Olvasható/írható Boolean. |
| [TargetFrame](../../aspose.slides/hyperlink/targetframe) { get; set; } | Visszaadja a szülő HTML keretcsoportban a célhoz tartó keretet, ha létezik. Olvasható/írható String. |
| [TargetSlide](../../aspose.slides/hyperlink/targetslide) { get; } | Ha a Hyperlink egy adott diára mutat, visszaadja azt a diát. Csak olvasható [`ISlide`](../islide). |
| [Tooltip](../../aspose.slides/hyperlink/tooltip) { get; set; } | Visszaadja a sztringet, amely felhasználói felületen megjelenhet a szülő hiperlinkhez kapcsolódóan. Olvasható/írható String. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [Equals](../../aspose.slides/hyperlink/equals#equals)(IHyperlink) | Megállapítja, hogy a két Hyperlink példány egyenlő-e. |
| override [Equals](../../aspose.slides/hyperlink/equals#equals_1)(object) | Megállapítja, hogy a két Hyperlink példány egyenlő-e. |
| override [GetHashCode](../../aspose.slides/hyperlink/gethashcode)() | Hashfüggvényként szolgál egy adott típushoz, amely alkalmas hash algoritmusok és adatstruktúrák, például hash tábla használatához. |
| [operator ==](../../aspose.slides/hyperlink/op_equality) | Két hiperlinket tesztel egyenlőség szempontjából. |
| [operator !=](../../aspose.slides/hyperlink/op_inequality) | Két hiperlinket tesztel egyenlőtlenség szempontjából. |

### Lásd még

* osztály [PVIObject](../pviobject)
* interfész [IHyperlink](../ihyperlink)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->