---
title: FontsManager
second_title: Aspose.Slides för Java API-referens
description: Hanterar teckensnitt i hela presentationen.
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

Hanterar teckensnitt i presentationen.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Ladda presentationen
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Ladda källteckensnitt som ska ersättas
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
>      // Spara presentationen
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Teckensnittsersättningar att använda vid rendering. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Teckensnittsersättningar att använda vid rendering. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Representerar en användares samling av FontFallBack-regler för hantering av samlingar av teckensnitt för korrekta ersättningar via fallback-funktionalitet Läs/skriv [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Representerar en användares samling av FontFallBack-regler för hantering av samlingar av teckensnitt för korrekta ersättningar via fallback-funktionalitet Läs/skriv [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Returnerar de teckensnitt som används i presentationen |
| [getSubstitutions()](#getSubstitutions--) | Hämtar information om teckensnitt som kommer att ersättas vid presentationens rendering. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Hämtar information om teckensnitt som kommer att ersättas under rendering av de specificerade bilderna. |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | Anger om registrerade teckensnitt ska föredras framför inbäddade teckensnitt med samma namn och stil. |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | Anger om registrerade teckensnitt ska föredras framför inbäddade teckensnitt med samma namn och stil. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Returnerar de teckensnitt som är inbäddade i presentationen |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Tar bort det inbäddade teckensnittet |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Lägger till det inbäddade teckensnittet |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Lägger till det inbäddade teckensnittet |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Ersätt teckensnitt i presentationen |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Ersätt teckensnitt i presentationen med information som tillhandahålls i [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Ersätt teckensnitt i presentationen med information som tillhandahålls i samling av [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Hämtar bytearrayen som representerar teckensnittsdata för en specificerad teckensnittsstil och teckensnittsdata. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Bestämmer inbäddningsnivån för ett teckensnitt från den angivna bytearrayen och teckensnittsnamnet. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

Teckensnittsersättningar att använda vid rendering. Läs/skriv [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Returnerar:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Teckensnittsersättningar att använda vid rendering. Läs/skriv [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Representerar en användares samling av FontFallBack-regler för hantering av samlingar av teckensnitt för korrekta ersättningar via fallback-funktionalitet Läs/skriv [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Hämtar tom eller förinitierad regelkollektion från FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // Lägger till regler i kollektionen
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // eller 
>      // Initiering av en ny instans av regelkollektionen
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // Lägger till regler i kollektionen
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // Och ersätter befintlig kollektion med den nya i FontsManager 
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

Representerar en användares samling av FontFallBack-regler för hantering av samlingar av teckensnitt för korrekta ersättningar via fallback-funktionalitet Läs/skriv [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Hämtar tom eller förinitierad regelkollektion från FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // Lägger till regler i kollektionen
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // eller 
>      // Initiering av en ny instans av regelkollektionen
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // Lägger till regler i kollektionen
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // och ersätter befintlig kollektion med den nya i FontsManager 
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

Returnerar de teckensnitt som används i presentationen

**Returnerar:**
com.aspose.slides.IFontData[] - En array av teckensnitt

### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Samling av alla teckensnitts ersättningar [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Hämtar information om teckensnitt som kommer att ersättas under rendering av de specificerade bilderna.

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
| slides | int[] | En array av bildindex för vilka teckensnittsersättningsinformation ska hämtas, med start från 1. |

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - En samling av alla teckensnitts ersättningar ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) för de specificerade bilderna.

### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public final boolean getPreferRegisteredFontsOverEmbedded()
```

Anger om registrerade teckensnitt ska föredras framför inbäddade teckensnitt med samma namn och stil. När aktiverad ersätts matchande inbäddade teckensnitt tillfälligt med motsvarande registrerade teckensnitt under export.

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

Standard är **false**.

**Returnerar:**
boolean

### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public final void setPreferRegisteredFontsOverEmbedded(boolean value)
```

Anger om registrerade teckensnitt ska föredras framför inbäddade teckensnitt med samma namn och stil. När aktiverad ersätts matchande inbäddade teckensnitt tillfälligt med motsvarande registrerade teckensnitt under export.

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

Standard är **false**.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

Returnerar de teckensnitt som är inbäddade i presentationen

**Returnerar:**
com.aspose.slides.IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

Tar bort det inbäddade teckensnittet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Lägger till det inbäddade teckensnittet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Lägger till det inbäddade teckensnittet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

Ersätt teckensnitt i presentationen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Källteckensnitt |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Måtteckensnitt |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

Ersätt teckensnitt i presentationen med information som tillhandahålls i [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Information om teckensnittsersättning |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

Ersätt teckensnitt i presentationen med information som tillhandahålls i samling av [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Samling av teckensnittsersättningsregler |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Hämtar bytearrayen som representerar teckensnittsdata för en specificerad teckensnittsstil och teckensnittsdata.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Hämta alla teckensnitt som används i presentationen
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Hämta bytearrayen som representerar den vanliga stilen för det första teckensnittet i presentationen
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Teckensnittsdataobjektet som innehåller information om teckensnittet [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Stilen på teckensnittet för vilken data ska hämtas [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Returnerar:**
byte[] - En bytearray som innehåller teckensnittsdata för den specificerade teckensnittsstilen. Om teckensnittsdata eller stil inte hittas, returneras null.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Bestämmer inbäddningsnivån för ett teckensnitt från den givna bytearrayen och teckensnittsnamnet.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Hämta alla teckensnitt som används i presentationen
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Hämta bytearrayen som representerar den vanliga stilen för det första teckensnittet i presentationen
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // Bestäm inbäddningsnivån för teckensnittet
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontBytes | byte[] | Bytearrayen som innehåller teckensnittsdata. |
| fontName | java.lang.String | Namnet på teckensnittet. |

**Returnerar:**
int - Inbäddningsnivån för det specificerade teckensnittet.