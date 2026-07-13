---
title: ISection
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Reprezentuje sekcję slajdów.
type: docs
url: /pl/com.aspose.slides/isection/
---```
public interface ISection
```

Reprezentuje sekcję slajdów.

## Metody

| Metoda | Opis |
| --- | --- |
| [getName()](#getName--) | Nazwa sekcji. |
| [setName(String value)](#setName-java.lang.String-) | Nazwa sekcji. |
| [getSectionId()](#getSectionId--) | Identyfikator sekcji. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Zwraca pierwszy slajd sekcji. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Zwraca listę slajdów w sekcji. |
### getName() {#getName--}
```
public abstract String getName()
```

Nazwa sekcji.

**Zwraca:**  
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Nazwa sekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```

Identyfikator sekcji.

**Zwraca:**  
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```

Zwraca pierwszy slajd sekcji.

**Zwraca:**  
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```

Zwraca listę slajdów w sekcji.

**Zwraca:**  
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Lista slajdów [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)