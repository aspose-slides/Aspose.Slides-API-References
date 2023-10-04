---
title: Connector
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/connector/
---

## Connector class

  Represents a connector.
 

## Functions

| Name | Description |
| --- | --- |
| [getConnectorLock]() | Returns connector's locks. Read-only IConnectorLock. |

### Result
[ConnectorLock](../../connectorlock)


---


| [getEndShapeConnectedTo]() | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Result
[LegacyDiagram](../../legacydiagram), [Connector](../../connector), [GraphicalObject](../../graphicalobject), [Shape](../../shape), [Ink](../../ink), [GroupShape](../../groupshape), [SmartArtShape](../../smartartshape), [SummaryZoomSection](../../summaryzoomsection), [ZoomObject](../../zoomobject), [SmartArt](../../smartart), [VideoFrame](../../videoframe), [PictureFrame](../../pictureframe), [ZoomFrame](../../zoomframe), [AutoShape](../../autoshape), [GeometryShape](../../geometryshape), [OleObjectFrame](../../oleobjectframe), [SectionZoomFrame](../../sectionzoomframe), [AudioFrame](../../audioframe), [Chart](../../chart), [Table](../../table), [SummaryZoomFrame](../../summaryzoomframe)

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [getEndShapeConnectionSiteIndex]() | Returns or sets the index of connection site for end shape. Read/write long. |

### Result
long

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when value is less than EndShapeConnectedTo.ConnectionSiteCount |


---


| [getShapeLock]() | Returns shape's locks. Read-only IConnectorLock. |

### Result
[ConnectorLock](../../connectorlock)


---


| [getShapeType]() | Returns or sets the AutoShape type. Read/write ShapeType. |

### Result
int


---


| [getStartShapeConnectedTo]() | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Result
[LegacyDiagram](../../legacydiagram), [Connector](../../connector), [GraphicalObject](../../graphicalobject), [Shape](../../shape), [Ink](../../ink), [GroupShape](../../groupshape), [SmartArtShape](../../smartartshape), [SummaryZoomSection](../../summaryzoomsection), [ZoomObject](../../zoomobject), [SmartArt](../../smartart), [VideoFrame](../../videoframe), [PictureFrame](../../pictureframe), [ZoomFrame](../../zoomframe), [AutoShape](../../autoshape), [GeometryShape](../../geometryshape), [OleObjectFrame](../../oleobjectframe), [SectionZoomFrame](../../sectionzoomframe), [AudioFrame](../../audioframe), [Chart](../../chart), [Table](../../table), [SummaryZoomFrame](../../summaryzoomframe)

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [getStartShapeConnectionSiteIndex]() | Returns or sets the index of connection site for start shape. Read/write long. |

### Result
long

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when value is less than StartShapeConnectedTo.ConnectionSiteCount |


---


| [reroute]() | Reroutes connector so that it take the shortest possible path between the shapes it connect. |


---


| [setEndShapeConnectedTo]([LegacyDiagram](../legacydiagram)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setEndShapeConnectedTo]([Connector](../connector)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setEndShapeConnectedTo]([GraphicalObject](../graphicalobject)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setEndShapeConnectedTo]([Shape](../shape)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setEndShapeConnectedTo]([Ink](../ink)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setEndShapeConnectedTo]([GroupShape](../groupshape)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setEndShapeConnectedTo]([SmartArtShape](../smartartshape)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setEndShapeConnectedTo]([SummaryZoomSection](../summaryzoomsection)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setEndShapeConnectedTo]([ZoomObject](../zoomobject)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setEndShapeConnectedTo]([SmartArt](../smartart)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setEndShapeConnectedTo]([VideoFrame](../videoframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setEndShapeConnectedTo]([PictureFrame](../pictureframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setEndShapeConnectedTo]([ZoomFrame](../zoomframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setEndShapeConnectedTo]([AutoShape](../autoshape)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setEndShapeConnectedTo]([OleObjectFrame](../oleobjectframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setEndShapeConnectedTo]([SectionZoomFrame](../sectionzoomframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setEndShapeConnectedTo]([AudioFrame](../audioframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setEndShapeConnectedTo]([Chart](../chart)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setEndShapeConnectedTo]([Table](../table)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setEndShapeConnectedTo]([SummaryZoomFrame](../summaryzoomframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setEndShapeConnectionSiteIndex](long) | Returns or sets the index of connection site for end shape. Read/write long. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when value is less than EndShapeConnectedTo.ConnectionSiteCount |


---


| [setShapeType](int) | Returns or sets the AutoShape type. Read/write ShapeType. |


---


| [setStartShapeConnectedTo]([LegacyDiagram](../legacydiagram)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setStartShapeConnectedTo]([Connector](../connector)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setStartShapeConnectedTo]([GraphicalObject](../graphicalobject)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setStartShapeConnectedTo]([Shape](../shape)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setStartShapeConnectedTo]([Ink](../ink)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setStartShapeConnectedTo]([GroupShape](../groupshape)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setStartShapeConnectedTo]([SmartArtShape](../smartartshape)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setStartShapeConnectedTo]([SummaryZoomSection](../summaryzoomsection)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setStartShapeConnectedTo]([ZoomObject](../zoomobject)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setStartShapeConnectedTo]([SmartArt](../smartart)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setStartShapeConnectedTo]([VideoFrame](../videoframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setStartShapeConnectedTo]([PictureFrame](../pictureframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setStartShapeConnectedTo]([ZoomFrame](../zoomframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setStartShapeConnectedTo]([AutoShape](../autoshape)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setStartShapeConnectedTo]([OleObjectFrame](../oleobjectframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setStartShapeConnectedTo]([SectionZoomFrame](../sectionzoomframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setStartShapeConnectedTo]([AudioFrame](../audioframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setStartShapeConnectedTo]([Chart](../chart)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setStartShapeConnectedTo]([Table](../table)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setStartShapeConnectedTo]([SummaryZoomFrame](../summaryzoomframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


| [setStartShapeConnectionSiteIndex](long) | Returns or sets the index of connection site for start shape. Read/write long. |

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when value is less than StartShapeConnectedTo.ConnectionSiteCount |


---


