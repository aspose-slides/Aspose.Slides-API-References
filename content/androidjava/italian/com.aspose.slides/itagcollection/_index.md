---
title: ITagCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta la collezione di tag (coppie di stringhe definite dall'utente)
type: docs
url: /it/com.aspose.slides/itagcollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Rappresenta la collezione di tag (coppie di stringhe definite dall'utente)
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Aggiunge un nuovo tag alla collezione. |
| [remove(String name)](#remove-java.lang.String-) | Rimuove il tag con un nome specificato dalla collezione. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | Restituisce l'indice basato su zero della chiave specificata nella collezione. |
| [contains(String name)](#contains-java.lang.String-) | Determina se la collezione contiene un nome specifico. |
| [removeAt(int index)](#removeAt-int-) | Rimuove il tag all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti i tag dalla collezione. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | Restituisce il valore di un tag all'indice specificato. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | Restituisce la chiave di un tag all'indice specificato. |
| [getNamesOfTags()](#getNamesOfTags--) | Restituisce i nomi dei tag. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Restituisce o imposta una coppia chiave/valore di un tag. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Restituisce o imposta una coppia chiave/valore di un tag. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```


Aggiunge un nuovo tag alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Il nome del tag. |
| value | java.lang.String | Il valore del tag. |

**Restituisce:**
int - L'indice del tag aggiunto.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


Rimuove il tag con un nome specificato dalla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Il nome del tag da rimuovere. |

### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```


Restituisce l'indice basato su zero della chiave specificata nella collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Il nome da trovare nella collezione. |

**Restituisce:**
int - L'indice basato su zero della chiave, se la chiave è presente nella collezione; altrimenti, -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```


Determina se la collezione contiene un nome specifico.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | La chiave da trovare. |

**Restituisce:**
boolean - True se la collezione contiene un tag con la chiave specificata; altrimenti, false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Rimuove il tag all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero del tag da rimuovere. |

### clear() {#clear--}
```
public abstract void clear()
```


Rimuove tutti i tag dalla collezione.

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```


Restituisce il valore di un tag all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di un tag da restituire. |

**Restituisce:**
java.lang.String - Valore di un tag.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```


Restituisce la chiave di un tag all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di un tag da restituire. |

**Restituisce:**
java.lang.String - Chiave di un tag.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```


Restituisce i nomi dei tag.

**Restituisce:**
java.lang.String[] - Nomi dei tag.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```


Restituisce o imposta una coppia chiave/valore di un tag.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Chiave di un tag. |

**Restituisce:**
java.lang.String - Valore di un tag.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```


Restituisce o imposta una coppia chiave/valore di un tag.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Chiave di un tag. |
| value | java.lang.String |  |