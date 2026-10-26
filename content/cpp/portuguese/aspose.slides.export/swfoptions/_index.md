---
title: SwfOptions
second_title: Referência da API Aspose.Slides para C++
description: Fornece opções que controlam como uma apresentação é salva no formato Swf.
type: docs
weight: 742
url: /pt/aspose.slides.export/swfoptions/
---
## SwfOptions classe

Fornece opções que controlam como uma apresentação é salva no formato Swf.

```cpp
class SwfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISwfOptions
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| **bool** [get_Compressed](./get_compressed/)() override | Especifica se o documento SWF gerado deve ser compactado ou não. O padrão é **true**. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Retorna a fonte usada caso a fonte de origem não seja encontrada. Lê [System::String](../../system/string/). |
| **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() override | Habilita/Desabilita o menu de contexto. O padrão é true. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Retorna o estilo visual do gradiente. Lê [GradientStyle](../../aspose.slides/gradientstyle/). |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Especifica a qualidade das imagens JPEG. O padrão é 95. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() override | Imagem que será exibida como logotipo no canto superior direito do visualizador. A imagem deve ser PNG de 32x64 pixels, caso contrário o logotipo pode ser exibido incorretamente. |
| [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() override | Obtém o endereço de hyperlink completo para um logotipo. Tem efeito apenas se um [set_LogoImageBytes()](./set_logoimagebytes/) for especificado. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Representa um objeto de callback para salvar atualizações de progresso em percentual. Veja [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowBottomPane](./get_showbottompane/)() override | Exibe/oculta o painel inferior. Pode ser sobrescrito em flashvars. O padrão é true. |
| **bool** [get_ShowFullScreen](./get_showfullscreen/)() override | Exibe/oculta o botão de tela cheia. Pode ser sobrescrito em flashvars. O padrão é true. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é **false**. |
| **bool** [get_ShowLeftPane](./get_showleftpane/)() override | Exibe/oculta o painel esquerdo. Pode ser sobrescrito em flashvars. O padrão é true. |
| **bool** [get_ShowPageBorder](./get_showpageborder/)() override | Especifica se a borda ao redor das páginas deve ser exibida. O padrão é true. |
| **bool** [get_ShowPageStepper](./get_showpagestepper/)() override | Exibe/oculta o controlador de páginas. Pode ser sobrescrito em flashvars. O padrão é true. |
| **bool** [get_ShowSearch](./get_showsearch/)() override | Exibe/oculta a seção de pesquisa. Pode ser sobrescrito em flashvars. O padrão é true. |
| **bool** [get_ShowTopPane](./get_showtoppane/)() override | Exibe/oculta todo o painel superior. Pode ser sobrescrito em flashvars. O padrão é true. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Especifica se deve pular hyperlinks com chamadas JavaScript ao salvar a apresentação. Leia **bool**. O valor padrão é **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Obtém o modo em que os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../islideslayoutoptions/). Esta propriedade não suporta atribuição de objetos do tipo [HandoutLayoutingOptions](../handoutlayoutingoptions/). |
| **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() override | Inicia com o painel esquerdo aberto. Pode ser sobrescrito em flashvars. O padrão é false. |
| **bool** [get_ViewerIncluded](./get_viewerincluded/)() override | Especifica se o documento SWF gerado deve incluir o visualizador de documentos integrado ou não. O padrão é **true**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Leia [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita o hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o travamento da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita a clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_Compressed](./set_compressed/)(**bool**) override | Especifica se o documento SWF gerado deve ser compactado ou não. O padrão é **true**. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Define a fonte usada caso a fonte de origem não seja encontrada. Grava [System::String](../../system/string/). |
| void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) override | Habilita/Desabilita o menu de contexto. O padrão é true. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Define o estilo visual do gradiente. Grava [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Especifica a qualidade das imagens JPEG. O padrão é 95. |
| void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Imagem que será exibida como logotipo no canto superior direito do visualizador. A imagem deve ser PNG de 32x64 pixels, caso contrário o logotipo pode ser exibido incorretamente. |
| void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) override | Define o endereço de hyperlink completo para um logotipo. Tem efeito apenas se um [set_LogoImageBytes()](./set_logoimagebytes/) for especificado. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Representa um objeto de callback para salvar atualizações de progresso em percentual. Veja [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowBottomPane](./set_showbottompane/)(**bool**) override | Exibe/oculta o painel inferior. Pode ser sobrescrito em flashvars. O padrão é true. |
| void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) override | Exibe/oculta o botão de tela cheia. Pode ser sobrescrito em flashvars. O padrão é true. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é **false**. |
| void [set_ShowLeftPane](./set_showleftpane/)(**bool**) override | Exibe/oculta o painel esquerdo. Pode ser sobrescrito em flashvars. O padrão é true. |
| void [set_ShowPageBorder](./set_showpageborder/)(**bool**) override | Especifica se a borda ao redor das páginas deve ser exibida. O padrão é true. |
| void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) override | Exibe/oculta o controlador de páginas. Pode ser sobrescrito em flashvars. O padrão é true. |
| void [set_ShowSearch](./set_showsearch/)(**bool**) override | Exibe/oculta a seção de pesquisa. Pode ser sobrescrito em flashvars. O padrão é true. |
| void [set_ShowTopPane](./set_showtoppane/)(**bool**) override | Exibe/oculta todo o painel superior. Pode ser sobrescrito em flashvars. O padrão é true. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Especifica se deve pular hyperlinks com chamadas JavaScript ao salvar a apresentação. Grave **bool**. O valor padrão é **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Define o modo em que os slides são posicionados na página ao exportar uma apresentação [ISlidesLayoutOptions](../islideslayoutoptions/). Esta propriedade não suporta atribuição de objetos do tipo [HandoutLayoutingOptions](../handoutlayoutingoptions/). |
| void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) override | Inicia com o painel esquerdo aberto. Pode ser sobrescrito em flashvars. O padrão é false. |
| void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) override | Especifica se o documento SWF gerado deve incluir o visualizador de documentos integrado ou não. O padrão é **true**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Grave [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
|  [SwfOptions](./swfoptions/)() | Construtor padrão. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Observações

O exemplo a seguir mostra como converter PowerPoint para SWF Flash. 
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

## Veja Também

* Classe [SaveOptions](../saveoptions/)
* Classe [ISwfOptions](../iswfoptions/)
* Namespace [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)