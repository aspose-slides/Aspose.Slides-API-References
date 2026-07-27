---
title: ISVGOptions
second_title: Referencia de API de Aspose.Slides para C++
description: Representa opciones SVG.
type: docs
weight: 404
url: /es/aspose.slides.export/isvgoptions/
---
## ISVGOptions clase

Representa opciones SVG.

```cpp
class ISVGOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Métodos

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para usos internos. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Devuelve la fuente utilizada en caso de que la fuente original no se encuentre. Lee [System::String](../../system/string/). |
| virtual **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() | Una bandera booleana indica si las partes recortadas permanecen como parte del documento. Si es true, las partes recortadas serán eliminadas; si es false, se serializarán en el documento (lo que puede llevar a un archivo más grande). Lee **bool**. |
| virtual **bool** [get_Disable3DText](./get_disable3dtext/)() | Determina si el texto 3D está deshabilitado en SVG. Lee **bool**. |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | Obtiene un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en **true**, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad está establecida en **false**. |
| virtual **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() | Desactiva la división de los gradientes FromCornerX y FromCenter. Lee **bool**. |
| virtual **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() | SVG 1.1 carece de la capacidad de definir inserciones para marcadores. [Aspose.Slides](../../aspose.slides/) el motor de escritura SVG tiene una solución alternativa para ese problema: recorta el extremo de la línea con flecha, de modo que la línea no se superponga a los marcadores. Esta opción desactiva dicho comportamiento. Lee **bool**. |
| virtual [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() | Determina una forma de manejar fuentes cargadas externamente. Lee [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Devuelve el estilo visual del gradiente. Lee [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | Proporciona opciones que controlan la apariencia de los objetos [Ink](../../aspose.slides.ink/) en el documento exportado. Solo lectura [IInkOptions](../iinkoptions/) |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Determina la calidad de codificación JPEG. Lee **int32_t**. |
| virtual **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() | Devuelve el límite de resolución inferior para la rasterización de metaficheros. Lee **int32_t**. |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | Representa el nivel de compresión de imágenes. Lee [PicturesCompression](../picturescompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Representa un objeto de devolución de llamada para guardar actualizaciones de progreso en porcentaje. Ver [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() | Devuelve y establece una interfaz de devolución de llamada que permite al usuario controlar la conversión de formas. Lee [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. Lee **bool**. El valor predeterminado es **false**. |
| virtual **bool** [get_UseFrameRotation](./get_useframerotation/)() | Determina si se debe realizar la rotación especificada de la forma al renderizar o no. Lee **bool**. El valor predeterminado es **true**. |
| virtual **bool** [get_UseFrameSize](./get_useframesize/)() | Determina si el marco de texto se incluirá en un área de renderizado o no. Lee **bool**. El valor predeterminado es **false**. |
| virtual **bool** [get_VectorizeText](./get_vectorizetext/)() | Determina si el texto en una diapositiva se guardará como gráficos. Lee **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Devuelve un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Lee [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
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
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Establece la fuente utilizada en caso de que la fuente original no se encuentre. Escribe [System::String](../../system/string/). |
| virtual void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) | Una bandera booleana indica si las partes recortadas permanecen como parte del documento. Si es true, las partes recortadas serán eliminadas; si es false, se serializarán en el documento (lo que puede llevar a un archivo más grande). Escribe **bool**. |
| virtual void [set_Disable3DText](./set_disable3dtext/)(**bool**) | Determina si el texto 3D está deshabilitado en SVG. Escribe **bool**. |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | Establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en **true**, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad está establecida en **false**. |
| virtual void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) | Desactiva la división de los gradientes FromCornerX y FromCenter. Escribe **bool**. |
| virtual void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) | SVG 1.1 carece de la capacidad de definir inserciones para marcadores. [Aspose.Slides](../../aspose.slides/) el motor de escritura SVG tiene una solución alternativa para ese problema: recorta el extremo de la línea con flecha, de modo que la línea no se superponga a los marcadores. Esta opción desactiva dicho comportamiento. Escribe **bool**. |
| virtual void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) | Determina una forma de manejar fuentes cargadas externamente. Escribe [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Establece el estilo visual del gradiente. Escribe [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Determina la calidad de codificación JPEG. Escribe **int32_t**. |
| virtual void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) | Establece el límite de resolución inferior para la rasterización de metaficheros. Escribe **int32_t**. |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | Representa el nivel de compresión de imágenes. Escribe [PicturesCompression](../picturescompression/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Representa un objeto de devolución de llamada para guardar actualizaciones de progreso en porcentaje. Ver [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) | Devuelve y establece una interfaz de devolución de llamada que permite al usuario controlar la conversión de formas. Escribe [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. Escribe **bool**. El valor predeterminado es **false**. |
| virtual void [set_UseFrameRotation](./set_useframerotation/)(**bool**) | Determina si se debe realizar la rotación especificada de la forma al renderizar o no. Escribe **bool**. El valor predeterminado es **true**. |
| virtual void [set_UseFrameSize](./set_useframesize/)(**bool**) | Determina si el marco de texto se incluirá en un área de renderizado o no. Escribe **bool**. El valor predeterminado es **false**. |
| virtual void [set_VectorizeText](./set_vectorizetext/)(**bool**) | Determina si el texto en una diapositiva se guardará como gráficos. Escribe **bool**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Escribe [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Habilita la conversión de objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [ISaveOptions](../isaveoptions/)
* Espacio de nombres [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)