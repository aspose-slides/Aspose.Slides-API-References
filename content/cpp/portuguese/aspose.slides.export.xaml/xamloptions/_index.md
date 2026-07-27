---
title: XamlOptions
second_title: Referência da API Aspose.Slides para C++
description: Opções que controlam como um documento XAML é salvo.
type: docs
weight: 27
url: /pt/aspose.slides.export.xaml/xamloptions/
---
## XamlOptions classe

Options that control how a XAML document is saved.

```cpp
class XamlOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::Xaml::IXamlOptions
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../../aspose.slides.export/saveoptions/get_defaultregularfont/)() override | Retorna a fonte usada caso a fonte de origem não seja encontrada. Lê [System::String](../../system/string/). |
| **bool** [get_ExportHiddenSlides](./get_exporthiddenslides/)() override | Determina se slides ocultos serão exportados. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../../aspose.slides.export/saveoptions/get_gradientstyle/)() override | Retorna o estilo visual do gradiente. Leia [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IXamlOutputSaver](../ixamloutputsaver/)\> [get_OutputSaver](./get_outputsaver/)() override | Representa uma implementação da interface IOutputSaver. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../../aspose.slides.export/saveoptions/get_progresscallback/)() override | Representa um objeto de retorno de chamada para salvar atualizações de progresso em porcentagem. Veja [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/get_skipjavascriptlinks/)() override | Especifica se deve pular hyperlinks com chamadas JavaScript ao salvar a apresentação. Leia **bool**. O valor padrão é **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../../aspose.slides.export/saveoptions/get_warningcallback/)() override | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Leia [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogia ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Habilita hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogia à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogia ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogia ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Habilita clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas internas de dados. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e habilita a construção de cópia em subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e habilita a construção de cópia em subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
|  [SaveOptions](../../aspose.slides.export/saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../../aspose.slides.export/saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Define a fonte usada caso a fonte de origem não seja encontrada. Escreve [System::String](../../system/string/). |
| void [set_ExportHiddenSlides](./set_exporthiddenslides/)(**bool**) override | Determina se slides ocultos serão exportados. |
| void [set_GradientStyle](../../aspose.slides.export/saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Define o estilo visual do gradiente. Escreve [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_OutputSaver](./set_outputsaver/)([System::SharedPtr](../../system/sharedptr/)\<[IXamlOutputSaver](../ixamloutputsaver/)\>) override | Representa uma implementação da interface IOutputSaver. |
| void [set_ProgressCallback](../../aspose.slides.export/saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Representa um objeto de retorno de chamada para salvar atualizações de progresso em porcentagem. Veja [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/set_skipjavascriptlinks/)(**bool**) override | Especifica se deve pular hyperlinks com chamadas JavaScript ao salvar a apresentação. Escreve **bool**. O valor padrão é **false**. |
| void [set_WarningCallback](../../aspose.slides.export/saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Retorna ou define um objeto que recebe avisos e decide se o processo de carregamento continuará ou será abortado. Escreve [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogia ao método C# [Object.ToString()](../../system/object/tostring/). Habilita a conversão de objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
|  [XamlOptions](./xamloptions/)() | Cria a instância [XamlOptions](./). |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas internas de dados. |

## Observações

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```

## Ver também

* Classe [SaveOptions](../../aspose.slides.export/saveoptions/)
* Classe [IXamlOptions](../ixamloptions/)
* Namespace [Aspose::Slides::Export::Xaml](../)
* Biblioteca [Aspose.Slides](../../)