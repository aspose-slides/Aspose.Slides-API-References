---
title: IFontData
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Betűtípus-definíciót képvisel.
type: docs
url: /hu/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Betűtípus-definíciót képvisel.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getFontName()](#getFontName--) | Visszaadja a betűtípus nevét. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Visszaadja a betűtípus nevét, a téma hivatkozás helyett a ténylegesen használt betűtípussal. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Visszaadja a betűtípus nevét. Csak olvasható String.

**Visszatérési érték:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```


Visszaadja a betűtípus nevét, a téma hivatkozás helyett a ténylegesen használt betűtípussal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | A téma, amelyből a témához tartozó betűtípus nevet kell venni. A hívónak kell biztosítania a helyes értéket. |

**Visszatérési érték:**
java.lang.String - Betűtípus neve.