---
title: Section
second_title: Aspose.Slides per Android via Riferimento API Java
description: Rappresenta una sezione di diapositive.
type: docs
url: /it/com.aspose.slides/section/
---
**Eredità:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
```

Rappresenta una sezione di diapositive.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getName()](#getName--) | Nome della sezione. |
| [setName(String value)](#setName-java.lang.String-) | Nome della sezione. |
| [getSectionId()](#getSectionId--) | Id della sezione. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Restituisce la prima diapositiva della sezione. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Restituisce l'elenco delle diapositive nella sezione. |
### getName() {#getName--}
```
public final String getName()
```


Nome della sezione.

**Restituisce:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Nome della sezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```


Id della sezione.

**Restituisce:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```


Restituisce la prima diapositiva della sezione.

**Restituisce:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```


Restituisce l'elenco delle diapositive nella sezione.

**Restituisce:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Elenco di diapositive.