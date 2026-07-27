---
title: PdfOptions
second_title: Referencia de la API de Aspose.Slides para C++
description: Proporciona opciones que controlan cómo se guarda una presentación en formato Pdf.
type: docs
weight: 573
url: /es/aspose.slides.export/pdfoptions/
---
## PdfOptions clase

Proporciona opciones que controlan cómo se guarda una presentación en formato Pdf.

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## Métodos

| Method | Descripción |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando la semántica de C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referencia al estilo de C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor al estilo de C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula la comparación de punto flotante al estilo C# donde dos NaN se consideran iguales aunque según IEC 60559:1989 NaN no es igual a ningún valor, incluido NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Solo para propósitos internos. |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | Contiene un conjunto de indicadores que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario. Ver [PdfAccessPermissions](../pdfaccesspermissions/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | Devuelve una matriz de nombres de familias de fuentes definidos por el usuario que [Aspose.Slides](../../aspose.slides/) debería considerar comunes. Lea [System::String](../../system/string/)[]. |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | Aplica el color transparente especificado a una imagen si **true**. |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | Indica si la compresión más eficaz (en lugar de la predeterminada) para cada imagen debe seleccionarse automáticamente. Si se establece en **bool**.true, para cada imagen en la presentación se elegirá el algoritmo de compresión más apropiado, lo que conducirá a un tamaño menor del documento PDF resultante. |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | Nivel de conformidad deseado para el documento PDF generado. Lea [PdfCompliance](../pdfcompliance/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Devuelve la fuente utilizada en caso de que la fuente origen no se encuentre. Lea [System::String](../../system/string/). |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | True para dibujar un marco negro alrededor de cada diapositiva. Lea **bool**. |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | Determina si todos los caracteres de la fuente deben incrustarse o solo un subconjunto usado. Lea **bool**. |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | Determina si [Aspose.Slides](../../aspose.slides/) incrustará fuentes comunes para texto ASCII (rango de códigos 33..127). [Fonts](../../aspose.slides/fonts/) para códigos de carácter mayores que 127 siempre se incrustan. La lista de fuentes comunes incluye las 14 fuentes base de PDF y fuentes adicionales especificadas por el usuario. Lea **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Devuelve el estilo visual del degradado. Lea [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | Obtiene el color transparente de la imagen. |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | True para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Lea **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Proporciona opciones que controlan la apariencia de los objetos [Ink](../../aspose.slides.ink/) en el documento exportado. Solo lectura [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | Devuelve un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. Lea **uint8_t**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | Establece la contraseña de usuario para proteger el documento PDF. Lea [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Representa un objeto de devolución de llamada para guardar actualizaciones de progreso en porcentaje. Ver [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | Indica si el texto debe rasterizarse como un mapa de bits y guardarse en PDF cuando la fuente no admite estilo negrita. Este enfoque puede mejorar la calidad del texto en el PDF resultante para ciertas fuentes. Lea **bool**. |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | True para convertir todos los metarchivos usados en una presentación a imágenes PNG. Lea **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. Lea **bool**. El valor predeterminado es **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Obtiene el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../islideslayoutoptions/). |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | Devuelve un valor que determina la resolución de las imágenes dentro del documento PDF. |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | Especifica el tipo de compresión a usar para todo el contenido textual del documento. Lea [PdfTextCompression](../pdftextcompression/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Lea [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtiene la estructura de datos del contador de referencias asociada al objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo del método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite el hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtiene el tipo real del objeto. Análogo de la llamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Comprueba si el objeto representa una instancia del tipo descrito por targetType. Análogo del operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa el bloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo del método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Crea el objeto. Inicializa todas las estructuras de datos internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructor de copia. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de asignación. Realmente no copia nada, solo inicializa un nuevo objeto y permite la construcción por copia de subclases. |
|  [PdfOptions](./pdfoptions/)() | Constructor por defecto. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referencia. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referencia un objeto de tipo valor con nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadena y nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialización de [Object::ReferenceEquals](../../system/object/referenceequals/) para el caso de cadenas. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Disminuye el contador de referencias compartidas en el valor especificado. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | Contiene un conjunto de indicadores que especifican qué permisos de acceso deben concederse cuando el documento se abre con acceso de usuario. Ver [PdfAccessPermissions](../pdfaccesspermissions/). |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | Establece una matriz de nombres de familias de fuentes definidos por el usuario que [Aspose.Slides](../../aspose.slides/) debería considerar comunes. Escriba [System::String](../../system/string/)[]. |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | Aplica el color transparente especificado a una imagen si **true**. |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | Indica si la compresión más eficaz (en lugar de la predeterminada) para cada imagen debe seleccionarse automáticamente. Si se establece en **bool**.true, para cada imagen en la presentación se elegirá el algoritmo de compresión más apropiado, lo que conducirá a un tamaño menor del documento PDF resultante. |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | Nivel de conformidad deseado para el documento PDF generado. Escriba [PdfCompliance](../pdfcompliance/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Establece la fuente utilizada en caso de que la fuente origen no se encuentre. Escribe [System::String](../../system/string/). |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | True para dibujar un marco negro alrededor de cada diapositiva. Escriba **bool**. |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | Determina si todos los caracteres de la fuente deben incrustarse o solo un subconjunto usado. Escriba **bool**. |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | Determina si [Aspose.Slides](../../aspose.slides/) incrustará fuentes comunes para texto ASCII (rango de códigos 33..127). [Fonts](../../aspose.slides/fonts/) para códigos de carácter mayores que 127 siempre se incrustan. La lista de fuentes comunes incluye las 14 fuentes base de PDF y fuentes adicionales especificadas por el usuario. Escriba **bool**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Establece el estilo visual del degradado. Escriba [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | Establece el color transparente de la imagen. |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | True para convertir todos los datos OLE de la presentación en archivos incrustados en el PDF resultante. Escriba **bool**. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | Establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. Escriba **uint8_t**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | Establece la contraseña de usuario para proteger el documento PDF. Escriba [System::String](../../system/string/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Representa un objeto de devolución de llamada para guardar actualizaciones de progreso en porcentaje. Ver [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | Indica si el texto debe rasterizarse como un mapa de bits y guardarse en PDF cuando la fuente no admite estilo negrita. Este enfoque puede mejorar la calidad del texto en el PDF resultante para ciertas fuentes. Escriba **bool**. |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | True para convertir todos los metarchivos usados en una presentación a imágenes PNG. Escriba **bool**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Especifica si se deben omitir los hipervínculos con llamadas JavaScript al guardar la presentación. Escriba **bool**. El valor predeterminado es **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | Establece un valor que determina la resolución de las imágenes dentro del documento PDF. |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | Especifica el tipo de compresión a usar para todo el contenido textual del documento. Escriba [PdfTextCompression](../pdftextcompression/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Devuelve o establece un objeto que recibe advertencias y decide si el proceso de carga continuará o se abortará. Escriba [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Establece el n-ésimo argumento de plantilla como un puntero débil (en lugar de compartido). Permite cambiar los punteros en contenedores a modo débil. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtiene el valor actual del contador de referencias compartidas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa y devuelve el contador de referencias compartidas. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo del método C# [Object.ToString()](../../system/object/tostring/). Permite convertir objetos personalizados a cadena. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa la construcción C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa el desbloqueo de la sentencia C# lock(). Llame directamente o use el objeto centinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa el contador de referencias débiles. No debe llamarse directamente; en su lugar, use punteros inteligentes o ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |

## Comentarios





El siguiente ejemplo muestra cómo convertir PowerPoint a PDF con opciones personalizadas. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Instancia la clase PdfOptions
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Establece la calidad Jpeg
pdfOptions->set_JpegQuality(90);
// Establece el comportamiento para los metafiles
pdfOptions->set_SaveMetafilesAsPng(true);
// Establece el nivel de compresión de texto
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// Define el estándar PDF
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// Guarda la presentación como PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 El siguiente ejemplo muestra cómo convertir PowerPoint a PDF con diapositivas ocultas. 
```cpp
// Instancia una clase Presentation que representa un archivo PowerPoint
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Instancia la clase PdfOptions
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Añade diapositivas ocultas
pdfOptions->set_ShowHiddenSlides(true);
// Guarda la presentación como PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 El siguiente ejemplo muestra cómo convertir PowerPoint a PDF protegido con contraseña. 
```cpp
// Instancia un objeto Presentation que representa un archivo PowerPoint
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// Establece la contraseña PDF y los permisos de acceso
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// Guarda la presentación como PDF
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 El siguiente ejemplo muestra cómo convertir PowerPoint a PDF con notas. 
```cpp
// Instancia un objeto Presentation que representa un archivo de presentación
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// Setting Slide Type and Size
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
pdfOptions->set_SlidesLayoutOptions(slidesLayoutOptions);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## Ver también

* Clase [SaveOptions](../saveoptions/)
* Clase [IPdfOptions](../ipdfoptions/)
* Espacio de nombres [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)