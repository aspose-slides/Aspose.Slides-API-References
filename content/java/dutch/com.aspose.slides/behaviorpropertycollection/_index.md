---
title: BehaviorPropertyCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt timing-eigenschappen voor het effectgedrag voor.
type: docs
url: /nl/com.aspose.slides/behaviorpropertycollection/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

Stelt timing-eigenschappen voor het effectgedrag voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Retourneert het aantal eigenschappen dat in de collectie is opgeslagen. |
| [isReadOnly()](#isReadOnly--) | Haalt een waarde op die aangeeft of de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | Voegt een nieuwe eigenschap toe aan de collectie. |
| [add(String propertyValue)](#add-java.lang.String-) | Voegt een nieuwe eigenschap toe aan de collectie. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | Bepaalt de index van een specifiek item in de lijst. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Bepaalt de index van een specifiek item op basis van de eigenschapswaarde in de lijst. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | Voegt een nieuwe eigenschap toe aan de collectie op de opgegeven index. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Voegt een nieuwe eigenschap (met de opgegeven eigenschapswaarde) toe aan de collectie op de opgegeven index. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | Kopieert de elementen van de [IGenericCollection](../../com.aspose.slides/igenericcollection) naar een array, beginnend bij een bepaalde array-index. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | Verwijdert opgegeven eigenschap uit de collectie. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Verwijdert opgegeven eigenschap uit de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert eigenschap op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle eigenschappen uit de collectie. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat. |
| [get_Item(int index)](#get-Item-int-) | Retourneert een eigenschap op de opgegeven index. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | Stelt een eigenschap in op de opgegeven index. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie iterereert. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de gehele collectie. |
### size() {#size--}
```
public final int size()
```

Retourneert het aantal eigenschappen dat in de collectie is opgeslagen. Alleen-lezen int.

**Retour:**  
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Haalt een waarde op die aangeeft of de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is. Alleen-lezen boolean.

**Retour:**  
boolean - waar als de [IGenericCollection](../../com.aspose.slides/igenericcollection) alleen-lezen is; anders onwaar.
### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

Voegt een nieuwe eigenschap toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Eigenschap om toe te voegen. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

Voegt een nieuwe eigenschap toe aan de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propertyValue | java.lang.String | Waarde van de toe te voegen eigenschap. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```

Bepaalt de index van een specifiek item in de lijst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Het object om te vinden in de lijst. |

**Retour:**  
int - De index van het item als het gevonden is in de lijst; anders -1.
### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

Bepaalt de index van een specifiek item op basis van de eigenschapswaarde in de lijst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propertyValue | java.lang.String | Waarde van de eigenschap |

**Retour:**  
int - De index van de eigenschap met de opgegeven waarde
### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

Voegt een nieuwe eigenschap toe aan de collectie op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index waar een nieuwe eigenschap moet worden ingevoegd. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Eigenschap om toe te voegen. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

Voegt een nieuwe eigenschap (met de opgegeven eigenschapswaarde) toe aan de collectie op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index waar een nieuwe eigenschap moet worden ingevoegd. |
| propertyValue | java.lang.String | Waarde van de toe te voegen eigenschap. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

Kopieert de elementen van de [IGenericCollection](../../com.aspose.slides/igenericcollection) naar een array, beginnend bij een bepaalde array-index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | De eendimensionale array die de bestemming is van de gekopieerde elementen van [IGenericCollection](../../com.aspose.slides/igenericcollection). De array moet nulgebaseerde indexering hebben. |
| arrayIndex | int | De nulgebaseerde index in de array waarop het kopiëren begint. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

Verwijdert opgegeven eigenschap uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Eigenschap om te verwijderen. |

**Retour:**  
boolean
### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

Verwijdert opgegeven eigenschap uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propertyValue | java.lang.String | Waarde van de te verwijderen eigenschap. |

**Retour:**  
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert eigenschap op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van de eigenschap die moet worden verwijderd. |

### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle eigenschappen uit de collectie.

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```

Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | De eigenschap om te vinden in de [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retour:**  
boolean - waar als item gevonden is in de [IGenericCollection](../../com.aspose.slides/igenericcollection); anders onwaar.
### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

Bepaalt of de [IGenericCollection](../../com.aspose.slides/igenericcollection) een specifieke waarde bevat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propertyValue | java.lang.String | Waarde van de eigenschap om te vinden in de [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retour:**  
boolean - waar als propertyValue gevonden is in de [IGenericCollection](../../com.aspose.slides/igenericcollection); anders onwaar.
### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

Retourneert een eigenschap op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een eigenschap om te retourneren. |

**Retour:**  
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - Animatiegedragseigenschap.
### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

Stelt een eigenschap in op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een eigenschap om te retourneren. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

Retourneert een enumerator die door de collectie iterereert.

**Retour:**  
com.aspose.ms System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Retour:**  
int
### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Retour:**  
boolean
### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Retour:**  
boolean
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```

Retourneert een java-iterator voor de gehele collectie.

**Retour:**  
com.aspose.ms System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - Een java.util.Iterator voor de gehele collectie.