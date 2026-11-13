---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
description: A prezentáció betűtípusainak kezelése.
type: docs
url: /hu/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Kezeli a betűtípusokat a prezentációban.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Betűtípus helyettesítések a rendereléshez, Olvasás/írás [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Betűtípus helyettesítések a rendereléshez, Olvasás/írás [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Felhasználó által kezelt FontFallBack szabályok gyűjteménye a betűtípusok megfelelő helyettesítéséhez, Olvasás/írás [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Felhasználó által kezelt FontFallBack szabályok gyűjteménye a betűtípusok megfelelő helyettesítéséhez, Olvasás/írás [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Visszaadja a prezentációban használt betűtípusokat |
| [getSubstitutions()](#getSubstitutions--) | Lekéri a betűtípusokról szóló információkat, amelyeket a prezentáció renderelése során helyettesítenek. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Lekéri a betűtípusokról szóló információkat, amelyeket a megadott diák renderelése során helyettesítenek. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Visszaadja a prezentációba beágyazott betűtípusokat |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Eltávolítja a beágyazott betűtípust |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Hozzáadja a beágyazott betűtípust. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Hozzáadja a beágyazott betűtípust |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Betűtípus cseréje a prezentációban |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Betűtípus cseréje a prezentációban a [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) által megadott információk alapján |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Betűtípus cseréje a prezentációban a [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) gyűjteményében megadott információk alapján |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Visszaadja a megadott betűtípusstílushoz és betűtípusadatokhoz tartozó bájt tömböt. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Meghatározza a betűtípus beágyazási szintjét a megadott bájt tömb és betűtípusnév alapján. |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | Megadja, hogy a regisztrált betűtípusok előnyben részesüljenek-e a beágyazottakkal azonos név és stílus esetén. |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | Megadja, hogy a regisztrált betűtípusok előnyben részesüljenek-e a beágyazottakkal azonos név és stílus esetén. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

Betűtípus helyettesítések a rendereléshez, Olvasás/írás [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Visszatér:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Betűtípus helyettesítések a rendereléshez, Olvasás/írás [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Felhasználó által kezelt FontFallBack szabályok gyűjteménye a betűtípusok megfelelő helyettesítéséhez, Olvasás/írás [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

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

Felhasználó által kezelt FontFallBack szabályok gyűjteménye a betűtípusok megfelelő helyettesítéséhez, Olvasás/írás [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

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
com.aspose.slides.IFontData[] - A betűtípusok tömbje

### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Lekéri a betűtípusokról szóló információkat, amelyeket a prezentáció renderelése során helyettesítenek.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Gyűjtemény az összes betűtípus helyettesítésről [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Lekéri a betűtípusokról szóló információkat, amelyeket a megadott diák renderelése során helyettesítenek.

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
| slides | int[] | Diák indexeinek tömbje, amelyhez a betűtípus helyettesítési információkat le kívánja kérni, 1-től kezdődően. |

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - A megadott diák betűtípus helyettesítéseinek gyűjteménye ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)).

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
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Betűtípus adatobjektum [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Hozzáadja a beágyazott betűtípust.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Betűtípus adatobjektum [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Beágyazott betűtípus szabály [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Tartsd szem előtt, hogy a legtöbb betűtípus szerzői jogvédelem alatt áll. Először keresd meg a betűtípus licencét, és ellenőrizd, hogy szabadon áthelyezhető-e egy másik gépre. |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Hozzáadja a beágyazott betűtípust

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontData | byte[] | Betűtípus adat byte[] |
| embedFontRule | int | Beágyazott betűtípus szabály [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Tartsd szem előtt, hogy a legtöbb betűtípus szerzői jogvédelem alatt áll. Először keresd meg a betűtípus licencét, és ellenőrizd, hogy szabadon áthelyezhető-e egy másik gépre. |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

Betűtípus cseréje a prezentációban

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Forrás betűtípus |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Cél betűtípus |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

Betűtípus cseréje a prezentációban a [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) által megadott információkkal

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Betűtípus helyettesítési információ |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Betűtípus cseréje a prezentációban a [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) gyűjteményében megadott információkkal

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Betűtípus helyettesítési információk gyűjteménye |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Visszaadja a megadott betűtípusstílushoz és betűtípusadatokhoz tartozó bájt tömböt.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // A prezentációban használt összes betűtípus lekérése
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
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | A betűtípus adatobjektum, amely a betűtípusról szóló információkat tartalmaz [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | A betűtípus stílusa, amelynek az adatait le kívánja kérni [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Visszatér:**
byte[] - A megadott betűtípusstílushoz tartozó betűtípusadatokat tartalmazó bájt tömb. Ha a betűtípus adat vagy stílus nem található, null értéket ad vissza.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Meghatározza a betűtípus beágyazási szintjét a megadott bájt tömb és betűtípusnév alapján.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // A prezentációban használt összes betűtípus lekérése
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // A prezentáció első betűtípusának normál stílusát reprezentáló bájt tömb lekérése
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // A betűtípus beágyazási szintjének meghatározása
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontBytes | byte[] | A betűtípus adatot tartalmazó bájt tömb. |
| fontName | java.lang.String | A betűtípus neve. |

**Visszatér:**
int - A megadott betűtípus beágyazási szintje.

### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public abstract boolean getPreferRegisteredFontsOverEmbedded()
```

Megadja, hogy a regisztrált betűtípusok előnyben részesüljenek-e a beágyazottakkal azonos név és stílus esetén. Engedélyezve a megfelelő beágyazott betűtípusok ideiglenesen a regisztráltakra cserélődnek exportáláskor.

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

Alapértelmezett érték **false**.

**Visszatér:**
boolean

### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public abstract void setPreferRegisteredFontsOverEmbedded(boolean value)
```

Megadja, hogy a regisztrált betűtípusok előnyben részesüljenek-e a beágyazottakkal azonos név és stílus esetén. Engedélyezve a megfelelő beágyazott betűtípusok ideiglenesen a regisztráltakra cserélődnek exportáláskor.

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

Alapértelmezett érték **false**.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |