---
title: IFontsManager
second_title: Aspose.Slides for Java API-referens
description: Hanterar teckensnitt över presentationen.
type: docs
url: /sv/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Hanterar teckensnitt över presentationen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Fontsubstitutioner att använda vid rendering Läs/skriv [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Fontsubstitutioner att använda vid rendering Läs/skriv [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Representerar en användares samling av FontFallBack-regler för hantering av samlingar av teckensnitt för korrekta substitutioner via fallback-funktionalitet Läs/skriv [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Representerar en användares samling av FontFallBack-regler för hantering av samlingar av teckensnitt för korrekta substitutioner via fallback-funktionalitet Läs/skriv [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Returnerar teckensnitten som används i presentationen |
| [getSubstitutions()](#getSubstitutions--) | Hämtar information om teckensnitt som kommer att ersättas vid presentationens rendering. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Hämtar information om teckensnitt som kommer att ersättas vid rendering av de angivna bilderna. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Returnerar teckensnitten som är inbäddade i presentationen |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Tar bort det inbäddade teckensnittet |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Lägger till det inbäddade teckensnittet. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Lägger till det inbäddade teckensnittet |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Ersätter teckensnitt i presentationen |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Ersätter teckensnitt i presentationen med information som tillhandahålls i [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Ersätter teckensnitt i presentationen med information som tillhandahålls i en samling av [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Hämtar byte-arrayen som representerar teckensnittsdata för en angiven teckensnittsstil och teckensnittsdata. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Bestämmer inbäddningsnivån för ett teckensnitt från den givna byte-arrayen och teckensnittsnamnet. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

Fontsubstitutioner att använda vid rendering Läs/skriv [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Returnerar:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Fontsubstitutioner att använda vid rendering Läs/skriv [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Representerar en användares samling av FontFallBack-regler för hantering av samlingar av teckensnitt för korrekta substitutioner via fallback-funktionalitet Läs/skriv [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

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
>      // initiering av ny instans av regelsamlingen
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

Representerar en användares samling av FontFallBack-regler för hantering av samlingar av teckensnitt för korrekta substitutioner via fallback-funktionalitet Läs/skriv [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

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
>      // initiering av ny instans av regelsamlingen
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

Returnerar teckensnitten som används i presentationen

**Returnerar:**
com.aspose.slides.IFontData[] - En array av teckensnitt
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Hämtar information om teckensnitt som kommer att ersättas vid presentationens rendering.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Samling av alla teckensnitts-substitutioner [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Hämtar information om teckensnitt som kommer att ersättas vid rendering av de angivna bilderna.

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
| slides | int[] | En array av bildindex för vilka teckensnitts-substitutionsinformation ska hämtas, räknat från 1. |

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - En samling av alla teckensnitts-substitutioner ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) för de angivna bilderna.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

Returnerar teckensnitten som är inbäddade i presentationen

**Returnerar:**
com.aspose.slides.IFontData[] - Inbäddade teckensnitt IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

Tar bort det inbäddade teckensnittet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Teckensnittsdatatobjekt [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Lägger till det inbäddade teckensnittet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Teckensnittsdatatobjekt [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Inbäddningsregel för teckensnitt [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Kom ihåg att de flesta teckensnitt är upphovsrättsskyddade när du kopierar dem. Kontrollera teckensnittets licens i förväg och verifiera att de får överföras fritt till en annan maskin. |
### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Lägger till det inbäddade teckensnittet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontData | byte[] | Teckensnittsdata byte[] |
| embedFontRule | int | Inbäddningsregel för teckensnitt [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Kom ihåg att de flesta teckensnitt är upphovsrättsskyddade när du lägger till dem. Kontrollera teckensnittets licens i förväg och verifiera att de får överföras fritt till en annan maskin. |
### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

Ersätt teckensnitt i presentationen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Källteckensnitt |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Destinations-teckensnitt |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

Ersätt teckensnitt i presentationen med information som tillhandahålls i [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Teckensnittssubstitutionsinfo |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Ersätt teckensnitt i presentationen med information som tillhandahålls i en samling av [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Samling av teckensnittssubstitutionsinfo |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Hämtar byte-arrayen som representerar teckensnittsdata för en angiven teckensnittsstil och teckensnittsdata.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Hämta alla teckensnitt som används i presentationen
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Hämta byte-arrayen som representerar den vanliga stilen för det första teckensnittet i presentationen
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Teckensnittsdatatobjektet som innehåller information om teckensnittet [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Stilen på teckensnittet vars data ska hämtas [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Returnerar:**
byte[] - En byte-array som innehåller teckensnittsdata för den angivna teckensnittsstilen. Om teckensnittsdata eller stil inte hittas, returneras null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Bestämmer inbäddningsnivån för ett teckensnitt från den angivna byte-arrayen och teckensnittsnamnet.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Hämta alla teckensnitt som används i presentationen
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Hämta byte-arrayen som representerar den vanliga stilen för det första teckensnittet i presentationen
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Bestäm inbäddningsnivån för teckensnittet
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontBytes | byte[] | Byte-arrayen som innehåller teckensnittsdata. |
| fontName | java.lang.String | Namnet på teckensnittet. |

**Returnerar:**
int - Inbäddningsnivån för det angivna teckensnittet.