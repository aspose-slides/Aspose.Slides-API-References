---
title: ISwfOptions
second_title: Aspose.Slides para C++ Referência da API
description: Fornece opções que controlam como uma apresentação é salva no formato SWF.
type: docs
weight: 469
url: /pt/aspose.slides.export/iswfoptions/
---
## ISwfOptions classe

Fornece opções que controlam como uma apresentação é salva no formato SWF.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual **bool** [get_Compressed](./get_compressed/)() | Especifica se o documento SWF gerado deve ser compactado ou não. O padrão é **true**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Retorna a fonte usada caso a fonte de origem não seja encontrada. Lê [System::String](../../system/string/). |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | Habilita/desabilita o menu de contexto. O padrão é true. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Retorna o estilo visual do gradiente. Lê [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Especifica a qualidade das imagens JPEG.\n\n O padrão é 95. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | Imagem que será exibida como logotipo no canto superior direito do visualizador.\n\n A imagem deve ser PNG de 32x64 pixels, caso contrário o logotipo pode ser exibido incorretamente. |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | Obtém o endereço de hiperlink completo para um logotipo. Tem efeito somente se um [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) for especificado. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Representa um objeto de callback para salvar atualizações de progresso em porcentagem. Veja [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | Exibir/ocultar o painel inferior. Pode ser sobrescrito em flashvars. O padrão é true. |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | Exibir/ocultar o botão de tela cheia. Pode ser sobrescrito em flashvars. O padrão é true. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é **false**. |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | Exibir/ocultar o painel esquerdo. Pode ser sobrescrito em flashvars. O padrão é true. |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | Especifica se a borda ao redor das páginas deve ser mostrada. O padrão é true. |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | Exibir/ocultar o seletor de página. Pode ser sobrescrito em flashvars. O padrão é true. |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | Exibir/ocultar a seção de busca. Pode ser sobrescrito em flashvars. O padrão é true. |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | Exibir/ocultar todo o painel superior. Pode ser sobrescrito em flashvars. O padrão é true. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Especifica se deve pular hiperlinks com chamadas JavaScript ao salvar a apresentação. Lê **bool**. O valor padrão é **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Obtém o modo em que os slides são colocados na página ao exportar uma apresentação [ISlidesLayoutOptions](../islideslayoutoptions/). Esta propriedade não suporta atribuição de objetos do tipo **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)**. |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | Iniciar com o painel esquerdo aberto. Pode ser sobrescrito em flashvars. O padrão é false. |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | Especifica se o documento SWF gerado deve incluir o visualizador de documentos integrado ou não. O padrão é **true**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Retorna um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Lê [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico do método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico do operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite copiar construindo subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite copiar construindo subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | Especifica se o documento SWF gerado deve ser compactado ou não. O padrão é **true**. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Define a fonte usada caso a fonte de origem não seja encontrada. Grava [System::String](../../system/string/). |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | Habilita/desabilita o menu de contexto. O padrão é true. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Define o estilo visual do gradiente. Grava [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Especifica a qualidade das imagens JPEG.\n\n O padrão é 95. |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Imagem que será exibida como logotipo no canto superior direito do visualizador.\n\n A imagem deve ser PNG de 32x64 pixels, caso contrário o logotipo pode ser exibido incorretamente. |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | Define o endereço de hiperlink completo para um logotipo. Tem efeito somente se um [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) for especificado. |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Representa um objeto de callback para salvar atualizações de progresso em porcentagem. Veja [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | Exibir/ocultar o painel inferior. Pode ser sobrescrito em flashvars. O padrão é true. |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | Exibir/ocultar o botão de tela cheia. Pode ser sobrescrito em flashvars. O padrão é true. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Especifica se o documento gerado deve incluir slides ocultos ou não. O padrão é **false**. |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | Exibir/ocultar o painel esquerdo. Pode ser sobrescrito em flashvars. O padrão é true. |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | Especifica se a borda ao redor das páginas deve ser mostrada. O padrão é true. |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | Exibir/ocultar o seletor de página. Pode ser sobrescrito em flashvars. O padrão é true. |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | Exibir/ocultar a seção de busca. Pode ser sobrescrito em flashvars. O padrão é true. |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | Exibir/ocultar todo o painel superior. Pode ser sobrescrito em flashvars. O padrão é true. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Especifica se deve pular hiperlinks com chamadas JavaScript ao salvar a apresentação. Grava **bool**. O valor padrão é **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Define o modo em que os slides são colocados na página ao exportar uma apresentação [ISlidesLayoutOptions](../islideslayoutoptions/). Esta propriedade não suporta atribuição de objetos do tipo **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)**. |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | Iniciar com o painel esquerdo aberto. Pode ser sobrescrito em flashvars. O padrão é false. |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | Especifica se o documento SWF gerado deve incluir o visualizador de documentos integrado ou não. O padrão é **true**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Grava [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico do método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa o construto C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |
## Veja Também

* Classe [ISaveOptions](../isaveoptions/)
* Namespace [Aspose::Slides::Export](../)
* Biblioteca [Aspose.Slides](../../)