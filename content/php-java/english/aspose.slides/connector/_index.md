---
title: Connector
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs

url: /aspose.slides/connector/
---

## Connector class

  Represents a connector.
 
### getConnectorLock {#getConnectorLock}

| Name | Description |
| --- | --- |
| getConnectorLock () | Returns connector's locks. Read-only IConnectorLock. |

 **Returns:**
[ConnectorLock](../connectorlock)


---


### getEndShapeConnectedTo {#getEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| getEndShapeConnectedTo () | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
[Connector](../connector), [GraphicalObject](../graphicalobject), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [GeometryShape](../geometryshape), [SummaryZoomFrame](../summaryzoomframe), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [SectionZoomFrame](../sectionzoomframe), [PictureFrame](../pictureframe), [AudioFrame](../audioframe), [Chart](../chart), [LegacyDiagram](../legacydiagram), [ZoomObject](../zoomobject)

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### getEndShapeConnectionSiteIndex {#getEndShapeConnectionSiteIndex}

| Name | Description |
| --- | --- |
| getEndShapeConnectionSiteIndex () | Returns or sets the index of connection site for end shape. Read/write long. |

 **Returns:**
long

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when value is less than EndShapeConnectedTo.ConnectionSiteCount |


---


### getShapeLock {#getShapeLock}

| Name | Description |
| --- | --- |
| getShapeLock () | Returns shape's locks. Read-only IConnectorLock. |

 **Returns:**
[ConnectorLock](../connectorlock)


---


### getShapeType {#getShapeType}

| Name | Description |
| --- | --- |
| getShapeType () | Returns or sets the AutoShape type. Read/write ShapeType. |

 **Returns:**
int


---


### getStartShapeConnectedTo {#getStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| getStartShapeConnectedTo () | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
[Connector](../connector), [GraphicalObject](../graphicalobject), [Shape](../shape), [SmartArtShape](../smartartshape), [Table](../table), [Ink](../ink), [GeometryShape](../geometryshape), [SummaryZoomFrame](../summaryzoomframe), [SummaryZoomSection](../summaryzoomsection), [ZoomFrame](../zoomframe), [OleObjectFrame](../oleobjectframe), [VideoFrame](../videoframe), [SmartArt](../smartart), [GroupShape](../groupshape), [InkActions](../inkactions), [AutoShape](../autoshape), [SectionZoomFrame](../sectionzoomframe), [PictureFrame](../pictureframe), [AudioFrame](../audioframe), [Chart](../chart), [LegacyDiagram](../legacydiagram), [ZoomObject](../zoomobject)

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### getStartShapeConnectionSiteIndex {#getStartShapeConnectionSiteIndex}

| Name | Description |
| --- | --- |
| getStartShapeConnectionSiteIndex () | Returns or sets the index of connection site for start shape. Read/write long. |

 **Returns:**
long

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when value is less than StartShapeConnectedTo.ConnectionSiteCount |


---


### reroute {#reroute}

| Name | Description |
| --- | --- |
| reroute () | Reroutes connector so that it take the shortest possible path between the shapes it connect. |

 **Returns:**
void


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([Connector](../connector)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([GraphicalObject](../graphicalobject)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([Shape](../shape)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([SmartArtShape](../smartartshape)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([Table](../table)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([Ink](../ink)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([GeometryShape](../geometryshape)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([SummaryZoomFrame](../summaryzoomframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([SummaryZoomSection](../summaryzoomsection)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([ZoomFrame](../zoomframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([OleObjectFrame](../oleobjectframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([VideoFrame](../videoframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([SmartArt](../smartart)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([GroupShape](../groupshape)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([InkActions](../inkactions)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([AutoShape](../autoshape)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([SectionZoomFrame](../sectionzoomframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([PictureFrame](../pictureframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([AudioFrame](../audioframe)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([Chart](../chart)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([LegacyDiagram](../legacydiagram)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectedTo {#setEndShapeConnectedTo}

| Name | Description |
| --- | --- |
| setEndShapeConnectedTo ([ZoomObject](../zoomobject)) | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setEndShapeConnectionSiteIndex {#setEndShapeConnectionSiteIndex}

| Name | Description |
| --- | --- |
| setEndShapeConnectionSiteIndex (long) | Returns or sets the index of connection site for end shape. Read/write long. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when value is less than EndShapeConnectedTo.ConnectionSiteCount |


---


### setShapeType {#setShapeType}

| Name | Description |
| --- | --- |
| setShapeType (int) | Returns or sets the AutoShape type. Read/write ShapeType. |

 **Returns:**
void


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([Connector](../connector)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([GraphicalObject](../graphicalobject)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([Shape](../shape)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([SmartArtShape](../smartartshape)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([Table](../table)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([Ink](../ink)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([GeometryShape](../geometryshape)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([SummaryZoomFrame](../summaryzoomframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([SummaryZoomSection](../summaryzoomsection)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([ZoomFrame](../zoomframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([OleObjectFrame](../oleobjectframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([VideoFrame](../videoframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([SmartArt](../smartart)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([GroupShape](../groupshape)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([InkActions](../inkactions)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([AutoShape](../autoshape)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([SectionZoomFrame](../sectionzoomframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([PictureFrame](../pictureframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([AudioFrame](../audioframe)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([Chart](../chart)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([LegacyDiagram](../legacydiagram)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectedTo {#setStartShapeConnectedTo}

| Name | Description |
| --- | --- |
| setStartShapeConnectedTo ([ZoomObject](../zoomobject)) | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when connected shape doesn't has any connection sites (IShape.ConnectionSiteCount equals zero) |


---


### setStartShapeConnectionSiteIndex {#setStartShapeConnectionSiteIndex}

| Name | Description |
| --- | --- |
| setStartShapeConnectionSiteIndex (long) | Returns or sets the index of connection site for start shape. Read/write long. |

 **Returns:**
void

 **Exception**

| Error | Condition |
| --- | --- |
 | ArgumentException | Thrown when value is less than StartShapeConnectedTo.ConnectionSiteCount |


---


