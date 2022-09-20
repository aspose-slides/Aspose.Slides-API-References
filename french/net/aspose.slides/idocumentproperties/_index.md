---
title: IDocumentProperties
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente les propriétés dune présentation.
type: docs
weight: 5240
url: /fr/net/aspose.slides/idocumentproperties/
---
## IDocumentProperties interface

Représente les propriétés d'une présentation.

```csharp
public interface IDocumentProperties
```

## Propriétés

| Nom | La description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/idocumentproperties/applicationtemplate) { get; set; } | Renvoie ou définit le modèle d'une application. Lecture/écritureString . |
| [AppVersion](../../aspose.slides/idocumentproperties/appversion) { get; } | Renvoie la version de l'application. Lecture seuleString . |
| [Author](../../aspose.slides/idocumentproperties/author) { get; set; } | Renvoie ou définit l'auteur d'une présentation. Lecture/écritureString . |
| [Category](../../aspose.slides/idocumentproperties/category) { get; set; } | Renvoie ou définit la catégorie d'une présentation. Lecture/écritureString . |
| [Comments](../../aspose.slides/idocumentproperties/comments) { get; set; } | Renvoie ou définit les commentaires d'une présentation. Lecture/écritureString . |
| [Company](../../aspose.slides/idocumentproperties/company) { get; set; } | Renvoie ou définit la propriété de l'entreprise. Lecture/écritureString . |
| [ContentStatus](../../aspose.slides/idocumentproperties/contentstatus) { get; set; } | Renvoie ou définit l'état du contenu d'une présentation. Lecture/écritureString . |
| [ContentType](../../aspose.slides/idocumentproperties/contenttype) { get; set; } | Renvoie ou définit le type de contenu d'une présentation. Lecture/écritureString . |
| [CountOfCustomProperties](../../aspose.slides/idocumentproperties/countofcustomproperties) { get; } | Renvoie le nombre de propriétés personnalisées réellement contenues dans une collection. Lecture seuleInt32 . |
| [CreatedTime](../../aspose.slides/idocumentproperties/createdtime) { get; set; } | Renvoie la date de création d'une présentation. Les valeurs sont en UTC. Lecture/écritureDateTime . |
| [HyperlinkBase](../../aspose.slides/idocumentproperties/hyperlinkbase) { get; set; } | Renvoie ou définit la propriété de document HyperlinkBase. Lecture/écritureString . |
| [Item](../../aspose.slides/idocumentproperties/item) { get; set; } | Renvoie ou définit la propriété personnalisée associée à un nom spécifié. Lecture/écritureObject . |
| [Keywords](../../aspose.slides/idocumentproperties/keywords) { get; set; } | Renvoie ou définit les mots-clés d'une présentation. Lecture/écritureString . |
| [LastPrinted](../../aspose.slides/idocumentproperties/lastprinted) { get; set; } | Renvoie la date de la dernière impression d'une présentation. Lecture/écritureDateTime . |
| [LastSavedBy](../../aspose.slides/idocumentproperties/lastsavedby) { get; set; } | Renvoie ou définit le nom d'une dernière personne qui a modifié une présentation. Lecture/écritureString . |
| [LastSavedTime](../../aspose.slides/idocumentproperties/lastsavedtime) { get; set; } | Renvoie la date à laquelle une présentation a été modifiée pour la dernière fois. Les valeurs sont en UTC.P En lecture seule dans le cas de Presentation.DocumentProperties (car il sera mis à jour en interne pendant le processus de sauvegarde de l'objet IPresentation). Peut être modifié via l'instance DocumentProperties renvoyée par méthode[`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) Veuillez voir l'exemple dans[`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) résumé de la méthode. |
| [Manager](../../aspose.slides/idocumentproperties/manager) { get; set; } | Renvoie ou définit la propriété du gestionnaire. Lecture/écritureString . |
| [NameOfApplication](../../aspose.slides/idocumentproperties/nameofapplication) { get; set; } | Renvoie ou définit le nom de l'application. Lecture/écritureString . |
| [PresentationFormat](../../aspose.slides/idocumentproperties/presentationformat) { get; set; } | Renvoie ou définit le format prévu d'une présentation. Lecture/écritureString . |
| [RevisionNumber](../../aspose.slides/idocumentproperties/revisionnumber) { get; set; } | Renvoie ou définit le numéro de révision de la présentation. Lecture/écritureInt32 . |
| [SharedDoc](../../aspose.slides/idocumentproperties/shareddoc) { get; set; } | Détermine si la présentation est partagée entre plusieurs personnes. Lecture/écritureBoolean . |
| [Subject](../../aspose.slides/idocumentproperties/subject) { get; set; } | Renvoie ou définit le sujet d'une présentation. Lecture/écritureString . |
| [Title](../../aspose.slides/idocumentproperties/title) { get; set; } | Renvoie ou définit le titre d'une présentation. Lecture/écritureString . |
| [TotalEditingTime](../../aspose.slides/idocumentproperties/totaleditingtime) { get; set; } | Temps d'édition total d'une présentation. Lecture/écritureTimeSpan . |

## Méthodes

| Nom | La description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/idocumentproperties/clearbuiltinproperties)() | Efface et définit les valeurs par défaut pour toutes les propriétés intégrées. |
| [ClearCustomProperties](../../aspose.slides/idocumentproperties/clearcustomproperties)() | Supprime toutes les propriétés personnalisées. |
| [ContainsCustomProperty](../../aspose.slides/idocumentproperties/containscustomproperty)(string) | Vérifier les présents d'une propriété personnalisée avec un nom spécifié. |
| [GetCustomPropertyName](../../aspose.slides/idocumentproperties/getcustompropertyname)(int) | Renvoie un nom de propriété personnalisé à l'index spécifié. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Obtient une valeur booléenne nommée à partir des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Obtient une valeur DateTime nommée à partir des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Obtient une valeur double nommée à partir des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Obtient une valeur flottante nommée à partir des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Obtient une valeur entière nommée à partir des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/idocumentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Obtient une valeur de chaîne nommée à partir des propriétés personnalisées. |
| [RemoveCustomProperty](../../aspose.slides/idocumentproperties/removecustomproperty)(string) | Supprimer une propriété personnalisée associée à un nom spécifié. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Définit une propriété personnalisée booléenne nommée. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Définit une propriété personnalisée DateTime nommée. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Définit une double propriété personnalisée nommée. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Définit une propriété personnalisée flottante nommée. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Définit une propriété personnalisée entière nommée. |
| [SetCustomPropertyValue](../../aspose.slides/idocumentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Définit une propriété personnalisée de chaîne nommée. |

### Voir également

* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
