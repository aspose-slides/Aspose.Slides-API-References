---
title: FontSubstitutionInfo
second_title: Aspose.Slides pro Java API Reference
description: Tato struktura představuje informace o nahrazení písma při vykreslování.
type: docs
url: /cs/com.aspose.slides/fontsubstitutioninfo/
---
**Dědičnost:**
java.lang.Object
```
public class FontSubstitutionInfo
```

Tato struktura představuje informace o nahrazení písma při vykreslování.

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

| Konstruktor | Popis |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Vytvoří instanci třídy [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo). |
## Metody

| Metoda | Popis |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Určuje název zdrojového písma v prezentaci. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Určuje název nahrazovacího písma pro originální písmo. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```


Vytvoří instanci třídy [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| originFontName | java.lang.String | Název zdrojového písma v prezentaci String |
| substFontName | java.lang.String | Název nahrazovacího písma pro originální písmo String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```


Určuje název zdrojového písma v prezentaci. Pouze pro čtení String

**Vrácená hodnota:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```


Určuje název nahrazovacího písma pro originální písmo. Pouze pro čtení String

**Vrácená hodnota:**
java.lang.String