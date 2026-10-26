---
title: ILoadOptions
second_title: Aspose.Slides pour Android via la référence API Java
description: Permet de spécifier des options supplémentaires, telles que le format ou la police par défaut, lors du chargement d’une présentation.
type: docs
url: /fr/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Permet de spécifier des options supplémentaires (telles que le format ou la police par défaut) lors du chargement d’une présentation.
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
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Cette propriété a un sens si le fichier de présentation est protégé par mot de passe. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Cette propriété a un sens si le fichier de présentation est protégé par mot de passe. |
| [getWarningCallback()](#getWarningCallback--) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être abandonné. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être abandonné. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Représente les options pouvant être utilisées pour gérer le comportement de traitement des Binary Large Objects (BLOBs), comme l’utilisation de fichiers temporaires ou le nombre maximal d’octets BLOB en mémoire. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Représente les options pouvant être utilisées pour gérer le comportement de traitement des Binary Large Objects (BLOBs), comme l’utilisation de fichiers temporaires ou le nombre maximal d’octets BLOB en mémoire. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Spécifie les sources des polices externes à utiliser pour la présentation. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Spécifie les sources des polices externes à utiliser pour la présentation. |
| [getInterruptionToken()](#getInterruptionToken--) | Le jeton à surveiller pour les demandes d’interruption. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Le jeton à surveiller pour les demandes d’interruption. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Renvoie ou définit l’interface de rappel qui gère le chargement des ressources externes. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Renvoie ou définit l’interface de rappel qui gère le chargement des ressources externes. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Représente les options pouvant être utilisées pour spécifier un comportement supplémentaire des feuilles de calcul. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Représente les options pouvant être utilisées pour spécifier un comportement supplémentaire des feuilles de calcul. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Renvoie ou définit la langue par défaut du texte de la présentation. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Renvoie ou définit la langue par défaut du texte de la présentation. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Détermine si Aspose.Slides supprimera tous les objets binaires incorporés lors du chargement de la présentation. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Détermine si Aspose.Slides supprimera tous les objets binaires incorporés lors du chargement de la présentation. |

### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Renvoie ou définit le format d’une présentation à charger. Lecture/écriture [LoadFormat](../../com.aspose.slides/loadformat).

**Renvoie :**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

Renvoie ou définit le format d’une présentation à charger. Lecture/écriture [LoadFormat](../../com.aspose.slides/loadformat).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Renvoie ou définit la police Regular utilisée si la police source n’est pas trouvée. Lecture/écriture String.

**Renvoie :**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Renvoie ou définit la police Regular utilisée si la police source n’est pas trouvée. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

Renvoie ou définit la police Symbol utilisée si la police source n’est pas trouvée. Lecture/écriture String.

**Renvoie :**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

Renvoie ou définit la police Symbol utilisée si la police source n’est pas trouvée. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

Renvoie ou définit la police Asian utilisée si la police source n’est pas trouvée. Lecture/écriture String.

**Renvoie :**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

Renvoie ou définit la police Asian utilisée si la police source n’est pas trouvée. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Obtient ou définit le mot de passe. Lecture/écriture String.

Valeur : le mot de passe.

**Renvoie :**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Obtient ou définit le mot de passe. Lecture/écriture String.

Valeur : le mot de passe.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

Cette propriété a un sens si le fichier de présentation est protégé par mot de passe. La valeur true signifie que seules les propriétés du document doivent être chargées depuis un fichier de présentation chiffré et que le mot de passe doit être ignoré. La valeur false signifie que la présentation complète chiffrée doit être chargée en utilisant le bon mot de passe. Si la présentation n’est pas chiffrée, la valeur de la propriété est toujours ignorée. Si les propriétés du document d’un fichier chiffré ne sont pas publiques et que la valeur de la propriété est true, les propriétés du document ne peuvent pas être chargées et une exception sera levée. Lecture/écriture boolean.

**Renvoie :**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

Cette propriété a un sens si le fichier de présentation est protégé par mot de passe. La valeur true signifie que seules les propriétés du document doivent être chargées depuis un fichier de présentation chiffré et que le mot de passe doit être ignoré. La valeur false signifie que la présentation complète chiffrée doit être chargée en utilisant le bon mot de passe. Si la présentation n’est pas chiffrée, la valeur de la propriété est toujours ignorée. Si les propriétés du document d’un fichier chiffré ne sont pas publiques et que la valeur de la propriété est true, les propriétés du document ne peuvent pas être chargées et une exception sera levée. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être abandonné. Lecture/écriture [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Renvoie :**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être abandonné. Lecture/écriture [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

Représente les options pouvant être utilisées pour gérer le comportement de traitement des Binary Large Objects (BLOBs), comme l’utilisation de fichiers temporaires ou le nombre maximal d’octets BLOB en mémoire. Ces options sont destinées à établir le meilleur rapport performance/consommation de mémoire pour un environnement ou des exigences particulières.

--------------------

Un Binary Large Object (BLOB) est une donnée binaire stockée comme une entité unique – par ex. un BLOB peut être un audio, une vidéo ou la présentation elle-même.

**Renvoie :**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

Représente les options pouvant être utilisées pour gérer le comportement de traitement des Binary Large Objects (BLOBs), comme l’utilisation de fichiers temporaires ou le nombre maximal d’octets BLOB en mémoire. Ces options sont destinées à établir le meilleur rapport performance/consommation de mémoire pour un environnement ou des exigences particulières.

--------------------

Un Binary Large Object (BLOB) est une donnée binaire stockée comme une entité unique – par ex. un BLOB peut être un audio, une vidéo ou la présentation elle-même.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

Spécifie les sources des polices externes à utiliser pour la présentation. Ces polices sont disponibles pendant toute la durée de vie de la présentation et ne sont pas partagées avec d’autres présentations.

**Renvoie :**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

Spécifie les sources des polices externes à utiliser pour la présentation. Ces polices sont disponibles pendant toute la durée de vie de la présentation et ne sont pas partagées avec d’autres présentations.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

Le jeton à surveiller pour les demandes d’interruption.

--------------------

Ce jeton gère la durée de vie de toute l’instance [IPresentation](../../com.aspose.slides/ipresentation). Toute opération de longue durée, comme le chargement ou l’enregistrement d’une présentation, sera interrompue en appelant la méthode [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) de [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Renvoie :**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

Le jeton à surveiller pour les demandes d’interruption.

--------------------

Ce jeton gère la durée de vie de toute l’instance [IPresentation](../../com.aspose.slides/ipresentation). Toute opération de longue durée, comme le chargement ou l’enregistrement d’une présentation, sera interrompue en appelant la méthode [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) de [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

Renvoie ou définit l’interface de rappel qui gère le chargement des ressources externes. Lecture/écriture [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Renvoie :**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Renvoie ou définit l’interface de rappel qui gère le chargement des ressources externes. Lecture/écriture [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

Représente les options pouvant être utilisées pour spécifier un comportement supplémentaire des feuilles de calcul.

**Renvoie :**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Représente les options pouvant être utilisées pour spécifier un comportement supplémentaire des feuilles de calcul.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

Renvoie ou définit la langue par défaut du texte de la présentation. Lecture/écriture String.

--------------------

> ```
> Example:
>   
>  // Utilisez les options de chargement pour définir la culture du texte par défaut
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
```
public abstract void setDefaultTextLanguage(String value)
```

Returns or sets the default language for presentation text. Read/write String.

--------------------

> ```
> Example:
>   
>  // Utilisez les options de chargement pour définir la culture du texte par défaut
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

Determines if Aspose.Slides will delete all embedded binary objects while presentation loading.

The types of the embedded binary objects:

 *  
 *  
 *  

Read/write  boolean .

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
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

Default is  **false** .

**Returns:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)

Détermine si Aspose.Slides supprimera tous les objets binaires incorporés lors du chargement de la présentation.

Les types des objets binaires incorporés :
 *  
 *  
 *  

Lecture/écriture boolean.

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
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

La valeur par défaut est **false**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |