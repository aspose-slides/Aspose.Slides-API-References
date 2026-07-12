---
title: IFontsManager
second_title: Aspose.Slides for Android via Java API Reference
description: A betűtípusokat kezeli a prezentáción belül.
type: docs
url: /hu/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

A betűtípusokat kezeli a prezentáció során.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Betűtípus-helyettesítések, amelyeket a renderelés során használni kell a Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) esetén. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Betűtípus-helyettesítések, amelyeket a renderelés során használni kell a Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) esetén. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | A felhasználó FontFallBack szabályainak gyűjteménye a betűtípus-gyűjtemények megfelelő helyettesítésének kezeléséhez fallback funkción keresztül Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | A felhasználó FontFallBack szabályainak gyűjteménye a betűtípus-gyűjtemények megfelelő helyettesítésének kezeléséhez fallback funkción keresztül Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Visszaadja a prezentációban használt betűtípusokat |
| [getSubstitutions()](#getSubstitutions--) | Megkapja a betűtípusokra vonatkozó információkat, amelyek a prezentáció renderelésekor helyettesítésre kerülnek. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Megkapja a megadott diák renderelése során helyettesítésre kerülő betűtípusokra vonatkozó információkat. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Visszaadja a prezentációba beágyazott betűtípusokat |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Eltávolítja a beágyazott betűtípust |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Hozzáadja a beágyazott betűtípust. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Hozzáadja a beágyazott betűtípust |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Betűtípust cserél a prezentációban |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Betűtípust cserél a prezentációban a [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) által biztosított információ alapján |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Betűtípust cserél a prezentációban a [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) gyűjteményében található információk alapján |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Lekéri a megadott betűtípus-stílushoz és betűtípus adathoz tartozó bájt tömböt. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Meghatározza egy betűtípus beágyazási szintjét a megadott bájt tömb és betűtípus neve alapján. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

Betűtípus-helyettesítések, amelyeket a renderelés során használni kell a Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) esetén.

**Visszatér:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Betűtípus-helyettesítések, amelyeket a renderelés során használni kell a Read/write [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) esetén.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

A felhasználó FontFallBack szabályainak gyűjteménye a betűtípus-gyűjtemények megfelelő helyettesítésének kezeléséhez fallback funkción keresztül Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // A FontsManager üres vagy előre inicializált szabálygyűjteményének lekérése
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // szabályok hozzáadása a gyűjteményhez
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // vagy 
>      // új szabálygyűjtemény példányának inicializálása
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // szabályok hozzáadása a gyűjteményhez
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // és a meglévő gyűjtemény helyettesítése az újjal a FontsManager-ben 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)

### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

A felhasználó FontFallBack szabályainak gyűjteménye a betűtípus-gyűjtemények megfelelő helyettesítésének kezeléséhez fallback funkción keresztül Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Üres vagy előre inicializált szabálygyűjtemény lekérése a FontsManager-ből
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // szabályok hozzáadása a gyűjteményhez
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // vagy 
>      // új szabálygyűjtemény példányának inicializálása
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // szabályok hozzáadása a gyűjteményhez
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // és a meglévő gyűjtemény helyettesítése az újjal a FontsManager-ben 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public abstract IFontData[] getFonts()
```

Visszaadja a prezentációban használt betűtípusokat

**Visszatér:**
com.aspose.slides.IFontData[] - Betűtípusok tömbje

### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Megkapja a betűtípusokra vonatkozó információkat, amelyek a prezentáció renderelésekor helyettesítésre kerülnek.

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


**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Az összes betűtípus-helyettesítés gyűjteménye [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Megkapja a megadott diák renderelése során helyettesítésre kerülő betűtípusokra vonatkozó információkat.

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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slides | int[] | Diák indexeit tartalmazó tömb, amelynek indexelése 1-től kezdődik. |

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Az összes betűtípus-helyettesítés gyűjteménye ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) a megadott diákra.

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

Visszaadja a prezentációba beágyazott betűtípusokat

**Visszatér:**
com.aspose.slides.IFontData[] - Beágyazott betűtípusok IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

Eltávolítja a beágyazott betűtípust

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Betűtípus-adatobjektum [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Hozzáadja a beágyazott betűtípust.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Betűtípus-adatobjektum [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Beágyazott betűtípus-szabály [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Ne feledje, hogy a betűtípusok egy része szerzői joggal védett. Először keresse meg a betűtípus licencét, és ellenőrizze, hogy szabadon áthelyezhető-e egy másik gépre. |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Hozzáadja a beágyazott betűtípust

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontData | byte[] | Betűtípus-adat byte[] |
| embedFontRule | int | Beágyazott betűtípus-szabály [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Ne feledje, hogy a betűtípusok egy része szerzői joggal védett. Először keresse meg a betűtípus licencét, és ellenőrizze, hogy szabadon áthelyezhető-e egy másik gépre. |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

Betűtípust cserél a prezentációban

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Forrás-betűtípus |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Cél-betűtípus |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

Betűtípust cserél a prezentációban a [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) által biztosított információ alapján

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Betűtípus-helyettesítési információ |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Betűtípust cserél a prezentációban a [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) gyűjteményében található információk alapján

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Betűtípus-helyettesítési információk gyűjteménye |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Lekéri a megadott betűtípus-stílushoz és betűtípus adathoz tartozó bájt tömböt.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // A prezentációban használt összes betűtípust lekérdezi
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // A prezentáció első betűtípusának normál stílusát reprezentáló bájt tömb lekérése
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | A betűtípus-adatobjektum, amely a betűtípusra vonatkozó információkat tartalmazza [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | A betűtípus-stílus, amelynek adatait le kell kérni [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Visszatér:**
byte[] - A megadott betűtípus-stílushoz tartozó betűtípus-adatokat tartalmazó bájt tömb. Ha a betűtípus-adat vagy a stílus nem található, null értékkel tér vissza.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Meghatározza egy betűtípus beágyazási szintjét a megadott bájt tömb és betűtípus neve alapján.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // A prezentációban használt összes betűtípust lekérdezi
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Lekéri a prezentáció első betűtípusának normál stílusát reprezentáló bájt tömböt
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Meghatározza a betűtípus beágyazási szintjét
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontBytes | byte[] | A betűtípus-adatokat tartalmazó bájt tömb. |
| fontName | java.lang.String | A betűtípus neve. |

**Visszatér:**
int - A megadott betűtípus beágyazási szintje.