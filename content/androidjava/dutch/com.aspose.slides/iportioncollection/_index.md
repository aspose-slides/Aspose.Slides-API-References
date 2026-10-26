---
title: IPortionCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van delen voor.
type: docs
url: /nl/com.aspose.slides/iportioncollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Stelt een collectie van delen voor.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [getCount()](#getCount--) | Haalt het aantal elementen op dat werkelijk in de collectie aanwezig is. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Voegt een Portion toe aan het einde van de collectie. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Bepaalt de index van een specifiek gedeelte in de collectie. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Voegt een Portion in de collectie in op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle elementen uit de collectie. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Verwijdert de eerste voorkoming van een specifiek object uit de [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index van de collectie. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

Haalt het element op op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IPortion](../../com.aspose.slides/iportion)

### getCount() {#getCount--}
```
public abstract int getCount()
```

Haalt het aantal elementen op dat werkelijk in de collectie aanwezig is. Alleen-lezen int.

**Retour:**
int

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

Voegt een Portion toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | De Portion die aan het einde van de collectie wordt toegevoegd. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

Bepaalt de index van een specifiek gedeelte in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Het gedeelte dat in de collectie moet worden gevonden. |

**Retour:**
int - De index van item als deze wordt gevonden in de collectie; anders -1.

### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

Voegt een Portion in de collectie in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index waarop de Portion moet worden ingevoegd. |
| value | [IPortion](../../com.aspose.slides/iportion) | De in te voegen Portion. |

### clear() {#clear--}
```
public abstract void clear()
```

Verwijdert alle elementen uit de collectie.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```

Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Het object dat moet worden gevonden in de [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retour:**
boolean - true als item wordt gevonden in de [IGenericCollection](../../com.aspose.slides/igenericcollection); anders false.

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

Verwijdert de eerste voorkoming van een specifiek object uit de [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Het object dat moet worden verwijderd uit de [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retour:**
boolean - true als item met succes is verwijderd uit de [IGenericCollection](../../com.aspose.slides/igenericcollection); anders false. Deze methode retourneert ook false als item niet wordt gevonden in de oorspronkelijke [IGenericCollection](../../com.aspose.slides/igenericcollection).

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert het element op de opgegeven index van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het element dat moet worden verwijderd. |