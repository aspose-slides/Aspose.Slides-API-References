---
title: IMasterTheme
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een masterthema voor.
type: docs
url: /nl/com.aspose.slides/imastertheme/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

Stelt een masterthema voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Retourneert de verzameling extra kleurenschema's. |
| [getName()](#getName--) | Retourneert de naam van een thema. |
| [setName(String value)](#setName-java.lang.String-) | Retourneert de naam van een thema. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```

Retourneert de verzameling extra kleurenschema's. Deze schema's hebben geen invloed op het uiterlijk van de presentatie, ze kunnen worden geselecteerd als hoofd kleurenschema voor een dia. Alleen-lezen [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Retourneert:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```

Retourneert de naam van een thema. Lezen/schrijven String.

**Retourneert:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Retourneert de naam van een thema. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |