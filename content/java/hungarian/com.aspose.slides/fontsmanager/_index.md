---
title: FontsManager
second_title: Aspose.Slides Java API referencia
description: Kezeli a betűtípusokat a prezentációban.
type: docs
url: /hu/com.aspose.slides/fontsmanager/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
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
>      // A cserélendő forrás betűtípus betöltése
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

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Rendereléskor használandó betűtípushelyettesítések. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Rendereléskor használandó betűtípushelyettesítések. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | A felhasználó FontFallBack szabályainak gyűjteménye a betűtípus-gyűjtemények kezeléséhez a megfelelő helyettesítésekhez visszalépési funkcióval. Olvasás/írás [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | A felhasználó FontFallBack szabályainak gyűjteménye a betűtípus-gyűjtemények kezeléséhez a megfelelő helyettesítésekhez visszalépési funkcióval. Olvasás/írás [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Visszaadja a prezentációban használt betűtípusokat |
| [getSubstitutions()](#getSubstitutions--) | Lekéri a prezentáció renderelése során lecserélendő betűtípusok információit. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Lekéri a megadott diák renderelése során lecserélendő betűtípusok információit. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Visszaadja a prezentációba beágyazott betűtípusokat |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Eltávolítja a beágyazott betűtípust |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Hozzáadja a beágyazott betűtípust |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Hozzáadja a beágyazott betűtípust |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Betűtípus cseréje a prezentációban |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Betűtípus cseréje a prezentációban a [FontSubstRule](../../com.aspose.slides/fontsubstrule) által biztosított információk alapján |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Betűtípus cseréje a prezentációban a [FontSubstRule](../../com.aspose.slides/fontsubstrule) gyűjteménye alapján |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Lekéri a megadott betűtípusstílus és betűtípus adatot reprezentáló bájtarray-t. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Meghatározza egy betűtípus beágyazási szintjét a megadott bájtarray és betűtípusnév alapján. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

Rendereléskor használandó betűtípushelyettesítések. Olvasás/írás [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Visszatérési érték:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Rendereléskor használandó betűtípushelyettesítések. Olvasás/írás [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

A felhasználó FontFallBack szabályainak gyűjteménye a betűtípus-gyűjtemények kezeléséhez a megfelelő helyettesítésekhez visszalépési funkcióval. Olvasás/írás [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

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
>      // és a meglévő gyűjtemény helyettesítése az újjal a FontsManagerben 
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

A felhasználó FontFallBack szabályainak gyűjteménye a betűtípus-gyűjtemények kezeléséhez a megfelelő helyettesítésekhez visszalépési funkcióval. Olvasás/írás [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

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
>      // és a meglévő gyűjtemény helyettesítése az újjal a FontsManagerben 
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
public final IFontData[] getFonts()
```

Visszaadja a prezentációban használt betűtípusokat

**Visszatérési érték:**
com.aspose.slides.IFontData[] - An array of fonts

### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Lekéri a prezentáció renderelése során lecserélendő betűtípusok információit.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Collection of all fonts substitution [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Lekéri a megadott diák renderelése során lecserélendő betűtípusok információit.

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
| slides | int[] | An array of slide indexes for which to retrieve font substitution information, starting from 1. |

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - A collection of all font substitutions ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) for the specified slides.

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

Visszaadja a prezentációba beágyazott betűtípusokat

**Visszatérési érték:**
com.aspose.slides.IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

Eltávolítja a beágyazott betűtípust

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Hozzáadja a beágyazott betűtípust

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Hozzáadja a beágyazott betűtípust

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

Betűtípus cseréje a prezentációban

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Forrás betűtípus |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Cél betűtípus |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

Betűtípus cseréje a prezentációban a [FontSubstRule](../../com.aspose.slides/fontsubstrule) által biztosított információk alapján

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Betűtípus helyettesítési információ |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

Betűtípus cseréje a prezentációban a [FontSubstRule](../../com.aspose.slides/fontsubstrule) gyűjteménye alapján

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Betűtípus helyettesítési szabályok gyűjteménye |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Lekéri a megadott betűtípusstílus és betűtípus adatot reprezentáló bájtarray-t.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // A prezentációban használt összes betűtípust lekéri
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // A prezentáció első betűtípusának normál stílusát reprezentáló bájtarray lekérése
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | A betűtípus adatot tartalmazó objektum, amely a [IFontData](../../com.aspose.slides/ifontdata) információkat tartalmazza. |
| fontStyle | int | A betűtípus stílusa, amelynek az adatát le kell kérni [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Visszatérési érték:**
byte[] - A megadott betűtípusstílushoz tartozó betűtípus adatot tartalmazó bájtarray. Ha a betűtípus adat vagy stílus nem található, null értékkel tér vissza.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Meghatározza egy betűtípus beágyazási szintjét a megadott bájtarray és betűtípusnév alapján.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // A prezentációban használt összes betűtípust lekéri
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // A prezentáció első betűtípusának normál stílusát reprezentáló bájtarray lekérése
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // A betűtípus beágyazási szintjének meghatározása
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontBytes | byte[] | A betűtípus adatot tartalmazó bájtarray. |
| fontName | java.lang.String | A betűtípus neve. |

**Visszatérési érték:**
int - A megadott betűtípus beágyazási szintje.