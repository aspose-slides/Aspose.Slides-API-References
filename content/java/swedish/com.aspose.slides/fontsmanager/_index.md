---
title: FontsManager
second_title: Aspose.Slides för Java API-referens
description: Hanterar typsnitt i hela presentationen.
type: docs
url: /sv/com.aspose.slides/fontsmanager/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

Hantera typsnitt i presentationen.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Load presentation
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Load source font to be replaced
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
>      // Save the presentation
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Typsnittssubstitutioner att använda vid rendering. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Typsnittssubstitutioner att använda vid rendering. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Representerar en användares samling av FontFallBack-regler för hantering av samlingar av typsnitt för korrekta substitutioner via reservfunktion Läs/skriv [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Representerar en användares samling av FontFallBack-regler för hantering av samlingar av typsnitt för korrekta substitutioner via reservfunktion Läs/skriv [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Returnerar de typsnitt som används i presentationen |
| [getSubstitutions()](#getSubstitutions--) | Hämtar information om typsnitt som kommer att ersättas vid presentationens rendering. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Hämtar information om typsnitt som kommer att ersättas vid rendering av de angivna bilderna. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Returnerar de inbäddade typsnitten i presentationen |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Tar bort det inbäddade typsnittet |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Lägger till det inbäddade typsnittet |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Lägger till det inbäddade typsnittet |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Ersätt typsnitt i presentationen |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Ersätt typsnitt i presentationen med information som tillhandahålls i [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Ersätt typsnitt i presentationen med information som tillhandahålls i samlingen av [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Hämtar bytearrayen som representerar typsnittsdatan för en angiven typsnittsstil och typsnittsdatan. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Bestämmer inbäddningsnivån för ett typsnitt från den givna bytearrayen och typsnittsnamnet. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```


Typsnittssubstitutioner att använda vid rendering. Läs/skriv [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Returnerar:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```


Typsnittssubstitutioner att använda vid rendering. Läs/skriv [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```


Representerar en användares samling av FontFallBack-regler för hantering av samlingar av typsnitt för korrekta substitutioner via reservfunktion Läs/skriv [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Hämtar en tom eller förinitialiserad reglersamling från FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // lägger till regler i samlingen
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // eller 
>      // initialisering av en ny instans av reglersamlingen
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // lägger till regler i samlingen
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // och ersätter den befintliga samlingen med den nya i FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```


Representerar en användares samling av FontFallBack-regler för hantering av samlingar av typsnitt för korrekta substitutioner via reservfunktion Läs/skriv [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Hämtar en tom eller förinitialiserad reglersamling från FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // lägger till regler i samlingen
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // eller 
>      // initialisering av en ny instans av reglersamlingen
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // lägger till regler i samlingen
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // och ersätter den befintliga samlingen med den nya i FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public final IFontData[] getFonts()
```


Returnerar de typsnitt som används i presentationen

**Returnerar:**
com.aspose.slides.IFontData[] - En array av typsnitt
### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```


Hämtar information om typsnitt som kommer att ersättas vid presentationens rendering.

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


**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Samling av alla typsnittssubstitutioner [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```


Hämtar information om typsnitt som kommer att ersättas vid rendering av de angivna bilderna.

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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slides | int[] | En array av bildindex för vilka typsnittssubstitutionsinformation ska hämtas, med start från 1. |

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - En samling av alla typsnittssubstitutioner ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) för de angivna bilderna.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```


Returnerar de inbäddade typsnitten i presentationen

**Returnerar:**
com.aspose.slides.IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```


Tar bort det inbäddade typsnittet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```


Lägger till det inbäddade typsnittet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```


Lägger till det inbäddade typsnittet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```


Ersätt typsnitt i presentationen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Källtypsnitt |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Destinations typsnitt |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```


Ersätt typsnitt i presentationen med information som tillhandahålls i [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Typsnittssubstitutionsinfo |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```


Ersätt typsnitt i presentationen med information som tillhandahålls i samlingen av [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Samling av typsnittssubstitutionsregler |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```


Hämtar bytearrayen som representerar typsnittsdatan för en angiven typsnittsstil och typsnittsdatan.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Hämta alla typsnitt som används i presentationen
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Hämta bytearrayen som representerar den vanliga stilen för det första typsnittet i presentationen
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Fontdataobjektet som innehåller information om typsnittet [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Stilen på typsnittet för vilket datan ska hämtas [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Returnerar:**
byte[] - En bytearray som innehåller typsnittsdatan för den angivna typsnittsstilen. Om typsnittsdatan eller stilen inte hittas, returneras null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```


Bestämmer inbäddningsnivån för ett typsnitt från den givna bytearrayen och typsnittsnamnet.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Hämta alla typsnitt som används i presentationen
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Hämta bytearrayen som representerar den vanliga stilen för det första typsnittet i presentationen
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // Bestäm inbäddningsnivån för typsnittet
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontBytes | byte[] | Bytearrayen som innehåller typsnittsdatan. |
| fontName | java.lang.String | Typsnittsnamnet. |

**Returnerar:**
int - Inbäddningsnivån för det angivna typsnittet.