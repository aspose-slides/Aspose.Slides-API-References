---
title: MarkdownSaveOptions
second_title: Referencia de API de Aspose.Slides para C++
description: Representa opciones que controlan cómo se debe guardar la presentación en markdown.
type: docs
weight: 547
url: /es/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions clase

Representa opciones que controlan cómo se debe guardar la presentación en markdown.

```cpp
class MarkdownSaveOptions : public Aspose::Slides::Export::SaveOptions
```

## Métodos

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo de C# donde dos NaN se consideran iguales aunque, según IEC 60559:1989, NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para usos internos. |
| [System::String](../../system/string/) [get_BasePath](./get_basepath/)() const | Especifica la ruta base donde se guardará el documento con recursos. El valor predeterminado es el directorio actual de la aplicación. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Devuelve la fuente utilizada cuando no se encuentra la fuente origen. Lee [System::String](../../system/string/). |
| [MarkdownExportType](../markdownexporttype/) [get_ExportType](./get_exporttype/)() const | Especifica la especificación markdown para convertir la presentación. El valor predeterminado es **TextOnly**. |
| [Aspose::Slides::Export::Flavor](../flavor/) [get_Flavor](./get_flavor/)() const | Especifica la especificación markdown para convertir la presentación. El valor predeterminado es **Multi-markdown**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Devuelve el estilo visual del degradado. Lee [GradientStyle](../../aspose.slides/gradientstyle/). |
| [Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/) [get_HandleRepeatedSpaces](./get_handlerepeatedspaces/)() const | Especifica cómo se deben manejar los caracteres de espacio regular repetidos durante la exportación a Markdown. |
| [System::String](../../system/string/) [get_ImagesSaveFolderName](./get_imagessavefoldername/)() const | Especifica el nombre de la carpeta donde se guardarán las imágenes. El valor predeterminado es **[Images](../../aspose.slides/images/)**. |
| [Aspose::Slides::Export::NewLineType](../newlinetype/) [get_NewLineType](./get_newlinetype/)() const | Especifica si el documento generado debe tener saltos de línea \r (Macintosh), \n (Unix) o \r\n (Windows). El valor predeterminado es **Unix**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Representa un objeto de devolución de llamada para guardar actualizaciones de progreso en porcentaje. Ver [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RemoveEmptyLines](./get_removeemptylines/)() const | Si se establece en **true**, elimina las líneas vacías o que contengan solo espacios en blanco del resultado final de Markdown. El valor predeterminado es **false**. |
| **bool** [get_ShowComments](./get_showcomments/)() const | Especifica si el documento generado debe mostrar comentarios o no. El valor predeterminado es **false**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() const | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es **false**. |
| **bool** [get_ShowSlideNumber](./get_showslidenumber/)() const | Especifica si el documento generado debe mostrar el número de cada diapositiva o no. El valor predeterminado es **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. Lee **bool**. El valor predeterminado es **false**. |
| [System::String](../../system/string/) [get_SlideNumberFormat](./get_slidenumberformat/)() | Obtiene la cadena de formato utilizada para los encabezados de número de diapositiva en la salida Markdown. El formato debe incluir el marcador \"{0}\", que será reemplazado con el índice de la diapositiva durante la exportación. Ejemplo: \"# Slide {0}\" producirá \"# Slide 1\", \"# Slide 2\", etc. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. Lee [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo al método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo a la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo al operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la instrucción C# lock(). Llámalo directamente o usa el objeto centinela [LockContext](../../system/lockcontext/). |
|  [MarkdownSaveOptions](./markdownsaveoptions/)() | Constructor. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo al método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. En realidad no copia nada, sólo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. En realidad no copia nada, sólo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BasePath](./set_basepath/)([System::String](../../system/string/)) | Especifica la ruta base donde se guardará el documento con recursos. El valor predeterminado es el directorio actual de la aplicación. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Establece la fuente utilizada cuando no se encuentra la fuente origen. Escribe [System::String](../../system/string/). |
| void [set_ExportType](./set_exporttype/)([MarkdownExportType](../markdownexporttype/)) | Especifica la especificación markdown para convertir la presentación. El valor predeterminado es **TextOnly**. |
| void [set_Flavor](./set_flavor/)([Aspose::Slides::Export::Flavor](../flavor/)) | Especifica la especificación markdown para convertir la presentación. El valor predeterminado es **Multi-markdown**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Establece el estilo visual del degradado. Escribe [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_HandleRepeatedSpaces](./set_handlerepeatedspaces/)([Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/)) | Especifica cómo se deben manejar los caracteres de espacio regular repetidos durante la exportación a Markdown. |
| void [set_ImagesSaveFolderName](./set_imagessavefoldername/)([System::String](../../system/string/)) | Especifica el nombre de la carpeta donde se guardarán las imágenes. El valor predeterminado es **[Images](../../aspose.slides/images/)**. |
| void [set_NewLineType](./set_newlinetype/)([Aspose::Slides::Export::NewLineType](../newlinetype/)) | Especifica si el documento generado debe tener saltos de línea \r (Macintosh), \n (Unix) o \r\n (Windows). El valor predeterminado es **Unix**. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Representa un objeto de devolución de llamada para guardar actualizaciones de progreso en porcentaje. Ver [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RemoveEmptyLines](./set_removeemptylines/)(**bool**) | Si se establece en **true**, elimina las líneas vacías o que contengan solo espacios en blanco del resultado final de Markdown. El valor predeterminado es **false**. |
| void [set_ShowComments](./set_showcomments/)(**bool**) | Especifica si el documento generado debe mostrar comentarios o no. El valor predeterminado es **false**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es **false**. |
| void [set_ShowSlideNumber](./set_showslidenumber/)(**bool**) | Especifica si el documento generado debe mostrar el número de cada diapositiva o no. El valor predeterminado es **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. Escribe **bool**. El valor predeterminado es **false**. |
| void [set_SlideNumberFormat](./set_slidenumberformat/)([System::String](../../system/string/)) | Establece la cadena de formato utilizada para los encabezados de número de diapositiva en la salida Markdown. El formato debe incluir el marcador \"{0}\", que será reemplazado con el índice de la diapositiva durante la exportación. Ejemplo: \"# Slide {0}\" producirá \"# Slide 1\", \"# Slide 2\", etc. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o será abortado. Escribe [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar punteros en contenedores al modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo al método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la instrucción C# lock(). Llámalo directamente o usa el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debería llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destruye el objeto. Libera todas las estructuras de datos internas. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [MarkdownImageSavingHandler](./markdownimagesavinghandler/) | Invocado para cada imagen que no sea SVG (bitmap o metarchivo) durante la exportación a Markdown.<br>Devuelve **true** para usar el *enlace* especificado,<br>o **false** para aplicar la lógica de guardado predeterminada. |
| [MarkdownSvgImageSavingHandler](./markdownsvgimagesavinghandler/) | Invocado para cada imagen SVG durante la exportación a Markdown.<br>Devuelve **true** para usar el *enlace* especificado,<br>o **false** para aplicar la lógica de guardado predeterminada. |

## Observaciones

Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(u"doc.md", slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## Ver también

* Clase [SaveOptions](../saveoptions/)
* Espacio de nombres [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)