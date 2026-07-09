---
title: ParagraphFormat
second_title: Aspose.Sildes pro .NET API Reference
description: Tato třída obsahuje vlastnosti formátování odstavce. Na rozdíl od IParagraphFormatEffectiveData./iparagraphformateffectivedata jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 9310
url: /cs/aspose.slides/paragraphformat/
---
## ParagraphFormat třída

Tato třída obsahuje vlastnosti formátování odstavce. Na rozdíl od [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Inicializuje novou instanci třídy [`ParagraphFormat`](../paragraphformat). |

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Vrací nebo nastavuje zarovnání textu v odstavci bez dědičnosti. Čtení/Zápis [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umožňuje získat základní rozhraní IPresentationComponent. Pouze ke čtení [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Vrací nebo nastavuje výchozí velikost tabulátoru bez dědičnosti. Čtení/Zápis Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Určuje, zda je v odstavci použito východoasijské zalomení řádku. Není použita dědičnost. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Vrací nebo nastavuje zarovnání písma v odstavci bez dědičnosti. Čtení/Zápis [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Určuje, zda je v odstavci použita zavěšená interpunkce. Není použita dědičnost. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Vrací nebo nastavuje první řádkové odsazení / zavěšené odsazení odstavce bez dědičnosti. Zavěšené odsazení může být definováno zápornými hodnotami. Čtení/Zápis Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Určuje, zda je v odstavci použito latinské zalomení řádku. Není použita dědičnost. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Vrací nebo nastavuje levý okraj v odstavci bez dědičnosti. Čtení/Zápis Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Vrací nebo nastavuje pravý okraj v odstavci bez dědičnosti. Čtení/Zápis Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Určuje, zda je v odstavci použito psaní zprava doleva. Není použita dědičnost. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Vrací nebo nastavuje množství prostoru za posledním řádkem v odstavci bez dědičnosti. Kladná hodnota udává procento velikosti písma, kterou by měl bílý prostor mít. Záporná hodnota udává velikost bílého prostoru v bodech. Čtení/Zápis Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Vrací nebo nastavuje množství prostoru před prvním řádkem v odstavci bez dědičnosti. Kladná hodnota udává procento velikosti písma, kterou by měl bílý prostor mít. Záporná hodnota udává velikost bílého prostoru v bodech. Čtení/Zápis Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Vrací nebo nastavuje množství prostoru mezi základními řádky v odstavci. Kladná hodnota znamená procenta, záporná - velikost v bodech. Není použita dědičnost. Čtení/Zápis Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Vrací tabulátory odstavce. Není použita dědičnost. Pouze ke čtení [`ITabCollection`](../itabcollection). |

## Metody

| Název | Popis |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porovnává se se zadaným objektem. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Získá účinná data formátování odstavce s aplikovanou dědičností. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Vrací hash kód. |

### Poznámky

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování odstavce definovanými pro konkrétní odstavec. To znamená, že při získávání hodnot není použita dědičnost, takže ve většině případů získáte hodnoty označující “neurčeno”.

Pro získání účinných hodnot parametrů formátování včetně zděděných musíte použít metodu [`GetEffective`](./geteffective), která vrací instanci [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Viz také

* třída [PVIObject](../pviobject)
* rozhraní [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* rozhraní [IParagraphFormat](../iparagraphformat)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* assemblie [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->