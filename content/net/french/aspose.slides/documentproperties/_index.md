---
title: DocumentProperties
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente les propriétés dune présentation.
type: docs
weight: 2660
url: /fr/aspose.slides/documentproperties/
---
## DocumentProperties class

Représente les propriétés d'une présentation.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [DocumentProperties](documentproperties)() | Initialise une nouvelle instance de classe[`DocumentProperties`](../documentproperties) . |

## Propriétés

| Nom | La description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Renvoie ou définit le modèle d'une application. Lecture/écritureString . |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Renvoie la version de l'application. Lecture seuleString . |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Renvoie ou définit l'auteur d'une présentation. Lecture/écritureString . |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Renvoie ou définit la catégorie d'une présentation. Lecture/écritureString . |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Renvoie ou définit les commentaires d'une présentation. Lecture/écritureString . |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Renvoie ou définit la propriété de l'entreprise. Lecture/écritureString . |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Renvoie ou définit l'état du contenu d'une présentation. Lecture/écritureString . |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Renvoie ou définit le type de contenu d'une présentation. Lecture/écritureString . |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Renvoie le nombre de propriétés personnalisées réellement contenues dans une collection. Lecture seuleInt32 . |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Renvoie la date de création d'une présentation. Les valeurs sont en UTC. Lecture/écritureDateTime . |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Renvoie ou définit la propriété de document HyperlinkBase. Lecture/écritureString . |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Renvoie ou définit la propriété personnalisée associée à un nom spécifié. Lecture/écritureObject . |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Renvoie ou définit les mots-clés d'une présentation. Lecture/écritureString . |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Renvoie la date de la dernière impression d'une présentation. Lecture/écritureDateTime . |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Renvoie ou définit le nom d'une dernière personne qui a modifié une présentation. Lecture/écritureString . |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Renvoie la date à laquelle une présentation a été modifiée pour la dernière fois. Les valeurs sont en UTC. En lecture seule dans le cas de Presentation.DocumentProperties (car il sera mis à jour en interne pendant le processus d'enregistrement de l'objet IPresentation). Peut être modifié via l'instance DocumentProperties renvoyée par méthode[`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties) Veuillez voir l'exemple dans[`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties) résumé de la méthode. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Renvoie ou définit la propriété du gestionnaire. Lecture/écritureString . |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Renvoie ou définit le nom de l'application. Lecture/écritureString . |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Renvoie ou définit le format prévu d'une présentation. Lecture/écritureString . |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Renvoie ou définit le numéro de révision de la présentation. Lecture/écritureInt32 . |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Détermine si la présentation est partagée entre plusieurs personnes. Lecture/écritureBoolean . |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Renvoie ou définit le sujet d'une présentation. Lecture/écritureString . |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Renvoie ou définit le titre d'une présentation. Lecture/écritureString . |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Temps d'édition total d'une présentation. Lecture/écritureTimeSpan . |

## Méthodes

| Nom | La description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Efface et définit les valeurs par défaut pour toutes les propriétés intégrées. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Supprime toutes les propriétés personnalisées. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Clone l'objet actuel |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Clone l'objet actuel |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Vérifier les présents d'une propriété personnalisée avec un nom spécifié. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Renvoie un nom de propriété personnalisé à l'index spécifié. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Obtient une valeur booléenne nommée à partir des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Obtient une valeur DateTime nommée à partir des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Obtient une valeur double nommée à partir des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Obtient une valeur flottante nommée à partir des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Obtient une valeur entière nommée à partir des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Obtient une valeur de chaîne nommée à partir des propriétés personnalisées. |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Supprimer une propriété personnalisée associée à un nom spécifié. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Définit une propriété personnalisée booléenne nommée. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Définit une propriété personnalisée DateTime nommée. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Définit une double propriété personnalisée nommée. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Définit une propriété personnalisée flottante nommée. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Définit une propriété personnalisée entière nommée. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Définit une propriété personnalisée de chaîne nommée. |

### Voir également

* interface [IDocumentProperties](../idocumentproperties)
* interface [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
