---
title: IPresentation
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Document de présentation
type: docs
url: /fr/com.aspose.slides/ipresentation/
---
**Toutes les interfaces implémentées :**  
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable  
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Document de présentation  
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Renvoie ou définit la date et l'heure qui remplaceront le contenu des champs datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Renvoie ou définit la date et l'heure qui remplaceront le contenu des champs datetime. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Renvoie le gestionnaire HeaderFooter de la présentation. |
| [getProtectionManager()](#getProtectionManager--) | Obtient le gestionnaire des autorisations de cette présentation. |
| [getSlides()](#getSlides--) | Renvoie une liste de toutes les diapositives définies dans la présentation. |
| [getSections()](#getSections--) | Renvoie une liste de toutes les sections de diapositives définies dans la présentation. |
| [getSlideSize()](#getSlideSize--) | Renvoie l'objet de taille de diapositive. |
| [getNotesSize()](#getNotesSize--) | Renvoie l'objet de taille des notes de diapositive. |
| [getLayoutSlides()](#getLayoutSlides--) | Renvoie une liste de toutes les diapositives de mise en page définies dans la présentation. |
| [getMasters()](#getMasters--) | Renvoie une liste de toutes les diapositives maîtres définies dans la présentation. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Renvoie le gestionnaire maître des notes. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Renvoie le gestionnaire maître des fascicules. |
| [getFontsManager()](#getFontsManager--) | Renvoie le gestionnaire de polices. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Renvoie le style de texte par défaut pour les formes. |
| [getCommentAuthors()](#getCommentAuthors--) | Renvoie la collection des auteurs de commentaires. |
| [getDocumentProperties()](#getDocumentProperties--) | Renvoie l'objet DocumentProperties qui contient les propriétés standard et personnalisées du document. |
| [getImages()](#getImages--) | Renvoie la collection de toutes les images de la présentation. |
| [getAudios()](#getAudios--) | Renvoie la collection de tous les fichiers audio intégrés dans la présentation. |
| [getVideos()](#getVideos--) | Renvoie la collection de tous les fichiers vidéo intégrés dans la présentation. |
| [getCustomData()](#getCustomData--) | Renvoie les données personnalisées de la présentation. |
| [getVbaProject()](#getVbaProject--) | Obtient le projet VBA avec les macros de la présentation. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Obtient le projet VBA avec les macros de la présentation. |
| [getSourceFormat()](#getSourceFormat--) | Renvoie des informations sur le format à partir duquel la présentation a été chargée. |
| [getMasterTheme()](#getMasterTheme--) | Renvoie le thème maître de la présentation. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fournit un accès facile à tous les hyperliens contenus dans toutes les diapositives de la présentation (pas dans les maîtres, mises en page, diapositives de notes). |
| [getViewProperties()](#getViewProperties--) | Obtient les propriétés de vue de la présentation. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Représente le numéro de la première diapositive dans la présentation. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Représente le numéro de la première diapositive dans la présentation. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Renvoie toutes les parties de données personnalisées de la présentation. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Renvoie la collection des signatures utilisées pour signer la présentation. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Renvoie la collection des libellés de sensibilité appliqués au document de présentation. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Enregistre toutes les diapositives d'une présentation dans un fichier au format spécifié. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Enregistre toutes les diapositives d'une présentation dans un fichier au format spécifié avec des options supplémentaires. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié avec des options supplémentaires. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Enregistre les diapositives spécifiées d'une présentation dans un fichier au format spécifié. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Enregistre les diapositives spécifiées d'une présentation dans un fichier au format spécifié. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Enregistre toutes les diapositives d'une présentation dans un ensemble de fichiers représentant le balisage XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Renvoie des objets image miniature pour toutes les diapositives d'une présentation. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Renvoie des objets IImage miniature pour les diapositives spécifiées d'une présentation. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Renvoie des objets image miniature pour toutes les diapositives d'une présentation avec mise à l'échelle personnalisée. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Renvoie des objets image miniature pour les diapositives spécifiées d'une présentation avec mise à l'échelle personnalisée. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Renvoie des objets image miniature pour toutes les diapositives d'une présentation avec une taille spécifiée. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Renvoie des objets image miniature pour les diapositives spécifiées d'une présentation avec une taille spécifiée. |
| [getSlideById(long id)](#getSlideById-long-) | Renvoie une diapositive, MasterSlide ou LayoutSlide par Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Fusionne les portions avec le même formatage dans tous les paragraphes de toutes les formes acceptables de toutes les diapositives. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Met en évidence toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Met en évidence toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Met en évidence toutes les correspondances de l'expression régulière avec la couleur spécifiée. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Remplace toutes les occurrences du texte spécifié par un autre texte spécifié. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Remplace toutes les correspondances de l'expression régulière par la chaîne spécifiée. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Renvoie ou définit la date et l'heure qui remplaceront le contenu des champs datetime. Heure de création de cet objet Presentation par défaut. **Lecture/écriture** java.util.Date.

**Retour :**  
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Renvoie ou définit la date et l'heure qui remplaceront le contenu des champs datetime. Heure de création de cet objet Presentation par défaut. **Lecture/écriture** java.util.Date.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Renvoie le gestionnaire HeaderFooter de la présentation. **Lecture seule** [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Retour :**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Obtient le gestionnaire des autorisations de cette présentation. **Lecture seule** [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Retour :**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Renvoie une liste de toutes les diapositives définies dans la présentation. **Lecture seule** [ISlideCollection](../../com.aspose.slides/islidecollection).

**Retour :**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Renvoie une liste de toutes les sections de diapositives définies dans la présentation. **Lecture seule** [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Retour :**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Renvoie l'objet de taille de diapositive. **Lecture seule** [ISlideSize](../../com.aspose.slides/islidesize).

**Retour :**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Renvoie l'objet de taille des notes de diapositive. **Lecture seule** [INotesSize](../../com.aspose.slides/inotessize).

**Retour :**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Renvoie une liste de toutes les diapositives de mise en page définies dans la présentation. **Lecture seule** [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Vous pouvez accéder à l'API alternative pour ajouter/insérer/supprimer/dupliquer des diapositives de mise en page en utilisant la propriété IMasterSlide.LayoutSlides.

**Retour :**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Renvoie une liste de toutes les diapositives maîtres définies dans la présentation. **Lecture seule** [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Retour :**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Renvoie le gestionnaire maître des notes. **Lecture seule** [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Retour :**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Renvoie le gestionnaire maître des fascicules. **Lecture seule** [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Retour :**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Renvoie le gestionnaire de polices. **Lecture seule** [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Retour :**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Renvoie le style de texte par défaut pour les formes. **Lecture seule** [ITextStyle](../../com.aspose.slides/itextstyle).

**Retour :**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Renvoie la collection des auteurs de commentaires. **Lecture seule** [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Retour :**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Renvoie l'objet DocumentProperties qui contient les propriétés standard et personnalisées du document. **Lecture seule** [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Retour :**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Renvoie la collection de toutes les images de la présentation. **Lecture seule** [IImageCollection](../../com.aspose.slides/iimagecollection).

**Retour :**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Renvoie la collection de tous les fichiers audio intégrés dans la présentation. **Lecture seule** [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Retour :**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Renvoie la collection de tous les fichiers vidéo intégrés dans la présentation. **Lecture seule** [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Retour :**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Renvoie les données personnalisées de la présentation. **Lecture seule** [ICustomData](../../com.aspose.slides/icustomdata).

**Retour :**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Obtient le projet VBA avec les macros de la présentation. **Lecture/écriture** [IVbaProject](../../com.aspose.slides/ivbaproject).

**Retour :**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Obtient le projet VBA avec les macros de la présentation. **Lecture/écriture** [IVbaProject](../../com.aspose.slides/ivbaproject).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Renvoie des informations sur le format à partir duquel la présentation a été chargée. **Lecture seule** [SourceFormat](../../com.aspose.slides/sourceformat).

**Retour :**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Renvoie le thème maître de la présentation. **Lecture seule** [IMasterTheme](../../com.aspose.slides/imastertheme).

**Retour :**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Fournit un accès facile à tous les hyperliens contenus dans toutes les diapositives de la présentation (pas dans les maîtres, mises en page, diapositives de notes). **Lecture seule** [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Retour :**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Obtient les propriétés de vue de la présentation. **Lecture seule** [IViewProperties](../../com.aspose.slides/iviewproperties).

**Retour :**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

Représente le numéro de la première diapositive dans la présentation. **Lecture/écriture** int.

**Retour :**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

Représente le numéro de la première diapositive dans la présentation. **Lecture/écriture** int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Renvoie toutes les parties de données personnalisées de la présentation. **Lecture seule** ICustomXmlPart[].

**Retour :**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Renvoie la collection des signatures utilisées pour signer la présentation. **Lecture seule** [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                    + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

Returns the collection of sensitivity labels applied to the presentation document. Read-only [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Affiche les libellés appliqués
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Ajoute le nouveau libellé
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Récupère l'ID du libellé de sensibilité depuis la politique
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Récupère l'identifiant du site Azure AD depuis la politique
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```
Saves all slides of a presentation to a file with the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| format | int | Format of the exported data. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```
Saves all slides of a presentation to a stream in the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| format | int | Format of the exported data. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

Saves all slides of a presentation to a file with the specified format and with additional options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| format | int | Format of the exported data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Additional format options. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Saves all slides of a presentation to a stream in the specified format and with additional options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| format | int | Format of the exported data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Additional format options. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

Enregistre les diapositives spécifiées d'une présentation dans un fichier au format spécifié.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Chemin du fichier créé. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```
Enregistre les diapositives spécifiées d'une présentation dans un fichier au format indiqué.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Additional format options. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Enregistre les diapositives spécifiées d'une présentation dans un flux au format indiqué.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux de sortie. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Enregistre les diapositives spécifiées d'une présentation dans un flux au format indiqué.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux de sortie. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Options de format supplémentaires. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```


Saves all slides of a presentation to a set of files representing XAML markup.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | The XAML format options. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```
Returns a Thumbnail Image objects for all slides of a presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |

**Returns:**
com.aspose.slides.IImage[] - objets IImage.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Renvoie des objets IImage miniature pour les diapositives spécifiées d'une présentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |

**Returns:**
com.aspose.slides.IImage[] - objets IImage.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```
Renvoie des objets Image miniature pour toutes les diapositives d'une présentation avec une mise à l'échelle personnalisée.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |
| scaleX | float | Valeur permettant de mettre à l'échelle cette miniature selon l'axe x. |
| scaleY | float | Valeur permettant de mettre à l'échelle cette miniature selon l'axe y. |

**Returns:**
com.aspose.slides.IImage[] - objets Bitmap.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Renvoie des objets Image miniature pour les diapositives spécifiées d'une présentation avec une mise à l'échelle personnalisée.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| slides | int[] | Array with slide positions, starting from 1. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.
### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```
Renvoie des objets Image miniature pour toutes les diapositives d'une présentation avec la taille spécifiée.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Taille de l'image à créer. |

**Returns:**
com.aspose.slides.IImage[] - objets IImage.
### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Returns a Thumbnail Image objects for specified slides of a presentation with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering options. |
| slides | int[] | Array with slide positions, starting from 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Size of the image to create. |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.
### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Renvoie une diapositive, MasterSlide ou LayoutSlide par Id.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| id | long | Id d'une diapositive. |

**Retour :**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```
Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```
 
Highlights all matches of the sample text with the specified color.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // mise en évidence de toutes les occurrences séparées de 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The text to highlight. |
| highlightColor | java.lang.Integer | The color to highlight the text. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Highlights all matches of the sample text with the specified color.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // mise en évidence de toutes les occurrences séparées de 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The text to highlight. |
| highlightColor | java.lang.Integer | The color to highlight the text. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Text search options [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | The callback object for receiving search results [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Highlights all matches of the regular expression with the specified color.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // mise en évidence de toutes les occurrences séparées de 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | The regular expression java.util.regex.Pattern to get strings to highlight. |
| highlightColor | java.lang.Integer | The color to highlight the text. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | The callback object for receiving search results [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Replaces all occurrences of the specified text with another specified text.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Remplace toutes les occurrences séparées de 'the' par '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | The string to be replaced. |
| newText | java.lang.String | The string to replace all occurrences of oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Text search options [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | The callback object for receiving search results [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)

Replaces all matches of the regular expression with the specified string.

--------------------

> ```
> L'exemple de code suivant montre comment remplacer du texte en utilisant une expression régulière par la chaîne spécifiée.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Replace all separate 'the' occurrences with '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | L'expression régulière java.util.regex.Pattern pour obtenir les chaînes à remplacer. |
| newText | java.lang.String | La chaîne qui remplacera toutes les occurrences des chaînes à remplacer. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |