---
title: ISwfOptions
second_title: Referencia de API de Aspose.Slides para C++
description: Proporciona opciones que controlan cómo se guarda una presentación en formato SWF.
type: docs
weight: 469
url: /es/aspose.slides.export/iswfoptions/
---
## ISwfOptions clase

Proporciona opciones que controlan cómo se guarda una presentación en formato SWF.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para uso interno. |
| virtual **bool** [get_Compressed](./get_compressed/)() | Especifica si el documento SWF generado debe estar comprimido o no. El valor predeterminado es **true**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Devuelve la fuente usada en caso de que la fuente origen no se encuentre. Lee [System::String](../../system/string/). |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | Habilita/deshabilita el menú contextual. El valor predeterminado es true. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Devuelve el estilo visual del degradado. Lee [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Especifica la calidad de las imágenes JPEG.\n\n El valor predeterminado es 95. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | Imagen que se mostrará como logotipo en la esquina superior derecha del visor.\n\n La imagen debe ser PNG de 32 × 64 píxeles; de lo contrario el logotipo podría mostrarse incorrectamente. |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | Obtiene la dirección completa del hipervínculo para un logotipo. Tiene efecto solo si se especifica un [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Representa un objeto de devolución de llamada para guardar actualizaciones de progreso en porcentaje. Ver [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | Mostrar/ocultar el panel inferior. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | Mostrar/ocultar el botón de pantalla completa. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es **false**. |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | Mostrar/ocultar el panel izquierdo. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | Especifica si se debe mostrar el borde alrededor de las páginas. El valor predeterminado es true. |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | Mostrar/ocultar el control de pasos de página. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | Mostrar/ocultar la sección de búsqueda. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | Mostrar/ocultar todo el panel superior. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. Lee **bool**. El valor predeterminado es **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Obtiene el modo en el que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../islideslayoutoptions/). Esta propiedad no admite asignar objetos del tipo **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | Iniciar con el panel izquierdo abierto. Puede sobrescribirse en flashvars. El valor predeterminado es false. |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | Especifica si el documento SWF generado debe incluir el visor de documentos integrado o no. El valor predeterminado es **true**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Devuelve un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. Lee [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita el hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita la clonación de tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, en realidad, solo inicializa un nuevo objeto y habilita la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, en realidad, solo inicializa un nuevo objeto y habilita la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | Especifica si el documento SWF generado debe estar comprimido o no. El valor predeterminado es **true**. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Establece la fuente usada en caso de que la fuente origen no se encuentre. Escribe [System::String](../../system/string/). |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | Habilita/deshabilita el menú contextual. El valor predeterminado es true. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Establece el estilo visual del degradado. Escribe [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Especifica la calidad de las imágenes JPEG.\n\n El valor predeterminado es 95. |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Imagen que se mostrará como logotipo en la esquina superior derecha del visor.\n\n La imagen debe ser PNG de 32 × 64 píxeles; de lo contrario el logotipo podría mostrarse incorrectamente. |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | Establece la dirección completa del hipervínculo para un logotipo. Tiene efecto solo si se especifica un [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Representa un objeto de devolución de llamada para guardar actualizaciones de progreso en porcentaje. Ver [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | Mostrar/ocultar el panel inferior. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | Mostrar/ocultar el botón de pantalla completa. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es **false**. |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | Mostrar/ocultar el panel izquierdo. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | Especifica si se debe mostrar el borde alrededor de las páginas. El valor predeterminado es true. |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | Mostrar/ocultar el control de pasos de página. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | Mostrar/ocultar la sección de búsqueda. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | Mostrar/ocultar todo el panel superior. Puede sobrescribirse en flashvars. El valor predeterminado es true. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. Escribe **bool**. El valor predeterminado es **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Establece el modo en el que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../islideslayoutoptions/). Esta propiedad no admite asignar objetos del tipo **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | Iniciar con el panel izquierdo abierto. Puede sobrescribirse en flashvars. El valor predeterminado es false. |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | Especifica si el documento SWF generado debe incluir el visor de documentos integrado o no. El valor predeterminado es **true**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. Escribe [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Disminuye y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Habilita la conversión de objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Disminuye el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Ver también

* Clase [ISaveOptions](../isaveoptions/)
* Espacio de nombres [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)