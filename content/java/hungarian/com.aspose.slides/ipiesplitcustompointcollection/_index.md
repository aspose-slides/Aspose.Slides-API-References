---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides Java API Referencia
description: Egy pontgyűjteményt képvisel, amely egyedi felosztással a bar-of-pie vagy pie-of-pie diagram második tortáján vagy oszlopán kerül kirajzolásra.
type: docs
url: /hu/com.aspose.slides/ipiesplitcustompointcollection/
---
**Minden megvalósított interfész:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Egy pontgyűjteményt képvisel, amely egyedi felosztással a bar-of-pie vagy pie-of-pie diagram második tortáján vagy oszlopán kerül kirajzolásra.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszaadja a diagram adatpontot index alapján. |
| [add(int dataPointIndex)](#add-int-) | Hozzáad egy adatpontot a szülő sorozat pontgyűjteményének indexe alapján. |
| [remove(int dataPointIndex)](#remove-int-) | Eltávolít egy elemet a gyűjteményből a szülő sorozat pontgyűjteményének indexe alapján. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

Visszaadja a diagram adatpontot index alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az adatpont indexe. |

**Visszatérési érték:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Diagram adatpont.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```

Hozzáad egy adatpontot a szülő sorozat pontgyűjteményének indexe alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dataPointIndex | int | Az adatpont indexe a szülő sorozat pontgyűjteményében. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

Eltávolít egy elemet a gyűjteményből a szülő sorozat pontgyűjteményének indexe alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| dataPointIndex | int | Az adatpont indexe a szülő sorozat pontgyűjteményében.. |