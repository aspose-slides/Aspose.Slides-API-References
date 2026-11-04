---
title: IParagraphFormat
second_title: Aspose.Sildes pro .NET API Reference
description: Tato třída obsahuje vlastnosti formátování odstavce. Na rozdíl od IParagraphFormatEffectiveData./iparagraphformateffectivedata jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 6610
url: /cs/aspose.slides/iparagraphformat/
---
## IParagraphFormat rozhraní

Tato třída obsahuje vlastnosti formátování odstavce. Na rozdíl od [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

```csharp
public interface IParagraphFormat
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Vrací nebo nastavuje zarovnání textu v odstavci bez dědičnosti. Čtení/zápis [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Vrací formát odrážky odstavce. Pouze pro čtení [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Vrací výchozí formát podílu odstavce. Není použita dědičnost. Pouze pro čtení [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Vrací nebo nastavuje výchozí velikost tabulátoru bez dědičnosti. Čtení/zápis Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Vrací nebo nastavuje hloubku odstavce. Hodnota 0 znamená nedefinovanou hodnotu. Čtení/zápis Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Určuje, zda je v odstavci používáno východoasijské zalomení řádku. Není použita dědičnost. Čtení/zápis [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Vrací nebo nastavuje zarovnání písma v odstavci bez dědičnosti. Čtení/zápis [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Určuje, zda je v odstavci používána zavěšená interpunkce. Není použita dědičnost. Čtení/zápis [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Vrací nebo nastavuje první řádkový odsazení/zavěšený odsazení odstavce bez dědičnosti. Zavěšený odsazení lze definovat zápornými hodnotami. Čtení/zápis Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Určuje, zda je v odstavci používáno latinské zalomení řádku. Není použita dědičnost. Čtení/zápis [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Vrací nebo nastavuje levý okraj v odstavci bez dědičnosti. Čtení/zápis Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Vrací nebo nastavuje pravý okraj v odstavci bez dědičnosti. Čtení/zápis Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Určuje, zda je v odstavci používán zápis zprava doleva. Není použita dědičnost. Čtení/zápis [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Vrací nebo nastavuje množství prostoru po posledním řádku v odstavci bez dědičnosti. Kladná hodnota určuje procento velikosti písma, které má být bílý prostor. Záporná hodnota určuje velikost bílého prostoru v bodech. Čtení/zápis Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Vrací nebo nastavuje množství prostoru před prvním řádkem v odstavci bez dědičnosti. Kladná hodnota určuje procento velikosti písma, které má být bílý prostor. Záporná hodnota určuje velikost bílého prostoru v bodech. Čtení/zápis Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Vrací nebo nastavuje množství prostoru mezi základními řádky v odstavci. Kladná hodnota znamená procento, záporná - velikost v bodech. Není použita dědičnost. Čtení/zápis Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Vrací tabulátory odstavce. Není použita dědičnost. Pouze pro čtení [`ITabCollection`](../itabcollection). |

## Metody

| Název | Popis |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Získá efektivní data formátování odstavce s aplikovanou dědičností. |

### Poznámky

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování odstavce definovanými pro konkrétní odstavec. To znamená, že při získávání hodnot není použita dědičnost, takže ve většině případů získáte hodnoty označující „nedefinováno“.

Pro získání efektivních hodnot parametrů formátování včetně zděděných je třeba použít metodu [`GetEffective`](./geteffective), která vrací instanci [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Viz také

* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->