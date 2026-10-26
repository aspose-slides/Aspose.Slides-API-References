---
title: ExtraColorSchemeCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung zusätzlicher Farbschemata dar.
type: docs
url: /de/com.aspose.slides/extracolorschemecollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

Stellt eine Sammlung zusätzlicher Farbschemata dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Gibt die Anzahl der Elemente int der Sammlung zurück. |
| [get_Item(int index)](#get-Item-int-) | Gibt ein Farbschema anhand des Index zurück. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen java-Iterator für die gesamte Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der anzeigt, ob der Zugriff auf die ArrayList synchronisiert ist (Thread-sicher). |
| [getSyncRoot()](#getSyncRoot--) | Gibt ein Objekt zurück, das verwendet werden kann, um den Zugriff auf die Sammlung zu synchronisieren. |
### size() {#size--}
```
public final int size()
```


Gibt die Anzahl der Elemente int der Sammlung zurück. Nur lesbarer int.

**Rückgabe:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```


Gibt ein Farbschema anhand des Index zurück. Nur lesbarer [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Gibt ein Parent_Immediate-Objekt zurück. Nur lesbares IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```


Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```


Gibt einen java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiert alle Elemente der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Ziel-Array. |
| index | int | Startindex im Array. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Gibt einen Wert zurück, der anzeigt, ob der Zugriff auf die ArrayList synchronisiert ist (Thread-sicher). Nur lesbarer boolean.

**Rückgabe:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Gibt ein Objekt zurück, das verwendet werden kann, um den Zugriff auf die Sammlung zu synchronisieren. Nur lesbares Object.

Gibt eine Synchronisationswurzel zurück. Nur lesbares Object.

**Rückgabe:**
java.lang.Object