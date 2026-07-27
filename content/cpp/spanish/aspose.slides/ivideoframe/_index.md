---
title: IVideoFrame
second_title: Referencia de API de Aspose.Slides para C++
description: Representa un clip de video en una diapositiva.
type: docs
weight: 4226
url: /es/aspose.slides/ivideoframe/
---
## IVideoFrame clase

Representa un clip de video en una diapositiva.

```cpp
class IVideoFrame : public virtual Aspose::Slides::IPictureFrame
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | Agrega un nuevo marcador de posición si no hay ninguno y establece las propiedades del marcador de posición a una especificada. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | Crea y devuelve una matriz de los elementos de la forma. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para fines internos. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | Devuelve el valor de ajuste de la forma en el índice especificado. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | Devuelve una colección de valores de ajuste de la forma. Solo lectura [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Devuelve el texto alternativo asociado a una forma. Lectura [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Devuelve el título del texto alternativo asociado a una forma. Lectura [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | La propiedad especifica cómo se representará una forma en modo de pantalla en blanco y negro. Lectura [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() | Obtiene la colección de subtítulos cerrados asociados al fotograma de audio. Esta propiedad es solo lectura y devuelve un [ICaptionsCollection](../icaptionscollection/) que contiene todas las pistas de subtítulos. |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | Devuelve el número de puntos de conexión en la forma. Solo lectura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | Devuelve los datos personalizados de la forma. Solo lectura [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | Devuelve el objeto [EffectFormat](../effectformat/) que contiene los efectos de píxel aplicados a una forma. Solo lectura [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_EmbeddedVideo](./get_embeddedvideo/)() | Devuelve el objeto de video incrustado. Lectura [IVideo](../ivideo/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | Devuelve el objeto [FillFormat](../fillformat/) que contiene las propiedades de formato de relleno para una forma. Solo lectura [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | Devuelve las propiedades del marco de la forma. Lectura [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_FullScreenMode](./get_fullscreenmode/)() | Determina si un video se muestra en modo pantalla completa. Lectura **bool**. |
| virtual **float** [get_Height](../ishape/get_height/)() | Obtiene la altura de la forma, medida en puntos. Lectura **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | Determina si la forma está oculta. Lectura **bool**. |
| virtual **bool** [get_HideAtShowing](./get_hideatshowing/)() | Determina si un [VideoFrame](../videoframe/) está oculto. Lectura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Devuelve el hipervínculo definido para clic del ratón. Lectura [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Gestor de hipervínculos Solo lectura [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Devuelve el hipervínculo definido para pasar el ratón por encima. Lectura [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | Obtiene la opción 'Marcar como decorativo' Lectura/escritura **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | Determina si la forma está agrupada. Solo lectura **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | Determina si la forma es TextHolder. Solo lectura **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | Devuelve el objeto [LineFormat](../lineformat/) que contiene las propiedades de formato de línea para una forma. Solo lectura [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | Devuelve el nombre de un archivo de video que está vinculado a un [VideoFrame](../videoframe/). Lectura [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Devuelve el nombre de una forma. Lectura [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | Devuelve un identificador único con alcance de diapositiva que permanece constante durante la vida de la forma y permite que PowerPoint o el código de interoperabilidad referencien la forma de forma fiable desde cualquier parte del documento. Solo lectura **uint32_t**. Ver también [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | Devuelve el objeto padre [GroupShape](../groupshape/) si la forma está agrupada. De lo contrario devuelve null. Solo lectura [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../ipictureframe/get_pictureformat/)() | Devuelve el objeto [PictureFillFormat](../picturefillformat/) para un marco de imagen. Solo lectura [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../ipictureframe/get_pictureframelock/)() | Devuelve los bloqueos de [PictureFrame](../pictureframe/). Solo lectura [IPictureFrameLock](../ipictureframelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | Devuelve el marcador de posición para una forma. Solo lectura [IPlaceholder](../iplaceholder/). |
| virtual **bool** [get_PlayLoopMode](./get_playloopmode/)() | Determina si un video está en bucle. Lectura **bool**. |
| virtual [VideoPlayModePreset](../videoplaymodepreset/) [get_PlayMode](./get_playmode/)() | Devuelve el modo de reproducción del video. Lectura [VideoPlayModePreset](../videoplaymodepreset/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Devuelve la presentación. Solo lectura [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | Devuelve las propiedades sin procesar del marco de la forma. Lectura [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_RelativeScaleHeight](../ipictureframe/get_relativescaleheight/)() | Devuelve la escala de la altura (relativa al tamaño original de la imagen) del marco de imagen. El valor 1.0 corresponde al 100%. Lectura **float**. |
| virtual **float** [get_RelativeScaleWidth](../ipictureframe/get_relativescalewidth/)() | Devuelve la escala del ancho (relativa al tamaño original de la imagen) del marco de imagen. El valor 1.0 corresponde al 100%. Lectura **float**. |
| virtual **bool** [get_RewindVideo](./get_rewindvideo/)() | Determina si un video se rebobina automáticamente al inicio tan pronto como la película ha terminado de reproducirse. Lectura **bool**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | Devuelve el número de grados que la forma especificada está girada alrededor del eje z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario. Lectura **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | Devuelve los bloqueos de la forma. Solo lectura [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | Devuelve el objeto de estilo de la forma. Solo lectura [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | Devuelve el tipo de preajuste de geometría. Nota: al cambiar el valor, todos los valores de ajuste se restablecerán a sus valores predeterminados. Lectura [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Devuelve la diapositiva base. Solo lectura [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | Devuelve el objeto [ThreeDFormat](../threedformat/) que contiene las propiedades de formato de línea para una forma. Solo lectura [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TrimFromEnd](./get_trimfromend/)() | Recorte final [ms] |
| virtual **float** [get_TrimFromStart](./get_trimfromstart/)() | Recorte inicial [ms] |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | Devuelve un identificador interno con alcance de presentación destinado al uso por complementos u otro código. Debido a que este valor puede ser reasignado por el usuario o programáticamente, no debe tratarse como una clave única persistente. Solo lectura **uint32_t**. Ver también [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() | Devuelve el volumen del audio. Lectura [AudioVolumeMode](../audiovolumemode/). |
| virtual **float** [get_Width](../ishape/get_width/)() | Obtiene el ancho de la forma, medido en puntos. Lectura **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | Obtiene la coordenada x de la esquina superior izquierda de la forma, medida en puntos. Lectura **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | Obtiene la coordenada y de la esquina superior izquierda de la forma, medida en puntos. Lectura **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Devuelve la posición de una forma en el orden z. Shapes[0] devuelve la forma al fondo del orden z, y Shapes[Shapes.Count - 1] devuelve la forma al frente del orden z. Solo lectura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la que la forma actual hereda). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | Devuelve una copia de la ruta de la forma de geometría. Las coordenadas son relativas a la esquina superior izquierda de la forma. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Devuelve la miniatura de la forma. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) forma de límites de miniatura se usa por defecto. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Devuelve la miniatura de la forma. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Analógico de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Analógico del operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llamar directamente o usar [LockContext](../../system/lockcontext/) centinela. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. Realmente no copia nada, solo inicializa un nuevo objeto y permite la copia de construcción de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. Realmente no copia nada, solo inicializa un nuevo objeto y permite la copia de construcción de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | Define que esta forma no es un marcador de posición. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | Establece el texto alternativo asociado a una forma. Escritura [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | Establece el título del texto alternativo asociado a una forma. Escritura [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | La propiedad especifica cómo se representará una forma en modo de pantalla en blanco y negro. Escritura [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_EmbeddedVideo](./set_embeddedvideo/)([System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\>) | Establece el objeto de video incrustado. Escritura [IVideo](../ivideo/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Establece las propiedades del marco de la forma. Escritura [IShapeFrame](../ishapeframe/). |
| virtual void [set_FullScreenMode](./set_fullscreenmode/)(**bool**) | Determina si un video se muestra en modo pantalla completa. Escritura **bool**. |
| virtual void [set_Height](../ishape/set_height/)(**float**) | Establece la altura de la forma, medida en puntos. Escritura **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | Determina si la forma está oculta. Escritura **bool**. |
| virtual void [set_HideAtShowing](./set_hideatshowing/)(**bool**) | Determina si un [VideoFrame](../videoframe/) está oculto. Escritura **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Establece el hipervínculo definido para clic del ratón. Escritura [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | Establece el hipervínculo definido para pasar el ratón por encima. Escritura [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | Establece la opción 'Marcar como decorativo' Lectura/escritura **bool**. |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | Establece el nombre de un archivo de video que está vinculado a un [VideoFrame](../videoframe/). Escritura [System::String](../../system/string/). |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | Establece el nombre de una forma. Escritura [System::String](../../system/string/). |
| virtual void [set_PlayLoopMode](./set_playloopmode/)(**bool**) | Determina si un video está en bucle. Escritura **bool**. |
| virtual void [set_PlayMode](./set_playmode/)([VideoPlayModePreset](../videoplaymodepreset/)) | Establece el modo de reproducción del video. Escritura [VideoPlayModePreset](../videoplaymodepreset/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | Establece las propiedades sin procesar del marco de la forma. Escritura [IShapeFrame](../ishapeframe/). |
| virtual void [set_RelativeScaleHeight](../ipictureframe/set_relativescaleheight/)(**float**) | Establece la escala de la altura (relativa al tamaño original de la imagen) del marco de imagen. El valor 1.0 corresponde al 100%. Escritura **float**. |
| virtual void [set_RelativeScaleWidth](../ipictureframe/set_relativescalewidth/)(**float**) | Establece la escala del ancho (relativa al tamaño original de la imagen) del marco de imagen. El valor 1.0 corresponde al 100%. Escritura **float**. |
| virtual void [set_RewindVideo](./set_rewindvideo/)(**bool**) | Determina si un video se rebobina automáticamente al inicio tan pronto como la película ha terminado de reproducirse. Escritura **bool**. |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | Establece el número de grados que la forma especificada está girada alrededor del eje z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario. Escritura **float**. |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | Establece el tipo de preajuste de geometría. Nota: al cambiar el valor, todos los valores de ajuste se restablecerán a sus valores predeterminados. Escritura [Slides::ShapeType](../shapetype/). |
| virtual void [set_TrimFromEnd](./set_trimfromend/)(**float**) | Recorte final [ms] |
| virtual void [set_TrimFromStart](./set_trimfromstart/)(**float**) | Recorte inicial [ms] |
| virtual void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) | Establece el volumen del audio. Escritura [AudioVolumeMode](../audiovolumemode/). |
| virtual void [set_Width](../ishape/set_width/)(**float**) | Establece el ancho de la forma, medido en puntos. Escritura **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | Establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos. Escritura **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | Establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos. Escritura **float**. |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | Actualiza la geometría de la forma a partir del objeto [IGeometryPath](../igeometrypath/). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ([ShapeType](../shapetype/)) a [ShapeType::Custom](../shapetype/). |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | Actualiza la geometría de la forma a partir de una matriz de [IGeometryPath](../igeometrypath/). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ([ShapeType](../shapetype/)) a [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llamar directamente o usar [LockContext](../../system/lockcontext/) centinela. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | Guarda el contenido de [Shape](../shape/) como archivo SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Guarda el contenido de [Shape](../shape/) como archivo SVG. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [IPictureFrame](../ipictureframe/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)