---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
description: Manages fonts across the presentation.
type: docs
url: /nl/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Beheert lettertypen in de presentatie.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Lettertype-substituties om te gebruiken bij het renderen Lezen/Schrijven [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Lettertype-substituties om te gebruiken bij het renderen Lezen/Schrijven [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Lezen/Schrijven [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Lezen/Schrijven [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Retourneert de lettertypen die in de presentatie worden gebruikt |
| [getSubstitutions()](#getSubstitutions--) | Haalt de informatie op over lettertypen die tijdens het renderen van de presentatie worden vervangen. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Haalt de informatie op over lettertypen die tijdens het renderen van de opgegeven slides zullen worden vervangen. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Retourneert de ingesloten lettertypen in de presentatie |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Verwijdert het ingesloten lettertype |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Voegt het ingesloten lettertype toe. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Voegt het ingesloten lettertype toe |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Vervang lettertype in de presentatie |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Vervang lettertype in de presentatie met behulp van de informatie geleverd in [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Vervang lettertype in de presentatie met behulp van de informatie geleverd in collectie van [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Haalt de byte-array op die de lettertypegegevens vertegenwoordigt voor een opgegeven lettertype-stijl en lettertype-gegevens. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Bepaalt het insluitingsniveau van een lettertype op basis van de gegeven byte-array en lettertype-naam. |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | Specificeert of geregistreerde lettertypen de voorkeur moeten krijgen boven ingesloten lettertypen met dezelfde naam en stijl. |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | Specificeert of geregistreerde lettertypen de voorkeur moeten krijgen boven ingesloten lettertypen met dezelfde naam en stijl. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

Lettertype-substituties om te gebruiken bij het renderen Lezen/Schrijven [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Retourneert:**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Lettertype-substituties om te gebruiken bij het renderen Lezen/Schrijven [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Vertegenwoordigt een collectie van FontFallBack-regels van een gebruiker voor het beheer van lettertypecollecties voor juiste substituties via fallback-functionaliteit Lezen/Schrijven [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Ophalen van lege of vooraf geïnitialiseerde regelsverzameling van FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // toevoegen van regels aan verzameling
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // of 
>      // initialisatie van een nieuw exemplaar van regelsverzameling
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // toevoegen van regels aan verzameling
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // en vervangen van de bestaande verzameling door de nieuwe in FontsManager 
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
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Vertegenwoordigt een collectie van FontFallBack-regels van een gebruiker voor het beheer van lettertypecollecties voor juiste substituties via fallback-functionaliteit Lezen/Schrijven [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Ophalen van lege of vooraf geïnitialiseerde regelsverzameling van FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // toevoegen van regels aan verzameling
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // of 
>      // initialisatie van een nieuw exemplaar van regelsverzameling
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // toevoegen van regels aan verzameling
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // en vervangen van de bestaande verzameling door de nieuwe in FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public abstract IFontData[] getFonts()
```

Retourneert de lettertypen die in de presentatie worden gebruikt

**Retourneert:**
com.aspose.slides.IFontData[] - Een array van lettertypen

### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Haalt de informatie op over lettertypen die tijdens het renderen van de presentatie worden vervangen.

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Collectie van alle lettertype-substituties [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Haalt de informatie op over lettertypen die tijdens het renderen van de opgegeven slides zullen worden vervangen.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| slides | int[] | Een array van slide-indexen waarvoor de informatie over lettertype-substitutie opgehaald moet worden, beginnend bij 1. |

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Een collectie van alle lettertype-substituties ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) voor de opgegeven slides.

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

Retourneert de ingesloten lettertypen in de presentatie

**Retourneert:**
com.aspose.slides.IFontData[] - Ingesloten lettertypen IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

Verwijdert het ingesloten lettertype

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Lettertype-datobject [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Voegt het ingesloten lettertype toe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Lettertype-datobject [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Ingesloten lettertype-regel [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Houd er rekening mee bij het kopiëren van lettertypen dat de meeste lettertypen auteursrechtelijk beschermd zijn. Zoek eerst de licentie van een lettertype op en controleer of ze vrij kunnen worden overgedragen naar een andere machine. |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Voegt het ingesloten lettertype toe

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontData | byte[] | Lettertype-gegevens byte[] |
| embedFontRule | int | Ingesloten lettertype-regel [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Houd er rekening mee bij het toevoegen van lettertypen dat de meeste lettertypen auteursrechtelijk beschermd zijn. Zoek eerst de licentie van een lettertype op en controleer of ze vrij kunnen worden overgedragen naar een andere machine. |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

Vervang lettertype in de presentatie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Bronlettertype |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Doellettertype |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

Vervang lettertype in de presentatie met behulp van de informatie geleverd in [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Lettertype-substitutie-informatie |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Vervang lettertype in de presentatie met behulp van de informatie geleverd in collectie van [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Collectie van lettertype-substitutie-informatie |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Haalt de byte-array op die de lettertype-gegevens vertegenwoordigt voor een opgegeven lettertype-stijl en lettertype-gegevens.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Haal alle lettertypen op die in de presentatie worden gebruikt
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Verkrijg de byte-array die de reguliere stijl van het eerste lettertype in de presentatie vertegenwoordigt
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Het lettertype-datobject dat de informatie over het lettertype [IFontData](../../com.aspose.slides/ifontdata) bevat. |
| fontStyle | int | De stijl van het lettertype waarvoor de gegevens moeten worden opgehaald [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Retourneert:**
byte[] - Een byte-array met de lettertype-gegevens voor de opgegeven lettertype-stijl. Als de lettertype-gegevens of stijl niet gevonden worden, retourneert null.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Bepaalt het insluitingsniveau van een lettertype op basis van de gegeven byte-array en lettertype-naam.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Haal alle lettertypen op die in de presentatie worden gebruikt
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Verkrijg de byte-array die de reguliere stijl van het eerste lettertype in de presentatie vertegenwoordigt
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Bepaal het insluitingsniveau van het lettertype
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontBytes | byte[] | De byte-array die de lettertype-gegevens bevat. |
| fontName | java.lang.String | De naam van het lettertype. |

**Retourneert:**
int - Het insluitingsniveau van het opgegeven lettertype.

### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public abstract boolean getPreferRegisteredFontsOverEmbedded()
```

Specificeert of geregistreerde lettertypen de voorkeur moeten krijgen boven ingesloten lettertypen met dezelfde naam en stijl. Indien ingeschakeld, worden overeenkomende ingesloten lettertypen tijdelijk vervangen door de overeenkomstige geregistreerde lettertypen tijdens export.

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

Default is  **false** .

**Retourneert:**
boolean

### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public abstract void setPreferRegisteredFontsOverEmbedded(boolean value)
```

Specificeert of geregistreerde lettertypen de voorkeur moeten krijgen boven ingesloten lettertypen met dezelfde naam en stijl. Indien ingeschakeld, worden overeenkomende ingesloten lettertypen tijdelijk vervangen door de overeenkomstige geregistreerde lettertypen tijdens export.

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

Default is  **false** .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |