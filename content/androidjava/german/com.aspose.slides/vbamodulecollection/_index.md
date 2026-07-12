---
title: VbaModuleCollection
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt eine Sammlung von VBA-Projektmodulen dar.
type: docs
url: /de/com.aspose.slides/vbamodulecollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

Stellt eine Sammlung von VBA-Projektmodulen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Gibt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen zurück. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Fügt dem VBA-Projekt ein neues leeres Modul hinzu. |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente aus der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (Thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt die Synchronisationswurzel zurück. |
### size() {#size--}
```
public final int size()
```


Gibt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen zurück. Nur lesend int.

**Rückgabe:**
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```


Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Das Modul, das aus der Sammlung entfernt werden soll. |
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```


Fügt dem VBA-Projekt ein neues leeres Modul hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name des Moduls |
**Rückgabe:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Hinzugefügtes Modul.
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```


Gibt das Element am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |
**Rückgabe:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```


Gibt einen Enumerator zurück, der durch die Sammlung iteriert.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```


Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - Ein java.util.Iterator für die gesamte Sammlung.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiert alle Elemente aus der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Ziel-Array. |
| index | int | Startindex im Ziel-Array. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (Thread-sicher) ist. Nur lesend boolean.

**Rückgabe:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Gibt die Synchronisationswurzel zurück. Nur lesend java.lang.Object.

**Rückgabe:**
java.lang.Object