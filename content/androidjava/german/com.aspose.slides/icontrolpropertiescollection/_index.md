---
title: IControlPropertiesCollection
second_title: Aspose.Slides für Android über die Java API Referenz
description: Eine Sammlung von ActiveX-Steuerelementen.
type: docs
url: /de/com.aspose.slides/icontrolpropertiescollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

Eine Sammlung von ActiveX-Steuerelementen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCount()](#getCount--) | Gibt die Anzahl der Eigenschaften in der Sammlung zurück. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Fügt der Sammlung eine Eigenschaft hinzu. |
| [remove(String name)](#remove-java.lang.String-) | Entfernt eine Eigenschaft mit dem angegebenen Namen. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gibt die Eigenschaft zurück oder setzt sie. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Gibt die Eigenschaft zurück oder setzt sie. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Gibt die Anzahl der Eigenschaften in der Sammlung zurück. |
| [clear()](#clear--) | Entfernt alle Eigenschaften. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Gibt die Anzahl der Eigenschaften in der Sammlung zurück. Nur lesbar int.

**Rückgabe:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```


Fügt der Sammlung eine Eigenschaft hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Der Name der Eigenschaft. |
| value | java.lang.String | Der Wert der Eigenschaft. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


Entfernt eine Eigenschaft mit dem angegebenen Namen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Der Name der zu entfernenden Eigenschaft. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```


Gibt die Eigenschaft zurück oder setzt sie.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der Eigenschaft. |

**Rückgabe:**
java.lang.String - Eigenschaft.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```


Gibt die Eigenschaft zurück oder setzt sie.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name der Eigenschaft. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


Gibt die Anzahl der Eigenschaften in der Sammlung zurück. Nur lesbar [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Rückgabe:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```


Entfernt alle Eigenschaften.