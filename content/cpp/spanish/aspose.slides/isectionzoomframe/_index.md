---
title: ISectionZoomFrame
second_title: Referencia de API de Aspose.Slides para C++
description: Representa un objeto Section Zoom en una diapositiva.
type: docs
weight: 3602
url: /es/aspose.slides/isectionzoomframe/
---
## ISectionZoomFrame clase


Representa un objeto Zoom [Section](../section/) en una diapositiva.

```cpp
class ISectionZoomFrame : public virtual Aspose::Slides::IZoomObject
```

## Métodos

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Agrega un nuevo marcador de posición si no hay ninguno y establece las propiedades del marcador de posición a uno especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Devuelve el texto alternativo asociado a una forma. Consulte [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Devuelve el título del texto alternativo asociado a una forma. Consulte [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | La propiedad especifica cómo se mostrará una forma en modo de visualización en blanco y negro. Consulte [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Devuelve el número de puntos de conexión en la forma. Solo lectura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Devuelve los datos personalizados de la forma. Solo lectura [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Devuelve el objeto [EffectFormat](../effectformat/) que contiene los efectos de píxel aplicados a una forma. Solo lectura [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Devuelve el objeto [FillFormat](../fillformat/) que contiene las propiedades de formato de relleno para una forma. Solo lectura [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Devuelve las propiedades del marco de la forma. Consulte [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | Devuelve los bloqueos de la forma. Solo lectura [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | Obtiene la altura de la forma, medida en puntos. Solo lectura **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Determina si la forma está oculta. Solo lectura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Devuelve el hipervínculo definido para clic del ratón. Consulte [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Administrador de hipervínculos. Solo lectura [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Devuelve el hipervínculo definido para pasar el ratón por encima. Consulte [IHyperlink](../ihyperlink/). |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](../izoomobject/get_imagetype/)() | Obtiene el tipo de imagen de un objeto zoom. Consulte [ZoomImageType](../zoomimagetype/). Valor predeterminado: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Obtiene la opción 'Mark as decorative'. Lectura/escritura **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Determina si la forma está agrupada. Solo lectura **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Determina si la forma es TextHolder. Solo lectura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Devuelve el objeto [LineFormat](../lineformat/) que contiene las propiedades de formato de línea para una forma. Solo lectura [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Devuelve el nombre de una forma. Consulte [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Devuelve un identificador único de alcance de diapositiva que permanece constante durante la vida útil de la forma y permite que PowerPoint o el código de interop la referencie de forma fiable desde cualquier parte del documento. Solo lectura **uint32_t**. Vea también [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Devuelve el objeto padre [GroupShape](../groupshape/) si la forma está agrupada. De lo contrario devuelve null. Solo lectura [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Devuelve el marcador de posición para una forma. Solo lectura [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Devuelve la presentación. Solo lectura [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Devuelve las propiedades crudas del marco de la forma. Consulte [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_ReturnToParent](../izoomobject/get_returntoparent/)() | Obtiene el comportamiento de navegación en la presentación. Solo lectura **bool**. Valor predeterminado: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Devuelve el número de grados que la forma especificada está girada alrededor del eje z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario. Solo lectura **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Devuelve los bloqueos de la forma. Solo lectura [IBaseShapeLock](../ibaseshapelock/). |
| virtual **bool** [get_ShowBackground](../izoomobject/get_showbackground/)() | Obtiene el valor que especifica si el Zoom utilizará el fondo de la diapositiva de destino. Solo lectura **bool**. Valor predeterminado: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Devuelve la diapositiva base. Solo lectura [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](./get_targetsection/)() | Obtiene el objeto de sección al que está vinculado el objeto Zoom [Section](../section/). Consulte [ISection](../isection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Devuelve el objeto [ThreeDFormat](../threedformat/) que contiene las propiedades de formato de línea para una forma. Solo lectura [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TransitionDuration](../izoomobject/get_transitionduration/)() | Obtiene la duración de la transición entre Zoom y diapositiva. Solo lectura **float**. Valor predeterminado: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Devuelve un identificador interno de alcance de presentación destinado a ser usado por complementos u otro código. Como este valor puede ser reasignado por el usuario o programáticamente, no debe tratarse como una clave única persistente. Solo lectura **uint32_t**. Vea también [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | Obtiene la anchura de la forma, medida en puntos. Solo lectura **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Obtiene la coordenada x de la esquina superior izquierda de la forma, medida en puntos. Solo lectura **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Obtiene la coordenada y de la esquina superior izquierda de la forma, medida en puntos. Solo lectura **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../izoomobject/get_zoomimage/)() | Obtiene la imagen para el objeto zoom. Consulte [IPPImage](../ippimage/). |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Devuelve la posición de una forma en el orden z. Shapes[0] devuelve la forma al fondo del orden z, y Shapes[Shapes.Count - 1] devuelve la forma al frente del orden z. Solo lectura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la que hereda la forma actual). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Devuelve la miniatura de la forma. El tipo de límites de miniatura de forma [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) se usa por defecto. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Devuelve la miniatura de la forma. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Analogo de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica si el objeto representa una instancia del tipo descrito por targetType. Analogo del operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa la instrucción lock() de C# bloqueando. Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, realmente, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, realmente, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Define que esta forma no es un marcador de posición. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Establece el texto alternativo asociado a una forma. Escribe [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Establece el título del texto alternativo asociado a una forma. Escribe [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | La propiedad especifica cómo se mostrará una forma en modo de visualización en blanco y negro. Escribe [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Establece las propiedades del marco de la forma. Escribe [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Establece la altura de la forma, medida en puntos. Escribe **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Determina si la forma está oculta. Escribe **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Establece el hipervínculo definido para clic del ratón. Escribe [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Establece el hipervínculo definido para pasar el ratón por encima. Escribe [IHyperlink](../ihyperlink/). |
| virtual void [set_ImageType](../izoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) | Establece el tipo de imagen de un objeto zoom. Escribe [ZoomImageType](../zoomimagetype/). Valor predeterminado: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Establece la opción 'Mark as decorative'. Lectura/escritura **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Establece el nombre de una forma. Escribe [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Establece las propiedades crudas del marco de la forma. Escribe [IShapeFrame](../ishapeframe/). |
| virtual void [set_ReturnToParent](../izoomobject/set_returntoparent/)(**bool**) | Establece el comportamiento de navegación en la presentación. Escribe **bool**. Valor predeterminado: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Establece el número de grados que la forma especificada está girada alrededor del eje z. Un valor positivo indica rotación horaria; un valor negativo indica rotación antihoraria. Escribe **float**. |
| virtual void [set_ShowBackground](../izoomobject/set_showbackground/)(**bool**) | Establece el valor que especifica si el Zoom usará el fondo de la diapositiva de destino. Escribe **bool**. Valor predeterminado: true |
| virtual void [set_TargetSection](./set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) | Establece el objeto de sección al que está vinculado el objeto Zoom [Section](../section/). Escribe [ISection](../isection/). |
| virtual void [set_TransitionDuration](../izoomobject/set_transitionduration/)(**float**) | Establece la duración de la transición entre Zoom y diapositiva. Escribe **float**. Valor predeterminado: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Establece la anchura de la forma, medida en puntos. Escribe **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos. Escribe **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos. Escribe **float**. |
| virtual void [set_ZoomImage](../izoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | Establece la imagen para el objeto zoom. Escribe [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa la instrucción lock() de C# desbloqueando. Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Guarda el contenido de [Shape](../shape/) como archivo SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Guarda el contenido de [Shape](../shape/) como archivo SVG. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |
## Ver también

* Clase [IZoomObject](../izoomobject/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)