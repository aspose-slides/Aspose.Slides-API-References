---
title: IMasterTheme
second_title: Aspose.Slides Androidra Java API hivatkozással
description: Egy mester témát képvisel.
type: docs
url: /hu/com.aspose.slides/imastertheme/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

Egy mester témát képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Visszaadja a további színsémák gyűjteményét. |
| [getName()](#getName--) | Visszaadja egy téma nevét. |
| [setName(String value)](#setName-java.lang.String-) | Visszaadja egy téma nevét. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```


Visszaadja a további színsémák gyűjteményét. Ezek a sémák nem befolyásolják a bemutató megjelenését, kiválaszthatók fő színsémaként egy dián. Csak olvasható [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Visszatér:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```


Visszaadja egy téma nevét. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Visszaadja egy téma nevét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |