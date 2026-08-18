---
title: IFontData
second_title: Aspose.Slides for Java API Reference
description: Egy betűtípusdefiníciót reprezentál.
type: docs
url: /hu/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Betűtípusdefiníciót reprezentál.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFontName()](#getFontName--) | Visszaadja a betűtípus nevét. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Visszaadja a betűtípust, a témával kapcsolatos hivatkozást helyettesítve a ténylegesen használt betűtípussal. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Visszaadja a betűtípus nevét. Csak olvasható String.

**Visszatér:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```


Visszaadja a betűtípust, a témával kapcsolatos hivatkozást helyettesítve a ténylegesen használt betűtípussal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | A téma, amelyből a tematizált betűtípus nevet kell venni. A hívó feladata, hogy helyes értéket adjon meg. |

**Visszatér:**
java.lang.String - Betűtípus neve.