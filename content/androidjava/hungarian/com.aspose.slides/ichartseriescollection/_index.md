---
title: IChartSeriesCollection
second_title: Aspose.Slides Androidra a Java API hivatkozás segítségével
description: Gyűjteményt képvisel
type: docs
url: /hu/com.aspose.slides/ichartseriescollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

A [IChartSeries](../../com.aspose.slides/ichartseries) gyűjteményt képviseli.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lekéri az elemet a megadott indexnél. |
| [add(int type)](#add-int-) | Új diagram sorozatot hoz létre, és hozzáadja a gyűjteményhez. |
| [insert(int index, int type)](#insert-int-int-) | Új diagram sorozatot hoz létre, és beilleszti a gyűjteménybe. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Új diagram sorozatot hoz létre a [IChartDataCell](../../com.aspose.slides/ichartdatacell) alapján, és hozzáadja a gyűjteményhez. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Új diagram sorozatot hoz létre a [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) alapján, és hozzáadja a gyűjteményhez. |
| [add(String name, int type)](#add-java.lang.String-int-) | Új diagram sorozatot hoz létre az értékből, és hozzáadja a gyűjteményhez. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Keres a megadott [IChartSeries](../../com.aspose.slides/ichartseries) után, és visszaadja a nulla alapú indexet az első előfordulásra az egész Gyűjteményben. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Eltávolítja a megadott értéket. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja az elemet a megadott indexnél. |
| [clear()](#clear--) | Eltávolítja az összes elemet (beleértve a diagram stílusát) a gyűjteményből. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Lekéri az elemet a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[IChartSeries](../../com.aspose.slides/ichartseries) - A megadott indexnél lévő elem.

### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

Új diagram sorozatot hoz létre, és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | int | Sorozat típusa |

**Visszatér:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Új diagram sorozat.

### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

Új diagram sorozatot hoz létre, és beilleszti a gyűjteménybe.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Beillesztési index |
| type | int | Diagram típusa [ChartType](../../com.aspose.slides/charttype) |

**Visszatér:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Új diagram sorozat [IChartSeries](../../com.aspose.slides/ichartseries)

### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Új diagram sorozatot hoz létre a [IChartDataCell](../../com.aspose.slides/ichartdatacell) alapján, és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | A sorozat nevet tartalmazó cella. |
| type | int | A sorozat típusának beállítása |

--------------------

Ha a diagram sorozat ugyanabból a cellából már szerepel a gyűjteményben, akkor a metódus nem ad hozzá semmit, és visszaadja az indexét. |

**Visszatér:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Hozzáadott diagram sorozat vagy a már a gyűjteményben lévő sorozat.

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Új diagram sorozatot hoz létre a [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) alapján, és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | A sorozat nevet tartalmazó cellák. |
| type | int | A sorozat típusának beállítása |

--------------------

Ha a diagram sorozat ugyanabból a cellából már szerepel a gyűjteményben, akkor a metódus nem ad hozzá semmit, és visszaadja az indexét. |

**Visszatér:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Hozzáadott diagram sorozat vagy a már a gyűjteményben lévő sorozat.

### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

Új diagram sorozatot hoz létre az értékből, és hozzáadja a gyűjteményhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | java.lang.String | Sorozat neve. |
| type | int | A sorozat típusának beállítása |

**Visszatér:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Hozzáadott diagram sorozat.

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

Keres a megadott [IChartSeries](../../com.aspose.slides/ichartseries) után, és visszaadja a nulla alapú indexet az első előfordulásra az egész Gyűjteményben.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Diagram sorozat értéke. |

**Visszatér:**
int - A nulla alapú index az első előfordulásra a teljes CollectionBase-ben, ha megtalálja; egyébként -1.

### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

Eltávolítja a megadott értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Az érték. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja az elemet a megadott indexnél.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Index |

### clear() {#clear--}
```
public abstract void clear()
```

Eltávolítja az összes elemet (beleértve a diagram stílusát) a gyűjteményből.