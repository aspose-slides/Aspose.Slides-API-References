---
title: SwfOptions
second_title: Référence de l'API Aspose.Slides pour Java
description: Fournit des options qui contrôlent la façon dont une présentation est enregistrée au format Swf.
type: docs
url: /fr/com.aspose.slides/swfoptions/
---
**Héritage :**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Toutes les interfaces implémentées :**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Fournit des options qui contrôlent la manière dont une présentation est enregistrée au format Swf.

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
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | Constructeur par défaut. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Spécifie si le document généré doit inclure les diapositives masquées ou non. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Spécifie si le document généré doit inclure les diapositives masquées ou non. |
| [getCompressed()](#getCompressed--) | Spécifie si le document SWF généré doit être compressé ou non. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Spécifie si le document SWF généré doit être compressé ou non. |
| [getViewerIncluded()](#getViewerIncluded--) | Spécifie si le document SWF généré doit inclure le visualiseur de document intégré ou non. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Spécifie si le document SWF généré doit inclure le visualiseur de document intégré ou non. |
| [getShowPageBorder()](#getShowPageBorder--) | Spécifie si la bordure autour des pages doit être affichée. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Spécifie si la bordure autour des pages doit être affichée. |
| [getShowFullScreen()](#getShowFullScreen--) | Afficher/masquer le bouton plein écran. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Afficher/masquer le bouton plein écran. |
| [getShowPageStepper()](#getShowPageStepper--) | Afficher/masquer le sélecteur de page. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Afficher/masquer le sélecteur de page. |
| [getShowSearch()](#getShowSearch--) | Afficher/masquer la section de recherche. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Afficher/masquer la section de recherche. |
| [getShowTopPane()](#getShowTopPane--) | Afficher/masquer le panneau supérieur complet. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Afficher/masquer le panneau supérieur complet. |
| [getShowBottomPane()](#getShowBottomPane--) | Afficher/masquer le panneau inférieur. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Afficher/masquer le panneau inférieur. |
| [getShowLeftPane()](#getShowLeftPane--) | Afficher/masquer le panneau gauche. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Afficher/masquer le panneau gauche. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Démarrer avec le panneau gauche ouvert. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Démarrer avec le panneau gauche ouvert. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Activer/désactiver le menu contextuel. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Activer/désactiver le menu contextuel. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Image qui sera affichée comme logo dans le coin supérieur droit du visualiseur. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Image qui sera affichée comme logo dans le coin supérieur droit du visualiseur. |
| [getLogoLink()](#getLogoLink--) | Obtient ou définit l'adresse hypertexte complète d'un logo. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Obtient ou définit l'adresse hypertexte complète d'un logo. |
| [getJpegQuality()](#getJpegQuality--) | Spécifie la qualité des images JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Spécifie la qualité des images JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```

Constructeur par défaut.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est false.

**Renvoie :**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Spécifie si le document généré doit inclure les diapositives masquées ou non. La valeur par défaut est false.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```

Spécifie si le document SWF généré doit être compressé ou non. La valeur par défaut est true.

**Renvoie :**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```

Spécifie si le document SWF généré doit être compressé ou non. La valeur par défaut est true.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```

Spécifie si le document SWF généré doit inclure le visualiseur de document intégré ou non. La valeur par défaut est true.

**Renvoie :**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```

Spécifie si le document SWF généré doit inclure le visualiseur de document intégré ou non. La valeur par défaut est true.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```

Spécifie si la bordure autour des pages doit être affichée. La valeur par défaut est true.

**Renvoie :**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```

Spécifie si la bordure autour des pages doit être affichée. La valeur par défaut est true.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```

Afficher/masquer le bouton plein écran. Peut être remplacé dans les flashvars. La valeur par défaut est true.

**Renvoie :**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```

Afficher/masquer le bouton plein écran. Peut être remplacé dans les flashvars. La valeur par défaut est true.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```

Afficher/masquer le sélecteur de page. Peut être remplacé dans les flashvars. La valeur par défaut est true.

**Renvoie :**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```

Afficher/masquer le sélecteur de page. Peut être remplacé dans les flashvars. La valeur par défaut est true.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```

Afficher/masquer la section de recherche. Peut être remplacé dans les flashvars. La valeur par défaut est true.

**Renvoie :**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```

Afficher/masquer la section de recherche. Peut être remplacé dans les flashvars. La valeur par défaut est true.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```

Afficher/masquer le panneau supérieur complet. Peut être remplacé dans les flashvars. La valeur par défaut est true.

**Renvoie :**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```

Afficher/masquer le panneau supérieur complet. Peut être remplacé dans les flashvars. La valeur par défaut est true.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```

Afficher/masquer le panneau inférieur. Peut être remplacé dans les flashvars. La valeur par défaut est true.

**Renvoie :**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```

Afficher/masquer le panneau inférieur. Peut être remplacé dans les flashvars. La valeur par défaut est true.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```

Afficher/masquer le panneau gauche. Peut être remplacé dans les flashvars. La valeur par défaut est true.

**Renvoie :**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```

Afficher/masquer le panneau gauche. Peut être remplacé dans les flashvars. La valeur par défaut est true.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```

Démarrer avec le panneau gauche ouvert. Peut être remplacé dans les flashvars. La valeur par défaut est false.

**Renvoie :**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```

Démarrer avec le panneau gauche ouvert. Peut être remplacé dans les flashvars. La valeur par défaut est false.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```

Activer/désactiver le menu contextuel. La valeur par défaut est true.

**Renvoie :**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```

Activer/désactiver le menu contextuel. La valeur par défaut est true.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```

Image qui sera affichée comme logo dans le coin supérieur droit du visualiseur. L'image doit être une image PNG de 32x64 pixels, sinon le logo peut s'afficher de manière incorrecte.

**Renvoie :**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```

Image qui sera affichée comme logo dans le coin supérieur droit du visualiseur. L'image doit être une image PNG de 32x64 pixels, sinon le logo peut s'afficher de manière incorrecte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```

Obtient ou définit l'adresse hypertexte complète d'un logo. A un effet seulement si un (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) est spécifié.

**Renvoie :**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```

Obtient ou définit l'adresse hypertexte complète d'un logo. A un effet seulement si un (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) est spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Spécifie la qualité des images JPEG. La valeur par défaut est 95.

**Renvoie :**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Spécifie la qualité des images JPEG. La valeur par défaut est 95.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Cette propriété ne prend pas en charge l'affectation d'objets du type [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Example:
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

**Renvoie :**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Obtient ou définit le mode dans lequel les diapositives sont placées sur la page lors de l'exportation d'une présentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Cette propriété ne prend pas en charge l'affectation d'objets du type [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions).

--------------------

> ```
> Example:
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