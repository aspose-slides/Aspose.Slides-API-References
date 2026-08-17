---
title: LoadOptions
second_title: Aspose.Slides pour Java Référence API
description: Permet de spécifier des options supplémentaires telles que le format ou la police par défaut lors du chargement d'une présentation.
type: docs
url: /fr/com.aspose.slides/loadoptions/
---
**Héritage :**  
java.lang.Object

**Toutes les interfaces implémentées :**  
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)  
```
public class LoadOptions implements ILoadOptions
```

Permet de spécifier des options supplémentaires (telles que le format ou la police par défaut) lors du chargement d’une présentation.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Crée de nouvelles options de chargement par défaut. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Crée de nouvelles options de chargement. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Renvoie ou définit le format d’une présentation à charger. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Renvoie ou définit le format d’une présentation à charger. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Renvoie ou définit la police Regular utilisée si la police source n’est pas trouvée. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Renvoie ou définit la police Regular utilisée si la police source n’est pas trouvée. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Renvoie ou définit la police Symbol utilisée si la police source n’est pas trouvée. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Renvoie ou définit la police Symbol utilisée si la police source n’est pas trouvée. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Renvoie ou définit la police Asian utilisée si la police source n’est pas trouvée. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Renvoie ou définit la police Asian utilisée si la police source n’est pas trouvée. |
| [getPassword()](#getPassword--) | Obtient ou définit le mot de passe. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Obtient ou définit le mot de passe. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Cette propriété a du sens si le fichier de présentation est protégé par un mot de passe. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Cette propriété a du sens si le fichier de présentation est protégé par un mot de passe. |
| [getWarningCallback()](#getWarningCallback--) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être abandonné. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être abandonné. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Représente les options pouvant être utilisées pour gérer le comportement de manipulation des objets binaires volumineux (BLOB), par exemple l’utilisation de fichiers temporaires ou le nombre maximal d’octets BLOB en mémoire. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Représente les options pouvant être utilisées pour gérer le comportement de manipulation des objets binaires volumineux (BLOB), par exemple l’utilisation de fichiers temporaires ou le nombre maximal d’octets BLOB en mémoire. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Spécifie les sources des polices externes à utiliser par la présentation. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Spécifie les sources des polices externes à utiliser par la présentation. |
| [getInterruptionToken()](#getInterruptionToken--) | Le jeton pour surveiller les demandes d’interruption. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Le jeton pour surveiller les demandes d’interruption. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Renvoie ou définit l’interface de rappel qui gère le chargement des ressources externes. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Renvoie ou définit l’interface de rappel qui gère le chargement des ressources externes. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Obtient les options pour les feuilles de calcul. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Obtient les options pour les feuilles de calcul. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Renvoie ou définit la langue par défaut du texte de la présentation. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Renvoie ou définit la langue par défaut du texte de la présentation. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Détermine si Aspose.Slides supprimera tous les objets binaires incorporés lors du chargement de la présentation. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Détermine si Aspose.Slides supprimera tous les objets binaires incorporés lors du chargement de la présentation. |

### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

Crée de nouvelles options de chargement par défaut.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

Crée de nouvelles options de chargement.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| loadFormat | int | Format d’une présentation à charger. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Renvoie ou définit le format d’une présentation à charger. Lecture/écriture [LoadFormat](../../com.aspose.slides/loadformat).

**Renvoie :**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

Renvoie ou définit le format d’une présentation à charger. Lecture/écriture [LoadFormat](../../com.aspose.slides/loadformat).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Renvoie ou définit la police Regular utilisée si la police source n’est pas trouvée. Lecture/écriture String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Utilisez les options de chargement pour définir les polices régulières et asiatiques par défaut
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Charger la présentation
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Générer la miniature de la diapositive
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // Générer le PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Générer le XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Renvoie ou définit la police Regular utilisée si la police source n’est pas trouvée. Lecture/écriture String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Utilisez les options de chargement pour définir les polices régulières et asiatiques par défaut
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Charger la présentation
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Générer la vignette de la diapositive
>      BufferedImage slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      ImageIO.write(slideImage, "PNG", new File("output_out.png"));
>      // Générer le PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Générer le XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

Renvoie ou définit la police Symbol utilisée si la police source n’est pas trouvée. Lecture/écriture String.

**Renvoie :**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Renvoie ou définit la police Symbol utilisée si la police source n’est pas trouvée. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Renvoie ou définit la police Asian utilisée si la police source n’est pas trouvée. Lecture/écriture String.

**Renvoie :**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Renvoie ou définit la police Asian utilisée si la police source n’est pas trouvée. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Obtient ou définit le mot de passe. Lecture/écriture String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // travaillez avec la présentation décryptée
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Valeur : le mot de passe.

**Renvoie :**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Obtient ou définit le mot de passe. Lecture/écriture String.

--------------------

> ```
> Le code d'exemple suivant montre comment ouvrir une présentation PowerPoint protégée par mot de passe.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // travaillez avec la présentation décryptée
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Valeur : le mot de passe.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

Cette propriété a du sens si le fichier de présentation est protégé par un mot de passe. Une valeur true signifie que seules les propriétés du document doivent être chargées à partir d’un fichier de présentation chiffré et que le mot de passe doit être ignoré. Une valeur false signifie que toute la présentation chiffrée doit être chargée en utilisant le bon mot de passe. Si la présentation n’est pas chiffrée, la valeur de la propriété est toujours ignorée. Si les propriétés du document d’un fichier chiffré ne sont pas publiques et que la valeur de la propriété est true, alors les propriétés du document ne peuvent pas être chargées et une exception sera levée. Lecture/écriture boolean.

**Renvoie :**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

Cette propriété a du sens si le fichier de présentation est protégé par un mot de passe. Une valeur true signifie que seules les propriétés du document doivent être chargées à partir d’un fichier de présentation chiffré et que le mot de passe doit être ignoré. Une valeur false signifie que toute la présentation chiffrée doit être chargée en utilisant le bon mot de passe. Si la présentation n’est pas chiffrée, la valeur de la propriété est toujours ignorée. Si les propriétés du document d’un fichier chiffré ne sont pas publiques et que la valeur de la propriété est true, alors les propriétés du document ne peuvent pas être chargées et une exception sera levée. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être abandonné. Lecture/écriture [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Renvoie :**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être abandonné. Lecture/écriture [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Représente les options pouvant être utilisées pour gérer le comportement de manipulation des objets binaires volumineux (BLOB), par exemple l’utilisation de fichiers temporaires ou le nombre maximal d’octets BLOB en mémoire. Ces options sont destinées à définir le meilleur rapport performance/consommation mémoire pour un environnement ou des exigences particulières.

--------------------

Un objet binaire volumineux (BLOB) est une donnée binaire stockée comme une entité unique – c’est-à-dire qu’un BLOB peut être un audio, une vidéo ou la présentation elle-même.

**Renvoie :**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Représente les options pouvant être utilisées pour gérer le comportement de manipulation des objets binaires volumineux (BLOB), par exemple l’utilisation de fichiers temporaires ou le nombre maximal d’octets BLOB en mémoire. Ces options sont destinées à définir le meilleur rapport performance/consommation mémoire pour un environnement ou des exigences particulières.

--------------------

Un objet binaire volumineux (BLOB) est une donnée binaire stockée comme une entité unique – c’est-à-dire qu’un BLOB peut être un audio, une vidéo ou la présentation elle-même.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

Spécifie les sources des polices externes à utiliser par la présentation. Ces polices sont disponibles pour la présentation pendant toute sa durée de vie et ne sont pas partagées avec d’autres présentations.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //work with the presentation
>  //CustomFont1, CustomFont2 as well as fonts from assets\fonts & global\fonts folders and their subfolders are available to the presentation
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Renvoie :**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

Spécifie les sources des polices externes à utiliser par la présentation. Ces polices sont disponibles pour la présentation pendant toute sa durée de vie et ne sont pas partagées avec d’autres présentations.

--------------------

> ```
> L'exemple suivant montre comment spécifier des polices personnalisées utilisées avec PowerPoint Presentation.
>  
>  byte[] memoryFont1 = Files.readAllBytes(Paths.get("customfonts\\CustomFont1.ttf"));
>  byte[] memoryFont2 = Files.readAllBytes(Paths.get("customfonts\\CustomFont2.ttf"));
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //travaillez avec la présentation
>  //CustomFont1, CustomFont2 ainsi que les polices provenant des dossiers assets\fonts & global\fonts et leurs sous-dossiers sont disponibles pour la présentation
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

Le jeton pour surveiller les demandes d’interruption.

--------------------

Ce jeton gère la durée de vie entière de l’instance [IPresentation](../../com.aspose.slides/ipresentation). Toute opération longue, comme le chargement ou l’enregistrement d’une présentation, sera interrompue en appelant la méthode [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) de [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Renvoie :**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

Le jeton pour surveiller les demandes d’interruption.

--------------------

Ce jeton gère la durée de vie entière de l’instance [IPresentation](../../com.aspose.slides/ipresentation). Toute opération longue, comme le chargement ou l’enregistrement d’une présentation, sera interrompue en appelant la méthode [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) de [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

Renvoie ou définit l’interface de rappel qui gère le chargement des ressources externes. Lecture/écriture [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Renvoie :**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Renvoie ou définit l’interface de rappel qui gère le chargement des ressources externes. Lecture/écriture [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

Obtient les options pour les feuilles de calcul. Par exemple, ces options affectent le calcul des formules pour les graphiques.

**Renvoie :**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Obtient les options pour les feuilles de calcul. Par exemple, ces options affectent le calcul des formules pour les graphiques.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

Renvoie ou définit la langue par défaut du texte de la présentation. Lecture/écriture String.

--------------------

> ```
> Example:
>   
>  // Utilisez les options de chargement pour définir la culture texte par défaut
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Ajoutez une nouvelle forme rectangle avec du texte
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Vérifiez la langue de la première portion
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

Renvoie ou définit la langue par défaut du texte de la présentation. Lecture/écriture String.

--------------------

> ```
> Exemple:
>   
>  // Utilisez les options de chargement pour définir la culture texte par défaut
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Ajoutez une nouvelle forme rectangle avec du texte
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Vérifiez la langue de la première portion
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```

Détermine si Aspose.Slides supprimera tous les objets binaires incorporés lors du chargement de la présentation.

Les types des objets binaires incorporés :

Lecture/écriture booléen.

--------------------

> ```
> L'exemple suivant montre comment charger la présentation sans aucun objet binaire incorporé.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Par défaut, **false**.

**Renvoie :**
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

Détermine si Aspose.Slides supprimera tous les objets binaires incorporés lors du chargement de la présentation.

Les types des objets binaires incorporés :

Lecture/écriture booléen.

--------------------

> ```
> L'exemple suivant montre comment charger la présentation sans aucun objet binaire incorporé.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Par défaut, **false**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |