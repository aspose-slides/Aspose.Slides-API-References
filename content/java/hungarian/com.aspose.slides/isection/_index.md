---
title: ISection
second_title: Aspose.Slides for Java API Reference
description: Ábrázolja a diák szekcióját.
type: docs
url: /hu/com.aspose.slides/isection/
---```
public interface ISection
```

Ábrázolja a diák szekcióját.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getName()](#getName--) | A szekció neve. |
| [setName(String value)](#setName-java.lang.String-) | A szekció neve. |
| [getSectionId()](#getSectionId--) | A szekció azonosítója. |
| [getStartedFromSlide()](#getStartedFromSlide--) | Visszaadja a szekció első diaját. |
| [getSlidesListOfSection()](#getSlidesListOfSection--) | Visszaadja a szekció diáinak listáját. |
### getName() {#getName--}
```
public abstract String getName()
```


A szekció neve.

**Visszatér:**  
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


A szekció neve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getSectionId() {#getSectionId--}
```
public abstract UUID getSectionId()
```


A szekció azonosítója.

**Visszatér:**  
java.util.UUID
### getStartedFromSlide() {#getStartedFromSlide--}
```
public abstract ISlide getStartedFromSlide()
```


Visszaadja a szekció első diaját.

**Visszatér:**  
[ISlide](../../com.aspose.slides/islide)
### getSlidesListOfSection() {#getSlidesListOfSection--}
```
public abstract ISectionSlideCollection getSlidesListOfSection()
```


Visszaadja a szekció diáinak listáját.

**Visszatér:**  
[ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection) - A diákok listája [ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)