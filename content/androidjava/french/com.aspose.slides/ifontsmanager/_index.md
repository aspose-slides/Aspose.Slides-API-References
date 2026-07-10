---
title: IFontsManager
second_title: Aspose.Slides for Android via Java API Reference
description: Gère les polices à travers la présentation.
type: docs
url: /fr/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Gère les polices à travers la présentation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Substitutions de police à utiliser lors du rendu Lecture/écriture [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Substitutions de police à utiliser lors du rendu Lecture/écriture [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Représente la collection d'un utilisateur de règles FontFallBack pour la gestion des collections de polices afin de permettre des substitutions appropriées grâce à la fonctionnalité de secours Lecture/écriture [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Représente la collection d'un utilisateur de règles FontFallBack pour la gestion des collections de polices afin de permettre des substitutions appropriées grâce à la fonctionnalité de secours Lecture/écriture [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Renvoie les polices utilisées dans la présentation |
| [getSubstitutions()](#getSubstitutions--) | Obtient les informations sur les polices qui seront remplacées lors du rendu de la présentation. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Obtient les informations sur les polices qui seront remplacées lors du rendu des diapositives spécifiées. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Renvoie les polices incorporées dans la présentation |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Supprime la police incorporée |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Ajoute la police incorporée. |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Ajoute la police incorporée |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Remplace la police dans la présentation |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Remplace la police dans la présentation en utilisant les informations fournies dans [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Remplace la police dans la présentation en utilisant les informations fournies dans la collection de [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Récupère le tableau d'octets représentant les données de police pour un style de police et des données de police spécifiés. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Détermine le niveau d'incorporation d'une police à partir du tableau d'octets fourni et du nom de la police. |
### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public abstract IFontSubstRuleCollection getFontSubstRuleList()
```

Substitutions de police à utiliser lors du rendu Lecture/écriture [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Renvoie :**
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Substitutions de police à utiliser lors du rendu Lecture/écriture [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public abstract IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Représente la collection d'un utilisateur de règles FontFallBack pour la gestion des collections de polices afin de permettre des substitutions appropriées grâce à la fonctionnalité de secours Lecture/écriture [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Getting of empty or preinitialized rules collection from FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // adding of rules to collection
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // or 
>      // initialization of new instance of rules collection
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // adding of rules to collection
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // and replacing of existing collection by the new one in FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Read/write [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Obtention d'une collection de règles vide ou préinitialisée depuis FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // ajout de règles à la collection
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ou 
>      // initialisation d'une nouvelle instance de collection de règles
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // ajout de règles à la collection
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // et remplacement de la collection existante par la nouvelle dans FontsManager 
>      pres.getFontsManager().setFontFallBackRulesCollection(rulesList);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public abstract IFontData[] getFonts()
```

Returns the fonts used in the presentation

**Returns:**
com.aspose.slides.IFontData[] - An array of fonts
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Gets the information about fonts that will be replaced on the presentation's rendering.

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

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Collection of all fonts substitution [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Gets the information about fonts that will be replaced during rendering of the specified slides.

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
| Parameter | Type | Description |
| --- | --- | --- |
| slides | int[] | An array of slide indexes for which to retrieve font substitution information, starting from 1. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - A collection of all font substitutions ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) for the specified slides.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

Returns the fonts embedded in the presentation

**Returns:**
com.aspose.slides.IFontData[] - Embedded fonts IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

Removes the embedded font

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Font data object [IFontData](../../com.aspose.slides/ifontdata) |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Adds the embedded font.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Font data object [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Embedded font rule [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Keep in mind when copying any fonts that most fonts are copyrighted. First locate the license of a font before hand and verify they can be freely transferred to another machine. |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Adds the embedded font

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | byte[] | Font data  byte[]  |
| embedFontRule | int | Embedded font rule [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Keep in mind when adding any fonts that most fonts are copyrighted. First locate the license of a font before hand and verify they can be freely transferred to another machine. |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

Replace font in presentation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Source font |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Destination font |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```
Replace font in presentation using information provided in [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Font substitution info |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Replace font in presentation using information provided in collection of [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Font substitution info collection |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Retrieves the byte array representing the font data for a specified font style and font data.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Récupérer toutes les polices utilisées dans la présentation
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Obtenir le tableau d'octets représentant le style régulier de la première police de la présentation
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | The font data object containing the information about the font [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | The style of the font for which the data is to be retrieved [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Returns:**
byte[] - A byte array containing the font data for the specified font style. If the font data or style is not found, returns null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)


Détermine le niveau d'incorporation d'une police à partir du tableau d'octets fourni et du nom de la police.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Retrieve all fonts used in the presentation
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Get the byte array representing the regular style of the first font in the presentation
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Determine the embedding level of the font
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontBytes | byte[] | Le tableau d'octets contenant les données de la police. |
| fontName | java.lang.String | Le nom de la police. |

**Renvoie :**
int - Le niveau d'incorporation de la police spécifiée.