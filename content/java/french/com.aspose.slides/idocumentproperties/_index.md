---
title: IDocumentProperties
second_title: Référence API Aspose.Slides pour Java
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
| [getCompany()](#getCompany--) | Renvoie ou définit la propriété company. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Renvoie ou définit la propriété company. |
| [getManager()](#getManager--) | Renvoie ou définit la propriété manager. |
| [setManager(String value)](#setManager-java.lang.String-) | Renvoie ou définit la propriété manager. |
| [getPresentationFormat()](#getPresentationFormat--) | Renvoie ou définit le format prévu d'une présentation. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Renvoie ou définit le format prévu d'une présentation. |
| [getSharedDoc()](#getSharedDoc--) | Détermine si la présentation est partagée entre plusieurs personnes. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Détermine si la présentation est partagée entre plusieurs personnes. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Renvoie ou définit le modèle d'une application. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Renvoie ou définit le modèle d'une application. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Durée totale d'édition d'une présentation. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Durée totale d'édition d'une présentation. |
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
| [getLastPrinted()](#getLastPrinted--) | Renvoie la date à laquelle une présentation a été imprimée la dernière fois. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Renvoie la date à laquelle une présentation a été imprimée la dernière fois. |
| [getLastSavedBy()](#getLastSavedBy--) | Renvoie ou définit le nom de la dernière personne qui a modifié une présentation. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Renvoie ou définit le nom de la dernière personne qui a modifié une présentation. |
| [getRevisionNumber()](#getRevisionNumber--) | Renvoie ou définit le numéro de révision de la présentation. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Renvoie ou définit le numéro de révision de la présentation. |
| [getContentStatus()](#getContentStatus--) | Renvoie ou définit le statut du contenu d'une présentation. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Renvoie ou définit le statut du contenu d'une présentation. |
| [getContentType()](#getContentType--) | Renvoie ou définit le type de contenu d'une présentation. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Renvoie ou définit le type de contenu d'une présentation. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Renvoie ou définit la propriété de document HyperlinkBase. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Renvoie ou définit la propriété de document HyperlinkBase. |
| [getScaleCrop()](#getScaleCrop--) | Indique le mode d'affichage de la vignette du document. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Indique le mode d'affichage de la vignette du document. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Indique si les hyperliens dans un document sont à jour. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Indique si les hyperliens dans un document sont à jour. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Spécifie qu'un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Spécifie qu'un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. |
| [getSlides()](#getSlides--) | Spécifie le nombre total de diapositives dans un document de présentation. |
| [getHiddenSlides()](#getHiddenSlides--) | Spécifie le nombre de diapositives masquées dans un document de présentation. |
| [getNotes()](#getNotes--) | Spécifie le nombre de diapositives d'une présentation contenant des notes. |
| [getParagraphs()](#getParagraphs--) | Spécifie le nombre total de paragraphes trouvés dans un document, le cas échéant. |
| [getWords()](#getWords--) | Spécifie le nombre total de mots contenus dans un document. |
| [getMultimediaClips()](#getMultimediaClips--) | Spécifie le nombre total de clips audio ou vidéo présents dans le document. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Spécifie le titre de chaque partie du document. |
| [getHeadingPairs()](#getHeadingPairs--) | Indique le regroupement des parties du document et le nombre de parties dans chaque groupe. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Renvoie le nombre de propriétés personnalisées réellement contenues dans une collection. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Renvoie le nom d'une propriété personnalisée à l'indice spécifié. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Supprime une propriété personnalisée associée à un nom spécifié. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Vérifie la présence d'une propriété personnalisée avec un nom spécifié. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Renvoie ou définit la propriété personnalisée associée à un nom spécifié. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Renvoie ou définit la propriété personnalisée associée à un nom spécifié. |
| [clearCustomProperties()](#clearCustomProperties--) | Supprime toutes les propriétés personnalisées. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Efface et définit les valeurs par défaut pour toutes les propriétés builtIn. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Obtient une valeur booléenne nommée à partir des propriétés personnalisées. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Obtient une valeur entière nommée à partir des propriétés personnalisées. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Obtient une valeur DateTime nommée à partir des propriétés personnalisées. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Obtient une valeur chaîne nommée à partir des propriétés personnalisées. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Obtient une valeur flottante nommée à partir des propriétés personnalisées. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Obtient une valeur double nommée à partir des propriétés personnalisées. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Définit une propriété personnalisée booléenne nommée. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Définit une propriété personnalisée entière nommée. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Définit une propriété personnalisée DateTime nommée. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Définit une propriété personnalisée chaîne nommée. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Définit une propriété personnalisée flottante nommée. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Définit une propriété personnalisée double nommée. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Obtient un tableau d'étiquettes de sensibilité à partir des propriétés personnalisées du document (Métadonnées du SDK Microsoft Information Protection). |
### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

Renvoie la version de l'application. Lecture seule String.

--------------------

Le contenu de cet élément doit être sous la forme XX.YYYY, où X et Y représentent des valeurs numériques ; sinon, le document sera considéré comme non conforme. Aspose.Slides représente sa version au format XX.YY.ZZ, où : XX - version majeure YY - version mineure ZZ - version correctif. Par exemple, la valeur 23.0105 signifie la version 23.1.5 d’Aspose.Slides.

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

Renvoie ou définit la propriété company. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

Renvoie ou définit la propriété company. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getManager() {#getManager--}
```
public abstract String getManager()
```

Renvoie ou définit la propriété manager. Lecture/écriture String.

**Renvoie :**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

Renvoie ou définit la propriété manager. Lecture/écriture String.

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

Durée totale d'édition d'une présentation. Lecture/écriture double.

**Renvoie :**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

Durée totale d'édition d'une présentation. Lecture/écriture double.

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


**Renvoie :**
java.util.Date

Renvoie la date à laquelle une présentation a été créée. Les valeurs sont en UTC. Lecture/écriture java.util.Date.

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

Renvoie la date à laquelle une présentation a été créée. Les valeurs sont en UTC. Lecture/écriture java.util.Date.

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```


**Renvoie :**
java.util.Date

Renvoie la date à laquelle une présentation a été modifiée pour la dernière fois. Les valeurs sont en UTC. Lecture seule dans le cas de Presentation.DocumentProperties (car il sera mis à jour en interne pendant le processus d'enregistrement de l'objet IPresentation). Peut être modifié via l'instance DocumentProperties retournée par la méthode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Veuillez consulter l'exemple dans le résumé de la méthode [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

Renvoie la date à laquelle une présentation a été modifiée pour la dernière fois. Les valeurs sont en UTC. Lecture seule dans le cas de Presentation.DocumentProperties (car il sera mis à jour en interne pendant le processus d'enregistrement de l'objet IPresentation). Peut être modifié via l'instance DocumentProperties retournée par la méthode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Veuillez consulter l'exemple dans le résumé de la méthode [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```


**Renvoie :**
java.util.Date

Renvoie la date à laquelle une présentation a été imprimée pour la dernière fois. Lecture/écriture java.util.Date.

### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

Renvoie la date à laquelle une présentation a été imprimée pour la dernière fois. Lecture/écriture java.util.Date.

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```


**Renvoie :**
java.lang.String

Renvoie ou définit le nom de la dernière personne ayant modifié une présentation. Lecture/écriture String.

### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

Renvoie ou définit le nom de la dernière personne ayant modifié une présentation. Lecture/écriture String.

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```


**Renvoie :**
int

Renvoie ou définit le numéro de révision de la présentation. Lecture/écriture int.

### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

Renvoie ou définit le numéro de révision de la présentation. Lecture/écriture int.

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```


**Renvoie :**
java.lang.String

Renvoie ou définit l'état du contenu d'une présentation. Lecture/écriture String.

### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

Renvoie ou définit l'état du contenu d'une présentation. Lecture/écriture String.

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


**Renvoie :**
java.lang.String

Renvoie ou définit le type de contenu d'une présentation. Lecture/écriture String.

### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

Renvoie ou définit le type de contenu d'une présentation. Lecture/écriture String.

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```


**Renvoie :**
java.lang.String

Renvoie ou définit la propriété de document HyperlinkBase. Lecture/écriture String.

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

Renvoie ou définit la propriété de document HyperlinkBase. Lecture/écriture String.

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```


**Renvoie :**
boolean

Indique le mode d'affichage de la vignette du document. Définissez cet élément sur **true** pour activer le redimensionnement de la vignette du document à l'affichage. Définissez cet élément sur **false** pour activer le recadrage de la vignette du document afin de n'afficher que les sections qui s'adaptent à l'affichage. Lecture/écriture boolean.

### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

Indique le mode d'affichage de la vignette du document. Définissez cet élément sur **true** pour activer le redimensionnement de la vignette du document à l'affichage. Définissez cet élément sur **false** pour activer le recadrage de la vignette du document afin de n'afficher que les sections qui s'adaptent à l'affichage. Lecture/écriture boolean.

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```


**Renvoie :**
boolean

Indique si les hyperliens dans un document sont à jour. Définissez cet élément sur **true** pour indiquer que les hyperliens sont mis à jour. Définissez cet élément sur **false** pour indiquer que les hyperliens sont obsolètes. Lecture/écriture boolean.

### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

Indique si les hyperliens dans un document sont à jour. Définissez cet élément sur **true** pour indiquer que les hyperliens sont mis à jour. Définissez cet élément sur **false** pour indiquer que les hyperliens sont obsolètes. Lecture/écriture boolean.

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```


**Renvoie :**
boolean

Spécifie qu'un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. Le producteur suivant qui ouvrira ce document devra mettre à jour les relations d'hyperliens avec les nouveaux hyperliens spécifiés dans cette partie. Lecture/écriture boolean.

### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

Spécifie qu'un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. Le producteur suivant qui ouvrira ce document devra mettre à jour les relations d'hyperliens avec les nouveaux hyperliens spécifiés dans cette partie. Lecture/écriture boolean.

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```


**Renvoie :**
int

Spécifie le nombre total de diapositives dans un document de présentation. Lecture seule int.

### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```


**Renvoie :**
int

Spécifie le nombre de diapositives masquées dans un document de présentation. Lecture seule int.

### getNotes() {#getNotes--}
```
public abstract int getNotes()
```


**Renvoie :**
int

Spécifie le nombre de diapositives d'une présentation contenant des notes. Lecture seule int.

### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```


**Renvoie :**
int

Spécifie le nombre total de paragraphes trouvés dans un document, le cas échéant. Lecture seule int.

### getWords() {#getWords--}
```
public abstract int getWords()
```


**Renvoie :**
int

Spécifie le nombre total de mots contenus dans un document. Lecture seule int.

### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```


**Renvoie :**
int

Spécifie le nombre total de clips audio ou vidéo présents dans le document. Lecture seule int.

### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```


**Renvoie :**
java.lang.String[]

Spécifie le titre de chaque partie du document. Ces parties ne sont pas des parties de document mais des représentations conceptuelles de sections du document. Lecture seule String[].

### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```


**Renvoie :**
com.aspose.slides.IHeadingPair[]

Indique le regroupement des parties du document et le nombre de parties dans chaque groupe. Lecture seule IHeadingPair[].

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```


**Renvoie :**
int

Renvoie le nombre de propriétés personnalisées réellement contenues dans une collection. Lecture seule int.

### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```


Renvoie le nom d'une propriété personnalisée à l'index spécifié.

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


Efface et définit les valeurs par défaut pour toutes les propriétés builtIn.

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```


Récupère une valeur booléenne nommée à partir des propriétés personnalisées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à obtenir |
| value | boolean[] | Valeur de la propriété personnalisée |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```


Récupère une valeur entière nommée à partir des propriétés personnalisées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à obtenir |
| value | int[] | Valeur de la propriété personnalisée |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```


Récupère une valeur DateTime nommée à partir des propriétés personnalisées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à obtenir |
| value | java.util.Date[] | Valeur de la propriété personnalisée |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```


Récupère une valeur de chaîne nommée à partir des propriétés personnalisées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à obtenir |
| value | java.lang.String[] | Valeur de la propriété personnalisée |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```


Récupère une valeur flottante nommée à partir des propriétés personnalisées.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à obtenir |
| value | float[] | Valeur de la propriété personnalisée |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```


Récupère une valeur double nommée à partir des propriétés personnalisées.
| name | java.lang.String | Nom de la propriété personnalisée à obtenir. |
| value | double[] | Valeur de la propriété personnalisée |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

Définit une propriété personnalisée booléenne nommée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à définir |
| value | boolean | Valeur de la propriété personnalisée |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

Définit une propriété personnalisée entière nommée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à définir |
| value | int | Valeur de la propriété personnalisée |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

Définit une propriété personnalisée DateTime nommée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à définir |
| value | java.util.Date | Valeur de la propriété personnalisée |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

Définit une propriété personnalisée chaîne de caractères nommée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à définir |
| value | java.lang.String | Valeur de la propriété personnalisée |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

Définit une propriété personnalisée à virgule flottante nommée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à définir |
| value | float | Valeur de la propriété personnalisée |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

Définit une propriété personnalisée double précision nommée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Nom de la propriété personnalisée à définir |
| value | double | Valeur de la propriété personnalisée |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

Récupère un tableau d'étiquettes de sensibilité à partir des propriétés personnalisées du document (Métadonnées du SDK Microsoft Information Protection).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Obtenir les étiquettes de sensibilité à partir des propriétés de document personnalisées
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Ajouter l'étiquette à la collection
>          // Ici vous pouvez ajouter une vérification de la validité des informations d'étiquette (l'étiquette est disponible, etc)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**
com.aspose.slides.ISensitivityLabel[]