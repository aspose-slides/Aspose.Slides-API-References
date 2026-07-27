---
title: AudioFrame
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa un clip de audio en una diapositiva.
type: docs
weight: 53
url: /es/aspose.slides/audioframe/
---
## AudioFrame clase

Representa un clip de audio en una diapositiva.

```cpp
class AudioFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IAudioFrame
```

## Methods

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Agrega un nuevo marcador de posición si no existe y establece las propiedades del marcador de posición a uno especificado. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | Crea y devuelve una matriz de los elementos de la forma. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C#, donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C#, donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | Devuelve el valor de ajuste de una forma en el índice especificado. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | Devuelve una colección de valores de ajuste de la forma. Solo lectura [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Devuelve el texto alternativo asociado a una forma. Lectura [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Devuelve el título del texto alternativo asociado a una forma. Lectura [System::String](../../system/string/). |
| **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() override | Devuelve el índice del último rastro. Lectura **int32_t**. |
| **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() override | Devuelve el tiempo del último rastro. Lectura **int32_t**. |
| **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() override | Devuelve el índice del rastro de inicio. Lectura **int32_t**. |
| **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() override | Devuelve el tiempo del rastro de inicio. Lectura **int32_t**. |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | La propiedad especifica cómo se renderizará una forma en modo de visualización en blanco y negro. Lectura [Slides::BlackWhiteMode](../blackwhitemode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | Obtiene la colección de subtítulos cerrados asociados con el marco de audio. Esta propiedad es solo lectura y devuelve un [ICaptionsCollection](../icaptionscollection/) que contiene todas las pistas de subtítulos. |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Devuelve el número de sitios de conexión en la forma. Solo lectura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Devuelve los datos personalizados de la forma. Solo lectura [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Devuelve el objeto [EffectFormat](../effectformat/) que contiene los efectos de píxel aplicados a una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de efecto. Solo lectura [IEffectFormat](../ieffectformat/). |
| **bool** [get_Embedded](./get_embedded/)() override | Determina si un sonido está incrustado en una presentación. Solo lectura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() override | Devuelve el objeto de audio incrustado. Lectura [IAudio](../iaudio/). |
| **float** [get_FadeInDuration](./get_fadeinduration/)() override | Especifica la duración en tiempo del fundido de entrada inicial de los medios en milisegundos. Lectura **float**. |
| **float** [get_FadeOutDuration](./get_fadeoutduration/)() override | Especifica la duración en tiempo del fundido de salida final de los medios en milisegundos. Lectura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Devuelve el objeto [FillFormat](../fillformat/) que contiene las propiedades de formato de relleno para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de relleno. Solo lectura [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Devuelve las propiedades del marco de la forma. Lectura [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | Obtiene la altura de la forma, medida en puntos. Lectura **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Determina si la forma está oculta. Lectura **bool**. |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | Determina si un [AudioFrame](./) está oculto. Lectura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Devuelve el hipervínculo definido para clic del ratón. Lectura [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Devuelve el gestor de hipervínculos. Solo lectura [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Devuelve el hipervínculo definido para pasar el ratón por encima. Lectura [IHyperlink](../ihyperlink/). |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | Determina si el [PictureFrame](../pictureframe/) es un objeto Cameo o no. Solo lectura **bool**. |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Obtiene la opción 'Marcar como decorativo' Lectura/escritura **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Determina si la forma está agrupada. Solo lectura **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Determina si la forma es TextHolder_PPT. Solo lectura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Devuelve el objeto [LineFormat](../lineformat/) que contiene las propiedades de formato de línea para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de línea. Solo lectura [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | Devuelve el nombre de un archivo de audio que está enlazado a un [AudioFrame](./). Lectura [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Devuelve el nombre de una forma. No debe ser null. Use una cadena vacía si es necesario. Lectura [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Devuelve un identificador único con alcance de diapositiva que permanece constante durante la vida de la forma y permite que PowerPoint o código interop la referencie de forma fiable desde cualquier parte del documento. Solo lectura **uint32_t**. Ver también [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Devuelve el objeto [GroupShape](../groupshape/) padre si la forma está agrupada. De lo contrario devuelve null. Solo lectura [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | Devuelve el objeto [PictureFillFormat](../picturefillformat/) para un marco de imagen. Solo lectura [IPictureFillFormat](../ipicturefillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | Devuelve los bloqueos de la forma. Solo lectura [IPictureFrameLock](../ipictureframelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Devuelve el marcador de posición para una forma. Devuelve null si la forma no tiene marcador de posición. Solo lectura [IPlaceholder](../iplaceholder/). |
| **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() override | Determina si el audio se reproduce a través de las diapositivas. Lectura **bool**. |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | Determina si un audio está en bucle. Lectura **bool**. |
| [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() override | Devuelve el modo de reproducción de audio. Lectura [AudioPlayModePreset](../audioplaymodepreset/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Devuelve la presentación padre de una diapositiva. Solo lectura [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Devuelve las propiedades brutas del marco de la forma. Lectura [IShapeFrame](../ishapeframe/). |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | Devuelve la escala de altura (relativa al tamaño original de la imagen) del marco de la imagen. El valor 1.0 corresponde al 100 %. Lectura **float**. |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | Devuelve la escala de ancho (relativa al tamaño original de la imagen) del marco de la imagen. El valor 1.0 corresponde al 100 %. Lectura **float**. |
| **bool** [get_RewindAudio](./get_rewindaudio/)() override | Determina si el audio se rebobina automáticamente al inicio después de reproducirse. Lectura **bool**. |
| **float** [get_Rotation](../shape/get_rotation/)() override | Devuelve el número de grados que la forma especificada está rotada alrededor del eje z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario. Lectura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Devuelve los bloqueos de la forma. Solo lectura [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | Devuelve el objeto de estilo de la forma. Solo lectura [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Devuelve la diapositiva padre de una forma. Solo lectura [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Devuelve el objeto [ThreeDFormat](../threedformat/) que contiene las propiedades de efecto 3D para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades 3D. Solo lectura [IThreeDFormat](../ithreedformat/). |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | Especifica la duración de tiempo que se eliminará del final del medio durante la reproducción, en milisegundos. Lectura **float**. |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | Especifica la duración de tiempo que se eliminará del principio del medio durante la reproducción, en milisegundos. Lectura **float**. |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Devuelve un identificador interno con alcance de presentación destinado al uso por complementos u otro código. Debido a que este valor puede ser reasignado por el usuario o programáticamente, no debe tratarse como una clave única persistente. Solo lectura **uint32_t**. Ver también [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | Devuelve el volumen de audio. Lectura [AudioVolumeMode](../audiovolumemode/). |
| **float** [get_VolumeValue](./get_volumevalue/)() override | Devuelve el volumen de audio en porcentajes. Lectura **float**. |
| **float** [get_Width](../shape/get_width/)() override | Obtiene el ancho de la forma, medido en puntos. Lectura **float**. |
| **float** [get_X](../shape/get_x/)() override | Obtiene la coordenada x de la esquina superior izquierda de la forma, medida en puntos. Lectura **float**. |
| **float** [get_Y](../shape/get_y/)() override | Obtiene la coordenada y de la esquina superior izquierda de la forma, medida en puntos. Lectura **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Devuelve la posición de una forma en el orden Z. Shapes[0] devuelve la forma al fondo del orden Z, y Shapes[Shapes.Count - 1] devuelve la forma al frente del orden Z. Solo lectura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la que hereda la forma actual). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | Devuelve una copia de la ruta de la forma geométrica. Las coordenadas son relativas a la esquina superior izquierda de la forma. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite generar hashes de objetos personalizados. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Devuelve la miniatura de la forma. El tipo de límites de miniatura [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) se usa por defecto. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Devuelve la miniatura de la forma. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Define que esta forma no es un marcador de posición. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Establece el texto alternativo asociado a una forma. Escritura [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Establece el título del texto alternativo asociado a una forma. Escritura [System::String](../../system/string/). |
| void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) override | Establece el índice del último rastro. Escritura **int32_t**. |
| void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) override | Establece el tiempo del último rastro. Escritura **int32_t**. |
| void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) override | Establece el índice del rastro de inicio. Escritura **int32_t**. |
| void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) override | Establece el tiempo del rastro de inicio. Escritura **int32_t**. |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | La propiedad especifica cómo se renderizará una forma en modo de visualización en blanco y negro. Escritura [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | Establece el objeto de audio incrustado. Escritura [IAudio](../iaudio/). |
| void [set_FadeInDuration](./set_fadeinduration/)(**float**) override | Especifica la duración en tiempo del fundido de entrada inicial de los medios en milisegundos. Escritura **float**. |
| void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) override | Especifica la duración en tiempo del fundido de salida final de los medios en milisegundos. Escritura **float**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Establece las propiedades del marco de la forma. Escritura [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Establece la altura de la forma, medida en puntos. Escritura **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Determina si la forma está oculta. Escritura **bool**. |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | Determina si un [AudioFrame](./) está oculto. Escritura **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Establece el hipervínculo definido para clic del ratón. Escritura [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Establece el hipervínculo definido para pasar el ratón por encima. Escritura [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Establece la opción 'Marcar como decorativo' Lectura/escritura **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | Establece el nombre de un archivo de audio que está enlazado a un [AudioFrame](./). Escritura [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Establece el nombre de una forma. No debe ser null. Use una cadena vacía si es necesario. Escritura [System::String](../../system/string/). |
| void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) override | Determina si el audio se reproduce a través de las diapositivas. Escritura **bool**. |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | Determina si un audio está en bucle. Escritura **bool**. |
| void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) override | Establece el modo de reproducción de audio. Escritura [AudioPlayModePreset](../audioplaymodepreset/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Establece las propiedades brutas del marco de la forma. Escritura [IShapeFrame](../ishapeframe/). |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | Establece la escala de altura (relativa al tamaño original de la imagen) del marco de la imagen. El valor 1.0 corresponde al 100 %. Escritura **float**. |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | Establece la escala de ancho (relativa al tamaño original de la imagen) del marco de la imagen. El valor 1.0 corresponde al 100 %. Escritura **float**. |
| void [set_RewindAudio](./set_rewindaudio/)(**bool**) override | Determina si el audio se rebobina automáticamente al inicio después de reproducirse. Escritura **bool**. |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Establece el número de grados que la forma especificada está rotada alrededor del eje z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario. Escritura **float**. |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | Especifica la duración en tiempo que se eliminará del final del medio durante la reproducción, en milisegundos. Escritura **float**. |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | Especifica la duración en tiempo que se eliminará del principio del medio durante la reproducción, en milisegundos. Escritura **float**. |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | Establece el volumen de audio. Escritura [AudioVolumeMode](../audiovolumemode/). |
| void [set_VolumeValue](./set_volumevalue/)(**float**) override | Establece el volumen de audio en porcentajes. Escritura **float**. |
| void [set_Width](../shape/set_width/)(**float**) override | Establece el ancho de la forma, medido en puntos. Escritura **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos. Escritura **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos. Escritura **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | Actualiza la geometría de la forma a partir del objeto [IGeometryPath](../igeometrypath/). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ([ShapeType](../shapetype/)) a [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | Actualiza la geometría de la forma a partir de una matriz de [IGeometryPath](../igeometrypath/). Las coordenadas deben ser relativas a la esquina superior izquierda de la forma. Cambia el tipo de la forma ([ShapeType](../shapetype/)) a [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el argumento de plantilla n-ésimo como puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Guarda el contenido de [Shape](../shape/) como archivo SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Guarda el contenido de [Shape](../shape/) como archivo SVG. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |
## Observaciones

Los siguientes ejemplos muestran cómo cambiar las Opciones de Reproducción de [Audio](../audio/).

```cpp
auto pres = System::MakeObject<Presentation>(u"AudioFrameEmbed_out.pptx");

// Gets the AudioFrame shape
System::SharedPtr<AudioFrame> audioFrame = System::ExplicitCast<AudioFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
// Sets the Play mode to play on click
audioFrame->set_PlayMode(AudioPlayModePreset::OnClick);
// Sets the volume to Low
audioFrame->set_Volume(AudioVolumeMode::Low);
// Sets the audio to play across slides
audioFrame->set_PlayAcrossSlides(true);
// Disables loop for the audio
audioFrame->set_PlayLoopMode(false);
// Hides the AudioFrame during the slide show
audioFrame->set_HideAtShowing(true);
// Rewinds the audio to start after playing
audioFrame->set_RewindAudio(true);
// Saves the PowerPoint file to disk
pres->Save(u"AudioFrameEmbed_changed.pptx", SaveFormat::Pptx);
```

## Ver también

* Clase [PictureFrame](../pictureframe/)
* Clase [IAudioFrame](../iaudioframe/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)