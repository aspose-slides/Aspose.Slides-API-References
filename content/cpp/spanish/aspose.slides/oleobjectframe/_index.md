---
title: OleObjectFrame
second_title: Referencia de la API de Aspose.Slides para C++
description: Representa un objeto OLE en una diapositiva.
type: docs
weight: 4603
url: /es/aspose.slides/oleobjectframe/
---
## OleObjectFrame clase

Representa un objeto OLE en una diapositiva.

```cpp
class OleObjectFrame : public Aspose::Slides::GraphicalObject,
                       public Aspose::Slides::IOleObjectFrame
```

## Métodos

| Método | Descripción |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | Agrega un nuevo marcador de posición si no existe y establece las propiedades del marcador de posición a una especificada. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales a pesar de que, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales a pesar de que, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | Devuelve el texto alternativo asociado a una forma. Lea [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | Devuelve el título del texto alternativo asociado a una forma. Lea [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | La propiedad especifica cómo se representará una forma en modo de visualización en blanco y negro. Lea [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | Devuelve el número de puntos de conexión en la forma. Solo lectura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | Devuelve los datos personalizados de la forma. Solo lectura [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | Devuelve el objeto [EffectFormat](../effectformat/) que contiene los efectos de píxel aplicados a una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de efecto. Solo lectura [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() override | Obtiene información sobre los datos OLE incrustados. Lea [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/). |
| [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() override | Devuelve el nombre de archivo del objeto OLE incrustado. |
| [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() override | Devuelve la ruta del objeto OLE incrustado. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | Devuelve el objeto [FillFormat](../fillformat/) que contiene las propiedades de formato de relleno para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de relleno. Solo lectura [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | Devuelve las propiedades del marco de la forma. Lea [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | Devuelve los bloqueos de la forma. Solo lectura [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | Obtiene la altura de la forma, medida en puntos. Solo lectura **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | Determina si la forma está oculta. Solo lectura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | Devuelve el hipervínculo definido para hacer clic con el ratón. Lea [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | Devuelve el gestor de hipervínculos. Solo lectura [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | Devuelve el hipervínculo definido para pasar el ratón por encima. Lea [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | Obtiene la opción 'Marcar como decorativo' Lectura/escritura **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | Determina si la forma está agrupada. Solo lectura **bool**. |
| **bool** [get_IsObjectIcon](./get_isobjecticon/)() override | Determina si un objeto es visible como ícono. Solo lectura **bool**. |
| **bool** [get_IsObjectLink](./get_isobjectlink/)() override | Determina si un objeto está enlazado a un archivo externo. Solo lectura **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | Determina si la forma es TextHolder_PPT. Solo lectura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | Devuelve el objeto [LineFormat](../lineformat/) que contiene las propiedades de formato de línea para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades de línea. Solo lectura [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() override | Devuelve la ruta completa a un archivo vinculado. Se usará el nombre corto del archivo. Solo lectura [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | Devuelve la ruta completa a un archivo vinculado. Se usará el nombre largo del archivo. Lea [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() override | Devuelve la ruta relativa a un archivo vinculado si está presente, de lo contrario devuelve una cadena vacía. Solo lectura [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | Devuelve el nombre de una forma. No debe ser nulo. Use una cadena vacía si es necesario. Lea [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() override | Devuelve el nombre de un objeto. Lea [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() override | Devuelve el ProgID de un objeto. Solo lectura [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | Devuelve un identificador único de alcance de diapositiva que permanece constante durante la vida útil de la forma y permite que PowerPoint o código interop lo referencie de forma fiable desde cualquier lugar del documento. Solo lectura **uint32_t**. Ver también [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | Devuelve el objeto [GroupShape](../groupshape/) padre si la forma está agrupada. De lo contrario devuelve null. Solo lectura [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | Devuelve el marcador de posición para una forma. Devuelve null si la forma no tiene marcador de posición. Solo lectura [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | Devuelve la presentación padre de una diapositiva. Solo lectura [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | Devuelve las propiedades sin procesar del marco de la forma. Lea [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | Devuelve el número de grados que la forma especificada está rotada alrededor del eje z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario. Solo lectura **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | Devuelve los bloqueos de la forma. Solo lectura [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | Devuelve la diapositiva padre de una forma. Solo lectura [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() override | Devuelve el objeto de propiedades de relleno de imagen OleObject. Solo lectura [IPictureFillFormat](../ipicturefillformat/). |
| [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() override | Devuelve el título para el ícono OleObject. Lea [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | Devuelve el objeto [ThreeDFormat](../threedformat/) que contiene las propiedades de efecto 3D para una forma. Nota: puede devolver null para ciertos tipos de formas que no tienen propiedades 3D. Solo lectura [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | Devuelve un identificador interno de alcance de presentación destinado al uso de complementos u otro código. Debido a que este valor puede ser reasignado por el usuario o programáticamente, no debe tratarse como una clave única persistente. Solo lectura **uint32_t**. Ver también [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **bool** [get_UpdateAutomatic](./get_updateautomatic/)() override | Determina si el objeto incrustado enlazado se actualiza automáticamente cuando la presentación se abre o imprime. Solo lectura **bool**. |
| **float** [get_Width](../shape/get_width/)() override | Obtiene el ancho de la forma, medido en puntos. Solo lectura **float**. |
| **float** [get_X](../shape/get_x/)() override | Obtiene la coordenada x de la esquina superior izquierda de la forma, medida en puntos. Solo lectura **float**. |
| **float** [get_Y](../shape/get_y/)() override | Obtiene la coordenada y de la esquina superior izquierda de la forma, medida en puntos. Solo lectura **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | Devuelve la posición de una forma en el orden z. Shapes[0] devuelve la forma que está al fondo del orden z, y Shapes[Shapes.Count - 1] devuelve la forma que está al frente del orden z. Solo lectura **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | Devuelve una forma de marcador de posición básica (forma del diseño y/o diapositiva maestra de la que la forma actual hereda). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | Devuelve la miniatura de la forma. El tipo de límites de la miniatura de forma [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) se usa por defecto. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | Devuelve la miniatura de la forma. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | Obtiene los límites visuales de la forma calculados a partir de su contenido renderizado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llámenos directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción de copias de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | Define que esta forma no es un marcador de posición. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | Establece el texto alternativo asociado a una forma. Escriba [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | Establece el título del texto alternativo asociado a una forma. Escriba [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | La propiedad especifica cómo se representará una forma en modo de visualización en blanco y negro. Escriba [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Establece las propiedades del marco de la forma. Escriba [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | Establece la altura de la forma, medida en puntos. Escriba **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | Determina si la forma está oculta. Escriba **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Establece el hipervínculo definido para hacer clic con el ratón. Escriba [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | Establece el hipervínculo definido para pasar el ratón por encima. Escriba [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | Establece la opción 'Marcar como decorativo' Lectura/escritura **bool**. |
| void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) override | Determina si un objeto es visible como ícono. Escriba **bool**. |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | Devuelve la ruta completa a un archivo vinculado. Se usará el nombre largo del archivo. Escriba [System::String](../../system/string/). |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | Establece el nombre de una forma. No debe ser nulo. Use una cadena vacía si es necesario. Escriba [System::String](../../system/string/). |
| void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) override | Establece el nombre de un objeto. Escriba [System::String](../../system/string/). |
| void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) override | Devuelve el ProgID de un objeto. Solo lectura [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Establece las propiedades sin procesar del marco de la forma. Escriba [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | Establece el número de grados que la forma especificada está rotada alrededor del eje z. Un valor positivo indica rotación en sentido horario; un valor negativo indica rotación en sentido antihorario. Escriba **float**. |
| void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) override | Establece el título para el ícono OleObject. Escriba [System::String](../../system/string/). |
| void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) override | Determina si el objeto incrustado enlazado se actualiza automáticamente cuando la presentación se abre o imprime. Escriba **bool**. |
| void [set_Width](../shape/set_width/)(**float**) override | Establece el ancho de la forma, medido en puntos. Escriba **float**. |
| void [set_X](../shape/set_x/)(**float**) override | Establece la coordenada x de la esquina superior izquierda de la forma, medida en puntos. Escriba **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | Establece la coordenada y de la esquina superior izquierda de la forma, medida en puntos. Escriba **float**. |
| void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) override | Establece la información sobre los datos OLE incrustados. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | Guarda el contenido de [Shape](../shape/) como archivo SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | Guarda el contenido de [Shape](../shape/) como archivo SVG. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Comentarios

El siguiente ejemplo muestra cómo acceder a los marcos de objetos OLE.

```cpp
// Carga el archivo PPTX a un objeto de presentación
auto pres = System::MakeObject<Presentation>(u"AccessingOLEObjectFrame.pptx");

// Accede a la primera diapositiva
auto slide = pres->get_Slides()->idx_get(0);
// Convierte la forma a OleObjectFrame
System::SharedPtr<OleObjectFrame> oleObjectFrame = System::AsCast<OleObjectFrame>(slide->get_Shapes()->idx_get(0));
// Lee el objeto OLE y lo escribe en disco
if (oleObjectFrame != nullptr)
{
    // Obtiene los datos del archivo incrustado
    System::ArrayPtr<uint8_t> data = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileData();
    // Obtiene la extensión del archivo incrustado
    System::String fileExtention = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileExtension();
    // Crea una ruta para guardar el archivo extraído
    System::String extractedPath = System::String(u"excelFromOLE_out") + fileExtention;
    // Guarda los datos extraídos
    auto stream = System::MakeObject<System::IO::FileStream>(extractedPath,
                                                             System::IO::FileMode::Create,
                                                             System::IO::FileAccess::Write);
    stream->Write(data, 0, data->get_Length());
}
```

## Ver también

* Clase [GraphicalObject](../graphicalobject/)
* Clase [IOleObjectFrame](../ioleobjectframe/)
* Espacio de nombres [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)