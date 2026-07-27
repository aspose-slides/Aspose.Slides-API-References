---
title: TiffOptions
second_title: Referência da API Aspose.Slides para C++
description: Fornece opções que controlam como uma apresentação é salva no formato TIFF.
type: docs
weight: 768
url: /pt/aspose.slides.export/tiffoptions/
---
## TiffOptions classe

Fornece opções que controlam como uma apresentação é salva no formato TIFF.

```cpp
class TiffOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::ITiffOptions
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() override | Especifica o algoritmo para converter uma imagem colorida em uma imagem preto e branca. Esta opção será aplicada somente se [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) estiver definido como [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) ou [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) Ler [BlackWhiteConversionMode](../blackwhiteconversionmode/). O padrão é [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() override | Especifica o tipo de compressão. Ler [TiffCompressionTypes](../tiffcompressiontypes/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Retorna a fonte usada caso a fonte de origem não seja encontrada. Lê [System::String](../../system/string/). |
| **uint32_t** [get_DpiX](./get_dpix/)() override | Especifica a resolução horizontal em pontos por polegada. Ler **uint32_t**. |
| **uint32_t** [get_DpiY](./get_dpiy/)() override | Especifica a resolução vertical em pontos por polegada. Ler **uint32_t**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Retorna o estilo visual do gradiente. Ler [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() override | Especifica o tamanho de uma imagem TIFF gerada. O valor padrão é 0x0, o que significa que os tamanhos das imagens geradas serão calculados com base no valor do tamanho do slide da apresentação. Ler [System::Drawing::Size](../../system.drawing/size/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Fornece opções que controlam a aparência dos objetos [Ink](../../aspose.slides.ink/) no documento exportado. Somente leitura [IInkOptions](../iinkoptions/) |
| [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() override | Especifica o formato de pixel para as imagens geradas. Ler [ImagePixelFormat](../imagepixelformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Representa um objeto de retorno de chamada para salvar atualizações de progresso em porcentagem. Ver [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Especifica se deve pular hiperlinks com chamadas JavaScript ao salvar a apresentação. Ler **bool**. O valor padrão é **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Obtém o modo em que os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../islideslayoutoptions/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Ler [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, na verdade, apenas inicializa um novo objeto e permite a construção de cópias em subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) override | Especifica o algoritmo para converter uma imagem colorida em uma imagem preto e branca. Esta opção será aplicada somente se [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) estiver definido como [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) ou [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) Escrever [BlackWhiteConversionMode](../blackwhiteconversionmode/). O padrão é [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) override | Especifica o tipo de compressão. Escrever [TiffCompressionTypes](../tiffcompressiontypes/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Define a fonte usada caso a fonte de origem não seja encontrada. Escreve [System::String](../../system/string/). |
| void [set_DpiX](./set_dpix/)(**uint32_t**) override | Especifica a resolução horizontal em pontos por polegada. Escrever **uint32_t**. |
| void [set_DpiY](./set_dpiy/)(**uint32_t**) override | Especifica a resolução vertical em pontos por polegada. Escrever **uint32_t**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Define o estilo visual do gradiente. Escrever [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) override | Especifica o tamanho de uma imagem TIFF gerada. O valor padrão é 0x0, o que significa que os tamanhos das imagens geradas serão calculados com base no valor do tamanho do slide da apresentação. Escrever [System::Drawing::Size](../../system.drawing/size/). |
| void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) override | Especifica o formato de pixel para as imagens geradas. Escrever [ImagePixelFormat](../imagepixelformat/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Representa um objeto de retorno de chamada para salvar atualizações de progresso em porcentagem. Ver [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Especifica se deve pular hiperlinks com chamadas JavaScript ao salvar a apresentação. Escrever **bool**. O valor padrão é **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Define o modo em que os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Escrever [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
|  [TiffOptions](./tiffoptions/)() | Construtor padrão. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo ao método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Observações

O exemplo a seguir mostra como converter PowerPoint para TIFF com tamanho padrão.  
```cpp
// Instanciar um objeto Presentation que representa um arquivo de apresentação
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

// Salvando a apresentação em um documento TIFF
presentation->Save(u"Tiffoutput_out.tiff", SaveFormat::Tiff);
```
O exemplo a seguir mostra como converter PowerPoint para TIFF com tamanho personalizado.  
```cpp
// Instanciar um objeto Presentation que representa um arquivo Presentation
auto pres = System::MakeObject<Presentation>(u"Convert_Tiff_Custom.pptx");

// Instanciar a classe TiffOptions
System::SharedPtr<TiffOptions> opts = System::MakeObject<TiffOptions>();
// Definindo o tipo de compressão
opts->set_CompressionType(TiffCompressionTypes::Default);

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
opts->set_SlidesLayoutOptions(slidesLayoutOptions);

// Tipos de compressão
// Default - Especifica o esquema de compressão padrão (LZW).
// None - Especifica nenhuma compressão.
// CCITT3
// CCITT4
// LZW
// RLE
// A profundidade depende do tipo de compressão e não pode ser definida manualmente.
// A unidade de resolução é sempre igual a "2" (pontos por polegada)
// Definindo DPI da imagem
opts->set_DpiX(200);
opts->set_DpiY(100);
// Definir tamanho da imagem
opts->set_ImageSize(System::Drawing::Size(1728, 1078));
// Save the presentation to TIFF with specified image size
pres->Save(u"TiffWithCustomSize_out.tiff", SaveFormat::Tiff, opts);
```
O exemplo a seguir mostra como converter PowerPoint para TIFF com formato de pixel de imagem personalizado.  
```cpp
// Instanciar um objeto Presentation que representa um arquivo Presentation
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_PixelFormat(ImagePixelFormat::Format8bppIndexed);

// Salvar a apresentação em TIFF com o tamanho de imagem especificado
presentation->Save(u"Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat::Tiff, options);
```

## Veja Também

* Classe [SaveOptions](../saveoptions/)
* Classe [ITiffOptions](../itiffoptions/)
* Espaço de nomes [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)