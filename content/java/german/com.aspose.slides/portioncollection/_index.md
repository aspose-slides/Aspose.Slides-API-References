---
title: PortionCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von Portionen dar.
type: docs
url: /de/com.aspose.slides/portioncollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

Stellt eine Sammlung von Portion-Objekten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCount()](#getCount--) | Gibt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen zurück. |
| [isReadOnly()](#isReadOnly--) | Gibt einen Wert zurück, der angibt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) schreibgeschützt ist. |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | Gibt das Element am angegebenen Index zurück. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Fügt eine Portion am Ende der Sammlung hinzu. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Ermittelt den Index eines bestimmten Elements in der Liste. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Fügt eine Portion in die Sammlung an dem angegebenen Index ein. |
| [clear()](#clear--) | Entfernt alle Elemente aus der Sammlung. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Ermittelt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | Kopiert die Elemente von [IGenericCollection](../../com.aspose.slides/igenericcollection) in ein Array, beginnend bei einem bestimmten Array-Index. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus dem [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index der Sammlung. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
### getCount() {#getCount--}
```
public final int getCount()
```


Gibt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen zurück. Nur-Lese int.

**Rückgabe:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Gibt einen Wert zurück, der angibt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) schreibgeschützt ist. Nur-Lese boolean.

**Rückgabe:**
boolean – true, wenn [IGenericCollection](../../com.aspose.slides/igenericcollection) schreibgeschützt ist; andernfalls false.
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```


Gibt das Element am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IPortion](../../com.aspose.slides/iportion)
### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```


Gibt das Element am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```


Fügt eine Portion am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Die hinzuzufügende Portion am Ende der Sammlung. |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```


Ermittelt den Index eines bestimmten Elements in der Liste.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Das zu findende Objekt in der Liste. |

**Rückgabe:**
int – Der Index des Elements, wenn es in der Liste gefunden wurde; andernfalls -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```


Fügt eine Portion in die Sammlung an dem angegebenen Index ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Portion eingefügt werden soll. |
| value | [IPortion](../../com.aspose.slides/iportion) | Die einzufügende Portion. |
### clear() {#clear--}
```
public final void clear()
```


Entfernt alle Elemente aus der Sammlung.
### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```


Ermittelt, ob [IGenericCollection](../../com.aspose.slides/igenericcollection) einen bestimmten Wert enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Das zu findende Objekt im [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Rückgabe:**
boolean – true, wenn das Element im [IGenericCollection](../../com.aspose.slides/igenericcollection) gefunden wurde; andernfalls false.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```


Kopiert die Elemente von [IGenericCollection](../../com.aspose.slides/igenericcollection) in ein Array, beginnend bei einem bestimmten Array-Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | Das eindimensionale Array, das das Ziel für die von [IGenericCollection](../../com.aspose.slides/igenericcollection) kopierten Elemente ist. Das Array muss nullbasiert indiziert sein. |
| arrayIndex | int | Der nullbasierte Index im Array, bei dem das Kopieren beginnt. |
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```


Entfernt das erste Vorkommen eines bestimmten Objekts aus dem [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Das zu entfernende Objekt aus dem [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Rückgabe:**
boolean – true, wenn das Element erfolgreich aus dem [IGenericCollection](../../com.aspose.slides/igenericcollection) entfernt wurde; andernfalls false. Diese Methode gibt ebenfalls false zurück, wenn das Element im ursprünglichen [IGenericCollection](../../com.aspose.slides/igenericcollection) nicht gefunden wird.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Entfernt das Element am angegebenen Index der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```


Gibt einen Enumerator zurück, der durch die Sammlung iteriert.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> – Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```


Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> – Ein java.util.Iterator für die gesamte Sammlung.