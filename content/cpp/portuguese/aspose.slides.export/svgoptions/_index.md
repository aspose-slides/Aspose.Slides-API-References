---
title: SVGOptions
second_title: Referência da API Aspose.Slides for C++
description: Representa opções SVG.
type: docs
weight: 703
url: /pt/aspose.slides.export/svgoptions/
---
## SVGOptions classe


Representa opções SVG.

```cpp
class SVGOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISVGOptions
```

## Métodos

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo de referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo de valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Default](./get_default/)() | Retorna configurações padrão. Somente leitura [SVGOptions](./). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Retorna fonte usada caso a fonte de origem não seja encontrada. Leitura [System::String](../../system/string/). |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. Se verdadeiro, as partes recortadas serão removidas; se falso, serão serializadas no documento (o que pode levar a um arquivo maior). |
| **bool** [get_Disable3DText](./get_disable3dtext/)() override | Determina se o texto 3D está desativado no SVG. Leitura **bool**. |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | Obtém um valor que indica se o texto é renderizado sem usar ligaduras. Quando definido como **true**, as ligaduras serão desativadas na saída renderizada. Por padrão, esta propriedade está definida como **false**. |
| **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() override | Desativa divisão de gradientes FromCornerX e FromCenter. Leitura **bool**. |
| **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() override | SVG 1.1 não tem capacidade de definir recuos para marcadores. [Aspose.Slides](../../aspose.slides/) o motor de escrita SVG tem uma solução alternativa para esse problema: ele corta a extremidade da linha com seta, de modo que a linha não sobreponha os marcadores. Esta opção desativa esse comportamento. Leitura **bool**. |
| [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() override | Determina uma forma de lidar com fontes carregadas externamente. Leitura [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Retorna o estilo visual do gradiente. Leitura [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Fornece opções que controlam a aparência dos objetos [Ink](../../aspose.slides.ink/) no documento exportado. Somente leitura [IInkOptions](../iinkoptions/) |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Determina a qualidade de codificação JPEG. Leitura **int32_t**. |
| **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() override | Retorna o limite de resolução inferior para rasterização de metafile. Leitura **int32_t**. |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | Representa o nível de compressão de imagens |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Representa um objeto de retorno de chamada para salvar atualizações de progresso em porcentagem. Veja [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() override | Retorna e define uma interface de retorno de chamada que permite ao usuário controlar a conversão de formas. Leitura [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Simple](./get_simple/)() | Retorna configurações para geração do arquivo SVG mais simples e pequeno. Somente leitura [SVGOptions](./). |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Especifica se deve pular hyperlinks com chamadas JavaScript ao salvar a apresentação. Leitura **bool**. O valor padrão é **false**. |
| **bool** [get_UseFrameRotation](./get_useframerotation/)() override | Determina se realiza a rotação especificada da forma ao renderizar ou não. Leitura **bool**. O valor padrão é true. |
| **bool** [get_UseFrameSize](./get_useframesize/)() override | Determina se a moldura de texto será incluída em uma área de renderização ou não. Leitura **bool**. O valor padrão é false. |
| **bool** [get_VectorizeText](./get_vectorizetext/)() override | Determina se o texto em um slide será salvo como gráficos. Leitura **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Leitura [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_WYSIWYG](./get_wysiwyg/)() | Retorna configurações para geração do arquivo SVG mais preciso. Somente leitura [SVGOptions](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogia ao método [Object.GetHashCode()](../../system/object/gethashcode/) do C#. Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogia à chamada [System.Object.GetType()](../../system/object/gettype/) do C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogia ao operador 'is' do C#. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogia ao método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) do C#. Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhado pelo valor especificado. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Define a fonte usada caso a fonte de origem não seja encontrada. Grava [System::String](../../system/string/). |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | Um sinalizador booleano indica se as partes recortadas permanecem como parte do documento. Se verdadeiro, as partes recortadas serão removidas; se falso, serão serializadas no documento (o que pode levar a um arquivo maior) |
| void [set_Disable3DText](./set_disable3dtext/)(**bool**) override | Determina se o texto 3D está desativado no SVG. Grava **bool**. |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | Define um valor que indica se o texto é renderizado sem usar ligaturas. Quando definido como **true**, as ligaturas serão desativadas na saída renderizada. Por padrão, esta propriedade está definida como **false**. |
| void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) override | Desativa divisão de gradientes FromCornerX e FromCenter. Grava **bool**. |
| void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) override | SVG 1.1 não tem capacidade de definir recuos para marcadores. [Aspose.Slides](../../aspose.slides/) o motor de escrita SVG tem uma solução alternativa para esse problema: ele corta a extremidade da linha com seta, de modo que a linha não sobreponha os marcadores. Esta opção desativa esse comportamento. Grava **bool**. |
| void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) override | Determina uma forma de lidar com fontes carregadas externamente. Grava [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Define o estilo visual do gradiente. Grava [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Determina a qualidade de codificação JPEG. Grava **int32_t**. |
| void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) override | Define o limite de resolução inferior para rasterização de metafile. Grava **int32_t**. |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | Representa o nível de compressão de imagens |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Representa um objeto de retorno de chamada para salvar atualizações de progresso em porcentagem. Veja [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) override | Retorna e define uma interface de retorno de chamada que permite ao usuário controlar a conversão de formas. Grava [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Especifica se deve pular hyperlinks com chamadas JavaScript ao salvar a apresentação. Grava **bool**. O valor padrão é **false**. |
| void [set_UseFrameRotation](./set_useframerotation/)(**bool**) override | Determina se realiza a rotação especificada da forma ao renderizar ou não. Grava **bool**. O valor padrão é true. |
| void [set_UseFrameSize](./set_useframesize/)(**bool**) override | Determina se a moldura de texto será incluída em uma área de renderização ou não. Grava **bool**. O valor padrão é false. |
| void [set_VectorizeText](./set_vectorizetext/)(**bool**) override | Determina se o texto em um slide será salvo como gráficos. Grava **bool**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Grava [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhado. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhado. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhado. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
|  [SVGOptions](./svgoptions/)() | Inicializa uma nova instância da classe [SVGOptions](./). |
|  [SVGOptions](./svgoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | Inicializa uma nova instância da classe [SVGOptions](./) especificando o objeto controlador de incorporação de vínculo. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogia ao método [Object.ToString()](../../system/object/tostring/) do C#. Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [SaveOptions](../saveoptions/)
* Classe [ISVGOptions](../isvgoptions/)
* Namespace [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)