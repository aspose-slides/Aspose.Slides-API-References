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
| [getConnectorLock](/php-java/connector/getconnectorlock/)() | IConnectorLock | Returns connector's locks. Read-only IConnectorLock. |
| [getEndShapeConnectedTo](/php-java/connector/getendshapeconnectedto/)() | IShape | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |
| [getEndShapeConnectionSiteIndex](/php-java/connector/getendshapeconnectionsiteindex/)() | long | Returns or sets the index of connection site for end shape. Read/write long. |
| [getShapeLock](/php-java/connector/getshapelock/)() | IConnectorLock | Returns shape's locks. Read-only IConnectorLock. |
| [getShapeType](/php-java/connector/getshapetype/)() | int | Returns or sets the AutoShape type. Read/write ShapeType. |
| [getStartShapeConnectedTo](/php-java/connector/getstartshapeconnectedto/)() | IShape | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |
| [getStartShapeConnectionSiteIndex](/php-java/connector/getstartshapeconnectionsiteindex/)() | long | Returns or sets the index of connection site for start shape. Read/write long. |
| [reroute](/php-java/connector/reroute/)() | void | Reroutes connector so that it take the shortest possible path between the shapes it connect. |
| [setEndShapeConnectedTo](/php-java/connector/setendshapeconnectedto/)(IShape) | void | Returns or sets the shape to attach the end of the connector to. Read/write IShape. |
| [setEndShapeConnectionSiteIndex](/php-java/connector/setendshapeconnectionsiteindex/)(long) | void | Returns or sets the index of connection site for end shape. Read/write long. |
| [setShapeType](/php-java/connector/setshapetype/)(int) | void | Returns or sets the AutoShape type. Read/write ShapeType. |
| [setStartShapeConnectedTo](/php-java/connector/setstartshapeconnectedto/)(IShape) | void | Returns or sets the shape to attach the beginning of the connector to. Read/write IShape. |
| [setStartShapeConnectionSiteIndex](/php-java/connector/setstartshapeconnectionsiteindex/)(long) | void | Returns or sets the index of connection site for start shape. Read/write long. |
