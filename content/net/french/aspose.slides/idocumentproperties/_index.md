---
title: IDocumentProperties
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente les propriétés d'une présentation.
type: docs
weight: 5710
url: /fr/aspose.slides/idocumentproperties/
---
## interface IDocumentProperties

Represents properties of a presentation.

```csharp
public interface IDocumentProperties
```

## Propriétés

| Name | Description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Renvoie ou définit le modèle d'une application. Lecture/écriture String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Renvoie la version de l'application. Lecture seule String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Renvoie ou définit l'auteur d'une présentation. Lecture/écriture String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Renvoie ou définit la catégorie d'une présentation. Lecture/écriture String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Renvoie ou définit les commentaires d'une présentation. Lecture/écriture String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Renvoie ou définit la propriété company. Lecture/écriture String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Renvoie ou définit le statut du contenu d'une présentation. Lecture/écriture String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Renvoie ou définit le type de contenu d'une présentation. Lecture/écriture String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Renvoie le nombre de propriétés personnalisées effectivement contenues dans une collection. Lecture seule Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Renvoie la date de création d'une présentation. Les valeurs sont en UTC. Lecture/écriture DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Indique le regroupement des parties du document et le nombre de parties dans chaque groupe. Lecture seule IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Spécifie le nombre de diapositives masquées dans un document de présentation. Lecture seule Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Renvoie ou définit la propriété de document HyperlinkBase. Lecture/écriture String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Spécifie qu'un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. Le prochain producteur à ouvrir ce document devra mettre à jour les relations d'hyperliens avec les nouveaux hyperliens spécifiés dans cette partie. Lecture/écriture Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Renvoie ou définit la propriété personnalisée associée à un nom spécifié. Lecture/écriture Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Renvoie ou définit les mots-clés d'une présentation. Lecture/écriture String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Renvoie la date à laquelle une présentation a été imprimée pour la dernière fois. Lecture/écriture DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Renvoie ou définit le nom de la dernière personne qui a modifié une présentation. Lecture/écriture String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Renvoie la date à laquelle une présentation a été modifiée pour la dernière fois. Les valeurs sont en UTC. Lecture seule dans le cas de Presentation.DocumentProperties (car elle sera mise à jour en interne pendant le processus d'enregistrement de l'objet IPresentation). Peut être modifiée via l'instance DocumentProperties renvoyée par la méthode [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Veuillez consulter l'exemple dans le résumé de la méthode [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Indique si les hyperliens dans un document sont à jour. Définissez cet élément sur **true** pour indiquer que les hyperliens sont mis à jour. Définissez cet élément sur **false** pour indiquer que les hyperliens sont obsolètes. Lecture/écriture Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Renvoie ou définit la propriété manager. Lecture/écriture String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Spécifie le nombre total de clips audio ou vidéo présents dans le document. Lecture seule Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Renvoie ou définit le nom de l'application. Lecture/écriture String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Spécifie le nombre de diapositives d'une présentation contenant des notes. Lecture seule Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Spécifie le nombre total de paragraphes trouvés dans un document le cas échéant. Lecture seule Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Renvoie ou définit le format prévu d'une présentation. Lecture/écriture String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Renvoie ou définit le numéro de révision de la présentation. Lecture/écriture Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Indique le mode d'affichage de la vignette du document. Définissez cet élément sur **true** pour activer le redimensionnement de la vignette du document à l'affichage. Définissez cet élément sur **false** pour activer le recadrage de la vignette du document afin d'afficher uniquement les sections qui correspondent à l'affichage. Lecture/écriture Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Détermine si la présentation est partagée entre plusieurs personnes. Lecture/écriture Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Spécifie le nombre total de diapositives dans un document de présentation. Lecture seule Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Renvoie ou définit le sujet d'une présentation. Lecture/écriture String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Renvoie ou définit le titre d'une présentation. Lecture/écriture String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Spécifie le titre de chaque partie du document. Ces parties ne sont pas des parties du document mais des représentations conceptuelles des sections du document. Lecture seule string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Durée totale d'édition d'une présentation. Lecture/écriture TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Spécifie le nombre total de mots contenus dans un document. Lecture seule Int32. |

## Méthodes

| Nom | Description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Efface et définit les valeurs par défaut pour toutes les propriétés intégrées. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Supprime toutes les propriétés personnalisées. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Vérifie la présence d'une propriété personnalisée avec un nom spécifié. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Renvoie le nom d'une propriété personnalisée à l'index spécifié. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Obtient une valeur booléenne nommée à partir des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Obtient une valeur DateTime nommée à partir des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Obtient une valeur double nommée à partir des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Obtient une valeur float nommée à partir des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Obtient une valeur entière nommée à partir des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Obtient une valeur chaîne nommée à partir des propriétés personnalisées. |
| [GetSensitivityLabels](../../aspose.slides/idocumentproperties/getsensitivitylabels)() | Obtient un tableau d'étiquettes de sensibilité à partir des propriétés personnalisées du document (Métadonnées Microsoft Information Protection SDK). |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Supprime une propriété personnalisée associée à un nom spécifié. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Définit une propriété booléenne personnalisée nommée. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Définit une propriété DateTime personnalisée nommée. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Définit une propriété double personnalisée nommée. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Définit une propriété float personnalisée nommée. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Définit une propriété entière personnalisée nommée. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Définit une propriété chaîne personnalisée nommée. |

### Voir aussi

* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->