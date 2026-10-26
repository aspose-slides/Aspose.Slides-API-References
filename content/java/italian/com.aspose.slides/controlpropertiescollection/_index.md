---
title: ControlPropertiesCollection
second_title: Riferimento API per Aspose.Slides per Java
description: Una raccolta di proprietà AcitveX.
type: docs
url: /it/com.aspose.slides/controlpropertiescollection/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

Una raccolta di proprietà AcitveX.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Aggiunge una proprietà alla raccolta. |
| [remove(String name)](#remove-java.lang.String-) | Rimuove una proprietà con il nome specificato. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Restituisce o imposta la proprietà. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Restituisce o imposta la proprietà. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Restituisce la raccolta dei nomi delle proprietà. |
| [clear()](#clear--) | Rimuove tutte le proprietà. |
| [getCount()](#getCount--) | Restituisce il numero di proprietà nella raccolta. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera raccolta. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```


Aggiunge una proprietà alla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Il nome della proprietà. |
| value | java.lang.String | Il valore della proprietà. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```


Rimuove una proprietà con il nome specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Il nome della proprietà da rimuovere. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```


Restituisce o imposta la proprietà.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà. |

**Restituisce:**
java.lang.String - Proprietà.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```


Restituisce o imposta la proprietà.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


Restituisce la raccolta dei nomi delle proprietà. Solo lettura [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Restituisce:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public final void clear()
```


Rimuove tutte le proprietà.

### getCount() {#getCount--}
```
public final int getCount()
```


Restituisce il numero di proprietà nella raccolta. Solo lettura int.

**Restituisce:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```


Restituisce un enumeratore che itera attraverso la raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```


Restituisce un iteratore java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.