---
title: IFontsManager
second_title: Aspose.Slides for Java API Reference
description: Gère les polices dans l’ensemble de la présentation.
type: docs
url: /fr/com.aspose.slides/ifontsmanager/
---```
public interface IFontsManager
```

Gère les polices dans l’ensemble de la présentation.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getFontSubstRuleList()](#getFontSubstRuleList--) | Substitutions de police à utiliser lors du rendu Lecture/écriture [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [setFontSubstRuleList(IFontSubstRuleCollection value)](#setFontSubstRuleList-com.aspose.slides.IFontSubstRuleCollection-) | Substitutions de police à utiliser lors du rendu Lecture/écriture [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection). |
| [getFontFallBackRulesCollection()](#getFontFallBackRulesCollection--) | Représente la collection d'un utilisateur de règles FontFallBack pour gérer des collections de polices afin d'effectuer des substitutions appropriées grâce à la fonctionnalité de repli Lecture/écriture [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
| [setFontFallBackRulesCollection(IFontFallBackRulesCollection value)](#setFontFallBackRulesCollection-com.aspose.slides.IFontFallBackRulesCollection-) | Représente la collection d'un utilisateur de règles FontFallBack pour gérer des collections de polices afin d'effectuer des substitutions appropriées grâce à la fonctionnalité de repli Lecture/écriture [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection). |
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
| [getFontEmbeddingLevel(byte[] fontBytes, String fontName)](#getFontEmbeddingLevel-byte---java.lang.String-) | Détermine le niveau d'intégration d'une police à partir du tableau d'octets donné et du nom de la police. |
| [getPreferRegisteredFontsOverEmbedded()](#getPreferRegisteredFontsOverEmbedded--) | Spécifie si les polices enregistrées doivent être privilégiées par rapport aux polices incorporées portant le même nom et le même style. |
| [setPreferRegisteredFontsOverEmbedded(boolean value)](#setPreferRegisteredFontsOverEmbedded-boolean-) | Spécifie si les polices enregistrées doivent être privilégiées par rapport aux polices incorporées portant le même nom et le même style. |
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

Représente la collection d'un utilisateur de règles FontFallBack pour gérer des collections de polices afin d'effectuer des substitutions appropriées grâce à la fonctionnalité de repli Lecture/écriture [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Obtention d'une collection de règles vide ou préinitialisée depuis FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // Ajout de règles à la collection
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ou 
>      // Initialisation d'une nouvelle instance de collection de règles
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // Ajout de règles à la collection
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // Et remplacement de la collection existante par la nouvelle dans FontsManager 
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
public abstract void setFontFallBackRulesCollection(IFontFallBackRulesCollection value)
```

Représente la collection d'un utilisateur de règles FontFallBack pour gérer des collections de polices afin d'effectuer des substitutions appropriées grâce à la fonctionnalité de repli Lecture/écriture [IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      // Obtention d'une collection de règles vide ou préinitialisée depuis FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      // Ajout de règles à la collection
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // ou 
>      // Initialisation d'une nouvelle instance de collection de règles
>      IFontFallBackRulesCollection rulesList = new FontFallBackRulesCollection();
>      // Ajout de règles à la collection
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      // Et remplacement de la collection existante par la nouvelle dans FontsManager 
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
public abstract IFontData[] getFonts()
```

Renvoie les polices utilisées dans la présentation

**Renvoie :**
com.aspose.slides.IFontData[] - Un tableau de polices
### getSubstitutions() {#getSubstitutions--}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions()
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
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Collection de toutes les substitutions de police [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).
### getSubstitutions(int[] slides) {#getSubstitutions-int---}
```
public abstract System.Collections.Generic.IGenericEnumerable<FontSubstitutionInfo> getSubstitutions(int[] slides)
```

Obtient les informations sur les polices qui seront remplacées lors du rendu des diapositives spécifiées.

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
| slides | int[] | Un tableau d'index de diapositives pour lesquelles récupérer les informations de substitution de police, à partir de 1. |

**Renvoie :**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.FontSubstitutionInfo> - Une collection de toutes les substitutions de police ([FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo)) pour les diapositives spécifiées.
### getEmbeddedFonts() {#getEmbeddedFonts--}
```
public abstract IFontData[] getEmbeddedFonts()
```

Renvoie les polices incorporées dans la présentation

**Renvoie :**
com.aspose.slides.IFontData[] - Polices incorporées IFontData[]
### removeEmbeddedFont(IFontData fontData) {#removeEmbeddedFont-com.aspose.slides.IFontData-}
```
public abstract void removeEmbeddedFont(IFontData fontData)
```

Supprime la police incorporée

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Objet de données de police [IFontData](../../com.aspose.slides/ifontdata) |
### addEmbeddedFont(IFontData fontData, int embedFontRule) {#addEmbeddedFont-com.aspose.slides.IFontData-int-}
```
public abstract void addEmbeddedFont(IFontData fontData, int embedFontRule)
```

Ajoute la police incorporée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | Objet de données de police [IFontData](../../com.aspose.slides/ifontdata) |
| embedFontRule | int | Règle de police incorporée [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Gardez à l'esprit que la plupart des polices sont protégées par le droit d'auteur. Localisez d'abord la licence d'une police et vérifiez qu'elle peut être transférée librement vers une autre machine. |
### addEmbeddedFont(byte[] fontData, int embedFontRule) {#addEmbeddedFont-byte---int-}
```
public abstract void addEmbeddedFont(byte[] fontData, int embedFontRule)
```

Ajoute la police incorporée

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontData | byte[] | Données de police  byte[]  |
| embedFontRule | int | Règle de police incorporée [EmbedFontCharacters](../../com.aspose.slides/embedfontcharacters)

--------------------

Gardez à l'esprit que la plupart des polices sont protégées par le droit d'auteur. Localisez d'abord la licence d'une police et vérifiez qu'elle peut être transférée librement vers une autre machine. |
### replaceFont(IFontData sourceFont, IFontData destFont) {#replaceFont-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public abstract void replaceFont(IFontData sourceFont, IFontData destFont)
```

Remplace la police dans la présentation

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Police source |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Police de destination |
### replaceFont(IFontSubstRule substRule) {#replaceFont-com.aspose.slides.IFontSubstRule-}
```
public abstract void replaceFont(IFontSubstRule substRule)
```

Remplace la police dans la présentation en utilisant les informations fournies dans [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| substRule | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Informations de substitution de police |
### replaceFont(IFontSubstRuleCollection substRules) {#replaceFont-com.aspose.slides.IFontSubstRuleCollection-}
```
public abstract void replaceFont(IFontSubstRuleCollection substRules)
```

Remplace la police dans la présentation en utilisant les informations fournies dans la collection de [IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| substRules | [IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection) | Collection d'informations de substitution de police |
### getFontBytes(IFontData fontData, int fontStyle) {#getFontBytes-com.aspose.slides.IFontData-int-}
```
public abstract byte[] getFontBytes(IFontData fontData, int fontStyle)
```

Récupère le tableau d'octets représentant les données de police pour un style de police et des données de police spécifiés.

--------------------

> ```
> Presentation pres = new Presentation ("Presentation.pptx");
>  try {
>      // Récupérer toutes les polices utilisées dans la présentation
>      IFontData[] fonts = pres.getFontsManager().getFonts();
>      // Obtenir le tableau d'octets représentant le style régulier de la première police dans la présentation
>      byte[] fontBytes = pres.getFontsManager().getFontBytes(fonts[0], FontStyleType.Regular);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontData | [IFontData](../../com.aspose.slides/ifontdata) | L'objet de données de police contenant les informations sur la police [IFontData](../../com.aspose.slides/ifontdata). |
| fontStyle | int | Le style de la police dont les données doivent être récupérées [FontStyleType](../../com.aspose.slides/fontstyletype). |

**Renvoie :**
byte[] - Un tableau d'octets contenant les données de police pour le style de police spécifié. Si les données de police ou le style ne sont pas trouvés, renvoie null.
### getFontEmbeddingLevel(byte[] fontBytes, String fontName) {#getFontEmbeddingLevel-byte---java.lang.String-}
```
public abstract int getFontEmbeddingLevel(byte[] fontBytes, String fontName)
```

Détermine le niveau d'intégration d'une police à partir du tableau d'octets donné et du nom de la police.

--------------------

> ```
> Presentation pres = new Presentation(pptxFileName);
>  try {
>      // Récupérer toutes les polices utilisées dans la présentation
>      IFontData[] fontDatas = pres.getFontsManager().getFonts();
>      // Obtenir le tableau d'octets représentant le style régulier de la première police dans la présentation
>      byte[] bytes = pres.getFontsManager().getFontBytes(fontDatas[0], FontStyleType.Regular);
>      // Déterminer le niveau d'intégration de la police
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
int - Le niveau d'intégration de la police spécifiée.
### getPreferRegisteredFontsOverEmbedded() {#getPreferRegisteredFontsOverEmbedded--}
```
public abstract boolean getPreferRegisteredFontsOverEmbedded()
```

Spécifie si les polices enregistrées doivent être privilégiées par rapport aux polices incorporées portant le même nom et le même style. Lorsqu'activée, les polices incorporées correspondantes sont temporairement remplacées par les polices enregistrées correspondantes lors de l'exportation.

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

Par défaut, c'est **false** .

**Renvoie :**
boolean
### setPreferRegisteredFontsOverEmbedded(boolean value) {#setPreferRegisteredFontsOverEmbedded-boolean-}
```
public abstract void setPreferRegisteredFontsOverEmbedded(boolean value)
```

Spécifie si les polices enregistrées doivent être privilégiées par rapport aux polices incorporées portant le même nom et le même style. Lorsqu'activée, les polices incorporées correspondantes sont temporairement remplacées par les polices enregistrées correspondantes lors de l'exportation.

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

Par défaut, c'est **false** .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |