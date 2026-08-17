---
title: Presentation
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une présentation Microsoft PowerPoint.
type: docs
url: /fr/com.aspose.slides/presentation/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

Représente une présentation Microsoft PowerPoint.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // Instancie un objet Presentation qui représente un fichier de présentation
>  Presentation pres = new Presentation();
>  try {
>      // Récupère la première diapositive
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Ajoute une forme auto de type ligne
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Enregistre le fichier de présentation.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Charge tout fichier supporté dans Presentation, par ex. ppt, pptx, odp, etc.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // Enregistre le fichier de présentation.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Presentation()](#Presentation--) | Ce constructeur crée une nouvelle présentation à partir de zéro. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | Ce constructeur crée une nouvelle présentation à partir de zéro. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Ce constructeur est le mécanisme principal pour lire une présentation existante. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Ce constructeur est le mécanisme principal pour lire une présentation existante. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Ce constructeur obtient le chemin du fichier source à partir duquel le contenu de la présentation est lu. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Ce constructeur obtient le chemin du fichier source à partir duquel le contenu de la présentation est lu. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Renvoie ou définit la date et l'heure qui remplaceront le contenu des champs datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Renvoie ou définit la date et l'heure qui remplaceront le contenu des champs datetime. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Renvoie le gestionnaire HeaderFooter actuel. |
| [getProtectionManager()](#getProtectionManager--) | Obtient le gestionnaire des autorisations pour cette présentation. |
| [getSlides()](#getSlides--) | Renvoie la liste de toutes les diapositives définies dans la présentation. |
| [getSections()](#getSections--) | Renvoie la liste de toutes les sections de diapositives définies dans la présentation. |
| [getSlideSize()](#getSlideSize--) | Renvoie l'objet taille de diapositive. |
| [getNotesSize()](#getNotesSize--) | Renvoie l'objet taille de diapositive de notes. |
| [getLayoutSlides()](#getLayoutSlides--) | Renvoie la liste de toutes les diapositives de mise en page définies dans la présentation. |
| [getMasters()](#getMasters--) | Renvoie la liste de toutes les diapositives maîtres définies dans la présentation. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Renvoie le gestionnaire maître des notes. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Renvoie le gestionnaire maître du document de distribution. |
| [getFontsManager()](#getFontsManager--) | Renvoie le gestionnaire de polices. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Renvoie le style de texte par défaut pour les formes. |
| [getCommentAuthors()](#getCommentAuthors--) | Renvoie la collection des auteurs de commentaires. |
| [getDocumentProperties()](#getDocumentProperties--) | Renvoie l'objet DocumentProperties qui contient les propriétés de document standard et personnalisées. |
| [getImages()](#getImages--) | Renvoie la collection de toutes les images de la présentation. |
| [getAudios()](#getAudios--) | Renvoie la collection de tous les fichiers audio intégrés dans la présentation. |
| [getVideos()](#getVideos--) | Renvoie la collection de tous les fichiers vidéo intégrés dans la présentation. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Renvoie les paramètres du diaporama pour la présentation. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Renvoie la collection de signatures utilisées pour signer la présentation. |
| [getCustomData()](#getCustomData--) | Renvoie les données personnalisées de la présentation. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Renvoie toutes les parties de données personnalisées dans la présentation. |
| [getVbaProject()](#getVbaProject--) | Obtient ou définit le projet VBA avec les macros de présentation. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Obtient ou définit le projet VBA avec les macros de présentation. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fournit un accès facile à tous les hyperliens contenus dans toutes les diapositives de la présentation (pas dans les maîtres, mises en page, diapositives de notes). |
| [getViewProperties()](#getViewProperties--) | Obtient les propriétés de vue de toute la présentation. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Représente le numéro de la première diapositive dans la présentation |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Représente le numéro de la première diapositive dans la présentation |
| [getSensitivityLabels()](#getSensitivityLabels--) | Renvoie la collection d'étiquettes de sensibilité appliquées au document de présentation. |
| [getSlideById(long id)](#getSlideById-long-) | Renvoie une Slide, MasterSlide ou LayoutSlide par Id. |
| [getSourceFormat()](#getSourceFormat--) | Renvoie les informations sur le format à partir duquel la présentation a été chargée. |
| [getMasterTheme()](#getMasterTheme--) | Renvoie le thème maître. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Enregistre toutes les diapositives d'une présentation dans un fichier au format spécifié. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Enregistre toutes les diapositives d'une présentation dans un fichier au format spécifié avec des options supplémentaires. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié avec des options supplémentaires. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Enregistre toutes les diapositives d'une présentation dans un ensemble de fichiers représentant le balisage XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Renvoie des objets Image pour toutes les diapositives d'une présentation. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Renvoie des objets Image miniature pour les diapositives spécifiées d'une présentation. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Renvoie des objets Image miniature pour toutes les diapositives d'une présentation avec un redimensionnement personnalisé. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Renvoie des objets Image miniature pour les diapositives spécifiées d'une présentation avec un redimensionnement personnalisé. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Renvoie des objets Image miniature pour toutes les diapositives d'une présentation avec une taille spécifiée. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Renvoie des objets Image miniature pour les diapositives spécifiées d'une présentation avec une taille spécifiée. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Enregistre les diapositives spécifiées d'une présentation dans un fichier au format spécifié en conservant le numéro de page. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Enregistre les diapositives spécifiées d'une présentation dans un fichier au format spécifié en conservant le numéro de page. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié en conservant le numéro de page. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié en conservant le numéro de page. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Fusionne les sections avec le même formatage dans tous les paragraphes de toutes les formes acceptables de toutes les diapositives. |
| [dispose()](#dispose--) | Libère toutes les ressources utilisées par cet objet Presentation. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parente d'un texte. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Met en surbrillance toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Met en surbrillance toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Met en surbrillance toutes les correspondances de l'expression régulière avec la couleur spécifiée. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Remplace toutes les occurrences du texte spécifié par un autre texte spécifié. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Remplace toutes les correspondances de l'expression régulière par la chaîne spécifiée. |

### Presentation() {#Presentation--}
```
public Presentation()
```

Ce constructeur crée une nouvelle présentation à partir de zéro. La présentation créée possède une diapositive vide.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

Ce constructeur crée une nouvelle présentation à partir de zéro. La présentation créée possède une diapositive vide.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Options de chargement supplémentaires. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

Ce constructeur est le mécanisme principal pour lire une présentation existante.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux d'entrée. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

Ce constructeur est le mécanisme principal pour lire une présentation existante.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Flux d'entrée. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Options de chargement supplémentaires. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Ce constructeur obtient le chemin du fichier source à partir duquel le contenu de la présentation est lu.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Fichier d'entrée. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

Ce constructeur obtient le chemin du fichier source à partir duquel le contenu de la présentation est lu.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Fichier d'entrée. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Options de chargement supplémentaires. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Renvoie ou définit la date et l'heure qui remplaceront le contenu des champs datetime. Temps de création de cet objet Presentation par défaut. Lecture/écriture java.util.Date.

**Renvoie :**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Renvoie ou définit la date et l'heure qui remplaceront le contenu des champs datetime. Temps de création de cet objet Presentation par défaut. Lecture/écriture java.util.Date.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie :**
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

Renvoie le gestionnaire HeaderFooter actuel. Lecture seule [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // La propriété IsFooterVisible est utilisée pour indiquer qu'un espace réservé au pied de page de la diapositive n'est pas présent.
>      {
>          headerFooterManager.setFooterVisibility(true); // La méthode SetFooterVisibility est utilisée pour rendre l'espace réservé au pied de page de la diapositive visible.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // La propriété IsSlideNumberVisible est utilisée pour indiquer qu'un espace réservé au numéro de page de la diapositive n'est pas présent.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // La méthode SetSlideNumberVisibility est utilisée pour rendre l'espace réservé au numéro de page de la diapositive visible.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // La propriété IsDateTimeVisible est utilisée pour indiquer qu'un espace réservé à la date et l'heure de la diapositive n'est pas présent.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // La méthode SetFooterVisibility est utilisée pour rendre l'espace réservé à la date et l'heure de la diapositive visible.
>      }
>      headerFooterManager.setFooterText("Footer text"); // La méthode SetFooterText est utilisée pour définir le texte de l'espace réservé au pied de page de la diapositive.
>      headerFooterManager.setDateTimeText("Date and time text"); // La méthode SetDateTimeText est utilisée pour définir le texte de l'espace réservé à la date et l'heure de la diapositive.
>      pres.save("Presentation.ppt", SaveFormat.Ppt);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set child footer visibility inside Slide.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IMasterSlideHeaderFooterManager headerFooterManager = pres.getMasters().get_Item(0).getHeaderFooterManager();
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // La méthode SetFooterAndChildFootersVisibility est utilisée pour rendre la diapositive maître et tous les pieds de page enfants visibles.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // La méthode SetSlideNumberAndChildSlideNumbersVisibility est utilisée pour rendre la diapositive maître et tous les numéros de page enfants visibles.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // La méthode SetDateTimeAndChildDateTimesVisibility est utilisée pour rendre la diapositive maître et tous les espaces réservés à la date et l'heure enfants visibles.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // La méthode SetFooterAndChildFootersText est utilisée pour définir le texte de la diapositive maître et de tous les pieds de page enfants.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // La méthode SetDateTimeAndChildDateTimesText est utilisée pour définir le texte de la diapositive maître et de tous les espaces réservés à la date et l'heure enfants.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

Obtient le gestionnaire des autorisations pour cette présentation. Lecture seule [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Renvoie :**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

Renvoie la liste de toutes les diapositives définies dans la présentation. Lecture seule [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // Instancie la classe Presentation qui représente le fichier de présentation
>  Presentation pres = new Presentation();
>  try
>  {
>      // Définit la couleur d'arrière-plan de la première ISlide à bleu
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.BLUE);
>      pres.save("ContentBG_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slides' background image of PowerPoint Presentation.
>  
>  // Instancie la classe Presentation qui représente le fichier de présentation
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Définit l'arrière-plan avec une image
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Définit l'image
>      BufferedImage img = ImageIO.read(new File("Tulips.jpg"));
>      // Ajoute l'image à la collection d'images de la présentation
>      IPPImage imgx = pres.getImages().addImage(img);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      // Enregistre la présentation sur le disque
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // Instancie la classe Presentation pour charger le fichier de présentation source
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Applique la transition de type cercle sur la diapositive 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Applique la transition de type peigne sur la diapositive 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Enregistre la présentation sur le disque
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // Instancie la classe Presentation qui représente un fichier de présentation
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Applique la transition de type cercle sur la diapositive 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Définit la durée de transition à 3 secondes
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Applique la transition de type peigne sur la diapositive 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Définit la durée de transition à 5 secondes
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Applique la transition de type zoom sur la diapositive 3
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Définit la durée de transition à 7 secondes
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // Enregistre la présentation sur le disque
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

Renvoie la liste de toutes les sections de diapositives définies dans la présentation. Lecture seule [ISectionCollection](../../com.aspose.slides/isectioncollection).

--------------------

> ```
> The following examples shows how to create Sections in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide defaultSlide = pres.getSlides().get_Item(0);
>      ISlide newSlide1 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide2 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide3 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide4 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISection section1 = pres.getSections().addSection("Section 1", newSlide1);
>      // la section1 se terminera à newSlide2 et après cela la section2 commencera
>      ISection section2 = pres.getSections().addSection("Section 2", newSlide3);
>      pres.save("pres-sections.pptx", SaveFormat.Pptx);
>      pres.getSections().reorderSectionWithSlides(section2, 0);
>      pres.save("pres-sections-moved.pptx", SaveFormat.Pptx);
>      pres.getSections().removeSectionWithSlides(section2);
>      pres.getSections().appendEmptySection("Last empty section");
>      pres.save("pres-section-with-empty.pptx",SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to changing the names of Sections.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISection section = pres.getSections().get_Item(0);
>      section.setName("My section");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

Renvoie l'objet taille de diapositive. Lecture seule [ISlideSize](../../com.aspose.slides/islidesize).

--------------------

> ```
> The following example shows how to change the slide size in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx");
>  try {
>      pres.getSlideSize().setSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
>      pres.save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slide size with respect to content scaling for a PowerPoint Presentation.
>  
>  // Instancie un objet Presentation qui représente un fichier de présentation
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Définit la taille des diapositives des présentations générées à celle de la source
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // La méthode SetSize est utilisée pour définir la taille de la diapositive avec redimensionnement du contenu afin d'assurer l'ajustement
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // La méthode SetSize est utilisée pour définir la taille de la diapositive en maximisant la taille du contenu
>          // Enregistre la présentation sur le disque
>          auxPresentation.save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (auxPresentation != null) auxPresentation.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  The following example shows how to specifying custom slide sizes in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // Taille papier A4
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

Renvoie l'objet taille de diapositive de notes. Lecture seule [INotesSize](../../com.aspose.slides/inotessize).

**Renvoie :**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Renvoie la liste de toutes les diapositives de mise en page définies dans la présentation. Lecture seule [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Vous pouvez accéder à l'API alternative pour ajouter/insérer/supprimer/cloner des diapositives de mise en page en utilisant la propriété IMasterSlide.LayoutSlides.

**Renvoie :**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Renvoie la liste de toutes les diapositives maîtres définies dans la présentation. Lecture seule [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // Instantiate the Presentation class that represents the presentation file
>  Presentation pres = new Presentation();
>  try
>  {
>      // Set the background color of the Master ISlide to Forest Green
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Write the presentation to disk
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the presentation file
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Try to search by layout slide type
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // The situation when a presentation doesn't contain some type of layouts.
>          // presentation File only contains Blank and Custom layout types.
>          // But layout slides with Custom types has different slide names,
>          // like "Title", "Title and Content", etc. And it is possible to use these
>          // names for layout slide selection.
>          // Also it is possible to use the set of placeholder shape types. For example,
>          // Title slide should have only Title pleceholder type, etc.
>          for (ILayoutSlide titleAndObjectLayoutSlide : (Iterable) layoutSlides)
>          {
>              if ("Title and Object".equals(titleAndObjectLayoutSlide.getName()))
>              {
>                  layoutSlide = titleAndObjectLayoutSlide;
>                  break;
>              }
>          }
>          if (layoutSlide == null)
>          {
>              for (ILayoutSlide titleLayoutSlide : (Iterable) layoutSlides)
>              {
>                  if ("Title".equals(titleLayoutSlide.getName()))
>                  {
>                      layoutSlide = titleLayoutSlide;
>                      break;
>                  }
>              }
>              if (layoutSlide == null)
>              {
>                  layoutSlide = layoutSlides.getByType(SlideLayoutType.Blank);
>                  if (layoutSlide == null)
>                  {
>                      layoutSlide = layoutSlides.add(SlideLayoutType.TitleAndObject, "Title and Object");
>                  }
>              }
>          }
>      }
>      // Adding empty slide with added layout slide
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Save presentation
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Renvoie :**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

Renvoie le gestionnaire maître des notes. Lecture seule [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Renvoie :**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Renvoie le gestionnaire maître du document de distribution. Lecture seule [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Renvoie :**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Renvoie le gestionnaire de polices. Lecture seule [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Charge la présentation
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Charge la police source à remplacer
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
>      // Enregistre la présentation
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

Renvoie le style de texte par défaut pour les formes. Lecture seule [ITextStyle](../../com.aspose.slides/itextstyle).

**Renvoie :**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Renvoie la collection des auteurs de commentaires. Lecture seule [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Renvoie :**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Renvoie l'objet DocumentProperties qui contient les propriétés de document standard et personnalisées. Lecture seule [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Renvoie :**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

Renvoie la collection de toutes les images de la présentation. Lecture seule [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // crée une nouvelle présentation à laquelle l'image sera ajoutée.
>  Presentation pres = new Presentation();
>  try
>  {
>      // supposons que nous ayons le gros fichier image que nous voulons inclure dans la présentation
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Ajoutons l'image à la présentation - nous choisissons le comportement KeepLocked car nous
>          // N'AVONS PAS l'intention d'accéder au fichier "largeImage.png" file.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Enregistre la présentation. Pendant la création d'une grande présentation, la consommation de mémoire
>          // reste faible pendant le cycle de vie de l'objet pres
>          pres.save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
>      }
>      finally
>      {
>          fip.close();
>      }
>  }
>  catch (java.io.IOException e) { }
>  finally
>  {
>      pres.dispose();
>  }
>  
>  The following examples add a hyperlink to an image in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Ajoute l'image à la présentation
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // Crée un cadre image sur la diapositive 1 basé sur l'image ajoutée précédemment
>      IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

Renvoie la collection de tous les fichiers audio intégrés dans la présentation. Lecture seule [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAudio audio = pres.getAudios().addAudio(Files.readAllBytes(Paths.get("audio.mp3")));
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>      audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```
Renvoie la collection de tous les fichiers vidéo incorporés dans la présentation. Lecture seule [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Get the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Embedd vide inside presentation
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // Add Video Frame
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // Set video to Video Frame
>      vf.setEmbeddedVideo(vid);
>      // Set Play Mode and Volume of the Video
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // Write the PPTX file to disk
>      pres.save("VideoFrame_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a video passing path to the video file directly into AddVideoFrame method for PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 150, "video1.avi");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add large file through BLOB to a Presentation.
>  
>  // Creates a new presentation to which the video will be added
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // Let's add the video to the presentation - we chose the KeepLocked behavior because we do
>          //not intend to access the "veryLargeVideo.avi" file.
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // Saves the presentation. While a large presentation gets outputted, the memory consumption
>          // stays low through the pres object's lifecycle
>          pres.save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fileStream != null) fileStream.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to export large file through BLOB from PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  // Locks the source file and does NOT load it into memory
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  // Creates a Presentation's instance, locks the "hugePresentationWithAudiosAndVideos.pptx" file.
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // Let's save each video to a file. To prevent high memory usage, we need a buffer that will be used
>      // to transfer the data from the presentation's video stream to a stream for a newly created video file.
>      byte[] buffer = new byte[81024];
>      // Iterates through the videos
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // Opens the presentation video stream. Please, note that we intentionally avoided accessing properties
>          // like video.BinaryData - because this property returns a byte array containing a full video, which then
>          // causes bytes to be loaded into memory. We use video.GetStream, which will return Stream - and does NOT
>          //  require us to load the whole video into the memory.
>          InputStream presVideoStream = video.getStream();
>          try {
>              FileOutputStream outputFileStream = new FileOutputStream("video{index}.avi");
>              try {
>                  int bytesRead;
>                  while ((bytesRead = presVideoStream.read(buffer, 0, buffer.length)) > 0) {
>                      outputFileStream.write(buffer, 0, bytesRead);
>                  }
>              } finally {
>                  if (outputFileStream != null) outputFileStream.close();
>              }
>          } finally {
>              if (presVideoStream != null) presVideoStream.close();
>          }
>          // Memory consumption will remain low regardless of the size of the video or presentation,
>      }
>      // If necessary, you can apply the same steps for audio files.
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a hyperlink to a video in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.avi")));
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 100, 100, video);
>      videoFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      videoFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to create Video Frame with Video from Web Source in a PowerPoint Presentation.
>  
>  public static void run()
>  {
>      Presentation pres = new Presentation();
>      try {
>          addVideoFromYouTube(pres, "Tj75Arhq5ho");
>          pres.save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
>      } catch(IOException e) {
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  }
>  private static void addVideoFromYouTube(Presentation pres, String videoId) throws IOException
>  {
>      //add videoFrame
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      //load thumbnail
>      String thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
>      URL url = new URL(thumbnailUri);
>      URLConnection connection = url.openConnection();
>      connection.setConnectTimeout(5000);
>      connection.setReadTimeout(10000);
>      InputStream input = connection.getInputStream();
>      ByteArrayOutputStream output = new ByteArrayOutputStream();
>      try
>      {
>          byte[] buffer = new byte[8192];
>          for (int count; (count = input.read(buffer)) > 0; )
>          {
>              output.write(buffer, 0, count);
>          }
>          videoFrame.getPictureFormat().getPicture().setImage(pres.getImages().addImage(output.toByteArray()));
>      } finally {
>          if (input != null) input.close();
>          if (output != null) output.close();
>      }
>  }
>  
>  The following examples shows how to extract Video from slide of PowerPoint Presentation.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation presentation = new Presentation("Video.pptx");
>  try {
>      for (ISlide slide : presentation.getSlides())
>      {
>          for (IShape shape : presentation.getSlides().get_Item(0).getShapes())
>          {
>              if (shape instanceof VideoFrame)
>              {
>                  IVideoFrame vf = (IVideoFrame) shape;
>                  String type = vf.getEmbeddedVideo().getContentType();
>                  int ss = type.lastIndexOf('/');
>                  type = type.substring(ss + 1);
>                  byte[] buffer = vf.getEmbeddedVideo().getBinaryData();
>                  FileOutputStream fop = new FileOutputStream("NewVideo_out." + type);
>                  try
>                  {
>                      fop.write(buffer);
>                      fop.flush();
>                      fop.close();
>                  }
>                  finally
>                  {
>                      if (presentation != null) presentation.dispose();
>                  }
>              }
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Renvoie :**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```


Renvoie les paramètres du diaporama pour la présentation.

**Renvoie :**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
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
>                   + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
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
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```


Renvoie les données personnalisées de la présentation. Lecture seule [ICustomData](../../com.aspose.slides/icustomdata).

**Renvoie :**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```


Renvoie toutes les parties de données personnalisées dans la présentation. Lecture seule ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Parcourt toutes les parties XML personnalisées
>      for (ICustomXmlPart item : pres.getAllCustomXmlParts())
>      {
>          item.remove();
>      }
>      pres.save("out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
com.aspose.slides.ICustomXmlPart[]
### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```


Obtient ou définit le projet VBA avec les macros de la présentation. Lecture/écriture [IVbaProject](../../com.aspose.slides/ivbaproject).

**Renvoie :**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```


Obtient ou définit le projet VBA avec les macros de la présentation. Lecture/écriture [IVbaProject](../../com.aspose.slides/ivbaproject).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```


Fournit un accès facile à tous les hyperliens contenus dans toutes les diapositives de la présentation (pas dans les diapositives maître, modèle, notes). Lecture seule [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Renvoie :**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```


Obtient les propriétés de vue de la présentation. Lecture seule [IViewProperties](../../com.aspose.slides/iviewproperties).

**Renvoie :**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```


Représente le numéro de la première diapositive dans la présentation

**Renvoie :**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```


Représente le numéro de la première diapositive dans la présentation

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```


Renvoie la collection d'étiquettes de sensibilité appliquées au document de présentation. Lecture seule [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Imprimer les libellés appliqués
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Ajouter le nouveau libellé
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Obtenez l'Id du libellé de sensibilité à partir de la stratégie
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Obtenez l'identifiant du site Azure AD à partir de la stratégie
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
### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```


Renvoie une Slide, MasterSlide ou LayoutSlide par Id.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| id | long | Id d'une diapositive. |

**Renvoie :**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```


Renvoie des informations sur le format à partir duquel la présentation a été chargée. Lecture seule [SourceFormat](../../com.aspose.slides/sourceformat).

**Renvoie :**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```


Renvoie le thème maître. Lecture seule [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  //Instantiate a presentation object that represents a presentation file
>  Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
>  try {
>      pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
>      ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
>      pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**Renvoie :**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```


Enregistre toutes les diapositives d'une présentation dans un fichier au format spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Chemin du fichier créé. |
| format | int | Format des données exportées. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```


Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux de sortie. |
| format | int | Format des données exportées. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```


Enregistre toutes les diapositives d'une présentation dans un fichier au format spécifié avec des options supplémentaires.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Chemin du fichier créé. |
| format | int | Format des données exportées. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Options de format supplémentaires. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```


Enregistre toutes les diapositives d'une présentation dans un flux au format spécifié avec des options supplémentaires.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux de sortie. |
| format | int | Format des données exportées. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Options de format supplémentaires. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
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
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | Les options du format XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```


Renvoie des objets Image pour toutes les diapositives d'une présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options Tiff. |

**Renvoie :**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```


Renvoie des objets Image miniature pour les diapositives spécifiées d'une présentation.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options Tiff. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |

**Renvoie :**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```


Renvoie des objets Image miniature pour toutes les diapositives d'une présentation avec une mise à l'échelle personnalisée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options Tiff. |
| scaleX | float | Valeur de mise à l'échelle de la miniature sur l'axe x. |
| scaleY | float | Valeur de mise à l'échelle de la miniature sur l'axe y. |

**Renvoie :**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```


Renvoie des objets Image miniature pour les diapositives spécifiées d'une présentation avec une mise à l'échelle personnalisée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options Tiff. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| scaleX | float | Valeur de mise à l'échelle de la miniature sur l'axe x. |
| scaleY | float | Valeur de mise à l'échelle de la miniature sur l'axe y. |

**Renvoie :**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```


Renvoie des objets Image miniature pour toutes les diapositives d'une présentation avec la taille spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options Tiff. |
| imageSize | java.awt.Dimension | Taille de l'image à créer. |

**Renvoie :**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```


Renvoie des objets Image miniature pour les diapositives spécifiées d'une présentation avec la taille spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Options Tiff. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| imageSize | java.awt.Dimension | Taille de l'image à créer. |

**Renvoie :**
com.aspose.slides.IImage[] - Image objects.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```


Enregistre les diapositives spécifiées d'une présentation dans un fichier au format spécifié tout en conservant le numéro de page.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Chemin du fichier créé. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```


Enregistre les diapositives spécifiées d'une présentation dans un fichier au format spécifié tout en conservant le numéro de page.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Chemin du fichier créé. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Options de format supplémentaires. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```


Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié tout en conservant le numéro de page.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux de sortie. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```


Enregistre les diapositives spécifiées d'une présentation dans un flux au format spécifié tout en conservant le numéro de page.

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom dimensions.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      float scaleX = 2f;
>      float scaleY = 2f;
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(scaleX, scaleY), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom size.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Dimension size = new Dimension(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(size), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Flux de sortie. |
| slides | int[] | Tableau des positions des diapositives, à partir de 1. |
| format | int | Format des données exportées. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Options de format supplémentaires. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Fusionne les segments avec le même format dans tous les paragraphes de toutes les formes acceptables de toutes les diapositives.

### dispose() {#dispose--}
```
public final void dispose()
```


Libère toutes les ressources utilisées par cet objet Presentation.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Renvoie la présentation parente d'un texte. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie :**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```


Met en surbrillance toutes les correspondances du texte d'exemple avec la couleur spécifiée.

--------------------

> ```
> Presentation presentation = new Presentation("SomePresentation.pptx");
> try {
>      // mise en évidence de toutes les occurrences séparées de 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
> } finally {
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
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


Met en surbrillance toutes les correspondances du texte d'exemple avec la couleur spécifiée.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // mise en évidence de toutes les occurrences séparées de 'the'
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
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
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```


Met en surbrillance toutes les correspondances de l'expression régulière avec la couleur spécifiée.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // mise en évidence de tous les mots de 10 caractères ou plus
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | L'expression régulière java.util.regex.Pattern pour obtenir les chaînes à mettre en surbrillance. |
| highlightColor | java.awt.Color | La couleur pour mettre en surbrillance le texte. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
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
>      // Remplace toutes les occurrences séparées de 'the' par '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | La chaîne à remplacer. |
| newText | java.lang.String | La chaîne qui remplace toutes les occurrences de oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Options de recherche de texte [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


Remplace toutes les correspondances de l'expression régulière par la chaîne spécifiée.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Remplace tous les mots de 10 caractères ou plus par '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | L'expression régulière java.util.regex.Pattern pour obtenir les chaînes à remplacer. |
| newText | java.lang.String | La chaîne qui remplace toutes les occurrences des chaînes à remplacer. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |