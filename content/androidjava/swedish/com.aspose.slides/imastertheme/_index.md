---
title: IMasterTheme
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett huvudtema.
type: docs
url: /sv/com.aspose.slides/imastertheme/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

Representerar ett huvudtema.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Returnerar samlingen av ytterligare färgscheman. |
| [getName()](#getName--) | Returnerar namnet på ett tema. |
| [setName(String value)](#setName-java.lang.String-) | Returnerar namnet på ett tema. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```


Returnerar samlingen av ytterligare färgscheman. Dessa scheman påverkar inte presentationens utseende, de kan väljas som huvudfärgschema för en bild. Skrivskyddad [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Returnerar:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```


Returnerar namnet på ett tema. Läs/skriv String.

**Returnerar:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Returnerar namnet på ett tema. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |