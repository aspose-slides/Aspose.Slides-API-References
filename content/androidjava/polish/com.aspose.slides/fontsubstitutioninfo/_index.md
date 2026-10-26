---
title: FontSubstitutionInfo
second_title: Aspose.Slides dla Androida poprzez odwołanie do API Java
description: Ta struktura przedstawia informacje o zastąpieniu czcionki, gdy będzie ona renderowana.
type: docs
url: /pl/com.aspose.slides/fontsubstitutioninfo/
---
**Dziedziczenie:**
java.lang.Object
```
public class FontSubstitutionInfo
```

Ta struktura przedstawia informacje o zastąpieniu czcionki, gdy będzie ona renderowana.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions())
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Tworzy instancję klasy [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo). |
## Metody

| Metoda | Opis |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Wskazuje nazwę czcionki źródłowej w prezentacji. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Wskazuje nazwę czcionki zastępczej dla oryginalnej czcionki. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```


Tworzy instancję klasy [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| originFontName | java.lang.String | Nazwa czcionki źródłowej w prezentacji String |
| substFontName | java.lang.String | Nazwa czcionki zastępczej dla oryginalnej czcionki String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```


Wskazuje nazwę czcionki źródłowej w prezentacji. Tylko do odczytu String

**Zwraca:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```


Wskazuje nazwę czcionki zastępczej dla oryginalnej czcionki. Tylko do odczytu String

**Zwraca:**
java.lang.String