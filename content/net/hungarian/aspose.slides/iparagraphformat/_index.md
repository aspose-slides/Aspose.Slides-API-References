---
title: IParagraphFormat
second_title: Aspose.Sildes .NET API Referencia
description: Ez az osztály tartalmazza a bekezdés formázási tulajdonságait. A IParagraphFormatEffectiveData./iparagraphformateffectivedata-tól eltérően, az osztály minden tulajdonsága írható.
type: docs
weight: 6570
url: /hu/aspose.slides/iparagraphformat/
---
## IParagraphFormat interfész

Ez az osztály tartalmazza a bekezdés formázási tulajdonságait. A [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata)-tól eltérően, az osztály minden tulajdonsága írható.

```csharp
public interface IParagraphFormat
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Visszaadja vagy beállítja a szöveg igazítását egy bekezdésben öröklődés nélkül. Olvasás/írás [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Visszaadja a bekezdés felsorolásformátumát. Csak olvasható [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Visszaadja a bekezdés alapértelmezett részformátumát. Nincs öröklődés alkalmazva. Csak olvasható [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Visszaadja vagy beállítja az alapértelmezett tabuláció méretét öröklődés nélkül. Olvasás/írás Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Visszaadja vagy beállítja a bekezdés mélységét. A 0 érték meghatározatlan értéket jelent. Olvasás/írás Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Meghatározza, hogy a kelet-ázsiai sortörést használják-e a bekezdésben. Nincs öröklődés alkalmazva. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Visszaadja vagy beállítja a betűtípus igazítását egy bekezdésben öröklődés nélkül. Olvasás/írás [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Meghatározza, hogy függő idézőjelet használnak-e a bekezdésben. Nincs öröklődés alkalmazva. Olvasás/írás [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Visszaadja vagy beállítja a bekezdés első sor behúzását/függő behúzást öröklődés nélkül. A függő behúzás negatív értékekkel is megadható. Olvasás/írás Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Meghatározza, hogy a latin sortörést használják-e a bekezdésben. Nincs öröklődés alkalmazva. Olvasás/írás [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Visszaadja vagy beállítja a bal oldali margót egy bekezdésben öröklődés nélkül. Olvasás/írás Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Visszaadja vagy beállítja a jobb oldali margót egy bekezdésben öröklődés nélkül. Olvasás/írás Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Meghatározza, hogy a jobbról balra írás irányt használják-e a bekezdésben. Nincs öröklődés alkalmazva. Olvasás/írás [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Visszaadja vagy beállítja az utolsó sor utáni térköz mennyiségét egy bekezdésben öröklődés nélkül. A pozitív érték a betűméret százalékát adja meg, amely a fehér térközt jelenti. A negatív érték a fehér térköz méretét pontban adja meg. Olvasás/írás Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Visszaadja vagy beállítja az első sor előtti térköz mennyiségét egy bekezdésben öröklődés nélkül. A pozitív érték a betűméret százalékát jelöli, amely a fehér térköz. A negatív érték a fehér térköz méretét pontban adja meg. Olvasás/írás Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Visszaadja vagy beállítja az alapsorok közötti térköz mennyiségét egy bekezdésben. A pozitív érték százalékot jelent, a negatív – pontokban kifejezett méretet. Nincs öröklődés alkalmazva. Olvasás/írás Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Visszaadja a bekezdés tabulációit. Nincs öröklődés alkalmazva. Csak olvasható [`ITabCollection`](../itabcollection). |

## Módszerek

| Név | Leírás |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Lekéri a hatékony bekezdés formázási adatokat, a öröklődés alkalmazásával. |

### Megjegyzés

Ez az osztály a meghatározott bekezdésre vonatkozó bekezdésformázási tulajdonságok visszaadására és módosítására szolgál. Ez azt jelenti, hogy az értékek lekérdezésekor nincs öröklődés alkalmazva, így a legtöbb esetben "nem definiált" értékeket kap.

Az örökölt értékeket is tartalmazó hatékony formázási paraméterek lekéréséhez a [`GetEffective`](./geteffective) metódust kell használni, amely egy [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) példányt ad vissza.

### Lásd még

* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->