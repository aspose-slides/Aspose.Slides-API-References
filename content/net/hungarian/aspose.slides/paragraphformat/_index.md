---
title: ParagraphFormat
second_title: Aspose.Sildes .NET API referencia
description: Ez az osztály a bekezdésformázási tulajdonságokat tartalmazza. A IParagraphFormatEffectiveData./iparagraphformateffectivedata-tól eltérően ennek az osztálynak az összes tulajdonsága írható.
type: docs
weight: 9310
url: /hu/aspose.slides/paragraphformat/
---
## ParagraphFormat osztály

Ez az osztály a bekezdésformázási tulajdonságokat tartalmazza. A [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata)-tól eltérően ennek az osztálynak az összes tulajdonsága írható.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Új példányt hoz létre a [`ParagraphFormat`](../paragraphformat) osztályból. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Visszaadja vagy beállítja a szöveg igazítását egy bekezdésben öröklődés nélkül. Olvasás/írás [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi a base IPresentationComponent interfész lekérését. Csak olvasás [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Visszaadja vagy beállítja az alapértelmezett tabuláció méretét öröklődés nélkül. Olvasás/írás Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Megállapítja, hogy a kelet-ázsiai sortörést használják-e egy bekezdésben. Nem alkalmazott öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Visszaadja vagy beállítja a betűtípus igazítását egy bekezdésben öröklődés nélkül. Olvasás/írás [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Megállapítja, hogy függőben lévő írásjelet használnak-e egy bekezdésben. Nem alkalmazott öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Visszaadja vagy beállítja a bekezdés első sor behúzását/függő behúzást öröklődés nélkül. A függő behúzás negatív értékekkel definiálható. Olvasás/írás Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Megállapítja, hogy a latin sortörést használják-e egy bekezdésben. Nem alkalmazott öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül. Olvasás/írás Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül. Olvasás/írás Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Megállapítja, hogy jobbról balra írás használatos-e egy bekezdésben. Nem alkalmazott öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Visszaadja vagy beállítja az utolsó sor utáni térköz mennyiségét egy bekezdésben öröklődés nélkül. A pozitív érték a betűméret százalékát adja meg a fehér térnek. A negatív érték a térköz méretét adja pontban. Olvasás/írás Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Visszaadja vagy beállítja az első sor előtti térköz mennyiségét egy bekezdésben öröklődés nélkül. A pozitív érték a betűméret százalékát adja meg a fehér térnek. A negatív érték a térköz méretét adja pontban. Olvasás/írás Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Visszaadja vagy beállítja az alapvonalak közötti térköz mennyiségét egy bekezdésben. A pozitív érték százalékot jelent, a negatív - pontban megadott méretet. Nem alkalmazott öröklődés. Olvasás/írás Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Visszaadja egy bekezdés tabulációit. Nem alkalmazott öröklődés. Csak olvasás [`ITabCollection`](../itabcollection). |

## Metódusok

| Név | Leírás |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Összehasonlítja a megadott objektummal. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Lekéri a hatékony bekezdésformázási adatokat az alkalmazott öröklődéssel. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Visszaadja a hash kódot. |

### Megjegyzés

Ez az osztály a megadott bekezdéshez definiált bekezdésformázási tulajdonságok visszaadására és módosítására szolgál. Ez azt jelenti, hogy értékek lekérésekor nem alkalmazódik az öröklődés, így a legtöbb esetben a visszakapott értékek „nem definiált” jelentéssel bírnak.

Az örökölt értékeket is tartalmazó hatékony formázási paraméterek lekéréséhez a [`GetEffective`](./geteffective) metódust kell használnia, amely egy [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) példányt ad vissza.

### Lásd még

* osztály [PVIObject](../pviobject)
* interfész [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* interfész [IParagraphFormat](../iparagraphformat)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->