---
title: IFontData
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een lettertype-definitie voor.
type: docs
url: /nl/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Stelt een lettertype-definitie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFontName()](#getFontName--) | Retourneert de naam van het lettertype. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Retourneert de naam van het lettertype, waarbij de thema-referentie wordt vervangen door een daadwerkelijk gebruikt lettertype. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Retourneert de naam van het lettertype. Alleen-lezen String.

**Retour:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```


Retourneert de naam van het lettertype, waarbij de thema-referentie wordt vervangen door een daadwerkelijk gebruikt lettertype.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Thema waaruit de thema-lettertype naam moet worden genomen. Het is aan de aanroeper om een correcte waarde te leveren. |

**Retour:**
java.lang.String - Lettertype naam.