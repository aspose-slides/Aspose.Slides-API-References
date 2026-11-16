---
title: ParagraphFormat
second_title: Aspose.Sildes pro .NET – referenční příručka API
description: Tato třída obsahuje vlastnosti formátování odstavců. Na rozdíl od IParagraphFormatEffectiveData./iparagraphformateffectivedata jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 9330
url: /cs/aspose.slides/paragraphformat/
---
## ParagraphFormat třída

Tato třída obsahuje vlastnosti formátování odstavců. Na rozdíl od [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Konstruktory

| Name | Description |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Inicializuje novou instanci třídy [`ParagraphFormat`](../paragraphformat). |

## Vlastnosti

| Name | Description |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Vrací nebo nastavuje zarovnání textu v odstavci bez dědičnosti. Čtení/Zápis [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umožňuje získat základní rozhraní IPresentationComponent. Pouze ke čtení [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Vrací nebo nastavuje výchozí velikost tabulátoru bez dědičnosti. Čtení/Zápis Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Určuje, zda se v odstavci používá východoasijské zalomení řádku. Není použita dědičnost. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Vrací nebo nastavuje zarovnání písma v odstavci bez dědičnosti. Čtení/Zápis [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Určuje, zda se v odstavci používá zavěšená interpunkce. Není použita dědičnost. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Vrací nebo nastavuje odsazení první řádky/visící odsazení odstavce bez dědičnosti. Visící odsazení může být definováno zápornými hodnotami. Čtení/Zápis Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Určuje, zda se v odstavci používá latinské zalomení řádku. Není použita dědičnost. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Vrací nebo nastavuje levý okraj v odstavci bez dědičnosti. Čtení/Zápis Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Vrací nebo nastavuje pravý okraj v odstavci bez dědičnosti. Čtení/Zápis Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Určuje, zda se v odstavci používá zápis zprava doleva. Není použita dědičnost. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Vrací nebo nastavuje množství prostoru za poslední řádkou v odstavci bez dědičnosti. Kladná hodnota udává procento velikosti písma, kterou by měl být bílý prostor. Záporná hodnota udává velikost bílého prostoru v bodech. Čtení/Zápis Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Vrací nebo nastavuje množství prostoru před první řádkou v odstavci bez dědičnosti. Kladná hodnota udává procento velikosti písma, kterou by měl být bílý prostor. Záporná hodnota udává velikost bílého prostoru v bodech. Čtení/Zápis Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Vrací nebo nastavuje množství prostoru mezi základními řádky v odstavci. Kladná hodnota znamená procento, záporná - velikost v bodech. Není použita dědičnost. Čtení/Zápis Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Vrací tabulátory odstavce. Není použita dědičnost. Pouze ke čtení [`ITabCollection`](../itabcollection). |

## Metody

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porovnává se se zadaným objektem. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Získá efektivní data formátování odstavce s použitou dědičností. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Vrací hash kód. |

### Poznámky

Tato třída slouží k vracení a manipulaci s vlastnostmi formátování odstavců definovanými pro konkrétní odstavec. To znamená, že při získávání hodnot není použita dědičnost, takže ve většině případů obdržíte hodnoty označující “neurčený”.

Pro získání efektivních hodnot parametrů formátování včetně zděděných je třeba použít metodu [`GetEffective`](./geteffective), která vrací instanci [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Viz také

* třída [PVIObject](../pviobject)
* rozhraní [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* rozhraní [IParagraphFormat](../iparagraphformat)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* assemblie [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->