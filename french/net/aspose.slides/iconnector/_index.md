---
title: IConnector
second_title: Référence de l'API Aspose.Slides pour .NET
description: Représente un connecteur.
type: docs
weight: 5140
url: /fr/net/aspose.slides/iconnector/
---
## IConnector interface

Représente un connecteur.

```csharp
public interface IConnector : IGeometryShape
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AsIGeometryShape](../../aspose.slides/iconnector/asigeometryshape) { get; } | Permet d'obtenir l'interface IGeometryShape de base. Lecture seule[`IGeometryShape`](../igeometryshape) . |
| [ConnectorLock](../../aspose.slides/iconnector/connectorlock) { get; } | Renvoie les verrous du connecteur. Lecture seule[`IConnectorLock`](../iconnectorlock) . |
| [EndShapeConnectedTo](../../aspose.slides/iconnector/endshapeconnectedto) { get; set; } | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture[`IShape`](../ishape) . |
| [EndShapeConnectionSiteIndex](../../aspose.slides/iconnector/endshapeconnectionsiteindex) { get; set; } | Renvoie ou définit l'index du site de connexion pour la forme de fin. Lecture/écritureUInt32 . |
| [ShapeLock](../../aspose.slides/iconnector/shapelock) { get; } | Renvoie les verrous de la forme. Lecture seule[`IConnectorLock`](../iconnectorlock) . |
| [StartShapeConnectedTo](../../aspose.slides/iconnector/startshapeconnectedto) { get; set; } | Renvoie ou définit la forme à laquelle attacher le début du connecteur. Lecture/écriture[`IShape`](../ishape) . |
| [StartShapeConnectionSiteIndex](../../aspose.slides/iconnector/startshapeconnectionsiteindex) { get; set; } | Renvoie ou définit l'index du site de connexion pour la forme de départ. Lecture/écritureUInt32 . |

## Méthodes

| Nom | La description |
| --- | --- |
| [Reroute](../../aspose.slides/iconnector/reroute)() | Redirige le connecteur afin qu'il emprunte le chemin le plus court possible entre les formes qu'il connecte. |

### Voir également

* interface [IGeometryShape](../igeometryshape)
* espace de noms [Aspose.Slides](../../aspose.slides)
* Assemblée [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->