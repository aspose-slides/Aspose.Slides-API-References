---
title: FontsManager
second_title: Référence de l'API Aspose.Slides pour Java
description: Gère les polices dans la présentation.
type: docs
url: /fr/com.aspose.slides/fontsmanager/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.IFontsManager](../../com.aspose.slides/ifontsmanager)
```
public class FontsManager implements IFontsManager
```

Gère les polices dans la présentation.

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Charger la présentation
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Charger la police source à remplacer
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
>      // Enregistrer la présentation
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Méthodes

| Méthode | Description |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Substitutions de polices à utiliser lors du rendu. |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Substitutions de polices à utiliser lors du rendu. |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Représente la collection d'un utilisateur de règles FontFallBack pour la gestion de collections de polices afin d'assurer des substitutions appropriées par la fonctionnalité de secours Lecture/écriture [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Représente la collection d'un utilisateur de règles FontFallBack pour la gestion de collections de polices afin d'assurer des substitutions appropriées par la fonctionnalité de secours Lecture/écriture [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [getFonts()](#getFonts--) | Renvoie les polices utilisées dans la présentation |
| [getSubstitutions()](#getSubstitutions--) | Obtient les informations sur les polices qui seront remplacées lors du rendu de la présentation. |
| [getSubstitutions(int[] slides)](#getSubstitutions-int---) | Obtient les informations sur les polices qui seront remplacées pendant le rendu des diapositives spécifiées. |
| [getEmbeddedFonts()](#getEmbeddedFonts--) | Renvoie les polices incorporées dans la présentation |
| [removeEmbeddedFont(IFontData fontData)](#removeEmbeddedFont-com.aspose.slides.IFontData-) | Supprime la police incorporée |
| [addEmbeddedFont(IFontData fontData, int embedFontRule)](#addEmbeddedFont-com.aspose.slides.IFontData-int-) | Ajoute la police incorporée |
| [addEmbeddedFont(byte[] fontData, int embedFontRule)](#addEmbeddedFont-byte---int-) | Ajoute la police incorporée |
| [replaceFont(IFontData sourceFont, IFontData destFont)](#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Remplace la police dans la présentation |
| [replaceFont(IFontSubstRule substRule)](#replaceFont-com.aspose.slides.IFontSubstRule-) | Remplace la police dans la présentation en utilisant les informations fournies dans [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [replaceFont(IFontSubstRuleCollection substRules)](#replaceFont-com.aspose.slides.IFontSubstRuleCollection-) | Remplace la police dans la présentation en utilisant les informations fournies dans la collection de [FontSubstRule](../../com.aspose.slides/fontsubstrule) |
| [getFontBytes(IFontData fontData, int fontStyle)](#getFontBytes-com.aspose.slides.IFontData-int-) | Récupère le tableau d'octets représentant les données de police pour un style de police et des données de police spécifiés. |
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Détermine le niveau d'incorporation d'une police à partir du tableau d'octets fourni et du nom de la police. |

### getFontSubstRuleList() {#getFontSubstRuleList--}
```
public final IFontSubstRuleCollection getFontSubstRuleList()
```

Substitutions de polices à utiliser lors du rendu. Lecture/écriture [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Renvoie :**  
[IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)

### setFontSubstRuleList(IFontSubstRuleCollection value) {#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void setFontSubstRuleList(IFontSubstRuleCollection value)
```

Substitutions de polices à utiliser lors du rendu. Lecture/écriture [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) |  |

### getFontFallBackRulesCollection() {#getFontFallBackRulesCollection--}
```
public final IFontFallBackRulesCollection getFontFallBackRulesCollection()
```

Représente la collection d'un utilisateur de règles FontFallBack pour la gestion de collections de polices afin d'assurer des substitutions appropriées par la fonctionnalité de secours Lecture/écriture [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

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


**Renvoie :**  
[IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)

### setFontFallBackRulesCollection(IFontFallBackRulesCollection value) {#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-}
```
public final void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Représente la collection d'un utilisateur de règles FontFallBack pour la gestion de collections de polices afin d'assurer des substitutions appropriées par la fonctionnalité de secours Lecture/écriture [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection) |  |

### getFonts() {#getFonts--}
```
public final IFontData[] getFonts()
```

Renvoie les polices utilisées dans la présentation

**Renvoie :**  
com.aspose.slides.IFontData[] - Un tableau de polices

### getSubstitutions() {#getSubstitutions--}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
```

Obtient les informations sur les polices qui seront remplacées lors du rendu de la présentation.

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


**Renvoie :**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Collection de toutes les substitutions de polices [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public final System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Obtient les informations sur les polices qui seront remplacées pendant le rendu des diapositives spécifiées.

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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| slides | int[] | Un tableau d'index de diapositives pour lesquelles récupérer les informations de substitution de polices, en commençant à 1. |

**Renvoie :**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Une collection de toutes les substitutions de polices ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) pour les diapositives spécifiées.

### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public final IFontData[] getEmbeddedFonts()
```

Renvoie les polices incorporées dans la présentation

**Renvoie :**  
com.aspose.slides.IFontData[]

### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public final void removeEmbeddedFont(IFontData fontData)
```

Supprime la police incorporée

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |

### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public final void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Ajoute la police incorporée

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) |  |
| embedFontRule | int |  |

### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public final void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Ajoute la police incorporée

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontData | byte[] |  |
| embedFontRule | int |  |

### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public final void replaceFont(IFontData sourceFont, IFontData destFont)
```

Remplace la police dans la présentation

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Police source |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Police de destination |

### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public final void replaceFont(IFontSubstRule substRule)
```

Remplace la police dans la présentation en utilisant les informations fournies dans [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Info de substitution de police |

### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public final void replaceFont(IFontSubstRuleCollection substRules)
```

Remplace la police dans la présentation en utilisant les informations fournies dans la collection de [FontSubstRule](../../com.aspose.slides/fontsubstrule)

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Collection de règles de substitution de police |

### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public final byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Récupère le tableau d'octets représentant les données de police pour un style de police et des données de police spécifiés.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Récupérer toutes les polices utilisées dans la présentation
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Obtenir le tableau d'octets représentant le style normal de la première police dans la présentation
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | L'objet contenant les données de police avec les informations sur la police [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Le style de la police pour lequel les données sont à récupérer [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Renvoie :**  
byte[] - Un tableau d'octets contenant les données de police pour le style de police spécifié. Si les données de police ou le style ne sont pas trouvés, renvoie null.

### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public final int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Détermine le niveau d'incorporation d'une police à partir du tableau d'octets fourni et du nom de la police.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Récupérer toutes les polices utilisées dans la présentation
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Obtenir le tableau d'octets représentant le style normal de la première police dans la présentation
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyle.Regular);
>      // Déterminer le niveau d'incorporation de la police
>      int embeddingLevel = pres.getFontsManager().getFontEmbeddingLevel(bytes, fontDatas[0].getFontName());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontBytes | byte[] | Le tableau d'octets contenant les données de police. |
| fontName | java.lang.String | Le nom de la police. |

**Renvoie :**  
int - Le niveau d'incorporation de la police spécifiée.