---
title: MarkdownSaveOptions
second_title: Referência da API Aspose.Slides para C++
description: Representa opções que controlam como a apresentação deve ser salva em markdown.
type: docs
weight: 547
url: /pt/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions classe

Representa opções que controlam como a apresentação deve ser salva em markdown.

```cpp
class MarkdownSaveOptions : public Aspose::Slides::Export::SaveOptions
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| [System::String](../../system/string/) [get_BasePath](./get_basepath/)() const | Especifica o caminho base onde o documento com recursos será salvo. O padrão é o diretório atual da aplicação. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Retorna a fonte usada caso a fonte de origem não seja encontrada. Lê [System::String](../../system/string/). |
| [MarkdownExportType](../markdownexporttype/) [get_ExportType](./get_exporttype/)() const | Especifica a especificação markdown para converter a apresentação. O padrão é **TextOnly**. |
| [Aspose::Slides::Export::Flavor](../flavor/) [get_Flavor](./get_flavor/)() const | Especifica a especificação markdown para converter a apresentação. O padrão é **Multi-markdown**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Retorna o estilo visual do gradiente. Leia [GradientStyle](../../aspose.slides/gradientstyle/). |
| [Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/) [get_HandleRepeatedSpaces](./get_handlerepeatedspaces/)() const | Especifica como caracteres de espaço regulares repetidos devem ser tratados durante a exportação Markdown. |
| [System::String](../../system/string/) [get_ImagesSaveFolderName](./get_imagessavefoldername/)() const | Especifica o nome da pasta para salvar imagens. O padrão é **[Images](../../aspose.slides/images/)**. |
| [Aspose::Slides::Export::NewLineType](../newlinetype/) [get_NewLineType](./get_newlinetype/)() const | Especifica se o documento gerado deve ter novas linhas \r(Macintosh) de \n(Unix) ou \r\n(Windows). O padrão é **Unix**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Representa um objeto de callback para salvar atualizações de progresso em porcentagem. Veja [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RemoveEmptyLines](./get_removeemptylines/)() const | Se definido como **true**, remove linhas vazias ou contendo apenas espaços em branco da saída final em Markdown. O padrão é **false**. |
| **bool** [get_ShowComments](./get_showcomments/)() const | Especifica se o documento gerado deve exibir comentários ou não. O padrão é **false**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() const | Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é **false**. |
| **bool** [get_ShowSlideNumber](./get_showslidenumber/)() const | Especifica se o documento gerado deve mostrar número de cada slide ou não. O padrão é **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Especifica se deve ignorar hyperlinks com chamadas JavaScript ao salvar a apresentação. Leia **bool**. O valor padrão é **false**. |
| [System::String](../../system/string/) [get_SlideNumberFormat](./get_slidenumberformat/)() | Obtém a string de formato usada para cabeçalhos de número de slide na saída Markdown. O formato deve incluir o placeholder \"{0}\", que será substituído pelo índice do slide durante a exportação. Exemplo: \"# Slide {0}\" produzirá \"# Slide 1\", \"# Slide 2\", etc. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Leia [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hashing de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
|  [MarkdownSaveOptions](./markdownsaveoptions/)() | Construtor. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BasePath](./set_basepath/)([System::String](../../system/string/)) | Especifica o caminho base onde o documento com recursos será salvo. O padrão é o diretório atual da aplicação. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Define a fonte usada caso a fonte de origem não seja encontrada. Escreve [System::String](../../system/string/). |
| void [set_ExportType](./set_exporttype/)([MarkdownExportType](../markdownexporttype/)) | Especifica a especificação markdown para converter a apresentação. O padrão é **TextOnly**. |
| void [set_Flavor](./set_flavor/)([Aspose::Slides::Export::Flavor](../flavor/)) | Especifica a especificação markdown para converter a apresentação. O padrão é **Multi-markdown**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Define o estilo visual do gradiente. Escreve [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_HandleRepeatedSpaces](./set_handlerepeatedspaces/)([Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/)) | Especifica como caracteres de espaço regulares repetidos devem ser tratados durante a exportação Markdown. |
| void [set_ImagesSaveFolderName](./set_imagessavefoldername/)([System::String](../../system/string/)) | Especifica o nome da pasta para salvar imagens. O padrão é **[Images](../../aspose.slides/images/)**. |
| void [set_NewLineType](./set_newlinetype/)([Aspose::Slides::Export::NewLineType](../newlinetype/)) | Especifica se o documento gerado deve ter novas linhas \r(Macintosh) de \n(Unix) ou \r\n(Windows). O padrão é **Unix**. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Representa um objeto de callback para salvar atualizações de progresso em porcentagem. Veja [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RemoveEmptyLines](./set_removeemptylines/)(**bool**) | Se definido como **true**, remove linhas vazias ou contendo apenas espaços em branco da saída final em Markdown. O padrão é **false**. |
| void [set_ShowComments](./set_showcomments/)(**bool**) | Especifica se o documento gerado deve exibir comentários ou não. O padrão é **false**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é **false**. |
| void [set_ShowSlideNumber](./set_showslidenumber/)(**bool**) | Especifica se o documento gerado deve mostrar número de cada slide ou não. O padrão é **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Especifica se deve ignorar hyperlinks com chamadas JavaScript ao salvar a apresentação. Escreva **bool**. O valor padrão é **false**. |
| void [set_SlideNumberFormat](./set_slidenumberformat/)([System::String](../../system/string/)) | Define a string de formato usada para cabeçalhos de número de slide na saída Markdown. O formato deve incluir o placeholder \"{0}\", que será substituído pelo índice do slide durante a exportação. Exemplo: \"# Slide {0}\" produzirá \"# Slide 1\", \"# Slide 2\", etc. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Escreva [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento do modelo como um ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Typedefs

| Typedef | Descrição |
| --- | --- |
| [MarkdownImageSavingHandler](./markdownimagesavinghandler/) | Invocado para cada imagem não-SVG (bitmap ou metafile) durante a exportação Markdown. Retorne **true** para usar o *link* especificado, ou **false** para aplicar a lógica padrão de salvamento. |
| [MarkdownSvgImageSavingHandler](./markdownsvgimagesavinghandler/) | Invocado para cada imagem SVG durante a exportação Markdown. Retorne **true** para usar o *link* especificado, ou **false** para aplicar a lógica padrão de salvamento. |

## Observações

Exemplo:
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

## Veja Também

* Classe [SaveOptions](../saveoptions/)
* Namespace [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)