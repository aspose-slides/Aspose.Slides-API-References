---
title: IFontData
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a font definition.
type: docs
url: /de/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Stellt eine Schriftdefinition dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFontName()](#getFontName--) | Gibt den Schriftnamen zurück. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Gibt den Schriftnamen zurück, wobei die Themenreferenz durch die tatsächlich verwendete Schrift ersetzt wird. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Gibt den Schriftnamen zurück. Nur lesbar String.

**Rückgabe:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```


Gibt den Schriftnamen zurück, wobei die Themenreferenz durch die tatsächlich verwendete Schrift ersetzt wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Thema, aus dem der thematisierte Schriftnamen übernommen werden soll. Es liegt in der Verantwortung des Aufrufers, einen korrekten Wert bereitzustellen. |

**Rückgabe:**
java.lang.String - Schriftnamen.