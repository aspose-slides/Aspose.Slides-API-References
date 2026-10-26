---
title: IParagraphFormat
second_title: Aspose.Sildes a .NET API referenciához
description: Ez az osztály tartalmazza a bekezdésformázási tulajdonságokat. Az IParagraphFormatEffectiveData./iparagraphformateffectivedata-vel ellentétben az összes tulajdonsága írható.
type: docs
weight: 6590
url: /hu/aspose.slides/iparagraphformat/
---
## IParagraphFormat interfész

Ez az osztály tartalmazza a bekezdésformázási tulajdonságokat. A [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata)-től eltérően ennek az osztálynak az összes tulajdonsága írható.

```csharp
public interface IParagraphFormat
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Visszaadja vagy beállítja a szöveg igazítását egy bekezdésben öröklődés nélkül. Olvasás/írás [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Visszaadja a bekezdés felsorolásformátumát. Csak olvasható [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Visszaadja egy bekezdés alapértelmezett szakaszformátumát. Nincs alkalmazott öröklődés. Csak olvasható [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Visszaadja vagy beállítja az alapértelmezett tabulációméretet öröklődés nélkül. Olvasás/írás Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Visszaadja vagy beállítja a bekezdés mélységét. A 0 érték meghatározatlan értéket jelent. Olvasás/írás Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Meghatározza, hogy a kelet-ázsiai sortörést használják-e a bekezdésben. Nincs alkalmazott öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Visszaadja vagy beállítja a betűtípus igazítását egy bekezdésben öröklődés nélkül. Olvasás/írás [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Meghatározza, hogy a lógó írásjelet használják-e a bekezdésben. Nincs alkalmazott öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Visszaadja vagy beállítja a bekezdés első sor behúzását/lógó behúzását öröklődés nélkül. A lógó behúzás negatív értékkel is megadható. Olvasás/írás Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Meghatározza, hogy a latin sortörést használják-e a bekezdésben. Nincs alkalmazott öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Visszaadja vagy beállítja a bal margót egy bekezdésben öröklődés nélkül. Olvasás/írás Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Visszaadja vagy beállítja a jobb margót egy bekezdésben öröklődés nélkül. Olvasás/írás Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Meghatározza, hogy a jobbról balra írás irányát használják-e a bekezdésben. Nincs alkalmazott öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Visszaadja vagy beállítja az utolsó sor után lévő térköz mennyiségét egy bekezdésben öröklődés nélkül. A pozitív érték a betűméret százalékában adja meg a fehér tér méretét. A negatív érték a fehér tér méretét pontban adja meg. Olvasás/írás Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Visszaadja vagy beállítja az első sor előtti térköz mennyiségét egy bekezdésben öröklődés nélkül. A pozitív érték a betűméret százalékában adja meg a fehér tér méretét. A negatív érték a fehér tér méretét pontban adja meg. Olvasás/írás Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Visszaadja vagy beállítja az alapvonalak közti térköz mennyiségét egy bekezdésben. A pozitív érték százalék, a negatív - méret pontban. Nincs alkalmazott öröklődés. Olvasás/írás Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Visszaadja a bekezdés tabulációit. Nincs alkalmazott öröklődés. Csak olvasható [`ITabCollection`](../itabcollection). |

## Metódusok

| Név | Leírás |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Lekéri a hatékony bekezdésformázási adatokat az öröklődés alkalmazával. |

### Megjegyzések

Ez az osztály a konkrét bekezdéshez definiált bekezdésformázási tulajdonságok visszaadására és módosítására szolgál. Ez azt jelenti, hogy az értékek lekérésekor nincs alkalmazott öröklődés, így a legtöbb esetben „határozatlan” értékeket kap.

Az öröklött értékeket is tartalmazó hatékony formázási paraméterek lekéréséhez a [`GetEffective`](./geteffective) metódust kell használni, amely egy [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) példányt ad vissza.

### Lásd még

* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->