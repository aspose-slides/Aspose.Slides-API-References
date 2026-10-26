---
title: Section
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma seção de slides.
type: docs
url: /pt/com.aspose.slides/section/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISection](../../com.aspose.slides/isection)
```
public class Section extends DomObject<SectionCollection> implements ISection
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
public final String getName()
```


Nome da seção.

**Retorna:** 
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Nome da seção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |
### getSectionId() {#getSectionId--}
```
public final UUID getSectionId()
```


Id da seção.

**Retorna:** 
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public final ISlide getStartedFromSlide()
```


Retorna o primeiro slide da seção.

**Retorna:** 
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public final ISectionSlideCollection getSlidesListOfSection()
```


Retorna a lista de slides da seção.

**Retorna:** 
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - Lista de slides.