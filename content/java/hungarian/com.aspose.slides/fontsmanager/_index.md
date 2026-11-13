---
title: FontsManager
second_title: Aspose.Slides Java API hivatkozás
description: Kezeli a betűtípusokat a prezentációban.
type: docs
url: /hu/com.aspose.slides/fontsmanager/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

Manages fonts across the presentation.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Töltsd be a prezentációt
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Töltsd be a cserélendő forrás betűtípust
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
>      // Mentsd el a prezentációt
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | A renderelés során használandó betűtípus helyettesítések. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | A renderelés során használandó betűtípus helyettesítések. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | A felhasználó FontFallBack szabályainak gyűjteménye a betűtípus-gyűjtemények kezelésére a megfelelő helyettesítéshez a visszaesés funkcióval. Olvasás/írás [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | A felhasználó FontFallBack szabályainak gyűjteménye a betűtípus-gyűjtemények kezelésére a megfelelő helyettesítéshez a visszaesés funkcióval. Olvasás/írás [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Visszaadja a prezentációban használt betűtípusokat |
| [getSubstitutions()](#getSubstitutions--) | Lekéri a prezentáció renderelése során cserélendő betűtípusokkal kapcsolatos információkat. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Lekéri a megadott diák renderelése során cserélendő betűtípusokkal kapcsolatos információkat. |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | Megadja, hogy a regisztrált betűtípusokat részesítsék előnyben a beágyazott, azonos névű és stílusú betűtípusokkal szemben. |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | Megadja, hogy a regisztrált betűtípusokat részesítsék előnyben a beágyazott, azonos névű és stílusú betűtípusokkal szemben. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Visszaadja a prezentációba beágyazott betűtípusokat |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Eltávolítja a beágyazott betűtípust |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Hozzáadja a beágyazott betűtípust |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Hozzáadja a beágyazott betűtípust |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Betűtípus cseréje a prezentációban |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Betűtípus cseréje a prezentációban a [FontSubstRule](../../com.aspose.slides/fontsubstrule) által biztosított információk alapján |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Betűtípus cseréje a prezentációban a [FontSubstRule](../../com.aspose.slides/fontsubstrule) gyűjtemény által biztosított információk alapján |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Lekéri a megadott betűtípus stílushoz és betűtípus adathoz tartozó bájt tömböt. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Megállapítja egy betűtípus beágyazási szintjét a megadott bájt tömb és betűtípus név alapján. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

Renderelés során használható betűtípus helyettesítések. Olvasás/írás [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Visszatérési érték:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Renderelés során használható betűtípus helyettesítések. Olvasás/írás [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

A felhasználó FontFallBack szabályainak gyűjteménye a betűtípus-gyűjtemények kezelésére a megfelelő helyettesítéshez a visszaesés funkcióval. Olvasás/írás [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Üres vagy előre inicializált szabálykészlet lekérése a FontsManager-ből
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // szabályok hozzáadása a gyűjteményhez
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // vagy 
>      // új szabálykészlet példányának inicializálása
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // szabályok hozzáadása a gyűjteményhez
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // és a meglévő gyűjtemény cseréje az újra a FontsManager-ben 
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

A felhasználó FontFallBack szabályainak gyűjteménye a betűtípus-gyűjtemények kezelésére a megfelelő helyettesítéshez a visszaesés funkcióval. Olvasás/írás [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Üres vagy előre inicializált szabálykészlet lekérése a FontsManager-ből
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // szabályok hozzáadása a gyűjteményhez
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // vagy 
>      // új szabálykészlet példányának inicializálása
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // szabályok hozzáadása a gyűjteményhez
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // és a meglévő gyűjtemény cseréje az újra a FontsManager-ben 
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
com.aspose.slides.IFontData[] - A betűtípusok tömbje

### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Lekéri a prezentáció renderelése során cserélendő betűtípusokkal kapcsolatos információkat.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Az összes betűtípus helyettesítés gyűjteménye [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Lekéri a megadott diák renderelése során cserélendő betűtípusokkal kapcsolatos információkat.

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
| slides | int[] | Egy tömb a diák indexeivel, amelyekhez a betűtípus helyettesítési információkat le kell kérni, 1-től kezdődően. |

**Visszatérési érték:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Az összes betűtípus helyettesítés ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) a megadott diákra.

### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public final boolean getPreferRegisteredFontsOverEmbedded()
```

Megadja, hogy a regisztrált betűtípusokat részesítsék előnyben a ugyanazt a betűtípusnevet és stílust használó beágyazott betűtípusokkal szemben. Ha engedélyezett, a megfelelő beágyazott betűtípusok ideiglenesen a megfelelő regisztrált betűtípusokkal lesznek helyettesítve exportálás során.

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

Az alapértelmezett **false**.

**Visszatérési érték:**
boolean

### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public final void setPreferRegisteredFontsOverEmbedded(boolean value)
```

Megadja, hogy a regisztrált betűtípusokat részesítsék előnyben a ugyanazt a betűtípusnevet és stílust használó beágyazott betűtípusokkal szemben. Ha engedélyezett, a megfelelő beágyazott betűtípusok ideiglenesen a megfelelő regisztrált betűtípusokkal lesznek helyettesítve exportálás során.

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

Az alapértelmezett **false**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

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

Betűtípus cseréje a prezentációban a [FontSubstRule](../../com.aspose.slides/fontsubstrule) gyűjtemény által biztosított információk alapján

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Betűtípus helyettesítési szabályok gyűjteménye |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Lekéri a bájt tömböt, amely a megadott betűtípus stílushoz és betűtípus adathoz tartozó betűtípust tartalmazza.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // A prezentációban használt összes betűtípus lekérése
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // A prezentációban az első betűtípus normál stílusát reprezentáló bájt tömb lekérése
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | A betűtípus adatobjektum, amely a [IFontData](../../com.aspose.slides/ifontdata) betűtípussal kapcsolatos információkat tartalmaz. |
| fontStyle | int | A betűtípus stílusa, amelyhez az adatot le kell kérni [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Visszatérési érték:**
byte[] - Egy bájt tömb, amely a megadott betűtípus stílushoz tartozó betűtípust tartalmazza. Ha a betűtípus adat vagy a stílus nem található, null értéket ad vissza.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Megállapítja egy betűtípus beágyazási szintjét a megadott bájt tömb és betűtípus név alapján.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // A prezentációban használt összes betűtípus lekérése
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // A prezentációban az első betűtípus normál stílusát reprezentáló bájt tömb lekérése
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
| fontBytes | byte[] | A betűtípust tartalmazó bájt tömb. |
| fontName | java.lang.String | A betűtípus neve. |

**Visszatérési érték:**
int - A megadott betűtípus beágyazási szintje.