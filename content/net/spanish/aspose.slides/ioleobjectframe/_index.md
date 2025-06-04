---  
title: IOleObjectFrame
second_title: Aspose.Sildes for .NET API Reference  
description: Representa un objeto OLE en una diapositiva.
type: docs  
weight: 6340  
url: /es/aspose.slides/ioleobjectframe/
---  

## Interfaz IOleObjectFrame  

Representa un objeto OLE en una diapositiva.  

```csharp  
public interface IOleObjectFrame : IGraphicalObject  
```  

## Propiedades  

| Nombre | Descripción |  
| --- | --- |  
| [AsIGraphicalObject](../../aspose.slides/ioleobjectframe/asigraphicalobject) { get; } | Permite obtener la interfaz base IGraphicalObject. Solo lectura [`IGraphicalObject`](../igraphicalobject). |  
| [EmbeddedData](../../aspose.slides/ioleobjectframe/embeddeddata) { get; } | Obtiene información sobre los datos OLE incrustados. Solo lectura [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |  
| [EmbeddedFileLabel](../../aspose.slides/ioleobjectframe/embeddedfilelabel) { get; } | Devuelve el nombre del archivo del objeto OLE incrustado |  
| [EmbeddedFileName](../../aspose.slides/ioleobjectframe/embeddedfilename) { get; } | Devuelve la ruta del objeto OLE incrustado |  
| [IsObjectIcon](../../aspose.slides/ioleobjectframe/isobjecticon) { get; set; } | Determina si un objeto es visible como icono. Booleano de lectura/escritura. |  
| [IsObjectLink](../../aspose.slides/ioleobjectframe/isobjectlink) { get; } | Determina si un objeto está vinculado a un archivo externo. Booleano de solo lectura. |  
| [LinkFileName](../../aspose.slides/ioleobjectframe/linkfilename) { get; } | Devuelve la ruta completa a un archivo vinculado. Se utilizará el nombre de archivo corto. Cadena de solo lectura. |  
| [LinkPathLong](../../aspose.slides/ioleobjectframe/linkpathlong) { get; set; } | Devuelve la ruta completa a un archivo vinculado. Se utilizará el nombre de archivo largo. Cadena de lectura/escritura. |  
| [LinkPathRelative](../../aspose.slides/ioleobjectframe/linkpathrelative) { get; } | Devuelve la ruta relativa a un archivo vinculado si está presente; de lo contrario, devuelve una cadena vacía. Cadena de solo lectura. |  
| [ObjectName](../../aspose.slides/ioleobjectframe/objectname) { get; set; } | Devuelve o establece el nombre de un objeto. Cadena de lectura/escritura. |  
| [ObjectProgId](../../aspose.slides/ioleobjectframe/objectprogid) { get; set; } | Devuelve el ProgID de un objeto. Cadena de solo lectura. |  
| [SubstitutePictureFormat](../../aspose.slides/ioleobjectframe/substitutepictureformat) { get; } | Devuelve el objeto de propiedades de imagen de relleno de OleObject. Solo lectura [`IPictureFillFormat`](../ipicturefillformat). |  
| [SubstitutePictureTitle](../../aspose.slides/ioleobjectframe/substitutepicturetitle) { get; set; } | Devuelve o establece el título para el icono de OleObject. Cadena de lectura/escritura. |  
| [UpdateAutomatic](../../aspose.slides/ioleobjectframe/updateautomatic) { get; set; } | Determina si el objeto incrustado vinculado se actualiza automáticamente cuando se abre o imprime la presentación. Booleano de lectura/escritura. |  

## Métodos  

| Nombre | Descripción |  
| --- | --- |  
| [SetEmbeddedData](../../aspose.slides/ioleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Establece información sobre los datos OLE incrustados. |  

### Ver También  

* interfaz [IGraphicalObject](../igraphicalobject)  
* espacio de nombres [Aspose.Slides](../../aspose.slides)  
* ensamblaje [Aspose.Slides](../../)  

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->