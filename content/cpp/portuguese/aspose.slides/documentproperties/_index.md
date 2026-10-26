---
title: DocumentProperties
second_title: Aspose.Slides para C++ Referência da API
description: Representa as propriedades de uma apresentação.
type: docs
weight: 794
url: /pt/aspose.slides/documentproperties/
---
## DocumentProperties classe

Representa as propriedades de uma apresentação.

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## Métodos

| Método | Descrição |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | Apaga e define valores padrão para todas as propriedades integradas. |
| void [ClearCustomProperties](./clearcustomproperties/)() override | Remove todas as propriedades personalizadas. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | Clona o objeto atual. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | Clona o objeto atual. |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | Verifica a presença de uma propriedade personalizada com um nome especificado. |
|  [DocumentProperties](./documentproperties/)() | Inicializa nova instância da classe [DocumentProperties](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | Retorna o modelo de um aplicativo. Leia [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | Retorna a versão do aplicativo. Somente leitura [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | Retorna o autor de uma apresentação. Leia [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | Retorna a categoria de uma apresentação. Leia [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | Retorna os comentários de uma apresentação. Leia [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | Retorna a propriedade da empresa. Leia [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | Retorna o status de conteúdo de uma apresentação. Leia [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Retorna o tipo de conteúdo de uma apresentação. Leia [System::String](../../system/string/). |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | Retorna o número de propriedades personalizadas realmente contidas em uma coleção. Somente leitura **int32_t**. |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | Retorna a data em que a apresentação foi criada. Os valores estão em UTC. Leia [System::DateTime](../../system/datetime/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | Indica o agrupamento de partes do documento e o número de partes em cada grupo. Somente leitura [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | Retorna o número de slides ocultos em um documento de apresentação. Somente leitura **int32_t**. |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | Retorna a propriedade HyperlinkBase do documento. Leia [System::String](../../system/string/). |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | Especifica que um ou mais hyperlinks nesta parte foram atualizados exclusivamente nesta parte por um produtor. O próximo produtor que abrir este documento deverá atualizar os relacionamentos de hyperlink com os novos hyperlinks especificados nesta parte. Leia **bool**. |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | Retorna as palavras-chave de uma apresentação. Leia [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | Retorna a data em que a apresentação foi impressa pela última vez. Leia [System::DateTime](../../system/datetime/). |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | Retorna o nome da última pessoa que modificou uma apresentação. Leia [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | Retorna a data em que a apresentação foi modificada pela última vez. Os valores estão em UTC. Somente leitura no caso de [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (porque será atualizado internamente durante o processo de gravação do objeto [IPresentation](../ipresentation/)). Pode ser alterado via instância [DocumentProperties](./) retornada pelo método [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Consulte o exemplo no resumo do método [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | Indica se os hyperlinks em um documento estão atualizados. Defina este elemento como **true** para indicar que os hyperlinks estão atualizados. Defina como **false** para indicar que os hyperlinks estão desatualizados. Leia **bool**. |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | Retorna a propriedade do gerente. Leia [System::String](../../system/string/). |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | Retorna o número total de clipes de áudio ou vídeo presentes no documento. Somente leitura **int32_t**. |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | Retorna o nome do aplicativo. Leia [System::String](../../system/string/). |
| **int32_t** [get_Notes](./get_notes/)() override | Retorna o número de slides em uma apresentação que contêm anotações. Somente leitura **int32_t**. |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | Retorna o número total de parágrafos encontrados em um documento, se aplicável. Somente leitura **int32_t**. |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | Retorna o formato pretendido de uma apresentação. Leia [System::String](../../system/string/). |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | Retorna o número de revisão da apresentação. Leia **int32_t**. |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | Indica o modo de exibição da miniatura do documento. Defina este elemento como **true** para habilitar o redimensionamento da miniatura do documento ao display. Defina como **false** para habilitar o corte da miniatura para mostrar apenas as seções que cabem no display. Leia **bool**. |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | Determina se a apresentação é compartilhada entre várias pessoas. Leia **bool**. |
| **int32_t** [get_Slides](./get_slides/)() override | Retorna o número total de slides em um documento de apresentação. Somente leitura **int32_t**. |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | Retorna o assunto de uma apresentação. Leia [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | Retorna o título de uma apresentação. Leia [System::String](../../system/string/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | Especifica o título de cada parte do documento. Essas partes não são partes do documento, mas representações conceituais de seções do documento. Somente leitura [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | Tempo total de edição de uma apresentação. Leia [System::TimeSpan](../../system/timespan/). |
| **int32_t** [get_Words](./get_words/)() override | Retorna o número total de palavras contidas em um documento. Somente leitura **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referências associada ao objeto. |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | Retorna um nome de propriedade personalizada no índice especificado. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | Obtém um valor booleano nomeado das propriedades personalizadas. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | Obtém um valor inteiro nomeado das propriedades personalizadas. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | Obtém um valor DateTime nomeado das propriedades personalizadas. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | Obtém um valor string nomeado das propriedades personalizadas. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | Obtém um valor float nomeado das propriedades personalizadas. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | Obtém um valor double nomeado das propriedades personalizadas. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | Obtém um array de rótulos de sensibilidade das propriedades personalizadas do documento (Metadata do Microsoft Information Protection SDK). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo atual do objeto. Analogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | Retorna a propriedade personalizada associada a um nome especificado. Leia [System::Object](../../system/object/). |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Define a propriedade personalizada associada a um nome especificado. Escreva [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite copiar construindo subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite copiar construindo subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto do tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | Remove uma propriedade personalizada associada a um nome especificado. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referências compartilhadas pelo valor especificado. |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | Define o modelo de um aplicativo. Escreva [System::String](../../system/string/). |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | Define o autor de uma apresentação. Escreva [System::String](../../system/string/). |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | Define a categoria de uma apresentação. Escreva [System::String](../../system/string/). |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | Define os comentários de uma apresentação. Escreva [System::String](../../system/string/). |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | Define a propriedade da empresa. Escreva [System::String](../../system/string/). |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | Define o status de conteúdo de uma apresentação. Escreva [System::String](../../system/string/). |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | Define o tipo de conteúdo de uma apresentação. Escreva [System::String](../../system/string/). |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | Retorna a data em que a apresentação foi criada. Os valores estão em UTC. Escreva [System::DateTime](../../system/datetime/). |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | Define a propriedade HyperlinkBase do documento. Escreva [System::String](../../system/string/). |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | Especifica que um ou mais hyperlinks nesta parte foram atualizados exclusivamente nesta parte por um produtor. O próximo produtor que abrir este documento deverá atualizar os relacionamentos de hyperlink com os novos hyperlinks especificados nesta parte. Escreva **bool**. |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | Define as palavras-chave de uma apresentação. Escreva [System::String](../../system/string/). |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | Retorna a data em que a apresentação foi impressa pela última vez. Escreva [System::DateTime](../../system/datetime/). |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | Define o nome da última pessoa que modificou uma apresentação. Escreva [System::String](../../system/string/). |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | Retorna a data em que a apresentação foi modificada pela última vez. Os valores estão em UTC. Somente leitura no caso de [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (porque será atualizado internamente durante o processo de gravação do objeto [IPresentation](../ipresentation/)). Pode ser alterado via instância [DocumentProperties](./) retornada pelo método [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Consulte o exemplo no resumo do método [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | Indica se os hyperlinks em um documento estão atualizados. Defina este elemento como **true** para indicar que os hyperlinks estão atualizados. Defina como **false** para indicar que os hyperlinks estão desatualizados. Escreva **bool**. |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | Define a propriedade do gerente. Escreva [System::String](../../system/string/). |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | Define o nome do aplicativo. Escreva [System::String](../../system/string/). |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | Define o formato pretendido de uma apresentação. Escreva [System::String](../../system/string/). |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | Define o número de revisão da apresentação. Escreva **int32_t**. |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | Indica o modo de exibição da miniatura do documento. Defina este elemento como **true** para permitir o redimensionamento da miniatura ao display. Defina como **false** para permitir o corte da miniatura mostrando apenas as seções que cabem no display. Escreva **bool**. |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | Determina se a apresentação é compartilhada entre várias pessoas. Escreva **bool**. |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | Define o assunto de uma apresentação. Escreva [System::String](../../system/string/). |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | Define o título de uma apresentação. Escreva [System::String](../../system/string/). |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | Tempo total de edição de uma apresentação. Escreva [System::TimeSpan](../../system/timespan/). |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | Define uma propriedade personalizada booleana nomeada. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | Define uma propriedade personalizada inteira nomeada. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | Define uma propriedade personalizada DateTime nomeada. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Define uma propriedade personalizada string nomeada. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | Define uma propriedade personalizada float nomeada. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | Define uma propriedade personalizada double nomeada. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referências compartilhadas. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referências compartilhadas. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referências compartilhadas. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referências fracas. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referências fracas. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Observações

O exemplo a seguir mostra como acessar as Propriedades incorporadas do PowerPoint [Presentation](../presentation/).
```cpp
// Instancie a classe Presentation que representa a apresentação
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
O exemplo a seguir mostra como modificar as Propriedades incorporadas do PowerPoint [Presentation](../presentation/).
```cpp
// Instancie a classe Presentation que representa a Presentation
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// Crie uma referência ao objeto IDocumentProperties associado à Presentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// Defina as propriedades incorporadas
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// Salve sua apresentação em um arquivo
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## Veja Também

* Classe [IDocumentProperties](../idocumentproperties/)
* Classe [IGenericCloneable](../igenericcloneable/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)