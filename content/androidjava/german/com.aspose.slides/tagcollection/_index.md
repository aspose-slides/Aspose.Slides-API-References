---
title: TagCollection
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt die Sammlung von Tags dar, benutzerdefinierte Paare von Zeichenketten
type: docs
url: /de/com.aspose.slides/tagcollection/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

Stellt die Sammlung von Tags (benutzerdefinierte Paarungen von Zeichenketten) dar

--------------------

> ```
> Das folgende Beispiel zeigt, wie ein Tag zu einer PowerPoint-Präsentation hinzugefügt wird.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ITagCollection tags = pres.getCustomData().getTags();
>      pres.getCustomData().getTags().add("MyTag", "My Tag Value");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Gibt die Anzahl der Tags in der Sammlung zurück. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Fügt der Sammlung ein neues Tag hinzu. |
| [remove(String name)](#remove-java.lang.String-) | Entfernt das Tag mit einem angegebenen Namen aus der Sammlung. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Gibt den nullbasierten Index des angegebenen Schlüssels in der Sammlung zurück. |
| [contains(String name)](#contains-java.lang.String-) | Ermittelt, ob die Sammlung einen bestimmten Namen enthält. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Tag am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Tags aus der Sammlung. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Gibt den Wert eines Tags am angegebenen Index zurück. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Gibt den Schlüssel eines Tags am angegebenen Index zurück. |
| [getNamesOfTags()](#getNamesOfTags--) | Gibt die Namen der Tags zurück. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gibt ein Schlüssel-Wert-Paar eines Tags zurück oder setzt es. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Gibt ein Schlüssel-Wert-Paar eines Tags zurück oder setzt es. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt eine Synchronisationswurzel zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [iteratorJava()](#iteratorJava--) | Gibt einen java iterator für die gesamte Sammlung zurück. |
### size() {#size--}
```
public final int size()
```


Gibt die Anzahl der Tags in der Sammlung zurück. Nur lesend int.

**Rückgabe:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```


Fügt der Sammlung ein neues Tag hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Der Name des Tags. |
| value | java.lang.String | Der Wert des Tags. |

**Rückgabe:**
int - Der Index des hinzugefügten Tags.
### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```


Entfernt das Tag mit einem angegebenen Namen aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Der Name des zu entfernenden Tags. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```


Gibt den nullbasierten Index des angegebenen Schlüssels in der Sammlung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Der zu findende Name in der Sammlung. |

**Rückgabe:**
int - Der nullbasierte Index des Schlüssels, wenn der Schlüssel in der Sammlung gefunden wird; andernfalls -1.
### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


Ermittelt, ob die Sammlung einen bestimmten Namen enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Der zu suchende Schlüssel. |

**Rückgabe:**
boolean - Wahr, wenn die Sammlung ein Tag mit dem angegebenen Schlüssel enthält; andernfalls falsch.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Entfernt das Tag am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Tags. |
### clear() {#clear--}
```
public final void clear()
```


Entfernt alle Tags aus der Sammlung.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```


Gibt den Wert eines Tags am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index eines Tags, der zurückgegeben werden soll. |

**Rückgabe:**
java.lang.String - Wert eines Tags.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```


Gibt den Schlüssel eines Tags am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index eines Tags, der zurückgegeben werden soll. |

**Rückgabe:**
java.lang.String - Schlüssel eines Tags.
### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```


Gibt die Namen der Tags zurück.

**Rückgabe:**
java.lang.String[] - Namen der Tags.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```


Gibt ein Schlüssel-Wert-Paar eines Tags zurück oder setzt es.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Schlüssel eines Tags. |

**Rückgabe:**
java.lang.String - Wert eines Tags.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```


Gibt ein Schlüssel-Wert-Paar eines Tags zurück oder setzt es.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Schlüssel eines Tags. |
| value | java.lang.String |  |
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiert alle Elemente der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Zu füllendes Array. |
| index | int | Startposition im Zielarray. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. Nur lesend boolean.

**Rückgabe:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Gibt eine Synchronisationswurzel zurück. Nur lesend Object.

**Rückgabe:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```


Gibt einen Enumerator zurück, der durch die Sammlung iteriert.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```


Gibt einen java iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - Ein java.util.Iterator für die gesamte Sammlung.