---
title: IFontsManager
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Spravuje písma napříč prezentací.
type: docs
url: /cs/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Spravuje písma napříč prezentací.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Substituce písem k použití při vykreslování Čtení/Zápis [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Substituce písem k použití při vykreslování Čtení/Zápis [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Představuje uživatelskou kolekci pravidel FontFallBack pro správu kolekcí písem pro správné substituce pomocí funkce fallback Čtení/Zápis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Představuje uživatelskou kolekci pravidel FontFallBack pro správu kolekcí písem pro správné substituce pomocí funkce fallback Čtení/Zápis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Vrací písma použitá v prezentaci |
| [getSubstitutions()](#getSubstitutions--) | Získává informace o písmách, která budou nahrazena při vykreslování prezentace. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Získává informace o písmách, která budou nahrazena při vykreslování určených snímků. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Vrací písma vložená v prezentaci |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Odstraňuje vložené písmo |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Přidává vložené písmo. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Přidává vložené písmo |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Nahradí písmo v prezentaci |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Nahradí písmo v prezentaci pomocí informací poskytnutých v [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Nahradí písmo v prezentaci pomocí informací poskytnutých v kolekci [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Načte pole bytů představující data písma pro zadaný styl písma a data písma. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Určuje úroveň vložení písma z daného pole bytů a názvu písma. |
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

Představuje uživatelskou kolekci pravidel FontFallBack pro správu kolekcí písem pro správné substituce pomocí funkce fallback Čtení/Zápis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

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
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Představuje uživatelskou kolekci pravidel FontFallBack pro správu kolekcí písem pro správné substituce pomocí funkce fallback Čtení/Zápis [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

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
public abstract IFontData[] getFonts()
```

Vrací písma použitá v prezentaci

**Vrací:**
com.aspose.slides.IFontData[] - Pole písem
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Získává informace o písmách, která budou nahrazena při vykreslování prezentace.

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
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Získává informace o písmách, která budou nahrazena při vykreslování určených snímků.

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
| slides | int[] | Pole indexů snímků, pro které se mají načíst informace o substituci písem, počínaje 1. |

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Sbírka všech substitucí písem ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) pro určené snímky.
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
| embedFontRule | int | Pravidlo vloženého písma [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Mějte na paměti při kopírování libovolných písem, že většina písem je chráněna autorským právem. Nejprve najděte licenci daného písma a ověřte, že může být volně přenesena na jiný počítač. |
### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Přidává vložené písmo

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontData | byte[] | Data písma  byte[]  |
| embedFontRule | int | Pravidlo vloženého písma [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Mějte na paměti při přidávání libovolných písem, že většina písem je chráněna autorským právem. Nejprve najděte licenci daného písma a ověřte, že může být volně přenesena na jiný počítač. |
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

Nahradí písmo v prezentaci pomocí informací poskytnutých v [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Informace o substituci písma |
### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Nahradí písmo v prezentaci pomocí informací poskytnutých v kolekci [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Kolekce informací o substituci písem |
### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Načte pole bytů představující data písma pro zadaný styl písma a data písma.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Získá všechna písma použitá v prezentaci
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Získá pole bytů představující běžný styl prvního písma v prezentaci
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Objekt dat písma obsahující informace o písmu [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Styl písma, pro který mají být data načtena [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Vrací:**
byte[] - Pole bytů obsahující data písma pro zadaný styl písma. Pokud data písma nebo styl nejsou nalezeny, vrací null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Určuje úroveň vložení písma z daného pole bytů a názvu písma.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Získá všechna písma použitá v prezentaci
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Získá pole bytů představující běžný styl prvního písma v prezentaci
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
| fontBytes | byte[] | Pole bytů obsahující data písma. |
| fontName | java.lang.String | Název písma. |

**Vrací:**
int - Úroveň vložení zadaného písma.