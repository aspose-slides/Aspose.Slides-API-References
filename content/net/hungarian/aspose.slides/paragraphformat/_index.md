---
title: ParagraphFormat
second_title: Aspose.Sildes .NET API Referencia
description: Ez az osztály tartalmazza a bekezdésformázási tulajdonságokat. A IParagraphFormatEffectiveData./iparagraphformateffectivedata-tól eltérően az osztály összes tulajdonsága írható.
type: docs
weight: 9330
url: /hu/aspose.slides/paragraphformat/
---
## ParagraphFormat osztály

Ez az osztály tartalmazza a bekezdésformázási tulajdonságokat. A [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata)-tól eltérően az osztály összes tulajdonsága írható.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Konstruktorok

| Name | Description |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Új példányt hoz létre a [`ParagraphFormat`](../paragraphformat) osztályból. |

## Tulajdonságok

| Name | Description |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Visszaadja vagy beállítja a szöveg igazítását egy bekezdésben öröklődés nélkül. Olvasás/írás [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi az alap IPresentationComponent interfész lekérését. Csak olvasható [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Visszaadja vagy beállítja az alapértelmezett tabuláció méretét öröklődés nélkül. Olvasás/írás Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Meghatározza, hogy a kelet-ázsiai sortörést használják-e a bekezdésben. Nincs öröklődés alkalmazva. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Visszaadja vagy beállítja a betűtípus igazítását egy bekezdésben öröklődés nélkül. Olvasás/írás [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Meghatározza, hogy a függőleges írásjelek használatban vannak-e a bekezdésben. Nincs öröklődés alkalmazva. Olvasás/írás [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Visszaadja vagy beállítja a bekezdés első sor behúzását/függőleges behúzást öröklődés nélkül. A függőleges behúzás negatív értékekkel is definiálható. Olvasás/írás Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Meghatározza, hogy a latin sortörést használják-e a bekezdésben. Nincs öröklődés alkalmazva. Olvasás/írás [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül. Olvasás/írás Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül. Olvasás/írás Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Meghatározza, hogy a jobbról balra írás használatban van-e a bekezdésben. Nincs öröklődés alkalmazva. Olvasás/írás [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Visszaadja vagy beállítja az utolsó sor utáni szóköz mennyiségét egy bekezdésben öröklődés nélkül. A pozitív érték a betűméret százalékában adja meg a szóköz nagyságát. A negatív érték a szóköz méretét pontban határozza meg. Olvasás/írás Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Visszaadja vagy beállítja az első sor előtti szóköz mennyiségét egy bekezdésben öröklődés nélkül. A pozitív érték a betűméret százalékában adja meg a szóköz nagyságát. A negatív érték a szóköz méretét pontban határozza meg. Olvasás/írás Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Visszaadja vagy beállítja az alapvonalak közötti szóköz mennyiségét egy bekezdésben. A pozitív érték százalékot, a negatív - pontban megadott méretet jelent. Nincs öröklődés alkalmazva. Olvasás/írás Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Visszaadja egy bekezdés tabulációit. Nincs öröklődés alkalmazva. Csak olvasható [`ITabCollection`](../itabcollection). |

## Módszerek

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Összehasonlítja a megadott objektummal. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Megkapja a hatékony bekezdésformázási adatokat az öröklődés alkalmazásával. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Visszaadja a hash-kódot. |

### Megjegyzés

Ez az osztály a konkrét bekezdéshez definiált bekezdésformázási tulajdonságok visszaadására és módosítására szolgál. Ez azt jelenti, hogy az értékek lekérésekor nincs öröklődés alkalmazva, ezért a legtöbb esetben olyan értékeket kapunk, amelyek jelentése „nem definiált”.

Az öröklött értékeket is tartalmazó hatékony formázási paraméterek lekéréséhez a [`GetEffective`](./geteffective) metódust kell használni, amely egy [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) példányt ad vissza.

### Lásd még

* osztály [PVIObject](../pviobject)
* interfész [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* interfész [IParagraphFormat](../iparagraphformat)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->