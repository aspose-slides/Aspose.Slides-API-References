---
title: SectionCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una raccolta di sezioni.
type: docs
url: /it/com.aspose.slides/sectioncollection/
---
**Ereditarietà:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

Rappresenta una raccolta di sezioni.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Aggiunge una sezione di diapositive iniziata da una diapositiva specifica. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Aggiunge una sezione vuota alla fine della raccolta. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Aggiunge una sezione vuota alla posizione specificata nella raccolta. |
| [size()](#size--) | Restituisce il numero di elementi effettivamente contenuti nella raccolta. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Restituisce l'indice della sezione specificata nella raccolta. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Rimuove la sezione e le diapositive contenute nella sezione. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Rimuove la sezione. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Sposta la sezione e le sue diapositive dalla raccolta alla posizione specificata. |
| [clear()](#clear--) | Rimuove tutte le sezioni dalla raccolta. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia l'intera raccolta nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera raccolta. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```


Restituisce l'elemento all'indice specificato. Solo lettura [ISection](../../com.aspose.slides/isection).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```


Aggiunge una sezione di diapositive iniziata da una diapositiva specifica.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della sezione |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Prima diapositiva della sezione |

**Restituisce:**
[ISection](../../com.aspose.slides/isection) - Sezione aggiunta.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```


Aggiunge una sezione vuota alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della sezione |

**Restituisce:**
[ISection](../../com.aspose.slides/isection) - Sezione aggiunta.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```


Aggiunge una sezione vuota alla posizione specificata nella raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della sezione |
| index | int | Indice della nuova sezione. |

**Restituisce:**
[ISection](../../com.aspose.slides/isection) - Sezione aggiunta.
### size() {#size--}
```
public final int size()
```


Restituisce il numero di elementi effettivamente contenuti nella raccolta. Solo lettura int.

**Restituisce:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```


Restituisce l'indice della sezione specificata nella raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sezione da trovare. |

**Restituisce:**
int - Indice di una sezione o -1 se la sezione non proviene da questa raccolta.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```


Rimuove la sezione e le diapositive contenute nella sezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | La sezione da rimuovere dalla raccolta. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```


Rimuove la sezione. Le diapositive contenute nella sezione verranno unite alla sezione precedente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | La sezione da rimuovere dalla raccolta. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```


Sposta la sezione e le sue diapositive dalla raccolta alla posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sezione da spostare. |
| index | int | Indice di destinazione. |

### clear() {#clear--}
```
public final void clear()
```


Rimuove tutte le sezioni dalla raccolta.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia l'intera raccolta nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione |
| index | int | Indice nell'array di destinazione. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). Solo lettura boolean.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Restituisce una radice di sincronizzazione. Solo lettura Object.

**Restituisce:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```


Restituisce un enumeratore che itera attraverso la raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Un IGenericEnumerator che può essere usato per iterare attraverso la raccolta.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```


Restituisce un iteratore java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Un java.util.Iterator per l'intera raccolta.