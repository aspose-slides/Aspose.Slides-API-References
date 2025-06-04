---
title: IDocumentProperties
second_title: Référence API Aspose.Slides pour .NET
description: Représente les propriétés d'une présentation.
type: docs
weight: 5510
url: /fr/aspose.slides/idocumentproperties/
---

## Interface IDocumentProperties

Représente les propriétés d'une présentation.

```csharp
public interface IDocumentProperties
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Retourne ou définit le modèle d'une application. Lecture/écriture String. |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Retourne la version de l'application. Lecture seule String. |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Retourne ou définit l'auteur d'une présentation. Lecture/écriture String. |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Retourne ou définit la catégorie d'une présentation. Lecture/écriture String. |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Retourne ou définit les commentaires d'une présentation. Lecture/écriture String. |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Retourne ou définit la propriété de l'entreprise. Lecture/écriture String. |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Retourne ou définit le statut du contenu d'une présentation. Lecture/écriture String. |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Retourne ou définit le type de contenu d'une présentation. Lecture/écriture String. |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Retourne le nombre de propriétés personnalisées réellement contenues dans une collection. Lecture seule Int32. |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Retourne la date à laquelle une présentation a été créée. Les valeurs sont en UTC. Lecture/écriture DateTime. |
| [HeadingPairs](../../aspose.slides/idocumentproperties/headingpairs) { get; } | Indique le regroupement des parties du document et le nombre de parties dans chaque groupe. Lecture seule IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/idocumentproperties/hiddenslides) { get; } | Spécifie le nombre de diapositives cachées dans un document de présentation. Lecture seule Int32. |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Retourne ou définit la propriété HyperlinkBase du document. Lecture/écriture String. |
| [HyperlinksChanged](../../aspose.slides/idocumentproperties/hyperlinkschanged) { get; set; } | Spécifie qu'un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. Le prochain producteur à ouvrir ce document devra mettre à jour les relations d'hyperliens avec les nouveaux hyperliens spécifiés dans cette partie. Lecture/écriture Boolean. |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Retourne ou définit la propriété personnalisée associée à un nom spécifié. Lecture/écriture Object. |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Retourne ou définit les mots-clés d'une présentation. Lecture/écriture String. |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Retourne la date à laquelle une présentation a été imprimée pour la dernière fois. Lecture/écriture DateTime. |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Retourne ou définit le nom de la dernière personne ayant modifié une présentation. Lecture/écriture String. |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Retourne la date à laquelle une présentation a été modifiée pour la dernière fois. Les valeurs sont en UTC. Lecture seule en cas de Presentation.DocumentProperties (car elle sera mise à jour en interne lors du processus de sauvegarde de l'objet IPresentation). Peut être modifiée via une instance DocumentProperties renvoyée par la méthode [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Veuillez voir l'exemple dans le résumé de la méthode [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/idocumentproperties/linksuptodate) { get; set; } | Indique si les hyperliens dans un document sont à jour. Définir cet élément sur **true** pour indiquer que les hyperliens sont mis à jour. Définir cet élément sur **false** pour indiquer que les hyperliens sont obsolètes. Lecture/écriture Boolean. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Retourne ou définit la propriété du gestionnaire. Lecture/écriture String. |
| [MultimediaClips](../../aspose.slides/idocumentproperties/multimediaclips) { get; } | Spécifie le nombre total de clips audio ou vidéo présents dans le document. Lecture seule Int32. |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Retourne ou définit le nom de l'application. Lecture/écriture String. |
| [Notes](../../aspose.slides/idocumentproperties/notes) { get; } | Spécifie le nombre de diapositives dans une présentation contenant des notes. Lecture seule Int32. |
| [Paragraphs](../../aspose.slides/idocumentproperties/paragraphs) { get; } | Spécifie le nombre total de paragraphes trouvés dans un document, le cas échéant. Lecture seule Int32. |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Retourne ou définit le format souhaité d'une présentation. Lecture/écriture String. |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Retourne ou définit le numéro de révision de la présentation. Lecture/écriture Int32. |
| [ScaleCrop](../../aspose.slides/idocumentproperties/scalecrop) { get; set; } | Indique le mode d'affichage de la miniature du document. Définir cet élément sur **true** pour activer le redimensionnement de la miniature du document à l'affichage. Définir cet élément sur **false** pour activer le recadrage de la miniature du document afin d'afficher uniquement les sections qui s'adaptent à l'affichage. Lecture/écriture Boolean. |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Détermine si la présentation est partagée entre plusieurs personnes. Lecture/écriture Boolean. |
| [Slides](../../aspose.slides/idocumentproperties/slides) { get; } | Spécifie le nombre total de diapositives dans un document de présentation. Lecture seule Int32. |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Retourne ou définit le sujet d'une présentation. Lecture/écriture String. |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Retourne ou définit le titre d'une présentation. Lecture/écriture String. |
| [TitlesOfParts](../../aspose.slides/idocumentproperties/titlesofparts) { get; } | Spécifie le titre de chaque partie du document. Ces parties ne sont pas des parties du document mais des représentations conceptuelles de sections du document. Lecture seule string[]. |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Temps total de modification d'une présentation. Lecture/écriture TimeSpan. |
| [Words](../../aspose.slides/idocumentproperties/words) { get; } | Spécifie le nombre total de mots contenus dans un document. Lecture seule Int32. |

## Méthodes

| Nom | Description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Efface et définit les valeurs par défaut pour toutes les propriétés intégrées. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Supprime toutes les propriétés personnalisées. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Vérifie la présence d'une propriété personnalisée avec un nom spécifié. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Retourne un nom de propriété personnalisée à l'index spécifié. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Obtient une valeur booléenne nommée des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Obtient une valeur DateTime nommée des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Obtient une valeur double nommée des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Obtient une valeur float nommée des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Obtient une valeur entière nommée des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Obtient une valeur string nommée des propriétés personnalisées. |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Supprime une propriété personnalisée associée à un nom spécifié. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Définit une propriété personnalisée booléenne nommée. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Définit une propriété personnalisée DateTime nommée. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Définit une propriété personnalisée double nommée. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Définit une propriété personnalisée float nommée. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Définit une propriété personnalisée entière nommée. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Définit une propriété personnalisée string nommée. |

### Voir Aussi

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->