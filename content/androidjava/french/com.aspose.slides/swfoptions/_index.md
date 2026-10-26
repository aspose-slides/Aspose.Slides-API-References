---
title: SwfOptions
second_title: Référence API Java d'Aspose.Slides pour Android
description: Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format Swf.
type: docs
url: /fr/com.aspose.slides/swfoptions/
---
**Héritage:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Toutes les interfaces implémentées:**  
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)  
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format Swf.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // Instancie un objet Presentation qui représente un fichier de présentation
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // Enregistrement de la présentation et des pages de notes
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | Default constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifies whether the generated document should include hidden slides or not. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifies whether the generated document should include hidden slides or not. |
| [getCompressed()](#getCompressed--) | Specifies whether the generated SWF document should be compressed or not. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Specifies whether the generated SWF document should be compressed or not. |
| [getViewerIncluded()](#getViewerIncluded--) | Specifies whether the generated SWF document should include the integrated document viewer or not. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Specifies whether the generated SWF document should include the integrated document viewer or not. |
| [getShowPageBorder()](#getShowPageBorder--) | Specifies whether border around pages should be shown. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Specifies whether border around pages should be shown. |
| [getShowFullScreen()](#getShowFullScreen--) | Show/hide fullscreen button. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Show/hide fullscreen button. |
| [getShowPageStepper()](#getShowPageStepper--) | Show/hide page stepper. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Show/hide page stepper. |
| [getShowSearch()](#getShowSearch--) | Show/hide search section. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Show/hide search section. |
| [getShowTopPane()](#getShowTopPane--) | Show/hide whole top pane. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Show/hide whole top pane. |
| [getShowBottomPane()](#getShowBottomPane--) | Show/hide bottom pane. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Show/hide bottom pane. |
| [getShowLeftPane()](#getShowLeftPane--) | Show/hide left pane. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Show/hide left pane. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Start with opened left pane. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Start with opened left pane. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Enable/disable context menu. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Enable/disable context menu. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Image that will be displayed as logo in the top right corner of the viewer. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Image that will be displayed as logo in the top right corner of the viewer. |
| [getLogoLink()](#getLogoLink--) | Gets or sets the full hyperlink address for a logo. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Gets or sets the full hyperlink address for a logo. |
| [getJpegQuality()](#getJpegQuality--) | Specifies the quality of JPEG images. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Specifies the quality of JPEG images. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```

Default constructor.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Specifies whether the generated document should include hidden slides or not. Default is false.

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Specifies whether the generated document should include hidden slides or not. Default is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```

Spécifie si le document SWF généré doit être compressé ou non. La valeur par défaut est true.

**Retourne :**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```

Specifies whether the generated SWF document should be compressed or not. Default is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```

Specifies whether the generated SWF document should include the integrated document viewer or not. Default is true.

**Returns:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```

Spécifie si le document SWF généré doit inclure le visualiseur de document intégré ou non. La valeur par défaut est true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```

Specifies whether border around pages should be shown. Default is true.

**Returns:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```

Specifies whether border around pages should be shown. Default is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```

Afficher/masquer le bouton plein écran. Peut être remplacé dans les flashvars. La valeur par défaut est true.

**Retourne :**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```

Show/hide fullscreen button. Can be overridden in flashvars. Default is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```

Afficher/masquer le sélecteur de page. Peut être remplacé dans les flashvars. La valeur par défaut est true.

**Retourne :**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```

Afficher/masquer le sélecteur de page. Peut être remplacé dans les flashvars. La valeur par défaut est true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```

Show/hide search section. Can be overridden in flashvars. Default is true.

**Returns:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```

Afficher/masquer la section de recherche. Peut être remplacé dans les flashvars. La valeur par défaut est true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```

Show/hide whole top pane. Can be overridden in flashvars. Default is true.

**Returns:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```

Afficher/masquer tout le panneau supérieur. Peut être remplacé dans les flashvars. La valeur par défaut est true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```

Show/hide bottom pane. Can be overridden in flashvars. Default is true.

**Returns:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```

Show/hide bottom pane. Can be overridden in flashvars. Default is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```

Afficher/masquer le volet gauche. Peut être remplacé dans les flashvars. La valeur par défaut est true.

**Retourne :**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```

Afficher/masquer le volet gauche. Peut être remplacé dans les flashvars. La valeur par défaut est true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```

Démarre avec le volet gauche ouvert. Peut être remplacé dans les flashvars. La valeur par défaut est false.

**Retour :**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```

Démarre avec le volet gauche ouvert. Peut être remplacé dans les flashvars. La valeur par défaut est false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```

Activer/désactiver le menu contextuel. La valeur par défaut est true.

**Retourne :**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```

Enable/disable context menu. Default is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```

Image qui sera affichée comme logo dans le coin supérieur droit du visualiseur. L'image doit être au format PNG de 32x64 pixels, sinon le logo peut s'afficher de manière incorrecte.

**Returns:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```

Image qui sera affichée comme logo dans le coin supérieur droit du visualiseur. L'image doit être au format PNG de 32x64 pixels, sinon le logo peut s'afficher de manière incorrecte.

**Retourne :**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final String getLogoLink()
```

Obtient ou définit l'adresse hypertexte complète d'un logo. N'a d'effet que si un (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) est spécifié.

**Retourne :**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```

Obtient ou définit l'adresse hypertexte complète d'un logo. N'a d'effet que si un (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) est spécifié.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Spécifie la qualité des images JPEG. La valeur par défaut est 95.

**Retourne :**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Spécifie la qualité des images JPEG. La valeur par défaut est 95.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```
Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Cette propriété ne prend pas en charge l'affectation d'objets du type [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Exemple :
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourne :**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)


Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Cette propriété ne prend pas en charge l'affectation d'objets du type [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions).

--------------------

> ```
> Exemple :
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |