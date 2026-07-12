---
title: BehaviorPropertyCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt Zeiteneigenschaften für das Effektverhalten dar.
type: docs
url: /de/com.aspose.slides/behaviorpropertycollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

Stellt Zeiteneigenschaften für das Effektverhalten dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Gibt die Anzahl der in der Sammlung gespeicherten Eigenschaften zurück. |
| [isReadOnly()](#isReadOnly--) | Ermittelt einen Wert, der angibt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) schreibgeschützt ist. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | Fügt der Sammlung eine neue Eigenschaft hinzu. |
| [add(String propertyValue)](#add-java.lang.String-) | Fügt der Sammlung eine neue Eigenschaft hinzu. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | Bestimmt den Index eines bestimmten Elements in der Liste. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Bestimmt den Index eines bestimmten Elements anhand des Eigenschaftswerts in der Liste. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | Fügt der Sammlung an der angegebenen Position eine neue Eigenschaft ein. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Fügt der Sammlung an der angegebenen Position eine neue Eigenschaft (mit dem angegebenen Eigenschaftswert) ein. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | Kopiert die Elemente von [IGenericCollection](../../com.aspose.slides/igenericcollection) in ein Array, beginnend bei einem bestimmten Array-Index. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | Entfernt die angegebene Eigenschaft aus der Sammlung. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Entfernt die angegebene Eigenschaft aus der Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt die Eigenschaft am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Eigenschaften aus der Sammlung. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | Bestimmt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Bestimmt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält. |
| [get_Item(int index)](#get-Item-int-) | Gibt eine Eigenschaft am angegebenen Index zurück. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | Setzt eine Eigenschaft am angegebenen Index. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |

### size() {#size--}
```
public final int size()
```

Gibt die Anzahl der in der Sammlung gespeicherten Eigenschaften zurück. Nur-Lese int.

**Rückgabe:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

Ermittelt einen Wert, der angibt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) schreibgeschützt ist. Nur-Lese boolean.

**Rückgabe:**
boolean - true, wenn [IGenericCollection](../../com.aspose.slides/igenericcollection) schreibgeschützt ist; andernfalls false.

### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

Fügt der Sammlung eine neue Eigenschaft hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Hinzuzufügende Eigenschaft. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

Fügt der Sammlung eine neue Eigenschaft hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propertyValue | java.lang.String | Wert der hinzuzufügenden Eigenschaft. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```

Bestimmt den Index eines bestimmten Elements in der Liste.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Das in der Liste zu suchende Objekt. |

**Rückgabe:**
int - Der Index des Elements, falls in der Liste gefunden; andernfalls -1.

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

Bestimmt den Index eines bestimmten Elements anhand des Eigenschaftswerts in der Liste.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propertyValue | java.lang.String | Wert der gesuchten Eigenschaft |

**Rückgabe:**
int - Der Index der Eigenschaft mit dem angegebenen Wert

### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

Fügt der Sammlung an dem angegebenen Index eine neue Eigenschaft ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index, an dem eine neue Eigenschaft eingefügt werden soll. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Hinzuzufügende Eigenschaft. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

Fügt der Sammlung an dem angegebenen Index eine neue Eigenschaft (mit dem angegebenen Eigenschaftswert) ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index, an dem eine neue Eigenschaft eingefügt werden soll. |
| propertyValue | java.lang.String | Wert der hinzuzufügenden Eigenschaft. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

Kopiert die Elemente von [IGenericCollection](../../com.aspose.slides/igenericcollection) in ein Array, beginnend bei einem bestimmten Array-Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | Das eindimensionale Array, das Ziel der von [IGenericCollection](../../com.aspose.slides/igenericcollection) kopierten Elemente ist. Das Array muss nullbasiert indiziert sein. |
| arrayIndex | int | Der nullbasierte Index im Array, an dem das Kopieren beginnt. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

Entfernt die angegebene Eigenschaft aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Zu entfernende Eigenschaft. |

**Rückgabe:**
boolean

### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

Entfernt die angegebene Eigenschaft aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propertyValue | java.lang.String | Wert der zu entfernenden Eigenschaft. |

**Rückgabe:**
boolean

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt die Eigenschaft am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der zu löschenden Eigenschaft. |

### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Eigenschaften aus der Sammlung.

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```

Bestimmt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Die zu suchende Eigenschaft in [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Rückgabe:**
boolean - true, wenn das Element in [IGenericCollection](../../com.aspose.slides/igenericcollection) gefunden wird; andernfalls false.

### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

Bestimmt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| propertyValue | java.lang.String | Wert der zu suchenden Eigenschaft in [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Rückgabe:**
boolean - true, wenn propertyValue in [IGenericCollection](../../com.aspose.slides/igenericcollection) gefunden wird; andernfalls false.

### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

Gibt eine Eigenschaft am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der zurückzugebenden Eigenschaft. |

**Rückgabe:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - Animationsverhaltenseigenschaft.

### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

Setzt eine Eigenschaft am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der zu setzenden Eigenschaft. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.

### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Rückgabe:**
int

### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Rückgabe:**
boolean

### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Rückgabe:**
boolean

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - Ein java.util.Iterator für die gesamte Sammlung.