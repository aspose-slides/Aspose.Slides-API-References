---
title: IDocumentProperties
second_title: Aspose.Slides for Android via Java API Reference
description: Représente les propriétés d'une présentation.
type: docs
url: /fr/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

Représente les propriétés d'une présentation.
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
| [getLastSavedTime()](#getLastSavedTime--) | Renvoie la date de la dernière modification d'une présentation. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Renvoie la date de la dernière modification d'une présentation. |
| [getLastPrinted()](#getLastPrinted--) | Renvoie la date de la dernière impression d'une présentation. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Renvoie la date de la dernière impression d'une présentation. |
| [getLastSavedBy()](#getLastSavedBy--) | Renvoie ou définit le nom de la dernière personne ayant modifié une présentation. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Renvoie ou définit le nom de la dernière personne ayant modifié une présentation. |
| [getRevisionNumber()](#getRevisionNumber--) | Renvoie ou définit le numéro de révision de la présentation. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Renvoie ou définit le numéro de révision de la présentation. |
| [getContentStatus()](#getContentStatus--) | Renvoie ou définit le statut de contenu d'une présentation. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Renvoie ou définit le statut de contenu d'une présentation. |
| [getContentType()](#getContentType--) | Renvoie ou définit le type de contenu d'une présentation. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Renvoie ou définit le type de contenu d'une présentation. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Renvoie ou définit la propriété de document HyperlinkBase. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Renvoie ou définit la propriété de document HyperlinkBase. |
| [getScaleCrop()](#getScaleCrop--) | Indique le mode d'affichage de la vignette du document. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Indique le mode d'affichage de la vignette du document. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Indique si les hyperliens d'un document sont à jour. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Indique si les hyperliens d'un document sont à jour. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Spécifie qu'un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Spécifie qu'un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. |
| [getSlides()](#getSlides--) | Spécifie le nombre total de diapositives dans un document de présentation. |
| [getHiddenSlides()](#getHiddenSlides--) | Spécifie le nombre de diapositives masquées dans un document de présentation. |
| [getNotes()](#getNotes--) | Spécifie le nombre de diapositives contenant des notes dans une présentation. |
| [getParagraphs()](#getParagraphs--) | Spécifie le nombre total de paragraphes trouvés dans un document le cas échéant. |
| [getWords()](#getWords--) | Spécifie le nombre total de mots contenus dans un document. |
| [getMultimediaClips()](#getMultimediaClips--) | Spécifie le nombre total de clips sonores ou vidéo présents dans le document. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Spécifie le titre de chaque partie du document. |
| [getHeadingPairs()](#getHeadingPairs--) | Indique le regroupement des parties du document et le nombre de parties dans chaque groupe. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Renvoie le nombre de propriétés personnalisées effectivement contenues dans une collection. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Renvoie le nom d'une propriété personnalisée à l'index spécifié. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Supprime une propriété personnalisée associée à un nom spécifié. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Vérifie la présence d'une propriété personnalisée avec un nom spécifié. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Renvoie ou définit la propriété personnalisée associée à un nom spécifié. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Renvoie ou définit la propriété personnalisée associée à un nom spécifié. |
| [clearCustomProperties()](#clearCustomProperties--) | Supprime toutes les propriétés personnalisées. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Efface et définit les valeurs par défaut pour toutes les propriétés intégrées. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Obtient une valeur booléenne nommée à partir des propriétés personnalisées. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Obtient une valeur entière nommée à partir des propriétés personnalisées. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Obtient une valeur DateTime nommée à partir des propriétés personnalisées. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Obtient une valeur chaîne nommée à partir des propriétés personnalisées. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Obtient une valeur float nommée à partir des propriétés personnalisées. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Obtient une valeur double nommée à partir des propriétés personnalisées. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Définit une propriété booléenne personnalisée nommée. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Définit une propriété entière personnalisée nommée. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Définit une propriété DateTime personnalisée nommée. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Définit une propriété chaîne personnalisée nommée. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Définit une propriété float personnalisée nommée. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Définit une propriété double personnalisée nommée. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Obtient un tableau d'étiquettes de sensibilité à partir des propriétés personnalisées du document (Microsoft Information Protection SDK Metadata). |
### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

Renvoie la version de l'application. Lecture seule String.

--------------------

Le contenu de cet élément doit être sous la forme XX.YYYY, où X et Y représentent des valeurs numériques ; sinon, le document sera considéré comme non conforme. Aspose.Slides représente sa version au format XX.YY.ZZ, où : XX - version majeure ; YY - version mineure ; ZZ - version du correctif. Par exemple, la valeur 23.0105 signifie la version Aspose.Slides 23.1.5.

**Renvoie :**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

Renvoie ou définit le nom de l'application. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

Renvoie ou définit le nom de l'application. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

Renvoie ou définit la propriété de l'entreprise. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

Renvoie ou définit la propriété de l'entreprise. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```

Renvoie ou définit la propriété du responsable. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

Renvoie ou définit la propriété du responsable. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

Renvoie ou définit le format prévu d'une présentation. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

Renvoie ou définit le format prévu d'une présentation. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

Détermine si la présentation est partagée entre plusieurs personnes. Lecture/écriture boolean.

**Renvoie :**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

Détermine si la présentation est partagée entre plusieurs personnes. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

Renvoie ou définit le modèle d'une application. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

Renvoie ou définit le modèle d'une application. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

Temps total d'édition d'une présentation. Lecture/écriture double.

**Renvoie :**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

Temps total d'édition d'une présentation. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

Renvoie ou définit le titre d'une présentation. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

Renvoie ou définit le titre d'une présentation. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

Renvoie ou définit le sujet d'une présentation. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

Renvoie ou définit le sujet d'une présentation. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

Renvoie ou définit l'auteur d'une présentation. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

Renvoie ou définit l'auteur d'une présentation. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

Renvoie ou définit les mots-clés d'une présentation. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

Renvoie ou définit les mots-clés d'une présentation. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

Renvoie ou définit les commentaires d'une présentation. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

Renvoie ou définit les commentaires d'une présentation. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

Renvoie ou définit la catégorie d'une présentation. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

Renvoie ou définit la catégorie d'une présentation. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Renvoie la date de création d'une présentation. Les valeurs sont en UTC. Lecture/écriture java.util.Date.

**Renvoie :**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Renvoie la date de création d'une présentation. Les valeurs sont en UTC. Lecture/écriture java.util.Date.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

Renvoie la date de la dernière modification d'une présentation. Les valeurs sont en UTC. Lecture seule dans le cas de Presentation.DocumentProperties (car elle est mise à jour en interne pendant le processus d'enregistrement de l'objet IPresentation). Peut être modifiée via l'instance DocumentProperties retournée par la méthode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Voir l'exemple dans le résumé de la méthode [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Renvoie :**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

Renvoie la date de la dernière modification d'une présentation. Les valeurs sont en UTC. Lecture seule dans le cas de Presentation.DocumentProperties (car elle est mise à jour en interne pendant le processus d'enregistrement de l'objet IPresentation). Peut être modifiée via l'instance DocumentProperties retournée par la méthode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Voir l'exemple dans le résumé de la méthode [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

Renvoie la date de la dernière impression d'une présentation. Lecture/écriture java.util.Date.

**Renvoie :**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

Renvoie la date de la dernière impression d'une présentation. Lecture/écriture java.util.Date.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

Renvoie ou définit le nom de la dernière personne ayant modifié une présentation. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

Renvoie ou définit le nom de la dernière personne ayant modifié une présentation. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

Renvoie ou définit le numéro de révision de la présentation. Lecture/écriture int.

**Renvoie :**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

Renvoie ou définit le numéro de révision de la présentation. Lecture/écriture int.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

Renvoie ou définit le statut de contenu d'une présentation. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

Renvoie ou définit le statut de contenu d'une présentation. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Renvoie ou définit le type de contenu d'une présentation. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

Renvoie ou définit le type de contenu d'une présentation. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

Renvoie ou définit la propriété de document HyperlinkBase. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

Renvoie ou définit la propriété de document HyperlinkBase. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

Indique le mode d'affichage de la vignette du document. Définit cet élément à **true** pour activer le redimensionnement de la vignette du document à l'affichage. Définit cet élément à **false** pour activer le recadrage de la vignette du document afin d'afficher uniquement les sections qui s'adaptent à l'affichage. Lecture/écriture boolean.

**Renvoie :**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

Indique le mode d'affichage de la vignette du document. Définit cet élément à **true** pour activer le redimensionnement de la vignette du document à l'affichage. Définit cet élément à **false** pour activer le recadrage de la vignette du document afin d'afficher uniquement les sections qui s'adaptent à l'affichage. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

Indique si les hyperliens d'un document sont à jour. Définit cet élément à **true** pour indiquer que les hyperliens sont mis à jour. Définit cet élément à **false** pour indiquer que les hyperliens sont obsolètes. Lecture/écriture boolean.

**Renvoie :**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

Indique si les hyperliens d'un document sont à jour. Définit cet élément à **true** pour indiquer que les hyperliens sont mis à jour. Définit cet élément à **false** pour indiquer que les hyperliens sont obsolètes. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

Spécifie qu'un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. Le prochain producteur ouvrant ce document devra mettre à jour les relations d'hyperliens avec les nouveaux hyperliens spécifiés dans cette partie. Lecture/écriture boolean.

**Renvoie :**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

Spécifie qu'un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. Le prochain producteur ouvrant ce document devra mettre à jour les relations d'hyperliens avec les nouveaux hyperliens spécifiés dans cette partie. Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

Spécifie le nombre total de diapositives dans un document de présentation. Lecture seule int.

**Renvoie :**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

Spécifie le nombre de diapositives masquées dans un document de présentation. Lecture seule int.

**Renvoie :**
int
### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

Spécifie le nombre de diapositives contenant des notes dans une présentation. Lecture seule int.

**Renvoie :**
int
### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

Spécifie le nombre total de paragraphes trouvés dans un document le cas échéant. Lecture seule int.

**Renvoie :**
int
### getWords() {#getWords--}
```
public abstract int getWords()
```

Spécifie le nombre total de mots contenus dans un document. Lecture seule int.

**Renvoie :**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

Spécifie le nombre total de clips sonores ou vidéo présents dans le document. Lecture seule int.

**Renvoie :**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

Spécifie le titre de chaque partie du document. Ces parties ne sont pas des parties de document mais des représentations conceptuelles de sections du document. Lecture seule String[].

**Renvoie :**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

Indique le regroupement des parties du document et le nombre de parties dans chaque groupe. Lecture seule IHeadingPair[].

**Renvoie :**
com.aspose.slides.IHeadingPair[]
### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

Renvoie le nombre de propriétés personnalisées réellement contenues dans une collection. Lecture seule int.

**Renvoie :**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

Renvoie un nom de propriété personnalisée à l'index spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index basé sur zéro d'une propriété personnalisée à obtenir. |

**Renvoie :**
java.lang.String - Nom de la propriété personnalisée à l'index spécifié.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

Supprime une propriété personnalisée associée à un nom spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à supprimer. |

**Renvoie :**
boolean - Retourne true si une propriété a été supprimée, false sinon.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

Vérifie la présence d'une propriété personnalisée avec un nom spécifié.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à vérifier. |

**Renvoie :**
boolean - Retourne true si la propriété existe, false sinon.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

Renvoie ou définit la propriété personnalisée associée à un nom spécifié. Lecture/écriture Object.

--------------------

La valeur peut être **int**, **float**, **double**, **String**, **boolean** ou **Date**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Renvoie :**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

Renvoie ou définit la propriété personnalisée associée à un nom spécifié. Lecture/écriture Object.

--------------------

La valeur peut être **int**, **float**, **double**, **String**, **boolean** ou **Date**.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

Supprime toutes les propriétés personnalisées.

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

Efface et définit les valeurs par défaut pour toutes les propriétés intégrées.

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

Obtient une valeur booléenne nommée à partir des propriétés personnalisées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à obtenir |
| value | boolean[] | Valeur de la propriété personnalisée |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

Obtient une valeur entière nommée à partir des propriétés personnalisées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à obtenir |
| value | int[] | Valeur de la propriété personnalisée |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

Obtient une valeur DateTime nommée à partir des propriétés personnalisées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à obtenir |
| value | java.util.Date[] | Valeur de la propriété personnalisée |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

Obtient une valeur chaîne nommée à partir des propriétés personnalisées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à obtenir |
| value | java.lang.String[] | Valeur de la propriété personnalisée |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

Obtient une valeur float nommée à partir des propriétés personnalisées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à obtenir |
| value | float[] | Valeur de la propriété personnalisée |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

Obtient une valeur double nommée à partir des propriétés personnalisées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à obtenir. |
| value | double[] | Valeur de la propriété personnalisée |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

Définit une propriété booléenne personnalisée nommée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à définir |
| value | boolean | Valeur de la propriété personnalisée |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

Définit une propriété entière personnalisée nommée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à définir |
| value | int | Valeur de la propriété personnalisée |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

Définit une propriété DateTime personnalisée nommée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à définir |
| value | java.util.Date | Valeur de la propriété personnalisée |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

Définit une propriété chaîne personnalisée nommée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à définir |
| value | java.lang.String | Valeur de la propriété personnalisée |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

Définit une propriété float personnalisée nommée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à définir |
| value | float | Valeur de la propriété personnalisée |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

Définit une propriété double personnalisée nommée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à définir |
| value | double | Valeur de la propriété personnalisée |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

Obtient un tableau d'étiquettes de sensibilité à partir des propriétés personnalisées du document (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Get sensitivity labels from the custom document properties
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Add label to the collection
>          // Here you can add a check for the validity of the label information (the label is available, etc)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  ```

**Renvoie :**
com.aspose.slides.ISensitivityLabel[]