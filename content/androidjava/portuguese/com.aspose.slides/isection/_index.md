---
title: ISection
second_title: Aspose.Slides for Android via Java API Reference
description: Representa uma seção de slides.
type: docs
url: /pt/com.aspose.slides/isection/
---```
public interface ISection
```

Representa uma seção de slides.
## Métodos

| Método | Descrição |
| --- | --- |
| [getName()](#getName--) | Nome da seção. |
| [setName(String value)](#setName-java.lang.String-) | Nome da seção. |
| [getSectionId()](#getSectionId--) | Id da seção. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Retorna o primeiro slide da seção. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Retorna a lista de slides da seção. |
### getName() {#getName--}
```
public abstract String getName()
```


Nome da seção.

**Retorna:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Nome da seção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```


Id da seção.

**Retorna:**
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```


Retorna o primeiro slide da seção.

**Retorna:**
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```


Retorna a lista de slides da seção.

**Retorna:**
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Lista de slides [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)