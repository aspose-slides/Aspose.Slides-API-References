---
title: SwfOptions
second_title: Referencia de API de Aspose.Slides para C++
description: Proporciona opciones que controlan cómo se guarda una presentación en formato Swf.
type: docs
weight: 742
url: /es/aspose.slides.export/swfoptions/
---
## SwfOptions clase


Proporciona opciones que controlan cómo se guarda una presentación en formato Swf.

```cpp
class SwfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISwfOptions
```

## Métodos

| Método | Descripción |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Sólo para propósitos internos. |
| **bool** [get_Compressed](./get_compressed/)() override | Especifica si el documento SWF generado debe comprimirse o no. Por defecto es **true**. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Devuelve la fuente utilizada cuando no se encuentra la fuente origen. Lee [System::String](../../system/string/). |
| **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() override | Habilita/deshabilita el menú contextual. Por defecto es true. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Devuelve el estilo visual del degradado. Lea [GradientStyle](../../aspose.slides/gradientstyle/). |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Especifica la calidad de las imágenes JPEG. Por defecto es 95. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() override | Imagen que se mostrará como logotipo en la esquina superior derecha del visor. La imagen debe ser PNG de 32 × 64 píxeles; de lo contrario el logotipo puede mostrarse incorrectamente. |
| [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() override | Obtiene la dirección de hipervínculo completa para un logotipo. Tiene efecto solo si se especifica un [set_LogoImageBytes()](./set_logoimagebytes/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Representa un objeto de devolución de llamada para actualizar el progreso del guardado en porcentaje. Vea [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowBottomPane](./get_showbottompane/)() override | Muestra/oculta el panel inferior. Puede sobrescribirse en flashvars. Por defecto es true. |
| **bool** [get_ShowFullScreen](./get_showfullscreen/)() override | Muestra/oculta el botón de pantalla completa. Puede sobrescribirse en flashvars. Por defecto es true. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Especifica si el documento generado debe incluir diapositivas ocultas o no. Por defecto es **false**. |
| **bool** [get_ShowLeftPane](./get_showleftpane/)() override | Muestra/oculta el panel izquierdo. Puede sobrescribirse en flashvars. Por defecto es true. |
| **bool** [get_ShowPageBorder](./get_showpageborder/)() override | Especifica si debe mostrarse el borde alrededor de las páginas. Por defecto es true. |
| **bool** [get_ShowPageStepper](./get_showpagestepper/)() override | Muestra/oculta el selector de página. Puede sobrescribirse en flashvars. Por defecto es true. |
| **bool** [get_ShowSearch](./get_showsearch/)() override | Muestra/oculta la sección de búsqueda. Puede sobrescribirse en flashvars. Por defecto es true. |
| **bool** [get_ShowTopPane](./get_showtoppane/)() override | Muestra/oculta todo el panel superior. Puede sobrescribirse en flashvars. Por defecto es true. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. Lea **bool**. El valor predeterminado es **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Obtiene el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../islideslayoutoptions/). Esta propiedad no permite asignar objetos del tipo [HandoutLayoutingOptions](../handoutlayoutingoptions/). |
| **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() override | Inicia con el panel izquierdo abierto. Puede sobrescribirse en flashvars. Por defecto es false. |
| **bool** [get_ViewerIncluded](./get_viewerincluded/)() override | Especifica si el documento SWF generado debe incluir el visor de documentos integrado o no. Por defecto es **true**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Lea [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# ‘is’. |
| void [Lock](../../system/object/lock/)() | Implementa la instrucción C# lock() bloqueando. Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita la clonación de tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. No copia nada, simplemente inicializa un nuevo objeto y permite la copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. No copia nada, simplemente inicializa un nuevo objeto y permite la copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas por el valor especificado. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_Compressed](./set_compressed/)(**bool**) override | Especifica si el documento SWF generado debe comprimirse o no. Por defecto es **true**. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Establece la fuente utilizada cuando no se encuentra la fuente origen. Escribe [System::String](../../system/string/). |
| void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) override | Habilita/deshabilita el menú contextual. Por defecto es true. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Establece el estilo visual del degradado. Escriba [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Especifica la calidad de las imágenes JPEG. Por defecto es 95. |
| void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Imagen que se mostrará como logotipo en la esquina superior derecha del visor. La imagen debe ser PNG de 32 × 64 píxeles; de lo contrario el logotipo puede mostrarse incorrectamente. |
| void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) override | Establece la dirección de hipervínculo completa para un logotipo. Tiene efecto solo si se especifica un [set_LogoImageBytes()](./set_logoimagebytes/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Representa un objeto de devolución de llamada para actualizar el progreso del guardado en porcentaje. Vea [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowBottomPane](./set_showbottompane/)(**bool**) override | Muestra/oculta el panel inferior. Puede sobrescribirse en flashvars. Por defecto es true. |
| void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) override | Muestra/oculta el botón de pantalla completa. Puede sobrescribirse en flashvars. Por defecto es true. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Especifica si el documento generado debe incluir diapositivas ocultas o no. Por defecto es **false**. |
| void [set_ShowLeftPane](./set_showleftpane/)(**bool**) override | Muestra/oculta el panel izquierdo. Puede sobrescribirse en flashvars. Por defecto es true. |
| void [set_ShowPageBorder](./set_showpageborder/)(**bool**) override | Especifica si debe mostrarse el borde alrededor de las páginas. Por defecto es true. |
| void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) override | Muestra/oculta el selector de página. Puede sobrescribirse en flashvars. Por defecto es true. |
| void [set_ShowSearch](./set_showsearch/)(**bool**) override | Muestra/oculta la sección de búsqueda. Puede sobrescribirse en flashvars. Por defecto es true. |
| void [set_ShowTopPane](./set_showtoppane/)(**bool**) override | Muestra/oculta todo el panel superior. Puede sobrescribirse en flashvars. Por defecto es true. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. Escriba **bool**. El valor predeterminado es **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../islideslayoutoptions/). Esta propiedad no permite asignar objetos del tipo [HandoutLayoutingOptions](../handoutlayoutingoptions/). |
| void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) override | Inicia con el panel izquierdo abierto. Puede sobrescribirse en flashvars. Por defecto es false. |
| void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) override | Especifica si el documento SWF generado debe incluir el visor de documentos integrado o no. Por defecto es **true**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Escriba [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como puntero débil (en vez de compartido). Permite cambiar punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
|  [SwfOptions](./swfoptions/)() | Constructor predeterminado. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Habilita la conversión de objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa la instrucción C# lock() desbloqueando. Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Comentarios


El siguiente ejemplo muestra cómo convertir PowerPoint a SWF Flash. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"HelloWorld.pptx");
auto swfOptions = System::MakeObject<SwfOptions>();

swfOptions->set_ViewerIncluded(false);
auto notesOptions = swfOptions->get_NotesCommentsLayouting();
notesOptions->set_NotesPosition(NotesPositions::BottomFull);

// Saving presentation and notes pages
presentation->Save(u"SaveAsSwf_out.swf", SaveFormat::Swf, swfOptions);
swfOptions->set_ViewerIncluded(true);
presentation->Save(u"SaveNotes_out.swf", SaveFormat::Swf, swfOptions);
```

## Ver también

* Clase [SaveOptions](../saveoptions/)
* Clase [ISwfOptions](../iswfoptions/)
* Espacio de nombres [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)