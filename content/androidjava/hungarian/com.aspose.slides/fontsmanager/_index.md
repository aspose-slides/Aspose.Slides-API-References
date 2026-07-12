---
title: FontsManager
second_title: Aspose.Slides Androidra Java API hivatkozás
description: A prezentációban használt betűtípusokat kezeli.
type: docs
url: /hu/com.aspose.slides/fontsmanager/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

A prezentációban használt betűtípusok kezelését végzi.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Prezentáció betöltése
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Cserélendő forrás betűtípus betöltése
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
>      // Prezentáció mentése
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Rendereléskor használandó betűtípus helyettesítések. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Rendereléskor használandó betűtípus helyettesítések. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | A felhasználó FontFallBack szabályok gyűjteményét képviseli a betűtípusok megfelelő helyettesítése érdekében a visszalépés (fallback) funkcióval. Olvasás/írás [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | A felhasználó FontFallBack szabályok gyűjteményét képviseli a betűtípusok megfelelő helyettesítése érdekében a visszalépés (fallback) funkcióval. Olvasás/írás [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Visszaadja a prezentációban használt betűtípusokat |
| [getSubstitutions()](#getSubstitutions--) | Lekéri a betűtípusokkal kapcsolatos információkat, amelyeket a prezentáció renderelése során helyettesítenek. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Lekéri a betűtípusokkal kapcsolatos információkat, amelyeket a megadott diák renderelése során helyettesítenek. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Visszaadja a prezentációban beágyazott betűtípusokat |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Eltávolítja a beágyazott betűtípust |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Hozzáadja a beágyazott betűtípust |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Hozzáadja a beágyazott betűtípust |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Betűtípust cserél a prezentációban |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Betűtípust cserél a prezentációban a [FontSubstRule](../../com.aspose.slides/fontsubstrule) által biztosított információk alapján |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Betűtípust cserél a prezentációban a [FontSubstRule](../../com.aspose.slides/fontsubstrule) gyűjteménye által biztosított információk alapján |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Lekéri a megadott betűtípus stílushoz tartozó betűtípus adatot ábrázoló bájt tömböt |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Megállapítja egy betűtípus beágyazási szintjét a megadott bájt tömb és betűtípus név alapján |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```


Rendereléskor használandó betűtípus helyettesítések. Olvasás/írás [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Visszatérési érték:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```


Rendereléskor használandó betűtípus helyettesítések. Olvasás/írás [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```


A felhasználó FontFallBack szabályok gyűjteményét képviseli a betűtípusok megfelelő helyettesítése érdekében a visszalépés (fallback) funkcióval. Olvasás/írás [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Üres vagy előre inicializált szabálygyűjtemény lekérése a FontsManagerből
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // szabályok hozzáadása a gyűjteményhez
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // vagy 
>      // új szabálygyűjtemény példányának inicializálása
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // szabályok hozzáadása a gyűjteményhez
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // és a meglévő gyűjtemény cseréje az újra a FontsManagerben 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```


A felhasználó FontFallBack szabályok gyűjteményét képviseli a betűtípusok megfelelő helyettesítése érdekében a visszalépés (fallback) funkcióval. Olvasás/írás [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Üres vagy előre inicializált szabálygyűjtemény lekérése a FontsManagerből
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // szabályok hozzáadása a gyűjteményhez
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // vagy 
>      // új szabálygyűjtemény példányának inicializálása
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // szabályok hozzáadása a gyűjteményhez
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // és a meglévő gyűjtemény lecserélése az újjal a FontsManagerben 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public final IFontData[] getFonts()
```


Visszaadja a prezentációban használt betűtípusokat

**Visszatérési érték:**
com.aspose.slides.IFontData[] - Egy betűtípus tömb
### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```


Lekéri a betűtípusokkal kapcsolatos információkat, amelyeket a prezentáció renderelése során helyettesítenek.

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


**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - A teljes betűtípus helyettesítési gyűjtemény [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```


Lekéri a betűtípusokkal kapcsolatos információkat, amelyeket a megadott diák renderelése során helyettesítenek.

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
| --- | --- | |
| slides | int[] | Diák indexeinek tömbje, amelyhez a betűtípus helyettesítési információkat le kell kérni, 1-től kezdődően. |

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - A megadott diákra vonatkozó összes betűtípus helyettesítés gyűjteménye ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)).
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```


Visszaadja a prezentációban beágyazott betűtípusokat

**Visszatérési érték:**
com.aspose.slides.IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```


Eltávolítja a beágyazott betűtípust

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```


Hozzáadja a beágyazott betűtípust

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```


Hozzáadja a beágyazott betűtípust

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```


Betűtípust cserél a prezentációban

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Forrás betűtípus |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Cél betűtípus |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```


Betűtípust cserél a prezentációban a [FontSubstRule](../../com.aspose.slides/fontsubstrule) által biztosított információk alapján

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Betűtípus helyettesítési információ |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```


Betűtípust cserél a prezentációban a [FontSubstRule](../../com.aspose.slides/fontsubstrule) gyűjteménye által biztosított információk alapján

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Betűtípus helyettesítési szabályok gyűjteménye |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```


Lekéri a megadott betűtípus stílushoz tartozó betűtípus adatot ábrázoló bájt tömböt.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // A prezentációban használt összes betűtípust lekéri
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // A prezentáció első betűtípusának normál (regular) stílusát ábrázoló bájt tömböt lekéri
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | A betűtípust tartalmazó adatobjektum, amely a [IFontData](../../com.aspose.slides/ifontdata) betűtípusról információt tárol |
| fontStyle | int | A betűtípus stílusa, amelyhez az adatot le kell kérni [FontStyleType](../../com.aspose.slides/fontstyletype) |

**Visszatérési érték:**
byte[] - A megadott betűtípus stílushoz tartozó betűtípus adatot tartalmazó bájt tömb. Ha a betűtípus adat vagy a stílus nem található, null értékkel tér vissza.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```


Megállapítja egy betűtípus beágyazási szintjét a megadott bájt tömb és betűtípus név alapján.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // A prezentációban használt összes betűtípust lekéri
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // A prezentáció első betűtípusának normál (regular) stílusát ábrázoló bájt tömböt lekéri
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // Meghatározza a betűtípus beágyazási szintjét
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | |
| fontBytes | byte[] | A betűtípust tartalmazó bájt tömb |
| fontName | java.lang.String | A betűtípus neve |

**Visszatérési érték:**
int - A megadott betűtípus beágyazási szintje.