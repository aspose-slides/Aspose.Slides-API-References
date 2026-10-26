---
title: IParagraphFormat
second_title: Aspose.Sildes pro .NET reference API
description: Tato třída obsahuje vlastnosti formátování odstavce. Na rozdíl od IParagraphFormatEffectiveData./iparagraphformateffectivedata jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 6590
url: /cs/aspose.slides/iparagraphformat/
---
## IParagraphFormat rozhraní

Tato třída obsahuje vlastnosti formátování odstavce. Na rozdíl od [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

```csharp
public interface IParagraphFormat
```

## Vlastnosti

| Name | Description |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Vrací nebo nastavuje zarovnání textu v odstavci bez dědičnosti. Čtení/Zápis [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Vrací formát odrážky odstavce. Pouze ke čtení [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Vrací výchozí formát úseku odstavce. Není použita dědičnost. Pouze ke čtení [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Vrací nebo nastavuje výchozí velikost tabelace bez dědičnosti. Čtení/Zápis Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Vrací nebo nastavuje hloubku odstavce. Hodnota 0 znamená nedefinovanou hodnotu. Čtení/Zápis Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Určuje, zda je v odstavci použito východněasijské zalomení řádku. Není použita dědičnost. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Vrací nebo nastavuje zarovnání písma v odstavci bez dědičnosti. Čtení/Zápis [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Určuje, zda je v odstavci použita zavěšená interpunkce. Není použita dědičnost. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Vrací nebo nastavuje první řádkový odsazení/zavěšený odsazení odstavce bez dědičnosti. Zavěšený odsazení může být definován zápornými hodnotami. Čtení/Zápis Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Určuje, zda je v odstavci použito latinské zalomení řádku. Není použita dědičnost. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Vrací nebo nastavuje levý okraj v odstavci bez dědičnosti. Čtení/Zápis Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Vrací nebo nastavuje pravý okraj v odstavci bez dědičnosti. Čtení/Zápis Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Určuje, zda je v odstavci použito psaní zprava doleva. Není použita dědičnost. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Vrací nebo nastavuje množství prostoru po posledním řádku v odstavci bez dědičnosti. Kladná hodnota určuje procento velikosti písma, které má bílý prostor představovat. Záporná hodnota určuje velikost bílého prostoru v bodech. Čtení/Zápis Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Vrací nebo nastavuje množství prostoru před prvním řádkem v odstavci bez dědičnosti. Kladná hodnota určuje procento velikosti písma, které má bílý prostor představovat. Záporná hodnota určuje velikost bílého prostoru v bodech. Čtení/Zápis Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Vrací nebo nastavuje množství prostoru mezi základními řádky v odstavci. Kladná hodnota znamená procento, záporná - velikost v bodech. Není použita dědičnost. Čtení/Zápis Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Vrací tabelace odstavce. Není použita dědičnost. Pouze ke čtení [`ITabCollection`](../itabcollection). |

## Metody

| Name | Description |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Získá efektivní data formátování odstavce s aplikovanou dědičností. |

### Poznámky

Tato třída se používá k vrácení a manipulaci s vlastnostmi formátování odstavce definovanými pro konkrétní odstavec. To znamená, že při získávání hodnot není použita žádná dědičnost, takže ve většině případů získáte hodnoty označující „nedefinováno“. Pro získání efektivních hodnot parametrů formátování včetně zděděných musíte použít metodu [`GetEffective`](./geteffective), která vrací instanci [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Viz také

* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestava [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->