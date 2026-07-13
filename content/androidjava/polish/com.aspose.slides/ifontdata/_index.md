---
title: IFontData
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje definicję czcionki.
type: docs
url: /pl/com.aspose.slides/ifontdata/
---```
public interface IFontData
```

Reprezentuje definicję czcionki.
## Metody

| Metoda | Opis |
| --- | --- |
| [getFontName()](#getFontName--) | Zwraca nazwę czcionki. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Zwraca nazwę czcionki, zastępując odwołanie do motywu rzeczywistą używaną czcionką. |
### getFontName() {#getFontName--}
```
public abstract String getFontName()
```


Zwraca nazwę czcionki. String tylko do odczytu.

**Zwraca:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public abstract String getFontName(IThemeEffectiveData theme)
```


Zwraca nazwę czcionki, zastępując odwołanie do motywu rzeczywistą używaną czcionką.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Motyw, z którego powinna zostać pobrana nazwa czcionki motywu. To po stronie wywołującego, aby dostarczyć prawidłową wartość. |

**Zwraca:**
java.lang.String - Nazwa czcionki.