---
title: FontSubstitutionInfo
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Tato struktura představuje informace o náhradě písma, když bude vykresleno.
type: docs
url: /cs/com.aspose.slides/fontsubstitutioninfo/
---
**Dědičnost:**
java.lang.Object
```
public class FontSubstitutionInfo
```

Tato struktura představuje informace o náhradě písma, když bude vykresleno.

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
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Vytvoří instance třídy [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo). |
## Metody

| Metoda | Popis |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Indikuje název zdrojového písma v prezentaci. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Indikuje název náhradního písma pro původní písmo. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```

Vytvoří instance třídy [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| originFontName | java.lang.String | Název zdrojového písma v prezentaci String |
| substFontName | java.lang.String | Název náhradního písma pro původní písmo String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```

Indikuje název zdrojového písma v prezentaci. Pouze pro čtení String

**Vrací:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```

Indikuje název náhradního písma pro původní písmo. Pouze pro čtení String

**Vrací:**
java.lang.String