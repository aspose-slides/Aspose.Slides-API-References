---
title: IFontData
second_title: Aspose.Slides for Java API Reference
description: Stellt eine Schriftartdefinition dar.
type: docs
url: /de/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Stellt eine Schriftartdefinition dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFontName()](#getFontName--) | Gibt den Schriftartnamen zurück. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Gibt den Schriftartnamen zurück, wobei die Themenreferenz durch die tatsächlich verwendete Schriftart ersetzt wird. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Gibt den Schriftartnamen zurück. Schreibgeschützter String.

**Rückgabe:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```


Gibt den Schriftartnamen zurück, wobei die Themenreferenz durch die tatsächlich verwendete Schriftart ersetzt wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Thema, aus dem der themenbezogene Schriftartname entnommen werden soll. Es liegt beim Aufrufer, einen korrekten Wert bereitzustellen. |

**Rückgabe:**
java.lang.String - Schriftartname.