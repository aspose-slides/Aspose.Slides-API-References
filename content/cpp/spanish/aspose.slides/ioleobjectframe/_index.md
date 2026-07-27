---
title: IOleObjectFrame
second_title: Referencia de API de Aspose.Slides para C++
description: Representa un objeto OLE en una diapositiva.
type: docs
weight: 3095
url: /es/aspose.slides/ioleobjectframe/
---
## IOleObjectFrame clase

Representa un objeto OLE en una diapositiva.

```cpp
class IOleObjectFrame : public virtual Aspose::Slides::IGraphicalObject
```

## Métodos

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Agrega un nuevo marcador de posición si no existe y establece las propiedades del marcador de posición a una especificada. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Devuelve el texto alternativo asociado a una forma. Lea [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Devuelve el título del texto alternativo asociado a una forma. Lea [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | La propiedad especifica cómo se renderizará una forma en modo de pantalla en blanco y negro. Lea [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Devuelve el número de puntos de conexión en la forma. Solo lectura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Devuelve los datos personalizados de la forma. Solo lectura [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Devuelve el objeto [EffectFormat](../effectformat/) que contiene los efectos de píxel aplicados a una forma. Solo lectura [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() | Obtiene información sobre los datos incrustados OLE. Solo lectura [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/). |
| virtual [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() | Devuelve el nombre de archivo del objeto OLE incrustado |
| virtual [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() | Devuelve la ruta del objeto OLE incrustado |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Devuelve el objeto [FillFormat](../fillformat/) que contiene las propiedades de formato de relleno para una forma. Solo lectura [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Devuelve las propiedades del marco de la forma. Lea [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | Devuelve los bloqueos de la forma. Solo lectura [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Obtiene la altura de la forma, medida en puntos. Solo lectura **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Determina si la forma está oculta. Solo lectura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Devuelve el hipervínculo definido para el clic del ratón. Lea [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Administrador de hipervínculos. Solo lectura [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Devuelve el hipervínculo definido para pasar el ratón por encima. Lea [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Obtiene la opción 'Marcar como decorativo'. Lectura/escritura **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Determina si la forma está agrupada. Solo lectura **bool**. |
| virtual **bool** [get_IsObjectIcon](./get_isobjecticon/)() | Determina si un objeto es visible como ícono. Solo lectura **bool**. |
| virtual **bool** [get_IsObjectLink](./get_isobjectlink/)() | Determina si un objeto está vinculado a un archivo externo. Solo lectura **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Determina si la forma es TextHolder. Solo lectura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Devuelve el objeto [LineFormat](../lineformat/) que contiene las propiedades de formato de línea para una forma. Solo lectura [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() | Devuelve la ruta completa a un archivo vinculado. Se usará el nombre de archivo corto. Solo lectura [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | Devuelve la ruta completa a un archivo vinculado. Se usará el nombre de archivo largo. Lea [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() | Devuelve la ruta relativa a un archivo vinculado si está presente, de lo contrario devuelve una cadena vacía. Solo lectura [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Devuelve el nombre de una forma. Lea [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() | Devuelve el nombre de un objeto. Lea [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() | Devuelve el ProgID de un objeto. Solo lectura [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Devuelve un identificador único con alcance de diapositiva que permanece constante durante la vida útil de la forma y permite que PowerPoint o el código de interoperabilidad referencien la forma de forma fiable desde cualquier parte del documento. Solo lectura **uint32_t**. Vea también [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Devuelve el objeto padre [GroupShape](../groupshape/) si la forma está agrupada. De lo contrario devuelve null. Solo lectura [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Devuelve el marcador de posición para una forma. Solo lectura [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Devuelve la presentación. Solo lectura [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Devuelve las propiedades del marco de forma sin procesar. Lea [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Devuelve el número de grados que la forma especificada está rotada alrededor del eje z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario. Solo lectura **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Devuelve los bloqueos de la forma. Solo lectura [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Devuelve la diapositiva base. Solo lectura [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() | Devuelve el objeto de propiedades de relleno de imagen OleObject. Solo lectura [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() | Devuelve el título para el ícono OleObject. Lea [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Devuelve el objeto [ThreeDFormat](../threedformat/) que contiene las propiedades de formato de línea para una forma. Solo lectura [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Devuelve un identificador interno con alcance de presentación destinado al uso por complementos u otro código. Como este valor puede ser reasignado por el usuario o programáticamente, no debe tratarse como una clave única persistente. Solo lectura **uint32_t**. Vea también [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **bool** [get_UpdateAutomatic](./get_updateautomatic/)() | Determina si el objeto incrustado vinculado se actualiza automáticamente cuando la presentación se abre o se imprime. Solo lectura **bool**. |
| virtual **float** [get_Width](../ishape/get_width/)() | Obtiene el ancho de la forma, medido en puntos. Solo lectura **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Obtiene la coordenada x de la esquina superior izquierda de la forma, medida en puntos. Solo lectura **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Obtiene la coordenada y de la esquina superior izquierda de la forma, medida en puntos. Solo lectura **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Devuelve la posición de una forma en el orden Z. Shapes[0] devuelve la forma en la parte posterior del orden Z, y Shapes[Shapes.Count - 1] devuelve la forma en la parte frontal del orden Z. Solo lectura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la que la forma actual hereda). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Devuelve la miniatura de la forma. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) tipo de límites de miniatura de forma se usa por defecto. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Devuelve la miniatura de la forma. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo del operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, en realidad, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Define que esta forma no es un marcador de posición. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Establece el texto alternativo asociado a una forma. Escriba [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Establece el título del texto alternativo asociado a una forma. Escriba [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | La propiedad especifica cómo se renderizará una forma en modo de pantalla en blanco y negro. Escriba [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Establece las propiedades del marco de la forma. Escriba [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Establece la altura de la forma, medida en puntos. Escriba **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Establece si la forma está oculta. Escriba **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Establece el hipervínculo definido para el clic del ratón. Escriba [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Establece el hipervínculo definido para pasar el ratón por encima. Escriba [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Establece la opción 'Marcar como decorativo'. Lectura/escritura **bool**. |
| virtual void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) | Determina si un objeto es visible como ícono. Escriba **bool**. |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | Devuelve la ruta completa a un archivo vinculado. Se usará el nombre de archivo largo. Escriba [System::String](../../system/string/). |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Establece el nombre de una forma. Escriba [System::String](../../system/string/). |
| virtual void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) | Establece el nombre de un objeto. Escriba [System::String](../../system/string/). |
| virtual void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) | Devuelve el ProgID de un objeto. Solo lectura [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Establece las propiedades del marco de forma sin procesar. Escriba [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Establece el número de grados que la forma especificada está rotada alrededor del eje z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario. Escriba **float**. |
| virtual void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) | Establece el título para el ícono OleObject. Escriba [System::String](../../system/string/). |
| virtual void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) | Determina si el objeto incrustado vinculado se actualiza automáticamente cuando la presentación se abre o se imprime. Escriba **bool**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Establece el ancho de la forma, medido en puntos. Escriba **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos. Escriba **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos. Escriba **float**. |
| virtual void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) | Establece información sobre los datos incrustados OLE. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Guarda el contenido de [Shape](../shape/) como archivo SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Guarda el contenido de [Shape](../shape/) como archivo SVG. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |
## Ver también

* Clase [IGraphicalObject](../igraphicalobject/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)