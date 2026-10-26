---
title: MasterTheme
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt een hoofdthema.
type: docs
url: /nl/com.aspose.slides/mastertheme/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

Vertegenwoordigt een hoofdthema.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Retourneert het kleurenschema. |
| [getFontScheme()](#getFontScheme--) | Retourneert het lettertype-schema. |
| [getFormatScheme()](#getFormatScheme--) | Retourneert het vormopmaak-schema. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Retourneert de collectie van extra kleurenschema's. |
| [getName()](#getName--) | Retourneert de naam van een thema. |
| [setName(String value)](#setName-java.lang.String-) | Retourneert de naam van een thema. |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```


Retourneert het kleurenschema. Alleen-lezen [IColorScheme](../../com.aspose.slides/icolorscheme).

**Retour:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```


Retourneert het lettertype-schema. Alleen-lezen [IFontScheme](../../com.aspose.slides/ifontscheme).

**Retour:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```


Retourneert het vormopmaak-schema. Alleen-lezen [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Retour:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```


Retourneert de collectie van extra kleurenschema's. Deze schema's hebben geen invloed op het uiterlijk van de presentatie; ze kunnen worden geselecteerd als hoofd-kleurenschema voor een dia. Alleen-lezen [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Retour:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```


Retourneert de naam van een thema. Lezen/Schrijven String.

**Retour:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Retourneert de naam van een thema. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getVersion() {#getVersion--}
```
public long getVersion()
```


Versie. Alleen-lezen long.

**Retour:**
long