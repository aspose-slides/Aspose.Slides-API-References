---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt timing-eigenschappen voor het effectgedrag voor.
type: docs
url: /nl/com.aspose.slides/ibehaviorpropertycollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

Stelt timing-eigenschappen voor het effectgedrag voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | Voegt een nieuwe eigenschap toe aan de collectie. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Bepaalt de index van een specifiek item op basis van de eigenschapswaarde in de lijst. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Voegt een nieuwe eigenschap (met de opgegeven eigenschapswaarde) toe aan de collectie op de opgegeven index. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Verwijdert de opgegeven eigenschap uit de collectie. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```


Voegt een nieuwe eigenschap toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propertyValue | java.lang.String | Waarde van de toe te voegen eigenschap. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```


Bepaalt de index van een specifiek item op basis van de eigenschapswaarde in de lijst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propertyValue | java.lang.String | waarde van de eigenschap |

**Returns:**
int - De index van de eigenschap met de opgegeven waarde
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```


Voegt een nieuwe eigenschap (met de opgegeven eigenschapswaarde) toe aan de collectie op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index waarop een nieuwe eigenschap moet worden ingevoegd. |
| propertyValue | java.lang.String | Waarde van de eigenschap om toe te voegen. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```


Verwijdert de opgegeven eigenschap uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propertyValue | java.lang.String | Waarde van de te verwijderen eigenschap. |

**Returns:**
boolean - True if a property removed successfully boolean
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```


Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propertyValue | java.lang.String | Waarde van de eigenschap om te zoeken in de [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returns:**
boolean - true if propertyValue is found in the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false.