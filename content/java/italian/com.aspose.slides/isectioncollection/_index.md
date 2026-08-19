---
title: ISectionCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una raccolta di sezioni.
type: docs
url: /it/com.aspose.slides/isectioncollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

Rappresenta una raccolta di sezioni.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Aggiunge una nuova sezione iniziata da una diapositiva specifica. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Aggiunge una sezione vuota nella posizione specificata della raccolta. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Rimuove la sezione e le diapositive contenute nella sezione. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Rimuove la sezione. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Sposta la sezione e le sue diapositive dalla raccolta alla posizione specificata. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Aggiunge una sezione vuota alla fine della raccolta. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Restituisce l'indice della sezione specificata nella raccolta. |
| [clear()](#clear--) | Rimuove tutte le sezioni dalla raccolta. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```

Ottiene l'elemento all'indice specificato. **Sola lettura** [ISection](../../com.aspose.slides/isection).

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

Aggiunge una sezione vuota nella posizione specificata della raccolta.

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
| section | [ISection](../../com.aspose.slides/isection) | La sezione da rimuovere dalla raccolta. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```

Rimuove la sezione. Le diapositive contenute nella sezione saranno unite alla sezione precedente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | La sezione da rimuovere dalla raccolta. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```

Sposta la sezione e le sue diapositive dalla raccolta alla posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sezione da spostare. |
| index | int | Indice di destinazione. |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```

Aggiunge una sezione vuota alla fine della raccolta.

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

Restituisce l'indice della sezione specificata nella raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sezione da trovare. |

**Restituisce:**
int - Indice di una sezione o -1 se la sezione non appartiene a questa raccolta.
### clear() {#clear--}
```
public abstract void clear()
```

Rimuove tutte le sezioni dalla raccolta.