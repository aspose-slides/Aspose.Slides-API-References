---
title: IPresentation
second_title: Référence de l'API Aspose.Slides pour Java
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
| [getProtectionManager()](#getProtectionManager--) | Renvoie le gestionnaire des autorisations pour cette présentation. |
| [getSlides()](#getSlides--) | Renvoie la liste de toutes les diapositives définies dans la présentation. |
| [getSections()](#getSections--) | Renvoie la liste de toutes les sections de diapositives définies dans la présentation. |
| [getSlideSize()](#getSlideSize--) | Renvoie l'objet de taille de diapositive. |
| [getNotesSize()](#getNotesSize--) | Renvoie l'objet de taille de diapositive de notes. |
| [getLayoutSlides()](#getLayoutSlides--) | Renvoie la liste de toutes les diapositives de mise en page définies dans la présentation. |
| [getMasters()](#getMasters--) | Renvoie la liste de toutes les diapositives maîtres définies dans la présentation. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Renvoie le gestionnaire du maître des notes. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Renvoie le gestionnaire du maître du document de synthèse. |
| [getFontsManager()](#getFontsManager--) | Renvoie le gestionnaire des polices. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Renvoie le style de texte par défaut pour les formes. |
| [getCommentAuthors()](#getCommentAuthors--) | Renvoie la collection d’auteurs de commentaires. |
| [getDocumentProperties()](#getDocumentProperties--) | Renvoie l'objet DocumentProperties qui contient les propriétés de document standard et personnalisées. |
| [getImages()](#getImages--) | Renvoie la collection de toutes les images de la présentation. |
| [getAudios()](#getAudios--) | Renvoie la collection de tous les fichiers audio intégrés dans la présentation. |
| [getVideos()](#getVideos--) | Renvoie la collection de tous les fichiers vidéo intégrés dans la présentation. |
| [getCustomData()](#getCustomData--) | Renvoie les données personnalisées de la présentation. |
| [getVbaProject()](#getVbaProject--) | Renvoie le projet VBA contenant les macros de la présentation. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Renvoie le projet VBA contenant les macros de la présentation. |
| [getSourceFormat()](#getSourceFormat--) | Renvoie des informations sur le format à partir duquel la présentation a été chargée. |
| [getMasterTheme()](#getMasterTheme--) | Renvoie le thème maître de la présentation. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fournit un accès facile à tous les hyperliens contenus dans toutes les diapositives de la présentation (pas dans les diapositives maîtres, de mise en page ou de notes). |
| [getViewProperties()](#getViewProperties--) | Renvoie les propriétés de vue globales de la présentation. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Représente le numéro de la première diapositive dans la présentation. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Représente le numéro de la première diapositive dans la présentation. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Renvoie toutes les parties de données personnalisées dans la présentation. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Renvoie la collection de signatures utilisées pour signer la présentation. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Renvoie la collection d’étiquettes de sensibilité appliquées au document de présentation. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Enregistre toutes les diapositives d’une présentation dans un fichier au format spécifié. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Enregistre toutes les diapositives d’une présentation dans un fichier au format spécifié avec des options supplémentaires. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié avec des options supplémentaires. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Enregistre les diapositives spécifiées d’une présentation dans un fichier au format spécifié. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Enregistre les diapositives spécifiées d’une présentation dans un fichier au format spécifié. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Enregistre les diapositives spécifiées d’une présentation dans un flux au format spécifié. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Enregistre les diapositives spécifiées d’une présentation dans un flux au format spécifié. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Enregistre toutes les diapositives d’une présentation dans un ensemble de fichiers représentant le balisage XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Renvoie des objets Image miniature pour toutes les diapositives d’une présentation. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Renvoie des objets IImage miniature pour les diapositives spécifiées d’une présentation. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Renvoie des objets Image miniature pour toutes les diapositives d’une présentation avec un redimensionnement personnalisé. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Renvoie des objets Image miniature pour les diapositives spécifiées d’une présentation avec un redimensionnement personnalisé. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Renvoie des objets Image miniature pour toutes les diapositives d’une présentation avec la taille spécifiée. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Renvoie des objets Image miniature pour les diapositives spécifiées d’une présentation avec la taille spécifiée. |
| [getSlideById(long id)](#getSlideById-long-) | Renvoie une Slide, MasterSlide ou LayoutSlide par Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Fusionne les runs avec le même formatage dans tous les paragraphes de toutes les formes acceptables de toutes les diapositives. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Met en surbrillance toutes les correspondances du texte d’exemple avec la couleur spécifiée. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Met en surbrillance toutes les correspondances du texte d’exemple avec la couleur spécifiée. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Met en surbrillance toutes les correspondances de l’expression régulière avec la couleur spécifiée. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Remplace toutes les occurrences du texte spécifié par un autre texte spécifié. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Remplace toutes les correspondances de l’expression régulière par la chaîne spécifiée. |
| [refreshChartsData()](#refreshChartsData--) | Recharge les données de tous les graphiques de la présentation à partir de leurs classeurs source. |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | Recharge les données de tous les graphiques de la présentation à partir de leurs classeurs source. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Renvoie ou définit la date et l'heure qui remplaceront le contenu des champs datetime. Heure de création de cet objet Presentation par défaut. Lecture/écriture java.util.Date.

**Renvoie :**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Renvoie ou définit la date et l'heure qui remplaceront le contenu des champs datetime. Heure de création de cet objet Presentation par défaut. Lecture/écriture java.util.Date.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Renvoie le gestionnaire HeaderFooter de la présentation. Lecture seule [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Renvoie :**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Renvoie le gestionnaire des autorisations pour cette présentation. Lecture seule [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Renvoie :**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Renvoie la liste de toutes les diapositives définies dans la présentation. Lecture seule [ISlideCollection](../../com.aspose.slides/islidecollection).

**Renvoie :**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Renvoie la liste de toutes les sections de diapositives définies dans la présentation. Lecture seule [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Renvoie :**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Renvoie l'objet de taille de diapositive. Lecture seule [ISlideSize](../../com.aspose.slides/islidesize).

**Renvoie :**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Renvoie l'objet de taille de diapositive de notes. Lecture seule [INotesSize](../../com.aspose.slides/inotessize).

**Renvoie :**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Renvoie la liste de toutes les diapositives de mise en page définies dans la présentation. Lecture seule [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Vous pouvez accéder à l’API alternative pour ajouter/insérer/supprimer/dupliquer des diapositives de mise en page en utilisant la propriété IMasterSlide.LayoutSlides.

**Renvoie :**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Renvoie la liste de toutes les diapositives maîtres définies dans la présentation. Lecture seule [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Renvoie :**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Renvoie le gestionnaire du maître des notes. Lecture seule [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Renvoie :**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Renvoie le gestionnaire du maître du document de synthèse. Lecture seule [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Renvoie :**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Renvoie le gestionnaire des polices. Lecture seule [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Renvoie :**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Renvoie le style de texte par défaut pour les formes. Lecture seule [ITextStyle](../../com.aspose.slides/itextstyle).

**Renvoie :**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Renvoie la collection d’auteurs de commentaires. Lecture seule [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Renvoie :**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Renvoie l'objet DocumentProperties qui contient les propriétés de document standard et personnalisées. Lecture seule [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Renvoie :**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Renvoie la collection de toutes les images de la présentation. Lecture seule [IImageCollection](../../com.aspose.slides/iimagecollection).

**Renvoie :**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Renvoie la collection de tous les fichiers audio intégrés dans la présentation. Lecture seule [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Renvoie :**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Renvoie la collection de tous les fichiers vidéo intégrés dans la présentation. Lecture seule [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Renvoie :**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Renvoie les données personnalisées de la présentation. Lecture seule [ICustomData](../../com.aspose.slides/icustomdata).

**Renvoie :**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Renvoie le projet VBA contenant les macros de la présentation. Lecture/écriture [IVbaProject](../../com.aspose.slides/ivbaproject).

**Renvoie :**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Renvoie le projet VBA contenant les macros de la présentation. Lecture/écriture [IVbaProject](../../com.aspose.slides/ivbaproject).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Renvoie des informations sur le format à partir duquel la présentation a été chargée. Lecture seule [SourceFormat](../../com.aspose.slides/sourceformat).

**Renvoie :**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Renvoie le thème maître de la présentation. Lecture seule [IMasterTheme](../../com.aspose.slides/imastertheme).

**Renvoie :**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Fournit un accès facile à tous les hyperliens contenus dans toutes les diapositives de la présentation (pas dans les diapositives maîtres, de mise en page ou de notes). Lecture seule [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Renvoie :**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Renvoie les propriétés de vue globales de la présentation. Lecture seule [IViewProperties](../../com.aspose.slides/iviewproperties).

**Renvoie :**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

Représente le numéro de la première diapositive dans la présentation. Lecture/écriture int.

**Renvoie :**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

Représente le numéro de la première diapositive dans la présentation. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Renvoie toutes les parties de données personnalisées dans la présentation. Lecture seule ICustomXmlPart[].

**Renvoie :**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Renvoie la collection de signatures utilisées pour signer la présentation. Lecture seule [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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

**Renvoie :**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

Renvoie la collection d’étiquettes de sensibilité appliquées au document de présentation. Lecture seule [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

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
>      // Ajouter le nouveau libellé
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Obtenir l'Id du libellé de sensibilité depuis la politique
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Obtenir l'identifiant du site Azure AD depuis la politique
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

Enregistre toutes les diapositives d’une présentation dans un fichier au format spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Chemin du fichier créé. |
| format | int | Format des données exportées. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Enregistre toutes les diapositives d’une présentation dans un flux au format spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux de sortie. |
| format | int | Format des données exportées. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```
Enregistre toutes les diapositives d'une présentation dans un fichier avec le format spécifié et avec des options supplémentaires.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Chemin du fichier créé. |
| format | int | Format des données exportées. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Options de format supplémentaires. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié et avec des options supplémentaires.

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

Enregistre les diapositives spécifiées d'une présentation dans un fichier avec le format spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Chemin du fichier créé. |
| slides | int[] | Tableau avec les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Enregistre les diapositives spécifiées d'une présentation dans un fichier avec le format spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Chemin du fichier créé. |
| slides | int[] | Tableau avec les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Options de format supplémentaires. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux de sortie. |
| slides | int[] | Tableau avec les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux de sortie. |
| slides | int[] | Tableau avec les positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Options de format supplémentaires. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

Enregistre toutes les diapositives d'une présentation dans un ensemble de fichiers représentant le balisage XAML.

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
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | Options du format XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

Renvoie des objets Thumbnail Image pour toutes les diapositives d'une présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |

**Renvoie :**
com.aspose.slides.IImage[] - objets IImage.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Renvoie des objets Thumbnail IImage pour les diapositives spécifiées d'une présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |
| slides | int[] | Tableau avec les positions des diapositives, à partir de 1. |

**Renvoie :**
com.aspose.slides.IImage[] - objets IImage.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Renvoie des objets Thumbnail Image pour toutes les diapositives d'une présentation avec un redimensionnement personnalisé.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |
| scaleX | float | Valeur de mise à l'échelle de la miniature sur l'axe x. |
| scaleY | float | Valeur de mise à l'échelle de la miniature sur l'axe y. |

**Renvoie :**
com.aspose.slides.IImage[] - objets Bitmap.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Renvoie des objets Thumbnail Image pour les diapositives spécifiées d'une présentation avec un redimensionnement personnalisé.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |
| slides | int[] | Tableau avec les positions des diapositives, à partir de 1. |
| scaleX | float | Valeur de mise à l'échelle de la miniature sur l'axe x. |
| scaleY | float | Valeur de mise à l'échelle de la miniature sur l'axe y. |

**Renvoie :**
com.aspose.slides.IImage[] - objets IImage.

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

Renvoie des objets Thumbnail Image pour toutes les diapositives d'une présentation avec une taille spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |
| imageSize | java.awt.Dimension | Taille de l'image à créer. |

**Renvoie :**
com.aspose.slides.IImage[] - objets IImage.

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

Renvoie des objets Thumbnail Image pour les diapositives spécifiées d'une présentation avec une taille spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options de rendu. |
| slides | int[] | Tableau avec les positions des diapositives, à partir de 1. |
| imageSize | java.awt.Dimension | Taille de l'image à créer. |

**Renvoie :**
com.aspose.slides.IImage[] - objets IImage.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Renvoie une Slide, MasterSlide ou LayoutSlide par Id.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| id | long | Id d'une diapositive. |

**Renvoie :**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - objet IBaseSlide.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Joint les portions avec le même formatage dans tous les paragraphes de toutes les formes acceptables de toutes les diapositives.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

Met en évidence toutes les correspondances du texte d'exemple avec la couleur spécifiée.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // mise en surbrillance de toutes les occurrences distinctes de 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Le texte à mettre en évidence. |
| highlightColor | java.awt.Color | La couleur de mise en évidence du texte. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Met en évidence toutes les correspondances du texte d'exemple avec la couleur spécifiée.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // mise en surbrillance de toutes les occurrences distinctes de 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Le texte à mettre en évidence. |
| highlightColor | java.awt.Color | La couleur de mise en évidence du texte. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Options de recherche de texte [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

Met en évidence toutes les correspondances de l'expression régulière avec la couleur spécifiée.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // mise en surbrillance de toutes les occurrences distinctes de 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | L'expression régulière java.util.regex.Pattern pour obtenir les chaînes à mettre en évidence. |
| highlightColor | java.awt.Color | La couleur de mise en évidence du texte. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

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
>      // Remplacez toutes les occurrences distinctes de 'the' par '***'
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
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Remplace toutes les correspondances de l'expression régulière par la chaîne spécifiée.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Remplacez toutes les occurrences distinctes de 'the' par '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | L'expression régulière java.util.regex.Pattern pour obtenir les chaînes à remplacer. |
| newText | java.lang.String | La chaîne qui remplace toutes les occurrences des chaînes à remplacer. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### refreshChartsData() {#refreshChartsData--}
```
public abstract void refreshChartsData()
```

Recharge les données de tous les graphiques de la présentation à partir de leurs classeurs source.

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


### refreshChartsData(boolean skipFailedCharts) {#refreshChartsData-boolean-}
```
public abstract void refreshChartsData(boolean skipFailedCharts)
```

Recharge les données de tous les graphiques de la présentation à partir de leurs classeurs source.

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| skipFailedCharts | boolean | Détermine si le processus de rafraîchissement continue lorsqu'un graphique échoue à se mettre à jour. Si true, les graphiques qui provoquent une exception sont ignorés ; sinon l'exception est propagée. |