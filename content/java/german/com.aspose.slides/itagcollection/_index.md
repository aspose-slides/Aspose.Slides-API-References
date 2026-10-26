---
title: ITagCollection
second_title: Aspose.Slides für Java API Referenz
description: Stellt die Sammlung von Tags dar, benutzerdefinierte Paare von Zeichenketten
type: docs
url: /de/com.aspose.slides/itagcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Stellt die Sammlung von Tags (benutzerdefinierte Schlüssel-Wert-Paare von Zeichenketten) dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Fügt der Sammlung ein neues Tag hinzu. |
| [remove(String name)](#remove-java.lang.String-) | Entfernt das Tag mit einem angegebenen Namen aus der Sammlung. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Gibt den nullbasierten Index des angegebenen Schlüssels in der Sammlung zurück. |
| [contains(String name)](#contains-java.lang.String-) | Bestimmt, ob die Sammlung einen bestimmten Namen enthält. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Tag am angegebenen Index. |
| [clear()](#clear--) | Entfernt alle Tags aus der Sammlung. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Gibt den Wert eines Tags am angegebenen Index zurück. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Gibt den Schlüssel eines Tags am angegebenen Index zurück. |
| [getNamesOfTags()](#getNamesOfTags--) | Gibt die Namen der Tags zurück. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gibt den Schlüssel und den Wert eines Tags zurück oder setzt diese. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Gibt den Schlüssel und den Wert eines Tags zurück oder setzt diese. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

Fügt der Sammlung ein neues Tag hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Der Name des Tags. |
| value | java.lang.String | Der Wert des Tags. |

**Rückgabewert:**
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
| name | java.lang.String | Der zu suchende Name in der Sammlung. |

**Rückgabewert:**
int - Der nullbasierte Index des Schlüssels, wenn der Schlüssel in der Sammlung gefunden wird; sonst -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

Bestimmt, ob die Sammlung einen bestimmten Namen enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Der zu suchende Schlüssel. |

**Rückgabewert:**
boolean - True, wenn die Sammlung ein Tag mit dem angegebenen Schlüssel enthält; sonst false.
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
| index | int | Index eines Tags, dessen Wert zurückgegeben wird. |

**Rückgabewert:**
java.lang.String - Wert eines Tags.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

Gibt den Schlüssel eines Tags am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index eines Tags, dessen Schlüssel zurückgegeben wird. |

**Rückgabewert:**
java.lang.String - Schlüssel eines Tags.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

Gibt die Namen der Tags zurück.

**Rückgabewert:**
java.lang.String[] - Namen der Tags.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

Gibt den Schlüssel und den Wert eines Tags zurück oder setzt diese.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Schlüssel eines Tags. |

**Rückgabewert:**
java.lang.String - Wert eines Tags.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

Gibt den Schlüssel und den Wert eines Tags zurück oder setzt diese.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Schlüssel eines Tags. |
| value | java.lang.String |  |