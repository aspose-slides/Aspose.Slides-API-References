---
title: Connector
second_title: Referencia de API de Aspose.Slides para C++
description: Representa un conector.
type: docs
weight: 482
url: /es/aspose.slides/connector/
---
## Connector clase

Representa un conector.

```cpp
class Connector : public Aspise::Slides::GeometryShape,
                  public Aspise::Slides::IConnector
```

## Métodos

| Método | Descripción |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Agrega un nuevo marcador de posición si no existe y establece las propiedades del marcador de posición a una especificada. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Crea y devuelve una matriz de los elementos de la forma. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Devuelve el valor de ajuste de una forma en el índice especificado. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Devuelve una colección de valores de ajuste de la forma. Solo lectura [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Devuelve el texto alternativo asociado a una forma. Lectura [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Devuelve el título del texto alternativo asociado a una forma. Lectura [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | La propiedad especifica cómo se renderiza una forma en modo de visualización en blanco y negro. Lectura [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Devuelve el número de puntos de conexión en la forma. Solo lectura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IConnectorLock](../iconnectorlock/)\> [get_ConnectorLock](./get_connectorlock/)() override | Devuelve los bloqueos del conector. Solo lectura [IConnectorLock](../iconnectorlock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Devuelve los datos personalizados de la forma. Solo lectura [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Devuelve el objeto [EffectFormat](../effectformat/) que contiene los efectos de píxel aplicados a una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de efecto. Solo lectura [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_EndShapeConnectedTo](./get_endshapeconnectedto/)() override | Devuelve la forma a la que se adjunta el extremo del conector. Lectura [IShape](../ishape/). |
| **uint32_t** [get_EndShapeConnectionSiteIndex](./get_endshapeconnectionsiteindex/)() override | Devuelve el índice del punto de conexión para la forma final. Lectura **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Devuelve el objeto [FillFormat](../fillformat/) que contiene las propiedades de formato de relleno para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de relleno. Solo lectura [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Devuelve las propiedades del marco de la forma. Lectura [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Obtiene la altura de la forma, medida en puntos. Lectura **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Determina si la forma está oculta. Lectura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Devuelve el hipervínculo definido para clic del ratón. Lectura [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Devuelve el administrador de hipervínculos. Solo lectura [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Devuelve el hipervínculo definido para pasar el ratón por encima. Lectura [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Obtiene la opción 'Marcar como decorativo' Lectura/escritura **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Determina si la forma está agrupada. Solo lectura **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Determina si la forma es TextHolder_PPT. Solo lectura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Devuelve el objeto [LineFormat](../lineformat/) que contiene las propiedades de formato de línea para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de línea. Solo lectura [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Devuelve el nombre de una forma. No debe ser null. Use una cadena vacía si es necesario. Lectura [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Devuelve un identificador único con alcance de diapositiva que permanece constante durante la vida de la forma y permite que PowerPoint o el código interop lo referencie de manera fiable desde cualquier parte del documento. Solo lectura **uint32_t**. Véase también [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Devuelve el objeto [GroupShape](../groupshape/) padre si la forma está agrupada. De lo contrario, devuelve null. Solo lectura [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Devuelve el marcador de posición de una forma. Devuelve null si la forma no tiene marcador de posición. Solo lectura [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Devuelve la presentación padre de una diapositiva. Solo lectura [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Devuelve las propiedades del marco de forma sin procesar. Lectura [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | Devuelve el número de grados que la forma especificada está rotada alrededor del eje z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario. Lectura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Devuelve los bloqueos de la forma. Solo lectura [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Devuelve el objeto de estilo de la forma. Solo lectura [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](./get_shapetype/)() override | Devuelve el tipo [AutoShape](../autoshape/). Lectura [Slides::ShapeType](../shapetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Devuelve la diapositiva padre de una forma. Solo lectura [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_StartShapeConnectedTo](./get_startshapeconnectedto/)() override | Devuelve la forma a la que se adjunta el comienzo del conector. Lectura [IShape](../ishape/). |
| **uint32_t** [get_StartShapeConnectionSiteIndex](./get_startshapeconnectionsiteindex/)() override | Devuelve el índice del punto de conexión para la forma inicial. Lectura **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Devuelve el objeto [ThreeDFormat](../threedformat/) que contiene las propiedades de efecto 3D para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades 3D. Solo lectura [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Devuelve un identificador interno, con alcance de presentación, destinado al uso por complementos u otro código. Como este valor puede ser reasignado por el usuario o programáticamente, no debe considerarse una clave única persistente. Solo lectura **uint32_t**. Véase también [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | Obtiene el ancho de la forma, medido en puntos. Lectura **float**. |
| **float** [get_X](../shape/get_x/)() override | Obtiene la coordenada x de la esquina superior izquierda de la forma, medida en puntos. Lectura **float**. |
| **float** [get_Y](../shape/get_y/)() override | Obtiene la coordenada y de la esquina superior izquierda de la forma, medida en puntos. Lectura **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Devuelve la posición de una forma en el orden z. Shapes[0] devuelve la forma al fondo del orden z, y Shapes[Shapes.Count - 1] devuelve la forma al frente del orden z. Solo lectura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Devuelve una forma marcador de posición básica (forma del diseño y/o diapositiva maestra de la que la forma actual hereda). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Devuelve la copia de la ruta de la forma geométrica. Las coordenadas son relativas a la esquina superior izquierda de la forma. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita el hash de objetos personalizados. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Devuelve la miniatura de la forma. El tipo de límites de miniatura de forma [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) se usa por defecto. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Devuelve la miniatura de la forma. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita la clonación de tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Define que esta forma no es un marcador de posición. |
| void [Reroute](./reroute/)() override | Redirige el conector para que tome la ruta más corta posible entre las formas que conecta. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Establece el texto alternativo asociado a una forma. Escritura [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Establece el título del texto alternativo asociado a una forma. Escritura [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | La propiedad especifica cómo se renderiza una forma en modo de visualización en blanco y negro. Escritura [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_EndShapeConnectedTo](./set_endshapeconnectedto/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | Establece la forma a la que se adjunta el extremo del conector. Escritura [IShape](../ishape/). |
| void [set_EndShapeConnectionSiteIndex](./set_endshapeconnectionsiteindex/)(**uint32_t**) override | Establece el índice del punto de conexión para la forma final. Escritura **uint32_t**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Establece las propiedades del marco de la forma. Escritura [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Establece la altura de la forma, medida en puntos. Escritura **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Determina si la forma está oculta. Escritura **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Establece el hipervínculo definido para clic del ratón. Escritura [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Establece el hipervínculo definido para pasar el ratón por encima. Escritura [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Establece la opción 'Marcar como decorativo' Lectura/escritura **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Establece el nombre de una forma. No debe ser null. Use una cadena vacía si es necesario. Escritura [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Establece las propiedades del marco de forma sin procesar. Escritura [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Establece el número de grados que la forma especificada está rotada alrededor del eje z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario. Escritura **float**. |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override | Establece el tipo [AutoShape](../autoshape/). Escritura [Slides::ShapeType](../shapetype/). |
| void [set_StartShapeConnectedTo](./set_startshapeconnectedto/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | Establece la forma a la que se adjunta el comienzo del conector. Escritura [IShape](../ishape/). |
| void [set_StartShapeConnectionSiteIndex](./set_startshapeconnectionsiteindex/)(**uint32_t**) override | Establece el índice del punto de conexión para la forma inicial. Escritura **uint32_t**. |
| void [set_Width](../shape/set_width/)(**float**) override | Establece el ancho de la forma, medido en puntos. Escritura **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos. Escritura **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos. Escritura **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Actualiza la geometría de la forma a partir del objeto [IGeometryPath](../igeometrypath/). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ([ShapeType](../shapetype/)) a [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Actualiza la geometría de la forma a partir de una matriz de [IGeometryPath](../igeometrypath/). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ([ShapeType](../shapetype/)) a [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Habilita la conversión de objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llámese directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Guarda el contenido de [Shape](../shape/) como archivo SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Guarda el contenido de [Shape](../shape/) como archivo SVG. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [GeometryShape](../geometryshape/)
* Clase [IConnector](../iconnector/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)