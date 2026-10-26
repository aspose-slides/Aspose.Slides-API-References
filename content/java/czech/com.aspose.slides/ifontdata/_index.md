---
title: IFontData
second_title: Aspose.Slides pro Java API Reference
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
| [getFontName()](#getFontName--) | Vrací název písma. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Vrací název písma, nahrazuje odkaz na motiv skutečným použitým písmem. |
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


Vrací název písma, nahrazuje odkaz na motiv skutečným použitým písmem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Motiv, ze kterého by měl být převzat název tematického písma. Na volajícím je, aby poskytl správnou hodnotu. |

**Vrací:**
java.lang.String - Název písma.