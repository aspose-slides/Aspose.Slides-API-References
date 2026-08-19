---
title: FontsManager
second_title: Aspose.Slides pro Java – referenční příručka API
description: Spravuje písma v celé prezentaci.
type: docs
url: /cs/com.aspose.slides/fontsmanager/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

Spravuje písma v celé prezentaci.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Načíst prezentaci
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Načíst zdrojové písmo, které se má nahradit
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
>      // Uložit prezentaci
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metody

| Metoda | Popis |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Substituce písem používané při vykreslování. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Substituce písem používané při vykreslování. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Představuje uživatelskou kolekci pravidel FontFallBack pro správu kolekcí písem a správné nahrazování pomocí funkce fallback. Čtení/zápis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Představuje uživatelskou kolekci pravidel FontFallBack pro správu kolekcí písem a správné nahrazování pomocí funkce fallback. Čtení/zápis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Vrací písma použité v prezentaci |
| [getSubstitutions()](#getSubstitutions--) | Získá informace o písmenech, která budou nahrazena při vykreslování prezentace. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Získá informace o písmenech, která budou nahrazena během vykreslování zadaných snímků. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Vrací písma vložená v prezentaci |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Odstraní vložené písmo |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Přidá vložené písmo |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Přidá vložené písmo |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Nahradí písmo v prezentaci |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Nahradí písmo v prezentaci pomocí informací poskytnutých v [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Nahradí písmo v prezentaci pomocí informací poskytnutých ve sbírce [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Načte pole bajtů představující data písma pro zadaný styl písma a data písma. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Určuje úroveň vkládání písma z daného pole bajtů a názvu písma. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

Substituce písem používané při vykreslování. Čtení/zápis [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Vrací:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Substituce písem používané při vykreslování. Čtení/zápis [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Představuje uživatelskou kolekci pravidel FontFallBack pro správu kolekcí písem a správné nahrazování pomocí funkce fallback. Čtení/zápis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Získání prázdné nebo předinicializované kolekce pravidel z FontsManageru
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // přidání pravidel do kolekce
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // nebo 
>      // inicializace nové instance kolekce pravidel
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // přidání pravidel do kolekce
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // a nahrazení existující kolekce novou v FontsManageru 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Vrací:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Představuje uživatelskou kolekci pravidel FontFallBack pro správu kolekcí písem a správné nahrazování pomocí funkce fallback. Čtení/zápis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Získání prázdné nebo předinicializované kolekce pravidel z FontsManageru
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // přidání pravidel do kolekce
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // nebo 
>      // inicializace nové instance kolekce pravidel
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // přidání pravidel do kolekce
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // a nahrazení existující kolekce novou v FontsManageru 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public final IFontData[] getFonts()
```

Vrací písma použité v prezentaci

**Vrací:**
com.aspose.slides.IFontData[] - Pole písem
### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Získá informace o písmenech, která budou nahrazena při vykreslování prezentace.

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


**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Sbírka všech substitucí písem [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Získá informace o písmenech, která budou nahrazena během vykreslování zadaných snímků.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| slides | int[] | Pole indexů snímků, pro které získat informace o substitucích písem, počínaje 1. |

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Sbírka všech substitucí písem ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) pro zadané snímky.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

Vrací písma vložená v prezentaci

**Vrací:**
com.aspose.slides.IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

Odstraňuje vložené písmo

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Přidá vložené písmo

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Přidá vložené písmo

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

Nahradí písmo v prezentaci

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Zdrojové písmo |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Cílové písmo |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

Nahradí písmo v prezentaci pomocí informací poskytnutých v [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Informace o substituci písma |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

Nahradí písmo v prezentaci pomocí informací poskytnutých ve sbírce [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Sbírka pravidel substituce písem |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Načte pole bajtů představující data písma pro zadaný styl písma a data písma.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Získá všechna písma použitá v prezentaci
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Získá pole bajtů představující pravidelný styl prvního písma v prezentaci
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Objekt dat písma obsahující informace o písmu [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Styl písma, pro který se mají data získat [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Vrací:**
byte[] - Pole bajtů obsahující data písma pro zadaný styl písma. Pokud data písma nebo styl nejsou nalezeny, vrací null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Určuje úroveň vkládání písma z daného pole bajtů a názvu písma.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Získá všechna písma použitá v prezentaci
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Získá pole bajtů představující normální styl prvního písma v prezentaci
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // Určí úroveň vkládání písma
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontBytes | byte[] | Pole bajtů obsahující data písma. |
| fontName | java.lang.String | Název písma. |

**Vrací:**
int - Úroveň vkládání zadaného písma.