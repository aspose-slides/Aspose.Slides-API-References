---
title: IFontsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Zarządza czcionkami w całej prezentacji.
type: docs
url: /pl/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Zarządza czcionkami w całej prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Zastąpienia czcionek używane przy renderowaniu Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Zastąpienia czcionek używane przy renderowaniu Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Reprezentuje kolekcję reguł FontFallBack użytkownika służącą do zarządzania zbiorami czcionek w celu właściwych zastąpień przy użyciu funkcji awaryjnej Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Reprezentuje kolekcję reguł FontFallBack użytkownika służącą do zarządzania zbiorami czcionek w celu właściwych zastąpień przy użyciu funkcji awaryjnej Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Zwraca czcionki użyte w prezentacji |
| [getSubstitutions()](#getSubstitutions--) | Pobiera informacje o czcionkach, które zostaną zastąpione podczas renderowania prezentacji. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Pobiera informacje o czcionkach, które zostaną zastąpione podczas renderowania określonych slajdów. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Zwraca czcionki osadzone w prezentacji |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Usuwa osadzoną czcionkę |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Dodaje osadzoną czcionkę. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Dodaje osadzoną czcionkę |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Zastępuje czcionkę w prezentacji |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Zastępuje czcionkę w prezentacji przy użyciu informacji podanych w [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Zastępuje czcionkę w prezentacji przy użyciu informacji podanych w kolekcji [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Pobiera tablicę bajtów reprezentującą dane czcionki dla określonego stylu czcionki i danych czcionki. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Określa poziom osadzania czcionki z podanej tablicy bajtów i nazwy czcionki. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

Zastąpienia czcionek używane przy renderowaniu Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Zwraca:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Zastąpienia czcionek używane przy renderowaniu Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Reprezentuje kolekcję reguł FontFallBack użytkownika służącą do zarządzania zbiorami czcionek w celu właściwych zastąpień przy użyciu funkcji awaryjnej Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Pobieranie pustej lub wstępnie zainicjowanej kolekcji reguł z FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // dodawanie reguł do kolekcji
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // lub
>      // inicjalizacja nowej instancji kolekcji reguł
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // dodawanie reguł do kolekcji
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // i zamiana istniejącej kolekcji na nową w FontsManager 
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
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Reprezentuje kolekcję reguł FontFallBack użytkownika służącą do zarządzania zbiorami czcionek w celu właściwych zastąpień przy użyciu funkcji awaryjnej Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Pobieranie pustej lub wstępnie zainicjowanej kolekcji reguł z FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // dodawanie reguł do kolekcji
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // lub 
>      // inicjalizacja nowej instancji kolekcji reguł
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // dodawanie reguł do kolekcji
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // i zamiana istniejącej kolekcji na nową w FontsManager 
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
public abstract IFontData[] getFonts()
```

Zwraca czcionki użyte w prezentacji

**Zwraca:**
com.aspose.slides.IFontData[] - Tablica czcionek

### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Pobiera informacje o czcionkach, które zostaną zastąpione podczas renderowania prezentacji.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Zbiór wszystkich zamian czcionek [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Pobiera informacje o czcionkach, które zostaną zastąpione podczas renderowania określonych slajdów.

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
| slides | int[] | Tablica indeksów slajdów, dla których należy pobrać informacje o zamianie czcionek, zaczynając od 1. |

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Zbiór wszystkich zamian czcionek ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) dla określonych slajdów.

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

Zwraca czcionki osadzone w prezentacji

**Zwraca:**
com.aspose.slides.IFontData[] - Czcionki osadzone IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

Usuwa osadzoną czcionkę

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Obiekt danych czcionki [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Dodaje osadzoną czcionkę.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Obiekt danych czcionki [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Reguła osadzenia czcionki [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Pamiętaj, że przy kopiowaniu czcionek większość z nich jest objęta prawami autorskimi. Najpierw znajdź licencję czcionki i sprawdź, czy może być swobodnie przeniesiona na inny komputer.

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Dodaje osadzoną czcionkę

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fontData | byte[] | Dane czcionki  byte[]  |
| embedFontRule | int | Reguła osadzenia czcionki [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Pamiętaj, że przy dodawaniu czcionek większość z nich jest objęta prawami autorskimi. Najpierw znajdź licencję czcionki i sprawdź, czy może być swobodnie przeniesiona na inny komputer.

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

Zastępuje czcionkę w prezentacji

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Czcionka źródłowa |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Czcionka docelowa |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

Zastępuje czcionkę w prezentacji przy użyciu informacji podanych w [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Informacje o zamianie czcionki |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Zastępuje czcionkę w prezentacji przy użyciu informacji podanych w kolekcji [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Kolekcja informacji o zamianie czcionek |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Pobiera tablicę bajtów reprezentującą dane czcionki dla określonego stylu czcionki i danych czcionki.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Pobierz wszystkie czcionki użyte w prezentacji
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Pobierz tablicę bajtów reprezentującą styl regularny pierwszej czcionki w prezentacji
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Obiekt danych czcionki zawierający informacje o czcionce [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Styl czcionki, dla którego mają zostać pobrane dane [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Zwraca:**
byte[] - Tablica bajtów zawierająca dane czcionki dla określonego stylu czcionki. Jeśli dane czcionki lub styl nie zostaną znalezione, zwraca null.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Określa poziom osadzania czcionki z podanej tablicy bajtów i nazwy czcionki.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Pobierz wszystkie czcionki użyte w prezentacji
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Pobierz tablicę bajtów reprezentującą styl regularny pierwszej czcionki w prezentacji
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Określ poziom osadzania czcionki
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