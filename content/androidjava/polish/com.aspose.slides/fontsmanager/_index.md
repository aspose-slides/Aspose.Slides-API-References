---
title: FontsManager
second_title: Aspose.Slides dla Androida - odniesienie API Javy
description: Zarządza czcionkami w całej prezentacji.
type: docs
url: /pl/com.aspose.slides/fontsmanager/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

Zarządza czcionkami w całej prezentacji.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Wczytaj prezentację
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Wczytaj czcionkę źródłową do zastąpienia
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // Zapisz prezentację
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metody

| Metoda | Opis |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Substitucje czcionek używane podczas renderowania. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Substitucje czcionek używane podczas renderowania. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Reprezentuje kolekcję reguł FontFallBack użytkownika służących do zarządzania zbiorami czcionek w celu właściwych zastąpień przy użyciu funkcji awaryjnej Odczyt/zapis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Reprezentuje kolekcję reguł FontFallBack użytkownika służących do zarządzania zbiorami czcionek w celu właściwych zastąpień przy użyciu funkcji awaryjnej Odczyt/zapis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Zwraca czcionki używane w prezentacji |
| [getSubstitutions()](#getSubstitutions--) | Uzyskuje informacje o czcionkach, które zostaną zastąpione podczas renderowania prezentacji. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Uzyskuje informacje o czcionkach, które zostaną zastąpione podczas renderowania określonych slajdów. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Zwraca czcionki osadzone w prezentacji |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Usuwa osadzoną czcionkę |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Dodaje osadzoną czcionkę |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Dodaje osadzoną czcionkę |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Zastępuje czcionkę w prezentacji |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Zastępuje czcionkę w prezentacji przy użyciu informacji podanych w [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Zastępuje czcionkę w prezentacji przy użyciu informacji podanych w kolekcji [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Pobiera tablicę bajtów reprezentującą dane czcionki dla określonego stylu czcionki i danych czcionki. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Określa poziom osadzenia czcionki na podstawie podanej tablicy bajtów i nazwy czcionki. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

Substitucje czcionek używane podczas renderowania. Odczyt/zapis [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Zwraca:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Substitucje czcionek używane podczas renderowania. Odczyt/zapis [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Reprezentuje kolekcję reguł FontFallBack użytkownika służącą do zarządzania zbiorami czcionek w celu właściwych zastąpień przy użyciu funkcji awaryjnej Odczyt/zapis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Pobieranie pustej lub wstępnie zainicjalizowanej kolekcji reguł z FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // dodawanie reguł do kolekcji
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // lub
>      // inicjalizacja nowej instancji kolekcji reguł
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // dodawanie reguł do kolekcji
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // oraz zastąpienie istniejącej kolekcji nową w FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Reprezentuje kolekcję reguł FontFallBack użytkownika służącą do zarządzania zbiorami czcionek w celu właściwych zastąpień przy użyciu funkcji awaryjnej Odczyt/zapis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Pobieranie pustej lub wstępnie zainicjalizowanej kolekcji reguł z FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // Dodawanie reguł do kolekcji
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // lub 
>      // Inicjalizacja nowej instancji kolekcji reguł
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // Dodawanie reguł do kolekcji
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // i zastąpienie istniejącej kolekcji nową w FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public final IFontData[] getFonts()
```

Zwraca czcionki używane w prezentacji

**Zwraca:**
com.aspose.slides.IFontData[] - Tablica czcionek
### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Uzyskuje informacje o czcionkach, które zostaną zastąpione podczas renderowania prezentacji.

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

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Kolekcja wszystkich substytucji czcionek [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Uzyskuje informacje o czcionkach, które zostaną zastąpione podczas renderowania określonych slajdów.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      int[] targetSlides = { 1, 2, 5 };
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions(targetSlides))
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| slides | int[] | Tablica indeksów slajdów, dla których pobiera się informacje o substytucjach czcionek, licząc od 1. |

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Kolekcja wszystkich substytucji czcionek ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) dla określonych slajdów.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

Zwraca czcionki osadzone w prezentacji

**Zwraca:**
com.aspose.slides.IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

Usuwa osadzoną czcionkę

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Dodaje osadzoną czcionkę

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Dodaje osadzoną czcionkę

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

Zastępuje czcionkę w prezentacji

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Czcionka źródłowa |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Czcionka docelowa |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

Zastępuje czcionkę w prezentacji przy użyciu informacji podanych w [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Informacje o substytucji czcionki |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

Zastępuje czcionkę w prezentacji przy użyciu informacji podanych w kolekcji [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Kolekcja reguł substytucji czcionek |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Pobiera tablicę bajtów reprezentującą dane czcionki dla określonego stylu czcionki i danych czcionki.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Pobierz wszystkie czcionki użyte w prezentacji
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Pobierz tablicę bajtów reprezentującą zwykły styl pierwszej czcionki w prezentacji
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Obiekt danych czcionki zawierający informacje o czcionce [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Styl czcionki, dla którego mają być pobrane dane [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Zwraca:**
byte[] - Tablica bajtów zawierająca dane czcionki dla określonego stylu czcionki. Jeśli dane czcionki lub styl nie zostaną znalezione, zwraca null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Określa poziom osadzenia czcionki na podstawie podanej tablicy bajtów i nazwy czcionki.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Pobierz wszystkie czcionki użyte w prezentacji
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Pobierz tablicę bajtów reprezentującą zwykły styl pierwszej czcionki w prezentacji
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // Określ poziom osadzenia czcionki
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fontBytes | byte[] | Tablica bajtów zawierająca dane czcionki. |
| fontName | java.lang.String | Nazwa czcionki. |

**Zwraca:**
int - Poziom osadzenia określonej czcionki.