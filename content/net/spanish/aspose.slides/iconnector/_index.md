---  
title: IConnector
second_title: Aspose.Slides para .NET Referencia de API  
description: Representa un conector.
type: docs
weight: 5410  
url: /es/aspose.slides/iconnector/
---  

## Interfaz IConnector  

Representa un conector.  

```csharp  
public interface IConnector : IGeometryShape  
```  

## Propiedades  

| Nombre | Descripción |  
| --- | --- |  
| [AsIGeometryShape](../../aspose.slides/iconnector/asigeometryshape) { get; } | Permite obtener la interfaz base IGeometryShape. Solo lectura [`IGeometryShape`](../igeometryshape). |  
| [ConnectorLock](../../aspose.slides/iconnector/connectorlock) { get; } | Devuelve los bloqueos del conector. Solo lectura [`IConnectorLock`](../iconnectorlock). |  
| [EndShapeConnectedTo](../../aspose.slides/iconnector/endshapeconnectedto) { get; set; } | Devuelve o establece la forma a la que se adjunta el extremo del conector. Lectura/escritura [`IShape`](../ishape). |  
| [EndShapeConnectionSiteIndex](../../aspose.slides/iconnector/endshapeconnectionsiteindex) { get; set; } | Devuelve o establece el índice del sitio de conexión para la forma final. Lectura/escritura UInt32. |  
| [ShapeLock](../../aspose.slides/iconnector/shapelock) { get; } | Devuelve los bloqueos de la forma. Solo lectura [`IConnectorLock`](../iconnectorlock). |  
| [StartShapeConnectedTo](../../aspose.slides/iconnector/startshapeconnectedto) { get; set; } | Devuelve o establece la forma a la que se adjunta el principio del conector. Lectura/escritura [`IShape`](../ishape). |  
| [StartShapeConnectionSiteIndex](../../aspose.slides/iconnector/startshapeconnectionsiteindex) { get; set; } | Devuelve o establece el índice del sitio de conexión para la forma inicial. Lectura/escritura UInt32. |  

## Métodos  

| Nombre | Descripción |  
| --- | --- |  
| [Reroute](../../aspose.slides/iconnector/reroute)() | Redirige el conector para que tome el camino más corto posible entre las formas que conecta. |  

### Ver También  

* interfaz [IGeometryShape](../igeometryshape)  
* espacio de nombres [Aspose.Slides](../../aspose.slides)  
* ensamblaje [Aspose.Slides](../../)  

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->  