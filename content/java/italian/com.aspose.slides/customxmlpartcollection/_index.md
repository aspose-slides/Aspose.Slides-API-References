---
title: CustomXmlPartCollection
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta una raccolta di parti XML personalizzate.
type: docs
url: /it/com.aspose.slides/customxmlpartcollection/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Rappresenta la raccolta di parti XML personalizzate.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [size()](#size--) | Restituisce il conteggio delle parti XML personalizzate nella raccolta. |
| [add(String xmlString)](#add-java.lang.String-) | Aggiunge una nuova parte XML personalizzata. |
| [add(byte[] xmlData)](#add-byte---) | Aggiunge una nuova parte XML personalizzata. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Aggiunge una nuova parte XML personalizzata. |
| [removeAt(int index)](#removeAt-int-) | Rimuove la parte XML personalizzata all'indice specificato. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Rimuove la prima occorrenza di un oggetto specifico dalla raccolta. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla raccolta. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iterator Java per l'intera raccolta. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```


Restituisce l'elemento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da ottenere. |

**Restituisce:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - L'elemento all'indice specificato.
### size() {#size--}
```
public final int size()
```


Restituisce il conteggio delle parti XML personalizzate nella raccolta. int di sola lettura.

**Restituisce:**
int
### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```


Aggiunge una nuova parte XML personalizzata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmlString | java.lang.String | La stringa XML della nuova parte da aggiungere. |

**Restituisce:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte XML personalizzata creata.
### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```


Aggiunge una nuova parte XML personalizzata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmlData | byte[] | I dati XML della nuova parte da aggiungere. |

**Restituisce:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte XML personalizzata creata.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```


Aggiunge una nuova parte XML personalizzata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | java.io.InputStream | Lo stream di input con i dati XML della nuova parte da aggiungere. |

**Restituisce:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte XML personalizzata creata.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Rimuove la parte XML personalizzata all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da rimuovere. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```


Rimuove la prima occorrenza di un oggetto specifico dalla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | La parte XML personalizzata da rimuovere. |

**Restituisce:**
boolean - true se l'elemento è stato rimosso con successo; altrimenti, false.
### clear() {#clear--}
```
public final void clear()
```


Rimuove tutti gli elementi dalla raccolta.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array in cui copiare. |
| index | int | Indice da cui iniziare a copiare. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). boolean di sola lettura.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Restituisce una radice di sincronizzazione. Object di sola lettura.

**Restituisce:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```


Restituisce un enumeratore che itera attraverso la raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Un IGenericEnumerator che può essere usato per iterare attraverso la raccolta.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```


Restituisce un iterator Java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Un java.util.Iterator per l'intera raccolta.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Restituisce l'oggetto Parent_Immediate. IDOMObject di sola lettura.

**Restituisce:**
com.aspose.slides.IDOMObject