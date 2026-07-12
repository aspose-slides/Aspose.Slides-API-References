---
title: ITagCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt die Sammlung von Tags dar, die aus benutzerdefinierten Zeichenkettenpaaren bestehen
type: docs
url: /de/com.aspose.slides/itagcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Stellt die Sammlung von Tags (benutzerdefinierte Zeichenkettenpaare) dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Fügt ein neues Tag zur Sammlung hinzu. |
| [remove(String name)](#remove-java.lang.String-) | Entfernt das Tag mit einem angegebenen Namen aus der Sammlung. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Gibt den nullbasierten Index des angegebenen Schlüssels in der Sammlung zurück. |
| [contains(String name)](#contains-java.lang.String-) | Bestimmt, ob die Sammlung einen bestimmten Namen enthält. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Tag am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Tags aus der Sammlung. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Gibt den Wert eines Tags am angegebenen Index zurück. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Gibt den Schlüssel eines Tags am angegebenen Index zurück. |
| [getNamesOfTags()](#getNamesOfTags--) | Gibt die Namen der Tags zurück. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gibt ein Schlüssel-Wert-Paar eines Tags zurück oder setzt es. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Gibt ein Schlüssel-Wert-Paar eines Tags zurück oder setzt es. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

Fügt ein neues Tag zur Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Der Name des Tags. |
| value | java.lang.String | Der Wert des Tags. |

**Rückgabe:**
int - Der Index des hinzugefügten Tags.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Entfernt das Tag mit einem angegebenen Namen aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Der Name des zu entfernenden Tags. |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```

Gibt den nullbasierten Index des angegebenen Schlüssels in der Sammlung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Der Name, der in der Sammlung gesucht werden soll. |

**Rückgabe:**
int - Der nullbasierte Index des Schlüssels, falls der Schlüssel in der Sammlung gefunden wird; andernfalls -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

Bestimmt, ob die Sammlung einen bestimmten Namen enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Der zu suchende Schlüssel. |

**Rückgabe:**
boolean - Wahr, wenn die Sammlung ein Tag mit dem angegebenen Schlüssel enthält; andernfalls falsch.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Entfernt das Tag am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Tags. |
### clear() {#clear--}
```
public abstract void clear()
```

Entfernt alle Tags aus der Sammlung.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

Gibt den Wert eines Tags am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index eines zurückzugebenden Tags. |

**Rückgabe:**
java.lang.String - Wert eines Tags.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

Gibt den Schlüssel eines Tags am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index eines zurückzugebenden Tags. |

**Rückgabe:**
java.lang.String - Schlüssel eines Tags.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

Gibt die Namen der Tags zurück.

**Rückgabe:**
java.lang.String[] - Namen der Tags.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
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
public abstract void set_Item(String name, String value)
```

Gibt ein Schlüssel-Wert-Paar eines Tags zurück oder setzt es.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Schlüssel eines Tags. |
| value | java.lang.String |  |