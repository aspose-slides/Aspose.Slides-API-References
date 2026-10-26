---
title: ChartCategoryCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een collectie van
type: docs
url: /nl/com.aspose.slides/chartcategorycollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

Represents collection of [ChartCategory](../../com.aspose.slides/chartcategory)
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op de opgegeven index op. |
| [getUseCells()](#getUseCells--) | Als true wordt het werkblad gebruikt voor het opslaan van categorieën (dit geval ondersteunt meerlagige categorieën). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Als true wordt het werkblad gebruikt voor het opslaan van categorieën (dit geval ondersteunt meerlagige categorieën). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Retourneert het aantal gebruikte groeperingsniveaus voor categorieën. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Als de categorie bestaat in de collectie, retourneer deze. |
| [add(Object value)](#add-java.lang.Object-) | Maakt een nieuwe [ChartCategory](../../com.aspose.slides/chartcategory) van de waarde en voegt deze toe aan de collectie. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Zoekt naar de opgegeven [ChartCategory](../../com.aspose.slides/chartcategory) en retourneert de nulgebaseerde index van de eerste keer dat deze voorkomt in de volledige collectie. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Verwijdert de opgegeven waarde. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle elementen uit de collectie. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een Java-iterator voor de volledige collectie. |
| [size()](#size--) | Retourneert een aantal elementen in de collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen van de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de lijst gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een object dat kan worden gebruikt om de toegang tot de collectie te synchroniseren. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```

Haalt het element op de opgegeven index op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourneert:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Het element op de opgegeven index.

### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```

Als true wordt het werkblad gebruikt voor het opslaan van categorieën (dit geval ondersteunt meerlagige categorieën). Als false wordt het werkblad NIET gebruikt voor het opslaan van waarden (en dit geval ondersteunt geen meerlagige categorieën). Lees/schrijf boolean.

**Retourneert:**
boolean

### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```

Als true wordt het werkblad gebruikt voor het opslaan van categorieën (dit geval ondersteunt meerlagige categorieën). Als false wordt het werkblad NIET gebruikt voor het opslaan van waarden (en dit geval ondersteunt geen meerlagige categorieën). Lees/schrijf boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```

Retourneert het aantal gebruikte groeperingsniveaus voor categorieën. Is meer dan één voor meerlagige categorieën. Alleen-lezen int.

**Retourneert:**
int

### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```

Als de categorie bestaat in de collectie, retourneer deze. Anders maakt het een nieuwe diagramcategorie van [IChartDataCell](../../com.aspose.slides/ichartdatacell) en voegt deze toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cel gebruikt om een diagramcategorie te maken. |

**Retourneert:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Toegevoegde of bestaande categorie.

### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```

Maakt een nieuwe [ChartCategory](../../com.aspose.slides/chartcategory) van de waarde en voegt deze toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Object | De waarde. |

--------------------

Deze methode voegt een werkblad toe met de naam AUTO_DATA en voegt daar alle waarden toe. Als je [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) gebruikt om celwaarden toe te voegen of te bewerken, zorg er dan voor dat je dit werkblad niet gebruikt. Het maximale aantal waarden dat met deze methode wordt toegevoegd mag 16711680 niet overschrijden. |

**Retourneert:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Toegevoegde [IChartCategory](../../com.aspose.slides/ichartcategory).

### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```

Zoekt naar de opgegeven [ChartCategory](../../com.aspose.slides/chartcategory) en retourneert de nulgebaseerde index van de eerste keer dat deze voorkomt in de gehele collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Diagramcategorie. |

**Retourneert:**
int - De nulgebaseerde index van de eerste keer dat de waarde voorkomt in de gehele CollectionBase, indien gevonden; anders -1.

### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```

Verwijdert de opgegeven waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | De waarde. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert het element op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een te verwijderen categorie. |

### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle elementen uit de collectie.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```

Retourneert een enumerator die door de collectie iterereert.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```

Retourneert een Java-iterator voor de volledige collectie.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - Een java.util.Iterator voor de volledige collectie.

### size() {#size--}
```
public final int size()
```

Retourneert een aantal elementen in de collectie. Alleen-lezen int.

**Retourneert:**
int

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopieert alle elementen van de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doelarray. |
| index | int | Startindex in de array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourneert een waarde die aangeeft of de toegang tot de lijst gesynchroniseerd is (thread-safe). Alleen-lezen boolean.

**Retourneert:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een object dat kan worden gebruikt om de toegang tot de collectie te synchroniseren. Alleen-lezen Object.

Retourneert een synchronisatieroot. Alleen-lezen Object.

**Retourneert:**
java.lang.Object