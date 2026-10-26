---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
description: Beheert lettertypen in de presentatie.
type: docs
url: /nl/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Beheert lettertypen in de presentatie.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Lettertype-substituties die te gebruiken zijn bij het renderen Lezen/Schrijven [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Lettertype-substituties die te gebruiken zijn bij het renderen Lezen/Schrijven [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Vertegenwoordigt een verzameling van FontFallBack-regels van een gebruiker voor het beheren van collecties van lettertypen voor juiste substituties via fallback-functionaliteit Lezen/Schrijven [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Vertegenwoordigt een verzameling van FontFallBack-regels van een gebruiker voor het beheren van collecties van lettertypen voor juiste substituties via fallback-functionaliteit Lezen/Schrijven [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Retourneert de lettertypen die in de presentatie worden gebruikt |
| [getSubstitutions()](#getSubstitutions--) | Haalt de informatie op over lettertypen die bij het renderen van de presentatie zullen worden vervangen. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Haalt de informatie op over lettertypen die tijdens het renderen van de opgegeven dia's zullen worden vervangen. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Retourneert de ingebedde lettertypen in de presentatie |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Verwijdert het ingebedde lettertype |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Voegt het ingebedde lettertype toe. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Voegt het ingebedde lettertype toe |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Vervangt lettertype in de presentatie |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Vervangt lettertype in de presentatie met behulp van informatie verstrekt in [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Vervangt lettertype in de presentatie met behulp van informatie verstrekt in collectie van [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Haalt de byte-array op die de lettertype-gegevens vertegenwoordigt voor een opgegeven lettertype-stijl en lettertype-gegevens. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Bepaalt het inbeddings-niveau van een lettertype op basis van de opgegeven byte-array en lettertype-naam. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

Lettertype-substituties die te gebruiken zijn bij het renderen Lezen/Schrijven [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Retour:**  
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Lettertype-substituties die te gebruiken zijn bij het renderen Lezen/Schrijven [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Vertegenwoordigt een verzameling van FontFallBack-regels van een gebruiker voor het beheren van collecties van lettertypen voor juiste substituties via fallback-functionaliteit Lezen/Schrijven [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Lezen van een lege of vooraf geïnitialiseerde regels-collectie van FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // regels toevoegen aan collectie
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // of 
>      // initialisatie van een nieuw exemplaar van de regels-collectie
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // regels toevoegen aan collectie
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // en vervangen van de bestaande collectie door de nieuwe in FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retour:**  
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Vertegenwoordigt een verzameling van FontFallBack-regels van een gebruiker voor het beheren van collecties van lettertypen voor juiste substituties via fallback-functionaliteit Lezen/Schrijven [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Lezen van een lege of vooraf geïnitialiseerde regels-collectie van FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // regels toevoegen aan collectie
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // of 
>      // initialisatie van een nieuw exemplaar van de regels-collectie
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // regels toevoegen aan collectie
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // en vervangen van de bestaande collectie door de nieuwe in FontsManager 
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

**Retour:**  
com.aspose.slides.IFontData[] - Een array van lettertypen
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Haalt de informatie op over lettertypen die bij het renderen van de presentatie zullen worden vervangen.

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


**Retour:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Collectie van alle lettertype-substituties [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| slides | int[] | Een array van dia-indexen waarvoor de lettertype-substitutie-informatie moet worden opgehaald, beginnend bij 1. |

**Retour:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Een collectie van alle lettertype-substituties ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) voor de opgegeven dia's.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

Retourneert de ingebedde lettertypen in de presentatie

**Retour:**  
com.aspose.slides.IFontData[] - Ingebedde lettertypen IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

Verwijdert het ingebedde lettertype

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Lettertype-gegevensobject [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Voegt het ingebedde lettertype toe.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Lettertype-gegevensobject [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Ingebedde lettertype-regel [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Houd er rekening mee dat de meeste lettertypen auteursrechtelijk beschermd zijn. Zoek eerst de licentie van een lettertype op en controleer of het vrij kan worden overgedragen naar een andere machine. |
### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Voegt het ingebedde lettertype toe

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontData | byte[] | Lettertype-gegevens byte[] |
| embedFontRule | int | Ingebedde lettertype-regel [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Houd er rekening mee dat de meeste lettertypen auteursrechtelijk beschermd zijn. Zoek eerst de licentie van een lettertype op en controleer of het vrij kan worden overgedragen naar een andere machine. |
### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

Vervangt lettertype in de presentatie

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Bron-lettertype |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Doel-lettertype |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

Vervangt lettertype in de presentatie met behulp van informatie verstrekt in [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Lettertype-substitutie-informatie |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Vervangt lettertype in de presentatie met behulp van informatie verstrekt in collectie van [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

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
>      // Haal de byte array op die de reguliere stijl van het eerste lettertype in de presentatie vertegenwoordigt
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Het lettertype-gegevensobject dat de informatie over het lettertype bevat [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | De stijl van het lettertype waarvoor de gegevens moeten worden opgehaald [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Retour:**  
byte[] - Een byte-array die de lettertype-gegevens bevat voor de opgegeven lettertype-stijl. Als de lettertype-gegevens of stijl niet worden gevonden, wordt null geretourneerd.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Bepaalt het inbeddings-niveau van een lettertype op basis van de opgegeven byte-array en lettertype-naam.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Haal alle lettertypen op die in de presentatie worden gebruikt
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Haalt de byte array op die de reguliere stijl van het eerste lettertype in de presentatie vertegenwoordigt
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Bepaal het inbeddings niveau van het lettertype
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

**Retour:**  
int - Het inbeddings-niveau van het opgegeven lettertype.