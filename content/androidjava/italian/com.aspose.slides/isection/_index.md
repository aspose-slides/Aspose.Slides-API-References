---
title: ISection
second_title: Aspose.Slides per Android via Java API Reference
description: Rappresenta una sezione di diapositive.
type: docs
url: /it/com.aspose.slides/isection/
---```
public interface ISection
```

Rappresenta una sezione di diapositive.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getName()](#getName--) | Nome della sezione. |
| [setName(String value)](#setName-java.lang.String-) | Nome della sezione. |
| [getSectionId()](#getSectionId--) | ID della sezione. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Restituisce la prima diapositiva della sezione. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Restituisce l'elenco delle diapositive nella sezione. |
### getName() {#getName--}
```
public abstract String getName()
```

Nome della sezione.

**Restituisce:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Nome della sezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```

ID della sezione.

**Restituisce:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```

Restituisce la prima diapositiva della sezione.

**Restituisce:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```

Restituisce l'elenco delle diapositive nella sezione.

**Restituisce:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Elenco di diapositive [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)