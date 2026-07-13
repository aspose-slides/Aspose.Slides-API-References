---
title: CustomXmlPartCollection
second_title: Aspose.Slides per Android via Java API Reference
description: Rappresenta una raccolta di parti xml personalizzate.
type: docs
url: /it/com.aspose.slides/customxmlpartcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

Rappresenta una raccolta di parti xml personalizzate.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [size()](#size--) | Restituisce il conteggio delle parti xml personalizzate nella raccolta. |
| [add(String xmlString)](#add-java.lang.String-) | Aggiunge una nuova parte xml personalizzata. |
| [add(byte[] xmlData)](#add-byte---) | Aggiunge una nuova parte xml personalizzata. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | Aggiunge una nuova parte xml personalizzata. |
| [removeAt(int index)](#removeAt-int-) | Rimuove la parte xml personalizzata all'indice specificato. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | Rimuove la prima occorrenza di un oggetto specifico dalla raccolta. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla raccolta. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia in un array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera nella raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera raccolta. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```


Restituisce l'elemento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero dell'elemento da ottenere. |

**Restituisce:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - L'elemento all'indice specificato.
### size() {#size--}
```
public final int size()
```


Restituisce il conteggio delle parti xml personalizzate nella raccolta. int in sola lettura.

**Restituisce:**
int
### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```


Aggiunge una nuova parte xml personalizzata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmlString | java.lang.String | La stringa xml della nuova parte da aggiungere. |

**Restituisce:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte xml personalizzata creata.
### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```


Aggiunge una nuova parte xml personalizzata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmlData | byte[] | I dati xml della nuova parte da aggiungere. |

**Restituisce:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte xml personalizzata creata.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```


Aggiunge una nuova parte xml personalizzata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputStream | java.io.InputStream | Lo stream di input con i dati xml della nuova parte da aggiungere. |

**Restituisce:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - Parte xml personalizzata creata.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Rimuove la parte xml personalizzata all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero dell'elemento da rimuovere. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```


Rimuove la prima occorrenza di un oggetto specifico dalla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | La parte xml personalizzata da rimuovere. |

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


Copia in un array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| index | int | Indice da cui iniziare la copia. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). boolean in sola lettura.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Restituisce una radice di sincronizzazione. Object in sola lettura.

**Restituisce:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```


Restituisce un enumeratore che itera nella raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Un IGenericEnumerator che può essere usato per iterare nella raccolta.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```


Restituisce un iteratore java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - Un java.util.Iterator per l'intera raccolta.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Restituisce l'oggetto Parent_Immediate. IDOMObject in sola lettura.

**Restituisce:**
com.aspose.slides.IDOMObject