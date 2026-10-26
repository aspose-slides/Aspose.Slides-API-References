---
title: DocumentProperties
second_title: Référence API Aspose.Slides pour Java
description: Représente les propriétés d'une présentation.
type: docs
url: /fr/com.aspose.slides/documentproperties/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

Représente les propriétés d'une présentation.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // Instancie la classe Presentation qui représente la présentation
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Crée une référence à l'objet IDocumentProperties associé à la présentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Affiche les propriétés intégrées
>      System.out.println("Category : " + documentProperties.getCategory());
>      System.out.println("Current Status : " + documentProperties.getContentStatus());
>      System.out.println("Creation Date : " + documentProperties.getCreatedTime());
>      System.out.println("Author : " + documentProperties.getAuthor());
>      System.out.println("Description : " + documentProperties.getComments());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to modify built-in Properties of PowerPoint Presentation.
>  
>  // Instancie la classe Presentation qui représente la présentation
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Crée une référence à l'objet IDocumentProperties associé à la présentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Définit les propriétés intégrées
>      documentProperties.setAuthor("Aspose.Slides for Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // Enregistre votre présentation dans un fichier
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | Initialise une nouvelle instance de la classe [DocumentProperties](../../com.aspose.slides/documentproperties). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Renvoie la version de l'application. |
| [getNameOfApplication()](#getNameOfApplication--) | Renvoie ou définit le nom de l'application. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Renvoie ou définit le nom de l'application. |
| [getCompany()](#getCompany--) | Renvoie ou définit la propriété de l'entreprise. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Renvoie ou définit la propriété de l'entreprise. |
| [getManager()](#getManager--) | Renvoie ou définit la propriété du responsable. |
| [setManager(String value)](#setManager-java.lang.String-) | Renvoie ou définit la propriété du responsable. |
| [getPresentationFormat()](#getPresentationFormat--) | Renvoie ou définit le format prévu d'une présentation. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Renvoie ou définit le format prévu d'une présentation. |
| [getSharedDoc()](#getSharedDoc--) | Détermine si la présentation est partagée entre plusieurs personnes. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Détermine si la présentation est partagée entre plusieurs personnes. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Renvoie ou définit le modèle d'une application. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Renvoie ou définit le modèle d'une application. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Temps total d'édition d'une présentation. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Temps total d'édition d'une présentation. |
| [getTitle()](#getTitle--) | Renvoie ou définit le titre d'une présentation. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Renvoie ou définit le titre d'une présentation. |
| [getSubject()](#getSubject--) | Renvoie ou définit le sujet d'une présentation. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Renvoie ou définit le sujet d'une présentation. |
| [getAuthor()](#getAuthor--) | Renvoie ou définit l'auteur d'une présentation. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Renvoie ou définit l'auteur d'une présentation. |
| [getKeywords()](#getKeywords--) | Renvoie ou définit les mots-clés d'une présentation. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Renvoie ou définit les mots-clés d'une présentation. |
| [getComments()](#getComments--) | Renvoie ou définit les commentaires d'une présentation. |
| [setComments(String value)](#setComments-java.lang.String-) | Renvoie ou définit les commentaires d'une présentation. |
| [getCategory()](#getCategory--) | Renvoie ou définit la catégorie d'une présentation. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Renvoie ou définit la catégorie d'une présentation. |
| [getCreatedTime()](#getCreatedTime--) | Renvoie la date de création d'une présentation. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Renvoie la date de création d'une présentation. |
| [getLastSavedTime()](#getLastSavedTime--) | Renvoie la date de dernière modification d'une présentation. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Renvoie la date de dernière modification d'une présentation. |
| [getLastPrinted()](#getLastPrinted--) | Renvoie la date à laquelle une présentation a été imprimée la dernière fois. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Renvoie la date à laquelle une présentation a été imprimée la dernière fois. |
| [getLastSavedBy()](#getLastSavedBy--) | Renvoie ou définit le nom de la dernière personne ayant modifié une présentation. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Renvoie ou définit le nom de la dernière personne ayant modifié une présentation. |
| [getRevisionNumber()](#getRevisionNumber--) | Renvoie ou définit le numéro de révision de la présentation. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Renvoie ou définit le numéro de révision de la présentation. |
| [getContentStatus()](#getContentStatus--) | Renvoie ou définit l'état du contenu d'une présentation. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Renvoie ou définit l'état du contenu d'une présentation. |
| [getContentType()](#getContentType--) | Renvoie ou définit le type de contenu d'une présentation. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Renvoie ou définit le type de contenu d'une présentation. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Renvoie ou définit la propriété HyperlinkBase du document. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Renvoie ou définit la propriété HyperlinkBase du document. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Renvoie le nombre de propriétés personnalisées réellement contenues dans une collection. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Renvoie le nom d'une propriété personnalisée à l'index spécifié. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Supprime une propriété personnalisée associée à un nom spécifié. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Vérifie la présence d'une propriété personnalisée avec un nom spécifié. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Renvoie ou définit la propriété personnalisée associée à un nom spécifié. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Renvoie ou définit la propriété personnalisée associée à un nom spécifié. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Définit une propriété personnalisée booléenne nommée. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Définit une propriété personnalisée entière nommée. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Définit une propriété personnalisée DateTime nommée. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Définit une propriété personnalisée chaîne nommée. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Définit une propriété personnalisée flottante nommée. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Définit une propriété personnalisée double nommée. |
| [clearCustomProperties()](#clearCustomProperties--) | Supprime toutes les propriétés personnalisées. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Obtient un tableau d'étiquettes de sensibilité à partir des propriétés personnalisées du document (Métadonnées du SDK Microsoft Information Protection). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Efface et définit les valeurs par défaut pour toutes les propriétés intégrées. |
| [getScaleCrop()](#getScaleCrop--) | Indique le mode d'affichage de la miniature du document. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Indique le mode d'affichage de la miniature du document. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Indique si les hyperliens dans un document sont à jour. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Indique si les hyperliens dans un document sont à jour. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Spécifie qu'un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Spécifie qu'un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. |
| [getSlides()](#getSlides--) | Renvoie le nombre total de diapositives dans un document de présentation. |
| [getHiddenSlides()](#getHiddenSlides--) | Renvoie le nombre de diapositives masquées dans un document de présentation. |
| [getNotes()](#getNotes--) | Renvoie le nombre de diapositives dans une présentation contenant des notes. |
| [getParagraphs()](#getParagraphs--) | Renvoie le nombre total de paragraphes trouvés dans un document le cas échéant. |
| [getWords()](#getWords--) | Renvoie le nombre total de mots contenus dans un document. |
| [getMultimediaClips()](#getMultimediaClips--) | Renvoie le nombre total de clips audio ou vidéo présents dans le document. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Spécifie le titre de chaque partie du document. |
| [getHeadingPairs()](#getHeadingPairs--) | Indique le regroupement des parties du document et le nombre de parties dans chaque groupe. |
| [deepClone()](#deepClone--) | Clone l'objet actuel. |
| [cloneT()](#cloneT--) | Clone l'objet actuel. |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```

Initialise une nouvelle instance de la classe [DocumentProperties](../../com.aspose.slides/documentproperties).

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```

Renvoie la version de l'application. Lecture seule String.

**Renvoie :**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```

Renvoie ou définit le nom de l'application. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```

Renvoie ou définit le nom de l'application. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```

Renvoie ou définit la propriété de l'entreprise. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```

Renvoie ou définit la propriété de l'entreprise. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```

Renvoie ou définit la propriété du responsable. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```

Renvoie ou définit la propriété du responsable. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```

Renvoie ou définit le format prévu d'une présentation. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```

Renvoie ou définit le format prévu d'une présentation. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```

Détermine si la présentation est partagée entre plusieurs personnes. Lecture/écriture boolean.

**Renvoie :**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```

Détermine si la présentation est partagée entre plusieurs personnes. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```

Renvoie ou définit le modèle d'une application. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```

Renvoie ou définit le modèle d'une application. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```

Temps total d'édition d'une présentation. Lecture/écriture double.

**Renvoie :**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```

Temps total d'édition d'une présentation. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

Renvoie ou définit le titre d'une présentation. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

Renvoie ou définit le titre d'une présentation. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```

Renvoie ou définit le sujet d'une présentation. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```

Renvoie ou définit le sujet d'une présentation. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```

Renvoie ou définit l'auteur d'une présentation. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```

Renvoie ou définit l'auteur d'une présentation. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```

Renvoie ou définit les mots-clés d'une présentation. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```

Renvoie ou définit les mots-clés d'une présentation. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```

Renvoie ou définit les commentaires d'une présentation. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```

Renvoie ou définit les commentaires d'une présentation. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```

Renvoie ou définit la catégorie d'une présentation. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```

Renvoie ou définit la catégorie d'une présentation. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```
Renvoie la date à laquelle une présentation a été créée. Les valeurs sont en UTC. Lecture/écriture java.util.Date.

**Renvoie:**  
java.util.Date  
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}  
```
public final void setCreatedTime(Date value)
```

Renvoie la date à laquelle une présentation a été créée. Les valeurs sont en UTC. Lecture/écriture java.util.Date.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}  
```
public final Date getLastSavedTime()
```

Renvoie la date à laquelle une présentation a été modifiée pour la dernière fois. Les valeurs sont en UTC. Lecture seule dans le cas de Presentation.DocumentProperties (car elle sera mise à jour en interne pendant le processus de sauvegarde de l'objet IPresentation). Peut être modifiée via l'instance DocumentProperties retournée par la méthode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Veuillez consulter l'exemple dans le résumé de la méthode [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Renvoie:**  
java.util.Date  
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}  
```
public final void setLastSavedTime(Date value)
```

Renvoie la date à laquelle une présentation a été modifiée pour la dernière fois. Les valeurs sont en UTC. Lecture seule dans le cas de Presentation.DocumentProperties (car elle sera mise à jour en interne pendant le processus de sauvegarde de l'objet IPresentation). Peut être modifiée via l'instance DocumentProperties retournée par la méthode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Veuillez consulter l'exemple dans le résumé de la méthode [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}  
```
public final Date getLastPrinted()
```

Renvoie la date à laquelle une présentation a été imprimée pour la dernière fois. Lecture/écriture java.util.Date.

**Renvoie:**  
java.util.Date  
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}  
```
public final void setLastPrinted(Date value)
```

Renvoie la date à laquelle une présentation a été imprimée pour la dernière fois. Lecture/écriture java.util.Date.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}  
```
public final String getLastSavedBy()
```

Renvoie ou définit le nom de la dernière personne ayant modifié une présentation. Lecture/écriture String.

**Renvoie:**  
java.lang.String  
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}  
```
public final void setLastSavedBy(String value)
```

Renvoie ou définit le nom de la dernière personne ayant modifié une présentation. Lecture/écriture String.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}  
```
public final int getRevisionNumber()
```

Renvoie ou définit le numéro de révision de la présentation. Lecture/écriture int.

**Renvoie:**  
int  
### setRevisionNumber(int value) {#setRevisionNumber-int-}  
```
public final void setRevisionNumber(int value)
```

Renvoie ou définit le numéro de révision de la présentation. Lecture/écriture int.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}  
```
public final String getContentStatus()
```

Renvoie ou définit l’état du contenu d’une présentation. Lecture/écriture String.

**Renvoie:**  
java.lang.String  
### setContentStatus(String value) {#setContentStatus-java.lang.String-}  
```
public final void setContentStatus(String value)
```

Renvoie ou définit l’état du contenu d’une présentation. Lecture/écriture String.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}  
```
public final String getContentType()
```

Renvoie ou définit le type de contenu d’une présentation. Lecture/écriture String.

**Renvoie:**  
java.lang.String  
### setContentType(String value) {#setContentType-java.lang.String-}  
```
public final void setContentType(String value)
```

Renvoie ou définit le type de contenu d’une présentation. Lecture/écriture String.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}  
```
public final String getHyperlinkBase()
```

Renvoie ou définit la propriété de document HyperlinkBase. Lecture/écriture String.

**Renvoie:**  
java.lang.String  
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}  
```
public final void setHyperlinkBase(String value)
```

Renvoie ou définit la propriété de document HyperlinkBase. Lecture/écriture String.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}  
```
public final int getCountOfCustomProperties()
```

Renvoie le nombre de propriétés personnalisées réellement contenues dans une collection. Lecture seule int.

**Renvoie:**  
int  
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}  
```
public final String getCustomPropertyName(int index)
```

Renvoie le nom d’une propriété personnalisée à l’index spécifié.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L’index basé sur zéro d’une propriété personnalisée à obtenir. |

**Renvoie:**  
java.lang.String - Nom de la propriété personnalisée à l’index spécifié.  
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}  
```
public final boolean removeCustomProperty(String name)
```

Supprime une propriété personnalisée associée à un nom spécifié.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à supprimer. |

**Renvoie:**  
boolean - Retourne true si une propriété a été supprimée, false sinon.  
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}  
```
public final boolean containsCustomProperty(String name)
```

Vérifie la présence d’une propriété personnalisée avec un nom spécifié.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à vérifier. |

**Renvoie:**  
boolean - Retourne true si la propriété existe, false sinon.  
### get_Item(String name) {#get-Item-java.lang.String-}  
```
public final Object get_Item(String name)
```

Renvoie ou définit la propriété personnalisée associée à un nom spécifié. Lecture/écriture Object.

--------------------

La valeur peut être **int**, **float**, **String**, **boolean** ou **Date**.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Renvoie:**  
java.lang.Object  
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}  
```
public final void set_Item(String name, Object value)
```

Renvoie ou définit la propriété personnalisée associée à un nom spécifié. Lecture/écriture Object.

--------------------

La valeur peut être **int**, **float**, **String**, **boolean** ou **Date**.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}  
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

Obtient une valeur booléenne nommée à partir des propriétés personnalisées.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à obtenir |
| value | boolean[] | Valeur de la propriété personnalisée |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}  
```
public final void getCustomPropertyValue(String name, int[] value)
```

Obtient une valeur entière nommée à partir des propriétés personnalisées.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à obtenir |
| value | int[] | Valeur de la propriété personnalisée |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}  
```
public final void getCustomPropertyValue(String name, Date[] value)
```

Obtient une valeur DateTime nommée à partir des propriétés personnalisées.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à obtenir |
| value | java.util.Date[] | Valeur de la propriété personnalisée |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}  
```
public final void getCustomPropertyValue(String name, String[] value)
```

Obtient une valeur chaîne nommée à partir des propriétés personnalisées.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à obtenir |
| value | java.lang.String[] | Valeur de la propriété personnalisée |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}  
```
public final void getCustomPropertyValue(String name, float[] value)
```

Obtient une valeur flottante nommée à partir des propriétés personnalisées.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à obtenir |
| value | float[] | Valeur de la propriété personnalisée |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}  
```
public final void getCustomPropertyValue(String name, double[] value)
```

Obtient une valeur double nommée à partir des propriétés personnalisées.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à obtenir. |
| value | double[] | Valeur de la propriété personnalisée |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}  
```
public final void setCustomPropertyValue(String name, boolean value)
```

Définit une propriété personnalisée booléenne nommée.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à définir |
| value | boolean | Valeur de la propriété personnalisée |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}  
```
public final void setCustomPropertyValue(String name, int value)
```

Définit une propriété personnalisée entière nommée.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à définir |
| value | int | Valeur de la propriété personnalisée |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}  
```
public final void setCustomPropertyValue(String name, Date value)
```

Définit une propriété personnalisée DateTime nommée.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à définir |
| value | java.util.Date | Valeur de la propriété personnalisée |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}  
```
public final void setCustomPropertyValue(String name, String value)
```

Définit une propriété personnalisée chaîne nommée.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à définir |
| value | java.lang.String | Valeur de la propriété personnalisée |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}  
```
public final void setCustomPropertyValue(String name, float value)
```

Définit une propriété personnalisée flottante nommée.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à définir |
| value | float | Valeur de la propriété personnalisée |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}  
```
public final void setCustomPropertyValue(String name, double value)
```

Définit une propriété personnalisée double nommée.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à définir |
| value | double | Valeur de la propriété personnalisée |

### clearCustomProperties() {#clearCustomProperties--}  
```
public final void clearCustomProperties()
```

Supprime toutes les propriétés personnalisées.

### getSensitivityLabels() {#getSensitivityLabels--}  
```
public final ISensitivityLabel[] getSensitivityLabels()
```

Obtient un tableau d’étiquettes de sensibilité à partir des propriétés de document personnalisées (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Obtenir les étiquettes de sensibilité à partir des propriétés personnalisées du document
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Ajouter le label à la collection
>          // Ici, vous pouvez ajouter une vérification de la validité des informations du label (le label est disponible, etc.)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie:**  
com.aspose.slides.ISensitivityLabel[]  
### clearBuiltInProperties() {#clearBuiltInProperties--}  
```
public final void clearBuiltInProperties()
```

Efface et définit les valeurs par défaut pour toutes les propriétés intégrées.

### getScaleCrop() {#getScaleCrop--}  
```
public final boolean getScaleCrop()
```

Indique le mode d’affichage de la miniature du document. Définissez cet élément sur **true** pour activer le redimensionnement de la miniature du document à l’affichage. Définissez cet élément sur **false** pour activer le recadrage de la miniature du document afin de n’afficher que les sections qui correspondent à l’affichage. Lecture/écriture boolean.

**Renvoie:**  
boolean  
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}  
```
public final void setScaleCrop(boolean value)
```

Indique le mode d’affichage de la miniature du document. Définissez cet élément sur **true** pour activer le redimensionnement de la miniature du document à l’affichage. Définissez cet élément sur **false** pour activer le recadrage de la miniature du document afin de n’afficher que les sections qui correspondent à l’affichage. Lecture/écriture boolean.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}  
```
public final boolean getLinksUpToDate()
```

Indique si les hyperliens dans un document sont à jour. Définissez cet élément sur **true** pour indiquer que les hyperliens sont mis à jour. Définissez cet élément sur **false** pour indiquer que les hyperliens sont obsolètes. Lecture/écriture boolean.

**Renvoie:**  
boolean  
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}  
```
public final void setLinksUpToDate(boolean value)
```
Indique si les hyperliens d’un document sont à jour. Définissez cet élément sur **true** pour indiquer que les hyperliens sont mis à jour. Définissez cet élément sur **false** pour indiquer que les hyperliens sont obsolètes. Lecture/écriture booléen.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Spécifie qu’un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. Le producteur suivant qui ouvrira ce document mettra à jour les relations d’hyperliens avec les nouveaux hyperliens spécifiés dans cette partie. Lecture/écriture booléen.

**Renvoie:**
boolean

### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Spécifie qu’un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. Le producteur suivant qui ouvrira ce document mettra à jour les relations d’hyperliens avec les nouveaux hyperliens spécifiés dans cette partie. Lecture/écriture booléen.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

Renvoie le nombre total de diapositives dans un document de présentation. Lecture seule int.

**Renvoie:**
int

### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Renvoie le nombre de diapositives masquées dans un document de présentation. Lecture seule int.

**Renvoie:**
int

### getNotes() {#getNotes--}
```
public final int getNotes()
```

Renvoie le nombre de diapositives d’une présentation contenant des notes. Lecture seule int.

**Renvoie:**
int

### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

Renvoie le nombre total de paragraphes trouvés dans un document, le cas échéant. Lecture seule int.

**Renvoie:**
int

### getWords() {#getWords--}
```
public final int getWords()
```

Renvoie le nombre total de mots contenus dans un document. Lecture seule int.

**Renvoie:**
int

### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Renvoie le nombre total de clips sonores ou vidéo présents dans le document. Lecture seule int.

**Renvoie:**
int

### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Spécifie le titre de chaque partie du document. Ces parties ne sont pas des parties du document mais des représentations conceptuelles des sections du document. Lecture seule String[].

**Renvoie:**
java.lang.String[]

### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

Indique le regroupement des parties du document et le nombre de parties dans chaque groupe. Lecture seule IHeadingPair[].

**Renvoie:**
com.aspose.slides.IHeadingPair[]

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Clone l’objet actuel

**Renvoie:**
java.lang.Object - Clone

### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Clone l’objet actuel

**Renvoie:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone