---
title: ParagraphFormat
second_title: Aspose.Sildes pro .NET API Reference
description: Tato třída obsahuje vlastnosti formátování odstavců. Na rozdíl od IParagraphFormatEffectiveData./iparagraphformateffectivedata jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 9290
url: /cs/aspose.slides/paragraphformat/
---
## ParagraphFormat třída

Tato třída obsahuje vlastnosti formátování odstavců. Na rozdíl od [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), všechny vlastnosti této třídy jsou zapisovatelné.

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
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Vrací nebo nastavuje zarovnání textu v odstavci bez dědičnosti. Čtení/zápis [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umožňuje získat základní rozhraní IPresentationComponent. Pouze pro čtení [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Vrací nebo nastavuje výchozí velikost tabulátoru bez dědičnosti. Čtení/zápis Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Určuje, zda se v odstavci používá východoasijské zalomení řádku. Není použita žádná dědičnost. Čtení/zápis [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Vrací nebo nastavuje zarovnání písma v odstavci bez dědičnosti. Čtení/zápis [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Určuje, zda se v odstavci používá zavěšená interpunkce. Není použita žádná dědičnost. Čtení/zápis [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Vrací nebo nastavuje první řádkové odsazení/zavěšené odsazení odstavce bez dědičnosti. Zavěšené odsazení může být definováno zápornými hodnotami. Čtení/zápis Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Určuje, zda se v odstavci používá latinské zalomení řádku. Není použita žádná dědičnost. Čtení/zápis [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Vrací nebo nastavuje levý okraj v odstavci bez dědičnosti. Čtení/zápis Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Vrací nebo nastavuje pravý okraj v odstavci bez dědičnosti. Čtení/zápis Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Určuje, zda se v odstavci používá zápis zprava doleva. Není použita žádná dědičnost. Čtení/zápis [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Vrací nebo nastavuje množství prostoru za posledním řádkem v odstavci bez dědičnosti. Kladná hodnota určuje procento velikosti písma, které má bílý prostor zabírat. Záporná hodnota určuje velikost bílého prostoru v bodech. Čtení/zápis Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Vrací nebo nastavuje množství prostoru před prvním řádkem v odstavci bez dědičnosti. Kladná hodnota určuje procento velikosti písma, které má bílý prostor zabírat. Záporná hodnota určuje velikost bílého prostoru v bodech. Čtení/zápis Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Vrací nebo nastavuje množství prostoru mezi základními řádky v odstavci. Kladná hodnota znamená procento, záporná - velikost v bodech. Není použita žádná dědičnost. Čtení/zápis Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Vrací tabulátory odstavce. Není použita žádná dědičnost. Pouze pro čtení [`ITabCollection`](../itabcollection). |

## Metody

| Název | Popis |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porovnává se se zadaným objektem. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Získává efektivní data formátování odstavce s aplikovanou dědičností. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Vrací hash kód. |

### Poznámky

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování odstavce definovanými pro konkrétní odstavec. To znamená, že při získávání hodnot není použita žádná dědičnost, takže ve většině případů získáte hodnoty označující „nedefinováno“.

Pro získání efektivních hodnot parametrů formátování včetně zděděných je třeba použít metodu [`GetEffective`](./geteffective), která vrací instanci [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Viz také

* třída [PVIObject](../pviobject)
* rozhraní [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* rozhraní [IParagraphFormat](../iparagraphformat)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->