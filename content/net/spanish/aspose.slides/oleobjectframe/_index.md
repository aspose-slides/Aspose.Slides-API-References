---
title: OleObjectFrame
second_title: Aspose.Sildes for .NET API Reference
description: Representa un objeto OLE en una diapositiva.
type: docs
weight: 8960
url: /es/aspose.slides/oleobjectframe/
---

## OleObjectFrame class

Representa un objeto OLE en una diapositiva.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Properties

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Devuelve o establece el texto alternativo asociado a una forma. Lectura/escritura String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Devuelve o establece el título del texto alternativo asociado a una forma. Lectura/escritura String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Permite obtener la interfaz base IGraphicalObject. Solo lectura [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | La propiedad especifica cómo se renderizará una forma en modo de visualización en blanco y negro. Lectura/escritura [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Devuelve el número de sitios de conexión en la forma. Solo lectura Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Devuelve los datos personalizados de la forma. Solo lectura [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Devuelve el objeto EffectFormat que contiene efectos de píxel aplicados a una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de efecto. Solo lectura [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Obtiene o establece información sobre datos OLE incrustados. Lectura/escritura [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Devuelve el nombre del archivo del objeto OLE incrustado |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Devuelve la ruta del objeto OLE incrustado |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Devuelve el objeto FillFormat que contiene propiedades de formato de relleno para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de relleno. Solo lectura [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Devuelve o establece las propiedades del marco de la forma. Lectura/escritura [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Devuelve los bloqueos de la forma. Solo lectura [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Devuelve o establece la altura de la forma. Lectura/escritura Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina si la forma está oculta. Lectura/escritura Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Devuelve o establece el hipervínculo definido para el clic del mouse. Lectura/escritura [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Devuelve el administrador de hipervínculos. Solo lectura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Devuelve o establece el hipervínculo definido para el mouse sobre. Lectura/escritura [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtiene o establece la opción 'Marcar como decorativa' Lectura/escritura Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina si la forma está agrupada. Solo lectura Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Determina si un objeto es visible como ícono. Lectura/escritura Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Determina si un objeto está vinculado a un archivo externo. Solo lectura Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina si la forma es TextHolder_PPT. Solo lectura Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Devuelve el objeto LineFormat que contiene propiedades de formato de línea para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de línea. Solo lectura [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Devuelve la ruta completa a un archivo vinculado. Se utilizará el nombre de archivo corto. Solo lectura String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Devuelve la ruta completa a un archivo vinculado. Se utilizará el nombre de archivo largo. Lectura/escritura String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | Devuelve la ruta relativa a un archivo vinculado si está presente, de lo contrario devuelve una cadena vacía. Solo lectura String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Devuelve o establece el nombre de una forma. No debe ser nulo. Utilice una cadena vacía si es necesario. Lectura/escritura String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Devuelve o establece el nombre de un objeto. Lectura/escritura String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Devuelve el ProgID de un objeto. Solo lectura String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Obtiene el identificador único de la forma en el ámbito de la diapositiva. Solo lectura UInt32. Véase también [`UniqueId`](../shape/uniqueid) para obtener el identificador único de la forma en el ámbito de la presentación. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Devuelve el objeto GroupShape padre si la forma está agrupada. De lo contrario, devuelve null. Solo lectura [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Devuelve el marcador para una forma. Devuelve null si la forma no tiene marcador. Solo lectura [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Devuelve la presentación padre de una diapositiva. Solo lectura [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Devuelve o establece las propiedades del marco de forma sin procesar. Lectura/escritura [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Devuelve o establece el número de grados que la forma especificada está rotada alrededor del eje z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario. Lectura/escritura Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Devuelve los bloqueos de la forma. Solo lectura [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 propiedades) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Devuelve la diapositiva padre de una forma. Solo lectura [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Devuelve el objeto de propiedades de relleno de imagen OleObject. Solo lectura [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Devuelve o establece el título para el ícono de OleObject. Lectura/escritura String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Devuelve el objeto ThreeDFormat que contiene propiedades de efecto 3D para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades 3D. Solo lectura [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Obtiene el identificador único de la forma en el ámbito de la presentación. Solo lectura UInt32. Véase también [`OfficeInteropShapeId`](../shape/officeinteropshapeid) para obtener el identificador único de la forma en el ámbito de la diapositiva. |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Determina si el objeto incrustado vinculado se actualiza automáticamente cuando se abre o imprime la presentación. Lectura/escritura Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Devuelve o establece el ancho de la forma. Lectura/escritura Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Devuelve o establece la coordenada x de la esquina superior izquierda de la forma. Lectura/escritura Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Devuelve o establece la coordenada y de la esquina superior izquierda de la forma. Lectura/escritura Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Devuelve la posición de una forma en el orden z. Shapes[0] devuelve la forma en la parte trasera del orden z, y Shapes[Shapes.Count - 1] devuelve la forma en la parte delantera del orden z. Solo lectura Int32. |

## Methods

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Agrega un nuevo marcador si no hay ninguno y establece las propiedades del marcador a uno especificado. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Devuelve una forma de marcador básica (forma del diseño y/o diapositiva maestra de la que se hereda la forma actual). Se devuelve null si la forma actual no se hereda. |
| [GetImage](../../aspose.slides/shape/getimage)() | Devuelve la miniatura de la forma. El tipo de límites de miniatura de la forma ShapeThumbnailBounds es utilizado por defecto. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Devuelve la miniatura de la forma. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Define que esta forma no es un marcador. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Establece información sobre datos OLE incrustados. Este método cambia las propiedades del objeto para reflejar los nuevos datos y establece la bandera IsObjectLink en falso, indicando que el objeto OLE está incrustado. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Guarda el contenido de la forma como un archivo SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Guarda el contenido de la forma como un archivo SVG. |

### Examples

El siguiente ejemplo muestra cómo acceder a los marcos de objetos OLE.

```csharp
[C#]
// Carga el PPTX en un objeto de presentación
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // Accede a la primera diapositiva
    ISlide sld = pres.Slides[0];
    // Convierte la forma a OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // Lee el objeto OLE y lo escribe en el disco
    if (oleObjectFrame != null)
    {
        // Obtiene los datos del archivo incrustado
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Obtiene la extensión del archivo incrustado
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // Crea una ruta para guardar el archivo extraído
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // Guarda los datos extraídos
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### See Also

* class [GraphicalObject](../graphicalobject)
* interface [IOleObjectFrame](../ioleobjectframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->