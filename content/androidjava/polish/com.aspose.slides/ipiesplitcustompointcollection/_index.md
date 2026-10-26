---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides dla systemu Android - odniesienie API Java
description: Reprezentuje kolekcję punktów, które mają być rysowane w drugim kawałku lub słupku na wykresie typu bar-of-pie lub pie-of-pie z niestandardowym podziałem.
type: docs
url: /pl/com.aspose.slides/ipiesplitcustompointcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Reprezentuje kolekcję punktów, które mają być rysowane w drugim kawałku lub słupku na wykresie „bar-of-pie” lub „pie-of-pie” z niestandardowym podziałem.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca punkt danych wykresu według indeksu. |
| [add(int dataPointIndex)](#add-int-) | Dodaje punkt danych według jego indeksu w kolekcji punktów serii nadrzędnej. |
| [remove(int dataPointIndex)](#remove-int-) | Usuwa element z kolekcji według jego indeksu w kolekcji punktów serii nadrzędnej. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Zwraca punkt danych wykresu według indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks punktu danych. |

**Zwraca:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Punkt danych wykresu.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```

Dodaje punkt danych według jego indeksu w kolekcji punktów serii nadrzędnej.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| dataPointIndex | int | Indeks punktu danych w kolekcji punktów serii nadrzędnej. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

Usuwa element z kolekcji według jego indeksu w kolekcji punktów serii nadrzędnej.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| dataPointIndex | int | Indeks punktu danych w kolekcji punktów serii nadrzędnej.. |