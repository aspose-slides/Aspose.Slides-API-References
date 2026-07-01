---
title: IParagraphFormat
second_title: Aspose.Sildes pro .NET API Reference
description: Tato třída obsahuje vlastnosti formátování odstavců. Na rozdíl od IParagraphFormatEffectiveData./iparagraphformateffectivedata jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 6570
url: /cs/aspose.slides/iparagraphformat/
---
## IParagraphFormat rozhraní

Tato třída obsahuje vlastnosti formátování odstavců. Na rozdíl od [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

```csharp
public interface IParagraphFormat
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Vrací nebo nastavuje zarovnání textu v odstavci bez dědičnosti. Čtení/Zápis [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Vrací formát odrážek odstavce. Pouze pro čtení [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Vrací výchozí formát části odstavce. Není použita žádná dědičnost. Pouze pro čtení [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Vrací nebo nastavuje výchozí velikost tabulátorů bez dědičnosti. Čtení/Zápis Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Vrací nebo nastavuje hloubku odstavce. Hodnota 0 znamená nedefinovanou hodnotu. Čtení/Zápis Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Určuje, zda se v odstavci používá východoasijské zalomení řádku. Není použita žádná dědičnost. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Vrací nebo nastavuje zarovnání písma v odstavci bez dědičnosti. Čtení/Zápis [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Určuje, zda se v odstavci používá zavěšená interpunkce. Není použita žádná dědičnost. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Vrací nebo nastavuje první řádek/visící odsazení odstavce bez dědičnosti. Visící odsazení lze definovat zápornými hodnotami. Čtení/Zápis Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Určuje, zda se v odstavci používá latinské zalomení řádku. Není použita žádná dědičnost. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Vrací nebo nastavuje levý okraj v odstavci bez dědičnosti. Čtení/Zápis Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Vrací nebo nastavuje pravý okraj v odstavci bez dědičnosti. Čtení/Zápis Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Určuje, zda se v odstavci používá zápis zprava doleva. Není použita žádná dědičnost. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Vrací nebo nastavuje množství místa za posledním řádkem v odstavci bez dědičnosti. Kladná hodnota udává procento velikosti písma, které by měla bílá mezera mít. Záporná hodnota udává velikost bílé mezery v bodech. Čtení/Zápis Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Vrací nebo nastavuje množství místa před prvním řádkem v odstavci bez dědičnosti. Kladná hodnota udává procento velikosti písma, které by měla bílá mezera mít. Záporná hodnota udává velikost bílé mezery v bodech. Čtení/Zápis Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Vrací nebo nastavuje množství místa mezi základními řádky v odstavci. Kladná hodnota znamená procento, záporná – velikost v bodech. Není použita žádná dědičnost. Čtení/Zápis Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Vrací tabulátory odstavce. Není použita žádná dědičnost. Pouze pro čtení [`ITabCollection`](../itabcollection). |

## Metody

| Název | Popis |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Získá efektivní data formátování odstavce s aplikovanou dědičností. |

### Poznámky

Tato třída slouží k vracení a manipulaci s vlastnostmi formátování odstavců definovanými pro konkrétní odstavec. To znamená, že při získávání hodnot není použita žádná dědičnost, takže ve většině případů získáte hodnoty označující „nedefinováno“.

Pro získání efektivních hodnot parametrů formátování včetně zděděných je třeba použít metodu [`GetEffective`](./geteffective), která vrací instanci [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Viz také

* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->