---
title: IFontData
second_title: Aspose.Slides for Java API Reference
description: Represents a font definition.
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
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Zwraca nazwę czcionki, zastępując odniesienie do motywu rzeczywistą używaną czcionką. |
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

Zwraca nazwę czcionki, zastępując odniesienie do motywu rzeczywistą używaną czcionką.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Motyw, z którego ma zostać pobrana nazwa czcionki tematycznej. To zależy od wywołującego, aby dostarczył prawidłową wartość. |

**Zwraca:**
java.lang.String - Nazwa czcionki.