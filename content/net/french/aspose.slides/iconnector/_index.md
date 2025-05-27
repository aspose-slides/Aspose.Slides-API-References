---
title: IConnector
second_title: Référence API Aspose.Sildes pour .NET
description: Représente un connecteur.
type: docs
weight: 5410
url: /fr/aspose.slides/iconnector/
---

## Interface IConnector

Représente un connecteur.

```csharp
public interface IConnector : IGeometryShape
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AsIGeometryShape](../../aspose.slides/iconnector/asigeometryshape) { get; } | Permet d'obtenir l'interface de base IGeometryShape. Lecture seule [`IGeometryShape`](../igeometryshape). |
| [ConnectorLock](../../aspose.slides/iconnector/connectorlock) { get; } | Renvoie les verrouillages du connecteur. Lecture seule [`IConnectorLock`](../iconnectorlock). |
| [EndShapeConnectedTo](../../aspose.slides/iconnector/endshapeconnectedto) { get; set; } | Renvoie ou définit la forme à laquelle attacher l'extrémité du connecteur. Lecture/écriture [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/iconnector/endshapeconnectionsiteindex) { get; set; } | Renvoie ou définit l'index du site de connexion pour la forme de fin. Lecture/écriture UInt32. |
| [ShapeLock](../../aspose.slides/iconnector/shapelock) { get; } | Renvoie les verrouillages de la forme. Lecture seule [`IConnectorLock`](../iconnectorlock). |
| [StartShapeConnectedTo](../../aspose.slides/iconnector/startshapeconnectedto) { get; set; } | Renvoie ou définit la forme à laquelle attacher le début du connecteur. Lecture/écriture [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/iconnector/startshapeconnectionsiteindex) { get; set; } | Renvoie ou définit l'index du site de connexion pour la forme de départ. Lecture/écriture UInt32. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Reroute](../../aspose.slides/iconnector/reroute)() | Redirige le connecteur afin qu'il emprunte le chemin le plus court possible entre les formes qu'il relie. |

### Voir Aussi

* interface [IGeometryShape](../igeometryshape)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)