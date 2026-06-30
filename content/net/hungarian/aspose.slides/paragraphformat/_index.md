---
title: ParagraphFormat
second_title: Aspose.Sildes .NET API referencia
description: Ez az osztály tartalmazza a bekezdésformázási tulajdonságokat. Az IParagraphFormatEffectiveData./iparagraphformateffectivedata-tól eltérően, ennek az osztálynak az összes tulajdonsága írható.
type: docs
weight: 9290
url: /hu/aspose.slides/paragraphformat/
---
## ParagraphFormat osztály

Ez az osztály tartalmazza a bekezdésformázási tulajdonságokat. A [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata)-tól eltérően, ennek az osztálynak az összes tulajdonsága írható.

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
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Visszaadja vagy beállítja a szövegigazítást egy bekezdésben öröklődés nélkül. Olvasás/írás [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi a base IPresentationComponent interfész lekérését. Csak olvasható [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Visszaadja vagy beállítja az alapértelmezett tabuláció méretét öröklődés nélkül. Olvasás/írás Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Meghatározza, hogy a kelet-ázsiai sortörést használja-e a bekezdésben. Nincs alkalmazva öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Visszaadja vagy beállítja a betűtípus igazítását egy bekezdésben öröklődés nélkül. Olvasás/írás [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Meghatározza, hogy függő írásjelet használ-e a bekezdésben. Nincs alkalmazva öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Visszaadja vagy beállítja a bekezdés első sor behúzását/függő behúzást öröklődés nélkül. A függő behúzás negatív értékekkel is definiálható. Olvasás/írás Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Meghatározza, hogy a latin sortörést használja-e a bekezdésben. Nincs alkalmazva öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül. Olvasás/írás Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül. Olvasás/írás Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Meghatározza, hogy jobbról balra írási irányt használ-e a bekezdésben. Nincs alkalmazva öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Visszaadja vagy beállítja az utolsó sor utáni térköz mennyiségét egy bekezdésben öröklődés nélkül. Pozitív érték a betűméret százalékát adja meg, negatív érték a térköz méretét pontban. Olvasás/írás Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Visszaadja vagy beállítja az első sor előtti térköz mennyiségét egy bekezdésben öröklődés nélkül. Pozitív érték a betűméret százalékát adja meg, negatív érték a térköz méretét pontban. Olvasás/írás Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Visszaadja vagy beállítja az alapvonalak közti térköz mennyiségét egy bekezdésben. Pozitív érték százalék, negatív – méret pontban. Nincs alkalmazva öröklődés. Olvasás/írás Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Visszaadja a bekezdés tabulációit. Nincs alkalmazva öröklődés. Csak olvasható [`ITabCollection`](../itabcollection). |

## Metódusok

| Név | Leírás |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Összehasonlítja a megadott objektummal. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Megkapja a hatékony bekezdésformázási adatokat az alkalmazott öröklődéssel. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Visszaadja a hash kódot. |

### Megjegyzés

Ez az osztály a konkrét bekezdéshez definiált bekezdésformázási tulajdonságok visszaadására és módosítására szolgál. Ez azt jelenti, hogy öröklődés nem alkalmazandó az értékek lekérdezésekor, ezért a legtöbb esetben „nem definiált” értékeket kap.

A hatékony formázási paraméterértékek, beleértve az örökölt értékeket, lekéréséhez a [`GetEffective`](./geteffective) metódust kell használni, amely egy [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) példányt ad vissza.

### Kapcsolódó

* osztály [PVIObject](../pviobject)
* interfész [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* interfész [IParagraphFormat](../iparagraphformat)
* névtér [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->