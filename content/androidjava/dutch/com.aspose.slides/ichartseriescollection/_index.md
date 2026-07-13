---
title: IChartSeriesCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie voor van
type: docs
url: /nl/com.aspose.slides/ichartseriescollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

Stelt een collectie voor van [IChartSeries](../../com.aspose.slides/ichartseries)
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [add(int type)](#add-int-) | Maakt een nieuwe grafiekreeks aan en voegt deze toe aan de collectie. |
| [insert(int index, int type)](#insert-int-int-) | Maakt een nieuwe grafiekreeks aan en voegt deze in de collectie in. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | Maakt een nieuwe grafiekreeks aan van [IChartDataCell](../../com.aspose.slides/ichartdatacell) en voegt deze toe aan de collectie. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | Maakt een nieuwe grafiekreeks aan van [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) en voegt deze toe aan de collectie. |
| [add(String name, int type)](#add-java.lang.String-int-) | Maakt een nieuwe grafiekreeks aan van een waarde en voegt deze toe aan de collectie. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | Zoekt naar de opgegeven [IChartSeries](../../com.aspose.slides/ichartseries) en geeft de nulgebaseerde index van de eerste voorkoming in de volledige Collection terug. |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | Verwijdert de opgegeven waarde. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle elementen (inclusief de grafiekstijl) uit de collectie. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Haalt het element op op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Het element op de opgegeven index.
### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

Maakt een nieuwe grafiekreeks aan en voegt deze toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | int | Type van serie |

**Retour:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nieuwe grafiekreeks.
### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

Maakt een nieuwe grafiekreeks aan en voegt deze in de collectie in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index voor invoeging int |
| type | int | Grafiektype [ChartType](../../com.aspose.slides/charttype) |

**Retour:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Nieuwe grafiekreeks [IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

Maakt een nieuwe grafiekreeks aan van [IChartDataCell](../../com.aspose.slides/ichartdatacell) en voegt deze toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cel die de serienaam bevat. |
| type | int | Type van serie |

--------------------

Als een grafiekreeks al uit dezelfde cel bestaat in de collectie, voegt de methode niets toe en retourneert het index. |

**Retour:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Toegevoegde grafiekreeks of reeks die al in de collectie zit.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

Maakt een nieuwe grafiekreeks aan van [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) en voegt deze toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | Cellen die de serienaam bevatten. |
| type | int | Type van serie |

--------------------

Als een grafiekreeks al uit dezelfde cel bestaat in de collectie, voegt de methode niets toe en retourneert het index. |

**Retour:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Toegevoegde grafiekreeks of reeks die al in de collectie zit.
### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

Maakt een nieuwe grafiekreeks aan van een waarde en voegt deze toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Serienaam. |
| type | int | Type van serie |

**Retour:**
[IChartSeries](../../com.aspose.slides/ichartseries) - Toegevoegde grafiekreeks.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

Zoekt naar de opgegeven [IChartSeries](../../com.aspose.slides/ichartseries) en geeft de nulgebaseerde index van de eerste voorkoming in de volledige Collection terug.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | Grafiekreekswaarde. |

**Retour:**
int - De nulgebaseerde index van de eerste voorkoming van value binnen de gehele CollectionBase, indien gevonden; anders -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

Verwijdert de opgegeven waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | De waarde. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert het element op de opgegeven index

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index int |

### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle elementen (inclusief de grafiekstijl) uit de collectie.