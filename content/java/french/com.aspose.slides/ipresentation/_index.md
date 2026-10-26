---
title: IPresentation
second_title: Référence de l'API Aspose.Slides pour Java
description: Document de présentation
type: docs
url: /fr/com.aspose.slides/ipresentation/
---
**Toutes les interfaces implémentées:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Document de présentation
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Retourne ou définit la date et l'heure qui remplaceront le contenu des champs datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Retourne ou définit la date et l'heure qui remplaceront le contenu des champs datetime. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourne le gestionnaire HeaderFooter de la présentation. |
| [getProtectionManager()](#getProtectionManager--) | Obtient le gestionnaire des permissions pour cette présentation. |
| [getSlides()](#getSlides--) | Retourne une liste de toutes les diapositives définies dans la présentation. |
| [getSections()](#getSections--) | Retourne une liste de toutes les sections de diapositives définies dans la présentation. |
| [getSlideSize()](#getSlideSize--) | Retourne l'objet de taille de diapositive. |
| [getNotesSize()](#getNotesSize--) | Retourne l'objet de taille des notes de diapositive. |
| [getLayoutSlides()](#getLayoutSlides--) | Retourne une liste de toutes les diapositives de mise en page définies dans la présentation. |
| [getMasters()](#getMasters--) | Retourne une liste de toutes les diapositives maîtres définies dans la présentation. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Retourne le gestionnaire des notes maîtres. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Retourne le gestionnaire du maître de distribution. |
| [getFontsManager()](#getFontsManager--) | Retourne le gestionnaire de polices. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Retourne le style de texte par défaut pour les formes. |
| [getCommentAuthors()](#getCommentAuthors--) | Retourne la collection des auteurs de commentaires. |
| [getDocumentProperties()](#getDocumentProperties--) | Retourne l'objet DocumentProperties qui contient les propriétés de document standard et personnalisées. |
| [getImages()](#getImages--) | Retourne la collection de toutes les images de la présentation. |
| [getAudios()](#getAudios--) | Retourne la collection de tous les fichiers audio intégrés dans la présentation. |
| [getVideos()](#getVideos--) | Retourne la collection de tous les fichiers vidéo intégrés dans la présentation. |
| [getCustomData()](#getCustomData--) | Retourne les données personnalisées de la présentation. |
| [getVbaProject()](#getVbaProject--) | Obtient le projet VBA avec les macros de la présentation. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Obtient le projet VBA avec les macros de la présentation. |
| [getSourceFormat()](#getSourceFormat--) | Retourne les informations sur le format à partir duquel la présentation a été chargée. |
| [getMasterTheme()](#getMasterTheme--) | Retourne le thème maître de la présentation. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fournit un accès facile à tous les hyperliens contenus dans toutes les diapositives de la présentation (pas dans les maîtres, mises en page, diapositives de notes). |
| [getViewProperties()](#getViewProperties--) | Obtient les propriétés de vue de toute la présentation. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Représente le numéro de la première diapositive dans la présentation. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Représente le numéro de la première diapositive dans la présentation. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Retourne toutes les parties de données personnalisées de la présentation. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Retourne la collection des signatures utilisées pour signer la présentation. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Retourne la collection des étiquettes de sensibilité appliquées au document de présentation. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Enregistre toutes les diapositives d'une présentation dans un fichier avec le format spécifié. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Enregistre toutes les diapositives d'une présentation dans un fichier avec le format spécifié et avec des options supplémentaires. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié et avec des options supplémentaires. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Enregistre les diapositives spécifiées d'une présentation dans un fichier avec le format spécifié. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Enregistre les diapositives spécifiées d'une présentation dans un fichier avec le format spécifié. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Enregistre toutes les diapositives d'une présentation dans un ensemble de fichiers représentant le balisage XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Retourne des objets Image miniature pour toutes les diapositives d'une présentation. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Retourne des objets IImage miniature pour les diapositives spécifiées d'une présentation. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Retourne des objets Image miniature pour toutes les diapositives d'une présentation avec un redimensionnement personnalisé. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Retourne des objets Image miniature pour les diapositives spécifiées d'une présentation avec un redimensionnement personnalisé. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Retourne des objets Image miniature pour toutes les diapositives d'une présentation avec la taille spécifiée. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Retourne des objets Image miniature pour les diapositives spécifiées d'une présentation avec la taille spécifiée. |
| [getSlideById(long id)](#getSlideById-long-) | Retourne une Slide, MasterSlide ou LayoutSlide par Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Joint les cours qui ont le même formatage dans tous les paragraphes de toutes les formes admissibles de toutes les diapositives. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Met en évidence toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Met en évidence toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Met en évidence toutes les correspondances de l'expression régulière avec la couleur spécifiée. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Remplace toutes les occurrences du texte spécifié par un autre texte spécifié. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Remplace toutes les correspondances de l'expression régulière par la chaîne spécifiée. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

**Retourne ou définit la date et l'heure qui remplaceront le contenu des champs datetime. Heure de création de cet objet Presentation par défaut. Lecture/écriture java.util.Date.**

**Retourne :**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

**Retourne ou définit la date et l'heure qui remplaceront le contenu des champs datetime. Heure de création de cet objet Presentation par défaut. Lecture/écriture java.util.Date.**

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

**Retourne le gestionnaire HeaderFooter de la présentation. Lecture seule [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).**

**Retourne :**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

**Obtient le gestionnaire des permissions pour cette présentation. Lecture seule [IProtectionManager](../../com.aspose.slides/iprotectionmanager).**

**Retourne :**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

**Retourne une liste de toutes les diapositives définies dans la présentation. Lecture seule [ISlideCollection](../../com.aspose.slides/islidecollection).**

**Retourne :**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

**Retourne une liste de toutes les sections de diapositives définies dans la présentation. Lecture seule [ISectionCollection](../../com.aspose.slides/isectioncollection).**

**Retourne :**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

**Retourne l'objet de taille de diapositive. Lecture seule [ISlideSize](../../com.aspose.slides/islidesize).**

**Retourne :**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

**Retourne l'objet de taille des notes de diapositive. Lecture seule [INotesSize](../../com.aspose.slides/inotessize).**

**Retourne :**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

**Retourne une liste de toutes les diapositives de mise en page définies dans la présentation. Lecture seule [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).**

--------------------

Vous pouvez accéder à une API alternative pour ajouter/insérer/supprimer/dupliquer des diapositives de mise en page en utilisant la propriété IMasterSlide.LayoutSlides property.

**Retourne :**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

**Retourne une liste de toutes les diapositives maîtres définies dans la présentation. Lecture seule [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).**

**Retourne :**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

**Retourne le gestionnaire des notes maîtres. Lecture seule [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).**

**Retourne :**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

**Retourne le gestionnaire du maître de distribution. Lecture seule [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).**

**Retourne :**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

**Retourne le gestionnaire de polices. Lecture seule [IFontsManager](../../com.aspose.slides/ifontsmanager).**

**Retourne :**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

**Retourne le style de texte par défaut pour les formes. Lecture seule [ITextStyle](../../com.aspose.slides/itextstyle).**

**Retourne :**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

**Retourne la collection des auteurs de commentaires. Lecture seule [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).**

**Retourne :**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

**Retourne l'objet DocumentProperties qui contient les propriétés de document standard et personnalisées. Lecture seule [IDocumentProperties](../../com.aspose.slides/idocumentproperties).**

**Retourne :**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

**Retourne la collection de toutes les images de la présentation. Lecture seule [IImageCollection](../../com.aspose.slides/iimagecollection).**

**Retourne :**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

**Retourne la collection de tous les fichiers audio intégrés dans la présentation. Lecture seule [IAudioCollection](../../com.aspose.slides/iaudiocollection).**

**Retourne :**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

**Retourne la collection de tous les fichiers vidéo intégrés dans la présentation. Lecture seule [IVideoCollection](../../com.aspose.slides/ivideocollection).**

**Retourne :**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

**Retourne les données personnalisées de la présentation. Lecture seule [ICustomData](../../com.aspose.slides/icustomdata).**

**Retourne :**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

**Obtient le projet VBA avec les macros de la présentation. Lecture/écriture [IVbaProject](../../com.aspose.slides/ivbaproject).**

**Retourne :**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

**Obtient le projet VBA avec les macros de la présentation. Lecture/écriture [IVbaProject](../../com.aspose.slides/ivbaproject).**

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

**Retourne les informations sur le format à partir duquel la présentation a été chargée. Lecture seule [SourceFormat](../../com.aspose.slides/sourceformat).**

**Retourne :**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

**Retourne le thème maître de la présentation. Lecture seule [IMasterTheme](../../com.aspose.slides/imastertheme).**

**Retourne :**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

**Fournit un accès facile à tous les hyperliens contenus dans toutes les diapositives de la présentation (pas dans les maîtres, mises en page, diapositives de notes). Lecture seule [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).**

**Retourne :**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

**Obtient les propriétés de vue de toute la présentation. Lecture seule [IViewProperties](../../com.aspose.slides/iviewproperties).**

**Retourne :**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

**Représente le numéro de la première diapositive dans la présentation. Lecture/écriture int.**

**Retourne :**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

**Représente le numéro de la première diapositive dans la présentation. Lecture/écriture int.**

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

**Retourne toutes les parties de données personnalisées de la présentation. Lecture seule ICustomXmlPart[].**

**Retourne :**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

**Retourne la collection des signatures utilisées pour signer la présentation. Lecture seule [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).**

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


**Retourne :**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

**Retourne la collection des étiquettes de sensibilité appliquées au document de présentation. Lecture seule [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).**

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Imprimer les étiquettes appliquées
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Ajouter la nouvelle étiquette
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Obtenir l'ID de l'étiquette de sensibilité à partir de la politique
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Obtenir l'identifiant du site Azure AD à partir de la politique
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourne :**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

**Enregistre toutes les diapositives d'une présentation dans un fichier avec le format spécifié.**

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Chemin vers le fichier créé. |
| format | int | Format des données exportées. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

**Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié.**

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux de sortie. |
| format | int | Format des données exportées. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

**Enregistre toutes les diapositives d'une présentation dans un fichier avec le format spécifié et avec des options supplémentaires.**
| format | int | Format des données exportées. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Options de format supplémentaires. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```


Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié avec des options supplémentaires.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux de sortie. |
| format | int | Format des données exportées. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Options de format supplémentaires. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```


Enregistre les diapositives spécifiées d’une présentation dans un fichier au format indiqué.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Chemin du fichier créé. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```


Enregistre les diapositives spécifiées d’une présentation dans un fichier au format indiqué.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Chemin du fichier créé. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Options de format supplémentaires. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```


Enregistre les diapositives spécifiées d’une présentation dans un flux au format indiqué.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux de sortie. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```


Enregistre les diapositives spécifiées d’une présentation dans un flux au format indiqué.

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


Enregistre toutes les diapositives d’une présentation dans un ensemble de fichiers représentant le balisage XAML.

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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | Les options de format XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```


Renvoie des objets Image miniature pour toutes les diapositives d’une présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |

**Valeur de retour :**
com.aspose.slides.IImage[] - objets IImage.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```


Renvoie des objets IImage miniature pour les diapositives spécifiées d’une présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |

**Valeur de retour :**
com.aspose.slides.IImage[] - objets IImage.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```


Renvoie des objets Image miniature pour toutes les diapositives d’une présentation avec un redimensionnement personnalisé.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |
| scaleX | float | La valeur par laquelle mettre à l'échelle cette miniature dans la direction de l'axe x. |
| scaleY | float | La valeur par laquelle mettre à l'échelle cette miniature dans la direction de l'axe y. |

**Valeur de retour :**
com.aspose.slides.IImage[] - objets Bitmap.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```


Renvoie des objets Image miniature pour les diapositives spécifiées d’une présentation avec un redimensionnement personnalisé.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |
| scaleX | float | La valeur par laquelle mettre à l'échelle cette miniature dans la direction de l'axe x. |
| scaleY | float | La valeur par laquelle mettre à l'échelle cette miniature dans la direction de l'axe y. |

**Valeur de retour :**
com.aspose.slides.IImage[] - objets IImage.

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```


Renvoie des objets Image miniature pour toutes les diapositives d’une présentation avec la taille spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |
| imageSize | java.awt.Dimension | Taille de l'image à créer. |

**Valeur de retour :**
com.aspose.slides.IImage[] - objets IImage.

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```


Renvoie des objets Image miniature pour les diapositives spécifiées d’une présentation avec la taille spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |
| slides | int[] | Tableau contenant les positions des diapositives, à partir de 1. |
| imageSize | java.awt.Dimension | Taille de l'image à créer. |

**Valeur de retour :**
com.aspose.slides.IImage[] - objets IImage.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```


Renvoie une Slide, MasterSlide ou LayoutSlide par Id.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| id | long | Id d’une diapositive. |

**Valeur de retour :**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - objet IBaseSlide.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Joint les runs avec la même mise en forme dans tous les paragraphes de toutes les formes acceptables de toutes les diapositives.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```


Met en surbrillance toutes les correspondances du texte d’exemple avec la couleur spécifiée.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // mise en surbrillance de toutes les occurrences séparées de 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Le texte à mettre en surbrillance. |
| highlightColor | java.awt.Color | La couleur pour mettre en surbrillance le texte. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


Met en surbrillance toutes les correspondances du texte d’exemple avec la couleur spécifiée.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // mise en surbrillance de toutes les occurrences séparées de 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Le texte à mettre en surbrillance. |
| highlightColor | java.awt.Color | La couleur pour mettre en surbrillance le texte. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Options de recherche de texte [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L’objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```


Met en surbrillance toutes les correspondances de l’expression régulière avec la couleur spécifiée.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // mise en surbrillance de toutes les occurrences séparées de 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | L’expression régulière java.util.regex.Pattern pour obtenir les chaînes à mettre en surbrillance. |
| highlightColor | java.awt.Color | La couleur pour mettre en surbrillance le texte. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L’objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


Remplace toutes les occurrences du texte spécifié par un autre texte spécifié.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Remplacer toutes les occurrences séparées de 'the' par '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | La chaîne à remplacer. |
| newText | java.lang.String | La chaîne qui remplace toutes les occurrences de oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Options de recherche de texte [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L’objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


Remplace toutes les correspondances de l’expression régulière par la chaîne spécifiée.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Remplacer toutes les occurrences séparées de 'the' par '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | L’expression régulière java.util.regex.Pattern pour obtenir les chaînes à remplacer. |
| newText | java.lang.String | La chaîne qui remplace toutes les occurrences des chaînes à remplacer. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L’objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |