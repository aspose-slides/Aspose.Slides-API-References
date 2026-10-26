---
title: IChartCategoryCollection
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt eine Sammlung von dar
type: docs
url: /de/com.aspose.slides/ichartcategorycollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

Stellt eine Sammlung von [IChartCategory](../../com.aspose.slides/ichartcategory) dar
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Liefert das Element am angegebenen Index. |
| [getUseCells()](#getUseCells--) | Wenn true dann wird das Arbeitsblatt zur Speicherung von Kategorien verwendet (dieser Fall unterstützt mehrstufige Kategorien). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Wenn true dann wird das Arbeitsblatt zur Speicherung von Kategorien verwendet (dieser Fall unterstützt mehrstufige Kategorien). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Gibt die Anzahl der verwendeten Gruppierungsebenen für Kategorien zurück. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Wenn die Kategorie in der Sammlung existiert, wird sie zurückgegeben. |
| [add(Object value)](#add-java.lang.Object-) | Erstellt ein neues [IChartCategory](../../com.aspose.slides/ichartcategory) aus dem Wert und fügt es der Sammlung hinzu. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Durchsucht die angegebene [IChartCategory](../../com.aspose.slides/ichartcategory) und gibt den nullbasierten Index des ersten Vorkommens in der gesamten Collection zurück |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Entfernt den angegebenen Wert. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

Liefert das Element am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Das Element am angegebenen Index.

### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

Wenn true dann wird das Arbeitsblatt zur Speicherung von Kategorien verwendet (dieser Fall unterstützt mehrstufige Kategorien). Wenn false dann wird das Arbeitsblatt NICHT zur Speicherung von Werten verwendet (und dieser Fall unterstützt keine mehrstufigen Kategorien). Lese/Schreib-Boolean.

**Rückgabe:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

Wenn true dann wird das Arbeitsblatt zur Speicherung von Kategorien verwendet (dieser Fall unterstützt mehrstufige Kategorien). Wenn false dann wird das Arbeitsblatt NICHT zur Speicherung von Werten verwendet (und dieser Fall unterstützt keine mehrstufigen Kategorien). Lese/Schreib-Boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

Gibt die Anzahl der verwendeten Gruppierungsebenen für Kategorien zurück. Ist bei mehrstufigen Kategorien größer als eins. Nur lesbarer int.

**Rückgabe:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

Wenn die Kategorie in der Sammlung existiert, wird sie zurückgegeben. Andernfalls wird eine neue Diagrammkategorie aus [IChartDataCell](../../com.aspose.slides/ichartdatacell) erstellt und zur Sammlung hinzugefügt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Zelle, die zum Erstellen der Diagrammkategorie verwendet wird. |

**Rückgabe:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Hinzugefügte oder vorhandene Kategorie.

### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

Erstellt ein neues [IChartCategory](../../com.aspose.slides/ichartcategory) aus dem Wert und fügt es der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object | Der Wert. |

--------------------

Diese Methode fügt ein Arbeitsblatt mit dem Namen AUTO_DATA hinzu und legt dort alle Werte ab. Wenn Sie [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) zum Hinzufügen oder Bearbeiten von Zellwerten verwenden, stellen Sie sicher, dass Sie dieses Arbeitsblatt nicht benutzen. Die maximale Anzahl von Werten, die mit dieser Methode hinzugefügt werden dürfen, darf 16711680 nicht überschreiten |

**Rückgabe:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Hinzugefügtes [IChartCategory](../../com.aspose.slides/ichartcategory).

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

Durchsucht die angegebene [IChartCategory](../../com.aspose.slides/ichartcategory) und gibt den nullbasierten Index des ersten Vorkommens in der gesamten Collection zurück

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Diagrammkategorie. |

**Rückgabe:**
int - Der nullbasierte Index des ersten Vorkommens des Wertes in der gesamten CollectionBase, falls gefunden; sonst -1.

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

Entfernt den angegebenen Wert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Der Wert. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Entfernt das Element am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der zu entfernenden Kategorie. |

### clear() {#clear--}
```
public abstract void clear()
```

Entfernt alle Elemente aus der Sammlung.