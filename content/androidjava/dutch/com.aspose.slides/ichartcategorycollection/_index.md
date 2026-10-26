---
title: IChartCategoryCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie voor van
type: docs
url: /nl/com.aspose.slides/ichartcategorycollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

Stelt een collectie voor van [IChartCategory](../../com.aspose.slides/ichartcategory)
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [getUseCells()](#getUseCells--) | Als true, wordt werkblad gebruikt voor het opslaan van categorieën (dit geval ondersteunt meervoudige niveaus van categorieën). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | Als true, wordt werkblad gebruikt voor het opslaan van categorieën (dit geval ondersteunt meervoudige niveaus van categorieën). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Retourneert het aantal gebruikte groeperingsniveaus voor categorieën. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | Als de categorie bestaat in de collectie, retourneer deze. |
| [add(Object value)](#add-java.lang.Object-) | Maakt een nieuwe [IChartCategory](../../com.aspose.slides/ichartcategory) van de waarde en voegt deze toe aan de collectie. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Zoekt naar de gespecificeerde [IChartCategory](../../com.aspose.slides/ichartcategory) en retourneert de nulgebaseerde index van de eerste vondst binnen de gehele collectie |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Verwijdert de opgegeven waarde. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle elementen uit de collectie. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
```

Haalt het element op op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourneert:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Het element op de opgegeven index.
### getUseCells() {#getUseCells--}
```
public abstract boolean getUseCells()
```

Als true, wordt het werkblad gebruikt voor het opslaan van categorieën (dit geval ondersteunt meervoudige niveaus van categorieën). Als false, wordt het werkblad NIET gebruikt voor het opslaan van waarden (en dit geval ondersteunt geen meervoudige niveaus van categorieën). Lees/schrijf boolean.

**Retourneert:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```

Als true, wordt het werkblad gebruikt voor het opslaan van categorieën (dit geval ondersteunt meervoudige niveaus van categorieën). Als false, wordt het werkblad NIET gebruikt voor het opslaan van waarden (en dit geval ondersteunt geen meervoudige niveaus van categorieën). Lees/schrijf boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```

Retourneert het aantal gebruikte groeperingsniveaus voor categorieën. Is meer dan één voor meervoudige categorieën. Alleen-lezen int.

**Retourneert:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
```

Als de categorie bestaat in de collectie, retourneer deze. Anders maakt het een nieuwe grafiekcategorie aan van [IChartDataCell](../../com.aspose.slides/ichartdatacell) en voegt deze toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cel die wordt gebruikt om een grafiekcategorie te maken. |

**Retourneert:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Toegevoegde of bestaande categorie.
### add(Object value) {#add-java.lang.Object-}
```
public abstract IChartCategory add(Object value)
```

Maakt een nieuwe [IChartCategory](../../com.aspose.slides/ichartcategory) van de waarde en voegt deze toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Object | De waarde.

--------------------

Deze methode voegt een werkblad toe met de naam AUTO_DATA en voegt daar alle waarden toe. Als je [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) gebruikt om celwaarden toe te voegen of te bewerken, zorg er dan voor dat je dit werkblad niet gebruikt. Het maximum aantal waarden dat met deze methode kan worden toegevoegd mag 16711680 niet overschrijden |

**Retourneert:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Toegevoegde [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```

Zoekt naar de gespecificeerde [IChartCategory](../../com.aspose.slides/ichartcategory) en retourneert de nulgebaseerde index van de eerste vondst binnen de gehele collectie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Grafiekcategorie. |

**Retourneert:**
int - De nulgebaseerde index van de eerste vondst van value binnen de gehele CollectionBase, indien gevonden; anders -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```

Verwijdert de opgegeven waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | De waarde. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert het element op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een categorie die verwijderd moet worden. |

### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle elementen uit de collectie.