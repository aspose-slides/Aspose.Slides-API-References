---
title: IFontsManager
second_title: Aspose.Slides för Android via Java API-referens
description: Hanterar typsnitt i hela presentationen.
type: docs
url: /sv/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Hantera typsnitt i hela presentationen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Typsnittsersättningar att använda vid rendering Läs/skriv [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Typsnitts ersättningar att använda vid rendering Läs/skriv [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Representerar en användares samling av FontFallBack-regler för hantering av typsnittssamlingar för korrekta ersättningar via fallback-funktionalitet Läs/skriv [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Representerar en användares samling av FontFallBack-regler för hantering av typsnittssamlingar för korrekta ersättningar via fallback-funktionalitet Läs/skriv [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Returnerar de typsnitt som används i presentationen |
| [getSubstitutions()](#getSubstitutions--) | Hämtar information om typsnitt som kommer att ersättas vid presentationens rendering. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Hämtar information om typsnitt som kommer att ersättas vid rendering av de angivna bilderna. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Returnerar de inbäddade typsnitten i presentationen |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Tar bort det inbäddade typsnittet |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Lägger till det inbäddade typsnittet. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Lägger till det inbäddade typsnittet |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Ersätt typsnitt i presentationen |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Ersätt typsnitt i presentationen med information som tillhandahålls i [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Ersätt typsnitt i presentationen med information som tillhandahålls i samling av [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Hämtar bytearrayen som representerar typsnittsdata för en angiven typsnittsstil och typsnittsdata. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Bestämmer inbäddningsnivån för ett typsnitt från den givna bytearrayen och typsnittsnamnet. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

Typsnitts ersättningar att använda vid rendering Läs/skriv [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Returnerar:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Typsnitts ersättningar att använda vid rendering Läs/skriv [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Representerar en användares samling av FontFallBack-regler för hantering av typsnittssamlingar för korrekta ersättningar via fallback-funktionalitet Läs/skriv [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Hämtar en tom eller förinitierad regelsamling från FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // lägger till regler i samlingen
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // eller 
>      // initiering av ny instans av regelsamling
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // lägger till regler i samlingen
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // och ersätter befintlig samling med den nya i FontsManager 
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
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Representerar en användares samling av FontFallBack-regler för hantering av typsnittssamlingar för korrekta ersättningar via fallback-funktionalitet Läs/skriv [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Hämtar en tom eller förinitierad regelsamling från FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // lägger till regler i samlingen
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // eller 
>      // initiering av ny instans av regelsamling
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // lägger till regler i samlingen
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // och ersätter befintlig samling med den nya i FontsManager 
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
public abstract IFontData[] getFonts()
```

Returnerar de typsnitt som används i presentationen

**Returnerar:**
com.aspose.slides.IFontData[] - En array av typsnitt

### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Samling av alla typsnitts ersättningar [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
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
| slides | int[] | En array av bildindex för vilka typsnitts ersättningsinformation ska hämtas, med start från 1. |

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - En samling av alla typsnitts ersättningar ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) för de angivna bilderna.

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

Returnerar de inbäddade typsnitten i presentationen

**Returnerar:**
com.aspose.slides.IFontData[] - Inbäddade typsnitt IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

Tar bort det inbäddade typsnittet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Typsnittsdataobjekt [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Lägger till det inbäddade typsnittet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Typsnittsdataobjekt [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Inbäddningsregel för typsnitt [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Tänk på att de flesta typsnitt är upphovsrättsskyddade när du kopierar dem. Lokalisera först licensen för ett typsnitt i förväg och kontrollera att det kan överföras fritt till en annan maskin. |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Lägger till det inbäddade typsnittet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontData | byte[] | Typsnittsdata  byte[]  |
| embedFontRule | int | Inbäddningsregel för typsnitt [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Tänk på att de flesta typsnitt är upphovsrättsskyddade när du lägger till dem. Lokalisera först licensen för ett typsnitt i förväg och kontrollera att det kan överföras fritt till en annan maskin. |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

Ersätt typsnitt i presentationen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Källtypsnitt |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Måttypsnitt |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

Ersätt typsnitt i presentationen med information som tillhandahålls i [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Typsnitts ersättningsinfo |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Ersätt typsnitt i presentationen med information som tillhandahålls i samling av [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Samling av typsnitts ersättningsinfo |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Hämtar bytearrayen som representerar typsnittsdata för en angiven typsnittsstil och typsnittsdata.

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
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Typsnittsdataobjektet som innehåller information om typsnittet [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Stilen på typsnittet som data ska hämtas för [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Returnerar:**
byte[] - En bytearray som innehåller typsnittsdata för den angivna typsnittsstilen. Om typsnittsdata eller stil inte hittas, returneras null.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Bestämmer inbäddningsnivån för ett typsnitt från den givna bytearrayen och typsnittsnamnet.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Hämta alla typsnitt som används i presentationen
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Hämta bytearrayen som representerar den vanliga stilen för det första typsnittet i presentationen
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Bestäm inbäddningsnivån för typsnittet
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontBytes | byte[] | Bytearrayen som innehåller typsnittsdata. |
| fontName | java.lang.String | Namnet på typsnittet. |

**Returnerar:**
int - Inbäddningsnivån för det angivna typsnittet.