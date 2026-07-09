---
title: DocumentProperties
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Représente les propriétés d'une présentation.
type: docs
weight: 2790
url: /fr/aspose.slides/documentproperties/
---
## classe DocumentProperties

Représente les propriétés d’une présentation.

```csharp
public class DocumentProperties : IDocumentProperties, IGenericCloneable<IDocumentProperties>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [DocumentProperties](documentproperties)() | Initialise une nouvelle instance de la classe [`DocumentProperties`](../documentproperties). |

## Propriétés

| Nom | Description |
| --- | --- |
| [ApplicationTemplate](../../aspose.slides/documentproperties/applicationtemplate) { get; set; } | Renvoie ou définit le modèle d’une application. Lecture/écriture String. |
| [AppVersion](../../aspose.slides/documentproperties/appversion) { get; } | Renvoie la version de l’application. Lecture seule String. |
| [Author](../../aspose.slides/documentproperties/author) { get; set; } | Renvoie ou définit l’auteur d’une présentation. Lecture/écriture String. |
| [Category](../../aspose.slides/documentproperties/category) { get; set; } | Renvoie ou définit la catégorie d’une présentation. Lecture/écriture String. |
| [Comments](../../aspose.slides/documentproperties/comments) { get; set; } | Renvoie ou définit les commentaires d’une présentation. Lecture/écriture String. |
| [Company](../../aspose.slides/documentproperties/company) { get; set; } | Renvoie ou définit la propriété société. Lecture/écriture String. |
| [ContentStatus](../../aspose.slides/documentproperties/contentstatus) { get; set; } | Renvoie ou définit le statut du contenu d’une présentation. Lecture/écriture String. |
| [ContentType](../../aspose.slides/documentproperties/contenttype) { get; set; } | Renvoie ou définit le type de contenu d’une présentation. Lecture/écriture String. |
| [CountOfCustomProperties](../../aspose.slides/documentproperties/countofcustomproperties) { get; } | Renvoie le nombre de propriétés personnalisées réellement présentes dans une collection. Lecture seule Int32. |
| [CreatedTime](../../aspose.slides/documentproperties/createdtime) { get; set; } | Renvoie la date de création d’une présentation. Les valeurs sont en UTC. Lecture/écriture DateTime. |
| [HeadingPairs](../../aspose.slides/documentproperties/headingpairs) { get; } | Indique le regroupement des parties du document et le nombre de parties dans chaque groupe. Lecture seule IHeadingPair[]. |
| [HiddenSlides](../../aspose.slides/documentproperties/hiddenslides) { get; } | Renvoie le nombre de diapositives masquées dans un document de présentation. Lecture seule Int32. |
| [HyperlinkBase](../../aspose.slides/documentproperties/hyperlinkbase) { get; set; } | Renvoie ou définit la propriété de document HyperlinkBase. Lecture/écriture String. |
| [HyperlinksChanged](../../aspose.slides/documentproperties/hyperlinkschanged) { get; set; } | Spécifie qu’un ou plusieurs hyperliens dans cette partie ont été mis à jour exclusivement dans cette partie par un producteur. Le prochain producteur qui ouvrira ce document devra mettre à jour les relations d’hyperliens avec les nouveaux hyperliens spécifiés dans cette partie. Lecture/écriture Boolean. |
| [Item](../../aspose.slides/documentproperties/item) { get; set; } | Renvoie ou définit la propriété personnalisée associée à un nom spécifié. Lecture/écriture Object. |
| [Keywords](../../aspose.slides/documentproperties/keywords) { get; set; } | Renvoie ou définit les mots-clés d’une présentation. Lecture/écriture String. |
| [LastPrinted](../../aspose.slides/documentproperties/lastprinted) { get; set; } | Renvoie la date à laquelle une présentation a été imprimée pour la dernière fois. Lecture/écriture DateTime. |
| [LastSavedBy](../../aspose.slides/documentproperties/lastsavedby) { get; set; } | Renvoie ou définit le nom de la dernière personne ayant modifié une présentation. Lecture/écriture String. |
| [LastSavedTime](../../aspose.slides/documentproperties/lastsavedtime) { get; set; } | Renvoie la date à laquelle une présentation a été modifiée pour la dernière fois. Les valeurs sont en UTC. Lecture seule dans le cas de Presentation.DocumentProperties (car elle sera mise à jour en interne pendant le processus d’enregistrement de l’objet IPresentation). Peut être modifiée via l’instance DocumentProperties renvoyée par la méthode [`ReadDocumentProperties`](../ipresentationinfo/readdocumentproperties). Veuillez consulter l’exemple dans le résumé de la méthode [`UpdateDocumentProperties`](../ipresentationinfo/updatedocumentproperties). |
| [LinksUpToDate](../../aspose.slides/documentproperties/linksuptodate) { get; set; } | Indique si les hyperliens dans un document sont à jour. Définissez cet élément sur **true** pour indiquer que les hyperliens sont mis à jour. Définissez cet élément sur **false** pour indiquer que les hyperliens sont obsolètes. Lecture/écriture Boolean. |
| [Manager](../../aspose.slides/documentproperties/manager) { get; set; } | Renvoie ou définit la propriété manager. Lecture/écriture String. |
| [MultimediaClips](../../aspose.slides/documentproperties/multimediaclips) { get; } | Renvoie le nombre total de clips audio ou vidéo présents dans le document. Lecture seule Int32. |
| [NameOfApplication](../../aspose.slides/documentproperties/nameofapplication) { get; set; } | Renvoie ou définit le nom de l’application. Lecture/écriture String. |
| [Notes](../../aspose.slides/documentproperties/notes) { get; } | Renvoie le nombre de diapositives d’une présentation contenant des notes. Lecture seule Int32. |
| [Paragraphs](../../aspose.slides/documentproperties/paragraphs) { get; } | Renvoie le nombre total de paragraphes trouvés dans un document le cas échéant. Lecture seule Int32. |
| [PresentationFormat](../../aspose.slides/documentproperties/presentationformat) { get; set; } | Renvoie ou définit le format prévu d’une présentation. Lecture/écriture String. |
| [RevisionNumber](../../aspose.slides/documentproperties/revisionnumber) { get; set; } | Renvoie ou définit le numéro de révision de la présentation. Lecture/écriture Int32. |
| [ScaleCrop](../../aspose.slides/documentproperties/scalecrop) { get; set; } | Indique le mode d’affichage de la miniature du document. Définissez cet élément sur **true** pour activer le redimensionnement de la miniature du document à l’affichage. Définissez cet élément sur **false** pour activer le recadrage de la miniature du document afin d’afficher uniquement les sections qui correspondent à l’affichage. Lecture/écriture Boolean. |
| [SharedDoc](../../aspose.slides/documentproperties/shareddoc) { get; set; } | Détermine si la présentation est partagée entre plusieurs personnes. Lecture/écriture Boolean. |
| [Slides](../../aspose.slides/documentproperties/slides) { get; } | Renvoie le nombre total de diapositives dans un document de présentation. Lecture seule Int32. |
| [Subject](../../aspose.slides/documentproperties/subject) { get; set; } | Renvoie ou définit le sujet d’une présentation. Lecture/écriture String. |
| [Title](../../aspose.slides/documentproperties/title) { get; set; } | Renvoie ou définit le titre d’une présentation. Lecture/écriture String. |
| [TitlesOfParts](../../aspose.slides/documentproperties/titlesofparts) { get; } | Spécifie le titre de chaque partie du document. Ces parties ne sont pas des parties de document mais des représentations conceptuelles de sections de document. Lecture seule string[]. |
| [TotalEditingTime](../../aspose.slides/documentproperties/totaleditingtime) { get; set; } | Durée totale d’édition d’une présentation. Lecture/écriture TimeSpan. |
| [Words](../../aspose.slides/documentproperties/words) { get; } | Renvoie le nombre total de mots contenus dans un document. Lecture seule Int32. |

## Méthodes

| Nom | Description |
| --- | --- |
| [ClearBuiltInProperties](../../aspose.slides/documentproperties/clearbuiltinproperties)() | Efface et définit les valeurs par défaut pour toutes les propriétés intégrées. |
| [ClearCustomProperties](../../aspose.slides/documentproperties/clearcustomproperties)() | Supprime toutes les propriétés personnalisées. |
| [Clone](../../aspose.slides/documentproperties/clone)() | Clone l’objet actuel |
| [CloneT](../../aspose.slides/documentproperties/clonet)() | Clone l’objet actuel |
| [ContainsCustomProperty](../../aspose.slides/documentproperties/containscustomproperty)(string) | Vérifie la présence d’une propriété personnalisée avec un nom spécifié. |
| [GetCustomPropertyName](../../aspose.slides/documentproperties/getcustompropertyname)(int) | Renvoie le nom d’une propriété personnalisée à l’indice spécifié. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue)(string, out bool) | Obtient une valeur booléenne nommée à partir des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_4)(string, out DateTime) | Obtient une valeur DateTime nommée à partir des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_1)(string, out double) | Obtient une valeur double nommée à partir des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_3)(string, out float) | Obtient une valeur float nommée à partir des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_2)(string, out int) | Obtient une valeur entière nommée à partir des propriétés personnalisées. |
| [GetCustomPropertyValue](../../aspose.slides/documentproperties/getcustompropertyvalue#getcustompropertyvalue_5)(string, out string) | Obtient une valeur chaîne nommée à partir des propriétés personnalisées. |
| [GetSensitivityLabels](../../aspose.slides/documentproperties/getsensitivitylabels)() | Obtient un tableau d’étiquettes de sensibilité à partir des propriétés personnalisées du document (Métadonnées du SDK Microsoft Information Protection). |
| [RemoveCustomProperty](../../aspose.slides/documentproperties/removecustomproperty)(string) | Supprime une propriété personnalisée associée à un nom spécifié. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue)(string, bool) | Définit une propriété booléenne personnalisée nommée. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_4)(string, DateTime) | Définit une propriété DateTime personnalisée nommée. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_1)(string, double) | Définit une propriété double personnalisée nommée. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_3)(string, float) | Définit une propriété float personnalisée nommée. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_2)(string, int) | Définit une propriété entière personnalisée nommée. |
| [SetCustomPropertyValue](../../aspose.slides/documentproperties/setcustompropertyvalue#setcustompropertyvalue_5)(string, string) | Définit une propriété chaîne personnalisée nommée. |

### Exemples

L’exemple suivant montre comment accéder aux propriétés intégrées d’une présentation PowerPoint.

```csharp
[C#]
// Instancie la classe Presentation qui représente la présentation
using (Presentation pres = new Presentation(dataDir + "AccessBuiltin Properties.pptx"))
{
	// Crée une référence à l'objet IDocumentProperties associé à la présentation
	IDocumentProperties documentProperties = pres.DocumentProperties;
	// Affiche les propriétés intégrées
	Console.WriteLine("Category : " + documentProperties.Category);
	Console.WriteLine("Current Status : " + documentProperties.ContentStatus);
	Console.WriteLine("Creation Date : " + documentProperties.CreatedTime);
	Console.WriteLine("Author : " + documentProperties.Author);
	Console.WriteLine("Description : " + documentProperties.Comments);
}
```

L’exemple suivant montre comment modifier les propriétés intégrées d’une présentation PowerPoint.

```csharp
[C#]
// Instancie la classe Presentation qui représente la Presentation
using (Presentation presentation = new Presentation(dataDir + "ModifyBuiltinProperties.pptx"))
{
	// Crée une référence à l'objet IDocumentProperties associé à la Presentation
	IDocumentProperties documentProperties = presentation.DocumentProperties;
	// Définit les propriétés intégrées
	documentProperties.Author = "Aspose.Slides for .NET";
	documentProperties.Title = "Modifying Presentation Properties";
	documentProperties.Subject = "Aspose Subject";
	// Enregistre votre présentation dans un fichier
	presentation.Save(dataDir + "DocumentProperties_out.pptx", SaveFormat.Pptx);
}
```

### Voir aussi

* interface [IDocumentProperties](../idocumentproperties)
* interface [IGenericCloneable&lt;T&gt;](../igenericcloneable-1)
* espace de noms [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->