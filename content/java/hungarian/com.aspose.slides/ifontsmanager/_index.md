---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
description: A betűtípusok kezelését végzi a bemutatóban.
type: docs
url: /hu/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

A betűtípusok kezelését végzi a bemutatóban.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Betűtípus helyettesítések a rendereléshez Olvasás/írás [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Betűtípus helyettesítések a rendereléshez Olvasás/írás [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Egy felhasználó FontFallBack szabályainak gyűjteménye a betűtípusok gyűjteményeinek kezelése érdekében, a helyettesítéseket megfelelően a visszaeső funkcióval Olvasás/írás [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Egy felhasználó FontFallBack szabályainak gyűjteménye a betűtípusok gyűjteményeinek kezelése érdekében, a helyettesítéseket megfelelően a visszaeső funkcióval Olvasás/írás [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Visszaadja a bemutatóban használt betűtípusokat |
| [getSubstitutions()](#getSubstitutions--) | Betűtípusokról ad információt, amelyeket a bemutató renderelése során lecserélnek. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Betűtípusokról ad információt, amelyeket a megadott diák renderelése során lecserélnek. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Visszaadja a bemutatóba beágyazott betűtípusokat |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Eltávolítja a beágyazott betűtípust |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Hozzáadja a beágyazott betűtípust. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Hozzáadja a beágyazott betűtípust |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Betűtípust cserél a prezentációban |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Betűtípust cserél a prezentációban a(z) [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) által biztosított információk alapján |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Betűtípust cserél a prezentációban a(z) [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) gyűjteményben szereplő információk alapján |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Lekéri a megadott betűstílushoz és betűtípus adatához tartozó bájt tömböt. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Meghatározza egy betűtípus beágyazási szintjét a megadott bájt tömb és betűtípus név alapján. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```


Betűtípus helyettesítések a rendereléshez Olvasás/írás [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Visszatér:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```


Betűtípus helyettesítések a rendereléshez Olvasás/írás [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```


Egy felhasználó FontFallBack szabályainak gyűjteménye a betűtípusok gyűjteményeinek kezelése érdekében, a helyettesítéseket megfelelően a visszaeső funkcióval Olvasás/írás [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Üres vagy előre inicializált szabálykészlet lekérdezése a FontsManagerből
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // szabályok hozzáadása a gyűteményhez
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // vagy
>      // új szabálykészlet példányának inicializálása
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // szabályok hozzáadása a gyűteményhez
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // és a meglévő gyűtemény cseréje az újra a FontsManagerben 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
>  ```


**Visszatér:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```


Egy felhasználó FontFallBack szabályainak gyűjteménye a betűtípusok gyűjteményeinek kezelése érdekében, a helyettesítéseket megfelelően a visszaeső funkcióval Olvasás/írás [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Üres vagy előre inicializált szabálykészlet lekérdezése a FontsManagerből
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // szabályok hozzáadása a gyűteményhez
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // vagy 
>      // új szabálykészlet példányának inicializálása
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // szabályok hozzáadása a gyűteményhez
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // és a meglévő gyűtemény cseréje az újra a FontsManagerben 
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


Visszaadja a bemutatóban használt betűtípusokat

**Visszatér:**
com.aspose.slides.IFontData[] - Betűtípusok tömbje
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```


Információt ad a bemutató renderelése során lecserélendő betűtípusokról.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Az összes betűtípus helyettesítés [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) gyűjteménye.
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```


Információt ad a megadott diák renderelése során lecserélendő betűtípusokról.

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
| slides | int[] | A diák indexeinek tömbje, amelyekhez a betűtípus helyettesítési információt le kell kérni, 1-től kezdve. |

**Visszatér:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - A megadott diákhoz tartozó összes betűtípus helyettesítés ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) gyűjteménye.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```


Visszaadja a bemutatóba beágyazott betűtípusokat

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

Ne feledje, hogy a betűtípusok többsége szerzői jogvédelem alatt áll. Először keresse meg egy betűtípus licencét, és ellenőrizze, hogy szabadon áthelyezhető-e egy másik gépre. |
### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```


Hozzáadja a beágyazott betűtípust

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontData | byte[] | Betűtípus adat  byte[]  |
| embedFontRule | int | Beágyazott betűtípus szabály [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Ne feledje, hogy a betűtípusok többsége szerzői jogvédelem alatt áll. Először keresse meg egy betűtípus licencét, és ellenőrizze, hogy szabadon áthelyezhető-e egy másik gépre. |
### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```


Betűtípust cserél a prezentációban

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Forrás betűtípus |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Cél betűtípus |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```


Betűtípust cserél a prezentációban a(z) [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) által biztosított információk alapján

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Betűtípus helyettesítési információ |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```


Betűtípust cserél a prezentációban a(z) [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) gyűjteményben szereplő információk alapján

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Betűtípus helyettesítési információ gyűjtemény |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```


Lekéri a megadott betűstílushoz és betűtípus adatához tartozó bájt tömböt.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // A bemutatóban használt összes betűtípus lekérése
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // A bemutató első betűtípusának regular stílusát reprezentáló bájt tömb lekérése
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | A betűtípus adatobjektum, amely a betűtípusról szóló információt tartalmazza [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | A betűtípus stílusa, amelynek az adatát le kell kérni [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Visszatér:**
byte[] - A megadott betűstílushoz tartozó betűtípus adatot tartalmazó bájt tömb. Ha a betűtípus adat vagy a stílus nem található, nullát ad vissza.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```


Meghatározza egy betűtípus beágyazási szintjét a megadott bájt tömb és betűtípus név alapján.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // A bemutatóban használt összes betűtípus lekérése
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // A bemutató első betűtípusának regular stílusát reprezentáló bájt tömb lekérése
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