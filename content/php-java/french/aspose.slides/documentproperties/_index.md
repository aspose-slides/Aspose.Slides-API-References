---
title: DocumentProperties
second_title: Aspose.Sildes pour PHP via la référence de l'API Java
description: 
type: docs

url: /fr/aspose.slides/documentproperties/
---
## Classe DocumentProperties

 Représente les propriétés d’une présentation.

### DocumentProperties {#DocumentProperties}

| Nom | Description |
| --- | --- |
| DocumentProperties() | Initialise une nouvelle instance de la classe DocumentProperties. |

 **Retour:**  
DocumentProperties


---


### clearBuiltInProperties {#clearBuiltInProperties}

| Nom | Description |
| --- | --- |
| clearBuiltInProperties () | Efface et définit les valeurs par défaut pour toutes les propriétés builtIn. |

 **Retour:**  
void


---


### clearCustomProperties {#clearCustomProperties}

| Nom | Description |
| --- | --- |
| clearCustomProperties () | Supprime toutes les propriétés personnalisées. |

 **Retour:**  
void


---


### cloneT {#cloneT}

| Nom | Description |
| --- | --- |
| cloneT () | Clone l’objet actuel |

 **Retour:**  
[DocumentProperties](../documentproperties)


---


### containsCustomProperty {#containsCustomProperty}

| Nom | Description |
| --- | --- |
| containsCustomProperty (String) | Vérifie la présence d’une propriété personnalisée avec un nom spécifié. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom d’une propriété personnalisée à vérifier. |

 **Retour:**  
boolean


---


### deepClone {#deepClone}

| Nom | Description |
| --- | --- |
| deepClone () | Clone l’objet actuel |

 **Retour:**  
Object


---


### getAppVersion {#getAppVersion}

| Nom | Description |
| --- | --- |
| getAppVersion () | Renvoie la version de l’application. Lecture seule String. |

 **Retour:**  
String


---


### getApplicationTemplate {#getApplicationTemplate}

| Nom | Description |
| --- | --- |
| getApplicationTemplate () | Renvoie ou définit le modèle d’une application. Lecture/écriture String. |

 **Retour:**  
String


---


### getAuthor {#getAuthor}

| Nom | Description |
| --- | --- |
| getAuthor () | Renvoie ou définit l’auteur d’une présentation. Lecture/écriture String. |

 **Retour:**  
String


---


### getCategory {#getCategory}

| Nom | Description |
| --- | --- |
| getCategory () | Renvoie ou définit la catégorie d’une présentation. Lecture/écriture String. |

 **Retour:**  
String


---


### getComments {#getComments}

| Nom | Description |
| --- | --- |
| getComments () | Renvoie ou définit les commentaires d’une présentation. Lecture/écriture String. |

 **Retour:**  
String


---


### getCompany {#getCompany}

| Nom | Description |
| --- | --- |
| getCompany () | Renvoie ou définit la propriété company. Lecture/écriture String. |

 **Retour:**  
String


---


### getContentStatus {#getContentStatus}

| Nom | Description |
| --- | --- |
| getContentStatus () | Renvoie ou définit le statut du contenu d’une présentation. Lecture/écriture String. |

 **Retour:**  
String


---


### getContentType {#getContentType}

| Nom | Description |
| --- | --- |
| getContentType () | Renvoie ou définit le type de contenu d’une présentation. Lecture/écriture String. |

 **Retour:**  
String


---


### getCountOfCustomProperties {#getCountOfCustomProperties}

| Nom | Description |
| --- | --- |
| getCountOfCustomProperties () | Renvoie le nombre de propriétés personnalisées réellement contenues dans une collection. Lecture seule int. |

 **Retour:**  
int


---


### getCreatedTime {#getCreatedTime}

| Nom | Description |
| --- | --- |
| getCreatedTime () | Renvoie la date à laquelle une présentation a été créée. Les valeurs sont en UTC. Lecture/écriture java.util.Date. |

 **Retour:**  
Date


---


### getCustomPropertyName {#getCustomPropertyName}

| Nom | Description |
| --- | --- |
| getCustomPropertyName (int) | Renvoie le nom d’une propriété personnalisée à l’indice spécifié. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| index | int | L’indice basé sur zéro de la propriété personnalisée à obtenir. |

 **Retour:**  
String

 **Exception**

| Erreur | Condition |
| --- | --- |
| ArgumentOutOfRangeException | L’indice est inférieur à zéro. L’indice est égal ou supérieur à Count. |


---


### getCustomPropertyValue {#getCustomPropertyValue}

| Nom | Description |
| --- | --- |
| getCustomPropertyValue (String, boolean[]) | Obtient une valeur booléenne nommée à partir des propriétés personnalisées. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom de la propriété personnalisée à obtenir |
| value | boolean[] | Valeur de la propriété personnalisée |

 **Retour:**  
void


---


### getCustomPropertyValue {#getCustomPropertyValue}

| Nom | Description |
| --- | --- |
| getCustomPropertyValue (String, int[]) | Obtient une valeur entière nommée à partir des propriétés personnalisées. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom de la propriété personnalisée à obtenir |
| value | int[] | Valeur de la propriété personnalisée |

 **Retour:**  
void


---


### getCustomPropertyValue {#getCustomPropertyValue}

| Nom | Description |
| --- | --- |
| getCustomPropertyValue (String, java.util.Date[]) | Obtient une valeur DateTime nommée à partir des propriétés personnalisées. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom de la propriété personnalisée à obtenir |
| value | java.util.Date[] | Valeur de la propriété personnalisée |

 **Retour:**  
void


---


### getCustomPropertyValue {#getCustomPropertyValue}

| Nom | Description |
| --- | --- |
| getCustomPropertyValue (String, java.lang.String[]) | Obtient une valeur chaîne nommée à partir des propriétés personnalisées. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom de la propriété personnalisée à obtenir |
| value | java.lang.String[] | Valeur de la propriété personnalisée |

 **Retour:**  
void


---


### getCustomPropertyValue {#getCustomPropertyValue}

| Nom | Description |
| --- | --- |
| getCustomPropertyValue (String, float[]) | Obtient une valeur flottante nommée à partir des propriétés personnalisées. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom de la propriété personnalisée à obtenir |
| value | float[] | Valeur de la propriété personnalisée |

 **Retour:**  
void


---


### getCustomPropertyValue {#getCustomPropertyValue}

| Nom | Description |
| --- | --- |
| getCustomPropertyValue (String, double[]) | Obtient une valeur double nommée à partir des propriétés personnalisées. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom de la propriété personnalisée à obtenir. |
| value | double[] | Valeur de la propriété personnalisée |

 **Retour:**  
void


---


### getHeadingPairs {#getHeadingPairs}

| Nom | Description |
| --- | --- |
| getHeadingPairs () | Indique le regroupement des parties du document et le nombre de parties dans chaque groupe. Lecture seule IHeadingPair[]. |

 **Retour:**  
[HeadingPair](../headingpair)


---


### getHiddenSlides {#getHiddenSlides}

| Nom | Description |
| --- | --- |
| getHiddenSlides () | Renvoie le nombre de diapositives masquées dans un document de présentation. Lecture seule int. |

 **Retour:**  
int


---


### getHyperlinkBase {#getHyperlinkBase}

| Nom | Description |
| --- | --- |
| getHyperlinkBase () | Renvoie ou définit la propriété HyperlinkBase du document. Lecture/écriture String. |

 **Retour:**  
String


---


### getHyperlinksChanged {#getHyperlinksChanged}

| Nom | Description |
| --- | --- |
| getHyperlinksChanged () | Indique qu’un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. Le producteur suivant qui ouvrira ce document devra mettre à jour les relations d’hyperliens avec les nouveaux hyperliens spécifiés dans cette partie. Lecture/écriture boolean. |

 **Retour:**  
boolean


---


### getKeywords {#getKeywords}

| Nom | Description |
| --- | --- |
| getKeywords () | Renvoie ou définit les mots-clé d’une présentation. Lecture/écriture String. |

 **Retour:**  
String


---


### getLastPrinted {#getLastPrinted}

| Nom | Description |
| --- | --- |
| getLastPrinted () | Renvoie la date à laquelle une présentation a été imprimée pour la dernière fois. Lecture/écriture java.util.Date. |

 **Retour:**  
Date


---


### getLastSavedBy {#getLastSavedBy}

| Nom | Description |
| --- | --- |
| getLastSavedBy () | Renvoie ou définit le nom de la dernière personne qui a modifié une présentation. Lecture/écriture String. |

 **Retour:**  
String


---


### getLastSavedTime {#getLastSavedTime}

| Nom | Description |
| --- | --- |
| getLastSavedTime () | Renvoie la date à laquelle une présentation a été modifiée pour la dernière fois. Les valeurs sont en UTC. Lecture seule dans le cas de Presentation.DocumentProperties (car il sera mis à jour en interne pendant le processus de sauvegarde de l’objet IPresentation). Peut être modifié via l’instance DocumentProperties retournée par la méthode IPresentationInfo#readDocumentProperties. Veuillez consulter l’exemple dans le résumé de la méthode IPresentationInfo#updateDocumentProperties(IDocumentProperties). |

 **Retour:**  
Date


---


### getLinksUpToDate {#getLinksUpToDate}

| Nom | Description |
| --- | --- |
| getLinksUpToDate () | Indique si les hyperliens d’un document sont à jour. définissez cet élément sur true pour indiquer que les hyperliens sont mis à jour. définissez cet élément sur false pour indiquer que les hyperliens sont obsolètes. Lecture/écriture boolean. |

 **Retour:**  
boolean


---


### getManager {#getManager}

| Nom | Description |
| --- | --- |
| getManager () | Renvoie ou définit la propriété manager. Lecture/écriture String. |

 **Retour:**  
String


---


### getMultimediaClips {#getMultimediaClips}

| Nom | Description |
| --- | --- |
| getMultimediaClips () | Renvoie le nombre total de clips audio ou vidéo présents dans le document. Lecture seule int. |

 **Retour:**  
int


---


### getNameOfApplication {#getNameOfApplication}

| Nom | Description |
| --- | --- |
| getNameOfApplication () | Renvoie ou définit le nom de l’application. Lecture/écriture String. |

 **Retour:**  
String


---


### getNotes {#getNotes}

| Nom | Description |
| --- | --- |
| getNotes () | Renvoie le nombre de diapositives d’une présentation contenant des notes. Lecture seule int. |

 **Retour:**  
int


---


### getParagraphs {#getParagraphs}

| Nom | Description |
| --- | --- |
| getParagraphs () | Renvoie le nombre total de paragraphes trouvés dans un document le cas échéant. Lecture seule int. |

 **Retour:**  
int


---


### getPresentationFormat {#getPresentationFormat}

| Nom | Description |
| --- | --- |
| getPresentationFormat () | Renvoie ou définit le format prévu d’une présentation. Lecture/écriture String. |

 **Retour:**  
String


---


### getRevisionNumber {#getRevisionNumber}

| Nom | Description |
| --- | --- |
| getRevisionNumber () | Renvoie ou définit le numéro de révision de la présentation. Lecture/écriture int. |

 **Retour:**  
int


---


### getScaleCrop {#getScaleCrop}

| Nom | Description |
| --- | --- |
| getScaleCrop () | Indique le mode d’affichage de la miniature du document. définissez cet élément sur true pour activer le redimensionnement de la miniature du document à l’affichage. définissez cet élément sur false pour activer le recadrage de la miniature du document afin d’afficher uniquement les sections qui s’adaptent à l’affichage. Lecture/écriture boolean. |

 **Retour:**  
boolean


---


### getSensitivityLabels {#getSensitivityLabels}

| Nom | Description |
| --- | --- |
| getSensitivityLabels () | Obtient un tableau d’étiquettes de sensibilité à partir des propriétés personnalisées du document (Microsoft Information Protection SDK Metadata). |

 **Retour:**  
[SensitivityLabel](../sensitivitylabel)


---


### getSharedDoc {#getSharedDoc}

| Nom | Description |
| --- | --- |
| getSharedDoc () | Détermine si la présentation est partagée entre plusieurs personnes. Lecture/écriture boolean. |

 **Retour:**  
boolean


---


### getSlides {#getSlides}

| Nom | Description |
| --- | --- |
| getSlides () | Renvoie le nombre total de diapositives dans un document de présentation. Lecture seule int. |

 **Retour:**  
int


---


### getSubject {#getSubject}

| Nom | Description |
| --- | --- |
| getSubject () | Renvoie ou définit le sujet d’une présentation. Lecture/écriture String. |

 **Retour:**  
String


---


### getTitle {#getTitle}

| Nom | Description |
| --- | --- |
| getTitle () | Renvoie ou définit le titre d’une présentation. Lecture/écriture String. |

 **Retour:**  
String


---


### getTitlesOfParts {#getTitlesOfParts}

| Nom | Description |
| --- | --- |
| getTitlesOfParts () | Spécifie le titre de chaque partie du document. Ces parties ne sont pas des parties de document mais des représentations conceptuelles des sections du document. Lecture seule String[]. |

 **Retour:**  
String


---


### getTotalEditingTime {#getTotalEditingTime}

| Nom | Description |
| --- | --- |
| getTotalEditingTime () | Durée totale d'édition d'une présentation. Lecture/écriture double. |

 **Retour:**  
double


---


### getWords {#getWords}

| Nom | Description |
| --- | --- |
| getWords () | Renvoie le nombre total de mots contenus dans un document. Lecture seule int. |

 **Retour:**  
int


---


### get_Item {#get_Item}

| Nom | Description |
| --- | --- |
| get_Item (String) | Renvoie ou définit la propriété personnalisée associée à un nom spécifié. Lecture/écriture Object. La valeur peut être int, float, String, boolean ou Date. |

 **Retour:**  
Object


---


### removeCustomProperty {#removeCustomProperty}

| Nom | Description |
| --- | --- |
| removeCustomProperty (String) | Supprime une propriété personnalisée associée à un nom spécifié. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom d'une propriété personnalisée à supprimer. |

 **Retour:**  
boolean


---


### setApplicationTemplate {#setApplicationTemplate}

| Nom | Description |
| --- | --- |
| setApplicationTemplate (String) | Renvoie ou définit le modèle d'une application. Lecture/écriture String. |

 **Retour:**  
void


---


### setAuthor {#setAuthor}

| Nom | Description |
| --- | --- |
| setAuthor (String) | Renvoie ou définit l'auteur d'une présentation. Lecture/écriture String. |

 **Retour:**  
void


---


### setCategory {#setCategory}

| Nom | Description |
| --- | --- |
| setCategory (String) | Renvoie ou définit la catégorie d'une présentation. Lecture/écriture String. |

 **Retour:**  
void


---


### setComments {#setComments}

| Nom | Description |
| --- | --- |
| setComments (String) | Renvoie ou définit les commentaires d'une présentation. Lecture/écriture String. |

 **Retour:**  
void


---


### setCompany {#setCompany}

| Nom | Description |
| --- | --- |
| setCompany (String) | Renvoie ou définit la propriété company. Lecture/écriture String. |

 **Retour:**  
void


---


### setContentStatus {#setContentStatus}

| Nom | Description |
| --- | --- |
| setContentStatus (String) | Renvoie ou définit le statut du contenu d'une présentation. Lecture/écriture String. |

 **Retour:**  
void


---


### setContentType {#setContentType}

| Nom | Description |
| --- | --- |
| setContentType (String) | Renvoie ou définit le type de contenu d'une présentation. Lecture/écriture String. |

 **Retour:**  
void


---


### setCreatedTime {#setCreatedTime}

| Nom | Description |
| --- | --- |
| setCreatedTime (Date) | Renvoie la date à laquelle une présentation a été créée. Les valeurs sont en UTC. Lecture/écriture java.util.Date. |

 **Retour:**  
void


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Nom | Description |
| --- | --- |
| setCustomPropertyValue (String, boolean) | Définit une propriété personnalisée booléenne nommée. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom de la propriété personnalisée à définir |
| value | boolean | Valeur de la propriété personnalisée |

 **Retour:**  
void


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Nom | Description |
| --- | --- |
| setCustomPropertyValue (String, int) | Définit une propriété personnalisée entière nommée. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom de la propriété personnalisée à définir |
| value | int | Valeur de la propriété personnalisée |

 **Retour:**  
void


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Nom | Description |
| --- | --- |
| setCustomPropertyValue (String, Date) | Définit une propriété personnalisée DateTime nommée. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom de la propriété personnalisée à définir |
| value | Date | Valeur de la propriété personnalisée |

 **Retour:**  
void


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Nom | Description |
| --- | --- |
| setCustomPropertyValue (String, String) | Définit une propriété personnalisée chaîne de caractères nommée. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom de la propriété personnalisée à définir |
| value | String | Valeur de la propriété personnalisée |

 **Retour:**  
void


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Nom | Description |
| --- | --- |
| setCustomPropertyValue (String, float) | Définit une propriété personnalisée flottante nommée. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom de la propriété personnalisée à définir |
| value | float | Valeur de la propriété personnalisée |

 **Retour:**  
void


---


### setCustomPropertyValue {#setCustomPropertyValue}

| Nom | Description |
| --- | --- |
| setCustomPropertyValue (String, double) | Définit une propriété personnalisée double nommée. |

 **Paramètres:**

| Nom | Type | Description |
| --- | --- | --- |
| name | String | Nom de la propriété personnalisée à définir |
| value | double | Valeur de la propriété personnalisée |

 **Retour:**  
void


---


### setHyperlinkBase {#setHyperlinkBase}

| Nom | Description |
| --- | --- |
| setHyperlinkBase (String) | Renvoie ou définit la propriété de document HyperlinkBase. Lecture/écriture String. |

 **Retour:**  
void


---


### setHyperlinksChanged {#setHyperlinksChanged}

| Nom | Description |
| --- | --- |
| setHyperlinksChanged (boolean) | Spécifie qu'un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. Le prochain producteur à ouvrir ce document doit mettre à jour les relations d'hyperliens avec les nouveaux hyperliens spécifiés dans cette partie. Lecture/écriture boolean. |

 **Retour:**  
void


---


### setKeywords {#setKeywords}

| Nom | Description |
| --- | --- |
| setKeywords (String) | Renvoie ou définit les mots-clés d'une présentation. Lecture/écriture String. |

 **Retour:**  
void


---


### setLastPrinted {#setLastPrinted}

| Nom | Description |
| --- | --- |
| setLastPrinted (Date) | Renvoie la date à laquelle une présentation a été imprimée pour la dernière fois. Lecture/écriture java.util.Date. |

 **Retour:**  
void


---


### setLastSavedBy {#setLastSavedBy}

| Nom | Description |
| --- | --- |
| setLastSavedBy (String) | Renvoie ou définit le nom de la dernière personne ayant modifié une présentation. Lecture/écriture String. |

 **Retour:**  
void


---


### setLastSavedTime {#setLastSavedTime}

| Nom | Description |
| --- | --- |
| setLastSavedTime (Date) | Renvoie la date à laquelle une présentation a été modifiée pour la dernière fois. Les valeurs sont en UTC. Lecture seule dans le cas de Presentation.DocumentProperties (car elle sera mise à jour en interne pendant le processus d'enregistrement de l'objet IPresentation). Peut être modifiée via l'instance DocumentProperties renvoyée par la méthode IPresentationInfo#readDocumentProperties. Veuillez consulter l'exemple dans le résumé de la méthode IPresentationInfo#updateDocumentProperties(IDocumentProperties). |

 **Retour:**  
void


---


### setLinksUpToDate {#setLinksUpToDate}

| Nom | Description |
| --- | --- |
| setLinksUpToDate (boolean) | Indique si les hyperliens dans un document sont à jour. Définissez cet élément sur true pour indiquer que les hyperliens sont mis à jour. Définissez cet élément sur false pour indiquer que les hyperliens sont obsolètes. Lecture/écriture boolean. |

 **Retour:**  
void


---


### setManager {#setManager}

| Nom | Description |
| --- | --- |
| setManager (String) | Renvoie ou définit la propriété manager. Lecture/écriture String. |

 **Retour:**  
void


---


### setNameOfApplication {#setNameOfApplication}

| Nom | Description |
| --- | --- |
| setNameOfApplication (String) | Renvoie ou définit le nom de l'application. Lecture/écriture String. |

 **Retour:**  
void


---


### setPresentationFormat {#setPresentationFormat}

| Nom | Description |
| --- | --- |
| setPresentationFormat (String) | Renvoie ou définit le format prévu d'une présentation. Lecture/écriture String. |

 **Retour:**  
void


---


### setRevisionNumber {#setRevisionNumber}

| Nom | Description |
| --- | --- |
| setRevisionNumber (int) | Renvoie ou définit le numéro de révision de la présentation. Lecture/écriture int. |

 **Retour:**  
void


---


### setScaleCrop {#setScaleCrop}

| Nom | Description |
| --- | --- |
| setScaleCrop (boolean) | Indique le mode d'affichage de la miniature du document. Définissez cet élément sur true pour activer le redimensionnement de la miniature du document à l'affichage. Définissez cet élément sur false pour activer le recadrage de la miniature du document afin de n'afficher que les sections correspondant à l'affichage. Lecture/écriture boolean. |

 **Retour:**  
void


---


### setSharedDoc {#setSharedDoc}

| Nom | Description |
| --- | --- |
| setSharedDoc (boolean) | Détermine si la présentation est partagée entre plusieurs personnes. Lecture/écriture boolean. |

 **Retour:**  
void


---


### setSubject {#setSubject}

| Nom | Description |
| --- | --- |
| setSubject (String) | Renvoie ou définit le sujet d'une présentation. Lecture/écriture String. |

 **Retour:**  
void


---


### setTitle {#setTitle}

| Nom | Description |
| --- | --- |
| setTitle (String) | Renvoie ou définit le titre d'une présentation. Lecture/écriture String. |

 **Retour:**  
void


---


### setTotalEditingTime {#setTotalEditingTime}

| Nom | Description |
| --- | --- |
| setTotalEditingTime (double) | Durée totale d'édition d'une présentation. Lecture/écriture double. |

 **Retour:**  
void


---


### set_Item {#set_Item}

| Nom | Description |
| --- | --- |
| set_Item (String, Object) | Renvoie ou définit la propriété personnalisée associée à un nom spécifié. Lecture/écriture Object. La valeur peut être int, float, String, boolean ou Date. |

 **Retour:**  
void


---