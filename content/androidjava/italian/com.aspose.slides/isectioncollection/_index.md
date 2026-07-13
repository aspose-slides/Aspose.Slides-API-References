---
title: ISectionCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una collezione di sezioni.
type: docs
url: /it/com.aspose.slides/isectioncollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

Rappresenta una collezione di sezioni.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Aggiunge una nuova sezione iniziata da una diapositiva specifica. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Aggiunge una sezione vuota nella posizione specificata della collezione. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Rimuove la sezione e le diapositive contenute nella sezione. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Rimuove la sezione. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Sposta la sezione e le sue diapositive dalla collezione alla posizione specificata. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Aggiunge una sezione vuota alla fine della collezione. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Restituisce un indice della sezione specificata nella collezione. |
| [clear()](#clear--) | Rimuove tutte le sezioni dalla collezione. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```


Ottiene l'elemento all'indice specificato. Solo lettura [ISection](../../com.aspose.slides/isection).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```


Aggiunge una nuova sezione iniziata da una diapositiva specifica.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della sezione |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Prima diapositiva della sezione |

**Restituisce:**
[ISection](../../com.aspose.slides/isection) - Sezione aggiunta.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```


Aggiunge una sezione vuota nella posizione specificata della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della sezione |
| index | int | Indice della nuova sezione. |

**Restituisce:**
[ISection](../../com.aspose.slides/isection) - Sezione aggiunta.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```


Rimuove la sezione e le diapositive contenute nella sezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | La sezione da rimuovere dalla collezione. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```


Rimuove la sezione. Le diapositive contenute nella sezione verranno unite alla sezione precedente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | La sezione da rimuovere dalla collezione. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```


Sposta la sezione e le sue diapositive dalla collezione alla posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sezione da spostare. |
| index | int | Indice di destinazione. |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```


Aggiunge una sezione vuota alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome della sezione |

**Restituisce:**
[ISection](../../com.aspose.slides/isection) - Sezione aggiunta.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```


Restituisce un indice della sezione specificata nella collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sezione da trovare. |

**Restituisce:**
int - Indice della sezione o -1 se la sezione non proviene da questa collezione.
### clear() {#clear--}
```
public abstract void clear()
```


Rimuove tutte le sezioni dalla collezione.