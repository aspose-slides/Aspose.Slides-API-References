---
title: IOleObjectFrame
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente un objet OLE sur une diapositive.
type: docs
weight: 6010
url: /fr/aspose.slides/ioleobjectframe/
---
## IOleObjectFrame interface

Représente un objet OLE sur une diapositive.

```csharp
public interface IOleObjectFrame : IGraphicalObject
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AsIGraphicalObject](../../aspose.slides/ioleobjectframe/asigraphicalobject) { get; } | Permet d'obtenir l'interface IGraphicalObject de base. Lecture seule[`IGraphicalObject`](../igraphicalobject) . |
| [EmbeddedData](../../aspose.slides/ioleobjectframe/embeddeddata) { get; } | Obtient des informations sur les données intégrées OLE. Lecture seule[`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo) . |
| [EmbeddedFileLabel](../../aspose.slides/ioleobjectframe/embeddedfilelabel) { get; } | Renvoie le nom de fichier de l'objet OLE intégré |
| [EmbeddedFileName](../../aspose.slides/ioleobjectframe/embeddedfilename) { get; } | Renvoie le chemin de l'objet OLE intégré |
| [IsObjectIcon](../../aspose.slides/ioleobjectframe/isobjecticon) { get; set; } | Détermine si un objet est visible sous forme d'icône. Lecture/écritureBoolean . |
| [IsObjectLink](../../aspose.slides/ioleobjectframe/isobjectlink) { get; } | Détermine si un objet est lié à un fichier externe. Lecture seuleBoolean . |
| [LinkFileName](../../aspose.slides/ioleobjectframe/linkfilename) { get; } | Renvoie le chemin complet vers un fichier lié. Le nom de fichier court sera utilisé. Lecture seuleString . |
| [LinkPathLong](../../aspose.slides/ioleobjectframe/linkpathlong) { get; set; } | Renvoie le chemin complet vers un fichier lié. Le nom de fichier long sera utilisé. Lecture/écritureString . |
| [ObjectName](../../aspose.slides/ioleobjectframe/objectname) { get; set; } | Renvoie ou définit le nom d'un objet. Lecture/écritureString . |
| [ObjectProgId](../../aspose.slides/ioleobjectframe/objectprogid) { get; set; } | Renvoie le ProgID d'un objet. Lecture seuleString . |
| [SubstitutePictureFormat](../../aspose.slides/ioleobjectframe/substitutepictureformat) { get; } | Renvoie l'objet de propriétés de remplissage d'image OleObject. Lecture seule[`IPictureFillFormat`](../ipicturefillformat) . |
| [SubstitutePictureTitle](../../aspose.slides/ioleobjectframe/substitutepicturetitle) { get; set; } | Renvoie ou définit le titre de l'icône OleObject. Lecture/écritureString . |
| [UpdateAutomatic](../../aspose.slides/ioleobjectframe/updateautomatic) { get; set; } | Détermine si l'objet incorporé lié est automatiquement mis à jour lorsque la présentation est ouverte ou imprimée. Lecture/écritureBoolean . |

## Méthodes

| Nom | La description |
| --- | --- |
| [SetEmbeddedData](../../aspose.slides/ioleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Définit les informations sur les données intégrées OLE. |

### Voir également

* interface [IGraphicalObject](../igraphicalobject)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
