---
title: PieSplitType
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Reprezentuje typ bodů dělení ve druhém výsečkovém nebo pruhovém grafu v grafu typu výseč-ve-výseč nebo pruh-ve-pruh.
type: docs
weight: 1665
url: /cs/aspose.slides.charts/piesplittype/
---
## PieSplitType výčet


Reprezentuje typ bodů dělení ve druhém výsečkovém nebo pruhovém grafu u grafu typu výseč-ve-výseč nebo pruh-ve-pruh.

```cpp
enum class PieSplitType
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Default | 0 | Určuje, že datové body mají být rozděleny pomocí výchozího mechanismu pro tento typ grafu. |
| Custom | 1 | Určuje, že datové body mají být rozděleny mezi výseč a druhý graf podle hodnot **Custom Split**. |
| ByPercentage | 2 | Určuje, že datové body mají být rozděleny mezi výseč a druhý graf tak, že body s procentem menším než **Split Position** procento budou umístěny do druhého grafu. |
| ByPos | 3 | Určuje, že datové body mají být rozděleny mezi výseč a druhý graf tak, že poslední **Split Position** datových bodů bude umístěna do druhého grafu. |
| ByValue | 4 | Určuje, že datové body mají být rozděleny mezi výseč a druhý graf tak, že datové body s hodnotou menší než **Split Position** budou umístěny do druhého grafu. |

## See Also

* Namespace [Aspose::Slides::Charts](../)
* Library [Aspose.Slides](../../)