---
title: LoadOptions
second_title: Aspose.Slides pour Android via la référence de l'API Java
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
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Renvoie ou définit la police Regular utilisée si la police source est introuvable. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Renvoie ou définit la police Regular utilisée si la police source est introuvable. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Renvoie ou définit la police Symbol utilisée si la police source est introuvable. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Renvoie ou définit la police Symbol utilisée si la police source est introuvable. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Renvoie ou définit la police Asian utilisée si la police source est introuvable. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Renvoie ou définit la police Asian utilisée si la police source est introuvable. |
| [getPassword()](#getPassword--) | Obtient ou définit le mot de passe. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Obtient ou définit le mot de passe. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Cette propriété a du sens si le fichier de présentation est protégé par un mot de passe. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Cette propriété a du sens si le fichier de présentation est protégé par un mot de passe. |
| [getWarningCallback()](#getWarningCallback--) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement continue ou est interrompu. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement continue ou est interrompu. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Représente les options pouvant être utilisées pour gérer le comportement de manipulation des objets binaires volumineux (BLOB), comme l’utilisation de fichiers temporaires ou le nombre maximal d’octets BLOB en mémoire. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Représente les options pouvant être utilisées pour gérer le comportement de manipulation des objets binaires volumineux (BLOB), comme l’utilisation de fichiers temporaires ou le nombre maximal d’octets BLOB en mémoire. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Spécifie les sources des polices externes à utiliser par la présentation. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Spécifie les sources des polices externes à utiliser par la présentation. |
| [getInterruptionToken()](#getInterruptionToken--) | Le jeton à surveiller pour les demandes d’interruption. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Le jeton à surveiller pour les demandes d’interruption. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Renvoie ou définit l’interface de rappel qui gère le chargement des ressources externes. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Renvoie ou définit l’interface de rappel qui gère le chargement des ressources externes. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Obtient les options pour les feuilles de calcul. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Obtient les options pour les feuilles de calcul. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Renvoie ou définit la langue par défaut du texte de la présentation. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Renvoie ou définit la langue par défaut du texte de la présentation. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Détermine si Aspose.Slides supprimera tous les objets binaires intégrés lors du chargement de la présentation. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Détermine si Aspose.Slides supprimera tous les objets binaires intégrés lors du chargement de la présentation. |
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

Renvoie ou définit le format d’une présentation à charger. Lecture/Écriture [LoadFormat](../../com.aspose.slides/loadformat).

**Renvoie :**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

Renvoie ou définit le format d’une présentation à charger. Lecture/Écriture [LoadFormat](../../com.aspose.slides/loadformat).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Renvoie ou définit la police Regular utilisée si la police source est introuvable. Lecture/Écriture String.

--------------------

> ```markdown
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Utilisez les options de chargement pour définir les polices regular et asian par défaut
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Charger la présentation
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Générer la miniature de la diapositive
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // Générer le PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Générer le XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```


Returns or sets Regular font used in case source font is not found. Read/write String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Utilisez les options de chargement pour définir les polices regular et asian par défaut
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Charger la présentation
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Générer la miniature de la diapositive
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // Générer le PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Générer le XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```


Returns or sets Symbol font used in case source font is not found. Read/write String.

**Returns:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Returns or sets Symbol font used in case source font is not found. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Returns or sets Asian font used in case source font is not found. Read/write String.

**Returns:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Returns or sets Asian font used in case source font is not found. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Gets or sets the password. Read/write String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // travailler avec la présentation déchiffrée
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Value: The password.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Gets or sets the password. Read/write String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // travailler avec la présentation déchiffrée
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

Value: The password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

This property makes sense, if presentation file is password protected. Value of true means that only document properties must be loaded from an encrypted presentation file and password must be ignored. Value of false means that entire encrypted presentation must be loaded with use of right password. If presentation isn’t encrypted then property value is always ignored. If document properties of an encrypted file aren’t public and property value is true then document properties cannot be loaded and exception will be thrown. Read/write boolean.

**Returns:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

This property makes sense, if presentation file is password protected. Value of true means that only document properties must be loaded from an encrypted presentation file and password must be ignored. Value of false means that entire encrypted presentation must be loaded with use of right password. If presentation isn’t encrypted then property value is always ignored. If document properties of an encrypted file aren’t public and property value is true then document properties cannot be loaded and exception will be thrown. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Returns:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Returns or sets an object which receives warnings and decides whether loading process will continue or will be aborted. Read/write [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Represents the options which can be used to manage Binary Large Objects (BLOBs) handling behavior, such as using of temporary files or max BLOBs bytes in memory. These options intended to set up the best performance/memory consumption ratio for a perticular environment or requirements.

--------------------

A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an audio, video or presentation itself.

**Returns:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Represents the options which can be used to manage Binary Large Objects (BLOBs) handling behavior, such as using of temporary files or max BLOBs bytes in memory. These options intended to set up the best performance/memory consumption ratio for a perticular environment or requirements.

--------------------

A Binary Large Object (BLOB) is a binary data stored as a single entity - i.e. BLOB can be an audio, video or presentation itself.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```
Specifies sources for external fonts to be used by the presentation. These fonts are available to the presentation throughout its lifetime and are not shared with other presentations

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // travailler avec la présentation
>  // CustomFont1, CustomFont2 ainsi que les polices des dossiers assets\fonts & global\fonts et leurs sous-dossiers sont disponibles pour la présentation
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  ```

**Returns:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```
Specifies sources for external fonts to be used by the presentation. These fonts are available to the presentation throughout its lifetime and are not shared with other presentations

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // travailler avec la présentation
>  // CustomFont1, CustomFont2 ainsi que les polices des dossiers assets\fonts & global\fonts et leurs sous-dossiers sont disponibles pour la présentation
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```
Le jeton à surveiller pour les demandes d’interruption.

--------------------

Ce jeton gère la durée de vie entière de l’instance [IPresentation](../../com.aspose.slides/ipresentation). Toute opération de longue durée, comme le chargement ou l’enregistrement d’une présentation, sera interrompue en appelant la méthode [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) de [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Returns:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```
The token to monitor for interruption requests.

--------------------

This token manages the whole [IPresentation](../../com.aspose.slides/ipresentation) instance lifetime. Any long-running operation, such as loading or saving of presentation, will be interrupted via calling of the [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) method of the [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```
Returns or sets callback interface which manages external resources loading. Read/write [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Returns:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Returns or sets callback interface which manages external resources loading. Read/write [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

Gets options for spreadsheets. For example, these options affect calculating formulas for charts.

**Returns:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Gets options for spreadsheets. For example, these options affect calculating formulas for charts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```
Returns or sets the default language for presentation text. Read/write String.

--------------------

> ```
> Example:
>   
>   // Utilisez les options de chargement pour définir la culture de texte par défaut
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setDefaultTextLanguage("en-US");
>   Presentation pres = new Presentation(loadOptions);
>   try {
>       // Ajouter une nouvelle forme de rectangle avec du texte
>       IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>       shp.getTextFrame().setText("New Text");
>       // Vérifier la langue de la première portion
>       System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Returns:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```
Returns or sets the default language for presentation text. Read/write String.

--------------------

> ```
> Example:
>   
> // Utilisez les options de chargement pour définir la culture de texte par défaut
> LoadOptions loadOptions = new LoadOptions();
> loadOptions.setDefaultTextLanguage("en-US");
> Presentation pres = new Presentation(loadOptions);
> try {
>     // Ajouter une nouvelle forme de rectangle avec du texte
>     IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>     shp.getTextFrame().setText("New Text");
>     // Vérifier la langue de la première portion
>     System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
> } finally {
>     if (pres != null) pres.dispose();
> }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public final boolean getDeleteEmbeddedBinaryObjects()
```

Determines if Aspose.Slides will delete all embedded binary objects while presentation loading.

The types of the embedded binary objects:

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
public final void setDeleteEmbeddedBinaryObjects(boolean value)


Détermine si Aspose.Slides supprimera tous les objets binaires intégrés lors du chargement de la présentation.

Les types des objets binaires intégrés :

Lecture/Écriture boolean.

--------------------

> ```
> L'exemple suivant montre comment charger la présentation sans aucun objet binaire intégré.
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