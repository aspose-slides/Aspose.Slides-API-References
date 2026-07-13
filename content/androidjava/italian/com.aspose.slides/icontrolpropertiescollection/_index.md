---
title: IControlPropertiesCollection
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Una raccolta di controlli ActiveX.
type: docs
url: /it/com.aspose.slides/icontrolpropertiescollection/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

Una raccolta di controlli ActiveX.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCount()](#getCount--) | Restituisce un numero di proprietà nella raccolta. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Aggiunge una proprietà alla raccolta. |
| [remove(String name)](#remove-java.lang.String-) | Rimuove una proprietà con il nome specificato. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Restituisce o imposta la proprietà. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Restituisce o imposta la proprietà. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Restituisce un numero di proprietà nella raccolta. |
| [clear()](#clear--) | Rimuove tutte le proprietà. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Restituisce un numero di proprietà nella raccolta. Solo lettura int.

**Restituisce:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```


Aggiunge una proprietà alla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Il nome della proprietà. |
| value | java.lang.String | Il valore della proprietà. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


Rimuove una proprietà con il nome specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Il nome della proprietà da rimuovere. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
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
public abstract void set_Item(String name, String value)
```


Restituisce o imposta la proprietà.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della proprietà. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


Restituisce un numero di proprietà nella raccolta. Solo lettura [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Restituisce:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```


Rimuove tutte le proprietà.