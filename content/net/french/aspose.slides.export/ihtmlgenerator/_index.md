---
title: IHtmlGenerator
second_title: Référence API Aspose.Slides pour .NET
description: Générateur HTML.
type: docs
weight: 3790
url: /fr/aspose.slides.export/ihtmlgenerator/
---

## Interface IHtmlGenerator

Générateur HTML.

```csharp
public interface IHtmlGenerator
```

## Propriétés

| Nom | Description |
| --- | --- |
| [NextSlideIndex](../../aspose.slides.export/ihtmlgenerator/nextslideindex) { get; } | Renvoie l'index d'une diapositive, qui sera rendu après la diapositive actuelle ou -1 si la dernière diapositive est actuellement en cours de rendu. En lecture seule Int32. |
| [PreviousSlideIndex](../../aspose.slides.export/ihtmlgenerator/previousslideindex) { get; } | Renvoie l'index de la diapositive précédemment rendue ou -1 si la première diapositive est en cours de rendu. En lecture seule Int32. |
| [SlideImageSize](../../aspose.slides.export/ihtmlgenerator/slideimagesize) { get; } | Renvoie la taille de l'image de la diapositive. En lecture seule SizeF. |
| [SlideImageSizeUnit](../../aspose.slides.export/ihtmlgenerator/slideimagesizeunit) { get; } | Renvoie une unité dans laquelle la taille de l'image de la diapositive est spécifiée. En lecture seule [`SvgCoordinateUnit`](../svgcoordinateunit). |
| [SlideImageSizeUnitCode](../../aspose.slides.export/ihtmlgenerator/slideimagesizeunitcode) { get; } | Renvoie un code css d'unité dans laquelle la taille de l'image de la diapositive est spécifiée. En lecture seule String. |
| [SlideIndex](../../aspose.slides.export/ihtmlgenerator/slideindex) { get; } | Renvoie l'index de la diapositive actuellement rendue. En lecture seule Int32. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddAttributeValue](../../aspose.slides.export/ihtmlgenerator/addattributevalue#addattributevalue)(char[]) | Met en guillemets la valeur de l'attribut et l'ajoute au fichier html. |
| [AddAttributeValue](../../aspose.slides.export/ihtmlgenerator/addattributevalue#addattributevalue_2)(string) | Met en guillemets la valeur de l'attribut et l'ajoute au fichier html. |
| [AddAttributeValue](../../aspose.slides.export/ihtmlgenerator/addattributevalue#addattributevalue_1)(char[], int, int) | Met en guillemets la valeur de l'attribut et l'ajoute au fichier html. |
| [AddHtml](../../aspose.slides.export/ihtmlgenerator/addhtml#addhtml)(char[]) | Ajoute du texte HTML formaté. |
| [AddHtml](../../aspose.slides.export/ihtmlgenerator/addhtml#addhtml_2)(string) | Ajoute du texte HTML formaté. |
| [AddHtml](../../aspose.slides.export/ihtmlgenerator/addhtml#addhtml_1)(char[], int, int) | Ajoute du texte HTML formaté. |
| [AddText](../../aspose.slides.export/ihtmlgenerator/addtext#addtext)(char[]) | Ajoute du texte brut aux fichiers html, remplaçant les caractères spéciaux par des entités html. Les sauts de ligne et espaces ne sont pas remplacés. |
| [AddText](../../aspose.slides.export/ihtmlgenerator/addtext#addtext_2)(string) | Ajoute du texte brut aux fichiers html, remplaçant les caractères spéciaux par des entités html. Les sauts de ligne et espaces ne sont pas remplacés. |
| [AddText](../../aspose.slides.export/ihtmlgenerator/addtext#addtext_1)(char[], int, int) | Ajoute du texte brut aux fichiers html, remplaçant les caractères spéciaux par des entités html. Les sauts de ligne et espaces ne sont pas remplacés. |

### Voir aussi

* namespace [Aspose.Slides.Export](../../aspose.slides.export)
* assembly [Aspose.Slides](../../)

<!-- NE PAS ÉDITER : généré par xmldocmd pour Aspose.Slides.dll -->