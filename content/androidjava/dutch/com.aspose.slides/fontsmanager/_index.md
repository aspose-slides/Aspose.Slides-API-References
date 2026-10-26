---
title: FontsManager
second_title: Aspose.Slides voor Android via Java API-referentie
description: Beheert lettertypen in de presentatie.
type: docs
url: /nl/com.aspose.slides/fontsmanager/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

Beheert lettertypen in de presentatie.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Laad presentatie
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Laad bronlettertype om te vervangen
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
>      // Sla de presentatie op
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Methoden

| Methode | Omschrijving |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Lettertype-substituties om te gebruiken bij het renderen. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Lettertype-substituties om te gebruiken bij het renderen. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Vertegenwoordigt een verzameling FontFallBack-regels van de gebruiker voor het beheren van collecties van lettertypen voor correcte substituties via fallback-functionaliteit Lezen/schrijven [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Vertegenwoordigt een verzameling FontFallBack-regels van de gebruiker voor het beheren van collecties van lettertypen voor correcte substituties via fallback-functionaliteit Lezen/schrijven [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Retourneert de in de presentatie gebruikte lettertypen |
| [getSubstitutions()](#getSubstitutions--) | Haalt de informatie op over lettertypen die tijdens het renderen van de presentatie zullen worden vervangen. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Haalt de informatie op over lettertypen die tijdens het renderen van de opgegeven dia's zullen worden vervangen. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Retourneert de ingebedde lettertypen in de presentatie |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Verwijdert het ingebedde lettertype |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Voegt het ingebedde lettertype toe |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Voegt het ingebedde lettertype toe |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Vervang lettertype in presentatie |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Vervang lettertype in presentatie met informatie voorzien in [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Vervang lettertype in presentatie met informatie voorzien in collectie van [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Haalt de byte-array op die de lettertype-gegevens voor een opgegeven lettertype-stijl en fontgegevens weergeeft. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Bepaalt het insluitingsniveau van een lettertype op basis van de gegeven byte-array en lettertype-naam. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

Lettertype-substituties om te gebruiken bij het renderen. Lezen/schrijven [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Retourneert:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Lettertype-substituties om te gebruiken bij het renderen. Lezen/schrijven [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Vertegenwoordigt een verzameling FontFallBack-regels van de gebruiker voor het beheren van collecties van lettertypen voor correcte substituties via fallback-functionaliteit Lezen/schrijven [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Ophalen van lege of vooraf geïnitialiseerde regelsverzameling van FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // regels toevoegen aan verzameling
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // of 
>      // initialisatie van nieuwe instantie van regelsverzameling
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // regels toevoegen aan verzameling
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // en het vervangen van de bestaande verzameling door de nieuwe in FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Vertegenwoordigt een verzameling FontFallBack-regels van de gebruiker voor het beheren van collecties van lettertypen voor correcte substituties via fallback-functionaliteit Lezen/schrijven [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Ophalen van lege of vooraf geïnitialiseerde regelsverzameling van FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // regels toevoegen aan verzameling
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // of 
>      // initialisatie van nieuwe instantie van regelsverzameling
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // regels toevoegen aan verzameling
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // en het vervangen van de bestaande verzameling door de nieuwe in FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public final IFontData[] getFonts()
```

Retourneert de in de presentatie gebruikte lettertypen

**Retourneert:**
com.aspose.slides.IFontData[] - Een array van lettertypen
### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Haalt de informatie op over lettertypen die tijdens het renderen van de presentatie zullen worden vervangen.

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


**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Verzameling van alle lettertype-substituties [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Haalt de informatie op over lettertypen die tijdens het renderen van de opgegeven dia's zullen worden vervangen.

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


**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| slides | int[] | Een array van dia-indexen waarvoor de lettertype-substitutie-informatie moet worden opgehaald, beginnend bij 1. |

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Een verzameling van alle lettertype-substituties ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) voor de opgegeven dia's.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

Retourneert de ingebedde lettertypen in de presentatie

**Retourneert:**
com.aspose.slides.IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

Verwijdert het ingebedde lettertype

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Voegt het ingebedde lettertype toe

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Voegt het ingebedde lettertype toe

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

Vervang lettertype in presentatie

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Bronlettertype |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Doellettertype |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

Vervang lettertype in presentatie met informatie voorzien in [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Lettertype-substitutie-info |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

Vervang lettertype in presentatie met informatie voorzien in collectie van [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Collectie van lettertype-substitutieregels |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Haalt de byte-array op die de lettertype-gegevens voor een opgegeven lettertype-stijl en fontgegevens weergeeft.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Haal alle lettertypen op die in de presentatie worden gebruikt
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Haal de byte-array op die de gewone stijl van het eerste lettertype in de presentatie weergeeft
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Het lettertype-object met de informatie over het lettertype [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | De stijl van het lettertype waarvoor de gegevens moeten worden opgehaald [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Retourneert:**
byte[] - Een byte-array die de lettertype-gegevens bevat voor de opgegeven lettertype-stijl. Als de lettertype-gegevens of stijl niet worden gevonden, retourneert null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Bepaalt het insluitingsniveau van een lettertype op basis van de gegeven byte-array en lettertype-naam.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Haal alle lettertypen op die in de presentatie worden gebruikt
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Haal de byte-array op die de gewone stijl van het eerste lettertype in de presentatie weergeeft
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // Bepaal het insluitingsniveau van het lettertype
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| fontBytes | byte[] | De byte-array met de lettertype-gegevens. |
| fontName | java.lang.String | De naam van het lettertype. |

**Retourneert:**
int - Het insluitingsniveau van het opgegeven lettertype.