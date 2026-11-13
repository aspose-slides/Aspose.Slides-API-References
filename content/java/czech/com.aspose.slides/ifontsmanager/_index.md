---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
description: Spravuje písma v celé prezentaci.
type: docs
url: /cs/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Spravuje písma v celé prezentaci.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Font substitutions to use when rendering Čtení/Zápis [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Font substitutions to use when rendering Čtení/Zápis [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Čtení/Zápis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Čtení/Zápis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Returns the fonts used in the presentation |
| [getSubstitutions()](#getSubstitutions--) | Gets the information about fonts that will be replaced on the presentation's rendering. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Gets the information about fonts that will be replaced during rendering of the specified slides. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Returns the fonts embedded in the presentation |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Removes the embedded font |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Adds the embedded font. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Adds the embedded font |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Replace font in presentation |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Replace font in presentation using information provided in [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Replace font in presentation using information provided in collection of [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Retrieves the byte array representing the font data for a specified font style and font data. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Determines the embedding level of a font from the given byte array and font name. |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | Specifies whether registered fonts should be preferred over embedded fonts with the same font name and style. |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | Specifies whether registered fonts should be preferred over embedded fonts with the same font name and style. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

Substituce písem k použití při vykreslování Čtení/Zápis [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Vrací:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Substituce písem k použití při vykreslování Čtení/Zápis [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Čtení/Zápis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Získání prázdné nebo předinicializované kolekce pravidel z FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // přidání pravidel do kolekce
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // nebo
>      // inicializace nové instance kolekce pravidel
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // přidání pravidel do kolekce
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // a nahrazení existující kolekce novou v FontsManager 
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
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Čtení/Zápis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Získání prázdné nebo předinicializované kolekce pravidel z FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // přidání pravidel do kolekce
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // nebo 
>      // inicializace nové instance kolekce pravidel
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // přidání pravidel do kolekce
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // a nahrazení existující kolekce novou v FontsManager 
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
public abstract IFontData[] getFonts()
```

Vrací písma použitá v prezentaci

**Vrací:**
com.aspose.slides.IFontData[] - Pole písem
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Získává informace o písmenech, která budou nahrazena při vykreslování prezentace.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Kolekce všech substitucí písem [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Získává informace o písmenech, která budou nahrazena při vykreslování uvedených snímků.

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
| slides | int[] | Pole indexů snímků, pro které se mají získat informace o substitucích písem, počínaje 1. |

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Kolekce všech substitucí písem ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) pro zadané snímky.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

Vrací písma vložená v prezentaci

**Vrací:**
com.aspose.slides.IFontData[] - Vložená písma IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

Odstraňuje vložené písmo

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Objekt dat písma [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Přidává vložené písmo.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Objekt dat písma [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Pravidlo vložení písma [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Mějte na paměti, že většina písem je chráněna autorským právem. Předem zjistěte licenci písma a ověřte, že je možné jej volně přenést na jiný počítač. |
### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Přidává vložené písmo

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontData | byte[] | Data písma  byte[]  |
| embedFontRule | int | Pravidlo vložení písma [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Mějte na paměti, že většina písem je chráněna autorským právem. Předem zjistěte licenci písma a ověřte, že je možné jej volně přenést na jiný počítač. |
### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

Nahradí písmo v prezentaci

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Zdrojové písmo |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Cílové písmo |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

Nahradí písmo v prezentaci pomocí informací uvedených v [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Informace o substituci písma |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Nahradí písmo v prezentaci pomocí informací uvedených ve sbírce [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Sbírka informací o substituci písma |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Získá pole bajtů představující data písma pro zadaný styl písma a data písma.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Získá všechna písma použitá v prezentaci
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Získá pole bajtů představující normální styl prvního písma v prezentaci
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Objekt dat písma obsahující informace o písmu [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Styl písma, pro který se mají získat data [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Vrací:**
byte[] - Pole bajtů obsahující data písma pro zadaný styl. Pokud data písma nebo styl nejsou nalezeny, vrací se null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Určuje úroveň vložení písma ze zadaného pole bajtů a názvu písma.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Získá všechna písma použitá v prezentaci
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Získá pole bajtů představující normální styl prvního písma v prezentaci
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Určí úroveň vložení písma
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
int - Úroveň vložení zadaného písma.
### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public abstract boolean getPreferRegisteredFontsOverEmbedded()
```

Určuje, zda mají být registrovaná písma upřednostňována před vloženými písmy se stejným názvem a stylem. Při povolení jsou odpovídající vložená písma dočasně nahrazena registrovanými písmy během exportu.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      pres.getFontsManager().setPreferRegisteredFontsOverEmbedded(true);
>      pres.save("Presentation-out.pdf", SaveFormat.Pdf);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Výchozí hodnota je **false**.

**Vrací:**
boolean
### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public abstract void setPreferRegisteredFontsOverEmbedded(boolean value)
```

Určuje, zda mají být registrovaná písma upřednostňována před vloženými písmy se stejným názvem a stylem. Při povolení jsou odpovídající vložená písma dočasně nahrazena registrovanými písmy během exportu.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      pres.getFontsManager().setPreferRegisteredFontsOverEmbedded(true);
>      pres.save("Presentation-out.pdf", SaveFormat.Pdf);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Výchozí hodnota je **false**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |