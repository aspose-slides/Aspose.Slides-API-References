---
title: IChartCategoryCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar samling av
type: docs
url: /sv/com.aspose.slides/ichartcategorycollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

Representerar samling av [IChartCategory](../../com.aspose.slides/ichartcategory)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [getUseCells()](#getUseCells--) | Om true används arbetsbladet för att lagra kategorier (detta fall stöder flernivåkategorier). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Om true används arbetsbladet för att lagra kategorier (detta fall stöder flernivåkategorier). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Returnerar antalet nivåer för kategorigruppering som används. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Om kategorin finns i samlingen, returnera den. |
| [add(Object value)](#add-java.lang.Object-) | Skapar ny [IChartCategory](../../com.aspose.slides/ichartcategory) från värdet och lägger till den i samlingen. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Söker efter den angivna [IChartCategory](../../com.aspose.slides/ichartcategory) och returnerar det nollbaserade indexet för den första förekomsten i hela Collection |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Tar bort det angivna värdet. |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

Hämtar elementet på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Elementet på det angivna indexet.
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

Om true används arbetsbladet för att lagra kategorier (detta fall stöder flernivåkategorier). Om false används arbetsbladet INTE för att lagra värden (och detta fall stöder inte flernivåkategorier). Läs/skriv boolean.

**Returnerar:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

Om true används arbetsbladet för att lagra kategorier (detta fall stöder flernivåkategorier). Om false används arbetsbladet INTE för att lagra värden (och detta fall stöder inte flernivåkategorier). Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

Returnerar antalet nivåer för kategorigruppering som används. Är fler än ett för flernivåkategorier. Läs-endast int.

**Returnerar:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

Om kategorin finns i samlingen, returnera den. Annars skapas en ny diagramkategori från [IChartDataCell](../../com.aspose.slides/ichartdatacell) och läggs till i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell som används för att skapa diagramkategori. |

**Returnerar:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Tillagd eller befintlig kategori.
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

Skapar ny [IChartCategory](../../com.aspose.slides/ichartcategory) från värdet och lägger till den i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Object | Värdet.

--------------------

Denna metod lägger till ett arbetsblad med namnet AUTO_DATA och lägger till alla värden där. Om du använder [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) för att lägga till eller redigera cellvärden, se till att du inte använder detta arbetsblad. Maximalt antal värden som kan läggas till med denna metod får inte överstiga 16711680 |

**Returnerar:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Tillagd [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

Söker efter den angivna [IChartCategory](../../com.aspose.slides/ichartcategory) och returnerar det nollbaserade indexet för den första förekomsten i hela Collection

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Diagramkategori. |

**Returnerar:**
int - Det nollbaserade indexet för den första förekomsten av värdet i hela CollectionBase, om det finns; annars -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

Tar bort det angivna värdet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Värdet.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort elementet på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en kategori som ska tas bort.

### clear() {#clear--}
```
public abstract void clear()
```

Tar bort alla element från samlingen.