---
title: PdfOptions
second_title: Referência da API Aspose.Slides para C++
description: Fornece opções que controlam como uma apresentação é salva no formato Pdf.
type: docs
weight: 573
url: /pt/aspose.slides.export/pdfoptions/
---
## classe PdfOptions

Fornece opções que controlam como uma apresentação é salva no formato Pdf.

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | Contém um conjunto de flags que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário. Veja [PdfAccessPermissions](../pdfaccesspermissions/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | Retorna um array de nomes de famílias de fontes definidos pelo usuário que [Aspose.Slides](../../aspose.slides/) deve considerar comuns. Leia [System::String](../../system/string/)[]. |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | Aplica a cor transparente especificada a uma imagem se **true**. |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | Indica se a compressão mais eficaz (em vez da padrão) para cada imagem deve ser selecionada automaticamente. Se definido como **bool**.true, para cada imagem na apresentação o algoritmo de compressão mais apropriado será escolhido, o que resultará em um tamanho menor do documento PDF resultante. |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | Nível de conformidade desejado para o documento PDF gerado. Leia [PdfCompliance](../pdfcompliance/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Retorna a fonte usada caso a fonte de origem não seja encontrada. Leia [System::String](../../system/string/). |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | Verdadeiro para desenhar uma moldura preta ao redor de cada slide. Leia **bool**. |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | Determina se todos os caracteres da fonte devem ser incorporados ou apenas um subconjunto usado. Leia **bool**. |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | Determina se [Aspose.Slides](../../aspose.slides/) incorporará fontes comuns para texto ASCII (faixa de código 33..127). [Fonts](../../aspose.slides/fonts/) para códigos de caracteres maiores que 127 são sempre incorporados. A lista de fontes comuns inclui as 14 fontes base do PDF e fontes adicionais especificadas pelo usuário. Leia **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Retorna o estilo visual do gradiente. Leia [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | Obtém a cor transparente da imagem. |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | Verdadeiro para converter todos os dados OLE da apresentação em arquivos incorporados no PDF resultante. Leia **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Fornece opções que controlam a aparência dos objetos [Ink](../../aspose.slides.ink/) no documento exportado. Somente leitura [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | Retorna um valor que determina a qualidade das imagens JPEG dentro do documento PDF. Leia **uint8_t**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | Definindo a senha de usuário para proteger o documento PDF. Leia [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Representa um objeto de retorno de chamada para salvar atualizações de progresso em porcentagem. Veja [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | Indica se o texto deve ser rasterizado como bitmap e salvo em PDF quando a fonte não suporta estilo negrito. Esta abordagem pode melhorar a qualidade do texto no PDF resultante para certas fontes. Leia **bool**. |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | Verdadeiro para converter todos os metafiles usados em uma apresentação em imagens PNG. Leia **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Especifica se deve pular hyperlinks com chamadas JavaScript ao salvar a apresentação. Leia **bool**. O valor padrão é **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Obtém o modo em que os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../islideslayoutoptions/). |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | Retorna um valor que determina a resolução das imagens dentro do documento PDF. |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | Especifica o tipo de compressão a ser usado para todo o conteúdo textual no documento. Leia [PdfTextCompression](../pdftextcompression/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Leia [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita a clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
|  [PdfOptions](./pdfoptions/)() | Construtor padrão. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | Contém um conjunto de flags que especificam quais permissões de acesso devem ser concedidas quando o documento é aberto com acesso de usuário. Veja [PdfAccessPermissions](../pdfaccesspermissions/). |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | Define um array de nomes de famílias de fontes definidos pelo usuário que [Aspose.Slides](../../aspose.slides/) deve considerar comuns. Escreva [System::String](../../system/string/)[]. |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | Aplica a cor transparente especificada a uma imagem se **true**. |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | Indica se a compressão mais eficaz (em vez da padrão) para cada imagem deve ser selecionada automaticamente. Se definido como **bool**.true, para cada imagem na apresentação o algoritmo de compressão mais apropriado será escolhido, o que resultará em um tamanho menor do documento PDF resultante. |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | Nível de conformidade desejado para o documento PDF gerado. Escreva [PdfCompliance](../pdfcompliance/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Define a fonte usada caso a fonte de origem não seja encontrada. Escreve [System::String](../../system/string/). |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | Verdadeiro para desenhar uma moldura preta ao redor de cada slide. Escreva **bool**. |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | Determina se todos os caracteres da fonte devem ser incorporados ou apenas um subconjunto usado. Escreva **bool**. |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | Determina se [Aspose.Slides](../../aspose.slides/) incorporará fontes comuns para texto ASCII (faixa de código 33..127). [Fonts](../../aspose.slides/fonts/) para códigos de caracteres maiores que 127 são sempre incorporados. A lista de fontes comuns inclui as 14 fontes base do PDF e fontes adicionais especificadas pelo usuário. Escreva **bool**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Define o estilo visual do gradiente. Escreva [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | Define a cor transparente da imagem. |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | Verdadeiro para converter todos os dados OLE da apresentação em arquivos incorporados no PDF resultante. Escreva **bool**. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | Define um valor que determina a qualidade das imagens JPEG dentro do documento PDF. Escreva **uint8_t**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | Definindo a senha de usuário para proteger o documento PDF. Escreva [System::String](../../system/string/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Representa um objeto de retorno de chamada para salvar atualizações de progresso em porcentagem. Veja [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | Indica se o texto deve ser rasterizado como bitmap e salvo em PDF quando a fonte não suporta estilo negrito. Esta abordagem pode melhorar a qualidade do texto no PDF resultante para certas fontes. Escreva **bool**. |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | Verdadeiro para converter todos os metafiles usados em uma apresentação em imagens PNG. Escreva **bool**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Especifica se deve pular hyperlinks com chamadas JavaScript ao salvar a apresentação. Escreva **bool**. O valor padrão é **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Define o modo em que os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | Define um valor que determina a resolução das imagens dentro do documento PDF. |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | Define o tipo de compressão a ser usado para todo o conteúdo textual no documento. Escreva [PdfTextCompression](../pdftextcompression/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Escreva [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para o modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e devolve o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Observações





O exemplo a seguir mostra como converter PowerPoint para PDF com opções personalizadas. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Instancia a classe PdfOptions
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Define a qualidade do JPEG
pdfOptions->set_JpegQuality(90);
// Define o comportamento para metafiles
pdfOptions->set_SaveMetafilesAsPng(true);
// Define o nível de compressão de texto
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// Define o padrão PDF
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// Salva a apresentação como PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 O exemplo a seguir mostra como converter PowerPoint para PDF com slides ocultos. 
```cpp
// Instancia a classe Presentation que representa um arquivo PowerPoint
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Instancia a classe PdfOptions
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Adiciona slides ocultos
pdfOptions->set_ShowHiddenSlides(true);
// Salva a apresentação como PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 O exemplo a seguir mostra como converter PowerPoint para PDF protegido por senha. 
```cpp
// Instancia um objeto Presentation que representa um arquivo PowerPoint
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// Define a senha do PDF e as permissões de acesso
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// Salva a apresentação como PDF
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
 O exemplo a seguir mostra como converter PowerPoint para PDF com notas. 
```cpp
// Instancia um objeto Presentation que representa um arquivo de apresentação
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// Definindo o tipo e o tamanho do slide
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
pdfOptions->set_SlidesLayoutOptions(slidesLayoutOptions);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## Ver Também

* Classe [SaveOptions](../saveoptions/)
* Classe [IPdfOptions](../ipdfoptions/)
* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)