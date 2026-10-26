---
title: SectionCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una raccolta di sezioni.
type: docs
url: /it/com.aspose.slides/sectioncollection/
---
**Eredità:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le Interfacce Implementate:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

Rappresenta una raccolta di sezioni.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Aggiunge una sezione diapositive iniziata da una diapositiva specifica. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Aggiunge una sezione vuota alla fine della collezione. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Aggiunge una sezione vuota alla posizione specificata della collezione. |
| [size()](#size--) | Ottiene il numero di elementi effettivamente contenuti nella collezione. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Restituisce l'indice della sezione specificata nella collezione. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Rimuove la sezione e le diapositive contenute nella sezione. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Rimuove la sezione. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Sposta la sezione e le sue diapositive dalla collezione alla posizione specificata. |
| [clear()](#clear--) | Rimuove tutte le sezioni dalla collezione. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia l'intera collezione nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

Ottiene l'elemento all'indice specificato. [ISection](../../com.aspose.slides/isection) di sola lettura.

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

Aggiunge una sezione diapositive iniziata da una diapositiva specifica.

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

Aggiunge una sezione vuota alla fine della collezione.

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

Aggiunge una sezione vuota alla posizione specificata della collezione.

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

Ottiene il numero di elementi effettivamente contenuti nella collezione. int di sola lettura.

**Restituisce:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

Restituisce l'indice della sezione specificata nella collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sezione da trovare. |

**Restituisce:**
int - Indice di una sezione o -1 se la sezione non proviene da questa collezione.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

Rimuove la sezione e le diapositive contenute nella sezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | La sezione da rimuovere dalla collezione. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

Rimuove la sezione. Le diapositive contenute nella sezione saranno fuse nella sezione precedente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | La sezione da rimuovere dalla collezione. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

Sposta la sezione e le sue diapositive dalla collezione alla posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sezione da spostare. |
| index | int | Indice di destinazione. |

### clear() {#clear--}
```
public final void clear()
```

Rimuove tutte le sezioni dalla collezione.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia l'intera collezione nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione |
| index | int | Indice nell'array di destinazione. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). boolean di sola lettura.

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
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Un java.util.Iterator per l'intera collezione.