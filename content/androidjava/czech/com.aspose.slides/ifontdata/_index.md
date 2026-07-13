---
title: IFontData
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje definici písma.
type: docs
url: /cs/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Reprezentuje definici písma.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFontName()](#getFontName--) | Returns the font name. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Returns the font name, replacing theme referrence with an actual font used. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```

Vrací název písma. Pouze pro čtení String.

**Vrací:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```

Vrací název písma, nahrazuje odkaz na téma skutečným použitým písmem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Téma, ze kterého by měl být převzat název tematického písma. Je na volajícím, aby poskytl správnou hodnotu. |

**Vrací:**
java.lang.String - název písma.