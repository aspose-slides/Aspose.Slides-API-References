---
title: Connector
type: docs
weight: 0
url: /php-java/connector/
---

# Connector class

  Represents a connector.
 

## Methods

| name | return type | description |
| --- | --- | --- |
| [getConnectorLock](/slides/php-java/connector/getconnectorlock/)() | IConnectorLock | Returns connector's locks. Read-only IConnectorLock. |
| [getEndShapeConnectedTo](/slides/php-java/connector/getendshapeconnectedto/)() | IShape | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |
| [getEndShapeConnectionSiteIndex](/slides/php-java/connector/getendshapeconnectionsiteindex/)() | long | Returns or sets the index of connection site for end shape. Read/write long. |
| [getShapeLock](/slides/php-java/connector/getshapelock/)() | IConnectorLock | Returns shape's locks. Read-only IConnectorLock. |
| [getShapeType](/slides/php-java/connector/getshapetype/)() | int | Returns or sets the AutoShape type. Read/write ShapeType. |
| [getStartShapeConnectedTo](/slides/php-java/connector/getstartshapeconnectedto/)() | IShape | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |
| [getStartShapeConnectionSiteIndex](/slides/php-java/connector/getstartshapeconnectionsiteindex/)() | long | Returns or sets the index of connection site for start shape. Read/write long. |
| [reroute](/slides/php-java/connector/reroute/)() | void | Reroutes connector so that it take the shortest possible path between the shapes it connect. |
| [setEndShapeConnectedTo](/slides/php-java/connector/setendshapeconnectedto/)(IShape) | void | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |
| [setEndShapeConnectionSiteIndex](/slides/php-java/connector/setendshapeconnectionsiteindex/)(long) | void | Returns or sets the index of connection site for end shape. Read/write long. |
| [setShapeType](/slides/php-java/connector/setshapetype/)(int) | void | Returns or sets the AutoShape type. Read/write ShapeType. |
| [setStartShapeConnectedTo](/slides/php-java/connector/setstartshapeconnectedto/)(IShape) | void | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |
| [setStartShapeConnectionSiteIndex](/slides/php-java/connector/setstartshapeconnectionsiteindex/)(long) | void | Returns or sets the index of connection site for start shape. Read/write long. |
