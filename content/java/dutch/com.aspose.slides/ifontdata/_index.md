---
title: IFontData
second_title: Aspose.Slides for Java API Reference
description: Stelt een fontdefinitie voor.
type: docs
url: /nl/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Stelt een fontdefinitie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFontName()](#getFontName--) | Retourneert de fontnaam. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Retourneert de fontnaam, waarbij de thema-referentie wordt vervangen door een daadwerkelijk gebruikte font. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Retourneert de fontnaam. Alleen-lezen String.

**Retour:**  
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```


Retourneert de fontnaam, waarbij de thema-referentie wordt vervangen door een daadwerkelijk gebruikte font.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Thema waaruit de gethematiseerde fontnaam moet worden genomen. Het is aan de aanroeper om een correcte waarde te leveren. |

**Retour:**
java.lang.String - Fontnaam.